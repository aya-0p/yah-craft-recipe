## 馬力車
```mermaid
flowchart BT
subgraph a [つながれた乗用馬]
direction BT
aaa[[長いまっすぐの棒x2]]
aab[[ロープx2]]
aac[[荒馬]]
aad[["野生ニンジン|にんじん"]]
aae[[家畜のヒツジ]]
aaf[["針と糸|針と毛糸玉"]]

aaa ==> aba(2本の棒)
aba -->|鋼のちょうな| abb(フェンスキット)
abb --> abc(フェンス)
aah["(地面)"] -->|"-杭\nシャベル\n石\n+杭"| abc
aab --> abd(投げ縄)
abd --> abe(捕らえられた馬)
aac --> abe
abc --> abf(つながれた荒馬)
abe --> abf
abf --> abg(つながれた飼いなされた馬)
aad --> abg

aae -->|"-毛のないヒツジ\nナイフ(2回)"| abh(羊皮)
abh --> abi(羊皮のサドル)
aaf -->|"-針|針と糸|針と毛糸玉"| abi
abg --> abj{{つながれた乗用馬}}
abi --> abj
end

subgraph b [荷車]
direction BT
baa[[板]]
bab[[ロープ]]
bac[[長いまっすぐの棒]]
bad[[木製ディスク]]

baa --> bba{{木箱}}
bab --> bba
bba ---> bbb{{木製のそり}}
bac --> bbb
bad -->|火打ち石つき弓ぎり| bbc(穴の開いた木製ディスク)
bbb --> bbd{{一輪車}}
bbc --> bbd
bbd --> bbe{{荷車}}
bbc --> bbe
end

subgraph f [タイヤのある荷車]
direction BT
faa[[荷車]]
fab[[硬化ゴムタイヤx2]]
fab ==> fba(2つのゴムタイヤ)
faa --> fbb{{タイヤのある荷車}}
fba --> fbb
end
b -..- faa

subgraph c [つながれた馬力車]
direction BT
caa[[荷車]]
cab[[つながれた乗用馬]]
caa --> cb{{つながれた馬力車}}
cab --> cb
end
a -.- cab
b -.- caa

subgraph d [つながれた馬力車]
direction BT
subgraph e [2つ作る]
direction BT
eaa[[イチイの棒x4]]
eab[[曲がった棒x4]]
eac[[ロープ]]

eaa ==> eba(四本の曲がった棒)
eab ==> ebb(四本のイチイの棒)
eba --> ebc(イチイの棒と曲がった棒)
ebb --> ebc
ebc --> ebd(大きな車輪)
eac --> ebd
end
daa[[つながれた馬力車]]
e ==> dba(二つの大きな車輪)
daa --> dbb{{つながれた馬力車}}
dba --> dbb
end
c -...- daa
```
### 必要なもの
* 長いまっすぐの棒
* 小さな曲がった棒
* イチイの棒
* ロープ
* 荒馬
* 家畜のヒツジ
* 板
* 木製ディスク
* [硬化ゴムタイヤ](https://github.com/aya-0p/yah-craft-recipe/blob/main/Rubber.md)

### 道具
* [鋼のちょうな、シャベル、ナイフ](https://github.com/aya-0p/yah-craft-recipe/blob/main/Iron.md)
* 火打ち石つき弓切り
* 杭
* 針と糸|針と毛糸玉
* 石
