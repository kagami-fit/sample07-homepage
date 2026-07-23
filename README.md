# sample07-homepage

ホームページ作成スキルのサンプル歯科クリニックサイトです。

## 確認方法

`index.html` をブラウザで開くとトップページを確認できます。

```bash
open index.html
```

ローカルサーバーで確認する場合は次のコマンドを使います。

```bash
python3 -m http.server 8080
```

その後、`http://localhost:8080/` を開きます。

## 主な構成

- `index.html`：トップページ
- `service.html` / `about.html` / `faq.html` / `contact.html` / `privacy.html`：固定ページ
- `assets/css/_shared.css`：固定ページ共通CSS
- `src/`：画像素材
- `blog/`：初期ブログ記事の下書き
- `ABOUT.md`：このフォルダの説明
- `README_公開手順.md`：公開と更新の手順
