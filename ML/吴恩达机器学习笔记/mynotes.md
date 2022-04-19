# 机器学习
## 引言
### 机器学习是什么
  定义：<br>
  - Arthur Samuel: 在特定的编程环境下，给予计算机学习能力的领域。（Arthur Samuel）<br>
  - Tom Mitchell: 一个程序被认为能从经验E中学习，解决任务T，达到性能度量值P，
  当且仅当，有了经验E后，经过P评判，程序在处理T时的性能有所提升。

### 监督学习
定义：有预测目标Y，通过X预测Y。 <br>

### 无监督学习
定义：没有Y，只通过X进行分析并识别模式。 <br>

## 单变量线性回归
### 模型表示
![](http://latex.codecogs.com/svg.latex?h_\\theta(x)=\\theta_0+\\theta_1x)
### 代价函数
**cost funtion:** <br>
![](http://latex.codecogs.com/svg.latex?J(\\theta_0,\\theta_1)=\\frac{1}{2m}\\sum_{i=1}^{m}(h_\\theta(x^{(i)})-y^{(i)})^2) <br>
**Goal:** <br>
![](http://latex.codecogs.com/svg.latex?\\mathop{minimize}\\limits_{\\theta_0,\\theta_1}J(\\theta_0,\\theta_1))


## 线性代数回顾
