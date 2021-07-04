# Deep Learning(深度学习)

*Acknowledgement:* 本课程是根据 CMU 11-785 Introduction to Deep Learing 来设计.

## 课程简介

主要是对深度学习模型的入门学习，包括MLP, CNN,  RNN, LSTM, 以及深度生成模型，玻尔兹曼机.

### 预备知识

- 线性代数，前置课程.
- 多元微积分，概率论的前置课程.
- 概率论与数理统计，前置课程
- 机器学习: 不是必要的，可以阅读 [Stanford CS229 Machine Learing](http://cs229.stanford.edu/) 讲义来补机器学习的知识.
- Pytorch，参考[官网教程](https://pytorch.org/tutorials/).

### 学习形式

- 课程主页为[CMU 11-785 20FA](http://deeplearning.cs.cmu.edu/F20/index.html)，有科学上网条件的可以使用主页中的链接观看视频，也可以在[bilibili](https://www.bilibili.com/video/BV1B5411G7Je?p=1)上学习，课程内容不懂得可以讨论，阅读主页reading部分的论文或者看recitation部分的材料.
- 除了基本的11-785课程内容学习，每周还会有论文研习部分（1-2篇/周），相关论文的主题为课程基本内容的扩展，每周末将会组织4位学员进行20分钟的论文综述汇报，报告人顺序待定，报告具体时间段，结合学员具体情况来定。
- 阅读学术论文方法论的参考资料：
  - [Andrew Ng(吴恩达)关于机器学习职业生涯以及阅读论文的一些建议](https://mp.weixin.qq.com/s/83V--4IdtOJ4pP-muEiUVw)
  - [学术论文阅读与写作](https://bicmr.pku.edu.cn/~wenzw/paper/read-paper-wenzw.pdf)

##### 课程作业：

- 原课程共有4次课程作业，每次作业共有两个part，其中part1一般是代码实现，而part2一般是将part1的代码在kaggle竞赛平台进行测试打榜.
- 报告完之后需要各位交上不含数据的源代码，课程负责人将进行代码检查，并且根据完成情况给分.
- 课程材料可能需要科学上网，因此，作业材料会被统一上传到百度云.
- 在完成课程作业后，直接用Autograder（见课程作业说明）进行本地测试，不用管Autolab等信息，那是CMU校内服务器.
- 主页中的recitation可以理解为助教习题课，可以选择性的观看.
- 除了11-785 的课程作业，还需要**每位参与课程的成员**提交当周的论文阅读报告，可以以PPT或者Beamer的形式进行总结，可以从这几方面进行总结：
  - 该论文是为了解决什么问题；
  - 为了解决这个问题，前人采取了哪些手段，有哪些缺点；
  - 本论文提出了什么手段来解决这个问题；
  - 找得到相关的开源实现吗？找得到就跑一跑，看看效果如何；
  - 如果是网络结构类，请简要描述网络的结构层次，如果是算法类，请描述是用什么办法来求解这个算法的；
  - 深入思考论文有哪些地方是有问题并且待改进的，分条陈述。

##### 课程安排：

| DATE |                           Homeworks                           | Papers |
| :---------------: | :------------: | :---------------: |
| 第一周 | [hw0](https://pan.baidu.com/s/15PKGnyyN-tmrrRFZ32hy3A)，提取码：pbw6，Self-Taught，hw0不用交<br/>[hw1, part1 ](https://pan.baidu.com/s/1uUwlqTE-rebrgbdyr2J73A)，提取码：8sfh | [Gallant (1990)](https://www.ling.upenn.edu/courses/Fall_2007/cogs501/Gallant1990.pdf) |
| 第二周 | [hw1, part2](https://pan.baidu.com/s/1_s6sFAxWYjfwF5Hf2tMIMA) ，提取码：mk0n，hw1 deadline | [Bianca Zadrozny et al.(2003)](https://hunch.net/~jl/projects/reductions/costing/finalICDM2003.pdf) |
| 第三周 | [hw2, part1 ](https://pan.baidu.com/s/1_O_AHZu8s19BypAaZqqlxQ)，提取码：kczy |  |
| 第四周 | [hw2, part2](https://pan.baidu.com/s/16LYxM7u38LhQMK49Wb8sYg) ，提取码：ghkh，hw2 deadline |  |
|    第五周    |  |  |
| 第六周 |  |  |
| 第七周 |  |  |
| 第八周 |  |        |
|           |                                                              |  |



##### 作业说明

1. **<u>作业缴交形式</u>**：**只需要交代码文件**，不需要上交数据，打包为zip文件，邮件发送到到：scaudatahub_ds_center@outlook.com，邮件主题格式同下面的作业命名格式，缴交日期是在课程安排里面的**正常缴交截止日期的中午十二点**之前，
2. **<u>邮件主题命名格式</u>**：采用英文命名，具体格式为：**SCAUDataHub\_名字\_科目\_课程时间\_hw+作业第几次**，，例如：张三机器学习2021年夏季的第一次作业，其对应的主题格式即为SCAUDataHub_ZhangSan_DeepLearning_21SU_hw1，若出现重名到时候再处理.
3. **<u>作业命名格式</u>**：采用英文命名，具体格式为：**名字\_科目\_hw+作业第几次**，例如：张三深度学习2021年夏季的第一次作业，其对应的作业附件格式即为SCAUDataHub_ZhangSan_DeepLearning_21SU_hw1.zip，若出现重名到时候再处理.
4. <u>**考核形式**</u>：本次的考核内容即为4次作业和8次论文阅读报告，其中4次作业占60分，每次15分，而8次论文阅读报告为40分，每次5分，最后通过综合表现进行评价排名，并以此为标准进行人员筛选工作。
5. **<u>附加说明:</u>** 可以进行讨论，但是禁止代码抄袭.

### 参考资料

1.  [Deep Learning](https://www.deeplearningbook.org/), Ian Goodfellow and Yoshua Bengio and Aaron Courville.
2.  [神经网络与深度学习](https://nndl.github.io/)，邱锡鹏.
3.  [动手学深度学习](https://zh.d2l.ai/)， Aston Zhang et al.
4.  [Stanford CS 231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/).
5.  [Stanford CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/).
6.  [UC Berkeley EECS189: Introduction to Machine Learning](https://www.eecs189.org/).
7.  [NTU Machine Learning](https://speech.ee.ntu.edu.tw/~hylee/ml/2021-spring.html), HUNG-YI LEE (李宏毅).

