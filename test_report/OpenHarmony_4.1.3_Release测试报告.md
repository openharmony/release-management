# **OpenHarmony 4.1.3 Release 测试报告**

## **1** **概述**

 本报告针对OpenHarmony 4.1.3 Release 版本的测试验证及质量状态评估，包括对子系统特性和整机专项。 

## **2** **测试版本与测试环境**

 测试版本： 

| **版本名称**                    | **测试起始时间** | **测试结束时间** |
| ------------------------------- | ---------------- | ---------------- |
| OpenHarmony 4.1.9.1-4.1.9.4版本 | 2025-1-7         | 2025-2-24        |

 测试环境： 

| **硬件型号** | **备注**        | **版本**                                                |
| ------------ | --------------- | ------------------------------------------------------- |
| HI3861       | 轻量系统&不带屏 | hispark_pegasus版本                                     |
| HI3516DV300  | 小型系统&带屏   | hispark_taurus版本(LiteOS版本)/hispark_taurus_linux版本 |
| RK3568       | 标准系统&带屏   | RK3568 版本（32位）                                     |

## **3** **版本概要测试结论**

 总体测试结论：Go with Risk 

| **测试项** | **版本要求**                                                 | **测试结论** | **风险和遗留关键问题**    |
| ---------- | ------------------------------------------------------------ | ------------ | ------------------------- |
| 子系统验证 | 1、无严重与主要的缺陷 <br />2、总体问题关闭率95%以上         | Go           | 子系统评估详情请见4.1章节 |
| 兼容性测试 | 1、XTS通过率100%，达标<br />2、接口覆盖率100%                | Go           | 评估详情请见4.2章节       |
| 专项稳定性 | 4.1 release版本准出标准需要达到，核心服务/核心应用APR<=0.1， 整机重启APR<=0.6, 系统开关机异常APR<=0.1,预制应用异常APR<=3 。（ APR单位：次/千小时） | Go with Risk | 详情请见4.3章节           |
| 专项性能   | 静态KPI：预期目标胜率90%，实际胜率89.79%(44/49)，不达标 。<br />内存测试 ：整机内存基线845.24M，达标。 | Go with Risk | 详情请见4.4章节           |
| 安全       | 1、安全隐私漏洞：发布版本安全隐私漏洞扫描、清零  <br />2、安全问题：无安全问题遗留       <br />3、安全编码：安全类静态检查工具清零 | Go           | 评估详情请见4.5章节       |
| SDK        | 1、SDK配套IDE无关键问题，版本配套验证完成无关键问题   <br /> | Go           | 评估详情请见4.6章节       |
| 资料       | 无资料使用关键问题遗留                                       | Go           | 评估详情请见4.7章节       |

## **4** **版本详细测试结论**

### **4.1** **子系统测试**结论

