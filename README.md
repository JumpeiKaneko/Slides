# Slides — Jumpei Kaneko

発表用スライドと企画書のサイトです。HTMLとCSS/JSだけで動く静的サイトで、ビルドは要りません。

## 構成

```
index.html            Home(スライド一覧)
slides/               スライド本体(各ファイルが1本のスライド)
  100banch-proposal.html   100BANCH 常設展示企画書
  reunir.html              Reunir
  nihei-1003.html          二瓶さんミーティング「Interference（仮）」
  meetup-1001.html         100BANCH GARAGE Program MEETUP
assets/
  site.css / site.js       Home用
  slide.css / slide.js     スライド用
images/  strip/            画像
```

## リンクの決まり

- Home から各スライドへは移動できます。
- `slides/xxx.html#5` のように `#番号` を付けると、そのページから開きます。
- スライドから Home・一覧へのリンクはありません。スライドのURL(例: `slides/reunir.html`)だけを共有できます。

## GitHub Pages で公開する

1. このフォルダの中身をGitHubのリポジトリにアップロードします(`.nojekyll` も含めます)。
2. リポジトリの Settings → Pages で、Source を「Deploy from a branch」、Branch を `main` / `(root)` にします。
3. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で開きます。スライドは `.../slides/reunir.html` のように共有できます。

ローカルで見るときは `index.html` をブラウザで開くだけで動きます。

## 差し替えが必要な画像

次の画像は元のファイルが見つからなかったため、枠だけを置いています。同じファイル名で `images/` に入れると表示されます。

- `images/reunir-01.jpg` / `images/reunir-02.jpg` (Reunir)
- `images/1.jpg` (二瓶さんミーティング)

## 操作

↑↓ / ←→ / Space / PageUp・PageDown でページ移動、右上のボタンで全画面になります。
