---
title: "テスト記事"
description: "Wikiコンテンツの同期処理を確認するためのテスト記事です。"
---

# テスト記事
v-1.0.0

これは **wiki-content** リポジトリからR2への同期処理を確認するためのテスト記事です。

## 目的

このファイルを `main` ブランチへ追加して、次の処理が正常に動作することを確認します。

```text
GitHub
  ↓ push
Webhook
  ↓
Queue
  ↓
Sync Worker
  ↓
R2