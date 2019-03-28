> 感谢-liujm7

> GITHUB CODE
- [https://github.com/liujm7/RecommendSystem](https://github.com/liujm7/RecommendSystem)
    ```
    推荐系统重构版java
    1.Baseline: 实现了基准线预测,评分预测和topN预测均可
    2.MeanFilling:实现了全局均值插值法，用户均值插值法和商品均值插值法 ,评分预测
    3.UserKNN:基于用户的协同过滤KNN算法，实现了评分预测和topN预测
    4.ItemKNN:基于物品的协同过滤KNN算法, 实现了评分预测和topN预测
    5.MatrixFactorization:基本矩阵分解协同过滤，实现了sgd的评分预测和topN预测
    6.BiasedMatrixFactorization:偏差性矩阵分解，实现了sgd的评分预测和topN预测
    7.AlternatingLeastSquares:继承MatrixFactorization，实现了als的评分预测
    8.SVDPlusPlus:SVD++分解，综合考虑用户评分偏差、商品评分偏差和整体评分均值，实现了sgd的评分预测和topN预测
    ```
- [https://github.com/liujm7/Recommend](https://github.com/liujm7/Recommend)
    ```
    java推荐算法库
    使用java语言重新实现一部分python推荐方法
    UserBasedCF:基于用户协同过滤
    ItemBasedCF:基于商品协同过滤
    ModelCF:基于模型协同过滤 目前不成熟
    CBF:基于内容的推荐
    HybridCbfCF:基于内容和协同过滤的混合推荐
    BaselinePredictor: 基准预测的推荐
    SVD:结合基准预测的svd推荐重实现
    备注:实验数据 movielens
    ```
> 实验数据 movielens
- [http://files.grouplens.org/datasets/movielens/ml-100k/](http://files.grouplens.org/datasets/movielens/ml-100k/)

> DEMO-说明
- core.collaborativeFiltering.SVDPlusPlus （SVD++分解，综合考虑用户评分偏差、商品评分偏差和整体评分均值，实现了sgd的评分预测和topN预测）