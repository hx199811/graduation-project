# 毕业设计
##### 一点碎碎念
老师很早就布置下了毕业设计的题目，由于种种原因（主要是我懒），一直未系统的开始进行对毕业设计题目的思考，现在时间也拖得很晚了，再不整体规划毕设就要耽误了。想了挺久，既然老师把题目定下来了，就当是命题作文吧。时间序列分析作为传统的分析方法，已经有很多年的理论积淀，光从理论方面肯定是很难在毕设里写出亮眼的东西的。既然是毕业设计，本科四年学习结束的标志，肯定是不能像做几个实验，处理些数据，然后当成实验报告那样写的。想来想去，不如由特殊推广到一般，初步构想是开发一个基于flask框架的web应用，整合各种时间序列以及数据处理的方法，或许以后还能加以扩展，应用到其他学习中。以前只是在GitHub上查阅过一些资料，并未在GitHub上写过项目，正好借此机会，将毕设项目发在GitHub中，希望该项目的实现能对将来的学习有所启发。
## 题目
数据处理预测Web项目开发
## 目标
系统的学习时间序列分析，整合各种数据处理的方法，以此开发一个较为简单的项目，初步项目思考与设计如下：

#### what（做什么）

|问题|方案|
|---|----|
|这是什么|数据处理预测的Web应用|
|要实现什么功能|框架搭建，文件交互，数据处理|
|核心功能|框架搭建|
|不确定实现的功能|UI设计，文件存储，安全性验证，用户管理，不同主机间的通信，多台主机分别实现不同功能|
|侧重|侧重业务实现|
|数据库的要求|储存用户提交数据，可能储存用户信息|

#### who（谁）

|问题|方案|
|---|----|
|需求来源|个学习，毕业设计，web使用|
|使用者|暂做实验项目，不做推广|
|项目监督者|个人导师|
|项目检验者|个人导师以及答辩老师|

#### where （地点）
|问题|方案|
|---|----|
|部署地点|实验阶段为虚拟机，使用阶段为服务器|
|网络环境|内网|
|操作系统|尽量通用，不受OS的限制|


#### when （时间）
|问题|方案|
|---|----|
|时间分配|分期由主到次完善功能|
|估计时间|由完善功能而定|
|可承受目标时间下限|答辩月|

#### how （如何实现）
|问题|方案|
|---|----|
|技术难点|flask框架整体设计的统一性与拓展性|
|数据库设计|暂定mysql|
|业务流程|见流程图|
|框架|Django或者flask|
|UI|附属功能，依进度实现其复杂性|

#### how much （成本）
|问题|方案|
|---|----|
|时间成本|较大，随着功能的增加而增加|
|复杂度|框架搭建为整体（高），框架内功能实现为局部（低）|
|项目收益|学习收益为主，使用收益依凭项目完成度|
|可行性分析|主要功能可行性高，其他功能依时间而定|
