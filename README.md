# Agent Trending

Agent Trending 是一个面向 AI Agent 领域的大规模论文研究与趋势分析开源项目。

- **数据规模：** 借助 Codex 对 2025.01—2026.03 期间 **8701 篇** AI Agent 学术论文进行系统化采集、去重、分类与结构化标注，构建了目前该领域覆盖最完整的开源论文数据集之一。相关月度整理见 [monthly-reports/](./monthly-reports/)。
- **研究框架：** 围绕 **15 个核心方向**建立分类体系，涵盖应用系统、安全与对齐、架构与框架、评测基准、多 Agent 协作、多 Agent 强化学习、学习与自进化、仿真与社会模拟、人机协作、记忆与知识管理、规划与推理、具身智能、工具使用与环境交互、可解释性与透明度、低代码 / 无代码平台。对应方向论文集见 [topic-papers/](./topic-papers/)。
- **趋势分析：** 对每个方向完成技术演进脉络梳理、代表性论文提炼与最佳实践总结，输出 **15 份细分方向技术趋势报告**，识别出强化学习驱动的能力获取、分层闭环架构收敛、Agent 通信协议生态爆发、安全性系统升级等跨领域共振信号。对应报告见 [topic-reports/](./topic-reports/)。
- **研判结论：** 基于 15 份子报告完成跨方向交叉分析，产出 **1 份 [AI Agent 全局技术趋势深度总报告](./deep-report.md)**，覆盖技术栈分层、路线之争、商业化路径、共性瓶颈与预测；同时形成 **1 份 [下一代 Agent 原型设计文档](./next-gen-agent-vision.md)**，提出三进程分离架构、分级自主决策、结构化记忆管理等可工程化方案。

**适合谁读**

| 角色 | 你能获得什么 |
| :--- | :--- |
| **AI 研究者** | 15 个子领域的技术前沿、关键分化方向与最有价值的开放问题。 |
| **工程师 / 技术负责人** | 经过交叉验证的架构选型建议、技术路线判断与落地优先级排序。 |
| **产品经理 / 投资人** | 各场景的真实技术成熟度、商业化节奏与关键机会窗口。 |
| **AutoResearch 这类自主研究 Agent** | 可直接把本仓库作为研究上下文与方向地图，用于自动生成选题、组织实验假设、筛选重点论文、跟踪技术演进，并据此持续推进研究任务。 |
| **OpenClaw 这类任务执行型 Agent** | 可将本仓库作为长期知识底座，用于理解 AI Agent 领域结构、调用细分方向报告回答问题、辅助检索资料，并支持持续性的研究与分析工作流。 |

## 快速开始

