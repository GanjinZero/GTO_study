# 简介
在这里我们对NLHE的GTO打法进行一些计算，使用的软件是GTO+，涉及的场景都是HU。

# 牌局设定
牌局设定来自NL5, pokerstars.
- SB 0.4BB
- BB 1BB
- Stack 100BB
- rake 4.15%
- 2 Player Cap 10BB

# Size设定
- open 2.5BB
- open at sb
- 3bet ip
- 3bet oop
- 4bet ip
- 4bet oop

# 范围对抗

## OPEN only
OPEN范围:(From pokersnowie)
- UTG: A2s+, K9s+, Q9s+, J9s+, T9s, 55+, ATo+, KJo+, QJo (18%)
- MP: A2s+, K9s+, Q9s+, J9s+, T9s, 22+, ATo+, KTo+, QJo (20%)
- CO: A2s+, K6s+, Q8s+, J9s+, T8s+, 97s+, 87s, 76s, 65s, 54s, 22+, A9o+, KTo+, QTo+, JTo+ (26%)
- BTN: A2s+, K2s+, Q5s+, J7s+, T7s+, 97s+, 85s+, 75s+, 64s+, 54s, 22+, A4o+, K9o+, Q9o+, J9o+, T9o (38%)
- SB: 太复杂，先不考虑

### BB defend (IP)
#### UTG, MP
#### CO
#### BTN

### 后位跟注 (OOP)
#### MP, CO vs UTG
#### BTN vs UTG, MP
#### BTN vs CO
#### SB vs BB

## 3Bet

### 3Bet OOP

### 3Bet IP

## 4Bet
4Bet pot: TT+, ATs+, AQo+, A5s- 

### 4Bet OOP
hero open, villian 3bet, hero 4bet, villian call; hero oop.

### 4Bet IP
hero open, sb/bb 3bet, hero 4bet, villian call; hero ip.

# 翻牌面聚类
一共有22100种翻牌面，为了让人类简单的理解这个游戏。选择一些翻牌面代表这22100个翻牌面。

对于翻牌面，显然有如下的分类方法：
- 单花
- 双花
- 彩虹
- 公对
- 公三条
- 顺子面
- 单高张
- 双高张
- 三高张
