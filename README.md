# preview-roadmap
## 概要と使い方

roadmap.js を用いてロードマップをプレビューしながら生成するツール

全部 clone してローカルで preview-roadmap.html をブラウザで実行すれば動きます。

<br/>
本家の roadmap.js から下記変更を行っています。

* 日付表示を日本語にローカライズ
* 色指定を自分の好みにローカライズ
* ソート用のプレフィックスを利用できるように対応
* 複数の class=roadmap を持った div が存在している時に混在して表示されないよう対応
* roadmap.js が複数回呼ばれても正常に動作するよう対応

## 利用ライブラリ
* [roadmap.js](https://github.com/florentsolt/roadmap.js)
* [bootstrap-datepicker](https://github.com/uxsolutions/bootstrap-datepicker)