## ニューコメン系
```mermaid
flowchart BT
roota[[鋼]]
rootb[[錬鉄]]

rootb --->|鍛冶金づち1回\n熱| rootc(生硬なピストン)
rootb -->|鍛冶金づち2回\n熱| rootd(生硬なシリンダー)
rootb -->|鍛冶金づち3回\n熱| roote(燃料タンク)
rootb -->|鍛冶金づち4回\n熱| rootf(ボイラー)

subgraph a [多目的ニューコメンエンジン]
direction BT
aaa[[石ブロックx4]]
aab[[長いまっすぐの棒x2]]
aac[[小さな曲がった棒x2]]
aad[[ボイラー]]
aae[[生硬なシリンダー]]
aaf[[生硬なピストン]]
aag[[硬化ゴムタイヤ]]
aah[[ロープ]]
aai[[イチイの棒]]


aba["(地面)"] -->|"-杭\n石x5\n+杭"| abb(自立式ニューコメンタワー)
aaa --> abb
aab ==> abc(2本の棒)
aac ==> abd(2本の曲がった棒)
abc --> abe(ポンプビームキット)
abd --> abe
abb --> abf(ニューコメンエンジンタワー)
abe --> abf
aad --> abg(シリンダー付きのボイラー)
aae --> abg
aaf --> abh(密封した生硬なピストン)
aag --> abh
abg --> abi(ニューコメン大気圧中子)
abh --> abi
abf --> abj(ロープのないニューコメンエンジン)
abi --> abj
abj --> abk(棒のないニューコメンエンジン)
aah --> abk
abk --> abl(多目的ニューコメンエンジン)
aai --> abl
end
rootf -..- aad
rootc -..- aaf
rootd -..- aae


subgraph b [ローラー機構]
direction BT
baa[[長いまっすぐの棒]]
bab[[大きい滑車x2]]
baa --> bba[[ローラー機構]]
bab ==> bba
end
roota -.-> bab
subgraph c [滑車駆動機構]
direction BT
caa[[長いまっすぐの棒]]
cab[[大きい滑車]]
cac[[小さい滑車]]
cad[[硬化ゴムベルト]]

caa --> cba(滑車機構の一部)
cab --> cba
cba --> cbb(繋がっていない滑車駆動機構)
cac --> cbb
cbb --> cbc(滑車駆動機構)
cad --> cbc
end
roota -.-> cab
roota -..-> cac

subgraph d [ドリル機構]
direction BT
ca[[ドリルビット]]
cb[[滑車駆動機構]]
ca --> db(ドリル機構)
cb --> db
end
roota -.-> ca
c -.....- cb

subgraph e [のこぎり機構]
direction BT
eaa[[丸いのこぎり]]
eab[[ドリル機構]]
eaa --> eb(のこぎり機構)
eab --> eb
end
roota -.-> eaa
c -.....- eab

subgraph f [穴あけ機構]
direction BT
faa[[滑車駆動機構]]
fab[[鋼の刃]]
faa --> fb(穴あけ機構)
fab --> fb
end
roota -.-> fab
c -.....- faa

subgraph g [ろくろ機構]
direction BT
gaa[[滑車駆動機構]]
gab[[鋼の刃]]
gac[[短い棒]]
gad[[ロープ]]
gac --> gba(縛られた短い棒)
gad --> gba
gba --> gbb(ろくろの頭)
gab --> gbb
gaa --> gbc(ろくろ機構)
gbb --> gbc
end
roota -.-> gab
c -.....- gaa

b -...- topa("ローラー機構\nドリル機構\nのこぎり機構\n生硬なピストン\n穴あけ機構\nろくろ機構")
d -..- topa
e -..- topa
f -..- topa
g -..- topa
rootc -...- topa

topa <--> topb("ニューコメンタワーローラー\nニューコメンドリル\nニューコメンのこぎり\nニューコメンハンマー\nニューコメンタワー穴あけ機\nニューコメンろくろ")
a <------------> topb
```
### 必要なもの
* 石ブロック
* ロープ
* イチイの棒
* 小さな曲がった棒
* 長いまっすぐの棒
* [硬化ゴムタイヤ、硬化ゴムベルト](https://github.com/aya-0p/yah-craft-recipe/blob/main/Rubber.md)
* 鋼
* 錬鉄

### 道具
* [鍛冶金づち](https://github.com/aya-0p/yah-craft-recipe/blob/main/Iron.md)
* 石
* 杭
