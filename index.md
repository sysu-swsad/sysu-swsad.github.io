---
layout: default
---

## Software System Analysis and Design
{:.no_toc}

* 目录
{:toc}

### 一、课程简介

本课程是软件工程专业核心专业课程之一，本课程描述了在解决现实世界问题的过程中，运用面向对象思想，定义、设计、实现软件应用的方法与原则。通过本课程学习，学生应了解日益复杂的软件应用与技术环境下，开发企业级软件应用面临的业务、技术与项目管理的挑战，初步掌握敏捷的软件开发模型、OOA/D方法与技巧，常用软件体系结构与设计模式，以及现代的软件团队生产工具。使学生具备初级软件设计师要求的分析问题、设计方案的能力。

> **语言塑造了我们思考的方式，决定了思考的内容**  
>   
> --- 本杰明·沃尔夫（Benjamin Lee Whorf）

上世纪50年代开始，计算机软件经历了从数学计算应用、到商业事务处理应用、至当今的全球互联应用的历程。对应地，人们先后提出了[结构化方法](https://en.wikipedia.org/wiki/Structured_analysis)、[面向对象方法](https://en.wikipedia.org/wiki/Object-oriented_analysis_and_design)、[面向服务方法](https://en.wikipedia.org/wiki/Service-oriented_modeling)，以适应软件面临的业务日益复杂、多变，规模日益庞大，生态与技术环境日益丰富的现实，来提升软件生产效率和质量。我们描述现实与软件世界的方法决定了软件产品的最终形态，因而掌握面向对象、服务设计的思考方式与方法是现代软件开发的基础。

对于软件开发入门者，可能更关注软件开发技术（功能实现），而不太关注软件的产品属性（用户需求、经济性、软件质量等）。本课程通过具体的案例，让学生逐步学会基于软件产品的思考，包括观察和选择问题域、定义软件需求、设计软件架构、运用设计模式等方面的基本能力，最终将分析与设计能力、软件开发技术、项目管理方法、现代软件开发工具的使用融合在项目之中。

### 二、课程任务（目标）

1. 掌握面向对象的分析与设计方法，包括：软件需求获取与管理、面向对象的设计原则、软件结构设计、设计模式的应用，以及使用UML可视化设计。
2. 了解软件开发模型，并尝试在项目中尝试敏捷实践，持续改进软件系统。包括：Ratiaon UP（统一过程），Scrum 以及 XP 等。
3. 掌握现代团队软件开发工具，提升管理技能与团队生产效率。包括：配置管理，项目进度管理，UML绘图、界面原型设计，数据库设计，API设计等工具。

### 三、教材

Larman C . Applying UML and Patterns: An Introduction to Object-Oriented Analysis and Design and Iterative Development (3rd Edition)[M]. Prentice Hall PTR, 2004. [美] 拉曼 著，李洋 等译，UML和模式应用（原书第三版），机械工业出版社，2006，ISBN：9787111186823

参考书：

1. [美] Hassan Gomaa 著，彭鑫，吴毅坚，赵文耘 等译，软件建模与设计：UML、用例、模式和软件体系结构，机械工业出版社，2014，ISBN：9787111467595
2. [澳] 麦斯阿塞克 著，马素霞 等译，需求分析与系统设计（原书第3版） [Requirements Analysis and System Design]，机械工业出版社，2009，ISBN：9787111272809
3. [美] 惠腾（Whitten J.L. 著，肖刚，孙慧 等译，系统分析与设计方法（原书第7版），机械工业出版社，2007，ISBN：9787111205517

### 四、教学团队

**1、主讲教师**

* **Dr. 潘茂林**，邮箱：panml@mail.sysu.edu.cn，办公地点：A316

**2、教学助理团队**

| 班级 |课程时间与地点|  教学助理与联系方式 |
|:--------:| ----------- | ------------ |
| 嵌软+通软 |  周一（3-4），周三前（3-4） C301/C204  | 陈师姐 545686770@qq.com，时师姐 |
| 数媒 |  周一（5-6），周三前（5-6） C301/C204  | 何师兄 helang3@mail2.sysu.edu.cn，叶师姐 17862709031@163.com |
| 计应 | 周五（7-8），周三后（5-6）  C203/C204 | 黄师姐 hypjudy@qq.com，梁师姐 867949069@qq.com |
| 电政 | 周五（3-4），周三后（3-4）  C203/C204 | 张师兄 928778158@qq.com，叶师兄 yehy9@mail2.sysu.edu.cn |

### 五、课程内容

| 周 | OOAD内容 | 作业与工程实践 | 备注 |
|:--:| ---- | ---- | ---- |
| 1 | [OOAD简介](slides/01-ooad-intro.pdf) | [软件的本质与软件工程科学](https://sysu-swsad.github.io/swad-guide/01-nature-software) | &emsp;|
| 2 | [过程模型](slides/02-process.pdf): <br> 软件开发过程  | [软件项目与知识团队管理](https://sysu-swsad.github.io/swad-guide/02-prject-team) | &emsp;|
| 3 | 统一过程与敏捷实践  | [软件项目过程模型与规划](https://sysu-swsad.github.io/swad-guide/03-project-process) | &emsp;|
| 4 | [初始阶段](slides/03-inception.pdf)  | [Inception 实践指南](https://sysu-swsad.github.io/swad-guide/04-inception) | &emsp;|
| 5 | [用例建模](slides/04-usecase.pdf)  | [组织第一次迭代](https://sysu-swsad.github.io/swad-guide/05-first-iteration) | &emsp;|
| 6 | 用例建模  | [用例建模-绘制用例图](https://sysu-swsad.github.io/swad-guide/06-usecase-modeling) | &emsp;|
| 7 | 业务建模  | [用例建模-业务建模](https://sysu-swsad.github.io/swad-guide/07-usecase-modeling) | &emsp;|
| 8 | [领域建模](slides/05-domain.pdf)  | [领域建模-概念与数据建模](https://sysu-swsad.github.io/swad-guide/08-domain-modeling) | &emsp;|
| 9 | 领域建模  | [领域建模-模型验证与面向资源的API设计](https://sysu-swsad.github.io/swad-guide/09-domain-modeling) | &emsp;|
| 10 | [功能建模](slides/06-function.pdf)  | [功能建模-设计RPC风格API](https://sysu-swsad.github.io/swad-guide/10-functional-modeling) | &emsp;|
| 11 | [软件架构设计](slides/07-architecture.pdf)  | 软件架构、架构模式、与应用程序框架  | &emsp;|
| 12 | 软件架构设计  | [架构设计方法](https://sysu-swsad.github.io/swad-guide/11-architecture-design-methods) | &emsp;|
| 13 | 微服务架构与实践  | [微服务架构定义](https://www.martinfowler.com/articles/microservices.html) | &emsp; |
| 14 | 详细设计-对象建模[model](slides/08-object-model.pdf),[dynamic](slides/08-object-dynamic.pdf)  |  | &emsp;|
| 15 | 详细设计-对象建模  |  | &emsp;|
| 16 | 详细设计-对象建模  |  | &emsp;|
| 17 | 设计模式  |  | &emsp;|
| 18 | 设计模式  |  | &emsp;|
| 19 | 复习  |  | &emsp;|
| 20 | 考试  |  | &emsp;|

### 六、作业要求

1. [课程项目实践要求](https://sysu-swsad.github.io/swad-guide/00-project-intro)
2. [课程项目实践模板](https://sysu-swsad.github.io/dashboard/)
3. 作业提交要求
    - 个人平时作业都是电子文档，请用博客或 GitPage URL 提交
    - 平时作业收集，使用石墨文档    
    - 团队作业，请在 Github 建项目，用 dashboard 仓库的 GitPage 提交

* **[作业提交页面](2019assignments)**
* [考勤情况查询](https://shimo.im/sheets/lOSJQ79Nv1caO0xL/)

### 七、成绩

|项目 | 分数 | 备注 |
| --- |:---:| -- |
| 期末考试 | 50 | &emsp; |
| 平时作业 | 20 | 个人作业、课堂测试与考勤（三次缺席不给平时成绩、做后排减成绩） |
| 项目实践 | 30 | 项目文档、代码、效果展示 |
| 课堂互动 | 10 | 课程相关方法与技术博客分享，优秀作业分享与课程展示等 |
| 合计 | 110 | 总成绩大于100，按100分计算 |

请务必做到 **本周作业，本周完成！**  
没有特殊情况，每推迟一周提交作业，成绩降一个档次

### 八、温馨提示

首先，理解实践性课程的特点。请先看刘谦在北影“骗人的表演艺术”演讲的开场白 [“错误引导”](https://v.vzuu.com/video/1079868250250256384) ，然后回答：

* 在这十分钟内刘谦展示了魔术表演的原理、方法、技术或技巧、工具？
* 了解了这些原理和方法，是否人人都能玩魔术？

Q：软件工程类课程书籍既无公式，也无算法和程序，课程内容非常理论？
A：软件工程内容来源于软件项目最佳实践的经验总结，包括原理、方法、技巧、工具等，因此你需要在实践中使用和检验它们。课程主要内容是软件开发实践的原理和方法，的确是枯燥的。但在实践中，这些内容是鲜活、易于理解的。以 UI 设计为例，基本理论是眼球焦点管理，其方法包括设计模式等、同时涉及审美、心理等多方面内容，然后需要一些美术功力实施，加上效率工具，几个方面能力综合，在实践中你才能理解这些原理和方法的价值。因此，工程学科非常强调“做中学”！

Q：为什么分析设计课程内容不够有趣？
A：一个软件项目与一段个人表演差别太大。你可能注意到教材没有作业或练习，参考书有但也没趣。软件案例项目规模小了，你会认为用大炮打蚊子；规模大了，你无法知道正确答案；案例使用的技术旧了，你会认为课程跟不上时代；使用新技术，学习技术的压力太大而忽视了课程的主题。

Q：课程可以自学吗？
A：在一个学期时间内是不可以的，用个3-5年是可以的。对于软件开发者入门者，每年阅读一次这类教材体会差别是非常大。这是因为用自己的经验、教训验证教材是一件耗时的事情。大神自学也会挂科的，因为你有限的经验距离业界最佳实践距离实在太远。




