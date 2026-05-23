# 紫煙観測所🥀

Googleスプレッドシートの数値を読み込んで表示する、1ページ完結の公開カウンターサイトです。

## スプレッドシートの推奨列

1行目に下記を入れてください。

| title | count | message | updated |
|---|---:|---|---|
| 紫煙観測所🥀 | 0 | 静かな夜 | 23:41 |

## Vercelで公開する方法

1. このフォルダの `index.html` をGitHubにアップロード
2. Vercelで「New Project」
3. GitHubリポジトリを選択
4. Framework Presetは「Other」
5. Deploy

## 更新方法

Googleスプレッドシートの `count` を変更すると、サイト側は約30秒ごとに自動取得します。
すぐ見たい場合はページ内の「再観測」ボタンを押してください。
