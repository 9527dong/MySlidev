---
theme: default
lineNumbers: false
mdc: true
title: PET 3.0 - 智能项目估算平台
subtitle: 用结构化数据 + AI 重塑项目估算体验
---

# PET 3.0 - 智能项目估算平台

<div class="mt-6 text-lg text-blue-600 font-semibold">核心价值：让每一次项目估算都做到标准化、高效率</div>

<div class="mt-8 text-sm text-gray-500">智估先锋队 (Smart Estimation Vanguard) · Dong Wang</div>

---

# 议程

<div class="grid grid-cols-2 gap-8 mt-4">
<div>

### 🎯 业务价值 (2分钟)

1. 痛点与业务场景分析
2. 解决方案与落地路径

### 🤖 技术方案 (3分钟)

3. 技术栈 & 整体架构概览

</div>
<div>

### 🚀 演示效果 (4分钟)

4. 功能完成度展示
5. 在线网站
6. 功能演示视频

### 👥 团队与Q&A (6分钟)

7. 团队分工
8. Q&A

</div>
</div>

---

# 🎯 为什么需要 PET 3.0？

<div class="mt-4">

| 维度 | 🔥 传统痛点 | ✅ PET 3.0 方案 |
| :--- | :--- | :--- |
| **效率** | Epic 拆分 xx 天，工时计算靠手算 | AI 生成 Epic **分钟级**，公式引擎**秒级计算** |
| **估算标准** | 拍脑袋估算，估算偏差大 | 标准化模板 + 统一费率，口径一致 |
| **解释成本** | "50人天怎么来的？" —— 没人说得清 | 公式引擎逐行计算，**每一步可解释** |
| **数据管理** | Excel/邮件/Smartsheet 分散，历史难追溯 | 统一平台，项目全生命周期可追踪 |

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

<div class="mt-2">
  <!-- 流程图 - 使用 items-start 让所有框顶部对齐 -->
  <div class="flex items-start justify-center gap-1 text-sm">
    <div class="px-3 py-2 border border-gray-300 rounded bg-white mt-0">元数据</div>
    <span class="text-gray-400 text-xs mt-3">····▶</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">项目创建</div>
    <span class="text-gray-400 mt-3">→</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">BRD录入</div>
    <span class="text-gray-400 mt-3">→</span>
    <!-- Epic录入 - 带连接线和标签 -->
    <div class="flex flex-col items-center">
      <div class="px-4 py-2 border-2 border-purple-500 rounded bg-purple-500 text-white font-bold">Epic录入</div>
      <div class="w-0.5 h-4 border-l-2 border-dashed border-purple-400"></div>
      <div class="flex items-center gap-1">
        <div class="bg-purple-100 text-purple-700 px-3 py-1 rounded-full text-xs font-bold border border-purple-300">🤖 AI 生成Epic</div>
      </div>
    </div>
    <span class="text-gray-400 mt-3">→</span>
    <!-- 工时估算 - 带连接线和标签 -->
    <div class="flex flex-col items-center">
      <div class="px-4 py-2 border-2 border-red-400 rounded bg-red-400 text-white font-bold">工时估算</div>
      <div class="w-0.5 h-4 border-l-2 border-dashed border-red-400"></div>
      <div class="bg-red-100 text-red-700 px-3 py-1 rounded-full text-xs font-bold border border-red-300">⚙️ 公式引擎自动计算</div>
    </div>
    <span class="text-gray-400 mt-3">→</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">OGM估算</div>
    <span class="text-gray-400 mt-3">→</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">报表生成</div>
  </div>
</div>

<div style="font-size: 0.65rem;">

| 环节 | 📋 当前方式 | 🚀 PET 3.0 | 核心提升 |
| :---: | :--- | :--- | :--- |
| 项目管理 | SmartSheet 多平台 | 统一平台，一站式管理 | 平台统一 |
| BRD 录入 | Excel 手动维护 | 系统结构化录入 | 数据结构化 |
| **Epic 录入** | 人工逐条录入 | **🤖 AI 智能生成，PM 仅需 Review** | **效率提升** |
| **工时估算** | 拍脑袋，Excel 手算 | **⚙️ 公式引擎自动计算** | **效率提升、标准化** |
| OGM 估算 | Excel 手工填写 | 表单化填写，体验友好 | 体验提升 |
| 报表生成 | 透视表，样式简陋 | 实时生成，可视化报表 | 实时可视化 |

