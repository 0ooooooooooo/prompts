# 🧠 prompts

> 个人 AI 技能汇总仓库 · System Prompts · 插件索引 · 工作流 · 模板

---

## 📁 目录结构

```text
prompts/
├── instructions/     # System Prompt & 行为约束
├── plugins/          # 第三方工具 & 插件索引
├── workflows/        # 多步骤端到端工作流
├── personas/         # 专家角色人格设定
├── templates/        # 可复用 Prompt 模板
├── chains/           # 多轮串联 Prompt Chain
├── evaluations/      # Prompt 质量评测用例
└── snippets/         # 高频零碎 Prompt 片段
```

---

## 📂 目录说明

### ✅ instructions/
System Prompt 与角色行为约束。定义 AI 的回答风格、限制边界和工作原则，是所有 Prompt 的基础层。

示例：`frontend-engineer.md` · `code-reviewer.md` · `strict-mode.md`

---

### ✅ plugins/
第三方 AI 工具与插件的索引页。记录来源、安装方式、核心能力，便于快速接入与参考。

示例：`superpowers.md` · `mcp-tools.md` · `claude-code.md`

---

### 🆕 workflows/
完整的多步骤 AI 工作流。与 `plugins/` 互补：plugins 是「工具」，workflows 是「流程」。
适合从 Issue 到 PR、需求到上线等端到端场景。

示例：`issue-to-pr.md` · `debug-flow.md` · `onboarding.md`

---

### 🆕 personas/
专家角色人格设定。与 `instructions/` 区分：
- `instructions/` 约束「**怎么做**」
- `personas/` 定义「**以谁的身份做**」

适合需要特定领域风格回答的场景。

示例：`senior-cto.md` · `socratic-tutor.md` · `security-auditor.md`

---

### 🆕 templates/
可复用的 Prompt 模板，覆盖日常高频场景。填入变量即可使用，是最实用的日常目录。

示例：`prd.md` · `weekly-report.md` · `code-review-checklist.md`

---

### 🆕 chains/
多轮串联的 Prompt Chain。将复杂任务拆解为有序的提示词序列，上一步输出作为下一步输入。
适合需要推理链的深度任务。

示例：`spec-to-test.md` · `research-to-report.md` · `idea-to-code.md`

---

### 🆕 evaluations/
Prompt 质量评测用例。当维护多套 instructions/personas 时，此目录存放对比测试集，长期保障 Prompt 输出质量稳定。

示例：`baseline-cases.md` · `regression-test.md` · `ab-compare.md`

---

### 🆕 snippets/
零碎但高频的单行或短段 Prompt 片段。不成体系但复用率极高，统一收纳避免散落在各处笔记中。

示例：`output-format.md` · `role-constraints.md` · `tone-modifiers.md`

---

---

> **💡 instructions/ vs personas/**
> `instructions/` 写「禁止 var，必须有分号」这类约束；`personas/` 写「你是一位有 15 年经验的 CTO，倾向于从系统稳定性角度思考」这类身份。

> **💡 workflows/ vs chains/**
> `workflows/` 是面向任务场景的完整 SOP（有人工检查点）；`chains/` 是面向单次调用的自动串联提示词序列（纯 Prompt 组合，无人工干预）。

---
> 持续更新中。欢迎 Fork 使用。
