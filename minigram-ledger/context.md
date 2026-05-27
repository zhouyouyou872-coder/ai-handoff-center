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