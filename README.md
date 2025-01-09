# ActiveReportsJS-Invoice-Sample
JavaScript帳票開発ライブラリ「[ActiveReportsJS（アクティブレポートJS）](https://developer.mescius.jp/activereportsjs)」で作成した請求書のサンプルです。
請求書のレポートファイル（Invoice_green.rdlx-json）を、HTMLページ（index.html）に埋め込んだActiveReportsJSの帳票ビューワ上で表示します。

<center>
<img title="請求書のイメージ" src="https://devlog.mescius.jp/wp-content/uploads/detail/hatena/20191227104845.png" alt="請求書のイメージ" width="500">
</center>

ソース一式をダウンロードし、Webサーバー（Visual Studio Codeの拡張機能など含む）上で実行すると、ブラウザ上のActiveReportsJSの帳票ビューワに請求書のレポートが表示されます。

※PDFエクスポートは実装しておりません。PDFエクスポートを使用したい場合は、index.html内の「ar-js-pdf.js」への参照のコメントアウトを外してください。
また、日本語の出力を行う場合は、以下を参考にフォントの埋め込み設定も行ってください。
- https://support.mescius.jp/hc/ja/articles/360003943516

<img title="ビューワで請求書を表示" src="https://cdn-ak.f.st-hatena.com/images/fotolife/G/GrapeCity_dev/20200116/20200116161520.png" alt="ビューワで請求書を表示" >
