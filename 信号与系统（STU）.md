# 信号与系统（STU）

[TOC]

---

## 绪论

### 1课程方向

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315081840751.png" alt="image-20200315081840751" style="zoom: 67%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315082358246.png" alt="image-20200315082358246" style="zoom:67%;" /> 

数字信号处理，通信原理，控制理论，随机信号处理

### 2研究对象

- 信号：作为一个或几个独立变量函数的信号，都包含了有关某些现象性质的信息；
- 系统：系统综述对给定的信号做出响应而产生另外的信号，或是产生某些所需要的特性。

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315083110284.png" alt="image-20200315083110284" style="zoom:50%;" /> 

### 3数学工具

1. 微分方程、差分方程；
2. 数学变换：正交变换—傅里叶变换、拉普拉斯变换、Z变换；

目的：

1. 时频分析
2. 滤波、设计满足要求的滤波器

### 4学习方法

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315084301324.png" alt="image-20200315084301324" style="zoom:67%;" /> 

### 5考核方式

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315084356388.png" alt="image-20200315084356388" style="zoom:67%;" /> 



---

## 第0章   数学基本知识

### 0-1复数

#### 0-1-1复数的运算

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315084208868.png" alt="image-20200315084208868" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315084524070.png" alt="image-20200315084524070" style="zoom:50%;" /> 

#### 0-1-2幅角

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315084637173.png" alt="image-20200315084637173" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315085103362.png" alt="image-20200315085103362" style="zoom:50%;" /> 

#### 0-1-3棣模佛(De Moivre)公式

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315085725817.png" alt="image-20200315085725817" style="zoom: 50%;" /> 

#### 0-1-4复数的方根

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315085916818.png" alt="image-20200315085916818" style="zoom:67%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315090147471.png" alt="image-20200315090147471" style="zoom:50%;" /> 

### 0-2复变函数

#### 0-2-1定义

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315090350317.png" alt="image-20200315090350317" style="zoom:50%;" /> 几何意义：一个映射（变换）<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315090544928.png" alt="image-20200315090544928" style="zoom:50%;" /> 

#### 0-2-2映射

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315090733101.png" alt="image-20200315090733101" style="zoom:67%;" /> 

### 0-3线性常系数微分方程

#### 0-3-1一阶微分方程

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315090823382.png" alt="image-20200315090823382" style="zoom: 67%;" /> ——左边的每项中仅含 y 或 y‘，且均为 y 或 y’的一次项（线性的）.

称为一阶线性齐次微分方程，简称线性**齐次**方程——<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315091028590.png" alt="image-20200315091028590" style="zoom:50%;" /> 

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315091128452.png" alt="image-20200315091128452" style="zoom:67%;" /> 

#### 0-3-2一阶微分方程解法

1. 分离变量，两边积分

一阶线性**齐次**方程的通解公式为：<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315091306914.png" alt="image-20200315091306914" style="zoom:67%;" /> 

一阶线性**非齐次**方程的通解公式为：<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315091357263.png" alt="image-20200315091357263" style="zoom:50%;" /> 

#### 0-3-3二阶常系数微分方程

- 非齐次：<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315091911233.png" alt="image-20200315091911233" style="zoom:67%;" /> 
- 齐次：<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315091929613.png" alt="image-20200315091929613" style="zoom:67%;" /> 

性质——<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315092056498.png" alt="image-20200315092056498" style="zoom:67%;" /> 

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315092138981.png" alt="image-20200315092138981" style="zoom:50%;" /> 

#### 0-3-4二阶常系数齐次线性方程解法

1. 找出特征方程，求出特征根
2. 根据特征根写出通解——<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315092516163.png" alt="image-20200315092516163" style="zoom:50%;" />

#### 0-3-5二阶常系数非齐次线性方程解法

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315092313712.png" alt="image-20200315092313712" style="zoom:67%;" /> 