| **序号** | **子系统名称**         | **评估结论** | **风险和遗留关键问题**                                       |
| -------- | ---------------------- | ------------ | ------------------------------------------------------------ |
| 1        | 媒体子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：  <br/>【功能】功能用例全量覆盖，测试通过，无问题遗留<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无问题遗留<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描、Fuzz测试，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无问题遗留<br/>【遗留问题】无关键问题遗留 |
| 2        | 应用子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无问题遗留<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无问题遗留<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描等测试，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无遗留问题<br/>【遗留问题】无关键问题遗留 |
| 3        | 启动恢复子系统 | Go | 需求验收：无新增需求<br/>关键特性： 无新增关键特性<br/>测试活动：  <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无问题遗留<br/>【性能 】测试通过，无风险<br/>【安全】隐私合规用例全量覆盖，覆盖了Fuzz测试，病毒，漏洞，隐私扫描等，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 4        | 安全基础能力子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：  <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能】测试通过，无风险<br/>【安全】安全隐私合规用例全量覆盖，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】 无关键问题遗留 |
| 5        | ArkUI子系统   | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：  <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，无遗留关键稳定性问题<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了Fuzz测试、安全扫描等安全测试，验收通过<br/>【XTS】XTS已全部通过<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 6        | 驱动子系统   | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：  <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，无遗留关键稳定性问题<br/>【性能 】测试通过，无风险<br/>【安全】安全隐私合规用例全量覆盖，无问题遗留<br/>【XTS】测试通过<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 7        | 内核子系统        | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：<br/>【功能】功能用例全量覆盖，测试通过，无风险 <br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】验收通过<br/>【安全】安全扫描测试，无遗留问题<br/>【XTS】测试通过 <br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 8        | USB子系统          | Go | 需求验收：无新增需求<br/>关键特性： 无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无问题和风险<br/>【遗留问题】无关键问题遗留 |
| 9        | 泛Sensor子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，验收通过<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 10       | 多模输入子系统    | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，验收通过<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 11       | 文件存储子系统         | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，验收通过。<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 12       | 电源子系统             | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，无遗留问题<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 13       | 语言编译与运行时子系统 | Go | 需求验收：无新增需求<br/>关键特性： 无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，无遗留问题<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，无关键问题<br/>【XTS】测试通过<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 14       | 全局资源调度管控子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，验收通过 <br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 15       | 分布式任务调度子系统   | Go | 需求验收：无新增需求 <br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险 <br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险 <br/>【性能 】测试通过，无风险 <br/>【安全】覆盖了安全扫描和fuzz测试，验收通过 <br/>【XTS】用例通过率100% <br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险 <br/>【遗留问题】无关键问题遗留 |
| 16       | 系统服务管理子系统     | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，验收通过 <br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】无关键问题遗留 |
| 17       | 分布式DP子系统         | Go | 需求验收：无新增需求<br/>关键特性： 无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试，验收通过 <br/>【XTS】验收通过<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 18       | 分布式数据管理子系统   | Go | 需求验收：无新增需求<br/>关键特性：无关键新增特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了Fuzz、二进制文件安全扫描、敏感日志扫描测试，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 19       | 分布式硬件子系统       | Go | 需求验收：无新增需求<br/>关键特性：无关键新增特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了Fuzz测试，病毒，漏洞，隐私扫描等，无关键问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】IADAY7 音乐组网时对端不显示连接码 |
| 20       | 分布式软总线子系统     | Go | 需求验收：无新增需求<br/>关键特性：无关键新增特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，验收通过<br/>【稳定性】长稳测试用例全量覆盖，测试通过<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了Fuzz测试，病毒，漏洞，隐私扫描等，验收通过<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 21       | 杂散子系统             | Go | 需求验收：无新增需求<br/>关键特性：无关键新增特性<br/>测试活动： <br/>【功能】验收通过<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险。<br/>【安全】覆盖了Fuzz测试，病毒，漏洞，隐私扫描等，验收通过<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 22       | 无障碍子系统           | Go | 需求验收：无新增需求<br/>关键特性：无关键新增特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】【安全】覆盖了Fuzz测试，病毒，漏洞，隐私扫描等，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】无关键问题遗留 |
| 23       | 账号子系统             | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描和fuzz测试、隐私扫描测试，验收通过，无问题遗留<br/>【XTS】XTS通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 24       | 电话子系统             | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 25       | 事件通知子系统         | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键遗留问题 |
| 26       | 包管理子系统           |     Go      | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无关键问题<br/>【安全】覆盖了Fuzz、安全扫描，测试通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】测试通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 27      | WEB子系统              | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过<br/>【性能 】接口内存泄漏测试，测试通过，无关键问题<br/>【安全】覆盖了Fuzz、安全扫描，测试通过，无问题遗留<br/>【XTS】用例通过率 100%<br/>【资料】无新增资料需求<br/>【SDK】测试通过，覆盖全量接口，无风险<br/>【遗留问题】 无关键遗留问题 |
| 28       | 元能力子系统           |     Go     | 需求验收：无新增需求 <br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】无关键遗留问题 |
| 29 | 短距离通信子系统 | Go | 需求验收：无新增需求 <br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过<br/>【安全】覆盖FUZZ、安全扫描、二进制文件及代码扫描，无遗留问题<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】无关键遗留问题 |
| 30 | 图形子系统 | Go | 需求验收：无新增需求<br/>关键特性： 无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】无风险，无关键遗留问题<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无 |
| 31 | 窗口管理子系统 | Go | 需求验收：无新增需求<br/>关键特性： 无新增关键特性<br/>测试活动：<br/> 【功能】功能用例全量覆盖，测试通过，无关键遗留问题<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】无风险，无关键遗留问题<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无 |
| 32 | 全球化子系统 | Go | 需求验收：无新增需求<br/>关键特性： 无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无关键遗留问题<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】无风险，无关键遗留问题<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无 |
| 33 | 位置服务子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无遗留问题<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过<br/>【安全】覆盖安全扫描测试，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】无 |
| 34 | DFX | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：<br/> 【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过<br/>【性能 】测试通过<br/>【安全】覆盖了FUZZ、安全工具扫描，验收通过无风险<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】 无关键问题遗留 |
| 35 | 升级子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过<br/>【性能 】测试全量覆盖，无关键问题<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无 |
| 36 | 程序访问控制子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了fuzz和安全扫描测试，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，覆盖全量接口，无风险<br/>【遗留问题】无关键问题遗留 |
| 37 | 测试子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：<br/> 【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】覆盖了安全扫描测试，验收通过，无问题遗留<br/>【XTS】验收通过<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 38 | AI子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动： <br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】安全扫描测试通过<br/>【XTS】验收通过<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |
| 39 | 用户IAM子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：<br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】安全隐私合规用例全量覆盖，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】无关键问题遗留 |
| 40 | PKI签名中心子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：<br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无风险<br/>【安全】安全隐私合规用例全量覆盖，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过，无风险<br/>【遗留问题】无关键问题遗留 |
| 41 | 网络子系统 | Go | 需求验收：无新增需求<br/>关键特性：无新增关键特性<br/>测试活动：<br/>【功能】功能用例全量覆盖，测试通过，无风险<br/>【稳定性】长稳测试用例全量覆盖，测试通过，无风险<br/>【性能 】测试通过，无问题遗留<br/>【安全】覆盖了Fuzz、安全扫描，验收通过，无问题遗留<br/>【XTS】用例通过率100%<br/>【资料】无新增资料需求<br/>【SDK】验收通过<br/>【遗留问题】无关键问题遗留 |


