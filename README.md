# PDFページ抽出ツール

スマートフォン向けのPWAです。PDFをブラウザ内で読み込み、残したいページを選んで新しいPDFとして保存します。

## GitHub Pagesで公開
1. リポジトリのルートに `index.html`、`manifest.webmanifest`、`sw.js` と `icons` フォルダを配置
2. Settings → Pages → Deploy from a branch → `main` / `/(root)` → Save
3. 表示されたURLをAndroid Chromeで開き、メニューから「アプリをインストール」または「ホーム画面に追加」

PDF処理は端末内で行います。PDF.jsとpdf-libの初回読み込みにはインターネット接続が必要です。
