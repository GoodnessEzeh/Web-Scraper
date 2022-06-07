# ウェブスクレイパー

これは、ウェブページから簡単に情報を抽出するもので、コードには https://www.punchng.com への URL が含まれています。

## 始めるにあたって
まずは `npm install` を実行して、必要なパッケージをローカルマシンにインストールし、`package.json` ファイルを生成してください。

## 使用方
このウェブスクレイパーを使用するには、ウェブサイトのURLを取得し、開発者ツールで探している情報、例えばリンク、画像、テキストをターゲットにします。
cheerio.loadを使用してターゲットを設定し、その値を変数に保存します。その後、スクレイピングのアイテムをプッシュする配列を作成し、コードを実行します。

最後に `node index.js > result.txt` を実行し、抽出されたデータをテキストファイルに保存します。