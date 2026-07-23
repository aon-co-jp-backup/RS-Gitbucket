# RS-Gitbucket

**現状: プレースホルダー(2026-07-23時点でコード未着手)**。
[GitBucket](https://github.com/gitbucket/gitbucket)(Scala製の
セルフホスト型Gitプラットフォーム)相当の機能をRustで実装する構想の
リポジトリ。このエコシステムには既に`RS-Git`(Git forge、OTPログイン・
アクセス制御パターンの先行実装)が存在するため、着手時は`RS-Git`との
役割分担(何がRS-Gitと重複し、何が差分か)を先に整理すること。

## 復旧ポイント(どのリポジトリからでも作業を再開できるように)

エコシステム全体の開発方針・運用ルール・全プロジェクトの現況・直近の
セッションチェックポイントは
[`open-raid-z`の`CLAUDE.md`](https://github.com/aon-co-jp/open-raid-z/blob/main/CLAUDE.md)
を正本として一元管理している。このリポジトリから作業を再開する場合も、
まず`open-raid-z/CLAUDE.md`のHANDOFF節を読んでから着手すること。
