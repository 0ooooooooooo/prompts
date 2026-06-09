# 🦸 Superpowers

> **Upstream 原仓库：**[obra/superpowers](https://github.com/obra/superpowers)
> ⭐ 213k stars · 🍴 19k forks · 📄 MIT License

---

## 📌 简介

**Superpowers** 是一套完整的 **AI 编程智能体开发方法论**，基于一组可组合的 Skills 构建。
它能让你的 AI Coding Agent（Claude Code、Cursor、Gemini CLI 等）在开工之前先做设计、再拆任务、再写代码——而不是莽撞地直接生成代码。

> 核心原则：
> - 🧪 Test-Driven Development（先写测试）
> - 📐 Systematic over Ad-hoc（流程优于猜测）
> - ✂️ YAGNI + DRY（减少复杂度）
> - ✅ Evidence over Claims（验证再宣布完成）

---

## 🔗 快速跳转

| 资源 | 链接 |
|------|------|
| 原仓库 | [github.com/obra/superpowers](https://github.com/obra/superpowers) |
| 官方文档 | [README.md](https://github.com/obra/superpowers/blob/main/README.md) |
| Skills 库 | [/skills](https://github.com/obra/superpowers/tree/main/skills) |
| Release Notes | [RELEASE-NOTES.md](https://github.com/obra/superpowers/blob/main/RELEASE-NOTES.md) |
| Discord 社区 | [Join Us](https://discord.gg/35wsABTejz) |
| 作者博客 | [blog.fsck.com](https://blog.fsck.com/2025/10/09/superpowers/) |

---

## ⚙️ 支持的 Agent 平台

| 平台 | 安装方式 |
|------|----------|
| **Claude Code** | `/plugin install superpowers@claude-plugins-official` |
| **Cursor** | `/add-plugin superpowers` |
| **Gemini CLI** | `gemini extensions install https://github.com/obra/superpowers` |
| **Codex CLI** | `/plugins` → 搜索 `superpowers` |
| **OpenCode** | 参见 [README.opencode.md](https://github.com/obra/superpowers/blob/main/docs/README.opencode.md) |
| **GitHub Copilot CLI** | `copilot plugin install superpowers@superpowers-marketplace` |

---

## 🔄 核心工作流（7 阶段）

```text
1. brainstorming              → 需求澄清 & 设计文档
2. using-git-worktrees        → 隔离分支 & 干净基线
3. writing-plans              → 任务拆解（每个 2-5 分钟）
4. subagent-driven-development → 子 Agent 并发执行
5. test-driven-development    → RED → GREEN → REFACTOR
6. requesting-code-review     → 按严重性分级 Review
7. finishing-a-development-branch → 合并/PR/清理
```

---

## 📚 Skills 分类速览

### 🧪 Testing
| Skill | 描述 |
|-------|------|
| `test-driven-development` | RED-GREEN-REFACTOR 完整循环 |

### 🐛 Debugging
| Skill | 描述 |
|-------|------|
| `systematic-debugging` | 4 阶段根因分析 |
| `verification-before-completion` | 确认真正修复而非表面通过 |

### 🤝 Collaboration
| Skill | 描述 |
|-------|------|
| `brainstorming` | Socratic 式需求细化 |
| `writing-plans` | 详细实现计划 |
| `executing-plans` | 批次执行 + 检查点 |
| `dispatching-parallel-agents` | 并发子 Agent 工作流 |
| `requesting-code-review` | Pre-review checklist |
| `receiving-code-review` | 处理 Review 反馈 |
| `using-git-worktrees` | 并行开发分支管理 |
| `finishing-a-development-branch` | 合并/PR 决策流程 |
| `subagent-driven-development` | 两阶段 Review 的快速迭代 |

### 🧠 Meta
| Skill | 描述 |
|-------|------|
| `writing-skills` | 遵循最佳实践创建新 Skill |
| `using-superpowers` | Skills 系统入门导引 |

---

> 本文件为 [0ooooooooooo/prompts](https://github.com/0ooooooooooo/prompts) 仓库的索引页，
> 实际 Skills 内容请访问 [上游仓库](https://github.com/obra/superpowers)。
