# YeY-zi GitHub 主页配置说明

这份说明配合英文 `README.md` 和中文 `README.zh-CN.md` 使用。两份文案依据当前公开项目写作，定位是数据分析与 AI 应用兴趣方向，没有把学习项目包装成任职经历。作品集地址 `https://yey-zi.github.io/` 是计划使用的发布目的地；完成部署并实际访问后，再删除文案中的准备发布说明。

## 个人资料

在 GitHub 头像菜单进入 Your profile，然后选择 Edit profile。建议字段如下：

| 字段 | 建议内容 |
| --- | --- |
| Name | Yuhan Ye · 叶予涵 |
| Bio | MSc Electronic Commerce @ CityUHK · Interested in Data Analytics & AI Applications · Reproducible analysis and research tools |
| Location | Hong Kong |
| Website | https://yey-zi.github.io/，确认实际部署后填写 |

头像使用自己愿意公开且有权使用的照片或个人图形。电话号码、个人邮箱、住址和完整简历无需放在公开资料中。若公开联系信息，先单独确认具体内容。

## 让 README 出现在 GitHub 主页

GitHub 的个人 README 来自与用户名同名的公开仓库，且根目录需要非空 `README.md`。对本账号而言，仓库应为 `YeY-zi/YeY-zi`。具体条件见 [GitHub 官方说明](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)。

1. 在 `YeY-zi` 账号下创建或打开公开仓库 `YeY-zi`。
2. 把本目录英文 `README.md` 和中文 `README.zh-CN.md` 放在仓库根目录，保留文件名，使语言导航可用。
3. 提交后打开 `https://github.com/YeY-zi`，检查文本、项目链接和中英切换。
4. 当网站确认上线时，同时更新两份 README 的作品集发布状态。

个人 README 仓库与个人网站仓库用途不同。前者展示在 GitHub 账号首页；计划中的个人网站使用 `YeY-zi/YeY-zi.github.io`。GitHub Pages 用户站点的创建与发布设置见 [GitHub Pages 官方快速开始](https://docs.github.com/en/pages/quickstart)。

## 推荐置顶顺序

在主页 Popular repositories 或 Pinned 旁选择 Customize your pins，选中仓库并拖动排序。GitHub 最多支持六项；不必填满。操作见 [GitHub 官方置顶说明](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile)。

| 顺序 | 仓库 | 访客应能看见的证据 |
| --- | --- | --- |
| 1 | `research-evidence-workbench` | 问题定义、PRD、原型、离线演示与实际范围 |
| 2 | `Predict_repurchase` | 数据清洗、时间划分、模型比较、失败的特征实验及归属说明 |
| 3 | `research-agent-lab` | 真实 MCP 调用、固定工作流对照、失败轨迹与实验边界 |
| 4 | `ecg-tsfm-exploration` | 数据划分、基线、真实日志、逐记录误差与模型改编说明 |

网站发布后可以再置顶 `YeY-zi.github.io`。个人 README 仓库通常无需占用置顶位置。

## 项目简介建议

各仓库 About 区应简短说明问题与当前实现。以下文案仅供更新现有简介时使用：

| 仓库 | 建议 Description |
| --- | --- |
| `research-evidence-workbench` | Research evidence prototype: source-linked cards, manual review, and a local rule-based demo. |
| `Predict_repurchase` | Attributed Olist analysis extension: cleaning audit, temporal repurchase prediction, and segment-feature comparison. |
| `research-agent-lab` | AI-assisted research workflow prototype with real MCP tool calls, controlled experiments, and failure traces. |
| `ecg-tsfm-exploration` | AI-assisted ECG forecasting study with record-based splits, baselines, CNN and PatchTST-style experiments. |

只为实际使用的内容添加 Topics。例如 Olist 可用 `data-analysis`、`customer-analytics`、`classification`、`reproducible-research`；不要为计划中的功能添加已实现标签。

## 内容维护

每个精选项目应让访客找到问题、当前功能、自己的贡献、来源或改编关系、可运行入口、实际结果和局限。Olist 继续保留原项目与数据来源；AI 辅助开发说明继续保留。Workbench 的规则匹配演示不描述为自动检索或 AI 生成；Research Agent Lab 不描述为自主科研系统；ECG 不描述为临床诊断或官方论文完整复现。

Canvas、求职雷达等工具如果只是安装使用，可以写为使用笔记或开源实践。只有完成自己的具体修改、测试或上游贡献后，才把对应工作列为个人开发项目，并保留原作者与许可。不要将使用他人工具的截图当作自己研发的成果。

教育信息在这份文案中为：香港城市大学电子商务硕士，2026–2027 预计；福州大学物联网工程学士，2022–2026。后续发生变化时，英文和中文版本一起更新。