</div>

---

# 🏗️ 整体架构概览

<div class="grid grid-cols-5 gap-6 items-center mt-6" style="font-size: 0.82rem;">
<div class="col-span-2 flex items-center justify-center">

  <div class="rounded-2xl border-2 border-purple-300 bg-gradient-to-br from-purple-50 to-purple-100/70 p-6 shadow-lg w-full">
    <div class="flex gap-2 text-xl font-bold text-purple-800 mb-4">
      🤖 AI 能力
    </div>
    <ul class="space-y-3 text-sm text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI 生成需求</span>：DeepSeek API（JSON Mode），提升Epic生成效率</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI Coding</span>：Cursor、Codex 提升研发效率</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI PPT制作</span>：Cursor + Slidev，提升写PPT的效率</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI 视频编辑</span>：Cursor + Remotion，提升视频编辑的效率</span>
      </li>
    </ul>
  </div>

</div>
<div class="col-span-3">

### 整体架构

<div class="flex flex-col items-center gap-2 mt-2">
  <div class="w-full bg-blue-50 border border-blue-300 rounded-lg p-2">
    <div class="text-blue-700 font-bold text-sm text-center">🖥️ 客户端</div>
    <div class="text-xs text-gray-600 mt-1 text-center">表单渲染 · 结果展示 · 可视化报表</div>
  </div>
  <div class="text-blue-400 text-xl">↓</div>
  <div class="w-full bg-amber-50 border border-amber-300 rounded-lg p-2">
    <div class="text-amber-700 font-bold text-sm text-center">⚙️ 服务端</div>
    <div class="text-xs text-gray-600 mt-1 text-center">Server API · 元数据配置 · 规则引擎等</div>
  </div>
  <!-- 两个箭头分别指向 AI 层和存储层 -->
  <div class="w-full flex justify-around text-amber-400 text-xl">
    <span>↓</span>
    <span>↓</span>
  </div>
  <!-- AI 层和存储层并排 -->
  <div class="w-full flex gap-2">
    <div class="flex-1 bg-purple-50 border border-purple-300 rounded-lg p-2">
      <div class="text-purple-700 font-bold text-sm text-center">🧠 AI 层</div>
      <div class="text-xs text-gray-600 mt-1 text-center">DeepSeek API (Epic 生成)</div>
    </div>
    <div class="flex-1 bg-green-50 border border-green-300 rounded-lg p-2">
      <div class="text-green-700 font-bold text-sm text-center">💾 存储层</div>
      <div class="text-xs text-gray-600 mt-1 text-center">PostgreSQL（角色/模板/公式/常量等）</div>
    </div>
  </div>
</div>

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

# 🎬 在线网站

<div class="mt-10 flex justify-center">
<div class="w-full max-w-4xl rounded-2xl bg-gradient-to-br from-blue-50 to-purple-50/60 ring-1 ring-blue-200 shadow-xl p-8">
<div class="flex items-center justify-center gap-3 mb-6">
<div class="text-5xl leading-none">🚀</div>
<div class="text-3xl font-extrabold tracking-tight text-gray-900">PET 3.0 在线体验</div>
</div>
<div class="grid grid-cols-2 gap-10 items-start">
<div class="space-y-4">
<div class="text-sm text-gray-600">在线体验</div>
<a class="block rounded-xl border border-blue-200 bg-white/80 hover:bg-white transition px-5 py-3 font-mono text-base text-blue-700 shadow-sm select-all break-all" href="https://pet30.vercel.app/" target="_blank" rel="noopener noreferrer">https://pet30.vercel.app/</a>
<div class="rounded-xl border border-amber-200 bg-amber-50/70 px-4 py-3 text-sm text-amber-900 leading-snug">
<div class="font-semibold">⚠️ 国内网络可能无法访问</div>
<div class="text-xs opacity-80 mt-1">建议科学上网 / 切换网络环境后再试</div>
</div>
</div>
<div class="flex flex-col items-center">
<div class="text-sm text-gray-600 mb-3">扫码直达</div>
<div class="w-28 h-28 rounded-lg shadow-md overflow-hidden">
<img class="w-full h-full" alt="PET 3.0 在线演示二维码" src="./assets/pet30-demo-qr.png" />
</div>
<div class="text-xs text-gray-500 mt-2">手机浏览器打开更顺畅</div>
</div>
</div>
</div>
</div>

