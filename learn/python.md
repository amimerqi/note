# python数据分析概述
---
## 1.1认识数据分析


1.数据分析
2.数据获取
3.数据预处理
4.分析与建模
5.模型的评价与优化
6.部署

## 1.2熟悉python数据分析工具

|  | R | python | MATLAB |
| ---- | ---- | ---- | ---- |
| 语言学习难度 | 入门难度低 | 入门难度一般 | 入门难度一般 | 
| 使用场景 | 数据分析，数据挖掘，机器学习，数据可视化等等 | 数据分析，机器学习，矩阵运算，科学数据可视化，数字图像处理，web应用，网络爬虫，系统运维等 |矩阵计算，数值分析，科学数据可视化，机器学习，符号计算，数字图像处理，数字信号处理，仿真模拟等|
| 第三方支持 |拥有大量的Packages，能够调用C，C++，Fortran，Java等其他程序语言。|拥有大量的第三方库，能够简便地调用C，C++，Fortran，Java等其他程序语言|拥有大量专业的工具箱，在新版本中加入了对C，C++，Java的支持|

**NumPy(Numerical Python)—— Python 科学计算的基础包(重点、掌握)**
1. 快速高效的多维数组对象 ndarray
2. 对数组执行元素级的计算以及直接对数组执行数学运算的函数
3. 读写硬盘上基于数组的数据集的工具
4. 线性代数运算、傅里叶变换，以及随机数生成的功能
5. 将 C、C++、Fortran 代码集成到 Python 的工具


**Pandas——数据分析核心库(重点、掌握)**
1. 提供了一系列能够快速、便捷处理结构化数据的数据结构和函数。
2. 高性能的数组计算功能以及电子表格和关系型数据库(如 SQL)灵活的数据处理功能。
3. 复杂精细的索引功能，以便便捷地完成重塑、切片和切块、聚合及选取数据子集等操作。


**Matplotlib——绘制数据图表的 Python 库(重点、掌握)**
1. Python的2D绘图库，非常适合创建出版物上用的图表。
2. 操作比较容易，只需几行代码即可生成直方图、功率谱图、条形图、错误图和散点图等图形。
3. 提供了pylab的模块，其中包括了NumPy和pyplot中许多常用的函数，方便用户快速进行计算和绘图。
4. 交互式的数据绘图环境，绘制的图表也是交互式的。


**scikit-learn——数据挖掘和数据分析工具(自学、尽量掌握)**
1. 简单有效，可以供用户在各种环境下重复使用。
2. 封装了一些常用的算法方法.
3. 基本模块主要有数据预处理、模型选择、分类、聚类、数据降维和回归6个，在数据量不大的情况下，scikit-learn可以解决大部分问题。

