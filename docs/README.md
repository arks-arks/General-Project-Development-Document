# 项目文档导航

> 用途：让开发者和 AI 快速找到本次任务必须阅读的文档。  
> 什么时候更新：新增、废弃文档或文档职责变化时。

## 快速入口

| 你要做什么 | 先读 |
|---|---|
| 了解项目规则 | `../AGENTS.md` |
| 快速接手当前代码库 | `ai/PROJECT_STATE.md` |
| 查看未完成工作 | `ai/TODO.md` |
| 理解长期设计选择 | `ai/DECISIONS.md` |
| 开始一次修改或交接 | `ai/CHANGE_PROTOCOL.md` |
| 创建分支、提交、推送或发布 | `ai/GIT_WORKFLOW.md` |
| 理解整体架构 | `architecture/SYSTEM_ARCHITECTURE.md` |
| 修改某个模块 | 该模块的专项文档；可复制 `architecture/MODULE_TEMPLATE.md` |
| 构建、部署、更新或回滚 | `deployment/BUILD_AND_RELEASE.md` |
| 判断改完应该测什么 | `testing/TEST_MATRIX.md` |
| 现场诊断和恢复 | `operations/RUNBOOK.md` |

## 关键文件索引

| 模块 | 入口文件 | 测试 | 负责人/备注 |
|---|---|---|---|
| {{模块}} | `{{路径}}` | `{{路径/命令}}` | {{说明}} |

## 文档职责边界

- `AGENTS.md`：必须遵守什么。
- `PROJECT_STATE.md`：项目现在是什么状态。
- `DECISIONS.md`：为什么必须这样设计。
- `TODO.md`：还没完成什么。
- `CHANGE_PROTOCOL.md`：如何修改、验证和交接。
- `architecture/`：系统和模块如何工作。
- `BUILD_AND_RELEASE.md`：如何构建、部署、更新和回滚。
- `TEST_MATRIX.md`：修改后最低应该测什么。
- `RUNBOOK.md`：运行中如何检查、诊断和恢复。

不要在多份文档复制同一段长说明；需要时引用唯一职责文档。

## 已废弃文档

| 文档 | 废弃日期 | 替代文档 | 保留原因 |
|---|---|---|---|
| `{{旧文档}}` | {{日期}} | `{{新文档}}` | {{历史追溯/待归档}} |

