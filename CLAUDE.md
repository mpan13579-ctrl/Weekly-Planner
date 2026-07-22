# CLAUDE.md — 工作规则

## 开工规则（规则⑦）

开工只需读三份文件 + 看 handoff，其余一概不需要：

1. `README.md` — 项目是什么、怎么跑
2. `CLAUDE.md` — 本文件，工作规则
3. `PLAN.md` — 当前目标与本周结构
4. 最后看 `HANDOFF.md` — 上次干到哪、下一步做什么

读完这四样即可动手，不要为了"了解背景"去翻历史 commit 或整个 index.html。

## 收工规则

每次会话结束前：

- 更新 `HANDOFF.md`：新条目写在最上面（刚完成 / 卡点 / 下一步）
- 目标或周结构变了才改 `PLAN.md`，日常小任务不写进去

## 仓库约定

- 日常任务由 Telegram intake 自动提交（commit 信息为 "Update planner tasks from intake"），只改 `index.html`；不要与这些提交冲突，也不要手动模仿它们
- 计划的"实时状态"以部署出来的 `index.html` 为准；`PLAN.md` 只放稳定层（项目目标、周结构）
- 页面文案为英文，文档与交接用中文
