# 转换器

## 流程

1. 实例化（实例化就是一个转换器（Transformer））
2. 调用fit_transform = (x-mean)/std;是一个封装
3. 可以分解为
   1. fit()					计算 每一列的平均值，标准差
   2. transform()      （x-mean）/std 进行最终的转换

# 估计器（sklearn机器学习算法的实现）

在sklearn中,估计器（estimator）是一类实现算法的API

## 用于分类的估计器：

- sklearn.neighbors k- 临近算法
- sklearn.naive_bayes 贝叶斯
- sklearn.linear_model.LogisticRegression 逻辑回归
- sklearn.tree 决策树与随机森林

## 用于回归的估计器：

- sklearn.linear_mode.LinearRegression 线性回归
- sklearn.linear_model.Ridge 岭回归

## 用于无监督的估计器

- sklearn.cluster.KMeans 聚类

## 流程

1. 实例化一个估计器estimator

2.  estimator.fit(x_train,y_train) 计算，调用完毕，模型生成

3. 模型评估：

   1. 直接对比真实值和预测值

      - y_predict = estimator.predict(x_trst)
      - y_test == y_predict

   2. 计算准确率

      - accuracy = estimator.score(x_test,y_test)

      