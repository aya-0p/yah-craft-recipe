## 高/中/低周波AM送信機
**無給電の高/中/低周波花火送信機と誤表記があります**
```mermaid
flowchart BT
aa[[銅箔]]
ab[[炭素]]
ac[[銅線]]
ad[[板]]
ae[[炭素フィラメント]]
af[[紙]]
ag[[ダニエル電池x2]]
ah[[熱いガラス球付きの吹管]]
ai[[長いアンテナ]]

ab --> ba(銅箔と炭素粒)
aa --> ba
ba --> bb(銅箔カーボンサンドイッチ)
aa --> bb
bb --> bc(カーボンマイク)
ac --> bc
bc --> bd(AM送信機の一部)
ad --> bd

subgraph x [2つ作る]
direction BT
xa[[銅線]]
xa --> ca(炭素フィラメントとリードワイヤー)
ae --> ca
xa --> cb(ダイオードのリード)
ca --> cb
xa --> cc(トリオードのリード)
cb --> cc
cc --> cd(真空トリオード)
ah --> cd
end
ac -..- xa
x ==> da(2つの真空トリオード)
bd --> db(AM送信機の一部)
da --> db
ac -->|短い棒| dc(銅線コイル)
db --> dd(AM送信機の一部)
dc --> dd
dd --> de(AM送信機の一部)
ai --> de
subgraph z ["1-3つ作る"]
direction BT
subgraph y ["2-6つ作る"]
direction BT
yn[[銅箔]]
yn --> ya(箔と銅のサンドイッチ)
af --> ya
end
y ===> za(蓄電器)
end
aa -.- yn
de -----> ea(無給電の高/中/低周波花火送信機)
z ------>|"1/2/3つ"| ea
ag ==> eg(2つのダニエル電池)
ea ---> ed(高/中/低周波AM送信機)
eg ---> ed
```
### 必要なもの

### 道具

### 関連
* [AM受信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-receiver.md)
* [マルコーニレシーバー](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-receiver.md)
* [花火送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-transmitter.md)
