# 基于机器学习的交易欺诈行为识别研究

随着社会经济发展的不断增速，居民消费水平有了实质性提高。在大数据时代下，随着人们消费观念的转变，银行卡这种交易方式更加受到欢迎。在银行卡交易中存在交易欺诈的风险，所以有效识别欺诈行为，并及时采取有效措施是十分重要的。本文针对59万条银行卡持卡人交易行为数据进行描述性统计分析，构建机器学习模型识别交易欺诈行为。首先根据两类交易数据，对多个特征绘制直方图和折线图，分析交易行为之间的差异特征。使用过滤法进行特征工程来选出重要特征，并对其中的类型特征进行向量化处理。将数据集划分为训练集、验证集和测试集，利用随机欠采样将训练集数据进行平衡化，分别建立逻辑回归模型、XGBoost模型和LGBM模型。使用验证集AUC值作为主要指标进行模型评估，比较后得到LGBM模型在预测效果和运行速度方面都是三个模型中最佳的。最后使用测试集对最优模型测试，得到的AUC值达到94.86%。

With the continuous growth of social and economic development, the consumption level of residents has been substantially improved. Bank cards are becoming increasingly popular in the age of big data, as people’s purchasing habits change. Because there is a risk of transaction fraud, it is critical to efficiently identify fraud and implement appropriate countermeasures in a timely manner. This dissertation makes exploratory data analysis of 590,540 cardholder transaction behavior data and builds three machine learning models to detect transaction fraud. First, histograms and line charts of many features are generated based on the two types of transaction data to assess the difference between the two transaction behaviors. To choose the key features, the filtering method is used to perform feature engineering to select important features, and categorical features are vectorized. The data set is divided into training set, validation set and test set, and the training data is balanced using random undersampling. The logistic regression model, XGBoost model, and LGBM model are established respectively. The AUC on the validation set is the primary metric used to evaluate the model. In terms of prediction effect and running speed, the LGBM model outperforms the other two models. Finally, the best model is tested using the test set, and the AUC reaches 94.86%.

### EDA部分的代码
https://www.kaggle.com/code/cccbby/fraud-complete-eda
### 模型建立与预测部分的代码
https://www.kaggle.com/code/cccbby/fraud-models
