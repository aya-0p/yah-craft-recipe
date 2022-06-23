## AM送受信機/花火送信機/マルコーニレシーバー(部品)
```mermaid
flowchart BT
roota[[銅の延べ棒]]

subgraph a [雑多なもの]
direction BT
aa[[糸]]
ac[[銅の延べ棒]]
ae[[練鉄]]
ah[[亜鉛]]
aa -->|"-粘土のボウル\n-粘土の皿\n+燃える日干し煉瓦の炉(ふいご不要)\n+粘土の皿\n+粘土のボウル"| ab(炭素フィラメント)
ac -->|ニューコメンローラ機| ad(銅のロッド)
ae -->|"ニューコメンローラ機\n熱"| af(鉄のロッド)
ac -->|ニューコメンハンマー| ag(銅箔)
ah -->|ニューコメンローラ機| ai(亜鉛のロッド)

end
roota -.- ac

subgraph b [ダニエル電池]
direction BT
ba[[硝石]]
bb[[水入りのボウル]]
bc[[灰]]
bd[[紙]]
be[[硫黄入りのボウル]]
bf[[銅箔]]
bg[[銅の延べ棒]]
bh[[亜鉛のロッド]]
subgraph bn [硫酸入りのボウル]
direction BT
ba --> bxa(硝石溶液入りのボウル)
bb ---> bxa
bxa --> bxb(溶かした硝石入りのボウルと灰)
bc --> bxb
bxb --> bxc(灰と硝石溶液)
bd --> bxc
bxc -->|"-汚れた濾紙とボウル\n+粘土のボウル"| bxd(硝酸カリウム溶液入りのボウル)
bxd -->|"(時間経過)"| bxe(硝酸カリウム入りのボウル)
bxe --> bxf(硝酸カリウムと硫黄入りのボウル)
be -->|"-粘土のボウル"| bxf
bxf -->|"+熱い木炭"| bxg(三酸化硫黄反応)
bxg --> bxh(灰の上の硝酸)
bb -->|"-粘土のボウル"| bxh
bxh -->|"(取る)"| bxi(硫酸入りのボウル)
end
bn ---> bya(硫酸銅入りのボウル)
bf --> bya
bg -->|鍛冶金槌| byb(銅鍋)
byb --> byc(硫酸銅入りの鍋)
bya -->|"-粘土のボウル"| byc
bn --> byd(ダニエル電池アノード)
bh --> byd
byc --> bye(ダニエル電池)
byd --> bye
end
roota -.- bg
ai -.- bh
ag -.- bf

subgraph c [アンテナ]
direction BT
ca[[銅の延べ棒]]

ca -->|延伸板| cb(銅線)
cb ==> cc(短いアンテナ)
cc --> cd(中くらいのアンテナ)
cb --> cd
cd --> ce(長いアンテナ)
cb --> ce
end
roota -...- ca

```
### クラフト先
* [AM受信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-receiver.md)
* [AM送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/AM-transmitter.md)
* [マルコーニレシーバー](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-receiver.md)
* [花火送信機](https://github.com/aya-0p/yah-craft-recipe/blob/main/Marconi-transmitter.md)


### 必要なもの
* 銅の延べ棒
* 細工した鉄
* 糸
* 亜鉛
* 硝石
* 硫黄入りのボウル
* 水入りのボウル
* 紙
* 灰

### 道具
* 延伸板
* [土器系](https://github.com/aya-0p/yah-craft-recipe/blob/main/Cray.md)
* 鍛冶金槌
* ニューコメン系
