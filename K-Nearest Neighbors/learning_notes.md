## scikit-learn
### Simple and efficient tools for data mining and data analysis
![](https://github.com/guangfuhao/ImageCache/raw/master/deeplearning/sk-learn.png)
https://scikit-learn.org/stable/index.html<br>
scikit中的make_blobs方法常被用来生成聚类算法的测试数据<br>
from sklearn.datasets import make_blobs<br>
sklearn.datasets.make_blobs(n_samples=100, n_features=2,centers=3, cluster_std=1.0, center_box=(-10.0, 10.0), shuffle=True,random_state=None)<br>
n_samples:表示数据样本点个数,默认值100<br>
n_features:表示数据的维度，默认值是2<br>
centers表示类别数,默认值是3<br>
cluster_std：数据集的标准差，浮点数或者浮点数序列，默认值1.0,<br>
center_box：中心确定之后的数据边界，默认值(-10.0, 10.0)<br>
shuffle ：洗乱，默认值是True<br>
random_state:随机生成器的种子<br>
