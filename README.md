# 汽车价格预测与竞品分析

## 项目简介


中国的一家汽车公司渴望进入美国市场，他们计划在那里设立制造工厂，并在当地生产汽车，与其他同行竞争。他们希望了解影响美国市场汽车定价的因素，以及主要竞品有哪些。

**本项目主要解决以下两个问题：**

（1）	根据各种汽车属性预测汽车价格，了解影响汽车市场定价的因素。

（2）	对于指定的车型，通过聚类分析找到其竞品车型。

## Jupyter notebook 中包含:

1- 数据基本信息

2- 数据清洗与可视化

3- 数据准备：特征工程 & 数据缩放

4- **汽车价格预测模型的建立（Lasso/RFR/SVR）**

5- **竞品分析（PCA 降维与 K-means 聚类）**

## 复现说明：

1. 运行环境：python 3.11.7

2. 依赖包的版本：

       numpy==1.26.4

       pandas==2.2.3

       matplotlib==3.8.0

       seaborn==0.12.2

       joblib==1.2.0

       sklearn==1.2.2

3. 数据准备：

    - 下载数据集： [CarPrice_Assignment](https://www.kaggle.com/datasets/shaistashaikh/carprice-assignment/data)

    - 将数据集保存为 CarPrice_Assignment.csv

4. 代码实现：运行 Data_Analysis.ipynb 即可

