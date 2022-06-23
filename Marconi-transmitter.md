## 高/中/低周波花火送信機
```mermaid
flowchart BT
aa[[銅のロッド]]
ab[[銅の延べ棒]]
ac[[板]]
ad[[紙]]
ae[[銅箔]]
af[[銅線]]
ah[[ダニエル電池]]
ai[[短い/中くらい/長いアンテナ]]
subgraph x [2つ作る]
direction BT
ab --> ba(スパーク端子)
aa --> ba
end
x ==> bb(2つのスパーク端子)
bb --> bc(花火送信機の一部)
ac --> bc
subgraph z [2つ作る]
direction BT
subgraph y [4つ作る]
direction BT
ad --> bd(箔と紙のサンドイッチ)
ae --> bd
end
y ==> be(蓄電器)
end
z ==> bf(2つのコンデンサ)
bc --> bg(花火送信機の一部)
bf --> bg
af -->|短い棒| bh(銅線コイル)
bg --> bi(花火送信機の一部)
bh --> bi
bi ---> bj(高/中/低周波花火送信機)
ai --> bj
bj --> bm(高/中/低周波花火送信機)
ah --> bm
```
### 必要なもの

### 道具

### 関連
* [AM受信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-receiver.md)
* [AM送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-transmitter.md)
* [マルコーニレシーバー](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-receiver.md)
