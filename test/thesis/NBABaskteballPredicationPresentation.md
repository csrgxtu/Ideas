title: NBA Basketball Predication Presentation
author:
  name: Archer Reilly
  email: 1246506786@qq.com
  url: http://github.com/csrgxtu
output: nbabasketballpredicationpresentation.html
controls: true

--
# NBA篮球预测方法探究

<br/>
<br/>
<center>湘潭大学研究生开题报告</center>

--
<br/>
## 报告人： 李强
## 专业： 计算数学
## 导师： 程戈 教授

<br/>
<br/>
<center>湘潭大学  数学与计算科学学院  2013级</center>

--
### 内容
* 选题依据
* 研究现状
* 研究内容和意义
* 研究方案
* 实验方案
* 工作进展
* 工作进度和安排
* 参考文献

--
### 选题依据
#### 课题来源
本课题来源于参与的"基于轻量虚拟化可信基的可信计算环境构建机制"项目组。

--
#### 研究背景 (一)
篮球是一个团体竞技运动。一个球队比赛成绩好坏和许多因素有关, 如, 运动员的个人技术能力、球队的竞技状态、球队战术策略等等。由于诸多因素的影响，胜负结果显得复杂多变。

--
#### 研究背景 (二)
美国职业篮球联赛（NBA）创办于1946年，已有70年的历史。其已经成为全球范围内最职业化，最市场化，最受关注的联赛。

NBA比赛异常激烈，每场比赛双方球队整体实力非常相近，比赛胜负结果悬念较大，往往在一分钟或者一秒钟内，比赛结果可能发生大变。比如：麦迪的34秒13分的神奇逆转纪录等等...

--
#### 研究背景 (三)
大量的球迷和部分公司热衷与事先预测球队的胜负结果。由于胜负结果与诸多因素有关，而个体对结果的预测基本上是基于主观推断，甚至有球队偏好的影响，缺乏科学性，且预测的准确性较差。

--
#### 指导思想
本课题将使用极大熵，条件随机场等基于统计的学习方法，辅助计算机科学中Hadoop等大数据相关技术实现篮球比赛胜负的分析预测功能。

--
### 研究现状
#### 研究综述
近年来，体育竞技的分析已经演变成为一个重要的领域。大体上，对体育竞技的分析主要分为两个方面，分别为：
* 传统的人为比较分析，视频解说方法

* 简单的统计分析方法

--
#### 传统的比较分析方法
通过人为的视频解说，比赛情况分析进行研究的方法，参考文献[[3](#)],[[4](#)],[[5](#)]

--
#### 简单的统计分析方法
使用一些较简单的描述统计分析方法，如:
* 使用Logistic模型找出主要的影响特征[[6](#)]
* 使用Fisher判别分析[[7](#)]
* 使用主成分分析/聚类分析/相关性分析[[8](#)]
* 使用Bayes模型[[9](#)]
* 使用回归模型[[10](#)]
* Garstka通过动态规划模型预测胜负概率[[11](#)]
* Feifang Hu and James V.Zidek利用权重似然估计对NBA季后赛进行预测[[12](#)]

--
### 研究内容和意义
#### 研究内容（一）
通过对获取的1993-2013赛季20个常规赛技术统计数据进行分析，得出影响比赛结果较为全面的数据特征，利用最大熵模型对大量的特征数据进行权重的计算。

其次，采用幂方法，比赛对手的实力能过反应参赛队的实力，让球队之间相互投票，根据比赛结果的胜负对球队进行实力排名，对实力进行划分够造实力差。

--
#### 研究内容（二）
最后，综合分析影响比赛胜负的主要因素和球队实力的差值，再次通过最大熵原理求出影响比赛结果因素的权重，建立最优条件概率模型。将比赛的最近几场赛事的特征数据的平均值带入最优条件概率模型中。计算出参赛球队获胜的概率，给赛事关注者一个科学比赛预测

--
#### 研究意义
中国的体育彩票市场非常庞大，例如足球，篮球等。众多的球迷，公司投身其中，希望通过彩票市场获取盈利。但是球迷，公司等往往不能对赛事情况做整体判断，通常是使用主观的方法投注。

本研究的意义在于给出一种可行的计算篮球胜负概率的方案，使得球迷及公司有一个投注参考，同时提高篮球胜负预测的准确率。

--
### 研究方案
本课题的研究重点是使用统计学习方法和大数据相关技术对篮球比赛结果进行预测。

* 整理NBA官方网站公布出来的赛事数据

* 使用统计学习方法的算法实现， 在之前整理的赛事数据上进行训练和预测

* 对训练预测结果进行分析，找出主要的影响因素及其合理解释


--
### 实验方案
#### 已有实验条件
内存2GB，硬盘160GB，2.4GHZ Intel I3 CPU的DELL台式机

Ubuntu 14.04 64位操作系统

Java 8.0

Apache Mahout Libaries

--
#### 实验设计方案
* 从互联网上整理有关NBA篮球赛事的数据

* 极大熵及条件随机场的模型构造

* 使用统计学习方法的算法实现， 使用模型在之前整理的赛事数据上进行训练和预测

* 对训练预测结果进行分析，找出主要的影响因素及其合理解释

--
### 工作进展
#### 工作进展情况
* 对国内外篮球博彩预测的调查与综述
* NBA篮球赛事数据的整理
* 研究中使用的算法的编程语言实现
* 极大熵，条件随机场模型的构造
* 模型的训练和预测

--
#### 存在的问题
* NBA赛事数据的不完整性
* 模型训练特征的选取问题
* 模型训练用时超长

--
#### 解决方法
* 继续收集完善数据
* 通过多次实验选取最佳特征
* 更换性能更好的机器或者实现并行的算法

--
### 工作进度和安排
* 2014.07 - 2014.09 参考资料，基本文献，研究综述的整理完善

* 2014.10 - 2014.12 基本数据的整理

* 2015.01 - 2015.04 特征的选取和模型的构造

* 2015.05 - 2015.06 整理所有研究成果并形成文章

--
### 参考文献
[1]Ratnaparkhi A．Maximum entropy models for natural language am—biguity resolution[D]．University of Pennsylvania．1 998．

[2]perrron定理

[8]陈亮,孔靖. NBA2004~2005赛季常规技术统计与比赛胜负关系的研究[J]. 首都体育学院学报,2006,02:85-88.

[9]白银龙,柳景. 2010-2011赛季NBA总决赛进攻技术研究[J]. 云南师范大学学报(自然科学版),2012,03:74-78.

--
### 参考文献
[10]王焕波. 2011-2012赛季NBA总决赛技术统计分析[J]. 德州学院学报,2014,04:85-88.

[11]李林杰,张学东. 影响NBA常规赛胜负的Logistic分析[J]. 统计教育,2008,04:40-41.

[12]潘建武. 对NBA常规赛比赛胜负影响因素及Fisher判别分析[J]. 四川体育科学,2012,05:45-48.

[13]陈建宝,肖林,许世杰,林炳灿. NBA球队战绩影响因素的统计分析[J]. 中国体育科技,2010,06:15-22.

[14]邱胜,段重阳,陈征. NBA季后赛成绩分析及预测:Logistic和Bayes模型[J]. 统计教育,2010,10:46-51+25.