- [全局报告](#global-report)
- [细分方向总览](#topic-overview)
- [月度索引](#monthly-index)

---

<a id="global-report"></a>

## 📖 全局报告

### [AI Agent 全局技术趋势报告（2025.01—2026.03）](./deep-report.md)

### [下一代 Agent 原型设计文档](./next-gen-agent-vision.md)

> 基于 **15 个细分方向、8701 篇学术论文**的跨领域深度分析报告。

#### 这份报告是什么

过去 15 个月（2025.01—2026.03），AI Agent 领域经历了一次历史性的范畴跃迁，从"更聪明的聊天机器人"变成了"能在真实世界执行复杂任务的自主系统"。我们系统性地追踪了这一过程中 7700+ 篇学术论文的演进脉络，覆盖了从基础训练、认知架构、工具使用、多智能体协作到安全对齐、商业落地的完整技术栈，最终凝练为这份全景式趋势报告。

#### 为什么做这件事

Agent 领域的论文月产出在一年间从约 200 篇飙升至 700+ 篇，信息过载让从业者很难建立全局认知。我们希望通过这份开源报告，帮助研究者快速定位高价值研究方向，帮助工程团队做出更有依据的技术选型，帮助商业决策者理解真实的技术成熟度而非营销叙事。

#### 报告核心发现

报告识别出 **八大跨领域共振趋势**：

1. 强化学习全面取代监督微调，成为 Agent 能力获取的核心引擎
2. 分层闭环架构成为系统设计的事实标准
3. MCP / A2A 等通信协议催生"Agent 互联网"基础设施雏形
4. 安全性从附加特性升级为系统生存前提
5. 记忆与认知能力成为 Agent 从工具进化为助手的分水岭
6. 软件工程成为全领域的首要验证场景
7. 评测范式从结果打分转向过程审计
8. 物理世界与数字世界 Agent 加速融合

报告同时给出了商业化冲击波排序、五大共性瓶颈分析，以及面向研究者、技术团队和投资者的差异化战略建议。

<a id="topic-overview"></a>

## 📊 细分方向总览

下表汇总了 15 个细分方向的论文集、技术趋势报告，以及从各方向执行摘要中提炼出的核心趋势、面临挑战与未来推演。

<table>
  <thead>
    <tr>
      <th>细分方向</th>
      <th align="center">论文数</th>
      <th>报告</th>
      <th>核心趋势</th>
      <th>面临挑战</th>
      <th>未来推演</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>基于 Agent 的应用系统</strong></td>
      <td align="center"><a href="./topic-papers/1.%20基于Agent的应用系统.md">1598</a></td>
      <td><a href="./topic-reports/1.%20基于Agent的应用系统-技术趋势报告.md">查看</a></td>
      <td>SWE 向仓库级修复演进，AI 科学家、医疗、网络安全、金融等端到端 Agent 系统快速成熟。</td>
      <td>长程推理中的幻觉累积、动态评估基准不足、领域隐性知识对齐成本高。</td>
      <td>自动化代码修复、仓库级重构与企业数据分析 Agent 将率先规模化部署。</td>
    </tr>
    <tr>
      <td><strong>Agent 安全与对齐</strong></td>
      <td align="center"><a href="./topic-papers/2.%20Agent安全与对齐.md">1008</a></td>
      <td><a href="./topic-reports/2.%20Agent安全与对齐-技术趋势报告.md">查看</a></td>
      <td>风险从模型输出扩展到多 Agent 共谋、协议层攻击、记忆投毒与具身安全，防御转向运行时治理。</td>
      <td>动态非确定性行为与静态授权模型错位，低延迟高可靠运行时监管仍不成熟。</td>
      <td>企业受控多 Agent 系统将先落地，Agent 防火墙与面向 Agent 的 IAM 将成为新基建。</td>
    </tr>
    <tr>
      <td><strong>Agent 架构与框架设计</strong></td>
      <td align="center"><a href="./topic-papers/3.%20Agent架构与框架设计.md">915</a></td>
      <td><a href="./topic-reports/3.%20Agent架构与框架设计-技术趋势报告.md">查看</a></td>
      <td>架构从单体 LLM 转向多 Agent 微服务、Agentic OS、端边云协同和神经符号闭环验证。</td>
      <td>KV Cache 内存墙、长程任务错误级联、跨平台身份与鉴权基础设施缺失。</td>
      <td>跨应用 GUI 自动化和高信噪比 Deep Research 助手会更快进入商业落地。</td>
    </tr>
    <tr>
      <td><strong>Agent 评测与基准</strong></td>
      <td align="center"><a href="./topic-papers/4.%20Agent评测与基准.md">811</a></td>
      <td><a href="./topic-reports/4.%20Agent评测与基准-技术趋势报告.md">查看</a></td>
      <td>评测从静态结果转向动态过程感知，Agent-as-a-Judge、SWE/Web/GUI 端到端基准快速成为主流。</td>
      <td>数据污染、长程任务错误传播，以及缺乏衡量生产级资源消耗和经济价值的统一指标。</td>
      <td>企业自动化工作流与代码库维护场景会率先形成高价值评测基准与落地需求。</td>
    </tr>
    <tr>
      <td><strong>多 Agent 协作与通信</strong></td>
      <td align="center"><a href="./topic-papers/5.%20多Agent协作与通信.md">805</a></td>
      <td><a href="./topic-reports/5.%20多Agent协作与通信-技术趋势报告.md">查看</a></td>
      <td>通信从自然语言转向机器原生语义，拓扑动态化，无共识辩论与 Agent Internet 生态成型。</td>
      <td>缺乏标准化跨平台代理协议，多 Agent 推理成本和延迟居高不下。</td>
      <td>软件工程自动修复与多机器人协作最可能率先跑通规模化部署。</td>
    </tr>
    <tr>
      <td><strong>多 Agent 强化学习</strong></td>
      <td align="center"><a href="./topic-papers/6.%20多Agent强化学习.md">750</a></td>
      <td><a href="./topic-reports/6.%20多Agent强化学习-技术趋势报告.md">查看</a></td>
      <td>LLM/VLM 开始充当世界模拟器与高级教练，离线 MARL、安全约束与异构协同加速融合。</td>
      <td>稀疏奖励下的信用分配、环境非平稳性与 Sim-to-Real 泛化鸿沟仍是核心障碍。</td>
      <td>基于大模型指导的多车多机协同控制，将先在无人机物流和仓储环境突破。</td>
    </tr>
    <tr>
      <td><strong>Agent 学习与自进化</strong></td>
      <td align="center"><a href="./topic-papers/7.%20Agent学习与自进化.md">611</a></td>
      <td><a href="./topic-reports/7.%20Agent学习与自进化-技术趋势报告.md">查看</a></td>
      <td>RLVR/PRM、测试时计算、自博弈、GUI/Web 接管与多 Agent 自组织演化成为主线。</td>
      <td>长周期任务信用分配困难，高质量可验证环境构建成本高。</td>
      <td>原生代码开发、代码库维护和跨平台 GUI 自动化最可能率先形成商业闭环。</td>
    </tr>
    <tr>
      <td><strong>Agent 仿真与社会模拟</strong></td>
      <td align="center"><a href="./topic-papers/8.%20Agent仿真与社会模拟.md">428</a></td>
      <td><a href="./topic-reports/8.%20Agent仿真与社会模拟-技术趋势报告.md">查看</a></td>
      <td>仿真规模分布式扩张，LLM+ABM/PDE 混合范式确立，原生 AI 社会与行为机制白盒化成为热点。</td>
      <td>行为验证危机与大规模多轮交互带来的高昂 Token 成本限制商业化。</td>
      <td>合成用户池驱动的 Web 与产品 A/B 测试最可能先形成工具化落地。</td>
    </tr>
    <tr>
      <td><strong>人机协作 Agent</strong></td>
      <td align="center"><a href="./topic-papers/9.%20人机协作Agent.md">377</a></td>
      <td><a href="./topic-reports/9.%20人机协作Agent-技术趋势报告.md">查看</a></td>
      <td>Agent 从被动响应走向主动干预，引入 ToM、动态多层编排与精细化控制权设计。</td>
      <td>动态交互评估标准缺失，以及人类在长期协作中的认知去技能化风险。</td>
      <td>企业级复杂 SWE 协作与专业数据/文档联合创编会更早商业化。</td>
    </tr>
    <tr>
      <td><strong>Agent 记忆与知识管理</strong></td>
      <td align="center"><a href="./topic-papers/10.%20Agent记忆与知识管理.md">343</a></td>
      <td><a href="./topic-reports/10.%20Agent记忆与知识管理-技术趋势报告.md">查看</a></td>
      <td>记忆图谱化、RL 驱动读写、多模态长期记忆、分布式共享记忆和生物学启发遗忘成为核心方向。</td>
      <td>上下文膨胀导致推理成本和幻觉上升，异构记忆架构缺少动态评估，尾延迟难保障。</td>
      <td>长程 GUI 自动化助理和轻量级个性化对话系统有望更早突破。</td>
    </tr>
    <tr>
      <td><strong>Agent 规划与推理</strong></td>
      <td align="center"><a href="./topic-papers/11.%20Agent规划与推理.md">335</a></td>
      <td><a href="./topic-reports/11.%20Agent规划与推理-技术趋势报告.md">查看</a></td>
      <td>从 ReAct 走向结构化规划，测试时计算扩展、深度搜索 Agent 和可靠性治理成为主旋律。</td>
      <td>幻觉、过度推理、上下文漂移等失败模式，要求更强的验证、回溯与边界感知机制。</td>
      <td>深度研究 Agent 和智能规划系统将在未来 12 个月进入早期商业化。</td>
    </tr>
    <tr>
      <td><strong>具身智能 Agent</strong></td>
      <td align="center"><a href="./topic-papers/12.%20具身智能Agent.md">324</a></td>
      <td><a href="./topic-reports/12.具身智能Agent-技术趋势报告.md">查看</a></td>
      <td>LLM/VLM 认知架构成为事实标准，多 Agent 协作、数字物理融合、记忆与心智理论持续抬升。</td>
      <td>Sim-to-Real 迁移、长程任务可靠性和安全性仍然制约大规模部署。</td>
      <td>仓储物流与实验室自动化将更有机会率先规模化落地。</td>
    </tr>
    <tr>
      <td><strong>Agent 工具使用与环境交互</strong></td>
      <td align="center"><a href="./topic-papers/13.%20Agent工具使用与环境交互.md">293</a></td>
      <td><a href="./topic-reports/13.%20Agent工具使用与环境交互-技术趋势报告.md">查看</a></td>
      <td>GUI Agent、MCP 生态、工具使用 RL 与深度搜索闭环共同推动 Agent 从调用工具走向重塑接口。</td>
      <td>真实环境中的效率、可靠性与工程化复杂度仍高，工具选择和环境适配仍有明显门槛。</td>
      <td>GUI 自动化 Agent 与企业级工具调用 Agent 将在未来 12 个月进入规模商业部署。</td>
    </tr>
    <tr>
      <td><strong>Agent 可解释性与透明度</strong></td>
      <td align="center"><a href="./topic-papers/14.%20Agent可解释性与透明度.md">73</a></td>
      <td><a href="./topic-reports/14.%20Agent可解释性与透明度-技术趋势报告.md">查看</a></td>
      <td>可解释性从模型解释走向系统审计，因果推理、Agent 解释 Agent、生产级可观测性快速成熟。</td>
      <td>多 Agent 动态系统的实时审计、故障归因与标准化问责基础设施仍不完善。</td>
      <td>到 2027 年，生产级 Agent 将被要求具备标准化可观测性与可审计性。</td>
    </tr>
    <tr>
      <td><strong>低代码 / 无代码 Agent 平台</strong></td>
      <td align="center"><a href="./topic-papers/15.%20低代码_无代码Agent平台.md">27</a></td>
      <td><a href="./topic-reports/15.%20低代码_无代码Agent平台-技术趋势报告.md">查看</a></td>
      <td>方向从零代码幻想转向人机协作设计，垂直场景平台、工作流可靠性与社区化生态开始成型。</td>
      <td>复杂场景下纯自然语言构建不可靠，运行时工作流稳定性与可复用组件生态仍薄弱。</td>
      <td>面向客服、数据分析、科学实验等垂直场景的低代码平台将在 18–24 个月走向成熟。</td>
    </tr>
  </tbody>
</table>

---

<a id="monthly-index"></a>

## 📅 月度索引

下表按月份汇总论文收录情况，并给出对应阶段的一句话趋势演化总结。

| 月份 | 论文数量 | 趋势演化总结 |
| :--- | :---: | :--- |
| [2025年1月](./monthly-reports/AI%20agents%202025年1月学术分类汇总.md) | 205 | 起步期，以应用系统、MARL、架构框架为主，Agent 研究仍以能力验证和场景探索为核心。 |
| [2025年2月](./monthly-reports/AI%20agents%202025年2月学术分类汇总.md) | 431 | 第一轮明显放量，安全、MARL、应用系统和人机协作同步升温，领域开始从单点尝试转向体系化扩张。 |
| [2025年3月](./monthly-reports/AI%20agents%202025年3月学术分类汇总.md) | 388 | 多Agent协作、MARL、架构设计持续活跃，研究重心开始从“会不会做”转向“如何组织与协同”。 |
| [2025年4月](./monthly-reports/AI%20agents%202025年4月学术分类汇总.md) | 347 | 总量短暂回调，但应用系统和安全对齐继续走强，说明社区开始沉淀工程问题与风险治理。 |
| [2025年5月](./monthly-reports/AI%20agents%202025年5月学术分类汇总.md) | 596 | 进入加速期，架构、协作、评测、学习、自进化多线共振，Agent 从原型走向系统化设计。 |
| [2025年6月](./monthly-reports/AI%20agents%202025年6月学术分类汇总.md) | 506 | 评测、安全和应用系统维持高热，研究开始更关注可靠性、生产可用性与真实环境适配。 |
| [2025年7月](./monthly-reports/AI%20agents%202025年7月学术分类汇总.md) | 470 | 增长趋稳，应用系统继续领跑，记忆、具身、人机协作等方向逐步补齐 Agent 长程能力短板。 |
| [2025年8月](./monthly-reports/AI%20agents%202025年8月学术分类汇总.md) | 585 | 新一轮扩张出现，架构、安全、协作、应用系统同步抬升，社区开始为更复杂的 Agent 系统打基础。 |
| [2025年9月](./monthly-reports/AI%20agents%202025年9月学术分类汇总.md) | 675 | 深度搜索、测试时计算和多Agent协作升温，研究明显转向长程任务、复杂交互和系统级优化。 |
| [2025年10月](./monthly-reports/AI%20agents%202025年10月学术分类汇总.md) | 794 | 2025 年高点，应用系统、安全、架构、协作全面爆发，标志着 Agent 进入工程化密集推进阶段。 |
| [2025年11月](./monthly-reports/AI%20agents%202025年11月学术分类汇总.md) | 633 | 总量回落但结构更成熟，记忆、架构、MARL 与安全继续推进，研究开始聚焦效率、治理与落地质量。 |
| [2025年12月](./monthly-reports/AI%20agents%202025年12月学术分类汇总.md) | 608 | 年末进入反思与整合期，安全、评测、架构仍强，社区开始集中讨论成本、鲁棒性与长期可用性。 |
| [2026年1月](./monthly-reports/AI%20agents%202026年1月学术分类汇总.md) | 868 | 进入生态化跃迁期，评测、安全、架构、应用系统同步冲高，Agent 基础设施和协议生态快速成形。 |
| [2026年2月](./monthly-reports/AI%20agents%202026年2月学术分类汇总.md) | 956 | 观察窗口峰值月份，多Agent协作、安全、架构、应用和评测全面共振，领域进入全栈爆发阶段。 |
| [2026年3月](./monthly-reports/AI%20agents%202026年3月学术分类汇总.md) | 639 | 截至 3 月 20 日仍保持高位，安全、评测、架构和应用系统延续高热，显示生态建设已具持续性。 |

## 📝 数据来源与版权说明

本仓库主要基于公开可获取的学术论文信息、公开链接以及作者的研究整理与分析撰写而成。

- 论文标题、摘要信息、链接等原始内容的版权归原作者及原出版方所有
- 本仓库中的综述、归纳、结构化整理与趋势判断为仓库维护者的原创工作
- 如你认为仓库中存在不适合公开展示的内容，请通过 Issue 或邮件联系处理

---

## 🔄 更新策略

当前版本以资料整理和结构化发布为主，后续可能继续补充：

- 新月份追踪
- 方向报告迭代
- 导航页和索引页
- 英文化摘要

---

## 🤝 如何贡献

欢迎通过 Issue 或 Pull Request 参与改进，例如：

- 修正文档错误
- 补充遗漏论文
- 优化目录和导航
- 补充引用与来源说明

具体约定见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

---

## 📌 引用方式

如果这个仓库对你的研究或写作有帮助，欢迎在引用或转载时注明仓库地址与原作者信息。建议引用仓库中的具体文件，而不是仅引用仓库名。

---

## 📄 License

本仓库采用 [CC BY 4.0](./LICENSE) 许可协议。你可以转载、改编和分享，但需要保留署名。
