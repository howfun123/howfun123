## AI应用开发工程师 👋

## Hi there, I'm 李楚凡👋

### 🧠 LLM Application Engineer | Java Backend Expert

> 专注大模型应用落地与工程化，擅长用 **Multi-Agent 架构** 解决复杂内容审核业务问题。  
> 从 Java 高并发后端到 AI Infra，坚信模型是大脑，工程是血肉 —— 用确定性驾驭创造性。

- 🔭 **当前聚焦**: 基于 Multi-Agent 与 ReAct 的智能审核编排平台，探索 Workflow + SFT 在风控场景的最佳实践  
- 🌱 **技术栈**: Java / Python 双语言驱动，Spring Boot + LangChain 深度整合大模型与企业级后端  
- 💡 **核心理念**: 不做只会调 API 的“模型使用者”，要做懂业务、能落地、可量化的 AI 应用建设者  
- 📫 **联系方式**: 420506712@11.com

---

### 🛠️ 技术栈

**Languages & Frameworks**  
`Java` `Spring Boot` `Python` `LangChain` `LangGraph` `MyBatis-Plus`

**LLM & Agent**  
`Prompt Engineering` `ReAct` `Plan-and-Execute` `SFT` `LLaMA-Factory` `OpenAI API`

**Data & Infra**  
`MySQL` `Redis` `Kafka` `Docker` `Elasticsearch` `Prometheus+Grafana`

---

### 📌 精选项目

#### 1. [moderation-agent-hub] 智能内容审核 Agent 平台
> 基于 Multi-Agent 与 ReAct 框架的自动化审核解决方案，专攻黑话、谐音、隐晦广告等复杂场景。

- 🧩 **架构**: 路由 Agent 负责意图分发，谩骂/广告/低俗等专家 Agent 各司其职，支持工具调用（敏感词库、OCR）
- ⚙️ **工作流**: LangGraph 驱动审核全生命周期（待审→自动判定→人工复核→结单），状态可追溯
- 📊 **效果**: 将某类审核场景的人力成本降低 **40%**，召回率提升至 **92%**，审核延迟下降 **35%**
- 🛠️ **技术亮点**: 结构化 Prompt + Few-shot 对抗阴阳怪气；Java 网关负责高并发流量分发与结果落地

#### 2. [sft-data-pipeline] 大模型训练数据工厂
> 从业务日志到 SFT 样本的端到端管线，支撑模型在垂直审核场景的专项微调。

- 🔁 **流程**: 审核日志 → Java 高性能清洗/脱敏 → Python 指令转化与增强 → 质量评估 → 导出训练格式
- 🧪 **实验**: 基于 Qwen-7B 微调涉政敏感词识别，F1-Score 从 **0.71 提升至 0.86**
- 🧰 **工具链**: LLaMA-Factory + Axolotl，完整记录数据版本与实验配置

#### 3. [ai-gateway] 高性能 AI 网关与可观测平台
> 统一模型接入网关，解决多模型路由、成本控制与全链路审计的生产级问题。

- 🚦 **特性**: 多厂商适配（GPT/Claude/GLM）、负载均衡、熔断降级、自动重试
- 💰 **成本**: 精确到调用方的 Token 计量与预算预警，异常调用实时告警
- 📈 **可观测**: 基于 Prometheus + Grafana 的调用量、延迟、错误率大盘，支持 Prompt 链路追踪
- 🛠️ **技术栈**: Spring Boot + Redis + Kafka + Docker

---

### 📊 GitHub 统计

![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=howfun123&show_icons=true&theme=radical)

---
