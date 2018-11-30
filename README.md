# 毕业设计
##### 一点碎碎念
老师很早就布置下了毕业设计的题目，由于种种原因（主要是我懒），一直未系统的开始进行对毕业设计题目的思考，现在时间也拖得很晚了，再不整体规划毕设就要耽误了。想了挺久，既然老师把题目定下来了，就当是命题作文吧。时间序列分析作为传统的分析方法，已经有很多年的理论积淀，光从理论方面肯定是很难在毕设里写出亮眼的东西的。既然是毕业设计，本科四年学习结束的标志，肯定是不能像做几个实验，处理些数据，然后当成实验报告那样写的。想来想去，不如由特殊推广到一般，初步构想是开发一个简单的项目，整合各种时间序列以及数据处理的方法，或许以后还能派上点用场。以前只是在GitHub上查阅过一些资料，并未在GitHub上写过项目，正好借此机会，将毕设项目发在GitHub中，希望该项目的实现能对将来的学习有所启发。
## 题目
多时间序列分析
## 目标
系统的学习时间序列分析，整合各种时间序列的方法，以此开发一个较为简单的项目，初步项目目标如下：
#### 输入
尽可能兼容多的数据格式，最大限度的增加使用便利性
#### 处理 
处理方法分模块实现，调用方便
#### 输出
输出尽量美（bu）观（chou）
#### 易拓展性
能较为方便的增删功能
## UI设计
TODO
## 模块设计
TODO
## 分析方法
### 传统分析方法
#### AR
##### 原理
自回归模型，利用前期若干随机变量的先行组合描述之后随机变量的模型
<img src="http://chart.googleapis.com/chart?cht=tx&chl= $x_{t}=\phi_{0}+\phi_{1}x_{t-1}+\phi_{2}x_{t-2}+\dots+\phi_{p}x_{t-p}+a_{t}$">
<img src="http://www.forkosh.com/mathtex.cgi? $x_{t}=\phi_{0}+\phi_{1}x_{t-1}+\phi_{2}x_{t-2}+\dots+\phi_{p}x_{t-p}+a_{t}$">
<img src="http://www.hx1998.club/graduation_project/images/AR(p).PNG">
#### MA
#### ARMA
#### ARIMA
### 机器学习分析方法
#### tensorflow结合LSTM
## 初步结果
## 思考总结
