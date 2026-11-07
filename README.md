# ハートとクローバーのオセロ

ブラウザーで遊べる、1ファイル構成のオセロゲームです。ビルドや外部ライブラリは不要です。

## GitHub Pagesで公開する

1. このフォルダーをGitHubリポジトリへpushします。
2. リポジトリの **Settings → Pages → Build and deployment → Source** で **GitHub Actions** を選びます。
3. `main` または `master` にpushするか、**Actions → Deploy to GitHub Pages → Run workflow** を実行します。
4. Actionsのデプロイ完了後、`github-pages` environmentに表示されるURLで遊べます。

このworkflowはトップページの `index.html` を公開します。GitHub Pagesの利用可否はリポジトリの公開設定とGitHubプランに従います。
