workflows/ — 和 plugins/ 最互补。plugins 是"工具"，workflows 是"流程"，比如"从 GitHub Issue 到 PR 的完整 AI 辅助流程"。
personas/ — 和 instructions/ 区分：instructions 是行为约束，personas 是身份扮演（适合需要特定专业领域回答风格的场景）。
templates/ — 最实用的日常目录，PRD、技术方案、邮件、代码 Review checklist 等都可以放这里。
chains/ — 针对复杂任务的 Prompt 串联，比如"先提取需求 → 再生成测试用例 → 再生成实现代码"。
evaluations/ — 如果你有多套 instructions/personas，这里放对比测试用例，长期维护 Prompt 质量。
