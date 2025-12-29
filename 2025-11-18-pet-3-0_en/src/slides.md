---
theme: default
lineNumbers: false
mdc: true
title: PET 3.0 - Intelligent Project Estimation Platform
subtitle: Reshaping Project Estimation Experience with Structured Data + AI
---

# PET 3.0 - Intelligent Project Estimation Platform

<div class="mt-6 text-lg text-blue-600 font-semibold">Core Value: Standardize and streamline every project estimation</div>

<div class="mt-8 text-sm text-gray-500">Smart Estimation Vanguard · Dong Wang</div>

---

# Agenda

<div class="grid grid-cols-2 gap-8 mt-4">
<div>

### 🎯 Business Value (2 minutes)

1. Pain points and business scenario analysis
2. Solution and implementation path

### 🤖 Technical Solution (3 minutes)

3. Tech stack & overall architecture overview

</div>
<div>

### 🚀 Demo (4 minutes)

4. Feature completion showcase
5. Online website
6. Feature demo video

### 👥 Team & Q&A (6 minutes)

7. Team division
8. Q&A

</div>
</div>

---

# 🎯 Why PET 3.0?

<div class="mt-3" style="font-size: 0.75rem;">

| Dimension | 🔥 Traditional Pain Points | ✅ PET 3.0 Solution |
| :--- | :--- | :--- |
| **Efficiency** | Epic breakdown takes days, manual calculation | AI generates Epic in **minutes**, formula engine calculates in **seconds** |
| **Estimation Standard** | Gut-feel estimation, large deviation | Standardized templates + unified rates, consistent metrics |
| **Explanation Cost** | "How did 50 person-days come from?" — No one knows | Formula engine calculates step-by-step, **every step is explainable** |
| **Data Management** | Scattered across Excel/email/Smartsheet, hard to trace history | Unified platform, full project lifecycle traceable |

</div>

<div class="grid grid-cols-3 gap-3 mt-6 text-center">
  <div class="bg-red-50 border border-red-200 rounded-lg p-3">
    <div class="text-red-500 text-2xl font-bold">Before</div>
    <div class="text-gray-600 mt-1 text-xs">Black box · Inefficient · Uncontrollable</div>
  </div>
  <div class="text-3xl flex items-center justify-center text-blue-500">→</div>
  <div class="bg-green-50 border border-green-200 rounded-lg p-3">
    <div class="text-green-500 text-2xl font-bold">After</div>
    <div class="text-gray-600 mt-1 text-xs">Transparent · Efficient · Explainable</div>
  </div>
</div>

---

# 🎯 Business Scenario: End-to-End Project Cost Estimation

<div class="mt-2">
  <!-- Flowchart - using items-start to align all boxes at the top -->
  <div class="flex items-start justify-center gap-1 text-sm">
    <div class="px-3 py-2 border border-gray-300 rounded bg-white mt-0">Metadata</div>
    <span class="text-gray-400 text-xs mt-3">····▶</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">Project Creation</div>
    <span class="text-gray-400 mt-3">→</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">BRD Entry</div>
    <span class="text-gray-400 mt-3">→</span>
    <!-- Epic Entry - with connecting line and label -->
    <div class="flex flex-col items-center">
      <div class="px-4 py-2 border-2 border-purple-500 rounded bg-purple-500 text-white font-bold">Epic Entry</div>
      <div class="w-0.5 h-4 border-l-2 border-dashed border-purple-400"></div>
      <div class="flex items-center gap-1">
        <div class="bg-purple-100 text-purple-700 px-3 py-1 rounded-full text-xs font-bold border border-purple-300">🤖 AI Epic Generation</div>
      </div>
    </div>
    <span class="text-gray-400 mt-3">→</span>
    <!-- Effort Estimation - with connecting line and label -->
    <div class="flex flex-col items-center">
      <div class="px-4 py-2 border-2 border-red-400 rounded bg-red-400 text-white font-bold">Effort Estimation</div>
      <div class="w-0.5 h-4 border-l-2 border-dashed border-red-400"></div>
      <div class="bg-red-100 text-red-700 px-3 py-1 rounded-full text-xs font-bold border border-red-300">⚙️ Formula Engine Auto Calculation</div>
    </div>
    <span class="text-gray-400 mt-3">→</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">OGM Estimation</div>
    <span class="text-gray-400 mt-3">→</span>
    <div class="px-3 py-2 border border-gray-300 rounded bg-white">Report Generation</div>
  </div>
</div>

<div style="font-size: 0.65rem;">

