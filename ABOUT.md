# sample07-homepage について

## 一言で言うと

`sample07.zip` から展開した、ホームページ作成スキルのサンプル歯科クリニックサイトです。トップページ、固定ページ、画像素材、ブログ下書きを含む静的ホームページ一式です。

## 何ができるのか

- `index.html` を開いてトップページを確認できます。
- `service.html`、`about.html`、`faq.html`、`contact.html`、`privacy.html` の固定ページを確認できます。
- `src/` の画像を同じファイル名で差し替えると、サイト内の画像を差し替えられます。
- `README_公開手順.md` を見ながら Netlify Drop などで公開できます。
- WordPressへ移す場合は、WordPress移行スキル でテーマ化できます。

## 構成

- `index.html`：トップページ本体
- `service.html` / `about.html` / `faq.html` / `contact.html` / `privacy.html`：固定ページ
- `assets/css/_shared.css`：固定ページ共通のCSS
- `src/`：ロゴ、FV、人物写真、装飾、事例、声などの画像素材
- `blog/`：初期ブログ記事の下書きMarkdown
- `SPEC.md`：サイト構成とページ仕様
- `site-design.md`：デザイン・戦略の設計メモ
- `README_公開手順.md`：公開と更新の手順

## 使い方

ブラウザで次のファイルを開くと確認できます。

```bash
open /Users/hayatokagami/Documents/Codex/sample07-homepage/index.html
```

ローカルサーバーで確認する場合は、次のコマンドを使います。

```bash
cd /Users/hayatokagami/Documents/Codex/sample07-homepage
python3 -m http.server 8080
```

その後、ブラウザで `http://localhost:8080/` を開きます。

## 状態

- ルート一式：稼働中
- `assets/`：稼働中
- `src/`：稼働中
- `blog/`：下書き記事として準備済み
- WordPress移行：未実施
