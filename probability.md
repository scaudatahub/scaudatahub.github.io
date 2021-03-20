# Probability(概率论)

*Acknowledgement:* 本课程是根据 MIT 6.012 Introduction to Probability来设计.

## 课程简介

本次课程包括基本的概率论(不引入测度论)，即随机变量及其分布，以及基本的随机过程的内容，是学习机器学习以及自然语言处理的必要准备.

### 前置课程

单变量微积分，少量的多元微积分，高中数学.

### 学习形式

1. 在线根据下面的课程安排自主学习，无考勤，学堂在线平台：[概率论——不确定性的科学](https://www.xuetangx.com/course/MITX07011000210/5883955)，需要看完平台上所有的视频，**第一单元只需要看<u>课程概论 Lec. 0: Course overview</u>**，其他单元需要全部看，并且尽量完成平台上的习题(但不计分)，DataHub内部习题可能与上面有重合.
2. 课程教材：[概率导论 - Dimitri P.Bertsekas](https://detail.tmall.com/item.htm?spm=a230r.1.14.30.77aa1d8eGclXOL&id=525859904757&ns=1&abbucket=20)，建议购买，教材写的非常好

### 考核说明

##### 考核形式：课程作业(25%) + 期中考核(25%) + 期末考核(50%)

##### 补充说明:

1. 课程作业由DataHub内部出题，选题会采纳课程教材以及网上资源，会根据课程内容进度来安排.

2. 考核也由DataHub内部出题，暂定3月初，具体时间另行安排通知.

3. 作业在此页面上发放，发放的文件为压缩包，压缩包文件树为：

   ```
   .
   |-probability_assignment_hw_x.zip
   |-- probability_hw_x.tex
   |-- probability_hw_x.pdf
   |-- xx.cls // 样式文件
   ```
	
	直接到模板(.tex文件)填写答案即可.



##### 课程安排：

| Week | Date     | Lecture                                             | Homework&Project                                             |
| ---- | -------- | --------------------------------------------------- | ------------------------------------------------------------ |
| 1    | Fri.1/29 | Lec. 0: Course overview                             | [hw0](https://www.jianguoyun.com/p/DSMQRywQuI-XCRiqxt0D)(0 points)，仅供复习前置知识，不必提交 |
|      | Sat.1/30 | Unit 1: Probability models and axioms               |                                                              |
|      | Sun.1/31 | Unit1 cont. / Unit 2: Conditioning and independence |                                                              |
| 2    | Mon.2/1  | Unit 2 cont.                                        | [hw1 out](https://www.jianguoyun.com/p/DWITgf8QuI-XCRiuuN4D)(20 points) |
|      | Tue.2/2  | Unit 3: Counting                                    |                                                              |
|      | Wen.2/3  | Unit 4: Discrete random variables                   |                                                              |
|      | Thu.2/4  | Unit 4 cont.                                        |                                                              |
|      | Fri.2/5  | Unit 5: Continuous random variables                 |                                                              |
|      | Sat.2/6  | Unit 5 cont.                                        |                                                              |
|      | Sun.2/7  | Unit 5 cont.                                        | hw1 due                                                      |
| 3    | Mon.2/8  | Unit 5 cont.                                        | [hw2 out](https://www.jianguoyun.com/p/DWEWQS4QuI-XCRjNp-AD)(20 points) |
|      | Tue.2/9  | Unit 6: Further topics on random variables          | [hw1 sol out](todo)                                          |
|      | Wen.2/10 | Unit 6 cont.                                        | [Midterm Exam]()                                             |
|      | Thu.2/11 | Unit 6 cont.                                        |                                                              |
|      | Fri.2/12 | Unit 6 cont.                                        |                                                              |
|      | Sat.2/13 | Unit 7: Bayesian inference                          |                                                              |
|      | Sun.2/14 | Unit 7 cont.                                        | hw2 due                                                      |
| 4    | Mon.2/15 | Unit 7 cont.                                        | [hw3 out](https://www.jianguoyun.com/p/DblJCV4QuI-XCRiqxecD) (20 points) |
|      | Tue.2/16 | Unit 7 cont.                                        | [hw2 sol out](todo)                                          |
|      | Wen.2/17 | Unit 8: Limit theorems and classical statistics     |                                                              |
|      | Thu.2/18 | Unit 8 cont.                                        |                                                              |
|      | Fri.2/19 | Unit 8 cont.                                        |                                                              |
|      | Sat.2/20 | Unit 9: Bernoulli and Poisson processes             |                                                              |
|      | Sun.2/21 | Unit 9 cont.                                        | hw3 due                                                      |
| 5    | Mon.2/22 | Unit 9 cont.                                        | [hw4 out](todo)(20 points)                                   |
|      | Tue.2/23 | Unit 9 cont.                                        | [hw3 sol out]()                                              |
|      | Wen.2/24 | Unit 10: Markov chains                              |                                                              |
|      | Thu.2/25 | Unit 10 cont.                                       |                                                              |
|      | Fri.2/26 | Unit 10 cont.                                       |                                                              |
|      | Sat.2/27 | Unit 10 cont.                                       |                                                              |
|      | Sun.2/28 | Review                                              | hw4 due                                                      |
| 6    | Mon.3/1  | Review                                              | [hw5 out]() (20 points)                                      |
|      | Tue.3/2  | Review                                              | [hw4 sol out](todo)                                          |
|      | Wen.3/3  | Review                                              |                                                              |
|      | Thu.3/4  | Review                                              | hw5 due [hw5 sol out](todo)                                  |
|      | Fri.3/5  | todo                                                | [Final Exam](todo) temp                                      |
|      | Sat.3/6  | todo                                                |                                                              |

##### 作业说明

1. **<u>作业缴交形式</u>**：**只需要缴交由$\LaTeX$排版出来的pdf文件**，使用邮件发送到到：632373825@qq.com，邮件主题格式同下面的作业命名格式，缴交日期是在课程安排里面的**正常缴交截止日期的中午十二点**之前，迟交作业的积分规则见后面的**附加说明**.

2. **<u>邮件主题命名格式</u>**：采用英文命名，具体格式为：**SCAUDataHub\_名字\_科目\_课程时间\_hw+作业第几次**，比如**张三概率论2021年春季的第一次作业**，其对应的主题格式即为

   *SCAUDataHub_ZhangSan\_probability\_21sp_hw1*

   若出现重名到时候再处理.

3. **<u>作业命名格式</u>**：采用英文命名，具体格式为：**名字\_科目\_hw+作业第几次**，如**张三概率论2021年春季的第一次作业**，其对应的作业附件格式即为

   *SCAUDataHub_ZhangSan\_probability\_21sp_hw1.pdf*

   若出现重名到时候再处理.

4. **<u>附加说明:</u>**

   a. 以后计划使用gitee传输，但是涉及到作弊审查的问题，具体方案还需要研究讨论.

   b. 作业强制要求使用$\LaTeX$，手写或者其他方式均不计分.

   c. 作业迟交 $k(k \geq 0, ~k \in \mathbb{N})$ 天的记分规则：
   $$
   \text{score_you_will_get} = \frac{\text{score_without_delay}  }{2^k}
   $$
   d. 交作业的日期不得晚于作业答案放出当天的中午12点(答案将与放出当天的中午12点之后)，**不接受在此日期后的任何理由的迟交**，记0分.

   e. **本门课的最后成绩将记入 SCAU DataHub 2021 春季第一次大型考核的笔试分数之中.**

### 参考资料

1. [MIT OCW原始课程主页](https://ocw.mit.edu/resources/res-6-012-introduction-to-probability-spring-2018/)(包含视频，大纲，课件slides等，下载上面的文件和观看视频可能需要科学上网).
2. **陈希孺** 概率论与数理统计.
3. **李贤平** 概率论基础.
4. **Sheldon M. Ross** A First Course in Probability.
5. [UC Berkeley EECS 126](https://inst.eecs.berkeley.edu/~ee126/fa20/)，Berkeley的概率论与随机过程课程，讲应用较多，例如Google的PageRank等算法，可作为进阶课程来学习.
