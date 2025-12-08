---
theme: default
lineNumbers: false
mdc: true
title: PET 3.0 - AI 驱动的智能项目估算平台
subtitle: 用结构化数据 + AI 重塑项目估算体验
---

# PET 3.0 - AI 驱动的智能项目估算平台

<div class="mt-6 text-lg text-blue-600 font-semibold">核心价值：让每一次项目估算都有据可循、有迹可查、降本增效</div>

<div class="mt-8 text-sm text-gray-500">PET 团队 · Dong Wang</div>

---

# 议程

<div class="grid grid-cols-2 gap-8 mt-4">
<div>

### 🎯 业务价值 (2分钟)

1. 痛点与业务场景分析
2. 解决方案与落地路径

### 🤖 技术方案 (3分钟)

3. AI Epic生成技术架构
4. Cost Breakdown功能技术原理

</div>
<div>

### 🚀 演示效果 (4分钟)

5. Live Demo
6. 功能完成度展示

### 👥 团队与Q&A (1分钟)

7. 团队分工
8. Q&A

</div>
</div>

---

# 🎯 为什么需要 PET 3.0？

<div class="mt-4">

| 维度 | 🔥 传统痛点 | ✅ PET 3.0 方案 |
| :--- | :--- | :--- |
| **数据管理** | Excel/邮件/Smartsheet 分散，历史难追溯 | 统一平台，项目全生命周期可追踪 |
| **估算一致性** | 拍脑袋估算，估算偏差大 | 标准化模板 + 统一费率，口径一致 |
| **解释成本** | "50人天怎么来的？" —— 没人说得清 | 公式引擎逐行计算，**每一步可解释** |
| **效率** | Epic 拆分 xx 天，工时计算靠手算 | AI 生成 Epic **分钟级**，公式引擎**秒级计算** |

</div>

<div class="grid grid-cols-3 gap-4 mt-8 text-center">
  <div class="bg-red-50 border border-red-200 rounded-lg p-4">
    <div class="text-red-500 text-3xl font-bold">Before</div>
    <div class="text-gray-600 mt-2">黑盒 · 低效 · 不可控</div>
  </div>
  <div class="text-4xl flex items-center justify-center text-blue-500">→</div>
  <div class="bg-green-50 border border-green-200 rounded-lg p-4">
    <div class="text-green-500 text-3xl font-bold">After</div>
    <div class="text-gray-600 mt-2">透明 · 高效 · 可解释</div>
  </div>
</div>

---

# 🎯 业务场景：项目成本估算全链路

<div class="text-center mb-4">

```mermaid
graph LR
    A[元数据] -.-> B[项目创建] --> C[BRD录入] --> D[Epic录入]
    D --> E[工时估算]
    E --> F[OGM估算]
    F --> G[报表生成]
    style D fill:#a855f7,stroke:#333,stroke-width:2px,color:#fff
    style E fill:#ff6b6b,stroke:#333,stroke-width:2px,color:#fff
```

</div>

<div class="mt-2 text-center">
  <span class="bg-purple-100 text-purple-700 px-3 py-1 rounded-full text-xs font-bold mr-2">🤖 AI 加持</span>
  <span class="bg-red-100 text-red-700 px-3 py-1 rounded-full text-xs font-bold">⚙️ 规则引擎</span>
  <span class="text-gray-400 ml-2 text-xs">← 核心创新点</span>
</div>

<div style="font-size: 0.65rem;">

