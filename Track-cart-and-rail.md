## トロッコとレール
```mermaid
flowchart BT

subgraph a [トロッコキット]
direction BT
aaa[[板]]
aab[[穴の開いた木製ディスク]]
aac[[鋼のバネ]]

aaa ---> aba(トロッコキットの一部)
aab ---> aba
aba --> abb(トロッコキットの一部)
aab --> abb
abb --> abc(トロッコキットの一部)
aab --> abc
abc --> abd(トロッコキットの一部)
aab --> abd
abd ---> abe(トロッコキット)
aac --> abe
end

subgraph b [レール]
direction BT
baa[[砂利入りのかご]]
bab[[大きなプレート]]
bac[[鋼のバネ]]
bad[[小さい滑車]]
bae[[板]]
baf[[鋼の柄のない刃]]
bba[地面] -->|"-泥\nシャベル|くし|石のくわ|鋼のくわ\n石x4\n+杭"| bbb(半分掘られた溝)
bbb --> bbc(砂利の道)
baa -->|"-かご"| bbc
subgraph c [線路キット]
direction BT
bae --> cb(線路キット)
baf --> cb
end
c -------> bbe(線路)
bbc --> bbe

bbc --> bbf(大きなプレート)
bab --> bbf
bbf --> bbg(大きなプレートとバネ)
bac --> bbg
bbg --> bbi(転車台基礎)
bad --> bbi
bbi -->|"-たがね\n鍛冶金づちx(自由)\n+たがね"| bbi
bbi --> bbj("転車台[東|西|南|北]")
c -------> bbj
end

subgraph d [旗]
direction BT
daa[[イチイの棒]]
dab[[くし]]
dac[["毛織布(緑、赤)"]]

daa --> dba("Skewer and Long Shaft")
dab --> dba
dba --> dbb("方向旗|停止旗")
dac --> dbb
end
```
### 必要なもの
* 板
* 穴の開いた木製ディスク
* [鋼のバネ、柄のない刃](https://github.com/aya-0p/yah-craft-recipe/blob/main/Iron.md)
* 砂利入りのかご
* 大きなプレート
* [小さい滑車](https://github.com/aya-0p/yah-craft-recipe/blob/main/Engine-parts.md)
* イチイの棒
* くし
* 毛織布
### 道具
* [シャベル、鋼のくわ、たがね、鍛冶金づち](https://github.com/aya-0p/yah-craft-recipe/blob/main/Iron.md)
* くし
* 石のくわ
* 杭
