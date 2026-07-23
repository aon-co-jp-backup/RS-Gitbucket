# 開発方針・開発環境ルール(RS-Gitbucket)

作業ドライブは`F:\runo`。この節は
[`open-raid-z`](https://github.com/aon-co-jp/open-raid-z)の`CLAUDE.md`を
正本とし、各プロジェクトへコピーして同期する方針に準じる。
GitHubリポジトリ: [aon-co-jp/RS-Gitbucket](https://github.com/aon-co-jp/RS-Gitbucket)。

## 現状(2026-07-23時点)

**コード未着手**。リポジトリ自体は作成済みだがコミットが1件も無い
(空のプレースホルダー)。

## このプロジェクトの想定役割

[GitBucket](https://github.com/gitbucket/gitbucket)(Scala製の
セルフホスト型Gitプラットフォーム、GitHub風のWeb UI+プラグイン機構)
相当の機能をRustで実装する構想。**着手前に必ず`RS-Git`(このエコシステム
既存のGit forge実装、OTPログイン・アクセス制御パターン先行実装済み)を
調査し、役割分担・重複範囲を整理してから設計すること**——確認せず
重複実装から始めない。

## 復旧ポイント(どのリポジトリからでも作業を再開できるように)

エコシステム全体の開発方針・運用ルール・全プロジェクトの現況・直近の
セッションチェックポイントは
[`open-raid-z`の`CLAUDE.md`](https://github.com/aon-co-jp/open-raid-z/blob/main/CLAUDE.md)
を正本として一元管理している。このリポジトリから作業を再開する場合も、
まず`open-raid-z/CLAUDE.md`のHANDOFF節を読んでから着手すること。

## 関連プロジェクト

- [open-raid-z](https://github.com/aon-co-jp/open-raid-z) — 開発ルールの正本。
- [RS-Git](https://github.com/aon-co-jp/RS-Git) — 役割重複の可能性がある先行実装、着手前に必読。

## HANDOFF

- **2026-07-23 README/CLAUDE.md新規作成**: リポジトリが空(コミット0件)
  だったため、ドキュメント整備の一環として最小限のプレースホルダーを
  作成。実装自体はまだ着手していない。