| Stage | 📋 Current Approach | 🚀 PET 3.0 | Core Improvement |
| :---: | :--- | :--- | :--- |
| Project Management | SmartSheet multi-platform | Unified platform, one-stop management | Platform unification |
| BRD Entry | Excel manual maintenance | Structured system entry | Data structuring |
| **Epic Entry** | Manual entry one by one | **🤖 AI intelligent generation, PM only needs to review** | **Efficiency improvement** |
| **Effort Estimation** | Gut-feel, Excel manual calculation | **⚙️ Formula engine auto calculation** | **Efficiency improvement, standardization** |
| OGM Estimation | Excel manual entry | Form-based entry, user-friendly experience | Experience improvement |
| Report Generation | Pivot table, simple styling | Real-time generation, visual reports | Real-time visualization |

</div>

---

# 🏗️ Overall Architecture Overview

<div class="grid grid-cols-5 gap-6 items-center mt-6" style="font-size: 0.82rem;">
<div class="col-span-2 flex items-center justify-center">

  <div class="rounded-2xl border-2 border-purple-300 bg-gradient-to-br from-purple-50 to-purple-100/70 p-6 shadow-lg w-full">
    <div class="flex gap-2 text-xl font-bold text-purple-800 mb-4">
      🤖 AI Capabilities
    </div>
    <ul class="space-y-3 text-sm text-gray-700">
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI Requirement Generation</span>: DeepSeek API (JSON Mode), improves Epic generation efficiency</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI Coding</span>: Cursor, Codex improve development efficiency</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI PPT Creation</span>: Cursor + Slidev, improves PPT writing efficiency</span>
      </li>
      <li class="flex items-start gap-2">
        <span class="text-purple-500 mt-0.5">●</span>
        <span><span class="font-semibold text-purple-800">AI Video Editing</span>: Cursor + Remotion, improves video editing efficiency</span>
      </li>
    </ul>
  </div>

</div>
<div class="col-span-3">

### Overall Architecture

<div class="flex flex-col items-center gap-2 mt-2">
  <div class="w-full bg-blue-50 border border-blue-300 rounded-lg p-2">
    <div class="text-blue-700 font-bold text-sm text-center">🖥️ Client</div>
    <div class="text-xs text-gray-600 mt-1 text-center">Form rendering · Result display · Visual reports</div>
  </div>
  <div class="text-blue-400 text-xl">↓</div>
  <div class="w-full bg-amber-50 border border-amber-300 rounded-lg p-2">
    <div class="text-amber-700 font-bold text-sm text-center">⚙️ Server</div>
    <div class="text-xs text-gray-600 mt-1 text-center">Server API · Metadata configuration · Rule engine, etc.</div>
  </div>
  <!-- Two arrows pointing to AI layer and storage layer -->
  <div class="w-full flex justify-around text-amber-400 text-xl">
    <span>↓</span>
    <span>↓</span>
  </div>
  <!-- AI layer and storage layer side by side -->
  <div class="w-full flex gap-2">
    <div class="flex-1 bg-purple-50 border border-purple-300 rounded-lg p-2">
      <div class="text-purple-700 font-bold text-sm text-center">🧠 AI Layer</div>
      <div class="text-xs text-gray-600 mt-1 text-center">DeepSeek API (Epic generation)</div>
    </div>
    <div class="flex-1 bg-green-50 border border-green-300 rounded-lg p-2">
      <div class="text-green-700 font-bold text-sm text-center">💾 Storage Layer</div>
      <div class="text-xs text-gray-600 mt-1 text-center">PostgreSQL (roles/templates/formulas/constants, etc.)</div>
    </div>
  </div>
</div>

</div>
</div>

---

# 🚀 Feature Completion: Implemented Modules Overview


<div class="grid grid-cols-4 gap-3">

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">User Management</div>
  <div class="text-xs text-gray-600 mt-1">
    - Login authentication<br>
    - User CRUD<br>
    - User statistics
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">Metadata Management</div>
  <div class="text-xs text-gray-600 mt-1">
    - Foundation Epic CRUD<br>
    - Core parameter configuration
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">Project Management</div>
  <div class="text-xs text-gray-600 mt-1">
    - Project info CRUD<br>
    - Search/filter/pagination<br>
    - Batch status update
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">BRD & Epic</div>
  <div class="text-xs text-gray-600 mt-1">
    - BRD&Epic CRUD<br>
    - AI Epic generation<br>
    - dashboard
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">Cost Breakdown</div>
  <div class="text-xs text-gray-600 mt-1">
    - Dynamic parameter forms<br>
    - Formula engine parsing<br>
    - CRUD
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">OGM Estimation</div>
  <div class="text-xs text-gray-600 mt-1">
    - Automatic effort aggregation<br>
    - Multi-dimensional statistics<br>
    - CRUD
  </div>
