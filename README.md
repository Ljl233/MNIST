# 手写数字识别
1. 朴素贝叶斯实现手写数字识别 正确率 0.8436
2. 3层网络的识别 正确率 0.9339
> 第2个方法中，输出层使用了sigmod激活函数，使用softmax后，正确率为0.939
> 第2个方法中，激活函数换成relu后，正确率为0.9827 ，在此基础上，把x_train,y_train归一化时的255改成100，正确率会到0.9832
> 第2个方法中，不进行归一化（normalization），激活函数时relu时，正确率很低，改学习率也没啥用，但同样不归一化，激活函数为sigmoid的时候，正确率为0.9234







##### 欢迎交流
