# CV-paper-report
Computer Vision paper report
2022.6.22
VAE 变分自编码模型
一种无监督的学习模型，数据集中没有train,test集，故loss函数中包括输入图与重构图之间的残差，还有正则化项两部分。前向卷积神经网络提取图片特征，得到隐变量，转置卷积层得到重构图
