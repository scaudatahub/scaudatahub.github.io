# Linear Algebra(线性代数)

*Acknowledgement:* 本课程是根据 MIT 18.06 Linear Algebra 来设计.

## 课程简介

本次课程包括线性空间，线性方程组理论，基本的矩阵计算和分解算法，如SVD，以及线性代数在工程上的应用，是学习大部分机器学习算法的必要基础.

### 前置课程

高中数学.

### 学习形式

1. 在线根据下面的课程安排自主学习，无考勤，在Bilibili上进行学习：[麻省理工 - 线性代数](https://www.bilibili.com/video/BV1ix411f7Yp?from=search&seid=7727661642243154327)，需要看完所有的视频，并且尽量完成MIT OCW原网页上的习题[MIT OCW 18.06](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/assignments/)，DataHub内部习题可能与上面有重合.
2. 课程教材：[线性代数英文版 - G. Strang](https://detail.tmall.com/item.htm?spm=a230r.1.14.42.df0760e133GLxe&id=607862194595&ns=1&abbucket=20)，这本书不久前由清华出版社引进，是英文原版教材，建议购买，可以长期使用和查阅.

### 考核说明

##### 考核形式：课程作业(25%) + 期中考核(25%) + 期末考核(50%)

##### 补充说明:

1. 课程作业由DataHub内部出题，选题会采纳课程教材以及网上资源，会根据课程内容进度来安排.

2. 考核也由DataHub内部出题，暂定3月初，具体时间另行安排通知.

3. 作业在此页面上发放，发放的文件为压缩包，压缩包文件树为：

   ```
   .
   |-linearalgebra_assignment_hw_x.zip
   |-- linearalgebra_hw_x.tex
   |-- linearalgebra_hw_x.pdf
   |-- xx.cls // 样式文件
   ```
   
   直接到模板(.tex文件)填写答案即可.



##### 课程安排：

| Week | Date     | Lecture                                                      | Homework&Project                                             |
| ---- | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1    | Fri.1/29 | The geometry of linear equations                             |                                                              |
|      | Sat.1/30 | Elimination with matrices                                    |                                                              |
|      | Sun.1/31 | Matrix operations and inverses                               |                                                              |
| 2    | Mon.2/1  | *LU* and *LDU* factorization                                 | [hw1 out](https://www.jianguoyun.com/p/DSy5Li0QuI-XCRipuN4D)(20 points) |
|      | Tue.2/2  | Transposes and permutations                                  |                                                              |
|      | Wen.2/3  | Vector spaces and subspaces / The nullspace: Solving Ax = 0  |                                                              |
|      | Thu.2/4  | Rectangular *PA* = *LU* and Ax = b / Row reduced echelon form |                                                              |
|      | Fri.2/5  | Basis and dimension / The four fundamental subspaces         |                                                              |
|      | Sat.2/6  | The four fundamental subspaces                               |                                                              |
|      | Sun.2/7  | Graphs and networks                                          | hw1 due                                                      |
| 3    | Mon.2/8  | Orthogonality                                                | [hw2 out](https://www.jianguoyun.com/p/DWajgh4QuI-XCRi2keAD)(20 points) |
|      | Tue.2/9  | Orthogonality                                                | [hw1 sol out](todo)                                          |
|      | Wen.2/10 | Projections and subspaces                                    | [Midterm Exam]()                                             |
|      | Thu.2/11 | Least squares approximations                                 |                                                              |
|      | Fri.2/12 | Gram-Schmidt and *A* = *QR*                                  |                                                              |
|      | Sat.2/13 | Gram-Schmidt and *A* = *QR*                                  | [project1 out](https://www.jianguoyun.com/p/DbXXLOkQuI-XCRj3rucD) |
|      | Sun.2/14 | Properties of determinants                                   | hw2 due                                                      |
| 4    | Mon.2/15 | Formulas for determinants                                    | [hw3 out](https://www.jianguoyun.com/p/DXK6nYgQuI-XCRivxOMD) (20 points) |
|      | Tue.2/16 | Applications of determinants                                 | [hw2 sol out](todo)                                          |
|      | Wen.2/17 | Applications of determinants                                 |                                                              |
|      | Thu.2/18 | Eigenvalues and eigenvectors                                 |                                                              |
|      | Fri.2/19 | Eigenvalues and eigenvectors                                 |                                                              |
|      | Sat.2/20 | Diagonalization                                              |                                                              |
|      | Sun.2/21 | Diagonalization                                              | hw3 due                                                      |
| 5    | Mon.2/22 | Markov matrices                                              | [hw4 out](https://www.jianguoyun.com/p/DeC0-LUQuI-XCRigi-gD)(20 points) |
|      | Tue.2/23 | Differential equations                                       | [hw3 sol out]()                                              |
|      | Wen.2/24 | Symmetric matrices                                           |                                                              |
|      | Thu.2/25 | Positive definite matrices                                   |                                                              |
|      | Fri.2/26 | Matrices in engineering/Similar matrices                     |                                                              |
|      | Sat.2/27 | Singular value decomposition                                 |                                                              |
|      | Sun.2/28 | Fourier series, FFT, complex matrices                        | hw4 due                                                      |
| 6    | Mon.3/1  | Linear transformations / Choice of basis                     | [hw5 out]() (20 points)                                      |
|      | Tue.3/2  | Linear programming                                           | [hw4 sol out](todo)                                          |
|      | Wen.3/3  | Numerical linear algebra / Computational science             |                                                              |
|      | Thu.3/4  | review                                                       | hw5 due [hw5 sol out](todo)                                  |
|      | Fri.3/5  | review                                                       | [Final Exam](todo) temp                                      |
|      | Sat.3/6  | todo                                                         |                                                              |

##### 作业说明

1. **<u>作业缴交形式</u>**：**只需要缴交由$\LaTeX$排版出来的pdf文件**，使用邮件发送到到：632373825@qq.com，邮件主题格式同下面的作业命名格式，缴交日期是在课程安排里面的**正常缴交截止日期的中午十二点**之前，迟交作业的积分规则见后面的**附加说明**.

2. **<u>邮件主题命名格式</u>**：采用英文命名，具体格式为：**SCAUDataHub\_名字\_科目\_课程时间\_hw+作业第几次**，比如**张三线性代数2021年春季的第一次作业**，其对应的主题格式即为

   *SCAUDataHub_ZhangSan\_linearalgebra\_21sp_hw1*

   若出现重名到时候再处理.

3. **<u>作业命名格式</u>**：采用英文命名，具体格式为：**名字\_科目\_hw+作业第几次**，如**张三线性代数2021年春季的第一次作业**，其对应的作业附件格式即为

   *SCAUDataHub_ZhangSan\_linearalgebra\_21sp_hw1.pdf*

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

1. [MIT OCW原始课程主页](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/index.htm)(包含视频，大纲，课件slides等，下载上面的文件和观看视频可能需要科学上网).
2. **David C. Lay** Linear Algebra and Its Applications.
3. **G. Strang** Linear Algebra and Its Applications.
4. **Sheldon Axler** Linear Algebra Done Right.