### **4.2** **兼容性测试结论**

兼容性测试: 主要是验证设备和业务应用满足OpenHarmony开源兼容性定义的技术要求，确保运行在OpenHarmony上的设备和业务应用能稳定、正常运行，同时使用OpenHarmony的设备和业务应用有一致性的接口和业务体验。 

 准出结论：Go

| 系统分类 | **测试套名称**                      | **英文**                                        | **目的**            | **用例规模**           | **通过率** | **验收结论** |
| -------- | ----------------------------------- | ----------------------------------------------- | ------------------- | ---------------------- | ---------- | ------------ |
| 标准系统 | OpenHarmony应用兼容性测试套         | ACTS  （Application Compatibility Test Suite ） | 看护北向应用兼容性  | 152773                 | 100%       | Go           |
| 标准系统 | OpenHarmony应用兼容性测试套补充测试 | ACTS-Validator                                  | 看护基础体验兼容性  | 96                     | 100%       | Go           |
| 标准系统 | OpenHarmony分布式兼容性测试套       | DCTS  （Distributed Compatability Test Suite）  | 看护分布式兼容性    | 1203                   | 100%       | Go           |
| 标准系统 | OpenHarmony硬件抽象测试套           | HATS  （Hardware Abstraction Test Suite ）      | 看护HDI与内核兼容性 | 4678                   | 100%       | Go           |
| 小型系统 | OpenHarmony应用兼容性测试套         | ACTS  （Application Compatibility Test Suite ） | 看护北向应用兼容性  | liteOS:2802 linux：455 | 100% 100%  | Go           |
| 轻量系统 | OpenHarmony应用兼容性测试套         | ACTS  （Application Compatibility Test Suite ） | 看护北向应用兼容性  | 383                    | 100%       | Go           |

