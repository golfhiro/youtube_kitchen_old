# サービス名：　Youtubeキッチン(仮)
## サービス概要
Youtubeの料理動画で献立を作成するサービス

## メインのターゲットユーザー
- Youtubeの料理動画を参考にして、料理している人</br>
- Youtubeの料理動画で献立を作成したい人</br>

## ユーザーが抱える課題
- 毎日の献立を考えるのがめんどくさくストレスになる</br>
- Youtubeの料理動画で献立を考えたい</br>
- 料理動画を再生リストに保存しているけど、いちいちスクロールしなければならず見づらい</br>
- いつ何を食べたのか覚えることができない

## 解決方法
- Youtubeの料理動画をもとに近日に食べたものと被らないように配慮し、1週間の献立を提案しストレスを減らす</br>
- お気に入りの料理動画があれば再生リストを作成し、再生リスト内でも検索しやすいように探しづらいストレスを解消する

## 実装予定の機能
- 利用者</br>
  - 未登録ユーザー</br>
    - ユーザー登録できる</br>
    - トップページが閲覧できる</br>
    - 料理名,材料の一覧を表示し、動画の一覧の表示、再生ができる</br>
    - フリーワードから料理名,材料の検索ができる</br>
    - 1週だけの献立作成ができる</br>

  - 登録ユーザー</br>
    - ログイン、ログアウトができる</br>
    - 動画の一覧表示には、再生数が多い順から表示できる</br>
    - 気に入った動画は再生リストに保存できる</br>
    - 再生リスト内の検索ができる<br>
    - 作成した献立の履歴が残る<br>
    - 献立が作成できたら、LINEに通知し閲覧できる</br>

- 管理者</br>
  - ユーザーのCRUD</br>

## 今後実装してみたい機能（検討中のもあり）
- 料理人や料理系Youtuberタグを一覧で載せておき、そのタグから料理動画を一覧で表示、再生する</br>
- 似た献立が食べた日と近いに被らないように献立を作成できる</br>
- 再生リスト内の動画には、レシピや材料がメモできる</br>
- おすすめの料理動画あれば、紹介できる</br>
- ヘビロテしたい料理は料理名と空けたい期間を登録しておき、献立に反映する</br>
- 食べたい気分から動画を検索できる、提案してくれる。「ガッツリ」「あっさり」などから献立を提案</br>
- いつ何を食べたのかカレンダーに登録、表示できる

## なぜこのサービスを作りたいのか？
　Youtubeの料理動画を参考にすることが多く自分で再生リスト作成しているが、再生リスト内の動画を検索しづらく見づらいと感じていた。また、私のこだわりとしてその日に食べた料理を近日中に食べるのが嫌である。そのためいつ何を食べたのかカレンダーに登録して、それを参考にしながら献立を考えていたがカレンダーに登録するのがめんどくさくなった。そこで、自動でYoutubeの料理動画をもとに近日で食べた料理と被らないよう献立を作成してくれるサービスがあれば便利だと感じ作りたいと思った。


## スケジュール
企画〜技術調査及びREADME〜ER図作成：2/12〆切</br>
メイン機能実装：2/12 - 3/17</br>
β版をRUNTEQ内リリース（MVP)：3/18〆切</br>
本番リリース：4/2

##　画面遷移図

[Youtube キッチン]
(https://www.figma.com/file/qCH0aAnM3k2fJmUI60gIZ0/Youtube%E3%80%80%E3%82%AD%E3%83%83%E3%83%81%E3%83%B3%EF%BC%88%E4%BB%AE%EF%BC%89?node-id=0%3A1&t=mjXWwoaCMv0IuIe6-1)
