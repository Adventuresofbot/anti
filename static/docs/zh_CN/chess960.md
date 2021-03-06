# ![960](https://github.com/gbtami/pychess-variants/blob/master/static/icons/960.svg) 菲舍尔任意制象棋 (Chess960)

菲舍尔任意制象棋，是由前西洋棋世界冠军鲍比·菲舍尔（Bobby Fischer）在以不违反原先西洋棋的逻辑及平衡下，将固有体系完整地置入一个更广阔的大体系中为前提，提出了一种西洋棋变体。他认为这种棋可让棋手不再背颂复杂的布局变例，而单纯较量计算能力。

原先的西洋棋可以视为960种变化中的一种。

## 规则

棋子的初始排列顺序可以随机产生，但必须遵循下列原则：

* 黑白双方的棋子必须呈对称排列。
* 各方的两枚主教不可位于在同色格。
* 各方的两枚城堡只能位在国王的两侧。
* 士兵必须位于第二、第七横线。
* 包括西洋棋的正统排列方式，棋盘初始排列一共有960种。

任何一种排列都可进行王车易位，条件如同正统规则：王车之间不得有棋子；王车不得先移动过；王被将军时不能易位；王移动时经过或到达的格子不能是对方攻击的范围。

不论城堡和国王的初始位置在哪里，王车易位后国王城堡的位置就如同传统西洋棋。
当王与a线方向的车易位时，王移到c1 (c8)，车到d1 (d8)；当与h线方向的车易位时，王到g1 (g8)，车到f1 (f8)。
棋子的兵种、着法和普通西洋棋规则相同。

## 策略

正统西洋棋的战术和战略大致适用，但由于开局不固定，因此正统开局通常不适用。

可以看看visualdennis的[https://nine-sixty.netlify.app/](https://nine-sixty.netlify.app/)以更了解这个游戏。