### 4.3 稳定性专项测试结论

准出结论：Go with Risk

4.1.9.1-4.1.9.4版本累积测试时间为10053小时 ，APR=12.93(其中蓝牙问题APR=7.56)。遗留23个问题待解决，整体评估带风险发布。

| 测试类分类           | 准出标准（APR为牵引值）                                      | 质量状态 | 测试结果                                                     |
| -------------------- | :----------------------------------------------------------- | -------- | ------------------------------------------------------------ |
| 核心服务可靠性       | 1、mediaserver<br/>2、camera_server<br/>3、foundation<br/>4、Samgr<br/>5、hdf_devmgr<br/>6、appspawn<br/>7、softbus_server<br/>8、wifi_manager_se<br/>9、power_host<br/>10、accesstoken_ser<br/>11、render_service<br/> 各核心服务小于标准值0.1 | 不达标   | 版本测试数据：<br/>1、 mediaserver=0.22>0.1(标准值)<br/>2、 softbus_server=0.11>0.1(标准值)<br/> |
| 核心应用可靠性       | 1、com.ohos.mms<br/>2、com.ohos.photos<br/>3、com.ohos.note<br/>4、com.ohos.callui<br/>5、com.ohos.camera<br/>6、com.ohos.contacts<br/>7、com.ohos.settings<br/>8、com.ohos.launcher<br/>9、com.ohos.systemui <br/>10、com.ohos.screenlock<br/>11、com.ohos.filepicker<br/>12、com.example.kikakeyboard <br/>  各核心应用小于标准值0.1 | 不达标   | 版本测试数据：<br/>1、com.ohos.settings=4.95<br/>2、com.ohos.systemui= 2.69 <br/>3、com.ohos.note=0.97<br/>4、 com.ohos.launcher=0.43<br/>5、com.ohos.camera=0.32<br/>6、com.ohos.photos=0.32<br/>7、com.ohos.contacts=0.11<br/>8、com.ohos.mms=0.11<br/> |
| 预置应用异常         | 跟随版本发布预置的应用范围< 3次/千小时                       | 不达标   | 版本测试数据：预制应用APR=12.93                              |
| 死机重启             | < 0.6 次/千小时                                              | 达标     | 无死机重启问题                                               |
| 不开机(只统计OS导致) | 无OS导致的不开机关键问题                                     | 达标     | 无不开机问题                                                 |
| 内存泄露             | 无内存泄漏问题                                               | 达标     | 无内存泄漏问题                                               |
| 内存越界             | 无内存越界问题                                               | 达标     | 无内存越界问题                                               |

**遗留问题列表：**

