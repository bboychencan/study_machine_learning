# Time Series Analysis

大学的时候时间序列分析学的烂到爆，什么都不知道，工作中多次遇到时间序列的问题，只会套一些模型，这次希望能够梳理一下，真正学懂，似乎也没那么难。
首先捋一下定义，然后常见的问题，常见的模型等等。

大学的时候学怕了，把这些东西想的太难，可是自从刷leetcode上瘾以后，我发现那些以前觉得难的算法和数据结构理解以后都不过如此，而且练得多了之后简直就跟喝水一样自然。

尤其是数学这一块，很长时间不碰的话，看到数学公式就怵，可是自从硬着头皮刷了统计机器学习之后，发现也没那么难，那些看起来很复杂的公式无非就是求和、求积，求导，都是很简单的数学概念。当掌握最简单的一两个模型，比如LR，决策树以后，发现这些东西都是纸老虎。

包括重新学习了“统计机器学习方法”以后，我觉得那些机器学习算法也不过如此，没啥难度，所以就着这个劲头，我打算把那些之前学过的、用过的、接触过的模型全部梳理一遍.

# Models

## AR autoregression 自回归模型
自回归模型描述当前值与历史值之间的关系，用变量自身的历史时间数据对自身进行预测。

Xt = a1Xt-1 + a2Xt-2 + ... + apXt-p + ut

如果随机扰动ut是白噪声，则可以称为是一个纯AR过程

自回归模型首先要确定一个阶数p，表示用几期的历史值来预测当前值

自回归模型有很多的限制：

（1）自回归模型是用自身的数据进行预测

（2）时间序列数据必须具有平稳性

（3）自回归只适用于预测与自身前期相关的现象（时间序列的自相关性）




## MA 滑动平均模型

## ARMA

## ARIMA

