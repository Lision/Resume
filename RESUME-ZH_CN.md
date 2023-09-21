# 个人简历

## 李鑫

(+86)185-7665-3086  lisionmail@gmail.com

- 1992/男/北京
- 本科/内蒙古大学(211)/计算机科学与技术
- 工作年限：9 年
- GitHub：[https://github.com/Lision](https://github.com/Lision)
- 技术博客：[https://lision.me](https://lision.me)
- 掘金专栏（优秀作者）：[https://juejin.im/user/57dd4ff12e958a0054643da3](https://juejin.im/user/57dd4ff12e958a0054643da3)

## 技能清单

- 接近 8 年 iOS 工作开发经验
	- 熟悉 Xcode, Objective-C, Swift
	- 熟悉 CoreAnimation, Multitasking, Runtime, RunLoop, SwiftUI
	- 了解 Flutter, ReactNative 等主流跨端技术
- 接近 8 年 Git 命令行使用经验，熟悉常用的 Git 分支管理模型
- 自学 Ruby，Python，JavaScript，Html，CSS，Dart 等语言，具备相关开发能力

## 个人项目

### Hood - 屏幕时间管理工具

TestFlight 公测链接：[https://testflight.apple.com/join/22NPsJbj](https://testflight.apple.com/join/22NPsJbj)

> Note: 经过 Apple 审核通过后 App 才具备公测资格，TF 包内购不会收费，可体验所有功能。

## 开源项目

### WKWebViewJavascriptBridge - 针对 WKWebView 用于在 Swift 和 JavaScript 之间发送消息的桥。

[https://github.com/Lision/WKWebViewJavascriptBridge](https://github.com/Lision/WKWebViewJavascriptBridge) 1100+ Stars / 122 Forks / 27 Watch

### LSAnimator - 一个易于阅读和编写，非侵入性的多链式动画框架。

[https://github.com/Lision/LSAnimator](https://github.com/Lision/LSAnimator) 1600+ Stars / 164 Forks / 32 Watch

## 工作项目

### 腾讯

> [腾讯自选股-在线炒股票证券交易](https://apps.apple.com/cn/app/腾讯自选股-在线炒股票证券交易/id485653572)

#### 工程架构优化

原组件化做了很久但效果不太理想，香港券商业务「大丰满满」App 在我入职前**被迫通过 copy 代码**的方式实现自选股已有的部分业务。我通过**壳工程抽离将业务代码全量下沉**确保不会发生类似问题，在此基础上又依据**康威定律**将代码按照业务线人员组织重新划分并带队完成组件解藕拆分工作，获得「力行奖」。

#### ChatBot 工作流

自选股客户端的开发相关工作流从需求开发到需求交付**很多地方可进一步自动化**，特别是需求提测阶段，开发同学需要去触发流水线打包，等出包后通知 QA 进行验证，这个过程一个需求一般要重复几遍。
我做了一套**通过与企业微信 BOT 聊天的方式**完成自动化需求确认 > 开发 > 提测 > 交付的自动化工作流，**平均一个需求大约可以节省出 0.5 ～ 1 个工作人/日**。

### 猿辅导

> [猿辅导-中小学生全科在线辅导直播课](https://apps.apple.com/cn/app/猿辅导-中小学生全科在线辅导直播课/id974568444)

#### 批改模块业务模型建设

教师批改作业的模块在我的团队接手前刚被重构一轮，经常有教师反馈使用问题，定位问题的**成本较大**。我与日志基础组件团队共建了**会话形式**的日志 SDK，**覆盖了教师批改作业的完整链路**。结合已有的详细日志回捞工具记录异常现场，在**两次迭代后清空了问题列表**。我进一步建设了常用的批改操作链路报表，使批改模块**具备线上问题的主动运维能力**。

#### 精准测试

通过**插桩编译与代码覆盖率报告分析和增量合并**实现了 QA 手工测试到的代码染色能力，杜绝了少测、漏测 Case 出现，提升了代码交付质量，技术分享文章见 [https://mp.weixin.qq.com/s/14hmLWNXAh1FKZT5NI5QsQ](https://mp.weixin.qq.com/s/14hmLWNXAh1FKZT5NI5QsQ)。

### 美团外卖

> [美团外卖商家版-管家后台](https://apps.apple.com/cn/app/美团外卖商家版-管家后台/id869802614)

#### 订单模块平台化

闪购与外卖本属同一团队，随市场变化闪购业务独立出外卖，但两条业务线在订单系统上存在高度一致性且订单系统牵扯面广完全重建成本巨大。我当时作为订单模块负责人通过基于 Scene - Adaptor 理念的设计架构升级将订单模块平台化，面向协议解藕、封装下沉基础能力。**不影响双业务线正常独立迭代的同时服务于闪购与外卖两条业务线**。

#### Flap - MTFlutter 动态化能力的 Proxy 模块

MTFlutter 是美团内部使用的 Flutter 生态，我们还为它赋予了动态化更新的能力，即 Flap。其中我通过对 Dart 语言的 AST 剖析实现了支持类/库关系映射的 Proxy 代码自动生成器，使 **Flap 在动态性上不受限制**。

## 工作经历

### 腾讯（00700.HK）2022/01 - 至今

iOS Engineer （授予 RSU）

- 负责自选股 App 开发维护，架构设计优化，团队工作效率提升。

### 猿辅导在线教育 2020/06 - 2021/10

辅导研发部学习服务 iOS Team Leader （股权激励）

- 学习服务 iOS 负责人，负责提升组内开发效率和交付质量，搭建团队以及团队内部日常管理工作。
- 2020/2021 年秋季应届校招面试官，社招二面面试官，结合团队需要与面试标准把关候选人技术能力。

### 美团点评（03690.HK）2018/02 - 2020/06

iOS Engineer （职级晋升/人才盘点授予 RSU）

- 订单模块负责人，负责美团外卖 iOS 商家客户端订单模块的技术规划，架构设计，数据建设，指标定义以及相关 OKR 管理等工作。
- 2019/2020 年春季校招一面面试官，社招一面面试官。

### 深圳市随手科技有限公司（原金蝶随手记）2015/10 - 2018/01

iOS Engineer

### 深圳市金证科技股份有限公司（金证股份 - 600446）2014/02 - 2015/10

C/C++ Engineer

## 其他信息

- 英语 CET-4（具备日常查阅英文资料能力）
- 个人技术项目获得单项奖学金（**5%** 授予率）
- [IMUDGES（内蒙古大学精英学生开发者联盟）](http://www.imudges.com/)安卓 Team Leader（2012-2013）