| ISSUE  | 描述                                                         |
| ------ | ------------------------------------------------------------ |
| IB2Y58 | 进程com.ohos.settings因THREAD_BLOCK_6S出现3次appfreeze       |
| IBAJ4U | 进程com.ohos.systemui因THREAD_BLOCK_6S出现8次appfreeze       |
| IB9AXC | 进程com.ohos.settings因APP_INPUT_BLOCK出现12次appfreeze      |
| IBNOG5 | 进程ohos.samples.distributedcalc因THREAD_BLOCK_6S出现16次appfreeze |
| IBM99X | 进程bluetooth_servi下SaInit0线程出现2次cppcrash，崩溃栈：libbtservice.z.so |
| IBNONZ | 进程com.ohos.notes因APP_INPUT_BLOCK出现6次appfreeze          |
| IBNORA | 进程ohos.samples.distributedcalc因APP_INPUT_BLOCK出现4次appfreeze |
| IBJTWP | 进程com.ohos.launcher因THREAD_BLOCK_6S出现3次appfreeze       |
| IBJTWY | 进程com.ohos.camera因THREAD_BLOCK_6S出现3次appfreeze         |
| IBJTX6 | 进程com.ohos.photos因THREAD_BLOCK_6S出现3次appfreeze         |
| IBM9HC | 进程com.ohos.note下的ace.bg.4线程出现1次cppcrash，崩溃栈：libace_compatible.z.so |
| IBNOLP | 进程com.ohos.systemui因APP_INPUT_BLOCK出现3次appfreeze       |
| IBM9DG | 进程camera_host下的offlinepipeline线程导致libperipheral_camera_pipeline_core出现2次cppcrash |
| I8TLYJ | 进程bluetooth_servi下的SaInit1线程出现1次cppcrash，崩溃栈：libbtservice.z.so |
| IB2YXW | 进程com.ohos.smartperf的ohos.smartperf线程出现2次cppcrash，崩溃栈：libwm.z.so |
| IBJTXH | 进程com.ohos.settings下出现1次jscrash,栈名：'unregisterObserver |
| IBJTVL | 进程com.ohos.mms下的OS_IPC_2线程出现1次cppcrash，崩溃栈：libdatashare_consumer.z.so |
| IBKQB4 | 进程com.ohos.contacts下的com.ohos.contacts线程出现1次cppcrash，崩溃栈：librender_service_base.z.so |
| IBKQDG | 进程com.ohos.note下的com.ohos.note线程出现1次cppcrash，崩溃栈：libace_compatible.z.so |
| IBM9FJ | 进程com.ohos.smartperf下的com.ohos.smartperf线程出现1次cppcrash，崩溃栈：libwm.z.so |
| IBM9JB | 进程netmanager下的SaInit1线程出现1次cppcrash，崩溃栈：libethernet_manager.z.so |
| IBNO6V | 进程softbus_server下SaInit0线程出现1次cppcrash，崩溃栈：libwifi_sdk.z.so |
| IBNO9G | 进程com.ohos.launcher下出现1次jscrash                        |

### **4.4** **性能专项测试结论**

准出结论：Go with Risk

静态KPI：预期目标胜率90%，实际胜率89.79%(44/49) ，不达标但较在研发布版本略有优化，整体评估带风险发布。

内存测试 ：整机内存845.24M，优于基线860M，已达标。

