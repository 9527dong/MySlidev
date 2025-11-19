---
theme: default
highlighter: shiki
lineNumbers: false
mdc: true
title: PET 3.0 - 智能项目估算工具
subtitle: Next.js + Supabase 驱动的 AI 项目协作
---

# PET 3.0 - 智能项目估算工具

打造一套以 Next.js + Supabase 为核心的现代化管理平台，用结构化数据让 AI 真正落地项目协作。

<div class="mt-8 text-sm text-gray-500">Dong Wang · PET 团队</div>

---

# 议程

1. 为什么需要 PET 3.0
2. PET 3.0 解决方案蓝图
3. 项目管理模块成果
4. Cost Breakdown AI 估算引擎（POC）
5. 技术栈与架构
6. Demo 路线（3 分钟）
7. 业务价值与 ROI


---
layout: two-cols
---

## 现状：非结构化的黑盒

❌ **经验主义**：估算靠拍脑袋，不同Team估算口径差异大

❌ **数据孤岛**：Excel、邮件、smartsheet，数据分散在多个系统，无法做到全链路追踪

❌ **难以审计**：为什么是 50 人天？没人说得清

::right::

## PET 3.0：结构化的智能

✅ **数据标准化**：统一的角色、费率、任务模板

✅ **过程透明化**：基于公式的计算，每一步有迹可循

✅ **AI 就绪**：将感性经验转化为结构化数据，供 AI 学习

<!-- 
建议：这里可以配一张 Excel 混乱截图 vs PET 清晰界面的对比图
-->

---

# PET 3.0 解决方案蓝图

1. **数据底座**：Next.js App Router + Supabase，统一账户、权限和实时数据
2. **项目管理模块**：覆盖项目全生命周期 CRUD、筛选、批量操作
3. **Cost Breakdown 引擎**：基于模板 + 公式的动态工时计算，可扩展到 AI 辅助
4. **洞察与自动化**：为后续 LLM 解析需求、自动推荐模板打基础

<!--
- 先讲全貌，再逐个击穿
- 指出现在已经完成 1&2，POC 出 3，下一步冲刺 4
-->

---

# 项目管理模块成果

- 13 个核心字段的项目主表 + LOB、CapEx 等配置表，全部具备 RLS 策略
- Server Actions + Zod 表单验证，支持创建、编辑、删除、批量操作
- 列表页提供搜索、筛选、分页、状态批量更新，性能 <1s
- UI 基于 TailwindCSS + shadcn/ui，桌面/移动双端适配

<!--
- 可展示截图或现场走一遍 `/dashboard/projects`
- 强调“可部署”“可扩展”，比赛评委更看成熟度
-->

---

# Cost Breakdown AI 估算引擎（POC）

- Shared Epic 与普通 Epic 统一模板体系，编号以 `0` 判定共享任务
- Supabase 中维护角色任务模板、参数、公式、常量，Server Actions 渲染动态表单
- 估算结果写入 `epic_estimations`，含 breakdown JSON，透明记录每一步
- 可挂接 Edge Functions / LLM，实现批量导入、公式推荐

<!--
- 展示 JSON breakdown 示例，突出“过程可解释”
- 说明这是我们参赛的 AI 亮点：数据结构化后 AI 才能发挥
-->

---

# 技术栈与架构

- **前端**：Next.js 15、React 18、App Router、Server Component 预取
- **设计系统**：TailwindCSS、shadcn/ui、Figma 组件规范
- **后端**：Supabase Postgres、Auth、Realtime、Edge Functions 预留
- **DevOps**：pnpm、ESLint、TypeScript、Vercel 一键部署

<!--
- 突出“官方最佳实践”与工程可信度
- 提醒评委：我们不用额外搭建后端，Supabase 让迭代更快
-->

---

# 数据模型与安全

- `teams / roles / task_templates / parameters` 形成可配置的估算参数树
- `formulas + formula_constants` 支持版本化、可扩展计算引擎
- `epic_estimations` 记录输入、常量、解析表达式，方便审计
- 全量启用 Row Level Security，配合 Supabase Auth 与 JWT

<!--
- 用一张简易 ER 图或表格快速带过
- 安全话题是评委高频问题，提前回答
-->

---

# 体验 · 性能 · 质量

- `pnpm build`、TS、ESLint 全量通过，演示环境多次验证
- 首屏 <2s、搜索 <1s、表单提交 <3s，分页针对大数据优化
- Loading、Toast、确认弹窗等交互细节完整，支持移动端
- 自动化脚本：`pnpm db:init*`、`pnpm db:verify`、`pnpm db:diagnose`

<!--
- 展示性能数字，说明不是 PPT 项目
- 可加一张动态图显示交互体验
-->

---

# Demo 路线（3 分钟）

1. 注册/登录展示完整认证流程（Supabase Auth）
2. 仪表盘概览 + 项目列表筛选、批量操作
3. Cost Breakdown：选择 Epic → 动态参数表单 → 生成估算 → 查看 breakdown

<!--
- 将流程写进 README 里的路径 `/register`、`/dashboard/users`、`/dashboard/projects`
- 现场演示时注意提前填好种子数据
-->

---

# 业务价值与 ROI

- 估算时间从数小时降到十分钟内，排期决策提前 1-2 天
- 跨团队共享任务只算一次，人天浪费预计下降 20%+
- 项目信息与成本拆解联动，方便 PMO/财务实时掌控预算
- 为后续 AI 自动推荐模板、预测超支提供训练数据

<!--
- 可引用内部试点或预估数字
- 强调“AI 不止是 Demo，是真实提升效率”
-->

---

# 路线图与参赛诉求

- **Q2**：补齐任务模板管理后台、导入工具、Edge Functions 批处理
- **Q3**：引入 LLM 解析 PRD、自动分配模板、生成初版估算
- **Q4**：结合项目实际工时回填，训练 Cost vs Actual 模型
- 参赛诉求：希望评委关注“数据底座 + AI 迭代”能力，并给予真实业务场景试点机会

<!--
- 结束语：我们已经打好地基，期待与评委一起把 AI 估算推向生产
-->