# Qiita記事連動ファイル

## リポジトリについて
* Qitta記事で利用しているデータやipynbファイルをおいてあります。必要に応じてご利用ください。

## 解説記事
* quantile_regression.ipynb : [分位点回帰（線形モデル）](https://qiita.com/AzukiImo/items/871f23c0e95fa69ba6b7)
* quantile_nonlinear_regression.ipynb : [分位点回帰（非線形モデル）](https://qiita.com/AzukiImo/items/915331f703363cd2b14b)
* visualization_wage_japanmap.ipynb : [japanmapによる可視化](https://qiita.com/AzukiImo/items/c015ce9b40b08ee5a4f4)
* foreign_visitors.ipynb : plotlyによる可視化
* inbound_consumption.ipynb : plotlyによる可視化

## データについて
* data/minimum_wage_2025.csv

### 出典
* 最低賃金のデータは厚生労働省ホームページ[（令和７年度地域別最低賃金の全国一覧）](https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/koyou_roudou/roudoukijun/minimumichiran/index.html)から取得・加工したものを利用しています。
* 訪日外客数データは、[日本政府観光局「JNTO日本の観光統計データ」国籍/目的別 訪日外客数（2004年～2024年）](https://www.jnto.go.jp/statistics/data/visitors-statistics/)(PDF) からファイルを取得。2024年の観光客などの人数を抽出・加工しました。
* 消費単価データは、観光庁[「インバウンド消費動向調査（旧 訪日外国人消費動向調査）『2024年年間集計表』」](https://www.mlit.go.jp/kankocho/tokei_hakusyo/gaikokujinshohidoko.html)から抜粋「居住地（21区分）別　費目別購入率および購入者単価」を加工して作成しました。