| 应用名称 | 用例名称                                       | 触发方式     | 指标类型 | 安卓基线 | RK3568数据 |
| -------- | ---------------------------------------------- | ------------ | -------- | -------- | ---------- |
| 桌面     | 主桌面静态壁纸滑动                             | 滑动         | 帧率     | 54       | 60         |
| 信息     | 非首次启动短信息                               | 点击（启动） | 完成时延 | 1000     | 381.04     |
| 信息     | 首次启动短信息                                 | 点击（启动） | 完成时延 | 2300     | 1504.44    |
| 相机     | camera启动（冷启动）                           | 点击（启动） | 完成时延 | 2683     | 1362.5     |
| 相机     | camera启动（热启动）                           | 点击（启动） | 完成时延 | 2216     | 558.33     |
| 相机     | 拍照生成缩略图                                 | 点击拍照     | 完成时延 | 1220     | 1283.33    |
| 图库     | 图库缩略图列表滑动                             | 滑动         | 帧率     | 60       | 56.6       |
| 图库     | 图库单个图片缩放                               | 捏合         | 帧率     | 60       | 60         |
| 图库     | 图库缩略图列表滑动                             | 滑动         | 响应时延 | 150      | 118.75     |
| 图库     | 图库单个图片缩放                               | 捏合         | 响应时延 | 150      | 145.83     |
| 图库     | 查看图片                                       | 点击         | 完成时延 | 769      | 543.75     |
| 图库     | 复制一张图片（1张5M图片）                      | 点击         | 完成时延 | 2300     | 629.16     |
| 图库     | 剪切一张图片（1张1M图片）                      | 点击         | 完成时延 | 1833     | 591.72     |
| 图库     | 删除多张图片（2张5M图片）                      | 点击         | 完成时延 | 916      | 933.33     |
| 图库     | 图库从照片切换到相册（Tab切换）                | 点击         | 完成时延 | 442      | 333.16     |
| 图库     | 非首次启动图库                                 | 点击（启动） | 完成时延 | 579      | 358.33     |
| 图库     | 首次启动图库                                   | 点击（启动） | 完成时延 | 1404     | 1529.11    |
| 输入法   | 按键输入速度                                   | 点击         | 响应时延 | 80       | 72.22      |
| 输入法   | 输入法键盘弹出                                 | 点击         | 完成时延 | 540      | 545.83     |
| 设置     | 退出设置                                       | 点击         | 完成时延 | 650      | 204.16     |
| 设置     | 启动设置（原表是冷启动设置）                   | 点击（启动） | 完成时延 | 1145     | 1026.38    |
| 联系人   | 联系人列表滑动                                 | 滑动         | 帧率     | 60       | 54.5       |
| 联系人   | 联系人列表滑动                                 | 滑动         | 响应时延 | 150      | 145.83     |
| 联系人   | 查看一条联系人                                 | 点击         | 完成时延 | 883      | 445.83     |
| 联系人   | 存入联系人                                     | 点击         | 完成时延 | 625      | 341.83     |
| 联系人   | 联系人-拨号子Tab切换                           | 点击         | 完成时延 | 440      | 381.94     |
| 联系人   | 删除联系人                                     | 点击         | 完成时延 | 370      | 225.33     |
| 联系人   | 新建一个联系人                                 | 点击         | 完成时延 | 462      | 329.16     |
| 联系人   | 非首次启动联系人                               | 点击（启动） | 完成时延 | 604      | 362.5      |
| 联系人   | 首次启动联系人                                 | 点击（启动） | 完成时延 | 1270     | 1786.11    |
| webview  | 浏览器打开天猫网页，从上往下滑                 | 滑动         | 帧率     | 54       | 58.3       |
| webview  | 浏览器打开一个纯图片的网页，左右切换图片的滑动 | 滑动         | 帧率     | 54       | 60         |
| webview  | 浏览器微博首页滑动                             | 滑动         | 帧率     | 54       | 58.23      |
| webview  | 浏览器天猫界面缩放                             | 捏合         | 帧率     | 54       | 60         |
| webview  | 浏览器打开纯文本网页                           | 滑动         | 响应时延 | 150      | 76.38      |
| webview  | 浏览器打开天猫网页                             | 滑动         | 响应时延 | 300      | 79.1       |
| webview  | 浏览器天猫界面滑动                             | 滑动         | 响应时延 | 150      | 126.38     |
| webview  | 浏览器键鼠事件Hover响应时延                    | Hover        | 响应时延 | 200      | 33.3       |
| webview  | 首次启动浏览器                                 | 点击（启动） | 完成时延 | 1621     | 1327.77    |
| SystemUI | 状态栏下拉                                     | 滑动         | 响应时延 | 140      | 105.55     |
| SystemUI | 调起任务管理器                                 | 点击         | 完成时延 | 474      | 179.125    |
| SystemUI | 系统用户界面（清除所有后台进程时间）           | 点击         | 完成时延 | 1000     | 163.88     |
| SystemUI | 后台多任务的切换调度                           | 点击         | 完成时延 | 1041     | 379.45     |
| 开机     | 非首次开机                                     | 重启         | 完成时延 | 22916    | 22263.88   |
| 开机     | 唤醒屏幕                                       |              | 完成时延 | 600      | 39.66      |
| 开机     | 开机                                           | 开机         | 完成时延 | 20512    | 20485.16   |
| 通话     | 拨号盘按键                                     | 点击         | 响应时延 | 88       | 50         |
| 时钟     | 首次启动                                       | 点击         | 完成时延 | 704      | 657.29     |
| 计算器   | 首次启动                                       | 点击         | 完成时延 | 1206     | 741.66     |

