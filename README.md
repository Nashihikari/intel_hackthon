## 针对压缩包中的各个文件进行一些说明

#### "基于分类算法的淡水质量预测.docx" 是报告正文。

"data_preprocess_10w.ipynb" 是最初使用SVM在10万数据量上进行训练和测试的代码。

"data_preprocess_10w_test_100w_svm.ipynb" 是使用10万数据量训练的模型在100万数据量的测试集进行测试的代码。

"xgb_400w_without_oversample.ipynb" 使用XGBoost进行训练的模型，但没有经过上采样，效果一般。

#### "xgb_400w_last.ipynb" 使用是经过多轮优化（包括上采样）的最终结果的代码。测试可以使用该代码。

requirements.txt 是所依赖的库， 可以使用 pip install -r requirement.txt来安装
