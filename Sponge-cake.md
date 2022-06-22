## スポンジケーキ
```mermaid
flowchart BT
aaa([大きな粘土のボウル])

aba[[小麦粉入りのボウル]]
abb[[卵]]
abc[[バター入りのボウル]]
abd[[ハチミツ入りのボウル]]

aaa -->|"-粘土のボウル"| aca(小麦粉入りのボウル)
aba --> aca
aca --> acb("小麦粉と卵入りのボウル")
abb --> acb
acb -->|"-粘土のボウル"| acc("小麦粉、卵、バター")
abc --> acc
acc -->|"-粘土のボウル"| acd("ケーキ生地入りのボウル")
abd --> acd
acd -->|"-大きな粘土のボウル\n+粘土盤"| ace(ケーキ生地入りの平なべ)
ace -->|オーブン| acf(焼いたケーキ)
acf -->|"-粘土盤\n+大きな粘土の皿"| acg(スポンジケーキ)
```
### クラフト先
* [ケーキ](https://github.com/aya-0p/yah-craft-recipe/blob/main/Cake.md)
### 必要なもの
* 小麦粉入りのボウル
* 卵: 池から入手
* バター入りのボウル
* ハチミツ入りのボウル
### 道具
* オーブン
* [土器系](https://github.com/aya-0p/yah-craft-recipe/blob/main/Cray.md)
