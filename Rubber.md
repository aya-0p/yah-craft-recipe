## ゴム
```mermaid
flowchart BT
subgraph a [基本]
direction BT
aaa[[ゴムの木]]
aab[[硫黄入りのボウル]]
aac[["パーム油入りのボウル|パームオレイン入りのボウル"]]

aaa -->|"+空のバケツ\nナイフ"| aba(ゴムの木とバケツ)
aba -->|"-塞がれたゴムの木\n(時間)"| abc(乳液入りのバケツ)
abc -->|"(時間)"| abd(凝固した乳液)
abd --> abe(硫黄処理した乳液)
aab -->|"-粘土のボウル"| abe
abe ---> abf(油と硫黄で処理した乳液)
aac --> abf
abf -->|"くし|弱いくし"| abg(ゴムのり入りのバケツ)
end

subgraph b [ゴム製乳首]
direction BT
ba[[ゴムのり入りのバケツ]]
ba -->|"-吹管+粘土のボウル\n穴の開いた木製ディスク\n-ゴムのり入りのバケツ+吹管"| bb(ゴム製乳首入りのボウル)
end
a -.- ba

subgraph c [生ゴムタイヤ]
direction BT
ca[[ゴムのり入りのバケツ]]
ca -->|"-空のバケツ"| cb(生ゴムタイヤ)
end
a -.- ca

subgraph d [生ゴムベルト]
direction BT
da[[生ゴムタイヤ]]
da -->|繋がっていない滑車駆動機構| db(生ゴムベルト)
end
c -.- da

b -.- eba("生ゴムタイヤ\n生ゴムベルト\nゴム製乳首")
c -.- eba
d -.- eba
eba -->|日干し煉瓦のかまど| ebb("硬化ゴムタイヤ\n硬化ゴムベルト\nゴム製乳首")
ebb -.-|硬化ゴムベルトのみ| ebc(硬化ゴムベルト)
ebc -->|ナイフ| ebd(タイミングベルト)
```
### クラフト先
* [エンジン](https://github.com/aya-0p/yah-craft-recipe/blob/main/Engine-craft.md)
* [ほ乳瓶](https://github.com/aya-0p/yah-craft-recipe/blob/main/Glass.md)
* [ニューコメンエンジン、滑車駆動機構](https://github.com/aya-0p/yah-craft-recipe/blob/main/Newcomen-tools.md)
* 荒い車
* [タイヤのある荷車](https://github.com/aya-0p/yah-craft-recipe/blob/main/2.23.0/Horse-drawn-cart.md)
* [小さい一輪車](https://github.com/aya-0p/yah-craft-recipe/blob/main/Wheelbarrow.md)
### 必要なもの
* ゴムの木
* 硫黄入りのボウル
* パーム油入りのボウル|パームオレイン入りのボウル
### 道具
* [粘土のボウル](https://github.com/aya-0p/yah-craft-recipe/blob/main/Clay.md)
* くし|弱いくし
* ナイフ
* 空のバケツ
