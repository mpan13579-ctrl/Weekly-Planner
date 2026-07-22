# Weekly Agentic Planner

个人周计划页面：单文件静态站点，展示本周焦点、项目状态、周计划与收件箱。日常任务通过 Telegram intake 自动更新并提交。

## 组成

| 文件 | 作用 |
| --- | --- |
| `index.html` | 整个应用（样式、脚本、计划内容都在这一个文件里） |
| `server.js` | 本地预览用的极简静态服务器 |
| `.nojekyll` | GitHub Pages 直接按静态文件发布 |

## 本地运行

```bash
node server.js
# 打开 http://127.0.0.1:8765/
```

端口可用环境变量 `PORT` 覆盖。无依赖、无构建步骤。

## 开工须知

按 `CLAUDE.md` 的开工规则：只读 README.md、CLAUDE.md、PLAN.md 三份，再看 `HANDOFF.md`，然后动手。