</div>

<div class="border rounded-lg p-3 bg-green-50">
  <div class="text-xl mb-1">✅</div>
  <div class="font-bold text-sm">Budget Reports</div>
  <div class="text-xs text-gray-600 mt-1">
    - Visual charts<br>
    - BRD&EPIC Summary<br>
    - Budget Summary
  </div>
</div>

<div class="border rounded-lg p-3 bg-blue-50">
  <div class="text-xl mb-1">⚙️</div>
  <div class="font-bold text-sm">Technical Foundation</div>
  <div class="text-xs text-gray-600 mt-1">
    - CI/CD automation<br>
    - Database integration<br>
    - Cloud server deployment integration
  </div>
</div>

</div>

<div class="mt-4 text-center">
<span class="bg-blue-100 text-blue-800 px-4 py-2 rounded-full font-bold text-sm">
  7 Major Business Modules + Complete Tech Stack · 100% Functional · Demo Environment Deployed
</span>
</div>

---

# 🎬 Online Website

<div class="mt-10 flex justify-center">
<div class="w-full max-w-4xl rounded-2xl bg-gradient-to-br from-blue-50 to-purple-50/60 ring-1 ring-blue-200 shadow-xl p-8">
<div class="flex items-center justify-center gap-3 mb-6">
<div class="text-5xl leading-none">🚀</div>
<div class="text-3xl font-extrabold tracking-tight text-gray-900">PET 3.0 Online Experience</div>
</div>
<div class="grid grid-cols-2 gap-10 items-start">
<div class="space-y-4">
<div class="text-sm text-gray-600">Online Experience</div>
<a class="block rounded-xl border border-blue-200 bg-white/80 hover:bg-white transition px-5 py-3 font-mono text-base text-blue-700 shadow-sm select-all break-all" href="https://pet30.vercel.app/" target="_blank" rel="noopener noreferrer">https://pet30.vercel.app/</a>
<div class="rounded-xl border border-amber-200 bg-amber-50/70 px-4 py-3 text-sm text-amber-900 leading-snug">
<div class="font-semibold">⚠️ May not be accessible from domestic networks</div>
<div class="text-xs opacity-80 mt-1">Please use VPN / switch network environment and try again</div>
</div>
</div>
<div class="flex flex-col items-center">
<div class="text-sm text-gray-600 mb-3">Scan QR Code</div>
<div class="w-28 h-28 rounded-lg shadow-md overflow-hidden">
<img class="w-full h-full" alt="PET 3.0 Online Demo QR Code" src="./assets/pet30-demo-qr.png" />
</div>
<div class="text-xs text-gray-500 mt-2">Mobile browser opens more smoothly</div>
</div>
</div>
</div>
</div>

<div class="mt-6 text-center text-gray-500 text-sm">💡 Demo environment deployed, welcome to experience the complete feature workflow</div>

---

# 🎥 Feature Demo Video

<div class="flex items-center justify-center h-full">
<div class="text-center">
<div class="text-6xl mb-6">🎬</div>
<div class="text-2xl text-gray-400">Demo Video Area</div>
<div class="text-sm text-gray-400 mt-4">Please insert demo video here</div>
</div>
</div>

---

# 👥 Team Division

<div class="grid grid-cols-3 gap-3 mt-4 text-center">

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👨‍🎨</div>
  <div class="font-bold text-sm">Jeff Bu(卜昌荣)</div>
  <div class="text-xs text-gray-500">Delivery Manager</div>
  <div class="text-xs mt-1 text-purple-600">Cross-department communication/Requirement management/Overall progress control</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👨‍💻</div>
  <div class="font-bold text-sm">Dong Wang(王栋)</div>
  <div class="text-xs text-gray-500">Tech Lead</div>
  <div class="text-xs mt-1 text-purple-600">Architecture design / Cost Breakdown module development</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👩‍💻</div>
  <div class="font-bold text-sm">Maggie Zhu(朱玥)</div>
  <div class="text-xs text-gray-500">Full Stack</div>
  <div class="text-xs mt-1 text-purple-600">Project management, Opex, reports and other module development</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👩‍💻</div>
  <div class="font-bold text-sm">Summer Zhang(张夏倩)</div>
  <div class="text-xs text-gray-500">Scrum Master</div>
  <div class="text-xs mt-1 text-purple-600">Organize meetings, cross-department communication</div>
