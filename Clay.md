```mermaid
flowchart BT

subgraph a [焼く前の土器]
direction BT
aaa(粘土)
aab(濡れた粘土のボウル)
aac(濡れた粘土の皿)
aad(濡れた中空の粘土球)

aba(2つの粘土の塊)
abb(濡れた大きな粘土のボウル)
abc(濡れた粘土盤)
abd(濡れた大きな粘土の皿)

aca(3つの粘土の塊)
acb(濡れた粘土の壺)

aaa -.- aba
aaa -.- aca


aaa ---> aab
aab --> aac
aac --> aaa
aaa -->|"-石\nナイフ\n+石"| aad

aba --> abb
abb --> abc
abc --> abd
abd --> aba

aca <--> acb
end

subgraph b [焼いた土器]
direction BT
ba(粘土のボウル)
bb(粘土の皿)
bc(中空の粘土球)
bd(大きな粘土のボウル)
be(粘土盤)
bf(大きな粘土の皿)
bg(粘土の壺)
end
a -->|"かまど(ふいご不要)"| b
```
