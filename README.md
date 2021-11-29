# EngineX
 Engine X - 实时智能决策引擎  规则集、评分卡、决策树、决策表
## 概述

 Engine X - 实时智能决策引擎

​	一款将公司的商业规则转化成商业决策，通过将公司的行业决策经验进行知识化，来辅助公司做各种商业决策的决策引擎。

 Engine X 提供了三个版本：开源版本、商用基础版本、商用高级版本，点击https://www.fibo.cn/了解更多关于 Engine X商用版本更多信息。
 加微信群交流，公众号【FiboAI】后台回复「**加群**」即可。
         ![|](https://github.com/FiboAI/EngineX/blob/master/image/WechatIMG2355.jpeg)

## 核心概念和基本组成关系介绍

EngineX决策引擎系统核心概念有：指标、规则、决策节点、决策流、决策引擎。它们的组成关系如下： 

                       
  ![|](https://github.com/FiboAI/EngineX/blob/master/image/relation.png)
  
  
        
### 1 指标

指标是客户的某个维度的信息，可来源于公司内部数据或者第三方数据

### 2 规则

规则有指标+条件+动作组成，表示某种条件下做的动作

### 3 决策节点

决策流的核心组成部分，多种决策节点，支持不同业务场景的决策流设计

### 4 决策流

一个决策流，是一个决策流程，有多个决策节点串连组成

### 5 决策引擎

一个引擎，对外提供一套服务接口，使用方调用指定引擎来获取决策结果
