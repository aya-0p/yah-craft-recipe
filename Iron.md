## 金属加工
```mermaid
flowchart BT
aaa[[鉄鉱石]]
aab[[木炭]]
aaa -->|"石|鍛冶金づち\n炉(ふいごあり)"| aba(細工した鉄)
aba -->|"+粘土の皿\n+粘土のボウル"| abb(生の閉じたつぼ)
aab --> abb
abb -->|"-粘土のボウル\n-粘土の皿\n炉(ふいごあり)"| abc(鋼)

subgraph b [鋼加工]
direction LR
ba[[熱い鋼の延べ棒]]
ba --> bba(斧)
bba --> bbb(くわ)
bbb --> bbc(たがね)
bbc --> bbd(ちょうな)
bbd --> bbe(なた)
bbe --> bbf(目のないやすり)
bbf --> bbg(柄のない刃)
bbg --> bbh(シャベル)
bbh --> bbi(つるはし)
ba -->|石| bbj(鍛冶金づち)
end
abc -.-> b

bbg ---> abd(刃)
abd --> abh(ノコギリの刃)
bbg -->|粘土のボウル| abf(焼き入れた鋼のバネ)
bbf --> abe(やすり)


subgraph c [錬鉄加工]
direction BT
ca[[熱い錬鉄]]
ca --> cba(生硬なピストン)
cba --> cbb(生硬なシリンダー)
cbb --> cbc(空の燃料タンク)
cbc --> cbd(ボイラー)
end
aba -..-> c
```
### 必要なもの
* 鉄鉱石
* 木炭