| 环节 | 📋 当前方式 | 🚀 PET 3.0 | 核心提升 |
| :---: | :--- | :--- | :--- |
| 元数据 | Excel 分散维护，无权限 | 管理员统一配置，全局生效 | 集中管控 |
| 项目管理 | SmartSheet 多平台 | 统一平台，一站式管理 | 平台统一 |
| BRD 录入 | Excel 手动维护 | 系统结构化录入 | 数据结构化 |
| **Epic 录入** | 人工逐条录入 | **🤖 AI 智能生成，PM 仅需 Review** | **AI 自动化** |
| **工时估算** | 拍脑袋，Excel 手算 | **⚙️ 公式引擎自动计算** | **规则引擎** |
| OGM 估算 | Excel 手工填写 | 表单化填写，体验友好 | 体验提升 |
| 报表生成 | 透视表，样式简陋 | 实时生成，可视化报表 | 实时可视化 |

</div>


---

# 🤖 AI Epic 生成技术架构

<div class="grid grid-cols-2 gap-4" style="font-size: 0.65rem;">
<div>

### 系统架构

<div class="flex flex-col items-center gap-2 mt-2">
  <div class="w-full bg-blue-50 border-2 border-blue-400 rounded-lg p-2">
    <div class="text-blue-600 font-bold text-sm">📝 用户输入需求描述</div>
    <div class="text-xs text-gray-600 mt-1">选择 BRD · 输入功能需求 · 快速模板</div>
  </div>
  <div class="text-blue-400 text-xl">↓</div>
  <div class="w-full bg-purple-50 border-2 border-purple-400 rounded-lg p-2">
    <div class="text-purple-600 font-bold text-sm">🧠 Prompt Engineering</div>
    <div class="text-xs text-gray-600 mt-1">BRD 上下文注入 · 结构化输出约束 · JSON Schema</div>
  </div>
  <div class="text-purple-400 text-xl">↓</div>
  <div class="w-full bg-amber-50 border-2 border-amber-400 rounded-lg p-2">
    <div class="text-amber-600 font-bold text-sm">⚡ DeepSeek 大模型</div>
    <div class="text-xs text-gray-600 mt-1">硅基流动 API · JSON Mode</div>
  </div>
  <div class="text-amber-400 text-xl">↓</div>
  <div class="w-full bg-green-50 border-2 border-green-400 rounded-lg p-2">
    <div class="text-green-600 font-bold text-sm">📊 结构化 Epic 输出</div>
    <div class="text-xs text-gray-600 mt-1">5-8 个 Epic · 优先级/功能点 · 批量入库</div>
  </div>
</div>

</div>
<div>

### 技术亮点

🎯 **结构化 Prompt 设计**
- 注入 BRD 标题、层级、现有 Epic 作为上下文
- 严格 JSON Schema 约束输出格式
- 预设生成要求：标题 10-30 字、描述 50-150 字

🔒 **输出质量保障**
- `response_format: json_object` 强制 JSON 输出
- 服务端二次校验 + 类型断言

<div class="text-green-600 font-bold mt-2" style="font-size: 0.95rem;">✅ 30秒生成 5-8 个专业 Epic，效率提升 10x</div>

</div>


</div>

---

# 🔬 Cost Breakdown：数据模型设计

<div class="grid grid-cols-2 gap-6" style="font-size: 0.65rem;">
<div>

#### 多层配置体系

```
Team (团队)
  └── Role (角色)
        └── TaskTemplate (任务模板)
              ├── Parameters[] (参数定义)
              ├── Formula (公式)
              │     └── Constants[] (常量)
              └── category: shared | epic
```

#### 核心表结构

| 表名 | 作用 |
|------|------|
| `task_templates` | 角色任务模板，关联公式 |
| `parameters` | 参数定义（类型/约束/默认值）|
| `formulas` | 公式表达式 + 计算引擎 |
| `formula_constants` | 可配置常量（可编辑标记）|
| `epic_estimations` | 估算结果 + breakdown |

</div>
<div>

#### 设计亮点

⚙️ **配置与代码分离**
- 新增任务类型只需配置数据库，无需发版
- 公式、常量、参数约束均可热更新

📝 **完整估时链路**

```sql
epic_estimations (
  inputs JSONB,      -- 用户原始输入
  breakdown JSONB,   -- 计算过程快照
  computed_hours,    -- 最终结果
  created_by,        -- 操作人
  created_at         -- 时间戳
)
```

