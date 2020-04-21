## Programming Language
- jieba分词中的generator:
  - [Python yield 使用浅析](https://www.runoob.com/w3cnote/python-yield-used-analysis.html)
- TorchText中新的API
  - [Experimental datasets in torchtext 0.5.0 release](https://github.com/pytorch/text/issues/664)
- python中的@：
  - [谈谈python修饰器](https://www.jianshu.com/p/ab702e4d4ba7)

## 待整理文章
- [Batch Normalization 与Dropout 的冲突](https://www.cnblogs.com/cbattle/p/9475361.html)
- [BN和Dropout在训练和测试时的差别](https://zhuanlan.zhihu.com/p/61725100)

## 推荐系统
- 现在的推荐系统一直推荐已经购买的商品也不是完全不可以，还是要看商品的种类，如果是零食，还是要推荐零食的，如果是汽车，就应该推荐汽车的周边了

## 系列文章(TBC)
- 机器学习中的优化方法：[ref](https://blog.csdn.net/sunflower_sara/article/details/100558156)
- 从EM到CRF
- Boost系列
- github使用
- Leetcode系列
- 推荐系统handbook

## 杂感
- word embedding很多还只是“语义相近”，一些从属信息怎么解决呢？怎么知道自动知道“水果”和“苹果”的关系呢？生成对抗？多种任务自编码？那么编码完又如何把特定的信息提取出来呢？
- CR中的mention还是非常低效的枚举，更应该让神经网络进行自动分辨，但是mention的嵌套问题如何解决呢？NER中的模型都发展到什么程度了？
- 10 * 10 的全连接，要100个参数，10 * 2+2 * 10的全连接，要40个参数，这两个网络的表达能力一样么？
- 突发奇想，然后发现，晚了两年。[LINK](https://openreview.net/forum?id=B1Yy1BxCZ)
- 能否将电流/水流模型的一些特征融入到网络呢？

## 《深度学习》要点备忘
- 平方L2范数容易求导，但是在原点附近增长缓慢；当机器学习问题中零和非零元素之间的差异非常重要时，通常会使用L1范数；L1范数经常作为表示非零元素数目的替代函数。
- 并非所有的对角矩阵都是方阵。长方形的矩阵也有可能是对角矩阵。


-----------------------------------------------------------------------------------------

<div style="text-align:center;">
This page maintained by @ <a href="https://dasepeng.github.io/">DaSEPeng</a>, 	
<a href="https://github.com/DaSEPeng/Miscellaneous-Notes/">View on GitHub</a>
</div>
