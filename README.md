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
- いつ何を食べたのかカレンダーに登録、表示できる</br>
- おすすめ料理動画を他のユーザーが教えてくれる機能

## なぜこのサービスを作りたいのか？
　Youtubeの料理動画を参考にすることが多く自分で再生リスト作成しているが、再生リスト内の動画を検索しづらく見づらいと感じていた。また、私のこだわりとしてその日に食べた料理を近日中に食べるのが嫌である。そのためいつ何を食べたのかカレンダーに登録して、それを参考にしながら献立を考えていたがカレンダーに登録するのがめんどくさくなった。そこで、自動でYoutubeの料理動画をもとに近日で食べた料理と被らないよう献立を作成してくれるサービスがあれば便利だと感じ作りたいと思った。


## スケジュール
企画〜技術調査及びREADME〜ER図作成：2/12〆切</br>
メイン機能実装：2/12 - 3/17</br>
β版をRUNTEQ内リリース(MVP)：3/18〆切</br>
本番リリース：4/2

## 画面遷移図
[Youtube キッチン]
(https://www.figma.com/file/qCH0aAnM3k2fJmUI60gIZ0/Youtube%E3%80%80%E3%82%AD%E3%83%83%E3%83%81%E3%83%B3%EF%BC%88%E4%BB%AE%EF%BC%89?node-id=0%3A1&t=mjXWwoaCMv0IuIe6-1)

## ER図
(https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=youtube_kitchen.drawio#R7V1dk9o2FP01PCaDMebjMbDJNtPdSbtpm7QvO1qsBTXGorJYIL%2B%2BkrHMh2xWYo2NLc1sJrYsZKN7dI%2Fu0bVoueP5%2BpaAxewe%2BzBoddr%2BuuXetDodx%2B257D9estmWDAbtbcGUID%2BptCv4in7CpFBUWyIfRgcVKcYBRYvDwgkOQzihB2WAELw6rPaMg8O7LsAUSgVfJyCQS78hn86SUqfd3l34BaLpLLn1wEsuPIHJjynByzC5X4hDuL0yB6KZpGo0Az5e7RW5H1vumGBMt0fz9RgGvFtFj20%2F9ynnavrIBIZU5QOPo%2F%2F%2B6Ub487eVg36%2BLL01vf3yzu1tm3kBwTLpiz8jSKLkkelG9BB7%2BgU%2FpOCJF40iCghNDOm2WQEzDQUohIQVOPF5EIBFhOLq25IZCvw7sMFLKhoSZ6NntIb%2Bw9aOvC4z6R1rjJ%2Fyxp9Z41%2BTh%2BGXQYCmITuesO%2FO7zgiMGLPcgcimtSQeyfpsBdIKFzvFSW9dQvxHFKyYVWSqwLDm8PT1R5ARNlsDxspqEECymna8s467CAxkI6x%2BpKxTtvpgeNtNMME%2FeTWCZLe3LddfL5C8wCEDOHAPyoa4XhIxzZAQTDGAeYGjmF%2BbGNeySd48QcgU0iTggVGIY07whuxP9Y14%2FZ7r%2BWxZx2zc2d3zv54dULHOIwoYVjibUBm0hXkZh1RvEgaDeCzaJ8kHc%2BPnzCleJ4LgNMD4HVYJDhwFXHgXgwGAwkGv%2F2aCwTWAxSB4IG5TRBOg63ZYi8KdmbLsG1mb6c9fNz1xwMUs%2F58DmJ3N0O%2BD0MNi%2FSVLbJnAlfTAklju27Rbg0EzPWEgLIxwtx%2FJJk1fc43WHooWZrVr9bSwvVu646iBZigcHq3%2FWTvCApeaVBY5w9Or1BoKDVXAja6bUsGSmTQviQZ9Komg66jDoNyHAT0kWjvjUyQQtwyQbcjmRlMJux29DEEc%2F7MLfdDbHXCvPG1U0Q5mDCPEoaWAUpngGHVDCDA1wSHP1Tu%2FaY7fE%2FmdTgHKDDI06uDwThP75wY9NbVX8rVO52qfb0j3EIDnH2KYevtWV%2FI8%2FspDH1IUn%2FPBgWc8vPGOnwdQBjn8buuBBDLAOUzgFc1A3S76jioGyOkGLeE0PUkM0%2FIZkGh%2F7gAUbTCxDcoElDHhXm8IC%2FgW14onxdUkwMuxwsauQG14wV1ezSeF%2BS1%2F4jd1iAuUMeCcVzgyZOGMcY%2F%2FkI%2BxDaji10ZiOVaTe0%2BNXDx4r2l78JTutJhUJ%2BULk9m7yaldHmWwNOukAncqJQuDSgYx989WQS2ZPDGWE6fDCpP6eppSL11C%2BVSiFsm6MlKLkU0MCiXSwMM5nGBHMtZLiidCypP7uppxIe14wJ1czSeC%2BT4j86W86cQoOBxSQzK%2BtIAhXmcMLAUUDoFVJ%2F01ctP666dyx8od3%2FTXX5ffn%2FrBcHVY%2FxSR8ucrC8NSBjn8PtyEjhf0Bmxf3NAftg1HXalKwZS4q%2B7iu469euF%2B%2Bu%2BlfEKX9Ppq%2BPiWtZ0%2BrKM16Q1nRTllsr7spJn1JqOBhTMo3Cr4xUexOmTQeVrOv0G63h9q%2BOlXSHreMsIksfrp4Ny7G%2Be%2B5fTPaz7L939V76M05c3cmqO%2B7eanugKgakDTc%2BHuOH%2B3yp4%2BYiQQ8NbGBJopbvW3i6xYpauqtkML%2BWnBzZaK1y6S4dAfaS7gRytNUm6G9iALe0KOWC7fq4uULrTgIJx3D3U2FrRaDLQiN30yaBy6W7YUYdB3WK3ofqcrelMMJSX68zaWVMDC%2BZRgTxN%2BBxOCRuIkLtbG8t1nO5hLOeqam4Xi%2BWGVnotPJYbqm%2FIfi2x3FCWXpsUyw2t%2BpruHyd%2BrcfUYE4DC8YxuNO20Vzh0Zw%2BHVQezTntBodzO5BbNnDapgd0Omgwjw8cebJwg6KZXZnjV7vOYTTXU93f7nJZ9Y5jCbzweG43CuoT0DmOzOBNiuh2QLck7jgyiRsV0umAwUAO19gM22hK0IjpzqCE6oM6RyNvp3ZBnaO%2BZtp8PpAzcwwL6jTQ0GRC6D28mzwPlqtwNO967ugOtG9%2Ff9fxrPs%2F7f4l1KgzQq77LzO7Ptvsvbo4%2B1e6%2FwSoG%2B3rs7%2B3vOY%2B5anTtU6mLxIATXbv2Y4oY6BDfwpFrMV85QxPcQiCj7vSEeHPA4Uj39W5w7HR%2BYD9F1K6SQgALCnmJEHnQXKVWYdsvouhzk%2F%2B5ifvPXF6s96%2FeCMIIqaVD4TEOPj4sEVaXPgJBUH6EX9XZQ7CzbZsr4aMEvEbcHhJJvBEf4mfT6eCgPIqijf4eGeenFEQGACKXuDBcxQ%2Fne%2FIOx6VYec1oqmZ2fGeldnZzsj8ZLNv8e%2F7QKkJNsQ%2BzK9jY3Bd2HDlmP9%2Bcw%2FDpRXu%2BdVj4V71B8vS%2FK0LWMy%2BVFO8cO%2FW760ax232azU7oFuhxnENf7FGBwzmTeRdm5tbvHCvTwmqwv0F5wZydu6nqimhQOneLSw795QJ9BnhuLUyxry4Z8beOONO60P72smhJBxoksH5uFBqrgydz3r%2BC2j2WzLI9fxprnwZrj%2FT7HJiR30c%2F1kqbuPdfubXltUaH0Uz8zR885x9tl8SGy7USNptrOyfTkvK13YzB4m8en%2Ft0NBU%2FTN7%2Bzwjp4mB%2B1bWcT3lmFRWge6ZfyHMv3955lvZM5%2FbFN3%2BFVp4JeFe%2BGch1irr9kUk3Geazko0uqr9OROD%2Fslpepmafebj1frl6XPsMThrml4nvT7za2e8DXX9U3R1ub5AJDRZrM%2BGhn3vqmDF5gwiKDPFPhsFHQkFzdZrnOav3GZ%2Fb1mYM1KxybO%2Fef7fvmRVvf%2BvPMc%2B4w2rhvv%2FnAWUxvt%2FOUkLpVvdmccCOSgwjgWEzFSNOCuOL6nbt4oTZ8VGXK9qs3nwKkecTb9PfWxaB8E9b%2BZYklHlHwm3qyi5A1V5ESXnHay32pSdEozpvq8mYDG7xz7kNf4H)
