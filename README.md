# Cursor Customize

当前正在使用的 Cursor rules 与 skills 快照。

## 目录

- `rules/`：用户级规则，来自 `%USERPROFILE%\.cursor\rules`
- `skills/`：用户级技能，来自 `%USERPROFILE%\.cursor\skills`
- `cursor-skills/`：Cursor 内置技能，来自 `%USERPROFILE%\.cursor\skills-cursor`（不含本机同步清单）
- `project/FrontendWeb/`：FrontendWeb 的项目规则、`AGENTS.md`、`CLAUDE.md`，以及 `.agents/skills`
- `project/controlplatform/`：上级仓库的项目规则、`AGENTS.md`、`CLAUDE.md`
- `plugins/rules/`：本机会注入会话的插件规则（Cloudflare、GitLab、Grafana）

插件市场缓存里的整包技能（如 Vercel、Figma、Cloudflare、Superpowers）未纳入。那些是已安装插件，不是用户级或项目级配置。
