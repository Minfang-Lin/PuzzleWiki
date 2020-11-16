---
title: Pentaroll 翻滚吧！拼版
date: 2017-04-16 15:00
author: 叶卡林娜
categories: [Puzzle, 放置类谜题]
tag: [Western Puzzles]
toc: true

---

本题型由Riad Khanmagomedov在2009年4月的IPST中设计。在这之后的OAPC8中，Serkan Yürekli也用到了此题型。

## 规则

题目中给出了一些五格拼板，你需要把它们全部放入盘面中。任意两块拼版不可相邻，包括对角方向。在盘面中所给的向某一侧翻转一次，直立在盘面上后，从上方往下看被拼板遮盖住的部分如粗线标注。所给的拼板可以旋转或者翻转，您需要确定的是每块拼板竖起前所放置的位置。周围的提示数表示竖起前该行或列中拼板所占格数。

Given pentomino set was lying in the grid, without touching each other even at a point. Then each pentomino was rolled over one edge. The grid presents the top view after rollings. The numbers outside the grid indicate the number of pentomino pieces in the corresponding direction. Given pentominoes may be rotated and/or mirrored. Find the initial locations of pentominoes.

It is not important whether a pentomino can or cannot physically stand on the rolled face; and the rollings should be considered as virtual movements, ignoring the possible during collisions the movement.

![Pentaroll例题，作者：Serkan Yürekli](/images/pentaroll_e.png)
![Pentaroll例题解答](/images/pentaroll_a.png)

## 参考资料

> - [Serkan Yürekli's Blog](https://yureklis.wordpress.com/2012/05/31/pentaroll/)