<div class="mt-6 text-center text-gray-500 text-sm">💡 演示环境已部署，欢迎体验完整功能流程</div>

---

# 🎥 功能演示视频

<div class="flex items-center justify-center h-full">
<div class="text-center">
<div class="text-6xl mb-6">🎬</div>
<div class="text-2xl text-gray-400">演示视频区域</div>
<div class="text-sm text-gray-400 mt-4">请在此处插入演示视频</div>
</div>
</div>

---

# 👥 团队分工

<div class="grid grid-cols-3 gap-3 mt-4 text-center">

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👨‍🎨</div>
  <div class="font-bold text-sm">Jeff Bu(卜昌荣)</div>
  <div class="text-xs text-gray-500">Delivery Manager</div>
  <div class="text-xs mt-1 text-purple-600">跨部门沟通/需求管理/整体进度把控</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👨‍💻</div>
  <div class="font-bold text-sm">Dong Wang(王栋)</div>
  <div class="text-xs text-gray-500">Tech Lead</div>
  <div class="text-xs mt-1 text-purple-600">架构设计 / Cost Breakdown模块开发</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👩‍💻</div>
  <div class="font-bold text-sm">Maggie Zhu(朱玥)</div>
  <div class="text-xs text-gray-500">Full Stack</div>
  <div class="text-xs mt-1 text-purple-600">项目管理、Opex、报表等模块开发</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👩‍💻</div>
  <div class="font-bold text-sm">Summer Zhang(张夏倩)</div>
  <div class="text-xs text-gray-500">Scrum Master</div>
  <div class="text-xs mt-1 text-purple-600">组织会议、跨部门沟通</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👨‍🎨</div>
  <div class="font-bold text-sm">Groot Zhang(涨潮)</div>
  <div class="text-xs text-gray-500">Technical support</div>
  <div class="text-xs mt-1 text-purple-600">提供技术支持</div>
</div>

</div>

<div class="mt-4 pt-3 border-t border-gray-200">
  <div class="text-center">
    <div class="text-base font-semibold text-purple-600 mb-2">🙏 特此感谢</div>
    <div class="text-sm text-gray-700">
      <span class="font-medium">Cecilia Guo</span>、<span class="font-medium">Chunyang Liu</span>
    </div>
    <div class="text-xs text-gray-500 mt-1">为本项目提供的专业建议</div>
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

<!--
准备好回答：
1. cost breakdown那块的功能Excel也能实现，web版本有啥优势呢？
答：可协作，统一的输入校验，可追溯的计算过程，性能好，可维护性好。
2. 如后续变为一个正式的项目，是多大规模的项目呢？
答：正式做项目的话，需要多个角色配合(PM,qa,gqe,se,l2等)，如使用现有技术栈，在现有的代码仓库上开发，可以节省开发的工作量。同时需求没有大的变动的情况下，RC项目可以cover。如果需要完全符合我们公司的技术栈要求，需要重写前后端，代码无法复用，small Car规模的项目可以cover。
3. ai生成Epic和直接掉ai 接口有啥区别？
答：核心亮点在于 强约束输出结构 + 带层级上下文生成 + 结果可控导入到需求树（并受数据库规则兜底）。固定 schema（字段/枚举/数量/长度）：系统 Prompt 把 Epic 的字段（title/description/priority/hours/keyFeatures）和范围约束写死了，模型输出天然更“像表格数据”，而不是散文。由于当前我没有导入真实的I pick，未来的话，我们可以用真实的其他项目的Epic进行训练。生成IP卡的时候，可以通过这种相似性检索，找到其项目类似的这种IP卡，然后以便发给II让AI来参考。这样我们就可以生成更加准确的IP卡。
根据现有规范生成guideline，可以让他准确性更高。给他好的Epic和brd，让他自己学习。并加入对话机制，可以根据上下文去调整Epic内容。

4. 上线计划和推广策略？
-->