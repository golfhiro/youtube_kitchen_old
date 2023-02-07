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
(https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=youtube_kitchen.drawio#R7V1dk9o2FP01PKaDMebjMbDJNtPdSbppm7QvO1qsNWqMRWWxQH59JbBsQIa1FmNjSTObDJaFMfce3eN7dCVa7ni2uiVgPr3HPgxbnba%2Fark3rU5n6HXZ%2F7xhvW3oOb1tQ0CQv21ysoav6CdMGttJ6wL5MN7rSDEOKZrvN05wFMEJ3WsDhODlfrdnHO5%2F6hwEUGr4OgGh3PoN%2BXSatDrtdnbiV4iCafLRAy858QQmPwKCF1HyeRGO4PbMDIjLJF3jKfDxcqfJ%2FdByxwRjun01W41hyK0qLLZ938cjZ9NbJjCiRd7wOPrvn26MP31bOujny8Jb0dvP79zETy8gXCS2%2BDOGJE5uma6Fhdjdz%2FlLCp540yimgNDEkW6bNTDXUIAiSFiDszkOQzCP0ab7tmWKQv8OrPGCiguJo9EzWkH%2FYetH3pe59I5djB%2Fyiz%2Bzi39NboafBiEKIvZ6wr47%2F8QRgTG7lzsQ06SHbJ3EYC%2BQULjaaUqsdQvxDFKyZl2Ss4PEcev9w%2BUOQETbdAcbKahBAsogvXLmHfYicZCKs%2FqSs0776YHjbTTFBP3k3gkTa%2B76bnO8RLMQRAzhwD9oGuHNkN74AIXhGIeYO3gD80Mf804%2BwfM%2FAAkgTRrmGEV0YwhvxP6YacbtX7yWx%2B51zI6d7Jj98e6EjnEUU8KwxK8BmUuXkLt1RPE8uWgIn8X1SWJ4%2FvoJU4pnRwFwegC8DosEB25BHLgXg8FAgsGX344CgVmAIhA%2BsLAJoiDcum0TRUHmthzf5lo7tfCh6Q8HKGb2fA434W6KfB9GCh7pF%2FbIjgtcRQ8kF8vMonw1ELLQEwHKxggL%2F7Hk1vQ%2Bz%2FD0UPI061%2Bvp0Xo3fYdxXMwQVFwt31n7wAKXmVQWB0fnF6p0Ch0uQqw0W1bMihEBu1LkkGvbjLoOsVhUE2AgD4S1zuTCVKIWybodiQ3g8mEfRx9jMCM33PLfb%2FxOmHR%2BNopohpMmEcJQ8sAlTPAsG4GEODTIeAPC1tf94DvybwOZwCFBkX64mAwLtI7Jwa9DfWXCvVOp%2B5Y74iwoEGwTzFsoz2zhfx8H8DIhySN92xQwIAfaxvwVQBhXMTvuhJALANUzwBe3QzQ7RbHQdMYIcW4JYSuJ7l5QtZzCv3HOYjjJSa%2BQZlAcVyYxwvyBL7lhep5oWhxwOV4QaE2oHG8UNwf2vOCPPcfs481iAuKY8E4LvDkh4Yxxj%2F%2BQj7EtqKLnRmI6VpF7T51cPnivaXv0ku60mHQnJIuT2ZvnUq6PEvgqSlkAjeqpEsBCsbxd08WgS0ZnJnLqZNB7SVdPQWpt2mpXApxywQ9WcmliIYG1XIpgME8LpBzOcsFlXNB7cVdPYX8sHFcUNwd2nOBnP%2FR6WL2FAEUPi6IQVVfCqAwjxMGlgIqp4D6i756x8u6GxfyB4XNr3vI78vrt14QXD5uFnW0zKn6UoCEcQG%2FLxeB8wmdEfs3A%2BSHndNhZ7piICXxulswXKdxvfR43bcyXulzOv3iuLiWOZ2%2BLOPpNKeTotxSeV9W8oya01GAgnkUbnW80pM4dTKofU6nr7GO17c6XmoKWcdbxJA8Xj8dVON%2F88K%2FXO5hw3%2Fl4b%2F2aZy%2BvJGTPuHfanrCFAJTe5qeD7Hm8d8qeMcRIaeGtzAi0Ep37MzgYIfNXlHNZnipOD2w2Vrp0l06BJoj3Q3kbE0n6W5gE7bUFHLCdv1cXaJ0pwAF47h7qLC1otFkoJC7qZNB7dLdsFMcBk3L3YbFn9l0Z4KhPF1n1s6aClgwjwrkx4RPUUDYQIQ83NpcruN093M5t6jmdrFcbmil19JzuWHxDdmvJZcbytKrTrnc0Kqv6f5x4td6TE3mFLBgHIM7bZvNlZ7NqdNB7dmc09Y4nctAbtnAaZue0KmgwTw%2BcOSHhRsUT%2B3MHD%2FbdfazuV7R%2Fe0uV1XvOJbAS8%2FnslHQnITOcWQG1ymjy4BuSdxxZBI3KqVTAYOBHK6wGbbRlKCQ072BEupP6hyFup3GJXVO8TlT%2FflArswxLKlTQIPOhNB7eDd5HiyW0WjW9dzRHWjf%2Fv6u49nwX334r7K6Pt%2FtvSYG%2B5MINivW55tCnnMPeOm0NsX05wJA5%2FCeH5tyBjr0AyhyLRYrpzjAEQg%2FZK0jwu8HikCe9bnDG6fzAfsvpHSdEABYUMxJgs7C5CxzGFl%2FF0OdH%2FzND37xxOHNavfkjSCIDa28J2SDgw8PW6RtGj%2BiMEzf4mddZiBab9t2esjAEb8BhxdkAk%2FYS%2Fx8OhUEdKyjWMHHjXkScgSGgKIXuHcf5T%2FOd%2BQdj6rw8wrR1M3s9Y6X2VHmZH6w3vX4912gNAQbYh%2Fm17ExuC5suHLOf7%2B%2Bh9HCCvf87KFwX%2FQHy9L6rQt4zC6qKV%2B4d5u3qsZx9V5WkwHdqIf3I7YwfGGNChjMe5B3bW1u%2BcqNOiUUFe4v%2BGwgV%2Bd%2BrJsSSpTu3dKqc0%2B5QJ0RDq9WxZgXn5mzN86403rfvnZyqAgHimTwdlwUulwVOp%2BN%2FNVH%2FrRWvorQn%2Bt2ubCjmYH%2FFKbNCvu5lpDVGh%2FFU801fBvsj4YqseFCg6RdbWX%2F9LGkem03d9zIs%2FfXDo2mqf5pOeEuNk7FsCtBhiwm3bMwRRhNfH7mO%2BKz0G3lfx7RRZgXmm9h%2Bb%2BMuv1c11ml5xzx%2F%2BRouErpP%2FeOtVmDfRLiRsn%2BuZbIWVR1%2FU%2F6b1P9z0SCzpp%2FPjTs8q1zhJ9yiKDKSv18FHQkFGgk%2B5i5civfFLK%2Bp7%2FwYxdrnbCNXatVf%2FyvvVQ%2FZ6GWTvHfyJVa%2BaaQa71QumOe5ixgV2gdlxXlaf4KNV7xWmv5X%2BwC9qrEK3B6JRpv%2BgWbAw195X%2FR8VqwIf%2FyeZULf%2Brx81tmpt6ODbET%2FOszQ6UvFkre%2BoU%2FbWekODj4Yd90DyJxie1XSt6lQlXskGBMd7sTMJ%2FeYx%2FyHv8D)
