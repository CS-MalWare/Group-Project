# 这个文件夹包含所有游戏的设定内容
---
## 卡牌稀有度描述
common(白色)
rare(蓝色)
epic(紫色)
legendary(金色)

## 一、人物在基础属性值包含:  

| 攻击力 | 格挡 | 体力 |
|:-----|:-----|:-----|
|增加一次攻击的伤害|格外的格挡伤害|与玩家能够打出的卡片数量直接挂钩|

## 伤害的建议范围
- 1费: 5
- 2费: 12
- 3费: 21
- 4费: 无

## 二、特殊词语描述说明：
### 属性:
不同的怪物属性分成
- 金
- 木
- 水
- 火
- 土
- 混沌  
> 通过攻击时附加属性,可以对克制属性的怪物造成更高伤害,其中,五种基本属性按照五行相克,混沌属性不受任何克制

### buff 类
### (一）永久类（效果不会受回合数影响）
1. 力量(strength)： 每有一点力量，卡牌造成的伤害数值加一 
- every one strength makes the damage caused by cards increase one
2. 灵巧(dexterity)： 每有一点灵巧，从防御牌中获得的格挡加一
- every one dexterity makes the block caused by cards increase one
3. 闪避(dodge)： 将x次伤害转变成1 
- turn the next damage taken into 1 for x times 
- 人工制品(artifact)：抵消下x次受到的debuff

### (二)持续类（效果受回合数影响）
4. 振奋(excite)： 下回合多抽一张牌，持续x个回合  
- draw one more card in the next turn, lasting for x turn 
5. 幽灵化(intangible)： 将受到的伤害减少50%， 持续x个回合 
- reduce 50% damage, lasting for x turn

### debuf 类
### （一）永久类
1. 迟钝（languid）：每有一点迟钝，卡牌造成的伤害数值减一 (现已使用-1力量替代)
- every one languid makes the damage from cards decrease one
2. 迟缓（sluggish）：每有一点迟缓，卡牌获得的格挡值减一 (现已使用-1敏捷替代)
- every one sluggish makes the block from cards decrease one

### （一）持续类
3. 脆弱(vulnerable): 受到的伤害增加50%， 持续x个回合 
- increase the damage taken from enemies by 50%, lasting for x turn 
4. 虚弱（week）：造成的伤害减少25%，持续x个回合
- decrease the damage from cards by 25%, lasting for x turn
5. 腐朽(erode)：从卡牌中获得的格挡数值减少1/3，持续x个回合
- decrease the block from cards by 1/3, lasting for x turn 
6. 缴械 (disarm)：攻击时候有33%时候，伤害变为1， 持续x个回合
- 

8. 中毒 (posion)：在每个回合开始时，扣除x点HP
- at the start of each turn, take x damage
9. 流血(blooding): 每次受到伤害时候，受到x点伤害
- every time when attacked to lose Hp, take x damage
10. 眩晕(stun): 无法行动，持续x回合
- can't do anything, lasting for x turn

### 普通
1. 消耗(exhaust)：打出后，在这局游戏中把这张牌移除卡组
- after played, remove this card from the deck, lasting only for this battle
2. 熟练 (proficient)：第二次及以上打出这张牌时候，获得额外效果
- gain extra effect after played multiple times
4. 虚无(ethereal)：在回合结束时候，消耗这张牌
- at the end of this turn, exhaust this card


### 职业相关
（一） 战士

（二） 法师



