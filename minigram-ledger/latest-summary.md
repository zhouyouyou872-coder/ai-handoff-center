# Latest Summary

- Project: minigram-ledger
- Repo: https://github.com/zhouyouyou872-coder/minigram-ledger.git
- Branch: main
- Commit: a4ea2c5
- Updated At: 2026-05-27T01:07:50.970Z
- Handoff Repo: https://github.com/zhouyouyou872-coder/ai-handoff-center

## Working Tree

```text
?? .ai-handoff.json
?? .ai/
```

## Recent Commits

```text
a4ea2c5 docs: add AI collaboration context files
81aa909 docs: update README
3337c7f Merge branch 'main' of https://github.com/zhouyouyou872-coder/minigram-ledger
e333f4c init project
eb4e767 Initial commit
```

## Session Note

Initial end-to-end validation of ai-handoff workflow

## Context Files

### README.md

# Minigram Ledger

一个基于微信小程序的轻量记账项目，用于记录日常收支、查看账单列表，并按分类进行简单统计分析。

## 功能特性

- 支持新增收入和支出记录
- 支持账单列表展示
- 支持按分类查看记录
- 支持基础数据分析与图表展示
- 支持本地数据存储

## 项目结构

```text
miniprogram-ledger/
├── components/   # 通用组件
├── images/       # 图片资源
├── pages/        # 页面目录
├── utils/        # 工具函数与数据处理
├── app.js
├── app.json
├── app.wxss
└── project.config.json
```

## 本地运行

1. 安装并打开微信开发者工具
2. 选择“导入项目”
3. 项目目录选择当前仓库目录
4. 按照你自己的小程序 AppID 完成配置后即可预览和调试

## 注意事项

- `project.private.config.json` 为本地私有配置文件，已加入 `.gitignore`
- `project.config.json` 中包含小程序项目基础配置，请按实际需要调整

## 后续可扩展方向

- 增加月份筛选与账单汇总
- 增加预算管理功能
- 增加云端同步能力
- 增加更完整的数据可视化分析

### AI_CONTEXT.md

# AI Context

## 项目名称

Minigram Ledger

## 项目简介

这是一个基于微信小程序的轻量记账项目，用于记录日常收支、展示账单列表，并进行基础统计分析。

## 当前功能

- 新增收入和支出记录
- 账单列表展示
- 按分类查看记录
- 基础分析与图表展示
- 本地数据存储

## 主要目录

- `pages/`：小程序页面
- `components/`：复用组件
- `utils/`：工具函数、存储、分析逻辑
- `images/`：静态资源

## 当前开发状态

- 项目已初始化 Git 仓库
- 代码已推送到 GitHub
- 已补充基础 `README.md`
- 已添加 `.gitignore`，忽略 `project.private.config.json`

## GitHub 仓库

`https://github.com/zhouyouyou872-coder/minigram-ledger`

## 开发约束

- 这是微信小程序项目，主要在微信开发者工具中运行和调试
- 本地私有配置文件 `project.private.config.json` 不应提交
- 修改功能时优先保持现有页面结构稳定，避免无关重构

## 建议 AI 接手方式

换设备后，可先让 AI 阅读以下文件：

- `README.md`
- `AI_CONTEXT.md`
- `TASKS.md`
- `HANDOFF.md`

推荐提示词：

```text
先阅读 README.md、AI_CONTEXT.md、TASKS.md、HANDOFF.md，总结当前项目状态后继续开发，不要改动无关部分。
```

## 常用 Git 命令

```powershell
git pull
git add .
git commit -m "your message"
git push
```

## 备注

每次开发结束后，建议更新：

- `AI_CONTEXT.md`：项目阶段和关键约束
- `TASKS.md`：任务进度
- `HANDOFF.md`：本次改动和下一步

### TASKS.md

# Tasks

## In Progress

- 梳理并持续完善项目文档，便于多设备协作和 AI 接力开发

## Todo

- 检查各页面核心流程是否完整可用
- 补充项目截图或演示说明到 `README.md`
- 评估是否需要增加月份筛选
- 评估是否需要增加预算功能
- 评估是否需要增加云端同步能力

## Done

- 初始化本地 Git 仓库
- 关联 GitHub 远程仓库
- 完成首次代码提交和推送
- 新增 `.gitignore`
- 更新 `README.md`
- 新增 AI 协作上下文文件

## 使用规则

- 新任务放到 `Todo`
- 正在做的任务放到 `In Progress`
- 已完成的任务移动到 `Done`
- 如果某个任务卡住，在任务后面直接写明原因

### HANDOFF.md

# Handoff

## 当前状态

- 当前分支：`main`
- 远程仓库：`origin`
- GitHub 已完成首次同步

## 最近完成内容

- 初始化 Git 仓库并推送到 GitHub
- 更新项目 `README.md`
- 建立跨设备 AI 协作所需的上下文文件

## 重要说明

- `project.private.config.json` 是本地私有配置，不提交
- 终端里如果看到中文乱码，通常是 PowerShell 编码显示问题，不一定是文件内容损坏

## 下一步建议

- 先检查小程序在微信开发者工具中的运行情况
- 明确下一个具体功能点，再继续迭代
- 开发结束后同步更新本文件和 `TASKS.md`

## 给下一次 AI 会话的说明

请先阅读：

- `README.md`
- `AI_CONTEXT.md`
- `TASKS.md`
- `HANDOFF.md`

然后：

1. 总结当前项目状态
2. 确认最近未完成的任务
3. 只处理当前目标相关的改动

### .ai\latest-summary.md

# Latest Summary

Run `ai-handoff save` to generate this file.

### .ai\resume-prompt.txt

Please read .ai/latest-summary.md and continue the current project.

## Next AI Handoff

Tell the next AI to read `.ai/latest-summary.md` and `.ai/resume-prompt.txt` before making changes.
