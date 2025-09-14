# Tanakaya サイト（仮）

- 場所: `tanakaya/`
- トップページ: `index.html`
- スタイル: `assets/css/style.css`
- スクリプト: `assets/js/main.js`
- 画像: `assets/img/`（`placeholder.svg`は差し替え用）

## 差し替えポイント

- 会社名・英字表記・電話番号・住所・営業時間・定休日
- ヒーロー・商品・ギャラリー等の写真（`assets/img/`に追加し、`index.html`のパスを差し替え）
- 卸の最小ロット、価格、対応エリア、納品方法
- 小売の受付時間（電話）と受け取り時間（9:30–12:30 で実装）
- メールアドレス（卸向け）

## 参考

- 写真は横長で`2000x1200`程度のJPGが扱いやすいです。
- 画像タグに`loading="lazy"`と`decoding="async"`を付与済みです。
- スマホ対応済み。768–920pxのブレークポイントで最適化しています。

## 今後追加できるもの

- 実写真の差し替えと色の微調整
- Google マップ埋め込み
- 価格表・商品規格PDFのダウンロード
- 競合調査を踏まえたテキスト強化（ネット参照許可があれば対応）

## 画像の配置（現状の参照ファイル名）

- 特長1 仕込み: `assets/img/feature-prep-1920x1440.jpg`
- 特長2 衛生: `assets/img/feature-hygiene-640x427.jpg`
- 特長3 供給: `assets/img/feature-supply-1920x1280.jpg`
- 商品（仮・共通）: `assets/img/product-placeholder-640x431.jpg`
- 会社外観: `assets/img/exterior-700x386.jpg`

これらが未配置でも、`onerror`で`placeholder.svg`にフォールバックするため表示は保たれます。
