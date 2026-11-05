# 運命の導き・専属伴走サポート LP（jinsoku さん 2本目）

静的な HTML/CSS/JS だけで動きます（ビルド不要）。1本目（魂流開導）と同じ型で、色とグラフを変えたもの。

- 起動：このフォルダで `python3 -m http.server 8000` → http://localhost:8000/
- 公開：フォルダごと Vercel・GitHub Pages・Netlify などに置くだけ。
- プランの料金・URL・文言：`main.js` の `PLANS` を1か所直すと、冒頭の限定料金・期間の比べ・プラン欄・最後の申し込みエリア・下の帯に反映。通常価格を取り消し線で出すときは `regular` に入れる（今は空＝出さない）。
- カウントダウン：`main.js` の `DEADLINE_HOURS`（初めて開いた時から72時間・再読み込みでは戻らない）。
- LINE の感想画像：`img/voices/` に画像を置き、`index.html` の `<figure class="shot">` を足す・消す。
- 特商法：フッターのリンク（https://ummeishuuseish-4uj3w.stores.jp/tokushoho）。
- 色：水彩の水色〜若草色・白・金の細線・藍（`style.css` の `:root` と末尾の「2本目」の節）。背景の水彩と青もみじは、ご依頼の参考画像から切り出し（`img/bg-wash.jpg`・`orn-tl.jpg`・`orn-br.jpg`）。
- グラフ：III 章の棒グラフ（`index.html` の `.graph.bars`。棒の高さは各 `rect` の `y` と `height`）。
- 改行：`budoux.min.js`（Google の BudouX・Apache-2.0）で文節ごとに折り返します。
- 写真：ご支給の画像（ほまれさん2枚・Pexels 5枚）を切り抜いて使用。