<div class="text-blue-600 font-bold mt-2"  style="font-size: 0.95rem;">💡 任意历史估算都可完整复现计算过程</div>

</div>
</div>

---

# 🔬 Cost Breakdown：动态公式引擎

<div class="grid grid-cols-2 gap-4" style="font-size: 0.65rem;">
<div>

### 核心架构

<div class="flex flex-col items-center gap-2 mt-2">
  <div class="w-full bg-blue-50 border-2 border-blue-400 rounded-lg p-2">
    <div class="text-blue-600 font-bold text-sm">📝 用户输入参数表单</div>
    <div class="text-xs text-gray-600 mt-1">选择Epic、Role、taskTemplate · 输入参数</div>
  </div>
  <div class="text-blue-400 text-xl">↓</div>
  <div class="w-full bg-amber-50 border-2 border-amber-400 rounded-lg p-2">
    <div class="text-amber-600 font-bold text-sm">🔒 InputValidator 参数校验层</div>
    <div class="text-xs text-gray-600 mt-1">类型校验 · 范围约束 · 精度控制</div>
  </div>
  <div class="text-amber-400 text-xl">↓</div>
  <div class="w-full bg-purple-50 border-2 border-purple-400 rounded-lg p-2">
    <div class="text-purple-600 font-bold text-sm">⚙️ FormulaEngine 公式解析执行层</div>
    <div class="text-xs text-gray-600 mt-1">expr-eval 解析器 · 变量注入 · 数学运算</div>
  </div>
  <div class="text-purple-400 text-xl">↓</div>
  <div class="w-full bg-green-50 border-2 border-green-400 rounded-lg p-2">
    <div class="text-green-600 font-bold text-sm">📊 Breakdown 计算过程保存</div>
    <div class="text-xs text-gray-600 mt-1">原始公式 · 解析表达式 · 结果快照</div>
  </div>
</div>

</div>
<div>

### 技术亮点

🧮 **可配置公式引擎**
- 公式存储在数据库，**无需改代码即可调整计算逻辑**
- 支持用户输入、常量两种类型参数
- 支持复杂表达式

🔒 **多层参数校验**
- 类型转换 + 范围约束 + 步长验证 + 枚举匹配

📊 **计算过程快照示例**

```
{
  "expression": "page_count * base_hours",
  "resolved": "5 * 16",
  "result": 80,
  "unit": "hour"
}
```

<div class="text-green-600 font-bold mt-2">✅ 解释时可精确还原每一步计算</div>

</div>
</div>

---

# 🚀 功能完成度：已实现模块一览


<div class="grid grid-cols-4 gap-3">

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">用户管理</div>
  <div class="text-xs text-gray-600 mt-1">
    - 登录认证<br>
    - 用户 CRUD<br>
    - 用户统计
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">元数据管理</div>
  <div class="text-xs text-gray-600 mt-1">
    - Foundation Epic CRUD<br>
    - 核心参数配置
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">项目管理</div>
  <div class="text-xs text-gray-600 mt-1">
    - 项目信息 CRUD<br>
    - 搜索/筛选/分页<br>
    - 批量状态更新
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">BRD & Epic</div>
  <div class="text-xs text-gray-600 mt-1">
    - BRD&Epic CRUD<br>
    - AI 生成 Epic<br>
    - dashboard
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">Cost Breakdown</div>
  <div class="text-xs text-gray-600 mt-1">
    - 动态参数表单<br>
    - 公式引擎解析<br>
    - CRUD
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">OGM 估算</div>
  <div class="text-xs text-gray-600 mt-1">
    - 工时自动汇总<br>
    - 多维度统计<br>
    - CRUD
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">预算报表</div>
  <div class="text-xs text-gray-600 mt-1">
    - 可视化图表<br>
    - BRD&EPIC Summary<br>
    - Budget Summary
  </div>
