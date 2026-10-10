# 学生论文交付指导包

版本：**v0.5.0** · [GitHub 仓库](https://github.com/wangshi-LN/student-paper-guide)

## 1. 这个仓库有什么用

帮助你使用自己的 AI 助手，按统一要求准备与导师沟通的材料，覆盖从研究方案讨论到审稿回复的五个阶段。

> **注意：**
>
> - 指导包与研究工程分开存放。
> - GitHub 用于获取和更新通用指南、模板。
> - 个人论文材料通过导师约定的渠道提交。

## 2. 开始使用并确认任务

在研究工程目录之外打开终端，替换论文简称和日期后执行：

```bash
git clone https://github.com/wangshi-LN/student-paper-guide.git "指导包-论文简称-YYYY-MM-DD"
```

暂不使用 Git 时，可在仓库页面选择 **Code → Download ZIP**，解压后使用。

打开能读取本地文件的 AI 助手，填写并发送下面的提示词：

> 指导包路径是〔完整路径〕，研究项目路径是〔完整路径〕。请先读取指导包中的 README.md、AGENTS.md 和启动指南，只读盘点项目，简短说明当前状态、材料缺口和可选动作。等我确定本轮沟通目的和任务范围后，再开始整理交付材料。

听取 AI 简报后，由你确定：

- **这次希望导师帮助判断什么？**
- **本轮准备哪些材料？**

任务明确后，再进入下一节。详细操作见[学生使用与 AI 启动](https://github.com/wangshi-LN/student-paper-guide/blob/main/指南-论文流程-2026-10-09/00-学生使用与AI启动.md)。

## 3. 按任务准备材料

让 AI 根据本轮目的，复制所需模板并整理材料。专题请教只准备相关内容，选填栏目可以省略，尚未完成的内容如实说明。

| 本次任务 | 主要交付内容 | 入口 |
|---|---|---|
| 创新点与实验设计讨论 | 一份讨论文档 | [指南](https://github.com/wangshi-LN/student-paper-guide/blob/main/指南-论文流程-2026-10-09/01-选题与研究方案.md) · [模板](https://github.com/wangshi-LN/student-paper-guide/blob/main/模板-学生材料-2026-10-09/01-研究方案模板.md) |
| 实验进展与结果汇报 | 一份 Word，图片嵌入正文 | [指南](https://github.com/wangshi-LN/student-paper-guide/blob/main/指南-论文流程-2026-10-09/02-阶段研究成果.md) · [模板](https://github.com/wangshi-LN/student-paper-guide/blob/main/模板-学生材料-2026-10-09/02-阶段成果模板.md) |
| 初稿审阅 | 审阅说明及论文资源 | [指南](https://github.com/wangshi-LN/student-paper-guide/blob/main/指南-论文流程-2026-10-09/03-完整初稿.md) · [模板](https://github.com/wangshi-LN/student-paper-guide/blob/main/模板-学生材料-2026-10-09/03-初稿提交说明模板.md) |
| 投稿前确认 | 投稿确认说明及论文资源 | [指南](https://github.com/wangshi-LN/student-paper-guide/blob/main/指南-论文流程-2026-10-09/05-投稿前检查.md) · [模板](https://github.com/wangshi-LN/student-paper-guide/blob/main/模板-学生材料-2026-10-09/05-投稿前检查模板.md) |
| 审稿与审稿回复 | 审稿处理说明、完整意见原文及论文资源；修改后增加逐条回复 | [指南](https://github.com/wangshi-LN/student-paper-guide/blob/main/指南-论文流程-2026-10-09/07-审稿与审稿回复.md) · [模板](https://github.com/wangshi-LN/student-paper-guide/blob/main/模板-学生材料-2026-10-09/07-审稿处理说明模板.md) |

**论文资源**包括 Markdown 正文、独立图片和本轮相关代码；没有相关代码时注明不适用。第 2 阶段不交 PDF，第 3—5 阶段不交 Word 或 PDF。

## 4. 审核、打包与提交

1. **AI 自查。** 核对材料内容、来源、格式转换结果，以及反馈与稿件版本的对应关系，列出待确认事项。
2. **你审核实际文件。** 查看正文、图表及附件，确认事实、表达和沟通目的，不能只看 AI 摘要。
3. **按确认版本打包。** AI 只打包你确认过的材料；内容发生变化后，重新审核。
4. **你自行发送。** 通过导师约定的渠道提交，并在本地记录交付版本和发送时间。

## 5. 收到导师意见后

保存导师反馈，由你自主决定修改内容，在自己的项目中完成修改，再生成下一轮交付。

**导师意见 → 学生修改项目 → 生成新交付 → 再次提交**

交付文件夹保存沟通材料和历轮快照。每轮记录所依据的反馈及对应项目版本，旧版材料保留，不覆盖。

## 6. 后续更新与维护

更新前先备份个人交付材料，确认通用指南和模板没有本地改动，再在指导包目录运行：

```bash
git pull --ff-only
```

如有本地改动或更新失败，先保留现场，不强制覆盖。

通用模板复制后填写；个人交付按版本和日期留存，并定期备份。指导包版本与个人交付版本分别记录。

详细步骤见[提交与版本更新](https://github.com/wangshi-LN/student-paper-guide/blob/main/指南-论文流程-2026-10-09/06-提交与版本更新.md)，新版变化见[更新记录](https://github.com/wangshi-LN/student-paper-guide/blob/main/CHANGELOG.md)。
