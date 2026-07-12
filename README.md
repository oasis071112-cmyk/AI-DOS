# AI Design Operating System（AI-DOS）项目规划

## 项目定位

AI Design Operating System（AI-DOS）不是一个 Prompt 集合，也不是一个 Design System。

它是一个专为 AI Agent 设计的 **Design Knowledge Base + Agent Skill Framework + Pattern Library + Engineering Guide**。

项目目标是：

> Teach AI to think like a world-class design team.

而不是：

> Teach AI to generate beautiful UI.

AI-DOS 的核心价值是帮助 AI 从产品、设计、用户体验、工程实现等多个维度进行统一思考，而不是仅关注视觉效果。

---

# GitHub Repository

Repository Name

```text
ai-design-operating-system
```

Project Alias

```text
AI-DOS
```

Description

```text
A modular Design Operating System for AI Agents.
```

Alternative Description

```text
Teach AI to design like world-class product teams.
```

Repository Visibility

建议使用 **Public**。

原因：

* 支持社区贡献（Pull Request）
* 支持 Issue 与 Discussion
* 支持长期维护与版本演进
* 建立 AI Design 知识生态

License

建议：

MIT

未来如有商业化需求，可扩展为 Community / Pro 双版本策略。

---

# Repository Structure

第一版仓库结构如下：

```text
ai-design-operating-system/

README.md
LICENSE
CHANGELOG.md
ROADMAP.md
CONTRIBUTING.md
.gitignore

.github/

docs/

skill/

knowledge/

patterns/

components/

templates/

examples/

review/

tokens/

prompts/
```

第一阶段重点是建立稳定的目录结构，而不是一次性填充大量内容。

---

# Documentation

docs/

包含项目文档：

```text
Vision.md
Architecture.md
Principles.md
Roadmap.md
GettingStarted.md
```

README 仅负责介绍项目。

详细文档统一维护在 docs 中。

---

# Knowledge Layer

knowledge/

```text
brand/
philosophy/
visual/
motion/
layout/
ux/
engineering/
performance/
accessibility/
quality/
anti-patterns/
```

Knowledge Layer 是整个 AI-DOS 的核心知识体系，也是所有 Agent 的主要知识来源。

---

# Skill Layer

```text
skill/

skill.md
manifest.md
loader.md
```

skill.md 作为 Agent 的入口。

manifest.md 描述能力与模块。

loader.md 定义模块加载策略。

不同 Agent（Claude Code、Cursor、Codex、Gemini CLI 等）均可基于该结构进行扩展。

---

# Pattern Library

```text
patterns/

landing/
dashboard/
pricing/
authentication/
blog/
docs/
console/
settings/
enterprise/
```

Pattern Library 用于定义页面组织方式，而不仅仅是组件。

每个 Pattern 包括：

* 使用场景
* 页面结构
* 信息层级
* 动效策略
* 响应式规范
* 最佳实践

---

# Example Library

```text
examples/

landing/
dashboard/
pricing/
motion/
components/
```

通过完整示例帮助 AI 学习真实的设计方式，而不是孤立组件。

---

# Review System

```text
review/

design.md
motion.md
performance.md
ux.md
brand.md
premium.md
```

AI 在完成设计后，应执行自动 Review，包括：

* Brand Consistency
* Typography
* Spacing
* Motion
* Accessibility
* Performance
* Premium Score

如评分未达到目标，应自动优化后再次 Review。

---

# Design Tokens

```text
tokens/

colors.json
spacing.json
radius.json
shadow.json
motion.json
typography.json
```

Design Tokens 作为整个系统的统一数据源，可用于：

* Tailwind Config
* CSS Variables
* Figma Variables
* Design Token Pipeline

---

# GitHub Configuration

建议从项目初期即启用：

* Issue Templates
* Pull Request Template
* GitHub Discussions
* GitHub Projects
* Wiki

确保项目具备良好的协作能力与长期维护能力。

---

# Version Roadmap

```text
v0.1.0
Foundation

↓

v0.2.0
Visual Language

↓

v0.3.0
Motion System

↓

v0.4.0
Component Library

↓

v0.5.0
Pattern Library

↓

v0.6.0
Engineering Guide

↓

v0.7.0
Review System

↓

v1.0.0
Stable Release
```

每个版本都应包含：

* 完整目录结构
* CHANGELOG
* Release Notes
* Milestone
* 对应文档更新

采用持续迭代的方式推进，而不是一次性完成全部内容。

---

# 开发原则

AI-DOS 应按真正的开源软件项目进行维护，而不是作为一次性的 Prompt 仓库。

每完成一个模块：

* 提交一次 Commit
* 更新 CHANGELOG
* 更新对应文档
* 发布版本标签（Tag）

通过版本化、模块化和持续演进的方式，最终构建一个可维护、可扩展、可复用的 AI Design Operating System，为 AI Agent 提供长期稳定的设计知识体系。