</div>

<div class="border rounded-lg p-3 bg-blue-50">
  <div class="text-xl mb-1">⚙️</div>
  <div class="font-bold text-sm">技术基座</div>
  <div class="text-xs text-gray-600 mt-1">
    - CI/CD 自动化<br>
    - DataBase 集成<br>
    - 云服务器部署集成
  </div>
</div>

</div>

<div class="mt-4 text-center">
<span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full font-bold text-sm">
  7 大业务模块 + 完整技术栈 · 100% 可运行 · 演示环境已部署
</span>
</div>

---

# 🎬 Live Demo

<div class="flex flex-col items-center justify-center mt-6">

<div class="border-4 border-blue-500 rounded-2xl p-8 bg-gradient-to-br from-blue-50 to-purple-50 shadow-lg">
  <div class="text-6xl text-center mb-4">🚀</div>
  <div class="text-2xl font-bold text-center text-gray-800 mb-4">PET 3.0 在线演示</div>
  <div class="text-center">
    <code class="bg-white px-4 py-2 rounded-lg text-lg font-mono text-blue-600 border">
      https://pet30.vercel.app/
    </code>
  </div>
</div>

<div class="mt-6 text-center text-gray-500 text-sm">
  💡 演示环境已部署，欢迎体验完整功能流程
</div>

</div>

---

# 👥 团队分工

<div class="grid grid-cols-4 gap-4 mt-6 text-center">

<div class="border rounded-lg p-4">
  <div class="text-3xl mb-2">👨‍🎨</div>
  <div class="font-bold">Jeff Bu</div>
  <div class="text-sm text-gray-500">Delivery Manager</div>
  <div class="text-xs mt-2 text-purple-600">跨部门沟通/需求管理/整体进度把控</div>
</div>

<div class="border rounded-lg p-4">
  <div class="text-3xl mb-2">👨‍💻</div>
  <div class="font-bold">Dong Wang</div>
  <div class="text-sm text-gray-500">Tech Lead</div>
  <div class="text-xs mt-2 text-purple-600">架构设计 / Cost Breakdown模块开发</div>
</div>

<div class="border rounded-lg p-4">
  <div class="text-3xl mb-2">👩‍💻</div>
  <div class="font-bold">Maggie Zhu</div>
  <div class="text-sm text-gray-500">Full Stack</div>
  <div class="text-xs mt-2 text-purple-600">项目管理、Opex、报表等模块开发</div>
</div>

<div class="border rounded-lg p-4">
  <div class="text-3xl mb-2">👩‍💻</div>
  <div class="font-bold">Summer Zhang</div>
  <div class="text-sm text-gray-500">Scrum Master</div>
  <div class="text-xs mt-2 text-purple-600">组织会议、跨部门沟通</div>
</div>

<div class="border rounded-lg p-4">
  <div class="text-3xl mb-2">👨‍🎨</div>
  <div class="font-bold">Groot Zhang</div>
  <div class="text-sm text-gray-500">Technical support</div>
  <div class="text-xs mt-2 text-purple-600">提供专业建议</div>
</div>

</div>

---

# 🙏 谢谢聆听

<div class="text-center mt-16">

<div class="text-6xl mb-8">🤖 + 📊 = 🚀</div>

<div class="text-2xl font-bold mb-4">用结构化数据，让项目估算标准快捷</div>

<div class="text-lg text-gray-500 mb-8">PET 3.0 - 智能项目估算平台</div>

<div class="inline-block bg-gradient-to-r from-blue-500 to-purple-500 text-white px-8 py-4 rounded-full text-xl font-bold">
  Q & A 环节
</div>

</div>

<!--
准备好回答：
1. AI 技术具体怎么实现的？
2. 数据安全如何保障？
3. 与现有系统如何集成？
4. 上线计划和推广策略？
-->