</div>

<div class="border rounded-lg p-3">
  <div class="text-2xl mb-1">👨‍🎨</div>
  <div class="font-bold text-sm">Groot Zhang(涨潮)</div>
  <div class="text-xs text-gray-500">Technical support</div>
  <div class="text-xs mt-1 text-purple-600">Provide technical support</div>
</div>

</div>

<div class="mt-4 pt-3 border-t border-gray-200">
  <div class="text-center">
    <div class="text-base font-semibold text-purple-600 mb-2">🙏 Special Thanks</div>
    <div class="text-sm text-gray-700">
      <span class="font-medium">Cecilia Guo</span>、<span class="font-medium">Chunyang Liu</span>
    </div>
    <div class="text-xs text-gray-500 mt-1">For professional advice provided to this project</div>
  </div>
</div>

---

# 🙏 Thank You for Listening

<div class="text-center mt-16">

<div class="text-6xl mb-8">🤖 + 📊 = 🚀</div>

<div class="text-2xl font-bold mb-4">Standardize and streamline project estimation with structured data</div>

<div class="text-lg text-gray-500 mb-8">PET 3.0 - Intelligent Project Estimation Platform</div>

<div class="inline-block bg-gradient-to-r from-blue-500 to-purple-500 text-white px-8 py-4 rounded-full text-xl font-bold">
  Q & A Session
</div>

</div>

---

# 🤖 AI Epic Generation Technical Architecture

<div class="grid grid-cols-2 gap-4" style="font-size: 0.65rem;">
<div>

### System Architecture

<div class="flex flex-col items-center gap-2 mt-2">
  <div class="w-full bg-blue-50 border-2 border-blue-400 rounded-lg p-2">
    <div class="text-blue-600 font-bold text-sm">📝 User Input Requirement Description</div>
    <div class="text-xs text-gray-600 mt-1">Select BRD · Input functional requirements · Quick template</div>
  </div>
  <div class="text-blue-400 text-xl">↓</div>
  <div class="w-full bg-purple-50 border-2 border-purple-400 rounded-lg p-2">
    <div class="text-purple-600 font-bold text-sm">🧠 Prompt Engineering</div>
    <div class="text-xs text-gray-600 mt-1">BRD context injection · Structured output constraints · JSON Schema</div>
  </div>
  <div class="text-purple-400 text-xl">↓</div>
  <div class="w-full bg-amber-50 border-2 border-amber-400 rounded-lg p-2">
    <div class="text-amber-600 font-bold text-sm">⚡ DeepSeek Large Model</div>
    <div class="text-xs text-gray-600 mt-1">SiliconFlow API · JSON Mode</div>
  </div>
  <div class="text-amber-400 text-xl">↓</div>
  <div class="w-full bg-green-50 border-2 border-green-400 rounded-lg p-2">
    <div class="text-green-600 font-bold text-sm">📊 Structured Epic Output</div>
    <div class="text-xs text-gray-600 mt-1">5-8 Epics · Priority/features · Batch import</div>
  </div>
</div>

</div>
<div>

### Technical Highlights

🎯 **Structured Prompt Design**
- Inject BRD title, hierarchy, existing Epics as context
- Strict JSON Schema constraints on output format
- Preset generation requirements: title 10-30 chars, description 50-150 chars

🔒 **Output Quality Assurance**
- `response_format: json_object` enforces JSON output
- Server-side secondary validation + type assertion

<div class="text-green-600 font-bold mt-2" style="font-size: 0.95rem;">✅ Generate 5-8 professional Epics in 30 seconds, 10x efficiency improvement</div>

</div>


</div>

---

# 🔬 Cost Breakdown: Data Model Design

<div class="grid grid-cols-2 gap-6" style="font-size: 0.65rem;">
<div>

#### Multi-layer Configuration System

```
Team (团队)
  └── Role (角色)
        └── TaskTemplate (任务模板)
              ├── Parameters[] (参数定义)
              ├── Formula (公式)
              │     └── Constants[] (常量)
              └── category: shared | epic
```

#### Core Table Structure

| Table Name | Purpose |
|------|------|
| `task_templates` | Role task templates, associated with formulas |
| `parameters` | Parameter definitions (type/constraints/default values) |
| `formulas` | Formula expressions + calculation engine |
| `formula_constants` | Configurable constants (editable flag) |
| `epic_estimations` | Estimation results + breakdown |

