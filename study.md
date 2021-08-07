# Tips memo

参考 : https://nsuzuki7713.github.io/portfolio/

- 勉強したいこと
  - flexbox
  - カレンダーとか、いい感じのUIはフレームワークなりパッケージなりを使う。
    - https://saruwakakun.com/html-css/reference/buttons
    - https://www.webcreatorbox.com/tech/css-flexbox-cheat-sheet
    - https://qiita.com/kura07/items/e633b35e33e43240d363

## profile

- ポイント
  - まずdivタグなどで、枠組みを決める
  - その中で配置をどうするかを考える。
  - imgとかも、divで区切られた領域野中で、どのように配置するかを考えた方がわかりやすい！！
- **画像を中央寄せする話**
  - 画像を配置するdivタグを`display: flex;`にして、やったらうまく行った。
    - [ref](https://style.potepan.com/articles/23332.html)
  - margin auto みたいな感じでやるとうまくいかなかった
    - imgタグがインライン要素だかららしい。。。

## history

- refs
  - [1](https://blog.universe-web.jp/1680/)
  - [2](https://www.kabanoki.net/5305/)

- CSSに出てくる`::after`とか、`:hover`とかの謎
  - [ref](https://www.asobou.co.jp/blog/web/css2)
  - 擬似クラス、擬似要素という
    - タグのより狭い範囲だとか、カーソルを当てた時とかの特殊な状態に対してCSSを適用することができる。
- 
