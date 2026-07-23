# ぞろ屋歯科クリニック ホームページ公開手順

このフォルダには、Netlify Dropで公開できる1ページホームページ一式が入っています。

## 1. 公開する方法

1. `zoroya-site.zip` を解凍します。
2. Netlify Drop（https://app.netlify.com/drop）を開きます。
3. 解凍したフォルダの中身をドラッグしてアップロードします。
4. 表示されたURLを開き、ページを確認します。

## 2. 画像を差し替える方法

画像は `src` フォルダに入っています。

- ロゴ：`src/logo.png`
- メイン画像：`src/fv.jpg`
- 院長・説明画像：`src/profile.jpg`
- 診療イメージ：`src/case-1.jpg` から `src/case-3.jpg`
- 院内・設備・アクセス：`src/facility-1.jpg` から `src/facility-6.jpg`
- 患者さんの声：`src/voice-1.jpg` から `src/voice-3.jpg`

同じファイル名で上書きすると、HTMLを直さずに画像を差し替えられます。

## 3. 予約ボタンをつなぐ方法

`index.html` の中にある `https://example.com/reservation` を、実際の予約URLへ変更します。

使いやすい候補：

- Googleフォーム
- Tally
- Formspree
- 予約システムのURL

電話番号は `000-0000-0000` を正式な番号に変更してください。

## 4. 公開前に差し替えるところ

- 正式住所
- 電話番号
- Web予約URL
- 診療時間
- 休診日
- 対応エリア
- 設備名
- 実際の患者さんの声
- 実際の院内写真・スタッフ写真

## 5. WordPressへ移る目安

次のような運用をしたくなったら、WordPress化を検討してください。

- お知らせを自分で更新したい
- ブログや症例紹介を増やしたい
- 患者さんの声を継続的に追加したい
- 診療メニューごとの詳しいページを作りたい

## 6. Codexで続けて整えるとよいこと

- 正式な住所・時間に合わせたフッター修正
- スマートフォン表示の微調整
- 実写真への差し替え
- Googleフォームや予約システムへの接続
- よくある質問の追加

## 7. SEOとAI検索について

このサイトは公開用の初期ページです。地域名でしっかり見つけてもらうSEOや、AI検索で引用されやすくする設計には、別途の専門的な情報設計・競合調査・構造化データ設計が必要です。

## WordPress固定ページ対応

このフォルダは `ZOROYA:HEADER` / `ZOROYA:MAIN` / `ZOROYA:FOOTER` の目印を入れた状態です。
`index.html` はトップページ、`service.html`、`about.html`、`faq.html`、`contact.html`、`privacy.html` は固定ページとして移行できます。

お問い合わせページには `ZOROYA:CONTACTFORM` の差し込み枠があります。WordPress移行後は、Fluent Formsなどのフォームショートコードに置き換えてください。

ブログ下書きは `blog/` に入っています。WordPressへ移行したあと、内容を確認してから公開してください。

