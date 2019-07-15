# LFW 使用手册
首先进入[官网](http://vis-www.cs.umass.edu/lfw/index.html) 

### 阅读论文
1. [Labeled Faces in the Wild: A Database for Studying
Face Recognition in Unconstrained Environments](http://citeseer.ist.psu.edu/viewdoc/download;jsessionid=0004A606F5D7E280D472D654513BD96C?doi=10.1.1.122.8268&rep=rep1&type=pdf)
1. [Labeled Faces in the Wild: Updates and New Reporting Procedures](http://vis-www.cs.umass.edu/lfw/lfw_update.pdf)
### LFW结果分类
1. Unsupervised：无监督；

1. Image-Restricted, No Outside Data：图像受限，无外部数据；

1. Unrestricted, No Outside Data：无限制，无外部数据；

1. Image-Restricted, Label-Free Outside Data：图像受限，无标签的外部数据；

1. Unrestricted, Label-Free Outside Data：无限制，无标签的外部数据；

1. Unrestricted, Labeled Outside Data：无限制，标记的外部数据（我们测试大多属这种情况，利用外部数据训练，然后用LFW进行测试）；

1. Human Performance：人为判断。
下载数据集，对数据集的结构有初步的了解

代码编写
