# Antigravity Skills

基于自然语言创建符合Antigravity规范的rule或workflow，快速扩展Agent能力，汇集了多个强大的自动化技能（Skills），涵盖文档处理、创意设计、全栈开发及工作流辅助等领域。

## 📂 目录结构

```
.
├── .agent/                 # Antigravity Agent 核心目录
│   ├── workflows/          # Skill 工作流定义 (.md)
│   └── resources/          # Skill 依赖资源 (脚本、模板、文档)
├── skill-guide/            # 用户手册目录
│   └── Antigravity_Skills_Manual_CN.md  # 中文使用手册
```

## 📖 快速开始
1. 将`.agent/`目录复制到你的工作区：
```bash
cp -r .agent/ /path/to/your/workspace/
```
2. **调用 Skill**: 在对话框输入 `@` 或 `/` 即可唤起技能列表。
3. **查看手册**: 详细的使用案例和参数说明请查阅 [skill-guide/Antigravity_Skills_Manual_CN.md](skill-guide/Antigravity_Skills_Manual_CN.md)。
4. **环境依赖**: 部分 Skill (如 PDF, XLSX) 依赖 Python 环境，请确保 `.venv` 处于激活状态或系统已安装相应库。


## 🚀 已集成的 Skills
- Skills数量：33个
- Skills调用方式：`@[skill-name]` 或 `/skill-name`
- Skills来源
  - https://github.com/anthropics/skills
  - https://github.com/nextlevelbuilder/ui-ux-pro-max-skill
  - https://github.com/obra/superpowers
  - https://github.com/OthmanAdi/planning-with-files

### 📄 文档与办公
- **`@[pdf]`**: PDF 读取、合并、拆分及生成
- **`@[docx]`**: Word 文档创建、红线修订与分析
- **`@[pptx]`**: PowerPoint 演示文稿生成与编辑
- **`@[xlsx]`**: Excel 表格处理、公式计算与财务模型
- **`@[doc-coauthoring]`**: 交互式文档编写助手
- **`@[internal-comms]`**: 企业内部沟通稿件生成

### 🧠 核心思维与规划
- **`@[brainstorming]`**: 创意生成与需求澄清，在编码前明确意图
- **`@[planning-with-files]`**: Manus 风格的文件任务规划（task_plan.md, findings.md）
- **`@[writing-plans]`**: 编写详细的实施计划
- **`@[executing-plans]`**: 执行已有的实施计划
- **`@[using-superpowers]`**: 引导如何查找和使用最佳 Skill

### ⚙️ 开发全流程
- **`@[test-driven-development]`**: TDD 开发模式，先写测试再写代码
- **`@[systematic-debugging]`**: 系统化调试方法论，根因分析优先
- **`@[verification-before-completion]`**: 任务完成前的严格自我验证
- **`@[finishing-a-development-branch]`**: 开发分支收尾工作（合并、清理）

### 🤝 代码协作与审查
- **`@[requesting-code-review]`**: 发起代码审查请求，检查清单
- **`@[receiving-code-review]`**: 处理代码审查反馈，批判性思考
- **`@[using-git-worktrees]`**: 使用 Git Worktree 进行环境隔离

### 🤖 高级 Agent 能力
- **`@[subagent-driven-development]`**: 子 Agent 驱动开发，处理拆分的独立任务
- **`@[dispatching-parallel-agents]`**: 并行分发 Agent 处理多任务
- **`@[writing-skills]`**: 辅助编写或测试新的 Skill

### 🎨 设计与创意
- **`@[canvas-design]`**: 极简主义平面设计 (海报/封面)
- **`@[algorithmic-art]`**: 基于 p5.js 的算法生成艺术
- **`@[slack-gif-creator]`**: Slack 专用动态表情包制作
- **`@[theme-factory]`**: 文档与演示文稿的主题配色工厂
- **`@[brand-guidelines]`**: Anthropic 品牌视觉规范指南
- **`@[ui-ux-pro-max]`**: 全面的 UI/UX 设计智能库 (风格、配色、字体与技术栈指南)

### 💻 开发与构建
- **`@[frontend-design]`**: 高品质前端 UI 设计与代码实现
- **`@[web-artifacts-builder]`**: React + Tailwind + Shadcn/ui 应用构建器
- **`@[webapp-testing]`**: 基于 Playwright 的 Web 应用自动化测试
- **`@[mcp-builder]`**: Model Context Protocol 服务构建向导

### 🛠️ 扩展工具
- **`@[skill-creator]`**: Antigravity Skill 创建向导
- **`@[skill-migrator]`**: 旧版 Claude Code Skill 迁移工具
