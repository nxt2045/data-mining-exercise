# 实验结论
## KNN:
1. 精度高，但因为需要存储所有的训练集，占用很大内存，速度比较慢。
2. 模型复杂度主要由 K 的值决定，K 值越小，复杂度越高。
3. 训练准确度随着模型复杂增加而升高。
4. 测试准确率在模型过于复杂和过于简单的时候都比较低。
## Decision Tree:
1. 概念简单，计算复杂度不高，可解释性强，输出结果易于理解。
2. 在相对短的时间内能够对大型数据源做出可行且结果良好的结果。
3. 容易出现过拟合，但通过 max_depth 参数限定决策树深度，可以在一定程
度上避免过拟合。
## Naive Bayes：
1. 无需复杂的迭代求解框架，速度快。
2. 属性之间的独立性假设往往不成立。
3. 由于朴素贝叶斯的“朴素”特点，所以会带来一些准确率上的损失。