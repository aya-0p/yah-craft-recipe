## 高/中/低周波マルコーニレシーバー
```mermaid
flowchart BT
aa[[コヒーラー]]
ab[[板]]
ac[[銅線]]
ad[[鉄のロッド]]
ae[[炭素フィラメント]]
af[[熱いガラス球付きの吹管]]
ag[[ダニエル電池x2]]
ah[[短い/中くらいの/長いアンテナ]]

aa --> ba(マルコーニレシーバーの一部)
ab --> ba
subgraph x [2つ作る]
xa[[銅線]]
direction BT
xa -->|短い棒| xb(銅線コイル)
end
ac -.- xa
x ===>  bb(2つの銅線コイル)
ba --> bc(マルコーニレシーバーの一部)
bb --> bc
ad --> bd(電磁石)
ac --> bd
bc --> be(マルコーニレシーバーの一部)
bd --> be
ae --> bf(炭素フィラメントとリードワイヤ)
ac --> bf
bf --> bg(電球)
af --> bg
be --> bh(マルコーニレシーバーの一部)
bg --> bh
ag ==> bi(2つのダニエル電池)
bh --> bj(マルコーニレシーバーの一部)
bi --> bj
bj ---> bk(高/中/低周波マルコーニレシーバー)
ah --> bk
```
### 必要なもの

### 道具

### 関連
* [AM受信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-receiver.md)
* [AM送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-transmitter.md)
* [花火送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-transmitter.md)
