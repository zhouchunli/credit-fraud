1.此处的数据为部分样本数据  
2.其中Class为分类数据，在284807 笔交易中，一共有 492 笔是欺诈行为。样本分布极不平衡  
3.通过train_test_split划分训练和测试数据  
4.创建逻辑回归分类器，进行模型训练  
5.将预测结果与测试集的结果进行比对  
6.将精确率 - 召回率进行了可视化呈现  

因为考虑到评价指标是f1，此处样本分布极不平衡，提高f1的办法在于同时提高精确率和召回率的值，此处用到class_weight参数，进行调优，提高f1的值
