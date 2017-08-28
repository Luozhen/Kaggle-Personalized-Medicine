# 0826
利用TensorFlow构建DNN的基本过程:
- 数据输入
- 构造DNN的结构
- 模型训练并存储

|描述|简介
|数据输入| 利用tf.contrib.learn.datasets.base.load_csv_with_header获取csv文件
|特征构造|tf.contrib.layers.real_valued_column构造输入层的特征维度
DNN分类模型: tf.contrib.learn.DNNClassifier

但是, 即便知道这些, 也还是不知道怎么使用DNN用在比赛上啊啊啊啊......

---

# 0827
因为昨天的构建使用已封装好的函数接口, 完全不知道如何应用于比赛, 又迅速看了篇博客, 跟着写到最后发现原来是构建一个具有两层隐含层的神经网络. 先这样吧, 能构建出个神经网络也是可以滴, 之后再学学其他. 参考[神经网络实例]https://github.com/Luozhen/TensorFlow-Examples
