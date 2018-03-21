#  天池工业AI大赛-智能制造质量预测
天池工业AI大赛-智能制造质量预测思路和代码解读，以复赛为例。
文件说明：
1. 思路介绍 介绍整体的思路
2. fusai_selectfeature_fujianguo.ipynb 预测测试集a时的特征选择程序，以及前期预测测试集b时的特征选择程序
2. train_and_testa.ipynb 预测测试集b时的特征选择程序
3. gbdt_train_new.ipynb 根据选择的特征，利用gbdt算法进行模型训练和预测
4. [new] fusai_answer_a_20180127.csv 测试集a答案
5. nullcount.xlsx 确实值统计情况
6. resultb_gbdt_new5_200.csv 测试集b的预测结果，mse为0.02521，最终排名为28名
7. 训练_20180117-备份.xlsx  原版的训练集（数据较大，没有上传）
8. 训练_20180117.xlsx  删除异常样本的训练集（数据较大，没有上传）
9. 测试A_20180117.xlsx 测试级a数据
10. 测试B_20180117.xlsx 测试级b数据（数据较大，没有上传）