</div>
<div>

#### Design Highlights

⚙️ **Configuration and Code Separation**
- Adding new task types only requires database configuration, no release needed
- Formulas, constants, parameter constraints can be hot-updated

📝 **Complete Estimation Chain**

```sql
epic_estimations (
  inputs JSONB,      -- User original input
  breakdown JSONB,   -- Calculation process snapshot
  computed_hours,    -- Final result
  created_by,        -- Operator
  created_at         -- Timestamp
)
```

<div class="text-blue-600 font-bold mt-2"  style="font-size: 0.95rem;">💡 Any historical estimation can fully reproduce the calculation process</div>

</div>
</div>

---

# 🔬 Cost Breakdown: Dynamic Formula Engine

<div class="grid grid-cols-2 gap-4" style="font-size: 0.65rem;">
<div>

### Core Architecture

<div class="flex flex-col items-center gap-2 mt-2">
  <div class="w-full bg-blue-50 border-2 border-blue-400 rounded-lg p-2">
    <div class="text-blue-600 font-bold text-sm">📝 User Input Parameter Form</div>
    <div class="text-xs text-gray-600 mt-1">Select Epic, Role, taskTemplate · Input parameters</div>
  </div>
  <div class="text-blue-400 text-xl">↓</div>
  <div class="w-full bg-amber-50 border-2 border-amber-400 rounded-lg p-2">
    <div class="text-amber-600 font-bold text-sm">🔒 InputValidator Parameter Validation Layer</div>
    <div class="text-xs text-gray-600 mt-1">Type validation · Range constraints · Precision control</div>
  </div>
  <div class="text-amber-400 text-xl">↓</div>
  <div class="w-full bg-purple-50 border-2 border-purple-400 rounded-lg p-2">
    <div class="text-purple-600 font-bold text-sm">⚙️ FormulaEngine Formula Parsing Execution Layer</div>
    <div class="text-xs text-gray-600 mt-1">expr-eval parser · Variable injection · Mathematical operations</div>
  </div>
  <div class="text-purple-400 text-xl">↓</div>
  <div class="w-full bg-green-50 border-2 border-green-400 rounded-lg p-2">
    <div class="text-green-600 font-bold text-sm">📊 Breakdown Calculation Process Save</div>
    <div class="text-xs text-gray-600 mt-1">Original formula · Parsed expression · Result snapshot</div>
  </div>
</div>

</div>
<div>

### Technical Highlights

🧮 **Configurable Formula Engine**
- Formulas stored in database, **adjust calculation logic without code changes**
- Supports user input and constant parameter types
- Supports complex expressions

🔒 **Multi-layer Parameter Validation**
- Type conversion + range constraints + step validation + enum matching

📊 **Calculation Process Snapshot Example**

```
{
  "expression": "page_count * base_hours",
  "resolved": "5 * 16",
  "result": 80,
  "unit": "hour"
}
```

<div class="text-green-600 font-bold mt-2">✅ Can precisely restore every calculation step when explaining</div>

</div>
</div>

<!--
Ready to answer:
1. The cost breakdown functionality can also be implemented in Excel, what are the advantages of the web version?
Answer: Collaboration, unified input validation, traceable calculation process, good performance, good maintainability.
2. If it becomes a formal project later, what scale would it be?
Answer: For a formal project, multiple roles need to cooperate (PM, QA, GQE, SE, L2, etc.). If using the existing tech stack and developing on the existing code repository, development workload can be saved. If requirements don't change significantly, an RC project can cover it. If it needs to fully comply with our company's tech stack requirements, frontend and backend need to be rewritten, code cannot be reused, and a small Car-scale project can cover it.
3. What's the difference between AI Epic generation and directly calling the AI interface?
Answer: The core highlight is strong constraint output structure + hierarchical context generation + controllable result import to requirement tree (with database rules as fallback). Fixed schema (fields/enums/quantity/length): The system prompt hardcodes Epic fields (title/description/priority/hours/keyFeatures) and range constraints, making model output naturally more "table-like data" rather than prose. Since we haven't imported real I-picks currently, in the future we can train with real Epics from other projects. When generating I-cards, we can use similarity search to find similar I-cards from other projects, then send them to AI for reference. This way we can generate more accurate I-cards.
Generate guidelines based on existing standards to make it more accurate. Give it good Epics and BRDs, let it learn by itself. And add a conversation mechanism to adjust Epic content based on context.

4. Launch plan and promotion strategy?
-->

