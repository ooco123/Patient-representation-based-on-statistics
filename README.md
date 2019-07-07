# Patient-representation-based-on-statistics
基于MIMICIII临床数据库，对传统基于简单统计特征的患者表示进行改进，使用遗传算法获取重要统计特征对患者时间序列进行表示，基于StackIng的模型Super Learner预测患者进入ICU24时后的死亡率，与包括疾病严重程度评分以及基于简单统计特征的患者表示构成的baseline进行对比，AUC平均提高0.05。

代码中包括从MIMICIII（Postgresql）数据库中提取数据、数据预处理、嵌入交叉验证的遗传算法特征选择、基于Stacking的模型集成以及与baseline的对比等部分。