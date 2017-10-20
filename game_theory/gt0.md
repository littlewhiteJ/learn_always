# 多种纳什均衡分析方法
考虑帕累托效用
风险占优
纳什积

 严格纳什均衡：给定对手不偏离时 我方单独偏离时 收益减少
风险占优评估：
两种方法
- 假定对方选两者的概率都是1/2
- 给定对方不偏离而自己偏离的减少 减少更大的风险占优

纳什乘积更大的风险占优

聚点均衡 谢林
从博弈参与者的个人特点出发
文化习俗。。。。
没啥数学
赌徒分钱
写下自己的钱 总和过多就谁都得不到钱
构成纳什均衡

严格混合策略：所有赋予正的概率 不可以给零概率

抗共谋均衡
多人博弈没有多个人愿意共谋进行效率的提升

完美均衡（颤抖手完美均衡）
允许所有参与者都可能犯错误时也是均衡
- 抗颤抖的--犯错误的概率很低

每个人的策略都是抗颤抖的->完美均衡
| （1，1）    |  （0，0）   |
| -------- | -------- |
| （0，0）    |   （0，0）  |
完美均衡
任何一个颤抖手完美均衡 必然排除弱劣策略
因为弱劣策略不抗颤抖
用颤抖手完美均衡排除很多纳什均衡（尤其在重复博弈中）

二人有限博弈中：不含弱劣策略的均衡都是颤抖手完美均衡

适当均衡（完美均衡的加强）
**任何有限博弈都存在适当均衡**
错误越大 出错误的概率越低

最大最小值和最小最大值
防人之心不可无
基于安全的考虑

最大最小策略
i先行动 其他人害他 然后找个最大的
总想着别人要害他 然后反其道而行之
最大最小值

最小最大值
其他人先行动 i找个最大值 别人再害他

最小最大值 >= 最大最小值
若该博弈存在纯策略纳什均衡 则参与者在纯策略纳什均衡中获得收益大于最小最大值大于最大最小值
合作和报复
别人报复时只能获得最小最大收益/最大最小收益

混合策略中的最大最小值和最小最大值
混合策略下的最大最小值不一定等于其在纯策略下的最大最小值
两人博弈中混合策略的最大最小值等于最小最大值

### 矩阵博弈==双人零和博弈
常和博弈 两人收益之和为常数
零和博弈中
行参与者最大化最小值
最大最小策略==安全策略
对列参与者刚好相反
最小最大化行参与者的收益

鞍点：某一元素是行最小元素 列最大元素（矩阵博弈中）
每一个鞍点都是一个纳什均衡
鞍点恰好是行参与者的最大最小策略
恰好是列参与者的最小最大策略
alpha-beta pruning

双人零和博弈：鞍点 既稳定 又安全
纳什均衡只刻画了稳定性
而鞍点。。。

最大最小值 == 最小最大值 -> 有鞍点
矩阵的所有鞍点给参与者的utility是一样的

考虑混合策略的矩阵博弈
矩阵博弈一定存在混合策略纳什均衡








