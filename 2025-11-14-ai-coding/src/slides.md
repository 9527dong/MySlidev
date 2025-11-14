---
theme: seriph
title: AI 编程分享：让 AI 成为你的结对程序员
info: |
  ## 讲师：Dong Wang
  分享如何让 AI 在真实团队环境中落地，提高编码与协作效率。
class: text-center
transition: slide-left
mdc: true
---

# AI 编程分享

从灵感、编码到交付，让 AI 成为最稳的结对程序员

<div class="pt-10 text-lg opacity-70">
  2025.11.14 · Online Meetup
</div>

<div class="abs-br m-6 text-sm opacity-60">
  Slides: MySlidev · Powered by Slidev
</div>

---

# 议程

1. 为什么现在一定要学会 AI 编程
2. 工具与角色：如何挑选你的 AI 伙伴
3. 端到端工作流示例
4. 提示工程与代码质量策略
5. 团队落地清单 & Q&A

---

# AI 编程带来的价值

- 🚀 让需求探索与原型验证提速 3-5 倍
- 🧠 保留团队上下文，减少重复回答的心智负担
- 🛡️ 通过自动生成测试与评审清单降低回归风险
- 📚 将最佳实践沉淀到提示模板，形成可复用的知识库

> KPI 不是“AI 写了多少代码”，而是“人类被解放出来解决了多少真正的问题”。

---
layout: two-cols
layoutClass: gap-14
---

# 常用 AI 角色

- 需求澄清：结构化关键约束
- 代码生成：提供骨架并标明待补充内容
- Bug Hunter：基于日志定位根因
- 教练：总结复盘，输出 SOP

::right::

| 工具 | 最佳场景 |
| --- | --- |
| ChatGPT / Claude | 快速讨论方案、补全代码片段 |
| Cursor / Windsurf | 结合上下文的全局改动 |
| Copilot CLI | 批量命令、生成脚本 |
| 自建 RAG Bot | 注入私有仓库知识与流程 |

---

# 端到端工作流

```mermaid
flowchart LR
  A[需求草稿] --> B[提示模板：结构化拆解]
  B --> C[AI 生成设计草图]
  C --> D[人类补充&确认]
  D --> E[Cursor 多文件生成]
  E --> F[AI 生成测试+脚本]
  F --> G[CI / 评审]
  G --> H[知识库沉淀]
```

要点：保持“小步快跑 + 自动校验”循环，每个节点都要有可度量的输出。

---

# 提示工程三要素

1. **环境**：仓库结构、已有约束、技术栈
2. **任务**：期望成果 + 完成定义（DoD）
3. **反馈**：运行结果、错误日志、人工评语

提示示例：

```md
你是团队的API设计守门员。
目标：基于给定schema实现POST /projects。
约束：必须通过已有的 zod 校验，遵循REST约定。
输出：
- 新增文件列表
- 每个文件中的关键片段
- 自我检查 checklist
```

---
layout: image-right
image: https://images.unsplash.com/photo-1520607162513-77705c0f0d4a?auto=format&fit=crop&w=1200&q=80
---

# AI + 人类协作守则

- 明确“由谁最终负责”——AI 只给草案
- 让 AI 解释它的决策依据，再做采纳
- 任何未知输入都先建立沙盒 / mock
- 记录失败案例，持续调优提示

> 坚持“人类评审 -> AI 重构 -> 自动校验”的闭环。

---

# 落地检查清单

- [ ] 选定首批场景（如单元测试、脚手架）
- [ ] 建立提示模板仓库并版本化
- [ ] 训练团队使用 pair-programming 模式
- [ ] 设计度量：提交速度、质量指标、满意度
- [ ] 形成复盘节奏，2 周一小结

---

# Thank You!

欢迎交流你的 AI 编程实践 👇

`dong.wang@example.com`

<div class="text-sm opacity-60">扫描二维码加入交流群（待发布）</div>
