## 高/中/低周波AM受信機
```mermaid
flowchart BT
aa[[鉄のロッド]]
ab[[銅線]]
ac[[紙]]
ad[[板]]
ae[[炭素フィラメント]]
af[[熱いガラス球付きの吹管]]
ag[[銅箔]]
ah[[紙]]
ai[[電池x2]]
ac -.- ah
aj[[短い/中くらい/長いアンテナ]]

aa --> ba(電磁石)
ab --> ba
ba ----> bb(拡声器)
ac --> bb
bb --> bc(AM受信機の一部)
ad --> bc

subgraph x [2つ作る]
direction BT
xa[[銅線]]
xa --> ca(炭素フィラメントとリードワイヤ)
ae --> ca
xa --> cb(ダイオードのリード)
ca --> cb
end
ab -.- xa

x ---> da(トリオードのリード)
ab ---> da
da ----> db(真空トリオード)
af -->|"-吹管"| db
bc --> de(AM受信機の一部)
db --> de
x ---> df(真空ダイオード)
af -->|"-吹管"| df
de --> dg(AM受信機の一部)
df --> dg

subgraph y [2つ作る]
direction BT
ag --> ea(箔と紙のサンドイッチ)
ah --> ea
end
y ==> eb(蓄電器)

dg --> fa(AM受信機の一部)
eb --> fa

ai ==> fb(2つのダニエル電池)
fa --> fc(AM受信機の一部)
fb --> fc

fc ---> fd(高/中/低周波AM受信機)
aj --> fd
```
### 必要なもの
* [銅線x5、炭素フィラメントx2、銅箔x2、鉄のロッド、電池x2、アンテナ](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-marconi-parts.md)
* 紙
* 板
* [熱いガラス球付きの吹管](https://github.com/aya-0p/yah-craft-recipe/blob/main/Glass.md)

### 関連
* [AM送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-transmitter.md)
* [マルコーニレシーバー](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-receiver.md)
* [花火送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-transmitter.md)
