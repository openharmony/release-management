#### 一、维护职责

SIG Release会对LTS分支进行长期的支持和维护，维护内容主要为以下几点：

- 安全漏洞修复：包含OpenHarmony社区独有的漏洞，以及开源和三方软件发布的漏洞。漏洞通过[公告](https://gitee.com/openharmony/security/blob/master/zh/security-disclosure/README.md)发布。
- 缺陷修复：对社区反馈的缺陷issue进行修复，并在标签版本的[releasenotes](https://gitee.com/openharmony/docs/tree/master/zh-cn/release-notes)中对外公告。
- 特性变更：如果标签版本有相对应的修改，会在标签版本的[releasenotes](https://gitee.com/openharmony/docs/tree/master/zh-cn/release-notes)中公告。

#### 二、标签版本计划

1.Openharmony 1.0.1 release分支版本计划

| 版本计划                   | 版本号                | 版本构建日期 | 版本转测试 | 版本测试完成 |
| -------------------------- | --------------------- | ------------ | ---------- | ------------ |
| Openharmony_release_v1.1.0 | Openharmony 1.1.0 LTS | 2021/3/24    | 2021/3/24  | 2021/3/31    |
| Openharmony-v1.1.1-LTS     | Openharmony 1.1.1 LTS | 2021/6/4     | 2021/6/4   | 2021/6/18    |
| Openharmony-v1.1.2-LTS     | Openharmony 1.1.2 LTS | 2021/7/15    | 2021/7/15  | 2021/7/31    |
| Openharmony-v1.1.3-LTS     | Openharmony 1.1.3 LTS | 2021/9/15    | 2021/9/15  | 2021/9/30    |
| Openharmony-v1.1.4-LTS     | Openharmony 1.1.4 LTS | 2022/1/24    | 2022/1/24  | 2022/2/10    |
| Openharmony-v1.1.5-LTS     | Openharmony 1.1.5 LTS | 2022/7/01    | 2022/7/01  | 2022/7/15    |



2.Openharmony 3.0 LTS分支版本计划

| 版本计划               | 版本号                | 版本构建日期 | 版本转测试 | 版本测试完成 |
| ---------------------- | --------------------- | ------------ | ---------- | ------------ |
| Openharmony-v3.0-LTS   | Openharmony 3.0 LTS   | 2021/9/24    | 2021/9/24  | 2021/9/30    |
| Openharmony-v3.0.1-LTS | Openharmony 3.0.1 LTS | 2021/12/29   | 2021/12/29 | 2022/1/10    |
| Openharmony-v3.0.2-LTS | Openharmony 3.0.2 LTS | 2022/2/28    | 2022/2/28  | 2022/3/15    |
| Openharmony-v3.0.3-LTS | Openharmony 3.0.3 LTS | 2022/3/25    | 2022/3/25  | 2022/4/5     |
| Openharmony-v3.0.5-LTS | Openharmony 3.0.5 LTS | 2022/6/17    | 2022/6/17  | 2022/6/30    |
| Openharmony-v3.0.6-LTS | Openharmony 3.0.6 LTS | 2022/8/15    | 2022/8/15  | 2022/8/30    |
| Openharmony-v3.0.7-LTS | Openharmony 3.0.7 LTS | 2022/10/15   | 2022/10/15 | 2022/10/30   |

3.Openharmony 3.1 Release分支版本计划

| 版本计划                   | 版本号                    | 版本构建日期 | 版本转测试 | 版本测试完成 |
| -------------------------- | ------------------------- | ------------ | ---------- | ------------ |
| Openharmony-v3.1-Release   | Openharmony 3.1 Release   | 2022/3/15    | 2022/3/15  | 2022/3/30    |
| Openharmony-v3.1.1-Release | Openharmony 3.1.1 Release | 2022/5/18    | 2022/5/18  | 2022/5/30    |
| Openharmony-v3.1.2-Release | Openharmony 3.1.2 Release | 2022/7/10    | 2022/7/10  | 2022/7/30    |
| Openharmony-v3.1.3-Release | Openharmony 3.1.3 Release | 2022/8/15    | 2022/8/15  | 2022/8/30    |
| Openharmony-v3.1.4-Release | Openharmony 3.1.4 Release | 2022/9/12    | 2022/9/12  | 2022/9/23    |
| Openharmony-v3.1.5-Release | Openharmony 3.1.5 Release | 2022/11/15   | 2022/11/15 | 2022/11/30   |
| Openharmony-v3.1.6-Release | Openharmony 3.1.6 Release | 2023/1/16    | 2023/1/16  | 2023/1/30    |
| Openharmony-v3.1.7-Release | Openharmony 3.1.7 Release | 2023/4/5     | 2023/4/5   | 2023/4/15    |

#### 三、锁库说明

为了保证标签版本稳定和方便集成验证，在标签版本转测试期间对LTS分支进行锁库处理。在锁库期间，任何修改都不被允许合并到LTS分支。例如Openharmony 1.1.3 LTS版本9/15转测试，9/30完成测试，那么OpenHarmony_1.0.1_release分支锁库时间为2021/9/15——2021/9/30。
