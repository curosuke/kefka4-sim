# AGENTS.md

このリポジトリで作業するときの、ブランチ名とコミットメッセージの基本ルールです。

## ブランチ名

- `codex/` は使わず、一般的なプレフィックスを使う
- 変更の種類が一目で分かる名前にする
- 英小文字、数字、`-` を中心にする
- 長すぎない名前にする

### よく使う例

- `feature/start-screen-localization`
- `feature/role-hint-panel`
- `fix/debuff-layout`
- `fix/alag-debuff-position`
- `chore/update-docs`
- `refactor/ghost-movement`

### 付け方の目安

- 新機能追加: `feature/...`
- 不具合修正: `fix/...`
- 内部整理や置き換え: `refactor/...`
- ドキュメント更新: `docs/...`
- 雑務や設定変更: `chore/...`

## コミットメッセージ

- 1行で、変更内容が分かるように書く
- 命令形か、完了形のどちらかに揃える
- 1コミット1意図を基本にする
- 必要なら本文で補足する

### よく使う例

- `Add start screen language selection`
- `Fix debuff panel position`
- `Refactor ghost movement timing`
- `Update PR body formatting`
- `Document branch naming rules`

### 形式の目安

- 先頭は動詞から始めると読みやすい
- 変更が小さいなら短くてよい
- 変更理由が重要なら本文を付ける

## 補足

- PR 名もコミットと同じく、内容が伝わる名前にする
- PR タイトルと本文は日本語で書く
- 英語に統一したい場合は、ブランチ名とコミットメッセージを英語で揃える
- 迷ったら `feature/...` / `fix/...` のどちらかに寄せる
