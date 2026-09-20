# wiki-content

ITに関する知識・技術情報を収録するWikiのコンテンツリポジトリです。

このリポジトリのMarkdownを原稿の正本（source of truth）として管理し、`main` ブランチに取り込まれた記事をWebサイトへ同期します。

## ディレクトリ構成

```text
wiki-content/
├── articles/       # 公開するWiki記事
├── .github/        # Pull Request等の設定
├── CONTRIBUTING.md # 執筆・投稿ガイド
├── LICENSE         # コンテンツのライセンス
└── README.md
```

公開対象の記事は `articles/**/*.md` に配置してください。

## 公開までの流れ

```text
記事を作成・編集
    ↓
Pull Request
    ↓
レビュー
    ↓
main にマージ
    ↓
GitHub Webhook
    ↓
同期処理
    ↓
R2
    ↓
Wikiサイト
```

GitHubは原稿の管理・レビュー・変更履歴を担い、Webサイト側では実行時用のコピーを利用します。

## 執筆について

記事の作成・変更については [CONTRIBUTING.md](CONTRIBUTING.md) を確認してください。

## ライセンス

記事本文は原則として **CC BY-SA 4.0** で公開します。

第三者が権利を持つ文章・画像・その他の素材を使用する場合は、本文とは別に適切なライセンス・出典を確認してください。
