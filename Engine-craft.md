## エンジン(組み立て)
```mermaid
flowchart BT
aa[[鋼のパイプ]]
ab[[精密シリンダー]]
ac[[燃料ノズルボディ]]
ad[[鋼のバルブ]]
ae[[精密ピストン]]
af[[クランクシャフト]]
ag[[大きい滑車]]
ah[[小さい滑車]]
ai[[タイミングベルト]]
aj[[カムシャフト]]
ak[[長いまっすぐの棒]]
al[[空の燃料タンク]]

subgraph 2つ作る
direction BT
ab --> ba(バルブ1つつきのディーゼルシリンダーヘッド)
ad --> ba
ba --> bb(バルブつきのディーゼルシリンダーヘッド)
ad --> bb
ad --> bc(燃料噴射ノズル)
ac --> bc
bb --> bd(ディーゼルシリンダーヘッド)
bc --> bd
bd --> be(ディーゼルピストンヘッド)
ae --> be
end

2つ作る ==> bf(ディーゼルピストンブロック)
bf --> bg(ディーゼルクランク機構)
af --> bg

ag --> bh(滑車機構の一部)
ak --> bh
bh --> bi(繋がっていない滑車駆動機構)
ah --> bi
bi --> bj(滑車タイミング機構)
ai --> bj
bj --> bk(カムタイミング機構)
aj --> bk
bg --> bl(ディーゼル駆動機構)
bk -->|"-長いまっすぐの棒"| bl
aa --> bn(エンジン燃料システム)
al --> bn
bl --> bm(ディーゼルエンジン)
bn --> bm
```
### クラフト先
* 車
* エンジン井戸
### 必要なもの
* [部品](https://github.com/aya-0p/yah-craft-recipe/blob/main/Engine-parts.md)
* [タイミングベルト](https://github.com/aya-0p/yah-craft-recipe/blob/main/Rubber.md)
* 長いまっすぐの棒
