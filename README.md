# xgboost
1.数据采用的是广泛应用于机器学习社区的MNIST数据集（https://www.kaggle.com/c/digit-recognizer/data）,训练时间较长，预测得到的xgb_submission.csv文件上传到kaggle，看系统评分

2.关于xgboost与GBDT的区别，详见wepon大神的回复：https://www.zhihu.com/question/41354392

注：传统GBDT以CART作为基分类器，xgboost还支持线性分类器，此时xgboost相当于带L1和L2正则化项的逻辑斯蒂回归（分类问题）或者线性回归（回归问题）