遗留问题：

| ISSUE  | 描述                                                         |
| ------ | ------------------------------------------------------------ |
| IAE215 | 相机拍照生成缩略图场景基线1220ms，实际值1283.33ms，差基线63.33ms |
| IB0EDJ | 图库缩略图列表滑动基线60帧，实际值56.6帧，差基线3.4帧        |
| IANJ3R | 首次启动图库场景基线1404ms，实际值1529.11ms，差基线125.11ms  |
| IB0EIE | 联系人列表滑动基线60帧，实际值54.5帧，差基线5.5帧            |
| IB0EL5 | 首次启动联系人场景基线1270ms，实际值1786.11ms，差基线516.11ms |

### **4.5** **安全专项测试结论**

准出结论：Go

安全测试活动情况：漏洞按照社区开源组件漏洞SLA时间修复，未超期

| 安全测试大项     | 安全测试标准                                                 | 测试内容                                                     | 测试结论 | 安全问题状态                                      |
| ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | ------------------------------------------------- |
| 代码安全检视     | 各模块依据[OpenHarmony安全编码规范](https://gitee.com/openharmony/docs/blob/master/zh-cn/contribute/OpenHarmony-c-cpp-secure-coding-guide.md)，进行代码安全检视，检视问题均需要修复。 | 各模块参考安全编码规范，逐条进                               | Go       | 发现问题已经清零                                  |
| 静态编码扫描     | 使用安全编码扫描工具扫描测试，扫描告警结果清零。OpenHarmony代码门禁已集成一款安全编码扫描工具。 | 1、使用社区门禁编码扫描工具或其他编码工具扫描开源代码        | Go       | 发现问题已经清零                                  |
| 编译选项验证     | 依据[OpenHarmony编译规范](https://gitee.com/openharmony/community/blob/master/sig/sig-buildsystem/编译规范.md)，使用编译选项扫描工具检查二进制文件编译选项开启情况，二进制文件编译选项均需要符合规范要求。 | 1、检查二进制文件是否开启栈保护编译选项<br/>2、检查二进制文件是否开启立即绑定编译选项<br/>3、检查二进制文件是否开启堆栈不可执行编译选项<br/>4、检查二进制文件是否开启地址无关编译选项<br/>5、检查二进制文件是否开启随机化编译选项<br/>6、检查二进制文件是否开启GOT表保护编译选项<br/>7、检查二进制文件是否禁止动态库搜索路径编译选项<br/>8、检查二进制文件是否开启删除符号表搜索路径编译选项 | Go       | 无问题                                            |
| 开源软件漏洞扫描 | 针对开源组件使用业界漏洞扫描工具扫描，开源组件漏洞均已按照社区漏洞管理流程修复。 | 使用开源组件漏洞扫描工具，扫描开源组件是否存在已知漏洞       | Go       | 漏洞按照社区开源组件漏洞SLA时间修复，未超期<br /> |
| 设计规范验证     | 各模块依据[OpenHarmony安全设计规范](https://gitee.com/openharmony/docs/blob/master/zh-cn/contribute/OpenHarmony-security-design-guide.md)，结合业务完成安全设计自检验证，自检设计问题均需要修复。 | 各模块参考安全设计规范逐条进行验证                           | Go       | 问题均已闭环                                      |
| 病毒扫描         | 使用主流病毒扫描软件扫描软件包，病毒扫描结果均修复或确认为工具误报。 | 使用2款以上主流病毒扫描开源软件包及代码                      | Go       | 病毒告警问题已解决                                |
| 秘钥证书扫描     | 使用秘钥证书关键词扫描工具扫描软件包，秘钥证书问题均需要修复。 | 1、工具扫描开源代码中是否预置非社区公开证书<br/>2、工具扫描开源代码中是否预置非社区公开秘钥 | Go       | 无问题                                            |
| 黑盒Fuzz验证     | 针对暴露用户态接口进行黑盒Fuzz，包括但不限于系统服务接口、内核驱动接口、socket网络接口。 | 1、使用工具对系统服务接口进行黑盒Fuzz<br/>2、使用工具对内核驱动接口进行黑盒Fuzz<br/>3、使用工具对socket网络进行黑盒Fuzz | Go       | 问题均已闭环                                      |



### **4.6 SDK**专项测试结论

准出结论：Go。

测试从ArkTS、JS、toolchains、preview、native等维度进行看护：

| **特性**   | **子特性**                                        | **测试内容**                                                 | 结论                                                         |
| ---------- | ------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ArkTS      | API接口                                           | 1. d.ts文件描述验证<br/>2. API功能XTS兼容性验证<br/>3. API跨版本变更验证<br/>4. API接口联想能力验证 | 资料测试通过，API接口功能测试通过。                          |
| ArkTS      | 组件接口                                          | 1. d.ts文件描述验证<br/>2. 组件接口功能兼容性验证<br/>3. 组件接口联想能力验证 | 组件功能测试通过，组件资料测试通过                           |
| ArkTS      | 编译工具链                                        | IDE端到端编译ArkTS工程功能和性能验证                         | IDE完成ArkTS工程编译功能和性能验证，验收通过                 |
| JS         | API接口                                           | 同ArkTS，JS特有接口差异化测试                                | 验证通过，无关键问题遗留                                     |
| JS         | 组件接口                                          | 1. json文件描述验证<br/>2. 组件接口功能兼容性验证<br/>3. 组件接口联想能力验证 | 组件API接口（JS）已完成文件描述，功能和联想能力验证，无关键问题遗留，通过 |
| JS         | 编译工具链                                        | IDE端到端编译JS工程功能和性能验证                            | IDE完成JS工程编译功能和性能验证，验收通过                    |
| Toolchains | 配置文件合法性检查工具（configcheck&modulecheck） | 验证配置文件的合法性                                         | 验证通过，无关键问题遗留                                     |
| Toolchains | 签名工具(hap-sign-tool)                           | 验证hap通过工具进行签名                                      | 验证通过，无关键问题遗留                                     |
| Toolchains | 资源编译工具(restool)                             | 资源编译工具验证                                             | 验证通过，无关键问题遗留                                     |
| Toolchains | 打包&解包工具(app_packing_tool)                   | 验证hap和app打包和解包能力                                   | 验证通过，无关键问题遗留                                     |
| Toolchains | 调试工具（hdc_std）                               | 验证hdc调试能力                                              | 验证通过，无关键问题遗留                                     |
| Toolchains | SysCap编解码工具(Syscaptools)                     | 验证SysCap<->RPCID和SysCap<->PCID的编解码能力                | 验证通过，无关键问题遗                                       |
| Toolchains | 方舟字节码汇编器(ark_asm)                         | 验证方舟字节码和json相互转换能力                             | 验证通过，无关键问题遗留                                     |
| Preview    | 预览器                                            | IDE端到端验证全部富设备和轻设备组件的功能和预览效果（Windows+Mac） | 预览器功能验证通过                                           |
| Native     | API接口                                           | Native API功能和头文件验证                                   | Native API接口基础功能验证通过                               |
| Native     | 编译工具链                                        | IDE端到端编译构建native工程                                  | native工程编译通过                                           |
| 源码编译   | 应用源码编译                                      | 二进制交付与源码一致                                         | 验证通过，无关键问题遗留                                     |



### **4.7** **资料评估**

 准出结论：Go 

无新增资料需求。
