# Antigravity Skills 用户手册

本文档详细介绍了当前工作区中所有可用的 Skill (技能)。这些 Skill 提供了从文档处理、艺术创作到全栈开发和测试的广泛能力。

您可以通过 `@[skill-name]` 或 `/skill-name` 在对话中调用这些技能。

---

## 目录

1. [Algorithmic Art (算法艺术)](#1-algorithmic-art-算法艺术)
2. [Brand Guidelines (品牌指南)](#2-brand-guidelines-品牌指南)
3. [Canvas Design (平面设计)](#3-canvas-design-平面设计)
4. [Doc Co-authoring (文档共创)](#4-doc-co-authoring-文档共创)
5. [DOCX (Word 文档处理)](#5-docx-word-文档处理)
6. [Frontend Design (前段设计)](#6-frontend-design-前端设计)
7. [Internal Comms (内部沟通)](#7-internal-comms-内部沟通)
8. [NotebookLM (知识库问答)](#8-notebooklm-知识库问答)
9. [MCP Builder (MCP 服务构建)](#9-mcp-builder-mcp-服务构建)
10. [PDF (PDF 处理)](#10-pdf-pdf-处理)
11. [PPTX (演示文稿)](#11-pptx-演示文稿)
12. [Skill Creator (技能创建)](#12-skill-creator-技能创建)
13. [Slack GIF Creator (Slack 动图制作)](#13-slack-gif-creator-slack-动图制作)
14. [Theme Factory (主题工厂)](#14-theme-factory-主题工厂)
15. [Web Artifacts Builder (Web 应用构建)](#15-web-artifacts-builder-web-应用构建)
16. [Webapp Testing (Web 应用测试)](#16-webapp-testing-web-应用测试)
17. [XLSX (Excel 表格处理)](#17-xlsx-excel-表格处理)
18. [UI/UX Pro Max (UI/UX 设计智能)](#18-ui-ux-pro-max-ui-ux-设计智能)
19. [Brainstorming (头脑风暴)](#19-brainstorming-头脑风暴)
20. [Dispatching Parallel Agents (并行分发)](#20-dispatching-parallel-agents-并行分发)
21. [Executing Plans (执行计划)](#21-executing-plans-执行计划)
22. [Finishing a Development Branch (分支收尾)](#22-finishing-a-development-branch-分支收尾)
23. [Receiving Code Review (接收审查)](#23-receiving-code-review-接收审查)
24. [Requesting Code Review (请求审查)](#24-requesting-code-review-请求审查)
25. [Subagent Driven Development (子Agent开发)](#25-subagent-driven-development-子agent开发)
26. [Systematic Debugging (系统化调试)](#26-systematic-debugging-系统化调试)
27. [Test Driven Development (测试驱动开发)](#27-test-driven-development-测试驱动开发)
28. [Using Git Worktrees (Git工作树)](#28-using-git-worktrees-git工作树)
29. [Using Superpowers (使用超能力)](#29-using-superpowers-使用超能力)
30. [Verification Before Completion (完成前验证)](#30-verification-before-completion-完成前验证)
31. [Writing Plans (编写计划)](#31-writing-plans-编写计划)
32. [Writing Skills (编写技能)](#32-writing-skills-编写技能)
33. [Planning with Files (文件任务规划)](#33-planning-with-files-文件任务规划)

---

### 1. Algorithmic Art (算法艺术)

**调用方式**: `@[algorithmic-art]` 或 `/algorithmic-art`

**简介**:
专注于基于代码的生成艺术创作。它使用 p5.js 库，通过受控随机性和数学算法创造独特的视觉体验，而非简单复制现有艺术。

**核心能力**:
- **创作算法哲学**: 定义独特的生成艺术美学理念（如"有机湍流"、"量子谐波"）。
- **生成交互式艺术**: 创建包含参数控制、种子导航的 HTML 构件，支持实时探索和变体生成。
- **专业级工艺**: 强调精细的调整、色彩和谐及算法的深度。

**使用案例**:
> **用户**: "请为一个科技会议创作一个名为'数字脉冲'的生成艺术背景，要求体现数据的流动和连接。"
>
> **Skill 响应**:
> 1. 创建 "Digital Pulse" 算法哲学文档，定义视觉规则（粒子流、网络连接、霓虹色彩）。
> 2. 生成交互式 HTML 作品，包含"流动速度"、"连接密度"等可调参数。

---

### 2. Brand Guidelines (品牌指南)

**调用方式**: `@[brand-guidelines]` 或 `/brand-guidelines`

**简介**:
提供 Anthropic 官方品牌视觉识别指南，用于确保生成的文档、演示文稿或设计符合品牌标准。

**核心能力**:
- **色彩规范**: 提供官方配色板（深色背景 #141413，强调色 #d97757 等）。
- **字体规范**: 指导使用 Poppins (标题) 和 Lora (正文) 字体。
- **样式应用**: 将品牌元素应用于各类 Artifact。

**使用案例**:
> **用户**: "帮我美化这个幻灯片，使用 Anthropic 的品牌风格。"
>
> **Skill 响应**:
> 应用官方配色方案（Warm Dark 或 Light 模式），调整字体为 Poppins/Lora，并规范图表颜色。

---

### 3. Canvas Design (平面设计)

**调用方式**: `@[canvas-design]` 或 `/canvas-design`

**简介**:
用于创作高质量的静态视觉设计（海报、艺术图、封面）。强调极简主义、排版设计和视觉哲学。

**核心能力**:
- **设计哲学创作**: 定义视觉语言（如"野兽派喜悦"、"几何静默"）。
- **画布创作**: 生成 PDF 或 PNG 格式的高精度设计作品。
- **字体管理**: 支持加载自定义字体以提升排版质感。

**使用案例**:
> **用户**: "设计一张关于'未来城市'的极简主义海报。"
>
> **Skill 响应**:
> 1. 构思"Concrete Future"设计哲学（强调负空间、粗野主义线条）。
> 2. 生成包含建筑几何图形和精细排版的海报 PDF。

---

### 4. Doc Co-authoring (文档共创)

**调用方式**: `@[doc-coauthoring]` 或 `/doc-coauthoring`

**简介**:
通过结构化的引导流程，协助用户编写高质量文档（如 PRD、设计文档、提案）。

**核心能力**:
- **上下文收集**: 通过针对性提问挖掘用户意图和背景信息。
- **结构化起草**: 分章节进行头脑风暴、筛选和撰写。
- **读者视角测试**: 模拟读者视角审阅文档，发现盲点。

**使用案例**:
> **用户**: "我要写一份新功能的 PRD。"
>
> **Skill 响应**:
> 1. 引导用户回答关于目标用户、核心功能、约束条件的问题。
> 2. 建议 PRD 结构（背景、目标、方案、指标）。
> 3. 逐章协助撰写并完善内容。

---

### 5. DOCX (Word 文档处理)

**调用方式**: `@[docx]` 或 `/docx`

**简介**:
处理 Word 文档的创建、编辑和分析。支持复杂的修订模式（Track Changes）和底层 XML 编辑。

**核心能力**:
- **文档读取**: 提取文本或转换为 Markdown 以进行分析。
- **红线修订 (Redlining)**: 规划并批量实施修订（Track Changes），适合合同或论文修改。
- **OOXML 编辑**: 直接操作底层 XML 以处理复杂格式。
- **新文档创建**: 使用 `docx-js` 从头构建文档。

**使用案例**:
> **用户**: "帮我审阅这份合同 `contract.docx`，将所有的'30天'期限改为'60天'，并开启修订模式。"
>
> **Skill 响应**:
> 1. 读取文档并定位所有"30天"。
> 2. 使用底层脚本批量替换文本并标记 `<w:ins>` (插入) 和 `<w:del>` (删除) 标签。
> 3. 生成带有修订记录的新文档。

---

### 6. Frontend Design (前端设计)

**调用方式**: `@[frontend-design]` 或 `/frontend-design`

**简介**:
构建具有独特美感和生产级质量的前端界面。避免通用的 AI 审美，追求独特的视觉风格。

**核心能力**:
- **美学设计**: 选择独特的主题（如"复古未来主义"、"杂志排版风"）。
- **代码实现**: 生成 React/HTML/CSS 代码，包含细腻的动画和交互。
- **视觉差异化**: 使用非标准字体、独特的布局和配色。

**使用案例**:
> **用户**: "做一个展示新咖啡品牌的落地页。"
>
> **Skill 响应**:
> 设计一个以深棕色和奶油色为主调，配合衬线字体和视差滚动效果的页面，体现高端手工质感。

---

### 7. Internal Comms (内部沟通)

**调用方式**: `@[internal-comms]` 或 `/internal-comms`

**简介**:
撰写符合企业标准的内部沟通稿件，如周报、公告、FAQ 等。

**核心能力**:
- **模板套用**: 包含 3P (Progress, Plans, Problems)、Newsletter 等标准格式。
- **风格适配**: 确保语气专业、清晰且符合公司文化。

**使用案例**:
> **用户**: "写一份关于下周系统维护的内部通知。"
>
> **Skill 响应**:
> 使用标准公告模板，包含时间、影响范围、行动建议和联系方式，语气正式且体贴。

---

### 8. NotebookLM (知识库问答)

**调用方式**: `@[notebooklm]` 或 `/notebooklm`

**简介**:
直接查询 Google NotebookLM 笔记本，获取基于文档的、带有引用来源的确切答案。有效减少幻觉，通过浏览器自动化实现知识库交互。

**核心能力**:
- **知识检索**: 从用户上传的文档源（PDF, 文本等）中提取精准信息。
- **引用溯源**: 提供答案对应的原文引用链接。
- **持久化认证**: 管理浏览器会话，保持登录状态。

**使用案例**:
> **用户**: "根据我们的 RAG 技术白皮书，解释一下检索重排序的策略。"
>
> **Skill 响应**:
> 1. 自动连接到 NotebookLM 中的 "RAG Research" 笔记本。
> 2. 输入查询并获取包含引用的回答。
> 3. 返回："根据白皮书第 12 页，策略 A 优于 B..." [Source 1]

---

### 9. MCP Builder (MCP 服务构建)

**调用方式**: `@[mcp-builder]` 或 `/mcp-builder`

**简介**:
指导用户构建 Model Context Protocol (MCP) 服务器，使 LLM 能够连接外部数据或工具。

**核心能力**:
- **架构规划**: 确定资源 (Resources)、工具 (Tools) 和提示词 (Prompts)。
- **代码脚手架**: 提供 Python (FastMCP) 或 TypeScript SDK 的实现指导。
- **测试与评估**: 生成测试用例以验证 MCP 服务。

**使用案例**:
> **用户**: "我想做一个能查天气数据的 MCP server。"
>
> **Skill 响应**:
> 1. 规划 `get_weather` 工具的输入输出 Schema。
> 2. 提供基于 Python SDK 的完整代码实现。
> 3. 生成用于测试该 Server 的指令。

---

### 10. PDF (PDF 处理)

**调用方式**: `@[pdf]` 或 `/pdf`

**简介**:
全方位的 PDF 处理工具箱，支持读取、生成、合并、拆分和表单填充。

**核心能力**:
- **内容提取**: 提取文本、表格（保留布局）。
- **文件操作**: 合并、拆分、旋转页面。
- **生成 PDF**: 使用 ReportLab 从代码生成复杂 PDF。
- **图像转换**: PDF 转图片或图片转 PDF。

**使用案例**:
> **用户**: "把这三份报告合并成一份，并给每页加个水印。"
>
> **Skill 响应**:
> 1. 使用 `pypdf` 合并文件。
> 2. 创建水印页面并叠加到每一页上。
> 3. 输出最终文件。

---

### 11. PPTX (演示文稿)

**调用方式**: `@[pptx]` 或 `/pptx`

**简介**:
创建和编辑 PowerPoint 演示文稿。支持从大纲生成、模板应用和底层修改。

**核心能力**:
- **HTML 转 PPTX**: 将 HTML/CSS 设计转换为原生 PPTX 幻灯片（支持复杂布局）。
- **模板填充**: 基于现有 PPTX 模板替换文本和图片。
- **OOXML 编辑**: 解包 PPTX 修改底层 XML（如修改母版、深层样式）。

**使用案例**:
> **用户**: "基于这个 Markdown 大纲生成一份 10 页的演示文稿。"
>
> **Skill 响应**:
> 1. 规划每页内容和配图。
> 2. 使用 `html2pptx` 技术栈渲染每一页的布局。
> 3. 生成最终的 .pptx 文件。

---

### 12. Skill Creator (技能创建)

**调用方式**: `@[skill-creator]` 或 `/skill-creator`

**简介**:
指导用户创建高质量的 Antigravity Skill。

**核心能力**:
- **结构初始化**: 创建标准的 `.agent/resources` 和 `.agent/workflows` 结构。
- **最佳实践**: 提供 Workflow 编写指南和设计模式。

**使用案例**:
> **用户**: "我想创建一个自动分析财报的 Skill。"
>
> **Skill 响应**:
> 协助创建 `financial-analyst` skill 目录，规划 `analyze_report.py` 脚本，并编写 workflow 文件。

---

### 13. Slack GIF Creator (Slack 动图制作)

**调用方式**: `@[slack-gif-creator]` 或 `/slack-gif-creator`

**简介**:
制作针对 Slack 优化的动画表情包（GIF）。

**核心能力**:
- **参数优化**: 控制 128x128 尺寸、帧率和色彩数以满足 Slack 限制。
- **动画工具**: 提供 Python 绘图工具（PIL）绘制自定义动画（抖动、旋转、爆炸效果）。

**使用案例**:
> **用户**: "做一个'派对鹦鹉'风格的点头动画 GIF。"
>
> **Skill 响应**:
> 使用 Python 绘制逐帧动画，应用 Slack 优化参数导出 GIF。

---

### 14. Theme Factory (主题工厂)

**调用方式**: `@[theme-factory]` 或 `/theme-factory`

**简介**:
为 Artifacts（如 PPT、文档、网页）应用预设的专业设计主题。

**核心能力**:
- **主题库**: 提供 10+ 种预设主题（如"深海"、"日落"、"极简"）。
- **主题生成**: 根据描述生成新的配色和字体组合。

**使用案例**:
> **用户**: "把这个 PPT 换成'赛博朋克'风格。"
>
> **Skill 响应**:
> 生成包含霓虹色和暗色背景的主题配置，并应用到 PPT 生成流程中。

---

### 15. Web Artifacts Builder (Web 应用构建)

**调用方式**: `@[web-artifacts-builder]` 或 `/web-artifacts-builder`

**简介**:
构建复杂的、多文件的 React Web 应用，支持 Tailwind CSS 和 shadcn/ui。

**核心能力**:
- **项目脚手架**: 初始化包含 Vite, React, Tailwind 的完整项目。
- **组件库集成**: 预装 shadcn/ui 组件。
- **单文件打包**: 将整个应用打包为单个 HTML 文件，方便分享和预览。

**使用案例**:
> **用户**: "做一个带有仪表盘和数据可视化的交互式报表应用。"
>
> **Skill 响应**:
> 1. 初始化 React 项目。
> 2. 使用 shadcn/ui 搭建界面，集成 Recharts 图表。
> 3. 打包为 `dashboard.html` 交付。

---

### 16. Webapp Testing (Web 应用测试)

**调用方式**: `@[webapp-testing]` 或 `/webapp-testing`

**简介**:
使用 Playwright 对本地 Web 应用进行自动化测试和调试。

**核心能力**:
- **自动化测试**: 编写 Python 脚本模拟用户操作（点击、输入）。
- **状态验证**: 截图、检查 DOM 元素、验证网络请求。
- **服务器管理**: 自动启动和管理本地开发服务器。

**使用案例**:
> **用户**: "测试一下我的登录页面，确认输错密码会报错。"
>
> **Skill 响应**:
> 编写 Playwright 脚本，启动本地服务，模拟登录失败流程，并截图验证错误提示。

---

### 17. XLSX (Excel 表格处理)

**调用方式**: `@[xlsx]` 或 `/xlsx`

**简介**:
专业的 Excel 表格处理，支持复杂公式、格式保留和财务模型构建。

**核心能力**:
- **数据分析**: 使用 Pandas 进行数据清洗和统计。
- **模型构建**: 使用 openpyxl 构建带有公式和格式的复杂表格。
- **公式重算**: 使用 LibreOffice 引擎确保公式结果准确更新。
- **财务规范**: 遵循投行标准的格式规范（蓝字输入、黑字公式等）。

**使用案例**:
> **用户**: "帮我做一个 DCF 估值模型，包含 5 年预测和敏感性分析。"
>
> **Skill 响应**:
> 1. 构建假设页和预测页。
> 2. 编写 Excel 公式链接各个单元格（而非硬编码数字）。
> 3. 应用标准的财务模型格式和颜色编码。
> 4. 使用重算脚本验证模型结果。

---

### 18. UI/UX Pro Max (UI/UX 设计智能)

**调用方式**: `@[ui-ux-pro-max]` 或 `/ui-ux-pro-max`

**简介**:
一个强大的 UI/UX 设计智能数据库和搜索引擎，涵盖 50+ 种设计风格、21+ 种配色方案、字体搭配及不同技术栈（React, Vue, Tailwind 等）的最佳实践。

**核心能力**:
- **风格搜索**: 检索特定风格（如 Glassmorphism, Brutalism）的详细特征和实现参数。
- **资产推荐**: 提供针对特定行业（如 Fintech, SaaS）的配色、字体和图表建议。
- **技术栈指南**: 获取特定技术栈（如 HTML-Tailwind, React）的实现规范。

**使用案例**:
> **用户**: "我要为一款医疗 App 设计一个干净、专业的仪表盘。"
>
> **Skill 响应**:
> 1. 搜索 "healthcare" 获取配色（通常为蓝/青色系）和字体推荐。
> 2. 检索 "clean professional" 获取布局和风格建议。
> 3. 提供 Tailwind CSS 的具体实现参数（如阴影、圆角）。

---

### 19. Brainstorming (头脑风暴)

**调用方式**: `@[brainstorming]` 或 `/brainstorming`

**简介**:
在进行任何创造性工作（构建组件、添加功能）之前**必须**使用的 Skill。通过对话澄清用户意图、需求和设计约束。

**核心能力**:
- **需求澄清**: 通过多项选择题或针对性提问，挖掘隐含需求。
- **方案探索**: 在编码前提出 2-3 种不同的实现方案供用户选择。
- **主要原则**: 拒绝盲目编码，"Measure twice, cut once"。

**使用案例**:
> **用户**: "我想给我的 Todo 应用加个 AI 功能。"
>
> **Skill 响应**:
> 1. 询问用户具体场景（是自动生成任务、智能排序还是语音输入？）。
> 2. 提出三种集成方案：本地 LLM、云端 API 或浏览器侧模型。
> 3. 协助用户确定 MVP 范围。

---

### 20. Dispatching Parallel Agents (并行分发)

**调用方式**: `@[dispatching-parallel-agents]` 或 `/dispatching-parallel-agents`

**简介**:
当面临 2 个或更多相互独立、无状态共享的任务时，并行分发 Agent 同时处理。

**使用案例**:
> **用户**: "同时为这个项目的 Python 后端和 React 前端编写 Dockerfile，两者互不依赖。"
>
> **Skill 响应**:
> 1. 启动 Agent A 分析后端 `requirements.txt` 并编写 `Dockerfile`。
> 2. 启动 Agent B 分析前端 `package.json` 并编写 `Dockerfile`。
> 3. 汇总两者的产出并报告完成。

---

### 21. Executing Plans (执行计划)

**调用方式**: `@[executing-plans]` 或 `/executing-plans`

**简介**:
用于执行已编写好的实施计划（Implementation Plan）。它会按步骤引导执行，并在关键节点设置检查点。

**使用案例**:
> **用户**: "开始执行我们刚才制定的 重构数据库层 计划。"
>
> **Skill 响应**:
> 1. 读取 `implementation_plan.md`。
> 2. 提示即将在 Step 1 修改 `db.py`。
> 3. 执行修改并运行验证。
> 4. 询问用户是否继续进行 Step 2。

---

### 22. Finishing a Development Branch (分支收尾)

**调用方式**: `@[finishing-a-development-branch]` 或 `/finishing-a-development-branch`

**简介**:
当功能开发完成并通过测试后，引导用户进行分支收尾工作。提供合并策略、PR 描述生成以及分支清理建议。

**使用案例**:
> **用户**: "功能开发完了，测试也都过了，准备合并。"
>
> **Skill 响应**:
> 1. 检查是否存在未提交的更改。
> 2. 推荐 Squash Merge 策略以保持主分支整洁。
> 3. 生成包含主要变更点的 PR 描述草稿。
> 4. 提示删除本地和远程的 `feature/login` 分支。

---

### 23. Receiving Code Review (接收审查)

**调用方式**: `@[receiving-code-review]` 或 `/receiving-code-review`

**简介**:
辅助用户处理收到的代码审查反馈。它不仅仅是"照做"，而是会对反馈进行技术评估，指出不合理的建议，或对模糊反馈寻求澄清。

**使用案例**:
> **用户**: "同事 review 说这个函数太长需要拆分，但拆分会破坏上下文，帮我处理这个反馈。"
>
> **Skill 响应**:
> 1. 分析代码和反馈。
> 2. 建议回复：解释拆分可能带来的副作用，并提出替代方案（如添加详细注释或使用折叠区域）。
> 3. 或者是：承认反馈合理，并演示如何安全地提取子函数。

---

### 24. Requesting Code Review (请求审查)

**调用方式**: `@[requesting-code-review]` 或 `/requesting-code-review`

**简介**:
在提交代码前进行自我审查。检查代码是否符合要求、测试是否通过、文档是否更新，生成高质量的 PR 描述或审查请求。

**使用案例**:
> **用户**: "我要提交代码了，帮我做最后检查。"
>
> **Skill 响应**:
> 1. 运行 lint 和测试套件。
> 2. 发现 `README.md` 未更新新得配置项，提示用户。
> 3. 生成一份包含"变更摘要"和"测试覆盖率"的审查请求文本。

---

### 25. Subagent Driven Development (子Agent开发)

**调用方式**: `@[subagent-driven-development]` 或 `/subagent-driven-development`

**简介**:
将复杂的实施计划拆分为独立子任务，并利用子 Agent (Browser Subagent 等) 独立执行，保持主会话上下文清晰。

**使用案例**:
> **用户**: "按照计划，现在需要去 Ant Design 官网查一下 Table 组件的最新 API，然后更新我们的组件。"
>
> **Skill 响应**:
> 1. 启动 Browser Subagent 访问官网查找 Table API。
> 2. 将查到的 API 变更（如 `columns` 属性的变化）返回给主 Agent。
> 3. 主 Agent 根据信息修改本地代码。

---

### 26. Systematic Debugging (系统化调试)

**调用方式**: `@[systematic-debugging]` 或 `/systematic-debugging`

**简介**:
**Antigravity 核心调试方法论**。严禁猜测式修复。
1. **根因分析**: 必须先找到 Root Cause。
2. **模式分析**: 对比正常工作的类似代码。
3. **假设验证**: 提出假设 -> 最小化测试 -> 验证。
4. **修复实施**: 仅在确认根因后实施修复。

**使用案例**:
> **用户**: "生产环境的 API 偶尔报 502 错误，不知道为啥。"
>
> **Skill 响应**:
> 1. **拒绝**直接尝试重启或修改配置。
> 2. 指导用户收集日志（Phase 1: 证据收集）。
> 3. 发现错误集中在特定时间段，提出"数据库连接池耗尽"的假设（Phase 3: 假设）。
> 4. 编写脚本验证连接数峰值，确认后再调整连接池参数（Phase 4: 修复）。

---

### 27. Test Driven Development (测试驱动开发)

**调用方式**: `@[test-driven-development]` 或 `/test-driven-development`

**简介**:
**Antigravity 核心开发模式**。
1. **Red**: 编写一个失败的测试（Reproduction script 或 Unit test）。
2. **Green**: 编写最少量的代码让测试通过。
3. **Refactor**: 优化代码结构。

**使用案例**:
> **用户**: "帮我写一个解析这种特殊日期格式的函数。"
>
> **Skill 响应**:
> 1. 创建 `test_date_parser.py`，包含通过和失败的测试用例（Red）。
> 2. 编写简单的正则解析逻辑，确保测试通过（Green）。
> 3. 优化正则性能并处理边界情况（Refactor）。

---

### 28. Using Git Worktrees (Git工作树)

**调用方式**: `@[using-git-worktrees]` 或 `/using-git-worktrees`

**简介**:
在不干扰当前工作区（Checkout）的情况下，创建隔离的 Git Worktree 进行新功能开发或 Bug 修复。

**使用案例**:
> **用户**: "我现在正开发到一半，但线上有个急 Bug 要修，不想 stash 现在的修改。"
>
> **Skill 响应**:
> 1. 使用 `git worktree add ../hotfix-branch` 创建新目录。
> 2. 在新目录中修复 Bug 并提交。
> 3. 删除 Worktree，回到原目录继续开发。

---

### 29. Using Superpowers (使用超能力)

**调用方式**: `@[using-superpowers]` 或 `/using-superpowers`

**简介**:
Meta-Skill。用于在对话开始时，帮助用户发现有哪些 Skill 可用，以及如何正确使用它们。引导用户"先思考 Skill，再动手"。

**使用案例**:
> **用户**: "我想做一个 PPT，用什么工具好？"
>
> **Skill 响应**:
> 推荐使用 `@[pptx]` 生成结构，并结合 `@[theme-factory]` 应用设计主题，或者如果需要带品牌标识，使用 `@[brand-guidelines]`。

---

### 30. Verification Before Completion (完成前验证)

**调用方式**: `@[verification-before-completion]` 或 `/verification-before-completion`

**简介**:
在宣称"任务完成"之前的最后一道防线。强制运行验证命令（测试、构建、Lint），并要求提供实质性的成功证据（日志、截图）。

**使用案例**:
> **用户**: "我觉得这个 Bug 修好了。"
>
> **Skill 响应**:
> 1. 运行重现脚本，确认输出为 Success。
> 2. 运行全套测试套件，确保无回归。
> 3. 只有当看到绿色对勾时，才回复用户任务已完成。

---

### 31. Writing Plans (编写计划)

**调用方式**: `@[writing-plans]` 或 `/writing-plans`

**简介**:
在接触任何代码之前，先编写详细的实施计划（Implementation Plan）。包含：目标描述、用户审查点、详细变更列表、验证计划。

**使用案例**:
> **用户**: "我们要把数据库从 SQLite 迁移到 MySQL。"
>
> **Skill 响应**:
> 1. 创建 `implementation_plan.md`。
> 2. 规划步骤：Schema 导出、数据迁移脚本、应用配置修改。
> 3. 列出每个步骤涉及的具体文件和验证方式（如数据一致性校验）。
> 4. 等待用户确认计划后才开始执行。

---

### 32. Writing Skills (编写技能)

**调用方式**: `@[writing-skills]` 或 `/writing-skills`

**简介**:
辅助编写新的 Skill 或修改现有 Skill。提供 Antigravity Skill 的最佳实践、模板和测试方法。

**使用案例**:
> **用户**: "我想写一个新的 Skill，用来自动优化 SQL 查询。"
>
> **Skill 响应**:
> 1. 规划 Skill 结构（Workflow + Python Script）。
> 2. 编写 `explain_analyzer.py` 脚本。
> 3. 创建 `.agent/workflows/sql-optimizer.md`，定义触发条件和参数输入。

---

### 33. Planning with Files (文件任务规划)

**调用方式**: `@[planning-with-files]` 或 `/planning-with-files`

**简介**:
实现类似 Manus 的任务规划模式。利用 `task_plan.md`, `findings.md`, `progress.md` 三个持久化文件，作为复杂任务的"磁盘记忆"，避免 Context Window 限制。

**核心能力**:
- **持久化记忆**: 将关键决策、发现和进度写入文件，而非留在对话历史中。
- **任务分阶段**: 强制将复杂任务拆解为 Phase，并逐一标记完成。
- **错误学习**: 在 plan 文件中记录遇到的错误和尝试过的修复方案，避免重蹈覆辙。

**使用案例**:
> **用户**: "我要研究一下怎么把我们的 Django 项目迁移到 FastAPI，这可能涉及到很多文件的改动和调研。"
>
> **Skill 响应**:
> 1. 初始化 `task_plan.md`（定义调研、原型、迁移、测试四个阶段）。
> 2. 初始化 `findings.md`（用于记录 Django 和 FastAPI 的 API 差异）。
> 3. 初始化 `progress.md`（记录操作日志）。
> 4. 在调研过程中，不断将发现写入 `findings.md`，而非仅仅在对话中回复。



