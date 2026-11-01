# Jack Wang｜Agent 与 AI 应用开发

**AI Agent Engineer · Applied AI Developer · 企业 AI 应用解决方案**

## 让 AI 真正进入企业业务流程

聚焦企业 AI 应用场景，从业务需求诊断、Agent 方案设计到应用开发与工程验证，帮助企业探索可落地、可评估的 AI 解决方案。

## 我能解决什么问题

诊断企业场景与需求，设计 Agent 应用原型，结合业务规则、模型与人工流程，并以自动化测试、评估指标和验证边界检验可行性。

## 代表项目

### 01 · CreditPilot

**合成信用风险分析与解释演示**

**业务问题：** 信用风险应用需要将数据、规则、评分、策略决策和解释组织为可复核的工程链路。

**项目实现：** 基于 Python、FastAPI 和确定性模拟工具链，使用合成客户数据完成风险评分、策略决策、双阶段证据校验，并提供 REST API、Web UI 和结构化输出。

**工程验证：** 137 项自动化测试通过，Ruff 与 GitHub Actions CI 通过；已按 Apache-2.0 发布 v0.1.0。

**验证边界：** 仅使用合成数据，不用于真实信贷决策；未接入 LLM、RAG 或真实银行系统。

[查看 CreditPilot](https://github.com/wangluqing/CreditPilot) · [Release v0.1.0](https://github.com/wangluqing/CreditPilot/releases/tag/v0.1.0)

### 02 · AgentTaskPilot

**企业 AI Agent 需求诊断与任务规划**

**业务问题：** 企业 AI 应用需求通常模糊，缺乏清晰的任务流程、约束条件和可评估指标。

**项目实现：** 将业务需求转化为结构化诊断、任务流程、风险清单和评估指标，支持 Mock 与 DeepSeek BYOK。

**工程验证：** 已完成本地自动化测试、GitHub CI 和 Mock 浏览器验收。

**验证边界：** 当前验证不代表真实 DeepSeek API 已完成生产环境验证。

[查看 AgentTaskPilot](https://github.com/wangluqing/agent-task-pilot)

### 03 · ServicePilot

**AI 客服工单智能分析与人工复核**

**业务问题：** 客服工单需要进行分类、订单核验、风险识别和人工处理决策。

**项目实现：** 基于 FastAPI、Python 业务规则与可选 DeepSeek LLM，实现结构化工单分析、模拟订单核验、安全规则、失败降级和人工复核提示。

**工程验证：** 公开版 51 条离线自动化测试通过，提供可运行的 FastAPI 服务与真实 Web 界面截图。

**验证边界：** 使用模拟订单数据，支持可选 LLM 接入；当前为 Portfolio Demo，尚未完成生产环境部署验证。

[查看 ServicePilot](https://github.com/wangluqing/service-pilot)

## 关于我

我长期从事数据分析、机器学习与 Python/R 应用实践，目前聚焦 Agent 与 AI 应用工程。数据科学背景帮助我理解数据、模型与评估，工程实践帮助我将方案转化为边界清晰、可验证的应用。

## 技术能力

- **AI 应用：** DeepSeek API、Agent、RAG、Prompt 设计、模型评估
- **后端开发：** Python、FastAPI、Pydantic、Streamlit、REST API
- **质量工程：** pytest、Mock 测试、GitHub Actions、CI、uv
- **数据分析：** Python、R、机器学习、特征工程

## 我的工作方法

**业务问题 → 方案设计 → MVP → 评估 → 交付**

先明确目标、用户与约束，再验证关键假设；以测试和评估数据判断效果，补齐文档、质量保障与交付边界。

## 正在探索

**Enterprise RAG Agent｜企业知识库检索与智能问答**

**规划中：** 面向企业制度、业务文档和知识问答场景，探索 RAG 检索、引用溯源、质量评估与业务系统集成。

## 合作方向

- 企业 AI 场景识别与需求诊断
- Agent 应用原型开发与工程验证
- 企业知识库、客服工单及业务流程 AI 化探索
- AI 应用与数据分析技术培训

如果你正在评估企业 AI 应用场景，或需要 Agent 原型开发、技术验证与培训支持，欢迎通过邮件联系，交流具体业务问题。

## 联系方式

欢迎交流 AI Agent 应用开发、企业 AI 解决方案、技术培训及商务合作。

**联系邮箱：** [wangluqing360@163.com](mailto:wangluqing360@163.com)

也欢迎通过 GitHub 项目 Issues 交流技术问题。
