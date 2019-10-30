# 这个文件夹包含所有游戏的设定内容
---


## 一、人物在基础属性值包含:  

| 攻击力 | 防御力 | 体力 |
|:-----|:-----|:-----|
|能够直接增加玩家造成的伤害|能够直接降低玩家受到的伤害|与玩家能够打出的卡片数量直接挂钩|




## 二、特殊词语描述说明：
### buff 类
### (一）永久类（效果不会受回合数影响）
1. 力量(strength)： 每有一点力量，卡牌造成的伤害数值加一
2. 硬化(dexterity)： 每有一点硬化，从防御牌中获得的格挡加一
3. 闪避(dodge)： 将x次伤害转变成1

### (二)持续类（效果受回合数影响）
4. 振奋(excite)： 每有一点振奋，下回合多抽一张牌，持续x个回合
5. 幽灵化(intangible)： 将受到的伤害转化为1， 持续x个回合

### debuf 类
### （一）永久类
1. 迟钝（languid）： 每有一点弱化，卡牌造成的伤害数值减一
2.    ：每有一点弱化，卡牌获得的格挡值减一

### （一）持续类
3. 脆弱(vulnerable): 受到的伤害增加50%， 持续x个回合
4. 虚弱（week）：造成的伤害减少25%，持续x个回合
5. 腐朽(erode)：从卡牌中获得的格挡数值减少1/3，持续x个回合
6. 缴械 (disarm)：无法使用攻击牌， 持续x个回合
7. 沉默（slience）：无法使用技能牌， 持续x个回合
8. 中毒 (posion)：在每个回合开始时，扣除x点HP
9. 流 血(blooding): 每次受到伤害时候，受到x点伤害

### 普通
1. 消耗(exhaust)：打出后，在这局游戏中把这张牌移除卡组
2. 熟练 (proficient)：打出后，在在这局游戏中，这张牌体力消耗值减一
3. 无法打出 (unplayable)： 无法使用这张牌
4. 虚无(ethereal)：在回合结束时候，消耗这张牌
5. 固有(innate)：在战斗开始的第一个回合，抽取这张牌
 
### 职业相关
（一） 战士

（二） 法师


### 三、诅咒牌（通常污染卡组，给player造成麻烦）
1. 粘液(mucus)（1） ： 消耗
2. decay(unplayable) : at the end of term, take 2 damage
3. amnesia(unplayable): at the end of term, exhaust one random card
4. doubt(unplayable): at the end of term, gain 1 weak
5. writhe(unplayable): innate
6. normality(unplayable)： when this card in hand, you can't play more than 3 cards in one turn
7. worry(0): ethereal
