###### OpenHarmony社区版本发布计划





# OpenHarmony社区版本发布计划：

| **迭代计划** | **版本号**            |**API版本号**| **版本构建** | **版本转测试** | **版本测试完成** |
| ------------ | --------------------- | --------- | ------------ | -------------- | ---------------- |
| IT1          | OpenHarmony 2.2 Beta2  | 6         | 2021/7/21    | 2021/7/21      | **2021/7/30**    |
| IT2          | OpenHarmony 3.0 LTS   | 7         | 2021/9/22    | 2021/9/22      | **2021/9/28**    |
| IT3          | OpenHarmony 3.1 Beta | 8         | 2021/12/22   | 2021/12/22     | **2021/12/30**   |
| IT4          | OpenHarmony 3.1 Release | 8         | 2022/3/9    | 2022/3/9      | **2022/3/30**    |



# 各版本特性交付清单：


## OpenHarmony_release 2.2(beta1)版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                  | status     | sig                | owner                                         |
| :--- | ------------------------------------------------------------ | :-------------------------------------------------- | :--------- | :----------------- | :-------------------------------------------- |
| 1    | [I3HX0V](https://gitee.com/openharmony/hiviewdfx_hilog_lite/issues/I3HX0V) | 【HiLog】L1系统HiLog功能增强                 | 轻量系统 | SIG_BscSoftSrv | [@shenchenkai](https://gitee.com/shenchenkai) |
| 2    | [I3INEZ](https://gitee.com/openharmony/ai_engine/issues/I3INEZ)            | 【AI子系统】AI引擎支持基于共享内存的数据传输 | 轻量系统 | SIG_AI         | [@armylee0](https://gitee.com/armylee0)       |
| 3    | [I3ICFO](https://gitee.com/openharmony/utils_native_lite/issues/I3ICFO) | 【分布式数据管理】提供数据库内容的删除能力          | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 4    | [I3ICH0](https://gitee.com/openharmony/utils_native_lite/issues/I3ICH0) | 【分布式数据管理】提供统一的HAL文件系统操作函数实现 | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 5    | [I3ICG4](https://gitee.com/openharmony/utils_native_lite/issues/I3ICG4) | 【分布式数据管理】提供相关数据存储的原子操作能力    | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 6    | [I3ICGH](https://gitee.com/openharmony/utils_native_lite/issues/I3ICGH) | 【分布式数据管理】提供二进制Value的写入读取能力     | 轻量系统 | SIG_DataManagement   | [@widecode](https://gitee.com/widecode) |
| 7    | [I3NSPB](https://gitee.com/openharmony/graphic_ui/issues/I3NSPB) | 【轻量级图形】UIKit组件支持margin/padding           | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |
| 8    | [I3NSZH](https://gitee.com/openharmony/graphic_ui/issues/I3NSZH) | 【轻量级图形】圆形/胶囊按钮支持缩放和白色蒙层动效   | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua) |


## OpenHarmony_release 2.2(beta2)版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | platform     | sig                  | owner                                               |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :-------------------------------------------------- |
| 1    | [I3NCKH](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCKH) | 【轻内核子系统】L0上支持基于NOR Flash的littlefs文件系统      | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 2    | [I3NCTE](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCTE) | 【轻内核子系统】L0上对外提供统一的文件系统操作接口           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 3    | [I3NCX2](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NCX2) | 【轻内核子系统】L0 补充120个POSIX接口                        | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 4    | [I3NT2C](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2C) | 【轻内核子系统】移植mksh命令解析器                           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 5    | [I3NT2K](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2K) | 【轻内核子系统】shell交互友好性提升                          | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 6    | [I3NT2V](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT2V) | 【轻内核子系统】移植toybox命令集                             | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 7    | [I3NT4N](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT4N) | 【轻内核子系统】Namecache模块                                | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 8    | [I3NT58](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT58) | 【轻内核子系统】Vnode管理                                    | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 9    | [I3NT5Q](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT5Q) | 【轻内核子系统】Lookup模块                                   | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 10   | [I3NT6H](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6H) | 【轻内核子系统】文件系统维测增强                             | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 11   | [I3NT6U](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT6U) | 【轻内核子系统】liteos-a內核模块可配置                       | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 12   | [I3NT78](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT78) | 【轻内核子系统】liteos-a小系统三方芯片适配                   | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 13   | [I3SNIP](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNIP) | 【轻内核子系统】L0支持三方组件Mbedtls编译                    | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 14   | [I3SNKK](https://gitee.com/openharmony/kernel_liteos_m/issues/I3SNKK) | 【轻内核子系统】L0支持三方组件curl编译                       | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 15  | [I3NIME](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NIME) | 【启动恢复子系统】支持恢复出厂设置                           | 轻量系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 16   | [I3NTBC](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NTBC) | 【启动恢复子系统】L0/L1/L2接口优化                           | 轻量系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)           |
| 17   | [I3NN4H](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN4H) | 【DFX子系统】【HiLog】L0系统HiLog功能增强                    | 轻量系统 | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 18  | [I3NN53](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN53) | 【DFX子系统】【HiEvent】L0系统HiEvent功能增强                | 轻量系统 | SIG_BscSoftSrv       | [@shenchenkai](https://gitee.com/shenchenkai)       |
| 19   | [I3ID9Q](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9Q) | 【分布式调度】建立轻量设备DMS与富设备DMS通信通道             | 轻量系统 | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 20  | [I3ID9V](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3ID9V) | 【分布式调度】轻量设备启动富设备上的Ability                  | 轻量系统 | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)             |
| 21  | [I3I1V8](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1V8)         | 【全球化子系统】构建应用资源解析和加载机制                   | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 22  | [I3I1VJ](https://gitee.com/openharmony/global_resmgr_lite/issues/I3I1VJ) | 【全球化子系统】构建资源回溯机制                             | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)           |
| 23   | [I3QE85](https://gitee.com/openharmony/drivers_framework/issues/I3QE85) | 【驱动子系统】L0支持HDF框架                                  | 轻量系统 | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)                 |
| 24   | [I3NSVQ](https://gitee.com/openharmony/graphic_ui/issues/I3NSVQ) | 【轻量级图形】DFX维测能力：UIKit支持显示控件轮廓             | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 25   | [I3NSWY](https://gitee.com/openharmony/graphic_ui/issues/I3NSWY) | 【轻量级图形】ScrollView/List支持通过弧形进度条展示滑动进度  | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 26   | [I3NSZZ](https://gitee.com/openharmony/graphic_ui/issues/I3NSZZ) | 【轻量级图形】支持开关按钮/复选框/单选按钮动效               | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 27   | [I3NSQ6](https://gitee.com/openharmony/graphic_ui/issues/I3NSQ6) | 【轻量级图形】UIKit支持点阵字体产品化解耦                    | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |
| 28   | [I3NSZ1](https://gitee.com/openharmony/graphic_ui/issues/I3NSZ1) | 【轻量级图形】UI框架提供统一多后端框架支持多芯片平台         | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)             |           |
| 29    | [I3NCB9](https://gitee.com/openharmony/third_party_Linux_Kernel/issues/I3NCB9) | 【L1 Linux开源】编译器替换后的内核代码适配                   | 轻量系统 | SIG_Kernel           | [@zzzuo](https://gitee.com/zzzuo)                 |
| 30   | [I3NBVI](https://gitee.com/openharmony/build_lite/issues/I3NBVI) | 【L1 Linux开源】clang替换                                    | 轻量系统 | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 31   | [I3NC8H](https://gitee.com/openharmony/build_lite/issues/I3NC8H) | 【L1 Linux开源】musl库替换                                   | 轻量系统 | SIG_CompileRuntime   | [@zhuoli72](https://gitee.com/zhuoli72)           |
| 32    | [I3NCEF](https://gitee.com/openharmony/build_lite/issues/I3NCEF) | 【L1 Linux开源】工具集替换                                   | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 33   | [I3NCF7](https://gitee.com/openharmony/build_lite/issues/I3NCF7) | 【L1 Linux开源】rootfs替换                                   | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 34   | [I3NCG0](https://gitee.com/openharmony/build_lite/issues/I3NCG0) | 【L1 Linux开源】镜像制作工具替换                             | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 35   | [I3NCGM](https://gitee.com/openharmony/build_lite/issues/I3NCGM) | 【L1 Linux开源】开源编译构建                                 | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 36   | [I3NCCT](https://gitee.com/openharmony/drivers_adapter/issues/I3NCCT) | 【L1 Linux开源】编译器替换后的HDF适配                        | 轻量系统 | SIG_DriverFramework  | [@zianed](https://gitee.com/zianed)               |
| 37   | [I3N0LP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0LP?from=project-issue) | 【全球化子系统】构建自定义数据编译能力                       | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 38   | [I3N0OP](https://gitee.com/openharmony/global_i18n_lite/issues/I3N0OP?from=project-issue) | 【全球化子系统】构建星期、单复数、数字开关国际化能力         | 轻量系统 | SIG_AppFramework     | [@zhengbin5](https://gitee.com/zhengbin5)         |
| 39   | [I3NSY0](https://gitee.com/openharmony/graphic_ui/issues/I3NSY0) | 【轻量级图形】支持A4\A8、LUT8、TSC图片格式作为输入           | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 40   | [I3NT0R](https://gitee.com/openharmony/graphic_ui/issues/I3NT0R) | 【轻量级图形】支持多语言字体对齐                             | 轻量系统 | SIG_GraphicsandMedia | [@niulihua](https://gitee.com/niulihua)           |
| 41   | [I3SNGO](https://gitee.com/openharmony/build_lite/issues/I3SNGO) | 【编译子系统】build_lite支持开源软件的通用patch框架          | 轻量系统 | SIG_CompileRuntime   | [@taiyipei](https://gitee.com/taiyipei)           |
| 42 | [I3ZDIF](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIF) | RQ-[Demo&应用子系统][JSUI]【通用】JS动画（动画样式、渐变样式、转场样式、自定义字体样式） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 43 | [I3ZDIG](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIG) | RQ-[Demo&应用子系统][JSUI]【通用】原子布局 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 44 | [I3ZDIH](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIH) | RQ-[Demo&应用子系统][JSUI]【容器组件】新事件提醒（badge） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 45 | [I3ZDII](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDII) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】自定义组件（CustomComponent） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 46 | [I3ZDIJ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIJ) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】自定义布局（CustomLayout） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 47 | [I3ZDIK](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIK) | RQ-[Demo&应用子系统][JS UI]【HarmonyOS】FA卡片（JsFACard） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 48 | [I3ZDIL](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIL) | RQ-[Demo&应用子系统][多模]【HarmonyOS】多模输入（MultiModeInput） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 49 | [I3ZDIM](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIM) | RQ-[Demo&应用子系统][多模]【HarmonyOS】多模输入事件标准化（MultimodalEvent） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 50 | [I3ZDIN](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIN) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】Fraction | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 51 | [I3ZDIO](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIO) | RQ-[Demo&应用子系统][ServiceAbility]【HarmonyOS】前台服务（ForegroundService） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 52 | [I3ZDIP](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIP) | RQ-[Demo&应用子系统][Ability测试]【HarmonyOS】Ability的自动化测试（Delegator） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 53 | [I3ZDIQ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIQ) | RQ-[Demo&应用子系统][无障碍]【HarmonyOS】accessibility | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 54 | [I3ZDIR](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIR) | RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】AbilityForm | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 55 | [I3ZDIS](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIS) | RQ-[Demo&应用子系统][AI]【HarmonyOS】AI | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 56 | [I3ZDIT](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIT) | RQ-[Demo&应用子系统][媒体]【HarmonyOS】Audio | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 57 | [I3ZDIU](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIU) | RQ-[Demo&应用子系统][媒体]【HarmonyOS】AudioPlayer | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 58 | [I3ZDIW](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIW) | RQ-[Demo&应用子系统][设备]【HarmonyOS】BatteryInfo | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 59 | [I3ZDIX](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIX) | RQ-[Demo&应用子系统][设备]【HarmonyOS】指南针Compass | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 60 | [I3ZDIY](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIY) | RQ-[Demo&应用子系统][安全]【HarmonyOS】DataSecurity | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 61 | [I3ZDIZ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDIZ) | RQ-[Demo&应用子系统][网络]【HarmonyOS】DistributedAbility | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 62 | [I3ZDJ0](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ0) | RQ-[Demo&应用子系统][通用]【HarmonyOS】DistributedCommonEvent | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 63 | [I3ZDJ1](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ1) | RQ-[Demo&应用子系统][数据]【HarmonyOS】DistributedPictures | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 64 | [I3ZDJ3](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ3) | RQ-[Demo&应用子系统][安全]【HarmonyOS】FaceRecognition | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 65 | [I3ZDJ4](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ4) | RQ-[Demo&应用子系统][设备]【HarmonyOS】NFC | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 66 | [I3ZDJ5](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ5) | RQ-[Demo&应用子系统][数据]【HarmonyOS】关系型数据库 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 67 | [I3ZDJ6](https://gitee.com/open_harmony/dashboard?issue_id=I3ZDJ6) | RQ-[Demo&应用子系统][数据]【HarmonyOS】对象关系映射数据库 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 68 | [I3ZRBA](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBA) | 提供系统电源状态机管理能力 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 69 | [I3ZRBV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBV) | 提供休眠运行锁（RunningLock）管理能力 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 70 | [I3ZRCV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRCV) | 提供休眠、唤醒流程管理及实现 | 标准系统 | SIG_DistributedHardwareManagement | [@hhh2](https://gitee.com/hhh2) |
| 71 | [I3ZMUM](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMUM) | 【分布式数据管理子系统】【本地数据库】 轻量级数据库JS API交付，对标开源+小程序 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 72 | [I3ZMW4](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMW4) | 【分布式数据管理子系统】【本地数据库】提供RDB和PREFERENCES的能力 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 73 | [I3ZMX5](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMX5) | 【分布式数据管理子系统】【本地数据库】 支持ResultSet滑动窗口能力 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 74 | [I3YC8O](https://gitee.com/open_harmony/dashboard?issue_id=I3YC8O) | 【分布式数据管理】【分布式数据库】支持JS接口创建分布式数据库 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 75 | [I3WHJS](https://gitee.com/open_harmony/dashboard?issue_id=I3WHJS) | 基于HDF驱动框架提供马达驱动程序适配 | 标准系统 | SIG_DriverFramework | [@chenfeng469](https://gitee.com/chenfeng469) |
| 76 | [I3ZRA7](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRA7) | 基于HDF驱动框架提供加速度传感器驱动程序适配 | 标准系统 | SIG_DriverFramework | [@chenfeng469](https://gitee.com/chenfeng469) |
| 77   | [I3NN88](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN88) | 【DFX子系统】【HiDumper】LiteOS_M系统信息dump工具 | 轻量系统 | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 78    | [I3NN7D](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7D) | 【DFX子系统】【HiDumper】LiteOS_A系统信息dump工具 | 轻量系统 | SIG_BscSoftSrv | [@kkup180](https://gitee.com/kkup180) |
| 79   | [I3NT48](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT48) | 【轻内核子系统】proc文件系统增强                             | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 80   | [I3WLDI](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLDI) | 【轻内核子系统】L0支持轻量级shell框架和常用调测命令           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 81   | [I3WLCN](https://gitee.com/openharmony/kernel_liteos_m/issues/I3WLCN) | 【轻内核子系统】L0 LiteOS-M支持ARM9架构                     | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 82    | [I3NE8P](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NE8P) | 【电源管理】充放电状态查询接口                               | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 83   | [I3NIEJ)](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIEJ) | 【电源管理】电量查询接口                                     | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 84   | [I3NIFG](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFG) | 【电源管理】实现并提供低功耗模式                             | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 85  | [I3NIFR](https://gitee.com/openharmony/powermgr_powermgr_lite/issues/I3NIFR) | 【电源管理】提供低功耗模式统一API                            | 轻量系统 | SIG_HardwareMng      | [@zianed](https://gitee.com/zianed)               |
| 86   | [I3NN7V](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN7V) | 【DFX子系统】【BBoxDetector】LiteOS_A死机重启维测框架        | 轻量系统 | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |
| 87   | [I3NN9B](https://gitee.com/openharmony/hiviewdfx_hiview_lite/issues/I3NN9B) | 【DFX子系统】【BBoxDetector】LiteOS_M死机重启维测框架        | 轻量系统 | SIG_BscSoftSrv       | [@kkup180](https://gitee.com/kkup180)             |
| 88 | [I3ZN3M](https://gitee.com/open_harmony/dashboard?issue_id=I3ZN3M) | 【分布式数据管理】鸿蒙单框架L2分布式数据管理开源 | 标准系统 | SIG_DataManagement | [@widecode](https://gitee.com/widecode) |
| 89 | [I40K12](https://gitee.com/open_harmony/dashboard?issue_id=I40K12) | 【Samples】【JSUI】【容器组件】JS气泡（popup） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 90 | [I40K1P](https://gitee.com/open_harmony/dashboard?issue_id=I40K1P) | 【Samples】【JSUI】【容器组件】下拉刷新容器（refresh） | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 91 | [I40K2A](https://gitee.com/open_harmony/dashboard?issue_id=I40K2A) | 【Samples】【数据】【HarmonyOS】轻量级偏好数据库 | 标准系统 | SIG_Samples | [@illybyy](https://gitee.com/illybyy) |
| 92 | [I40NBW](https://gitee.com/open_harmony/dashboard?issue_id=I40NBW) | 【应用子系统】鸿蒙单框架L2系统应用-设置开源-WLAN | 标准系统 | SIG_SysApplication | [@nicolaswang](https://gitee.com/nicolaswang) |
| 93 | [I41LYF](https://gitee.com/open_harmony/dashboard?issue_id=I41LYF) | 导航栏支持显示BACK、HOME、RECENT菜单 | 标准系统 | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 94 | [I41LSC](https://gitee.com/open_harmony/dashboard?issue_id=I41LSC) | 【SystemUI】SystemUI权限系统弹窗能力 | 标准系统 | SIG_SysApplication | [@liuzhenyu2021](https://gitee.com/liuzhenyu2021) |
| 95 | [I3XY72](https://gitee.com/open_harmony/dashboard?issue_id=I3XY72) | c++与 js时间\日期和数字国际化能力构建 | 标准系统 | SIG_ApplicationFramework | [@meaty-bag-and-wangwang-meat](https://gitee.com/meaty-bag-and-wangwang-meat) |
|96|[I3XLZR](https://gitee.com/open_harmony/dashboard?issue_id=I3XLZR)|AudioService音频服务|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|97|[I3XM04](https://gitee.com/open_harmony/dashboard?issue_id=I3XM04)|Audio音频管理模块及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|98|[I3XM2C](https://gitee.com/open_harmony/dashboard?issue_id=I3XM2C)|CameraService 相机服务|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|99|[I3XM1U](https://gitee.com/open_harmony/dashboard?issue_id=I3XM1U)|Camera相机处理模块及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|100|[I3XM34](https://gitee.com/open_harmony/dashboard?issue_id=I3XM34)|MediaService播放录制服务|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|101|[I3XM2V](https://gitee.com/open_harmony/dashboard?issue_id=I3XM2V)|Media媒体处理模块及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|102|[I41GOS ](https://gitee.com/open_harmony/dashboard?issue_id=I41GOS)|【分布式文件子系统】（需求）基于JS语言实现system.file接口|标准系统|SIG_DataManagement|[@panqinxu](https://gitee.com/panqinxu)|
|103|[I426IN](https://gitee.com/open_harmony/dashboard?issue_id=I426IN)|【组网】自组网管理|标准系统|SIG_SoftBus|[@maerlii](https://gitee.com/maerlii)|
|104|[I40NBW](https://gitee.com/open_harmony/dashboard?issue_id=I40NBW)|WLAN设置项|标准系统|SIG_SystemApplication|[@xiongshiyi](https://gitee.com/xiongshiyi)|
|105|[I400ZM](https://gitee.com/open_harmony/dashboard?issue_id=I400ZM)|【应用子系统】【Launcher】桌面设置界面UX优化，Grid布局桌面支持图标拖动|标准系统|SIG_SystemApplication|[@xiongshiyi](https://gitee.com/xiongshiyi)|
|106|[I41J7Q](https://gitee.com/open_harmony/dashboard?issue_id=I41J7Q)|支持Video组件|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|107|[I41JBF](https://gitee.com/open_harmony/dashboard?issue_id=I41JBF)|支持Camera组件|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|108|[I41JG4](https://gitee.com/open_harmony/dashboard?issue_id=I41JG4)|支持JS与NAPI混合开发接口|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|109|[I3ZRBA](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBA)|提供系统电源状态机管理能力|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|110|[I3ZRBV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRBV)|提供休眠运行锁（RunningLock）管理能力|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|111|[I3ZRCV](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRCV)|提供休眠、唤醒流程管理及实现|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|112|[I3WHJS](https://gitee.com/open_harmony/dashboard?issue_id=I3WHJS)|基于HDF驱动框架提供马达驱动程序适配|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|113|[I3ZRA7](https://gitee.com/open_harmony/dashboard?issue_id=I3ZRA7)|基于HDF驱动框架提供加速度传感器驱动程序适配|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|114|[I41HBJ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBJ)|【驱动子系统】提供Audio HDI接口实现|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|115|[I41HBK](https://gitee.com/open_harmony/dashboard?issue_id=I41HBK)|【驱动子系统】Audio 驱动框架用户态接口库|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|116|[I41HBM](https://gitee.com/open_harmony/dashboard?issue_id=I41HBM)|【驱动子系统】提供支持MPI接口的用户态接口库|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|117|[I41HBN](https://gitee.com/open_harmony/dashboard?issue_id=I41HBN)|【驱动子系统】HDI接口支持跨进程通信|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|118|[I41HBH](https://gitee.com/open_harmony/dashboard?issue_id=I41HBH)|【驱动子系统】基于HDF驱动框架提供WIFI支持HDI接口能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|119|[I41HBG](https://gitee.com/open_harmony/dashboard?issue_id=I41HBG)|【驱动子系统】基于HDF驱动框架提供WIFI支持P2P驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|120|[I41HBI](https://gitee.com/open_harmony/dashboard?issue_id=I41HBI)|【驱动子系统】提供Audio Driver Model驱动模型框架|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|121|[I41HBA](https://gitee.com/open_harmony/dashboard?issue_id=I41HBA)|【驱动子系统】基于HDF驱动框架提供keyboard驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|122|[I41HBZ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBZ)|【驱动子系统】基于HDF框架提供USB device DDK|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|123|[I41HBU](https://gitee.com/open_harmony/dashboard?issue_id=I41HBU)|【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层BufferManager|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|124|[I41HBV](https://gitee.com/open_harmony/dashboard?issue_id=I41HBV)|【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层utils通用组件(thread、event、watchdog)r|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|125|[I41HBX](https://gitee.com/open_harmony/dashboard?issue_id=I41HBX)|【驱动子系统】基于HDF驱动框架提供Camera驱动多平台扩展平台适配|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|126|[I41HBY](https://gitee.com/open_harmony/dashboard?issue_id=I41HBY)|【驱动子系统】基于HDF框架提供USB host DDK|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|127|[I41HBP](https://gitee.com/open_harmony/dashboard?issue_id=I41HBP)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备控制（CameraDevice）|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|128|[I41HBQ](https://gitee.com/open_harmony/dashboard?issue_id=I41HBQ)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Image流控制（StreamOperator）|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|129|[I41HBR](https://gitee.com/open_harmony/dashboard?issue_id=I41HBR)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera HDI接口|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|130|[I41HBS](https://gitee.com/open_harmony/dashboard?issue_id=I41HBS)|【驱动子系统】基于HDF驱动框架提供Pipeline管理 |标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|131|[I41HBT](https://gitee.com/open_harmony/dashboard?issue_id=I41HBT)|【驱动子系统】基于HDF驱动框架提供Camera设备驱动模型框架层设备管理DeviceManager|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|132|[I41HBO](https://gitee.com/open_harmony/dashboard?issue_id=I41HBO)|【驱动子系统】基于HDF驱动框架提供相机标准南向接口Camera设备管理（CameraHost）|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|133|[I3ZVIO](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVIO)|Hi3516DV300开发板上，提供账号无关的设备认证能力|标准系统|SIG_DistributedHardwareManagement|[@locheng7](https://gitee.com/locheng7)|
|134|[I40PB8](https://gitee.com/open_harmony/dashboard?issue_id=I40PB8)|应用侧取消本地所有通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|135|[I40PB0](https://gitee.com/open_harmony/dashboard?issue_id=I40PB0)|应用侧发布本地多行类型通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|136|[I40PB1](https://gitee.com/open_harmony/dashboard?issue_id=I40PB1)|应用侧发布本地长文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|137|[I40PB2](https://gitee.com/open_harmony/dashboard?issue_id=I40PB2)|应用侧发布本地内容资讯类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|138|[I40PB3](https://gitee.com/open_harmony/dashboard?issue_id=I40PB3)|应用侧发布本地其他类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|139|[I40PB4](https://gitee.com/open_harmony/dashboard?issue_id=I40PB4)|应用侧发布本地服务提醒类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|140|[I40PB5](https://gitee.com/open_harmony/dashboard?issue_id=I40PB5)|应用侧发布本地社交通讯类型的普通文本通知|标准系统|SIG_SystemApplication|[@autumn330](https://gitee.com/autumn330)|
|141|[I3XY72](https://gitee.com/open_harmony/dashboard?issue_id=I3XY72)|c++与 js时间\日期和数字国际化能力构建|标准系统|SIG_ApplicationFramework|[@meaty-bag-and-wangwang-meat](https://gitee.com/meaty-bag-and-wangwang-meat)|
|142|[I42IMT](https://gitee.com/open_harmony/dashboard?issue_id=I42IMT)|RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式计算器|标准系统|SIG_SystemApplication|[@purple-ding-gags](https://gitee.com/purple-ding-gags)|
|143|[I42IKN](https://gitee.com/open_harmony/dashboard?issue_id=I42IKN)|RQ-[Demo&应用子系统][分布式]OpenHarmony版本分布式音乐播放器|标准系统|SIG_SystemApplication|[@purple-ding-gags](https://gitee.com/purple-ding-gags)|
|144|[I41JB1](https://gitee.com/openharmony/applications_photos/issues/I41JB1)|【应用子系统】【图库】图库基础功能-大图浏览|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
|145|[I41J2Y](https://gitee.com/openharmony/applications_photos/issues/I41J2Y)|【应用子系统】【图库】图库基础功能-相册管理|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|
|146|[I41JBB](https://gitee.com/openharmony/applications_photos/issues/I41JBB)|【应用子系统】【图库】图库基础功能-Toolbar操作|标准系统|SIG_SystemApplication|[@sunjunxiong](https://gitee.com/sunjunxiong)|


## OpenHarmony_release 3.0(LTS)版本特性清单：

状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | platform     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1 | [I40PAV](https://gitee.com/open_harmony/dashboard?issue_id=I40PAV) | 发布开启一个有页面的Ability的WantAgent通知 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 2 | [I40PAW](https://gitee.com/open_harmony/dashboard?issue_id=I40PAW) | 通知删除接口 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 3 | [I40PAX](https://gitee.com/open_harmony/dashboard?issue_id=I40PAX) | 查看Active通知内容和Active通知个数的接口 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 4 | [I40PAY](https://gitee.com/open_harmony/dashboard?issue_id=I40PAY) | 通知取消订阅 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 5 | [I40PAZ](https://gitee.com/open_harmony/dashboard?issue_id=I40PAZ) | 通知订阅 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 6 | [I426IT](https://gitee.com/open_harmony/dashboard?issue_id=I426IT) | 【组网】组网单框架FWK | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 7 | [I426IM](https://gitee.com/open_harmony/dashboard?issue_id=I426IM) | 【组网】组网框架构建：安全 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 8 | [I426IQ](https://gitee.com/open_harmony/dashboard?issue_id=I426IQ) | 【组网】节点信息管理 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 9 | [I3NIMY](https://gitee.com/open_harmony/dashboard?issue_id=I3NIMY) | 【连接】BR/EDR模块管理 | 标准系统 | SIG_SoftBus | [@tianmeimimi](https://gitee.com/tianmeimimi) |
| 10 | [I426J0](https://gitee.com/open_harmony/dashboard?issue_id=I426J0) | 【传输】通道管理 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 11 | [I3NIZD](https://gitee.com/open_harmony/dashboard?issue_id=I3NIZD) | 【连接】连接策略的定义与管理 | 标准系统 | SIG_SoftBus | [@tianmeimimi](https://gitee.com/tianmeimimi) |
| 12 | [I426IW](https://gitee.com/open_harmony/dashboard?issue_id=I426IW) | 【连接】连接状态机功能实现 | 标准系统 | SIG_SoftBus | [@maerlii](https://gitee.com/maerlii) |
| 13 | [I42UO1](https://gitee.com/open_harmony/dashboard?issue_id=I42UO1) | RQ-[Demo&应用子系统][JSUI][容器组件]JS堆叠容器（stack） | 标准系统 | SIG_SystemApplication | [@adslk](https://gitee.com/adslk) |
| 14 | [I42X0C](https://gitee.com/open_harmony/dashboard?issue_id=I42X0C) | RQ-[Demo&应用子系统][JSUI][容器组件]JS步骤导航器（stepper） | 标准系统 | SIG_SystemApplication | [@gaohui100](https://gitee.com/gaohui100) |
| 15 | [I42WY6](https://gitee.com/open_harmony/dashboard?issue_id=I42WY6) | RQ-[Demo&应用子系统][JSUI][容器组件]JS滑动容器（swiper） | 标准系统 | SIG_SystemApplication | [@gaohui100](https://gitee.com/gaohui100) |
| 16 | [I42UNK](https://gitee.com/open_harmony/dashboard?issue_id=I42UNK) | RQ-[Demo&应用子系统][JSUI][容器组件]JS页签容器（tabs） | 标准系统 | SIG_SystemApplication | [@adslk](https://gitee.com/adslk) |
| 17 | [I42S96](https://gitee.com/open_harmony/dashboard?issue_id=I42S96) | RQ-[Demo&应用子系统][数据][HarmonyOS]融合搜索 | 标准系统 | SIG_SystemApplication | [@guojin26](https://gitee.com/guojin26) |
| 18 | [I40PB6](https://gitee.com/open_harmony/dashboard?issue_id=I40PB6) | 应用侧增加slot | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 19 | [I40PB7](https://gitee.com/open_harmony/dashboard?issue_id=I40PB7) | 应用侧删除slot | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 20 | [I42WA2](https://gitee.com/open_harmony/dashboard?issue_id=I42WA2) | L2 提供 OHOS LLVM编译 | 标准系统 | SIG_CompileRuntime | [@zhuoli72](https://gitee.com/zhuoli72) |
| 21 | [I3U4DP](https://gitee.com/open_harmony/dashboard?issue_id=I3U4DP) | musl侵入式修改分离 | 标准系统 | SIG_CompileRuntime | [@caoruihong](https://gitee.com/caoruihong) |
| 22 | [I42WDD](https://gitee.com/open_harmony/dashboard?issue_id=I42WDD) | L2 musl c库支持 | 标准系统 | SIG_CompileRuntime | [@zhuoli72](https://gitee.com/zhuoli72) |
| 23 | [I4014F](https://gitee.com/open_harmony/dashboard?issue_id=I4014F) | 【帐号子系统】JS API交付，开源+小程序 | 标准系统 | SIG_BasicSoftwareService | [@verystone](https://gitee.com/verystone) |
| 24 | [I436VH](https://gitee.com/open_harmony/dashboard?issue_id=I436VH) | 创建串行任务分发器，使用串行任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 25 | [I436VI](https://gitee.com/open_harmony/dashboard?issue_id=I436VI) | 创建专有任务分发器，使用专有任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 26 | [I436VJ](https://gitee.com/open_harmony/dashboard?issue_id=I436VJ) | 创建全局并发任务分发器，使用全局并发任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 27 | [I436VK](https://gitee.com/open_harmony/dashboard?issue_id=I436VK) | 创建并发任务分发器，使用并发任务分发器执行任务 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 28 | [I436VL](https://gitee.com/open_harmony/dashboard?issue_id=I436VL) | ces部件化改造 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 29 | [I436VM](https://gitee.com/open_harmony/dashboard?issue_id=I436VM) | ans部件化改造 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 30 | [I436VX](https://gitee.com/open_harmony/dashboard?issue_id=I436VX) | 提供分布式的回调Native接口 | 标准系统 | SIG_ApplicationFramework | [@autumn330](https://gitee.com/autumn330) |
| 31 | [I436N0](https://gitee.com/open_harmony/dashboard?issue_id=I436N0) | 支持应用包信息分布式存储能力 | 标准系统 | SIG_ApplicationFramework | [@fuzhangHW](https://gitee.com/fuzhangHW) |
| 32 | [I4312I](https://gitee.com/open_harmony/dashboard?issue_id=I4312I) | 支持全新开发范式 | 标准系统 | SIG_ApplicationFramework | [@zhanghaibo0](https://gitee.com/zhanghaibo0) |
| 33 | [I4313W](https://gitee.com/open_harmony/dashboard?issue_id=I4313W) | 【分布式文件子系统】（需求）ext4&f2fs拍包工具 | 标准系统 | SIG_DataManagement | [@panqinxu](https://gitee.com/panqinxu) |
| 34 | [I41H57](https://gitee.com/open_harmony/dashboard?issue_id=I41H57) | 【驱动子系统】基于HDF驱动框架提供ADC平台总线驱动 | 标准系统 | SIG_DriverFramework | [@zianed](https://gitee.com/zianed) |
| 35    | [I3QEVG](https://gitee.com/openharmony/distributedschedule_dms_fwk_lite/issues/I3QEVG) | 【分布式调度】轻设备获取调用者APP的APPID并传输到富设备      | 轻量系统 | SIG_AppFramework     | [@lijiarun](https://gitee.com/lijiarun)            |
|36|[I43W4L](https://gitee.com/open_harmony/dashboard?issue_id=I43W4L)|RQ-[Demo&应用子系统][JSUI][基础组件]JS基础组件|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|37|[I43XA7](https://gitee.com/open_harmony/dashboard?issue_id=I43XA7)|RQ-[Demo&应用子系统][JSUI][图表组件]chart|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|38|[I43W8L](https://gitee.com/open_harmony/dashboard?issue_id=I43W8L)|RQ-[Demo&应用子系统][JSUI][滑动选择器组件] picker|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|39|[I41HBB](https://gitee.com/open_harmony/dashboard?issue_id=I41HBB)|【驱动子系统】基于HDF驱动框架提供mouse驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
| 40   | [I3XCB5](https://gitee.com/openharmony/appexecfwk_appexecfwk_lite/issues/I3XCB5) | 【应用程序框架】按照应用粒度的存储资源使用统计       | 轻量系统 | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)            |
| 41   | [I3NK7D](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NK7D) | 【多媒体子系统】适配新南向接口                               | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 42   | [I3NM60](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM60) | 【多媒体子系统】相机metadata管理及相机静态能力查询           | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 43   | [I3NM6F](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM6F) | 【多媒体子系统】相机设备管理                                 | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 44   | [I3NM73](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM73) | 【多媒体子系统】相机图像帧管理                               | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 45   | [I3NM8J](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NM8J) | 【多媒体子系统】本地mp3播放支持                              | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
| 46   | [I3NMMU](https://gitee.com/openharmony/multimedia_utils_lite/issues/I3NMMU) | 【多媒体子系统】编码视频流和音频流处理支持                   | 轻量系统 | SIG_GraphicsAndMedia | [@zhu-mingliang](https://gitee.com/zhu-mingliang)   |
|47|[I43G6T](https://gitee.com/open_harmony/dashboard?issue_id=I43G6T)|WM Client架构演进|标准系统|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|48|[I43HMM](https://gitee.com/open_harmony/dashboard?issue_id=I43HMM)|WM Server架构演进|标准系统|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|49|[I43I3O](https://gitee.com/open_harmony/dashboard?issue_id=I43I3O)|RQ-[图形子系统][vsync模块][vsync]vsync架构演进|标准系统|SIG_GraphicsandMedia|[@lz-230](https://gitee.com/lz-230)|
|50|[I44TNC](https://gitee.com/open_harmony/dashboard?issue_id=I44TNC)|RQ-[Demo&应用子系统][JSUI][Menu/Option]JSMenu|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|51|[I452UD](https://gitee.com/open_harmony/dashboard?issue_id=I452UD)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】工具栏|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|52|[I44TN0](https://gitee.com/open_harmony/dashboard?issue_id=I44TN0)|RQ-[Demo&应用子系统][JSUI][滑动条] slider|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|53|[I41HC0](https://gitee.com/open_harmony/dashboard?issue_id=I41HC0)|【驱动子系统】基于HDF驱动框架提供Display HDI的服务化|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|54|[I41LWL](https://gitee.com/open_harmony/dashboard?issue_id=I41LWL)|【SystemUI】状态栏最大最小化|标准系统|SIG_SystemApplication|[@liuzhenyu2021](https://gitee.com/liuzhenyu2021)|
|55|[I3NIOF](https://gitee.com/openharmony/communication_dsoftbus/issues/I3NIOF)|【传输】传输SDK|轻量系统|SIG_SoftBus|[@jiangkuaixue](https://gitee.com/jiangkuaixue)|
|56|[I3XHVJ](https://gitee.com/open_harmony/dashboard?issue_id=I3XHVJ)|支持全量升级包升级|标准系统|SIG_BasicSoftwareService|[@ailorna](https://gitee.com/ailorna)|
|57|[I3XHVP](https://gitee.com/open_harmony/dashboard?issue_id=I3XHVP)|支持差分升级包升级|标准系统|SIG_BasicSoftwareService|[@ailorna](https://gitee.com/ailorna)|
|58|[I436VT](https://gitee.com/open_harmony/dashboard?issue_id=I436VT)|安装读取shortcut信息|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
| 59    | [I3NN1Z](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3NN1Z) | 【应用程序框架】轻量级实现弹窗授权动态授权机制               | 轻量系统 | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)              |
| 60    | [I3NTAZ](https://gitee.com/openharmony/security_huks/issues/I3NTAZ) | 【安全】轻量级实现弹窗授权动态授权机制                       | 轻量系统 | SIG_Security         | [@scuteehuangjun](https://gitee.com/scuteehuangjun) |
|61|[I45ZKP](https://gitee.com/open_harmony/dashboard?issue_id=I45ZKP)|RQ-[Demo&应用子系统][JSUI][画布组件] JsCanvas|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|62|[I466KX](https://gitee.com/open_harmony/dashboard?issue_id=I466KX)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】 栅格布局|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|63|[I45YM2](https://gitee.com/open_harmony/dashboard?issue_id=I45YM2)|RQ-[Demo&应用子系统][JS UI]【OpenHarmony】JS自定义组件（JSUICustomComponent）|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|64|[I44Y4J](https://gitee.com/open_harmony/dashboard?issue_id=I44Y4J)|RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应卡片（AdaptiveServiceWidget）|标准系统|SIG_SystemApplication|[@caopan_com](https://gitee.com/caopan_com)|
|65|[I44Y0N](https://gitee.com/open_harmony/dashboard?issue_id=I44Y0N)|RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应页面（AdaptivePortalPage）|标准系统|SIG_SystemApplication|[@wangli325](https://gitee.com/wangli325)|
|66|[I44Y15](https://gitee.com/open_harmony/dashboard?issue_id=I44Y15)|RQ-[Demo&应用子系统][JS UI]【HarmonyOS】自适应效率型首页（AdaptivePortalList）|标准系统|SIG_SystemApplication|[@wangli325](https://gitee.com/wangli325)|
|67|[I46ZCN](https://gitee.com/open_harmony/dashboard?issue_id=I46ZCN)|RQ-[Demo&应用子系统][JAVA UI]【HarmonyOS】添加NativeLayer示例|标准系统|SIG_SystemApplication|[@guojin26](https://gitee.com/guojin26)|
|68|[I3ZVTJ](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVTJ)|【分布式任务调度子系统】接收远端拉起FA请求，跨设备拉起远端FA|标准系统|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|69|[I3ZVTT](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVTT)|【分布式任务调度子系统】鸿蒙单框架L2分布式能力建设-SAMGR模块构建|标准系统|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|70|[I3ZMY9](https://gitee.com/open_harmony/dashboard?issue_id=I3ZMY9)|【分布式数据管理子系统】【本地数据库】 XTS测试用例|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
|71|[I41H55](https://gitee.com/open_harmony/dashboard?issue_id=I41H55)|【驱动子系统】基于HDF驱动框架提供I2S/PCM平台总线驱动|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|72|[I41HBF](https://gitee.com/open_harmony/dashboard?issue_id=I41HBF)|【驱动子系统】基于HDF驱动框架提供Display驱动模型兼容DRM显示框架|标准系统|SIG_DistributedHardwareManagement|[@zianed](https://gitee.com/zianed)|
|73|[I46J19](https://gitee.com/open_harmony/dashboard?issue_id=I46J19)|add jsapi in compileruntime|标准系统|SIG_CompileRuntime|[@xliu-huanwei](https://gitee.com/xliu-huanwei)|
|74|[I46N37](https://gitee.com/open_harmony/dashboard?issue_id=I46N37)|升级quickjs使用worker|标准系统|SIG_CompileRuntime|[@wpyhuawei](https://gitee.com/wpyhuawei)|
|75|[I40PBC](https://gitee.com/open_harmony/dashboard?issue_id=I40PBC)|应用侧发布本地分组的普通通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|76|[I40PBF](https://gitee.com/open_harmony/dashboard?issue_id=I40PBF)|在免打扰模式下发布通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|77|[I40PBG](https://gitee.com/open_harmony/dashboard?issue_id=I40PBG)|发布开启一个无页面的Ability的wantAgent|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|78|[I40PBH](https://gitee.com/open_harmony/dashboard?issue_id=I40PBH)|取消WantAgent的实例|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|79|[I40PBI](https://gitee.com/open_harmony/dashboard?issue_id=I40PBI)|发布公共事件的WantAgent通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|80|[I40PBM](https://gitee.com/open_harmony/dashboard?issue_id=I40PBM)|应用侧取消本地通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|81|[I40PBN](https://gitee.com/open_harmony/dashboard?issue_id=I40PBN)|应用侧发布声音通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|82|[I40PBO](https://gitee.com/open_harmony/dashboard?issue_id=I40PBO)|应用侧发布振动通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|83|[I40PBP](https://gitee.com/open_harmony/dashboard?issue_id=I40PBP)|应用侧发布本地有输入框的通知（NotificationUserInput）|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
| 84    | [I46W6Q](https://gitee.com/openharmony/global_i18n_lite/issues/I46W6Q) | 【全球化】新增31种语言支持              | 轻量系统 | SIG_AppFramework     | [@zhiweilai](https://gitee.com/zhiweilai)              |
|85|[I47B4N](https://gitee.com/open_harmony/dashboard?issue_id=I47B4N)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】页面路由|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|86|[I479L2](https://gitee.com/open_harmony/dashboard?issue_id=I479L2)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】 系统时间与定时器|标准系统|SIG_SystemApplication|[@adslk](https://gitee.com/adslk)|
|87|[I48CJ3](https://gitee.com/open_harmony/dashboard?issue_id=I48CJ3)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】设备信息|标准系统|SIG_SystemApplication|[@caopan_com](https://gitee.com/caopan_com)|
|88|[I48VL4](https://gitee.com/open_harmony/dashboard?issue_id=I48VL4)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】设置屏幕亮度|标准系统|SIG_SystemApplication|[@caopan_com](https://gitee.com/caopan_com)|
|89|[I49B4X](https://gitee.com/open_harmony/dashboard?issue_id=I49B4X)|RQ-[Demo&应用子系统][JSUI]【OpenHarmony】国际化|标准系统|SIG_SystemApplication|[@gaohui100](https://gitee.com/gaohui100)|
|90|[I3ZXZF](https://gitee.com/open_harmony/dashboard?issue_id=I3ZXZF)|【Kernel升级适配】OpenHarmony L2内核版本升级至5.10|标准系统|SIG_Kernel|[@z-jax](https://gitee.com/z-jax)|
|91|[I41HC1](https://gitee.com/open_harmony/dashboard?issue_id=I41HC1)|【驱动子系统】基于HDF驱动框架提供Codec HDI的服务化|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|92|[I41HB1](https://gitee.com/open_harmony/dashboard?issue_id=I41HB1)|【驱动子系统】基于HDF驱动框架提供陀螺仪Sensor驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|93|[I41HBE](https://gitee.com/open_harmony/dashboard?issue_id=I41HBE)|【驱动子系统】基于HDF驱动框架提供backlight驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|94|[I41HB5](https://gitee.com/open_harmony/dashboard?issue_id=I41HB5)|【驱动子系统】基于HDF驱动框架提供压力Sensor驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|95|[I41HB4](https://gitee.com/open_harmony/dashboard?issue_id=I41HB4)|【驱动子系统】基于HDF驱动框架提供霍尔Sensor驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|96|[I41H50](https://gitee.com/open_harmony/dashboard?issue_id=I41H50)|【驱动子系统】驱动hdi-gen开发工具|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|97|[I41HBD](https://gitee.com/open_harmony/dashboard?issue_id=I41HBD)|【驱动子系统】基于HDF驱动框架提供Encoder驱动能力|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|98|[I3NJ0R](https://gitee.com/open_harmony/dashboard?issue_id=I3NJ0R)|【发现】发现调度模块功能实现|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|99|[I3NIPH](https://gitee.com/open_harmony/dashboard?issue_id=I3NIPH)|【传输】消息传输|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|100|[I3NIPO](https://gitee.com/open_harmony/dashboard?issue_id=I3NIPO)|【传输】Byte传输|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|101|[I3NIOF](https://gitee.com/open_harmony/dashboard?issue_id=I3NIOF)|【传输】传输SDK|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|102|[I3NINO](https://gitee.com/open_harmony/dashboard?issue_id=I3NINO)|【传输】会话协商|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|103|[I40PBD](https://gitee.com/open_harmony/dashboard?issue_id=I40PBD)|2个不同的slot，加入到同一个Slot组里面|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|104|[I40PBJ](https://gitee.com/open_harmony/dashboard?issue_id=I40PBJ)|提供管理角标显示/隐藏的接口|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|105|[I40PBK](https://gitee.com/open_harmony/dashboard?issue_id=I40PBK)|提供管理通知许可的接口（设置和查询）|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|106|[I40PBL](https://gitee.com/open_harmony/dashboard?issue_id=I40PBL)|应用删除SlotGroup|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|107|[I40PBQ](https://gitee.com/open_harmony/dashboard?issue_id=I40PBQ)|发布带ActionButton的本地通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|108|[I40PBR](https://gitee.com/open_harmony/dashboard?issue_id=I40PBR)|通知流控处理|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|109|[I40PBT](https://gitee.com/open_harmony/dashboard?issue_id=I40PBT)|死亡监听|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|110|[I40PBU](https://gitee.com/open_harmony/dashboard?issue_id=I40PBU)|通知shell命令|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|111|[I49HOX](https://gitee.com/open_harmony/dashboard?issue_id=I49HOX)|工具链提供维测能力|标准系统|SIG_CompileRuntime|[@dhy308](https://gitee.com/dhy308)|
|112|[I40OPG](https://gitee.com/open_harmony/dashboard?issue_id=I40OPG)|【定时服务】非功能性需求|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|113|[I40OPH](https://gitee.com/open_harmony/dashboard?issue_id=I40OPH)|【定时服务】时间时区同步|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|114|[I40OPI](https://gitee.com/open_harmony/dashboard?issue_id=I40OPI)|【定时服务】定时器功能|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|115|[I40OPJ](https://gitee.com/open_harmony/dashboard?issue_id=I40OPJ)|【定时服务】时间时区管理|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|116|[I3ZQED](https://gitee.com/open_harmony/dashboard?issue_id=I3ZQED)|【帐号子系统】添加分布式帐号登录状态IPC消息权限检查|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|117|[I40MWK](https://gitee.com/open_harmony/dashboard?issue_id=I40MWK)|构建语言和地区配置和区域显示能力|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|118|[I40OWT](https://gitee.com/open_harmony/dashboard?issue_id=I40OWT)|【搜网】Radio状态管理|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|119|[I40OWU](https://gitee.com/open_harmony/dashboard?issue_id=I40OWU)|【搜网】搜网注册|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|120|[I40OWN](https://gitee.com/open_harmony/dashboard?issue_id=I40OWN)|【SIM卡】卡状态处理|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|121|[I40OWO](https://gitee.com/open_harmony/dashboard?issue_id=I40OWO)|【SIM卡】解锁卡pin、puk|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|122|[I40OWM](https://gitee.com/open_harmony/dashboard?issue_id=I40OWM)|【SIM卡】卡账户处理|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|123|[I40OX3](https://gitee.com/open_harmony/dashboard?issue_id=I40OX3)|【短彩信】提供小区广播的能力|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|124|[I40OX6](https://gitee.com/open_harmony/dashboard?issue_id=I40OX6)|【短彩信】提供短信基本配置功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|125|[I40OSY](https://gitee.com/open_harmony/dashboard?issue_id=I40OSY)|【SIM卡】提供拷贝、删除、更新、获取卡短信的能力供电话子系统内部使用|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|126|[I40OTN](https://gitee.com/open_harmony/dashboard?issue_id=I40OTN)|【通话管理】CS域发送MMI命令|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|127|[I40OTS](https://gitee.com/open_harmony/dashboard?issue_id=I40OTS)|【通话管理】CS域DTMF功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|128|[I40OTW](https://gitee.com/open_harmony/dashboard?issue_id=I40OTW)|【通话管理】CS通话基础功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|129|[I40OTX](https://gitee.com/open_harmony/dashboard?issue_id=I40OTX)|【通话管理】CS通话扩展功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|130|[I40OTY](https://gitee.com/open_harmony/dashboard?issue_id=I40OTY)|【SIM卡】G/U卡文件信息获取、保存|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|131|[I40OU3](https://gitee.com/open_harmony/dashboard?issue_id=I40OU3)|【搜网】驻网信息(运营商信息及SPN广播GSM）|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|132|[I40OU5](https://gitee.com/open_harmony/dashboard?issue_id=I40OU5)|【搜网】网络状态(漫游、GSM/LTE/WCDMA接入技术）|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|133|[I40OU7](https://gitee.com/open_harmony/dashboard?issue_id=I40OU7)|【搜网】信号强度(WCDMA/GSM/LTE)|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|134|[I40OUC](https://gitee.com/open_harmony/dashboard?issue_id=I40OUC)|【短彩信】提供发送短信功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|135|[I40OUF](https://gitee.com/open_harmony/dashboard?issue_id=I40OUF)|【短彩信】提供接收短信功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|136|[I40OTT](https://gitee.com/open_harmony/dashboard?issue_id=I40OTT)|【通话管理】CS域呼叫等待功能|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
|137|[I49HPE](https://gitee.com/open_harmony/dashboard?issue_id=I49HPE)|独立发布SDK能力支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|138|[I49CTN](https://gitee.com/open_harmony/dashboard?issue_id=I49CTN)|【hdc_std】支持openharmony sdk独立发布|标准系统|SIG_R&DToolChain|[@chuxuezhe111](https://gitee.com/chuxuezhe111)|
|139|[I49HLR](https://gitee.com/open_harmony/dashboard?issue_id=I49HLR)|【Build】OpenHarmony SDK的打包和编译|标准系统|SIG_CompileRuntime|[@weichaox](https://gitee.com/weichaox)|
|140|[I40OWF](https://gitee.com/open_harmony/dashboard?issue_id=I40OWF)|【SIM卡】随卡功能实现，包括获取当前运营商配置等|标准系统|SIG_SoftBus|[@zhang-hai-feng](https://gitee.com/zhang-hai-feng)|
| 141    | [I3NT3F](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT3F) | 【轻内核子系统】内核支持trace功能                            | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
| 142   | [I3NT63](https://gitee.com/openharmony/kernel_liteos_a/issues/I3NT63) | 【轻内核子系统】pagecache功能完善                            | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)               |
|143|[I49V7K](https://gitee.com/open_harmony/dashboard?issue_id=I49V7K)|test code static check|标准系统|SIG_BasicSoftwareService|[@skyblackleon](https://gitee.com/skyblackleon)|
|144|[I49XVK](https://gitee.com/open_harmony/dashboard?issue_id=I49XVK)|AA/APPEXE/IPC合入master|标准系统|SIG_ApplicationFramework|[@fuzhangHW](https://gitee.com/fuzhangHW)|
|145|[I43UU4](https://gitee.com/open_harmony/dashboard?issue_id=I43UU4)|JS应用生命周期补充支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|146|[I43V4W](https://gitee.com/open_harmony/dashboard?issue_id=I43V4W)|支持使用JS开发service ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|147|[I43V73](https://gitee.com/open_harmony/dashboard?issue_id=I43V73)|支持使用JS开发data ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|148|[I43UZ0](https://gitee.com/open_harmony/dashboard?issue_id=I43UZ0)|支持系统服务弹窗|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|149|[I3ZVIO](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVIO)|Hi3516DV300开发板上，提供账号无关的设备认证能力|标准系统|SIG_DistributedHardwareManagement|[@locheng7](https://gitee.com/locheng7)|
|150|[I3ZVUD](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVUD)|L2系统上为系统服务（应用）提供kit接口（JS）|标准系统|SIG_DistributedHardwareManagement|[@locheng7](https://gitee.com/locheng7)|
|151|[I4A3YY](https://gitee.com/open_harmony/dashboard?issue_id=I4A3YY)|ACE2.0方舟对接|标准系统|SIG_CompileRuntime|[@guobingbing3](https://gitee.com/guobingbing3)|
|152|[I40SQU](https://gitee.com/open_harmony/dashboard?issue_id=I40SQU)|【工具链】提供hdc java lib|标准系统|SIG_R&DToolChain|[@chuxuezhe111](https://gitee.com/chuxuezhe111)|
|153|[I474ZZ](https://gitee.com/open_harmony/dashboard?issue_id=I474ZZ)|【分布式数据管理】【JS API接口】增加关系型数据库JS API|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
|154|[I40PBE](https://gitee.com/open_harmony/dashboard?issue_id=I40PBE)|应用侧发布本地带应用ICON的普通通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|155|[I43UU4](https://gitee.com/open_harmony/dashboard?issue_id=I43UU4)|JS应用生命周期补充支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|156|[I43UU4](https://gitee.com/open_harmony/dashboard?issue_id=I43UU4)|JS应用生命周期补充支持|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|157|[I43V4W](https://gitee.com/open_harmony/dashboard?issue_id=I43V4W)|支持使用JS开发service ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|158|[I43V73](https://gitee.com/open_harmony/dashboard?issue_id=I43V73)|支持使用JS开发data ability|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|159|[I43UZ0](https://gitee.com/open_harmony/dashboard?issue_id=I43UZ0)|支持系统服务弹窗|标准系统|SIG_ApplicationFramework|[@zhanghaibo0](https://gitee.com/zhanghaibo0)|
|160|[I42TIB](https://gitee.com/open_harmony/dashboard?issue_id=I42TIB)|RQ-[媒体子系统][Media][媒体录制器]音视频录制及API|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|161|[I42TMC](https://gitee.com/open_harmony/dashboard?issue_id=I42TMC)|RQ-[媒体子系统][Camera][相机框架管理]相机录像功能|标准系统|SIG_GraphicsandMedia|[@magekkkk](https://gitee.com/magekkkk)|
|162|[I3ZVT4](https://gitee.com/open_harmony/dashboard?issue_id=I3ZVT4)|【分布式任务调度子系统】鸿蒙单框架L2分布式能力建设-跨设备绑定元能力|标准系统|SIG_DataManagement|[@zjucx](https://gitee.com/zjucx)|
|163|[I49HB0](https://gitee.com/open_harmony/dashboard?issue_id=I49HB0)|【分布式任务调度子系统】启动、绑定能力添加组件visible权限校验|标准系统|SIG_DataManagement|[@zmxlye](https://gitee.com/zmxlye)|
|164|[I40121](https://gitee.com/open_harmony/dashboard?issue_id=I40121)|【Kernel升级适配】HDF适配OpenHarmony 5.10内核|标准系统|SIG_DriverFramework|[@yuanbogit](https://gitee.com/yuanbogit)|
|165|[I3ZY55](https://gitee.com/open_harmony/dashboard?issue_id=I3ZY55)|【Kernel升级适配】Hi3516DV300开发板适配OpenHarmony 5.10内核|标准系统|SIG_Kernel|[@z-jax](https://gitee.com/z-jax)|
|166|[I441K6](https://gitee.com/open_harmony/dashboard?issue_id=I441K6)|L2构建分布式权限管理主体标识转换能力|标准系统|SIG_Security|[@xuwenfang](https://gitee.com/xuwenfang)|
|167|[I4446U](https://gitee.com/open_harmony/dashboard?issue_id=I4446U)|L2构建分布式权限同步能力|标准系统|SIG_Security|[@xuwenfang](https://gitee.com/xuwenfang)|
|168|[I4447R](https://gitee.com/open_harmony/dashboard?issue_id=I4447R)|L2构建分布式权限管理能力|标准系统|SIG_Security|[@xuwenfang](https://gitee.com/xuwenfang)|
|169|[I3NIQX](https://gitee.com/open_harmony/dashboard?issue_id=I3NIQX)|【连接】BLE模块管理|标准系统|SIG_SoftBus|[@tianmeimimi](https://gitee.com/tianmeimimi)|
|170|[I426J6](https://gitee.com/open_harmony/dashboard?issue_id=I426J6)|【传输】文件传输|标准系统|SIG_SoftBus|[@maerlii](https://gitee.com/maerlii)|
|171|[I426J3](https://gitee.com/open_harmony/dashboard?issue_id=I426J3)|【传输】TCP通道复用打开和关闭|标准系统|SIG_SoftBus|[@maerlii](https://gitee.com/maerlii)|
|172|[I40PBB](https://gitee.com/open_harmony/dashboard?issue_id=I40PBB)|应用侧发布本地图片类型通知|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|173|[I40PBS](https://gitee.com/open_harmony/dashboard?issue_id=I40PBS)|通知图片大小限制|标准系统|SIG_ApplicationFramework|[@autumn330](https://gitee.com/autumn330)|
|174|[I4BE9N](https://gitee.com/open_harmony/dashboard?issue_id=I4BE9N)|modify dataabilityDB for LTS branch|标准系统|SIG_BasicSoftwareService|[@skyblackleon](https://gitee.com/skyblackleon)|
|175|[I48DFB](https://gitee.com/open_harmony/dashboard?issue_id=I48DFB)|【分布式任务调度子系统】分布式调度支持元能力迁移管理能力|标准系统|SIG_DataManagement|[@wangdd__zju](https://gitee.com/wangdd__zju)|
|176|[I48BOB](https://gitee.com/open_harmony/dashboard?issue_id=I48BOB)|【分布式文件子系统】（需求）JS 存储框架开发|标准系统|SIG_DataManagement|[@gudehe](https://gitee.com/gudehe)|
|177|[I4A3LY](https://gitee.com/open_harmony/dashboard?issue_id=I4A3LY)|【分布式文件子系统】（需求）JS 存储框架挂载能力 - FS manager|标准系统|SIG_DataManagement|[@zhangzhiwi](https://gitee.com/zhangzhiwi)|
|178|[I4BXPQ](https://gitee.com/open_harmony/dashboard?issue_id=I4BXPQ)|【DFX】libhicollie支持OpenHarmony standard|标准系统|SIG_BasicSoftwareService|[@stesen](https://gitee.com/stesen)|
|179|[I4BXMM](https://gitee.com/open_harmony/dashboard?issue_id=I4BXMM)|【DFX】libhitrace支持OpenHarmony standard|标准系统|SIG_BasicSoftwareService|[@stesen](https://gitee.com/stesen)|
|180|[I4BY0R](https://gitee.com/open_harmony/dashboard?issue_id=I4BY0R)|【DFX】鸿蒙应用事件打点接口与鸿蒙应用事件管理（JS）|标准系统|SIG_BasicSoftwareService|[@lyj](https://gitee.com/lyj_love_code)|

## OpenHarmony_release 3.1(Beta)版本特性清单：
状态说明：discussion(方案讨论，需求未接受)，Reject(未纳入版本)，developing(开发中)，Testing(测试中)，Accepted(已验收)

| no   | issue                                                        | feture description                                           | platform     | sig                  | owner                                             |
| :--- | ------------------------------------------------------------ | :----------------------------------------------------------- | :--------- | :------------------- | :------------------------------------------------ |
| 1   | [I3XGJH](https://gitee.com/openharmony/startup_init_lite/issues/I3XGJH) | init基础环境构建                             | 轻量系统 | SIG_BscSoftSrv| [@xionglei6](https://gitee.com/xionglei6) |
| 2   | [I3XGKV](https://gitee.com/openharmony/startup_init_lite/issues/I3XGKV) | sytemparameter管理                            | 轻量系统 | SIG_BscSoftSrv| [@xionglei6](https://gitee.com/xionglei6) |
| 3   | [I3XGLN](https://gitee.com/openharmony/startup_init_lite/issues/I3XGLN) | init 脚本管理                            | 轻量系统 | SIG_BscSoftSrv| [@xionglei6](https://gitee.com/xionglei6) |
| 4   | [I3XGM3](https://gitee.com/openharmony/startup_init_lite/issues/I3XGM3) | init 服务管理                            | 轻量系统 | SIG_BscSoftSrv| [@xionglei6](https://gitee.com/xionglei6) |
| 5   | [I3XGMQ](https://gitee.com/openharmony/startup_init_lite/issues/I3XGMQ) | 基础权限管理                             | 轻量系统 | SIG_BscSoftSrv| [@xionglei6](https://gitee.com/xionglei6) |
| 6   | [I3XGN8](https://gitee.com/openharmony/startup_init_lite/issues/I3XGN8) | bootimage构建和加载                             | 轻量系统 | SIG_BscSoftSrv| [@xionglei6](https://gitee.com/xionglei6) |
| 7   | [I3XGO7](https://gitee.com/openharmony/startup_init_lite/issues/I3XGO7) | uevent 管理                            | 轻量系统 | SIG_BscSoftSrv| [@xionglei6](https://gitee.com/xionglei6) |
| 8   | [I4BX5Z](https://gitee.com/openharmony/multimedia_histreamer/issues/I4BX5Z) | 【需求】HiStreamer支持音频播放和控制             | 轻量系统 | SIG_GraphicsandMedia         | [@guodongchen](https://gitee.com/guodongchen) |
| 9   | [I4BX8A](https://gitee.com/openharmony/multimedia_histreamer/issues/I4BX8A) | 【需求】HiStreamer支持常见音频格式mp3/wav的播放   | 轻量系统 | SIG_GraphicsandMedia         | [@guodongchen](https://gitee.com/guodongchen) |
| 10   | [I4BX9E](https://gitee.com/openharmony/multimedia_histreamer/issues/I4BX9E) | 【需求】HiStreamer播放引擎框架需求               | 轻量系统 | SIG_GraphicsandMedia         | [@guodongchen](https://gitee.com/guodongchen) |
| 11    | [I3XGNM](https://gitee.com/openharmony/startup_init_lite/issues/I3XGNM) | 烧写模式支持                           | 轻量系统 | SIG_BscSoftSrv           | [@xionglei6](https://gitee.com/xionglei6) |
| 12    | [I4FL3F](https://e.gitee.com/open_harmony/dashboard?issue=I4FL3F) | 3516开发板多模输入触屏和Back适配验证                          | 标准系统 | SIG_HardwareMgr           | [@hhh2](https://gitee.com/hhh2) |
| 13   | [I4DK89](https://gitee.com/openharmony/multimedia_histreamer/issues/I4DK89) | 【需求】HiStreamer插件框架需求                              | 轻量系统 | SIG_GraphicsandMedia | [@guodongchen](https://gitee.com/guodongchen) |
| 14   | [I4DK8D](https://gitee.com/openharmony/multimedia_histreamer/issues/I4DK8D) | 【需求】HiStreamer性能和DFX需求                             | 轻量系统 | SIG_GraphicsandMedia | [@guodongchen](https://gitee.com/guodongchen) |
| 15    | [I3ND6Y](https://gitee.com/openharmony/kernel_liteos_a/issues/I3ND6Y) | 【性能】OS内核&驱动启动优化                           | 轻量系统 | SIG_Kernel           | [@kkup180](https://gitee.com/kkup180)             |
| 16    | [I3NTCT](https://gitee.com/openharmony/startup_appspawn_lite/issues/I3NTCT) | 【启动恢复子系统】Linux版本init支持热插拔                    | 轻量系统 | SIG_BscSoftSrv       | [@handyohos](https://gitee.com/handyohos)         |
| 17    | [I3O2G8](https://gitee.com/openharmony/aafwk_aafwk_lite/issues/I3O2G8?from=project-issue) | 【应用程序框架】轻量级应用实现entity标签                     | 轻量系统 | SIG_AppFramework     | [@autumn](https://gitee.com/autumn330)|
| 18   | [I3NTDP](https://gitee.com/openharmony/communication_wifi_aware/issues/I3NTDP) | 【电话服务】支持轻量级mbed TLS协议栈                      | 轻量系统 | SIG_SoftBus          | [@rain_myf](https://gitee.com/rain_myf) |
|19|[I4M8FW](https://gitee.com/openharmony/account_os_account/issues/I4M8FF?from=project-issue)|【新增特性】支持应用账号基础信息管理|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|20|[I4MBQE](https://gitee.com/openharmony/miscservices_time/issues/I4MBQE)|新增特性：时间时区管理|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|21|[I4MBQF](https://gitee.com/openharmony/notification_ces_standard/issues/I4MBQF)|【增强特性】【事件通知子系统】线程间EventHandler支持HiTrace能力|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|22|[I4MBQG](https://gitee.com/openharmony/hiviewdfx_hisysevent/issues/I4MBQG?from=project-issue)|【资料】hisysevent部件资料需求|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|23|[I4MBQH](https://gitee.com/openharmony/hiviewdfx_hisysevent/issues/I4MBQH?from=project-issue)|【新增特性】支持鸿蒙HiSysEvent部件提供查询接口|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|24|[I4MBQI](https://gitee.com/openharmony/hiviewdfx_hisysevent/issues/I4MBQI?from=project-issue)|【新增特性】提供工具查询或者订阅系统事件|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|25|[I4MBQJ](https://gitee.com/openharmony/hiviewdfx_hisysevent/issues/I4MBQJ?from=project-issue)|【新增特性】支持鸿蒙HiSysEvent部件提供订阅接口|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|26|[I4MBQK](https://gitee.com/openharmony/hiviewdfx_hiappevent/issues/I4MBQK?from=project-issue)|【资料】hiappevent部件资料需求|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|27|[I4MBQL](https://gitee.com/openharmony/hiviewdfx_hiappevent/issues/I4MBQL?from=project-issue)|【新增特性】支持鸿蒙hiappevent部件的C接口|标准系统|SIG_BasicSoftwareService|[@yaomanhai](https://gitee.com/yaomanhai)|
|28|[I4MBQM](https://gitee.com/openharmony/build/issues/I4MBQM?from=project-issue)|【新增规格】L0-L2支持统一的部件配置|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|29|[I4MBQN](https://gitee.com/openharmony/build/issues/I4MBQN?from=project-issue)|【新增规格】L0-L2支持使用统一的编译命令进行编译|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|30|[I4MBQO](https://gitee.com/openharmony/build/issues/I4MBQO?from=project-issue)|【新增规格】L0-L2支持使用统一的编译流程|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|31|[I4MBQP](https://gitee.com/openharmony/build/issues/I4MBQP?from=project-issue)|【新增规格】L0-L2支持使用统一的gn模板|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|32|[I4MBQQ](https://gitee.com/openharmony/build/issues/I4MBQQ?from=project-issue)|【新增规格】L0-L2支持统一的产品配置|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|33|[I4MBQR](https://gitee.com/openharmony/build/issues/I4MBQR?from=project-issue)|【资料】制定gn编码规范和最佳实践指导|标准系统|SIG_CompileRuntime|[@wangxing-hw](https://gitee.com/wangxing-hw)|
|34|[I4MBQS](https://gitee.com/openharmony/account_os_account/issues/I4MBQS?from=project-issue)|【新增特性】支持应用账号信息查询|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|35|[I4MBQT](https://gitee.com/openharmony/account_os_account/issues/I4MBQT?from=project-issue)|【新增特性】支持应用账号功能设置与内容修改|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|36|[I4MBQU](https://gitee.com/openharmony/account_os_account/issues/I4MBQU?from=project-issue)|【新增特性】支持应用账号订阅及取消订阅|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|37|[I4MBQV](https://gitee.com/openharmony/account_os_account/issues/I4MBQV?from=project-issue)|【DFX】应用账号基础信息约束|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|38|[I4MBQW](https://gitee.com/openharmony/account_os_account/issues/I4MBQW?from=project-issue)|【新增特性】支持应用账号的新增和删除|标准系统|SIG_BasicSoftwareService|[@verystone](https://gitee.com/verystone)|
|39|[I4MBQX](https://gitee.com/openharmony/global_cust_lite/issues/I4MBQX?from=project-issue)|【增强特性】定制框架基础能力|标准系统|SIG_ApplicationFramework|[@zhengbin5](https://gitee.com/zhengbin5)|
|40|[I4MBQY](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBQY?from=project-issue)|【新增特性】资源编译工具支持增量编译|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|41|[I4MBQZ](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBQZ?from=project-issue)|【增强特性】时间段格式化|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|42|[I4MBR0](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR0?from=project-issue)|【增强特性】区域表示和属性|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|43|[I4MBR1](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR1?from=project-issue)|【增强特性】单复数支持|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|44|[I4MBR2](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR2?from=project-issue)|【增强特性】字符串排序|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|45|[I4MBR3](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR3?from=project-issue)|【增强特性】电话号码处理|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|46|[I4MBR4](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR4?from=project-issue)|【新增特性】字母表检索|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|47|[I4MBR5](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR5?from=project-issue)|【新增特性】度量衡体系和格式化|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|48|[I4MBR7](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR7?from=project-issue)|【新增特性】日历&本地历法|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|49|[I4MBR8](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR8?from=project-issue)|【增强特性】unicode字符属性|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|50|[I4MBR9](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBR9?from=project-issue)|【增强特性】断词断行|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|51|[I4MBRA](https://gitee.com/openharmony/global_resmgr_standard/issues/I4MBRA?from=project-issue)|【新增特性】系统资源管理|标准系统|SIG_ApplicationFramework|[@jameshw](https://gitee.com/jameshw)|
|52|[I4MBRB](https://gitee.com/openharmony/global_i18n_standard/issues/I4MBRB?from=project-issue)|【新增特性】rawfile资源管理|标准系统|SIG_ApplicationFramework|[@mengjingzhimo](https://gitee.com/mengjingzhimo)|
|53|[I4MBRC](https://gitee.com/openharmony/developtools_profiler/issues/I4MBRC?from=project-issue)|【hiperf部件】采样数据展示|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
|54|[I4MBRD](https://gitee.com/openharmony/developtools_profiler/issues/I4MBRD?from=project-issue)|【hiperf部件】性能数据采样记录|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
|55|[I4MBRE](https://gitee.com/openharmony/developtools_profiler/issues/I4MBRE?from=project-issue)|【hiperf部件】性能数据计数统计|标准系统|SIG_R&DToolChain|[@wangzaishang](https://gitee.com/wangzaishang)|
|56|[I4MBRF](https://gitee.com/openharmony/communication_wifi/issues/I4MBRF?from=project-issue)|【新增特性】支持STA基础特性的JS API接口|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|57|[I4MBRG](https://gitee.com/openharmony/communication_wifi/issues/I4MBRG?from=project-issue)|【新增特性】支持STA基础特性JS API资料文档|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|58|[I4MBRH](https://gitee.com/openharmony/communication_wifi/issues/I4MBRH?from=project-issue)|【新增特性】支持STA基础特性|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|59|[I4MBRI](https://gitee.com/openharmony/communication_wifi/issues/I4MBRI?from=project-issue)|【新增特性】支持SoftAP基础特性|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|60|[I4MBRJ](https://gitee.com/openharmony/communication_wifi/issues/I4MBRJ?from=project-issue)|【新增特性】提供WiFi模块的维测能力|标准系统|SIG_SoftBus|[@cheng_guohong](https://gitee.com/cheng_guohong)|
|61|[I4MBRK](https://gitee.com/openharmony/usb_manager/issues/I4MBRK?from=project-issue)|【新增特性】USB服务JS接口实现|标准系统|SIG_DistributedHardwareManagement|[@hhh2](https://gitee.com/hhh2)|
|62|[I4MBRP](https://gitee.com/openharmony/sensors_sensor/issues/I4MBRP?from=project-issue)|【泛Sensor】地磁场偏角和倾角|标准系统|SIG_DistributedHardwareManagement|[@hhh2](https://gitee.com/hhh2)|
|63|[I4MBRQ](https://gitee.com/openharmony/sensors_sensor/issues/I4MBRQ?from=project-issue)|【泛Sensor】地磁场偏角和倾角|标准系统|SIG_DistributedHardwareManagement|[@hhh2](https://gitee.com/hhh2)|
|64|[I4MBRR](https://gitee.com/openharmony/distributeddatamgr_datamgr/issues/I4MBRR?from=project-issue)|【资料】distributed_kv_store分布式数据库支持按谓词查询条件进行数据库记录的跨设备同步和订阅|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
|65|[I4MBRS](https://gitee.com/openharmony/distributeddatamgr_datamgr/issues/I4MBRS?from=project-issue)|【distributed_kv_store】分布式数据库支持按谓词查询条件进行数据库记录的跨设备同步和订阅|标准系统|SIG_DataManagement|[@widecode](https://gitee.com/widecode)|
|66|[I4MBRT](https://gitee.com/openharmony/distributeddatamgr_appdatamgr/issues/I4MBRT?from=project-issue)|【资料】RDB提供数据库级安全加密|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
|67|[I4MBRU](https://gitee.com/openharmony/distributeddatamgr_appdatamgr/issues/I4MBRU?from=project-issue)|【RDB】支持数据库加密|标准系统|SIG_DataManagement|[@mangtsang](https://gitee.com/mangtsang)|
|68|[I4MBRV](https://gitee.com/openharmony/distributedschedule_samgr/issues/I4MBRV?from=project-issue)|【samgr】系统服务状态监控|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|69|[I4MBRW](https://gitee.com/openharmony/distributedschedule_samgr/issues/I4MBRW?from=project-issue)|【samgr】服务进程内的SA名单管控|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|70|[I4MBRX](https://gitee.com/openharmony/distributedschedule_samgr/issues/I4MBRX?from=project-issue)|【samgr】加载指定系统服务|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|71|[I4MBRY](https://gitee.com/openharmony/distributedschedule_samgr/issues/I4MBRY?from=project-issue)|【samgr】系统服务进程管理|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|72|[I4MBRZ](https://gitee.com/openharmony/distributedschedule_samgr/issues/I4MBRZ?from=project-issue)|【samgr】全量服务列表初始化|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|73|[I4MBS0](https://gitee.com/openharmony/communication_dsoftbus/issues/I4MBS0?from=project-issue)|【新增特性】【组网】软总线支持网络切换组网|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
|74|[I4MBS1](https://gitee.com/openharmony/communication_dsoftbus/issues/I4MBS1?from=project-issue)|【新增特性】【传输】软总线提供传输ExtAPI接口|标准系统|SIG_SoftBus|[@bigpumpkin](https://gitee.com/bigpumpkin)|
|75|[I4MBS2](https://gitee.com/openharmony/distributeddatamgr_file/issues/I4MBS2?from=project-issue)|【新增特性】支持statfs API能力需求|标准系统|SIG_DataManagement|[@zhangzhiwi](https://gitee.com/zhangzhiwi)|
|76|[I4MBS3](https://gitee.com/openharmony/notification_ans_standard/issues/I4MBS3?from=project-issue)|【新增特性】支持长时任务通知|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|77|[I4MBS4](https://gitee.com/openharmony/notification_ans_standard/issues/I4MBS4?from=project-issue)|【新增特性】通知系统API支持权限管理|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|78|[I4MBS5](https://gitee.com/openharmony/notification_ans_standard/issues/I4MBS5?from=project-issue)|【新增特性】支持设置通知振动|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|79|[I4MBS6](https://gitee.com/openharmony/notification_ans_standard/issues/I4MBS6?from=project-issue)|【新增特性】支持通知声音设置和查询|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|80|[I4MBS7](https://gitee.com/openharmony/notification_ans_standard/issues/I4MBS7?from=project-issue)|【新增特性】通知支持免打扰|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|81|[I4MBS8](https://gitee.com/openharmony/notification_ans_standard/issues/I4MBS8?from=project-issue)|【新增特性】支持会话类通知|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|82|[I4MBS9](https://gitee.com/openharmony/notification_ces_standard/issues/I4MBS9?from=project-issue)|【新增特性】EventHandler支持hitrace|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|83|[I4MBSA](https://gitee.com/openharmony/notification_ces_standard/issues/I4MBSA?from=project-issue)|【新增特性】支持系统公共事件管理特性|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|84|[I4MBSB](https://gitee.com/openharmony/notification_ces_standard/issues/I4MBSB?from=project-issue)|【新增特性】支持eventEmitter|标准系统|SIG_BasicSoftwareService|[@autumn330](https://gitee.com/autumn330)|
|85|[I4MBSC](https://gitee.com/openharmony/appexecfwk_standard/issues/I4MBSC?from=project-issue)|【增强特性】支持Module和Ability的srcPath字段|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|86|[I4MBSD](https://gitee.com/openharmony/appexecfwk_standard/issues/I4MBSD?from=project-issue)|【新增特性】支持多hap包安装|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|87|[I4MBSE](https://gitee.com/openharmony/appexecfwk_standard/issues/I4MBSE?from=project-issue)|【新增特性】提供桌面包管理客户端|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|88|[I4MBSF](https://gitee.com/openharmony/appexecfwk_standard/issues/I4MBSF?from=project-issue)|【新增特性】提供清除缓存数据js api|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|89|[I4MBSG](https://gitee.com/openharmony/appexecfwk_standard/issues/I4MBSG?from=project-issue)|【增强特性】安装包信息查询|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|90|[I4MBSH](https://gitee.com/openharmony/appexecfwk_standard/issues/I4MBSH?from=project-issue)|【新增特性】多hap安装时的签名校验|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|91|[I4MBSI](https://gitee.com/openharmony/aafwk_standard/issues/I4MBSI?from=project-issue)|【新增特性】ZIDL工具自动生成Extension C++服务端及客户端接口文件|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|92|[I4MBT4](https://gitee.com/openharmony/aafwk_standard/issues/I4MBT4?from=project-issue)|【增强特性】支持常驻进程开机启动|标准系统|SIG_ApplicationFramework|[@gwang2008](https://gitee.com/gwang2008)|
|93|[I4MBTN](https://gitee.com/openharmony/kernel_linux_5.10/issues/I4MBTN?from=project-issue)|【新增特性】支持CMA复用特性|标准系统|SIG_Kernel|[@liuyoufang](https://gitee.com/liuyoufang)|
|94|[I4MBTO](https://gitee.com/openharmony/third_party_musl/issues/I4MBTO?from=project-issue)|【新增特性】支持内存占用分类查询|标准系统|SIG_CompileRuntime|[@huanghuijin](https://gitee.com/huanghuijin)|
|95|[I4MBTP](https://gitee.com/openharmony/drivers_peripheral/issues/I4MBTP?from=project-issue)|【增强特性】传感器驱动模型能力增强|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|96|[I4MBTQ](https://gitee.com/openharmony/drivers_peripheral/issues/I4MBTQ?from=project-issue)|【增强特性】传感器器件驱动能力增强|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|97|[I4MBTR](https://gitee.com/openharmony/drivers_peripheral/issues/I4MBTR?from=project-issue)|【新增特性】Display-Layer HDI接口针对L2的参考实现；  Display-Gralloc HDI接口针对L2的参考实现；  Display-Device  HDI接口针对L2的参考实现；|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|98|[I4MBTS](https://gitee.com/openharmony/drivers_framework/issues/I4MBTS?from=project-issue)|【增强特性】 HDF-Input设备能力丰富|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|99|[I4MBTT](https://gitee.com/openharmony/drivers_framework/issues/I4MBTT?from=project-issue)|【新增特性】支持Linux/Liteos-a内核系统级休眠唤醒|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|100|[I4MBTU](https://gitee.com/openharmony/drivers_framework/issues/I4MBTU?from=project-issue)|【新增特性】支持同步/异步电源管理调用|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|101|[I4MBTV](https://gitee.com/openharmony/drivers_framework/issues/I4MBTV?from=project-issue)|【新增特性】提供hcs宏式解析接口|标准系统|SIG_DriverFramework|[@zianed](https://gitee.com/zianed)|
|102|[I4MBU1](https://gitee.com/openharmony/applications_settings/issues/I4MBU1?from=project-issue)|【设置公共数据存储】Settings数据管理API|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|103|[I4MBU3](https://gitee.com/openharmony/applications_settings/issues/I4MBU3?from=project-issue)|【设置】系统-时间设置|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|104|[I4MBU5](https://gitee.com/openharmony/applications_settings/issues/I4MBU5?from=project-issue)|【设置】声音管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|105|[I4MBU6](https://gitee.com/openharmony/applications_settings/issues/I4MBU6?from=project-issue)|【设置】基础能力-数据管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|106|[I4MBU7](https://gitee.com/openharmony/applications_settings/issues/I4MBU7?from=project-issue)|【设置】基础能力-默认值管理|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|107|[I4MBU8](https://gitee.com/openharmony/applications_settings/issues/I4MBU8?from=project-issue)|【设置】基础能力-多设备形态差异化构建|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|108|[I4MBU9](https://gitee.com/openharmony/applications_systemui/issues/I4MBU9?from=project-issue)|【SystemUI】【通知】通知组件化|标准系统|SIG_SystemApplication|[@lv-zhongwei](https://gitee.com/lv-zhongwei)|
|109|[I4MBUB](https://gitee.com/openharmony/ark_ts2abc/issues/I4MBUB?from=project-issue)|【新增特性】提供windows/MacOS/Linux的前端编译工具链|标准系统|SIG_CompileRuntime|[@godmiaozi](https://gitee.com/godmiaozi)|
|110|[I4MBUC](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUC?from=project-issue)|【新增特性】Openharmony jsapi替换为ark版本|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|111|[I4MBUD](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUD?from=project-issue)|【新增规格】内存管理分配回收功能/Concurrent mark算法以及Concurrent Sweep实现|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|112|[I4MBUE](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUE?from=project-issue)|【新增特性】OpenharmonyOS上默认内置应用替换为ark版本|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|113|[I4MBUF](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUF?from=project-issue)|【增强特性】Inline Cache功能|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|114|[I4MBUG](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUG?from=project-issue)|【增强特性】支持解释器call指令优化|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|115|[I4MBUH](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUH?from=project-issue)|【新增规格】CPU Profiler运行时实现|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|116|[I4MBUI](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUI?from=project-issue)|【新增规格】内存管理分配回收功能/ 支持Old Space的Partial GC|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|117|[I4MBUJ](https://gitee.com/openharmony/ark_ts2abc/issues/I4MBUJ?from=project-issue)|【新增特性】OpenHarmony应用工程编译构建能力  【描述】  1、在正常构建场景下，能够将开发者程序代码编译成方舟字节码  2、在编译出现错误时，输出准确编译错误提示信息|标准系统|SIG_CompileRuntime|[@godmiaozi](https://gitee.com/godmiaozi)|
|118|[I4MBUK](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUK?from=project-issue)|【新增规格】JS运行时支持预览器|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|119|[I4MBUL](https://gitee.com/openharmony/ark_js_runtime/issues/I4MBUL?from=project-issue)|【新增规格】方舟支持调试并且支持attach模式|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|120|[I4MBUM](https://gitee.com/openharmony/js_util_module/issues/I4MBUM?from=project-issue)|【新增规格】提供libc，c++，clang基础测试框架|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|121|[I4MBUN](https://gitee.com/openharmony/js_sys_module/issues/I4MBUN?from=project-issue)|【新增规格】支持utils特性  /提供process接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|122|[I4MBUO](https://gitee.com/openharmony/js_util_module/issues/I4MBUO?from=project-issue)|【新增规格】支持utils特性  /提供提供Scope接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|123|[I4MBUP](https://gitee.com/openharmony/js_util_module/issues/I4MBUP?from=project-issue)|【新增规格】支持utils特性  /提供提供Base64接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|124|[I4MBUQ](https://gitee.com/openharmony/js_util_module/issues/I4MBUQ?from=project-issue)|【新增规格】支持utils特性  /提供提供RationalNumber接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|125|[I4MBUR](https://gitee.com/openharmony/js_util_module/issues/I4MBUR?from=project-issue)|【新增规格】支持语言增强特性/提供JS Typeof 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|126|[I4MBUS](https://gitee.com/openharmony/js_api_module/issues/I4MBUS?from=project-issue)|【新增规格】支持URI特性 /提供 URI解析接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|127|[I4MBUT](https://gitee.com/openharmony/js_util_module/issues/I4MBUT?from=project-issue)|【新增规格】支持utils特性提供LRUBuffer接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|128|[I4MBUU](https://gitee.com/openharmony/js_api_module/issues/I4MBUU?from=project-issue)|【新增规格】支持XML特性/提供XmlPullParser 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|129|[I4MBUV](https://gitee.com/openharmony/js_api_module/issues/I4MBUV?from=project-issue)|【新增规格】支持XML特性/提供xmlSerializer 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|130|[I4MBUW](https://gitee.com/openharmony/js_api_module/issues/I4MBUW?from=project-issue)|【新增规格】支持XML特性/提供xml2JSObject 接口规格|标准系统|SIG_CompileRuntime|[@wuzhefengh](https://gitee.com/wuzhefengh)|
|131|[I4MBUX](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBUX?from=project-issue)|【新增规格】资源管理特性对接全球化规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|132|[I4MBUY](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBUY?from=project-issue)|【新增规格】事件中增加Target获取尺寸|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|133|[I4MBUZ](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBUZ?from=project-issue)|【新增规格】Swiper组件支持设置缓存cache|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|134|[I4MBV1](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBV1?from=project-issue)|【新增规格】Image组件支持同步、异步渲染设置|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|135|[I4MBV3](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBV3?from=project-issue)|【新增规格】样式设置特性增加组件多态样式设置规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|136|[I4MBV5](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBV5?from=project-issue)|【新增规格】字母索引条组件增加提示菜单内容扩展规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|137|[I4MBV6](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBV6?from=project-issue)|【新增规格】组件自定义特性增加自定义容器组件规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|138|[I4MBV7](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBV7?from=project-issue)|【新增规格】滚动条样式自定义能力|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|139|[I4MBV8](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBV8?from=project-issue)|【新增规格】Swiper组件新增切换禁用规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|140|[I4MBV9](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBV9?from=project-issue)|【新增规格】Tabs组件新增TabBar内容自定义规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|141|[I4MBVA](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVA?from=project-issue)|【新增规格】Navigation组件新增标题栏设置规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|142|[I4MBVB](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVB?from=project-issue)|【新增规格】工具栏组件增加工具栏显隐控制规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|143|[I4MBVC](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVC?from=project-issue)|【新增规格】工具栏组件增加内容自定义能力规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|144|[I4MBVD](https://gitee.com/openharmony/interface_sdk-js/issues/I4MBVD?from=project-issue)|【新增特性】新增SysCap声明编译特性|标准系统|SIG_ApplicationFramework|[@karl-z](https://gitee.com/karl-z)|
|145|[I4MBVE](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVE?from=project-issue)|【新增特性】新增JS SDK编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|146|[I4MBVF](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVF?from=project-issue)|【新增特性】新增Config.json编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|147|[I4MBVG](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVG?from=project-issue)|【新增规格】新增断点调试特性支持单实例调试|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|148|[I4MBVH](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVH?from=project-issue)|【新增规格】新增attach调试特性支持单实例调试|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|149|[I4MBVI](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVI?from=project-issue)|【新增规格】新增声明式范式编译特性支持编译和校验规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|150|[I4MBVJ](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVJ?from=project-issue)|【新增特性】新增JS模块共享编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|151|[I4MBVK](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVK?from=project-issue)|【新增特性】新增HAR引用和编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|152|[I4MBVL](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVL?from=project-issue)|【新增特性】新增NPM引用和编译特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|153|[I4MBVM](https://gitee.com/openharmony/docs/issues/I4MBVM?from=project-issue)|【资料】ace_engine_standard部件IT2版本资料录入需求|标准系统|SIG_Docs|[@neeen](https://gitee.com/neeen)|
|154|[I4MBVN](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVN?from=project-issue)|【新增特性】纵向显示滑动条组件特性|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|155|[I4MBVO](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVO?from=project-issue)|【新增特性】Popup组件增加内容自定义规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|156|[I4MBVP](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVP?from=project-issue)|【新增特性】Canvas绘制能力支持|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|157|[I4MBVQ](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVQ?from=project-issue)|【新增规格】Canvas能力增强|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|158|[I4MBVR](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVR?from=project-issue)|【新增特性】触摸响应热区设置|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|159|[I4MBVS](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVS?from=project-issue)|【新增特性】Lottie动画支持|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|160|[I4MBVT](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVT?from=project-issue)|【新增特性】组件尺寸获取特性|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|161|[I4MBVU](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVU?from=project-issue)|【新增特性】Menu组件增加内容自定义规格|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|162|[I4MBVV](https://gitee.com/openharmony/ace_ace_engine/issues/I4MBVV?from=project-issue)|【新增特性】Swipe手势特性|标准系统|SIG_ApplicationFramework|[@davidwulanxi](https://gitee.com/davidwulanxi)|
|163|[I4MBVW](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVW?from=project-issue)|【新增特性】UI预览支持Inspector能力|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|164|[I4MBVX](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVX?from=project-issue)|【新增特性】新增非路由文件预览特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|165|[I4MBVY](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVY?from=project-issue)|【新增特性】新增NAPI预览特性|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|166|[I4MBVZ](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBVZ?from=project-issue)|【新增规格】新增声明式范式预览特性支持基础预览规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|167|[I4MBW2](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBW2?from=project-issue)|【新增规格】新增声明式范式热加载特性支持已有节点修改规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|168|[I4MBW3](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBW3?from=project-issue)|【新增规格】新增声明式范式热加载特性支持新增节点规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|169|[I4MBW4](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBW4?from=project-issue)|【新增规格】新增声明式范式热加载特性支持删除节点规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|170|[I4MBW5](https://gitee.com/openharmony/developtools_ace-ets2bundle/issues/I4MBW5?from=project-issue)|【新增规格】新增组件预览特性支持页面组件预览规格|标准系统|SIG_ApplicationFramework|[@lihong67](https://gitee.com/lihong67)|
|171|[I4NY1T](https://gitee.com/openharmony/device_profile_core/issues/I4NY1T?from=project-issue)|【device_profile】订阅profile信息变化|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|172|[I4NY1U](https://gitee.com/openharmony/device_profile_core/issues/I4NY1U?from=project-issue)|【device_profile】订阅同步通知|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|173|[I4NY1V](https://gitee.com/openharmony/device_profile_core/issues/I4NY1V?from=project-issue)|【device_profile】CS采集OS特征信息|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|174|[I4NY1W](https://gitee.com/openharmony/device_profile_core/issues/I4NY1W?from=project-issue)|【device_profile】向业务端提供同步profile能力|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|175|[I4NY1X](https://gitee.com/openharmony/device_profile_core/issues/I4NY1X?from=project-issue)|【device_profile】提供查询远程设备profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|176|[I4NY1Z](https://gitee.com/openharmony/device_profile_core/issues/I4NY1Z?from=project-issue)|【device_profile】profile上线同步（wifi组网下）|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|177|[I4NY21](https://gitee.com/openharmony/device_profile_core/issues/I4NY21?from=project-issue)|【device_profile】提供删除本地profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|178|[I4NY22](https://gitee.com/openharmony/device_profile_core/issues/I4NY22?from=project-issue)|【device_profile】提供查询本地profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|
|179|[I4NY23](https://gitee.com/openharmony/device_profile_core/issues/I4NY23?from=project-issue)|【device_profile】提供写入profile记录功能|标准系统|SIG_BasicSoftwareService|[@lijiarun](https://gitee.com/lijiarun)|



>  


###### 以上计划由OpenHarmony社区版本发布SIG组织发布