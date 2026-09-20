# Articles

このディレクトリ以下にWikiの記事を配置します。

## 配置ルール

公開対象の記事は `articles/**/*.md` に配置してください。

例:

```text
articles/
├── cloudflare/
│   ├── workers.md
│   └── r2.md
├── javascript/
│   └── typescript.md
└── web/
    └── http.md
```

ディレクトリは分野ごとに自由に分けられます。

## Markdown

基本的なMarkdownを使用してください。

```md
# HTTP

HTTPはWebで利用されるアプリケーション層のプロトコルです。

## HTTP/1.1

...

## HTTP/2

...

## 参考資料

- [MDN Web Docs](https://developer.mozilla.org/)
```

サイト側で必要となるフロントマターや追加の記法については、Web側の実装仕様に合わせて定義します。

## ファイル名

ファイル名は内容を識別しやすい英数字・ハイフンを基本としてください。

```text
good-example.md
http.md
cloudflare-workers.md
```

日本語ファイル名も技術的には利用できますが、URLや外部ツールとの互換性を考慮し、原則として英数字・ハイフンを推奨します。
