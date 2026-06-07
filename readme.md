# カレンダーアプリ

GitHub Pages で公開して、iPhone のホーム画面からアプリのように使えるカレンダーです。

## 入っているファイル

- `index.html`：カレンダー本体
- `manifest.json`：PWA設定
- `sw.js`：オフライン表示用
- `icon-192.png`：iPhoneホーム画面用アイコン
- `icon-512.png`：PWA用アイコン
- `icon-180.png`：Apple用補助アイコン
- `favicon.ico`：ブラウザ用アイコン

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作る
2. このフォルダ内のファイルをすべてアップロードする
3. GitHubの `Settings` を開く
4. 左側の `Pages` を開く
5. `Deploy from a branch` を選ぶ
6. `main` / `root` を選んで `Save`
7. 数分後に表示されるURLをSafariで開く

## iPhoneのホーム画面に追加

1. iPhoneのSafariでGitHub PagesのURLを開く
2. 共有ボタンを押す
3. 「ホーム画面に追加」を押す
4. 名前を確認して「追加」を押す

これで、ホーム画面からカレンダーアプリのように起動できます。
