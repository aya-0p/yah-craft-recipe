## ガラス
```mermaid
flowchart BT
subgraph a [基本]
direction BT
aaa[[アッケシソウ]]
aab[[水入りのボウル]]
aac[[紙]]
aad[[生石灰入りのボウル]]
aae[[砂入りのボウル]]

aaa -->|"+ボウル\n時間\n+火"| aba(アッケシソウの灰入りのボウル)
aba --> abb(漬けているアッケシソウの灰入りのボウル)
aab -->|"-ボウル"| abb
abb --> abc(アッケシソウの灰入りのボウルと濾紙)
aac --> abc
abc -->|"(時間)\n-ボウル\n+ボウルと濾紙"| abd(ソーダ灰入りのボウル)
abd --> abe(ソーダ石灰混合物入りのボウル)
aad -->|"-ボウル"| abe
abe --> abf(ソーダ石灰ガラス一杯分)
aae --> abf
abf -->|"ここから時間に注意！\n炉(ふいごあり)"| abg(融解したガラス)
end

subgraph b [蓋のついたガラス瓶]
direction BT
baa[[融解したガラス]]
bab[[長いまっすぐの棒]]
baa --> |"+吹管"| bba(熱いガラス球付きの吹管)
bba --> bbb(熱いガラス球付きの吹管)
baa --> bbb
bbb -->|"(地面)|平らな岩->(地面)\n木製ディスク"| bbc(ガラス瓶)
bab -->|つる鋸| bbd(小さい木製ディスク)
bbc --> bbe(蓋のついたガラス瓶)
bbd --> bbe
end
a -.- baa

subgraph c [哺乳瓶]
direction BT
caa[[融解したガラス]]
cab[[ゴム製乳首]]
caa --> |"+吹管"| cba(熱いガラス球付きの吹管)
cba -->|"(地面)|平らな岩->(地面)\n木製ディスク"| cbb(ガラス瓶)
cbb --> cbc(ほ乳瓶)
cab --> cbc
cbc -->|煮立つ水| cbd(滅菌ほ乳瓶)
end
a -.- caa
```
### クラフト先
* [コヒーラー -> マルコーニレシーバー](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-marconi-parts.md)
* [AM受信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-receiver.md)
* [AM送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-transmitter.md)
* [マルコーニレシーバー](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-receiver.md)
### 必要なもの
* アッケシソウ
* 水
* 紙
* 生石灰入りのボウル
* 砂入りのボウル
* 長いまっすぐの棒
* ゴム製乳首
### 道具
* 火
* [ボウル](https://github.com/aya-0p/yah-craft-recipe/blob/main/Clay.md)
* 吹管
* 木製ディスク
* 炉
* つる鋸
* 煮立つ水
