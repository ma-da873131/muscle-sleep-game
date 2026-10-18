# マッスル睡眠妨害

寝落ち寸前のマッチョ男を、30分（実時間で約3分）寝かせない2Dドット絵のギャグアクションゲームです。スマホとPCのブラウザで遊べます。

## 遊び方

- 眠気ゲージが100%になったら寝落ち。30分耐えればクリア
- 画面下の3択から行動を選ぶ（PCは `1` `2` `3` キー）
- 同じ手を続けると「慣れ」で大失敗しやすくなる
- 違うジャンルを続けるとコンボ、寝言のジャンルに合う手は1.5倍
- フィーバーゲージが満タンになるとポーズ連打タイム

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作る（例：`muscle-sleep-game`、Public）
2. このフォルダの `index.html`・`README.md`・`.nojekyll` をアップロードする
3. リポジトリの Settings → Pages を開く
4. Source を「Deploy from a branch」、Branch を `main` と `/ (root)` にして Save
5. 1〜2分後、`https://<ユーザー名>.github.io/muscle-sleep-game/` で遊べる

ビルドは不要です。`index.html` 1ファイルで動きます。
