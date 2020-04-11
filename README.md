# MiniTarget/小目标规划

2019-2020-2 软件需求工程与UML建模第二小组技术博客



- [一.项目前景和范围](#--------)
  * [1 业务需求](#1-----)
    + [1.1 应用背景](#11-----)
    + [1.2 业务机遇](#12-----)
    + [1.3 业务目标与成功标准](#13----------)
    + [1.4 业务风险](#14-----)
  * [2 项目前景](#2-----)
    + [2.1 前景概述](#21-----)
    + [2.2 主要特性](#22-----)
    + [2.3 假设与依赖](#23------)
  * [3 项目范围](#3-----)
    + [3.1 范围列表](#31-----)
    + [3.2 限制与排除](#32------)
- [二.涉众分析与硬数据采样](#-----------)
  * [1 涉众分析](#1-----)
  * [2 硬数据采样](#2------)
    + [2.1 采样形式及内容](#21--------)
    + [2.2 采样结果及分析](#22-------)
- [三.面谈](#---)
- [四.原型](#---)
  * [1 系统工作流程](#1-------)
  * [2 界面设计](#2-----)



# 一.项目前景和范围

## 1 业务需求

### 1.1 应用背景

目前工作学习的节奏不断加快，能够合理的规划安排生活、高效准时的完成任务和掌握技能成为一门重要的本领。在日常生活中制定一个个小目标，对于规划和高效利用时间十分有帮助。我们决定开发一款专注于通过小目标规划来完成短期时间管理和长期目标完成的软件，满足有此需求的用户。

### 1.2 业务机遇

有部分人群已经有规划生活、制定目标的习惯，他们有更加方便清晰地制定小目标的需求，希望有更好的用户体验；还有部分人群并没有此习惯，但是有养成安排制定目标的习惯的需求。

### 1.3 业务目标与成功标准

BO-1: 完成计划的所有功能。

BO-2: 招募体验人员，确实地验证软件对于规划时间的有效性。

SC-1: 正式上线后，收到的用户反馈70%以上好评。

### 1.4 业务风险

目前市面上已经有很多时间管理类软件，我们的项目虽然侧重在小目标规划，仍然面临激烈的竞争。

## 2 项目前景 

### 2.1 前景概述

为习惯于规划日常工作学习的人群提供一款轻便的可进行小目标规划的软件，让习惯于规划生活、制定目标的人能够更方便更清晰地管理时间。

帮助有规划生活、制定目标的需求的潜在人群找到自己的规划方式，养成时间管理的好习惯，更好地利用时间。

### 2.2 主要特性

FE-1: 用户可以创建和删除指定日期和时间截止的小目标。

FE-2: 小目标可以设定其属性和优先级，并标记完成状态。

FE-3: 指定任务会在指定时间向用户推送提醒消息。

FE-4: 用户可以查看任务完成历史记录和统计情况。

FE-5: 用户可以进行打卡和分享。

### 2.3 假设与依赖

AS-1: 用户倾向于在手机上进行目标安排与规划，认为其更加便捷。

DE-1: 软件运营中能够保障用户的隐私安全。

## 3 项目范围

### 3.1 范围列表

| 特性 | 版本一 | 版本二 | 版本三 |
| :--: | :----: | :----: | :----: |
| FE-1 |  实现  |        |        |
| FE-2 |  实现  |        |        |
| FE-3 |        |  实现  |        |
| FE-4 |        |  实现  |        |
| FE-5 |        |        |  实现  |

### 3.2 限制与排除

LI-1: 该软件侧重于个人的小目标规划，无法满足商业化的企业时间管理需要。

## 4 项目环境

### 4.1 操作环境

用户在日常生活中24小时随时随地可以使用软件。

对用户的个人数据进行严格的保密。

### 4.2 涉众

见涉众分析

### 4.3 项目属性

* 进度：在2019-2020-2学期结束前完成软件主要功能。

* 人员：

  **梅浩楠**  程序员，项目管理，文档编写

  **李辉**      模型绘制，测试

  **姚凇瀚**  组间沟通

  **徐尘化**  程序员

  **姜福伟**  测试

  **刘睿**    美工

# 二.涉众分析与硬数据采样

## 1 涉众分析

本软件的涉众不存在不同用户权限不统一问题，且不同身份涉众的需求高度一致，通过目标种类的划分可以满足不同涉众需求，因此仅将涉众划分为两类。

| 涉众编号 | 涉众名称 |        涉众说明        |         使用系统的方式         |
| :------: | :------: | :--------------------: | :----------------------------: |
|  US001   | 社会人员 | 在社会上工作的在职人员 | 使用软件规划工作任务和其它事项 |
|  US002   |   学生   |   在学校里学习的学生   | 使用软件规划学习任务和其它事项 |

## 2 硬数据采样

### 2.1 采样形式及内容

本次硬数据采样的方式是采用问卷星进行网上问卷调查

以下是问卷调查内容

1. 您目前的身份是？ [单选题] *
○学生
○社会人员

2. 你认为通过将工作或学习拆分成一个个的小目标对完成任务更加有帮助吗？ [单选题] *
○很有帮助
○有一定帮助
○没有

3. 你有规划生活、制定目标的习惯吗？ [单选题] *
○有
○没有，但有意向养成
○没有，且无意向养成

4. 你有使用过目标规划类软件吗？ [单选题] *
○有
○无

5. 你会想要尝试目标规划类软件吗？ [单选题]
○会
○不介意试试
○不会

6. 你认为好的目标规划软件应该有什么特点？ [多选题] *
□简洁轻量
□易于上手
□界面美观
□交互友好
□自由度高

7. 你认为好的目标规划软件应该具备的功能 [多选题] *
□创建指定时间截止的任务
□丰富的可编辑任务种类
□为任务设定属性、优先级
□天气功能
□统计和成就系统
□自动提醒用户
□分享及打卡

8. 你还有其他想要我们实现的功能吗？ [填空题]

 ### 2.2 采样结果

本次调查共回收有效问卷136份。

第1题：您目前的身份是？[单选题]

![avatar](/Picture/questionnaire_res1.png)

第2题：你认为通过将工作或学习拆分成一个个的小目标对完成任务更加有帮助吗？[单选题]

![avatar](/Picture/questionnaire_res2.png)

第3题：你有规划生活、制定目标的习惯吗？[单选题]

![avatar](/Picture/questionnaire_res3.png)

第4题：你有使用过目标规划类软件吗？[单选题]

![avatar](/Picture/questionnaire_res4.png)

第5题：你会想要尝试目标规划类软件吗？[单选题]

![avatar](/Picture/questionnaire_res5.png)

第6题：你认为好的目标规划软件应该有什么特点？[多选题]

![avatar](/Picture/questionnaire_res6.png)

第7题：你认为好的目标规划软件应该具备的功能[多选题]

![avatar](/Picture/questionnaire_res7.png)

第8题  你还有其他想要我们实现的功能吗？   [填空题]

* 社交功能，如团队打卡，互助打卡等
* 重要项目倒计时功能 可以设置固定模板，方便编辑 可以切换提醒用户的方式
* 激励机制
* 软件可以有弹性一些，不是所有的任务都必须要完成（我们常常会因为一些变故而无法完成一些目标）。可以设置一个维度，当无法完成全部目标时若能完成今日最重要的目标应当给予用户肯定，鼓励用户完成明日的目标，可以增加其积极性。
* 免费
* 叫起床
* 学习功能app黑白名单
* 每天早上发送一条鼓励性的提示语
* 专注中禁止切出功能
* 备忘功能
* 如果提供计划模板就很nice
* 不要花钱
* 免费
* 更加明显的提示显示和铃声提示
* 主要是方便操作，交互一定要良好
* 或许可以来个任务未完成的惩罚措施
* 适当添加娱乐性
* 自动化高
* 我觉得做到这些已经很好了
* 很好
* 有奖励功能
* 可以每天根据变化改变计划提醒

### **2.3 采样分析**

1. 由单选题分析得出，不管是学生还是社会人员，绝大部分都认为将工作或学习拆分成一个个的小目标对完成任务更加有帮助，并且有规划生活、指定目标的习惯或有意向养成此习惯，潜在的用户量是十分大的。有略微超过半数的人使用过目标规划类软件，其他人没使用过，且绝大多数人是会尝试目标规划类软件的，说明目标规划类软件有进一步普及的空间。

2. 从多选题可以看出，理想中的目标规划软件特点里简洁轻量和易于上手最为用户看重，超过70%，其它特点的看重用户接近一半。理想中的目标规划软件功能里创建指定时间截止的任务、丰富的可编辑任务种类、为任务设定属性和优先级最为用户看重，自动提醒功能和统计与成就功能次之，而天气功能和分享及打卡功能则显得不那么重要，只有少部分用户看重。
3. 从填空题可以看出，许多用户提出了自己期望的功能，其中激励功能、小目标模板期望较多，在开发过程中在有余力的情况下可以考虑实现。

# **三.面谈**

**时间**：2020/4/10晚

**方式**：QQ聊天

**甲方**：第13组梅浩楠

**乙方**：第2组朱志远

**内容：**

Q: 你好，你提出这个需求的背景是什么？

A: 当下，面对生活的压力，什么时候该做什么，什么事情重要又有什么事情允许被暂时搁置成了许多人迫切的需求，为方便用户进行时间管理，需要开发相应的软件。

Q: 这个软件的目标是什么呢？

A: 为需要规划时间的人群提供便利。

Q:你期望这个软件具有什么功能呢？

A: 允许用户新建多个目标，并可以在每个目标后设置多个子目标，主目标包括每个子目标处都可以选择设置时间限制，当特定时间到达时，允许该软件向系统发送通知。

Q: 你预想的时间设定具体如何呢？

A: 系统显示日历界面，点击相应日期后即可对查看当日的目标详情，亦可以在此界面新建目标或者修改已有目标。

Q: 对于目标具体的操作有哪些呢？

A: 点击已有目标后可以进行修改，内容包括修改时间，修改目标内容，删除对应目标，新建子目标，打上目标已完成的标签。点击新建目标将弹出目标界面，允许用户文本输入目标内容，新建目标完成后可以选择进行时间设定或者进行修改。

Q:目标有什么属性呢？

A:默认为按照主目标的结束时间升序排列，亦可由用户手动进行重要性排序。

Q:目标到期具体会发生什么呢？

A: 系统将向操作系统发送提醒，默认为振动可由用户修改为响铃或仅通知栏提示，目标距离结束少于多少时间时提醒或者是否提醒子目标由用户自行设定，默认为2小时，仅提醒主目标。  若目标已被打上完成的标签，则不进行提醒，并被标注为颜色，默认为绿色。  若以超时，则被标注颜色，默认为红色。  

Q:麻烦了，谢谢，你的需求非常具体。



# **四.原型**

## **1 系统工作流程**



## **2 界面设计**








