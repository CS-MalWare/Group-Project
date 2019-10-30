# 这个文件夹包含所有游戏的设定内容
---


## 一、人物在基础属性值包含:  

| 攻击力 | 防御力 | 体力 |
|:-----|:-----|:-----|
|能够直接增加玩家造成的伤害|能够直接降低玩家受到的伤害|与玩家能够打出的卡片数量直接挂钩|




## 二、特殊词语描述说明：
### 属性:
不同的怪物属性分成
- 金
- 木
- 水
- 火
- 土
- 混沌
通过攻击时附加属性,可以对克制属性的怪物造成更高伤害,其中,五种基本属性按照五行相克,混沌属性不受任何克制
### buff 类
### (一）永久类（效果不会受回合数影响）
1. 力量(strength)： 每有一点力量，卡牌造成的伤害数值加一 
- every one strength makes the damage caused by cards increase one
2. 灵巧(dexterity)： 每有一点灵巧，从防御牌中获得的格挡加一
- every one dexterity makes the block caused by cards increase one
3. 闪避(dodge)： 将x次伤害转变成1 
- turn the next damage taken into 1 for x times 

### (二)持续类（效果受回合数影响）
4. 振奋(excite)： 下回合多抽一张牌，持续x个回合  
- draw one more card in the next turn, lasting for x turn 
5. 幽灵化(intangible)： 将受到的伤害转化为1， 持续x个回合 
- turn the damage taken into 1, lasting for x turn

### debuf 类
### （一）永久类
1. 迟钝（languid）： 每有一点迟钝，卡牌造成的伤害数值减一 
- every one languid makes the damage from cards decrease one
2. 迟缓（sluggish）：每有一点迟缓，卡牌获得的格挡值减一 
- every one sluggish makes the block from cards decrease one

### （一）持续类
3. 脆弱(vulnerable): 受到的伤害增加50%， 持续x个回合 
- increase the damage taken from enemies by 50%, lasting for x turn 
4. 虚弱（week）：造成的伤害减少25%，持续x个回合
- decrease the damage from cards by 25%, lasting for x turn
5. 腐朽(erode)：从卡牌中获得的格挡数值减少1/3，持续x个回合
- decrease the block from cards by 1/3, lasting for x turn 
6. 缴械 (disarm)：无法使用攻击牌， 持续x个回合
- disable the target to use attack cards, lasting for x turn
7. 沉默（slience）：无法使用技能牌， 持续x个回合
- disable the target to use skill cards, lasting for x turn
8. 中毒 (posion)：在每个回合开始时，扣除x点HP
- at the start of each turn, take x damage
9. 流 血(blooding): 每次受到伤害时候，受到x点伤害
- every time when attacked to lose Hp, take x damage
10. 眩晕(stun): 无法行动，持续x回合
- can't do anything, lasting for x turn

### 普通
1. 消耗(exhaust)：打出后，在这局游戏中把这张牌移除卡组
- after played, remove this card from the deck, lasting only for this battle
2. 熟练 (proficient)：打出后，在在这局游戏中，这张牌体力消耗值减一
- after played, the cost of this card decrease by 1, lasting only for this battle
3. 无法打出 (unplayable)： 无法使用这张牌
- can't play this card
4. 虚无(ethereal)：在回合结束时候，消耗这张牌
- at the end of this turn, exhaust this card
5. 固有(innate)：在战斗开始的第一个回合，抽取这张牌
- at the first turn of battle, draw this card

### 职业相关
（一） 战士

（二） 法师


### 三、诅咒牌（通常污染卡组，给player造成麻烦）
1. 粘液(mucus)（1） ： 消耗
- exhaust after palyed
2. decay(unplayable) : 回合末，收到两点伤害 
- at the end of turn, take 2 damage
3. amnesia(unplayable): 回合末，随机消耗一张牌 
- at the end of term, exhaust one random card
4. doubt(unplayable): 回合末，获得一回合虚弱 
- at the end of term, gain 1 weak
5. writhe(unplayable): 固有 
- innate
6. normality(unplayable)：当这张卡在手牌中时候，每回合至多打出3张牌 
- when this card in hand, you can't play more than 3 cards in one turn
7. worry(unplayable): 虚无
- ethereal
