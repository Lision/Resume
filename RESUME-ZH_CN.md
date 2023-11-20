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

[https://apps.apple.com/us/app/hood-screentime-manager/id6449154620](https://apps.apple.com/us/app/hood-screentime-manager/id6449154620) SwiftUI / ScreenTimeAPI / IAP

> Note: 中国大陆地区因为 ICP 备案问题，暂不提供服务支持。

## 开源项目

### WKWebViewJavascriptBridge - 针对 WKWebView 用于在 Swift 和 JavaScript 之间发送消息的桥。

[https://github.com/Lision/WKWebViewJavascriptBridge](https://github.com/Lision/WKWebViewJavascriptBridge) 1100+ Stars / 100+ Forks / 27 Watch

### LSAnimator - 一个易于阅读和编写，非侵入性的多链式动画框架。

[https://github.com/Lision/LSAnimator](https://github.com/Lision/LSAnimator) 1600+ Stars / 100+ Forks / 32 Watch

## 工作项目

### 腾讯

> [腾讯自选股-在线炒股票证券交易](https://apps.apple.com/cn/app/腾讯自选股-在线炒股票证券交易/id485653572)

#### 工程架构优化

组件化效果不理想，香港券商业务「大丰满满」App **被迫通过 copy 代码**的方式实现自选股已有业务。我通过**壳工程抽离**将业务代码**全量下沉**后又依据康威定律将业务代码按照组内人员结构重新划分，带队完成业务组件解耦，获「力行奖」。

#### ChatBot 工作流

组内日常工作自动化流程比较传统，公司内各服务平台之间的 Gap 以及需求日常开发工作中存在不必要的人力成本消耗。我做了一套通过与企微 Bot 以**聊天**的方式完成需求**确认 > 开发 > 提测 > 交付**的自动化工作流，平均一个 5 人日的正常需求可**节省 0.5~1 人日**。

### 猿辅导

> [猿辅导-中小学生全科在线辅导直播课](https://apps.apple.com/cn/app/猿辅导-中小学生全科在线辅导直播课/id974568444)

#### 批改模块业务模型建设

教师批改作业模块重构后经常有问题反馈，定位**成本较大**。我与日志基础组件团队共建了会话形式的日志 SDK，**覆盖了教师批改作业的完整链路**，结合已有的日志回捞工具记录异常现场，在**两次迭代后清空了问题列表**。我进一步建设了常用的批改操作链路报表，使批改模块**具备主动运维能力**。

#### 精准测试

通过**插桩编译**与**代码覆盖率报告分析增量合并**实现了 QA 黑盒测试代码染色，杜绝了少测、漏测 Case 出现，提升了代码交付质量标准，技术分享文章见 [https://mp.weixin.qq.com/s/14hmLWNXAh1FKZT5NI5QsQ](https://mp.weixin.qq.com/s/14hmLWNXAh1FKZT5NI5QsQ)。

### 美团外卖

> [美团外卖商家版-管家后台](https://apps.apple.com/cn/app/美团外卖商家版-管家后台/id869802614)

#### 订单模块平台化

闪购随市场变化业务独立出外卖，但在订单逻辑上高度相似且**订单系统牵扯面广完全重建成本巨大**。我当时作为订单模块负责人通过基于 Scene - Adaptor 理念的设计将订单模块面向协议解藕，封装下沉基础能力，**未影响双业务线正常迭代**完成了平台化架构升级。

#### Flap - MTFlutter 动态化能力的 Proxy 模块

MTFlutter 作为美团内部使用的 Flutter 生态，我们为它赋予了动态化更新能力，即 Flap。其中我通过对 Dart 语言的 AST 剖析实现了支持类/库关系映射的 Proxy 代码自动生成器，**使 Flap 在动态性上不受限制**。

## 工作经历

### 腾讯（00700.HK）2022/01 - 至今

iOS Engineer （授予 RSU）

- 负责自选股 App 开发维护，架构设计优化，团队工作效率提升。

### 猿辅导在线教育 2020/06 - 2021/10

辅导研发部学习服务 iOS Team Leader （股权激励）

- 学习服务 iOS Leader，负责学习服务客户端团队搭建与管理工作。
- 2020/2021 年秋季校招面试官，社招二面面试官，结合团队需要与面试标准把关候选人技术能力。

### 美团点评（03690.HK）2018/02 - 2020/06

iOS Engineer （职级晋升/人才盘点授予 RSU）

- 订单模块 Owner，负责美团外卖 iOS 商家客户端订单模块的技术规划，架构设计，数据建设，OKR 管理等工作。
- 2019/2020 年春季校招一面面试官，社招一面面试官。

### 深圳市随手科技有限公司（原金蝶随手记）2015/10 - 2018/01

iOS Engineer

### 深圳市金证科技股份有限公司（金证股份 - 600446）2014/02 - 2015/10

C/C++ Engineer

## 其他信息

- 英语 CET-4（具备日常查阅英文资料能力）
- 个人技术项目获得单项奖学金（**5%** 授予率）
- [IMUDGES（内蒙古大学精英学生开发者联盟）](http://www.imudges.com/)安卓 Team Leader（2012-2013）