##### 0-3-5-1例题

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315092957745.png" alt="image-20200315092957745" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315093433248.png" alt="image-20200315093433248" style="zoom:50%;" /> 

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315093524294.png" alt="image-20200315093524294" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315093659209.png" alt="image-20200315093659209" style="zoom:50%;" /> 

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315093847106.png" alt="image-20200315093847106" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315094010911.png" alt="image-20200315094010911" style="zoom:50%;" /> 

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315094153689.png" alt="image-20200315094153689" style="zoom:50%;" /> 



---

## 第1章 信号与系统

> 难点：
>
> 1. 信号的自变量变换：时移和尺度变换
> 2. 信号周期性的判断
> 3. 广义函数（奇异函数）
> 4. 系统类型的判断

### 1-1信号的描述

#### 1-1-1连续时间与离散时间信号

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315083752382.png" alt="image-20200315083752382" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315083814151.png" alt="image-20200315083814151" style="zoom:67%;" /> 

> 连续时间信号在**离散时刻点上的样本**可以构成一个离散时间信号。

#### 1-1-2信号的能量与功率

##### 1-1-2-1连续时间信号

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315100258224.png" alt="image-20200315100258224" style="zoom:50%;" /> 

##### 1-1-2-2离散时间信号

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315100354607.png" alt="image-20200315100354607" style="zoom:50%;" /> 

##### 1-1-2-3无限区间上的能量与功率

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315100457072.png" alt="image-20200315100457072" style="zoom:50%;" />  <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315100537096.png" alt="image-20200315100537096" style="zoom:67%;" /> 

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315100515513.png" alt="image-20200315100515513" style="zoom:50%;" /> 

#### 1-1-3三类重要信号

1. 能量信号——**信号具有有限**的总能量，
   　　　 即：<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315094800880.png" alt="image-20200315094800880" style="zoom:67%;" /> 

2. 功率信号——信号有无限的总能量，但**平均功率有限**，

   ​			即：<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315094905386.png" alt="image-20200315094905386" style="zoom:67%;" /> 

3. 信号的总能量和平均功率**都是无限的**。

   ​			即：<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315094954398.png" alt="image-20200315094954398" style="zoom:67%;" /> 

#### 1-1-4周期信号与非周期信号

> ​    这种信号也称为功率信号，通常用它的平均功率来表征。

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315100143073.png" alt="image-20200315100143073" style="zoom:80%;" /> 

> 对非周期信号，且能量有限，则为能量信号。

##### 1-1-4-1基波周期

- 连续——可视为周期信号，但它的基波周期没有确定的定义。
- 离散——可以视为周期信号，其基波周期为1。

##### 1-1-4-2奇信号与偶信号

（Odd Signals and Even Signals）

**复信号** ——<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315102436737.png" alt="image-20200315102436737" style="zoom:50%;" /> 

>  **任何信号都能分解**成一个偶信号与一个奇信号之和。
>
> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315102603846.png" alt="image-20200315102603846" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315102636926.png" alt="image-20200315102636926" style="zoom:50%;" /> 

<img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315102744631.png" alt="image-20200315102744631" style="zoom:50%;" /> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315104447558.png" alt="image-20200315104447558" style="zoom:50%;" /> 

### 1-2信号的自变量变换

> 由于信号可视为自变量的函数，当**自变量改变**时，必然会使信号的特性相应地改变

1. 时移变换(Shift if signals)
2. 反转变换(Reflection of signals)
3. 尺度变换(Scaling)

> 由于离散时间信号的自变量只能取整数值，因而**尺度变换只对连续时间信号**而言。
>
> <img src="%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%B3%BB%E7%BB%9F%EF%BC%88STU%EF%BC%89.assets/image-20200315095406868.png" alt="image-20200315095406868" style="zoom:50%;" /> 
>
> 显然是从中**依次抽出自变量取偶数时的各点**而构成的。这一过程称为**对信号的抽取（decimation）**。





### 1-3基本信号



### 1-4系统及其数学模型



### 1-5系统的性质









---



