# K-means原理

![](http://img.wangzun233.top/%E9%BB%91%E9%A9%AC%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A015_1.png)

## 步骤

![](http://img.wangzun233.top/%E9%BB%91%E9%A9%AC%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A015_2.png)

# API

![](http://img.wangzun233.top/%E9%BB%91%E9%A9%AC%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A015_3.png)

# 案例：K-means对用户聚类

- k = 3

1. 
2. 

# 轮廓系数

- 如果b_i > a_i；趋近于1效果最好
- b_i < a_i 效果不好
- 轮廓系数值【-1,1】
- 趋近于1代表内聚度和分离度都相对较优

![](http://img.wangzun233.top/%E9%BB%91%E9%A9%AC%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A015_4.png)

## API

![](http://img.wangzun233.top/%E9%BB%91%E9%A9%AC%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A015_5.png)

# 总结

- 特点：采用迭代式算法，直观易懂并且非常实用
- 缺点：容易收敛到局部最优解（多次聚类）

# 场景

- 没有目标
- 聚类-》分类



# 2020.11.29