# watashi-studio-apps

「わたしも出てくる」シリーズの**公開ページ**(GitHub Pages: https://nakagawasanchi.github.io/watashi-studio-apps/)。リポジトリはPUBLIC。

## 中身と影響範囲(編集は慎重に)
- `index.html` — シリーズLP
- `privacy.html` — **4アプリ共通のプライバシーポリシー**(App Store審査でURL登録される。アプリ追加時は対象アプリ名・課金有無の記載を実態と一致させること)
- `apps.json` — **各アプリが実行時に取得する**クロスプロモ情報(raw.githubusercontent.com経由)。壊すとアプリ内の「ほかのアプリ」表示に即影響。URLは apps.apple.com のみ(アプリ側でドメイン検証あり)

## デプロイ
`git push` = 即本番反映(GitHub Pages)。push前にdiff確認。静的HTMLのみ・JSなしを維持。

## 表記
シリーズ名「わたしも出てくるシリーズ」、アプリ名は「しりとり」「わたしDJ」「ルーレット」「もちものリスト」。
