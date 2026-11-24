---
title: GEO（生成式引擎优化）生态全景与创业机会分析
date: 2026-11-24
version: 1.0
scope: 全球 + 中国市场，数据截至 2026-11-24
status: 已完成
tags: [GEO, AEO, AI搜索, agentic-commerce, 创业机会, 市场分析]
---

# GEO（生成式引擎优化）生态全景与创业机会分析

> **一句话结论**
>
> 资本已经完成定价，但商业价值还没有被验证。这个赛道目前卖出的是「保险」，不是「增长」——企业付钱是因为害怕在 AI 答案里缺席，而不是因为他们能量化出 ROI。真正的钱不在「监测看板」（已经血海），而在**帮商家的商品数据被 agent 真正读懂**这件苦活上。

---

## 目录

- [0. 结论速览](#0-结论速览)
- [1. 资本面：谁在赢，赢得多快](#1-资本面谁在赢赢得多快)
- [2. 中国市场](#2-中国市场)
- [3. 技术底座：哪些是真的，哪些是行业神话](#3-技术底座哪些是真的哪些是行业神话)
- [4. 真实用例（贴近实际使用）](#4-真实用例贴近实际使用)
- [5. 核心矛盾：可见性 ≠ 流量 ≠ 钱](#5-核心矛盾可见性--流量--钱)
- [6. 创业机会：分层图谱](#6-创业机会分层图谱)
- [7. 机会排序：如果现在下注](#7-机会排序如果现在下注)
- [8. 一个高匹配度的细分切入点](#8-一个高匹配度的细分切入点)
- [9. 方法论与数据局限](#9-方法论与数据局限)
- [10. 参考文献](#10-参考文献)

---

## 0. 结论速览

| 维度 | 结论 | 置信度 |
|---|---|---|
| **赛道阶段** | 资本过热（单点估值 $1.8B），商业验证不足（AI 渠道贡献 <1% 转化） | 高 |
| **已关闭的窗口** | 通用可见性监测看板（10 家融资 ~$619M，一家占 55%，老牌 SEO 用 $99–199/月插件砸穿地板） | 高 |
| **应该避开的** | 自动化内容投喂（已被 315 定性为「AI 投毒」，法律定时炸弹） | 高 |
| **最好的位置** | Agent 可读的产品数据层（34% 零售产品页对 AI 实质不可访问） | 中高 |
| **现金流最快的** | Agent Gateway / 准入治理（agent 流量涨 7,851%，仅 2.31% 到达结账页） | 中高 |
| **最容易被证伪的** | 押注 llms.txt 的「技巧型」产品（4 个独立研究、5 亿+ 次 bot 访问，97% 文件零请求） | 高 |
| **短期驱动力** | 恐惧 + 防御性预算（42% 在纠错，仅 30% 在建交易能力） | 中高 |
| **真正的转折点** | agent 从「协议入口」转向「像人一样直接逛站」（8 月 1% → 10 月 77%） | 中 |

> **通用原则**
>
> 凡是「依赖模型当前行为」的产品都会归零（模型一改，技巧失效）。凡是「依赖数据结构和协议」的产品会累积（协议成为标准后，接入方被锁定）。

---

## 1. 资本面：谁在赢，赢得多快

### 1.1 融资总额与节奏

| 口径 | 数字 | 备注 |
|---|---|---|
| Dealroom（7 家，2024–25 成立） | **$472M** | 含 2 家已被收购 |
| Value Add VC（10 家披露） | **~$619M** | 截至 2026-10-16 |
| 2025 全年 | ~$178M | 统计口径：19 个有日期轮次 |
| 2026 前三季 | ~$375M | **同比翻倍** |

⚠️ 两个总额口径不同（7 家 vs 10 家），不可混用。

### 1.2 Profound：25 个月 5 轮，$3.5M → $1.8B

| 轮次 | 时间 | 金额 | 估值 | 领投 |
|---|---|---|---|---|
| Seed | 2024-08 | $3.5M | — | Max Altman, Keith Rabois, Balaji Srinivasan, South Park Commons 等 |
| Series A | 2025-06 | $20M | — | Kleiner Perkins, Khosla Ventures, NVentures(英伟达) 等 |
| Series B | 2025-08 | $35M | — | Kleiner Perkins, Sequoia, Khosla |
| Series C | 2026-02 | $96M | **$1B** | Lightspeed, Sequoia, Kleiner Perkins |
| Series D | 2026-09-15 | $180M | **$1.8B** | **Sequoia + Kleiner Perkins** 联合领投 |

**累计 $334.5M，占整个赛道披露融资的 55%。**

公司自述（未经审计）：
- 收入 6 个月增长 **3 倍**
- **1,000+** 企业客户
- 覆盖 **1/3 的 Fortune 100**
- 客户含 Comcast、The Estée Lauder Companies、Walmart

### 1.3 第二梯队与「血海」信号

| 公司 | 累计融资 | 最新轮 |
|---|---|---|
| Bluefish（纽约） | $68M | $43M B 轮，2026-04，Threshold + NEA |
| AirOps | ~$62.5M | 公司口径 |
| Brandlight | ~$36M | — |
| **Peec AI（柏林）** | ~$29–40M | $19.8M A 轮，2025-11，Singular 领投（成立后 10 个月） |
| Evertune | $15M | A 轮，2025-08，Felicis 领投 |
| Promptwatch（阿姆斯特丹） | €7.2M | $6.6M seed，2026-07，seed + speed 领投 |
| geoSurge（英国） | $12M | Seed，2026-07，AlbionVC 领投 |
| Searchable（英国） | €11.9M | — |

**Peec AI 是最有信息量的样本**：融资只有 Profound 的 1/10，但**收入已做到 $20M**。创始人公开说：

> **「我们曾有 131 个对手。」**（We had 131 rivals）——GEO 的 gold rush 已经变成 **bloodbath**。

### 1.4 退出已经发生（这是最关键的信号）

| 事件 | 时间 | 金额 |
|---|---|---|
| HubSpot 收购 **XFunnel** | 2025-10 | ~$30M 现金 |
| Adobe 收购 **Semrush** | 2026-04-28 | **~$19 亿**（全现金，交易媒体口径） |
| Sitecore 收购 **Scrunch** | 2026-06（官宣 06-03） | 传 **~$225M**（Sitecore 未披露） |

### 1.5 老牌 SEO 工具如何应战（价格地板被砸穿）

| 产品 | 定价 | 上线时间 |
|---|---|---|
| **Ahrefs Brand Radar** | **$199/月 per AI index** | 2026 |
| **Semrush AI Visibility Toolkit** | **$99/月 per domain** | 2026（Adobe 收购后） |
| BrightEdge AI Catalyst | 企业定价 | 2026 |
| Conductor AEO/GEO platform | 企业定价 | 2026 |
| HubSpot AEO Grader + 监测模块 | 免费 + **$50/月** | 2025-10 起 |
| Adobe Brand Visibility | 企业定价 | 2026-06 |
| Surfer SEO | 内容工具改造 | 2026 |

> **这一组的含义**：一个六位数年单的创业公司（Profound）和一个 $99/月的插件（Semrush）在做同一件事。**中间层的独立 SaaS 会被两头碾死。**

### 1.6 三层竞争格局

```
企业级（六位数年单）     Profound（1/3 Fortune 100）
                        ↓ 已被锁定
中间层（独立 SaaS）      Bluefish / AirOps / Brandlight / Peec / Evertune
                        ↓ 正在被两头挤压 ← 死亡区间
插件层（$50–199/月）     Ahrefs / Semrush / HubSpot / BrightEdge / Adobe
                        ↓ 渠道与分发优势
```

---

## 2. 中国市场

### 2.1 市场规模（两个预测差 6 倍，口径不明）

| 机构 | 2025 | 2026 | 2027 |
|---|---|---|---|
| **易观分析** | ~2.5 亿元 | **~30 亿元** | 有望破 90 亿元 |
| **弗若斯特沙利文** | — | **突破 180 亿元** | CAGR >45% |

⚠️ 两个数字差 6 倍以上，且都未披露统计口径（是否含代运营、是否含投放、是否只算软件），**无法判断哪个可信**。

### 2.2 主要玩家

| 类型 | 代表 | 状态 |
|---|---|---|
| 上市公司子公司 | **蓝色光标「蓝标智投 GEO」** | 已上线 |
| 上市公司子公司 | **浙文互联「HochiGEO 智能体」** | 已上线 |
| 创业公司 | **PureblueAI 清蓝**（前豆包大模型市场负责人创业） | 千万级种子轮 |
| 创业公司 | **智推时代 GenOptima** | 2026 初完成天使轮 |
| 创业公司 | 某家（2025-10） | 千万级种子轮，**三七互娱领投 + 趣睡科技跟投** |
| 创业公司 | **Otterly.ai**（奥地利，全球） | 无融资，自称 4 万+ 营销人员使用 |

### 2.3 ⚠️ 315 定性：这是中国市场的最大变量

**2026-03-15 央视 3·15 晚会《谁在给 AI「投毒」》**

曝光内容（据央视调查与媒体报道）：
1. 记者在电商平台购买一套 **「力擎 GEO 优化系统」** 软件
2. 软件自动生成十余篇智能手环宣传软文，**所有虚假信息被完整写入**，还杜撰用户好评、伪造评分，把这款产品评为「业界第一」
3. 3 天内通过该系统发布 **11 篇**虚构软文（8 篇「专家测评」+ 2 篇「行业排名」+ 1 篇「用户测评」）
4. 行业人士对央视直言：**「你看我们现在干 GEO 的都是『投毒』，投的信息源太多，网上信息并不是很准。」**

**后续影响**：
- 行业标准缺失、监管处于真空
- 法律对「GEO 公司通过投喂内容影响 AI 输出**是否构成广告**」**尚无明确规定**
- **中国信通院人工智能研究所**于 2026-03 启动首轮 **《生成式引擎优化（GEO）可信基本要求》** 评测工作
- 业内开始区分「黑帽 GEO」（批量虚假软文、伪造权威认证、恶意指令藏在网页代码/元数据）与「白帽 GEO」（内容经审核、无虚假信息）

> **对创业决策的影响**：任何以「批量内容投喂」为核心的产品，在中国已从「灰色」变成「被公开点名的灰产」。一旦广告法定性落地，整个模式归零。**这不是商业风险，是法律风险。**

---

## 3. 技术底座：哪些是真的，哪些是行业神话

### 3.1 ❌ llms.txt：四个独立研究，5 亿+ bot 访问，结论高度一致

llms.txt 是 Jeremy Howard 于 2024-09 提出的规范：站点根目录下一个 markdown 文件，概述网站内容并链接重点页面，供 LLM/agent 按需读取。

**四个独立研究的结论**：

| 研究 | 样本 | 部署率 | 结果 |
|---|---|---|---|
| **SE Ranking** | ~300,000 域名 | **10.13%** | 与 AI 引用频率**无相关性**；把该变量从 XGBoost 模型去掉后，**预测反而更准** |
| **Limy** | 90 天 **5 亿+** AI bot 访问 | — | 仅 **408 次**请求 llms.txt |
| **Otterly** | 90 天服务器日志 | — | 62,100+ AI bot 访问中仅 **84 次**碰它（**0.1%**） |
| **Ahrefs** | **137,210** 域名（2026-05） | 28%（自称为上限） | **97% 的文件零请求** |

**Ahrefs 的请求构成拆解**（约 22,000 次请求，落在约 1,100 个域名上）：

| 请求方类型 | 占比 |
|---|---|
| AI agents（真正会读的） | **10.5%** |
| 训练爬虫 | **5.3%** |
| GEO/AEO 工具 + 研究者（「行业研究自己」） | 12% |
| **AI 检索机器人**（本该最关心的） | **1.1%** |
| 其中 GPTBot 单家 | 4.51% |
| 其中 Claude Code（编码 agent） | 第 2 位，超过所有 AI 检索/助手 bot |

**几条决定性证据**：
- **AI bot 从来不去找不存在的 llms.txt**：404 请求中 AI bot 占比 = **0**。发布文件不会让你进入任何 AI 雷达。
- **Google 官方两次表态**：2025-06 John Mueller「没有任何 AI 系统在用 llms.txt」；2026-07-10 的 AI optimization guide 明写可忽略「创建不必要的 AI 文本文件（如 llms.txt）」，**「不害也不帮」**。
- **OpenAI / Anthropic 均未承诺**：OpenAI 的爬虫文档只讲 robots.txt；Anthropic 自己发布 llms.txt 是**开发者文档用途**，不是搜索引用。
- **Common Crawl** 2026-07 分析 584,107 个文件：**68% 是模板生成**（Wix 独占 **41.34%**），只有 **49.9%** 结构完整，**22.56%** 全无链接。
- **安全风险**：已有针对 llms.txt 的 **prompt injection 探测**；agent 被设计为信任该文件，陈旧或被篡改的文件会误导每一个读取它的 agent。

**为什么没用**（四条结构性原因）：
1. AI 爬虫本来就能很好地读 HTML，剥离导航与模板是已解决问题
2. 检索是**逐页**发生的，一个站点摘要回答不了任何具体问题
3. **自我声明的摘要天然可被操纵**——这正是 meta keywords 标签死亡的原因
4. **没有任何大厂签署**。文件是「没有收件人的信」。

### 3.2 ✅ llms.txt 唯一真有效的场景：编码 agent

**Mintlify 对 20 个文档站的测试**：

| 条件 | agent 每个任务的失败页面请求数 |
|---|---|
| 纯 HTML | **2.23 次** |
| Markdown + 指向 llms.txt 的链接 | **0.11 次** |

Cursor / Claude Code / Copilot 确实会主动读取。**所以它的定位是「开发者文档的可用性优化」，不是「AI 搜索的可见性手段」。**

### 3.3 ✅ 真正在起作用的技术层：结构化产品数据 + 协议栈

| 协议 | 主导方 | 功能 | 状态 |
|---|---|---|---|
| **ACP**（Agentic Commerce Protocol） | OpenAI + Stripe | Agent 结账；2026-03 扩展到 product feeds | Beta（v0.2，2026-04-17），Apache 2.0 |
| **UCP**（Universal Commerce Protocol） | Google + Shopify / Etsy / Wayfair / Target / Walmart | 目录、购物车、跨 AI 界面结账 | Live，扩张中（2026-01-11 发布，20+ 背书） |
| **AP2**（Agent Payments Protocol） | Google + 支付伙伴 | 授权 agent 发起的支付 | Live，2026-04-28 v0.2 **捐给 FIDO Alliance** |
| **MCP**（Model Context Protocol） | Anthropic | 连接 agent 与工具/数据 | Live，2025-12 捐给 Linux Foundation |
| **A2A**（Agent2Agent） | Google | Agent 间任务交接 | Live |
| **WebMCP** | Google + Microsoft | 浏览器侧 agent 接口 | Chrome origin trial（I/O 2026）；**Shopify 2026-08-05 在全部 Liquid 店面启用** |

**最关键的一个数字**：

> **Adobe 研究：约 34% 的零售产品页对 AI 系统实质不可访问。**

原因不是缺少 llms.txt，而是：
1. 页面需要 JS 渲染，agent 跑不了
2. 价格和库存只活在客户端购物车状态里
3. 产品信息分散在多个从未为「机器读者」设计的系统里

---

## 4. 真实用例（贴近实际使用）

按**落地成熟度**排序。

### 4.1 用例 A：品牌可见性监测 —— 唯一已规模化验证的形态

**做什么**：跑一组 prompt，统计品牌在 ChatGPT / Gemini / Perplexity / AI Overviews 里的提及率、位置、描述文本。

**已落地的真实规模**：

| 公司 | 实际用量 |
|---|---|
| **Profound** | 1,000+ 企业客户，1/3 Fortune 100（Comcast / 雅诗兰黛 / Walmart） |
| **Obsero**（伦敦，2025 成立） | 第一年追踪分析 **1,000 万+ AI 回答**；客户 Zopa Bank、Pepperstone；代理伙伴 IDHL、Silverbean |
| **Otterly.ai**（奥地利，无融资） | 自称 **4 万+** 营销人员使用 |
| **First Answer**（巴西，2025-06 成立） | 客户 ClickBus、Afya、Ferrero、Avenue，覆盖巴西/美国/加拿大/英国/阿根廷 |

**判断**：这是当前唯一被验证「有人愿意付钱」的形态——但也正因为如此，它已经被打完了。

---

### 4.2 用例 B：内容与工程改造 —— 上半场在做，下半场没开始

**Gartner 2026 营销策略与参与度调研**（本文信息量最大的一组数字）：

| 已采取的行为 | 比例 |
|---|---|
| 已调整内容与 SEO/AEO 以提升**机器可读性** | **61%** |
| 在**监测并纠正** AI 输出中关于自己品牌的错误信息 | **42%** |
| 已针对机器/agent 决策**定制产品信息、定价或优惠** | **39%** |
| 把机器和 agent 当作**独立受众**管理 | **32%** |
| 已为 agent 交易**设计界面或工作流** | **30%** |

**读法**：61 / 42 / 39 是「被发现」层面，已经动起来了；30 / 32 是「被交易」层面，基本没动。

> **这就是创业机会的形状**——战场正从「曝光」转向「可交易性」，而绝大多数企业还没起步。

---

### 4.3 用例 C：Agentic Commerce —— 真正的新增市场，但漏斗极窄

#### Forter 网络数据（2026-11-18，60 天真实交易，含 Muse / Instinct / Grok）

| 指标 | 数字 |
|---|---|
| agent 订单量（新 agent 上线后一个月 vs 前一个月） | **+229%** |
| agent 订单渗透率 | 约 **1/10,000** 订单；比 2026 上半年日均 **25x** |
| 过去 30 天至少 1 笔 agent 订单的商户 | **60%**，其中 **9%** 超过 100 笔 |
| **「点站式」个人助理占 agent 订单比**（8 月初 → 10 月中） | **1% → 77%** ← 最关键变化 |
| agent 流量份额（11-12） | Muse **49%** / ChatGPT 协议 agent **22%** / Grok **14%** / Instinct **9%** |
| **agent 订单客单价 vs 人类** | **$227 vs $133（1.7x）** |
| 餐饮配送 | $117 vs $57（**2.1x**） |
| 数字商品与服务 | $145 vs $99（1.5x） |

> **「点站式」从 1% 涨到 77% 是本文最重要的一条趋势**：说明 agent 不再依赖 ACP/UCP 这类协议入口，而是**像人一样直接浏览商户网站**（有 headless checkout 就走，没有就自己点）。
>
> Forter 的 VP of Product 原话：**「这些是你的客户在用他们的 agent 跟你买东西。所以当这些 agent 被封的时候，你封的其实是你最好的客户。」**

#### 但漏斗的另一头极窄

> **HUMAN Security：agent 流量涨 7,851%，但只有 2.31% 到达结账页。**
>
> 意味着 **97.7% 的 agent 需求被浪费在门口**——被挡、走错、或迷路。

#### 市场规模（注意这条曲线本身在讲故事）

**eMarketer（美国零售端到端 agentic 电商）**：

| 年份 | 规模 | 增速 |
|---|---|---|
| 2026 | **$14.4 亿** | — |
| 2027 | $15.9 亿 | +10.6% |
| 2028 | $17.6 亿 | +11% |
| 2030 | **$2.17 万亿** | — |

> **前三年增速只有 10% 左右，真正的爆发被推到 2030。这条曲线本身说明短期市场极小。**

**Morgan Stanley**：2030 年美国 agentic 电商 $1,900–3,850 亿。

#### 最值得学的失败案例：ChatGPT Instant Checkout

| 时间 | 事件 |
|---|---|
| 2025-09-29 | 上线，美国用户可在聊天内购买 Etsy 商品，商户按成交付费 |
| 2026-03-24 | **收缩**。官方：「初始版本没提供我们希望商户拥有的灵活性，所以我们让商户用自己的结账流程，我们专注商品发现」 |
| 2026-03 | ACP 转向 product feeds / 商品发现 |
| 2026-11-13 | 改推 **ChatGPT Wallet**（在商户自己的结账页付款，仅 US Pro 订阅者） |

> **真实原因**：Walmart 高管告诉 Wired，**in-chat 转化比点击跳转到 Walmart 自己站点低 3 倍**。
>
> **教训**：**发现（discovery）跑得比结账（checkout）快得多。** 谁能控制发现，谁就有议价权；结账只是执行层。

#### 渠道战争已经开打

| 时间 | 事件 |
|---|---|
| 2026-03-11 | Amazon Shop Direct 开放外部 product feeds：**1 亿+ SKU / 40 万+ 商户** |
| 2026-09-20 | **Amazon 封禁 Meta 的 Muse** |
| 2026-10-21 | Walmart 推 **Agent Gateway**，让外部 agent 进店，并让用户设 **$50 / $100 / $200** 花费上限 |
| 2026-11-10 | OpenAI Business Hub（beta），验证过的商户可自己上传 feed |
| 2026-11-11 | **United Airlines 禁止未授权 AI agent**；a16z 发《Welcome to the B2A Economy》 |
| 2026-11-12 | Mastercard 报告一笔由 AI agent 完成并付款的真实机票订单 |

#### 消费者信任的真实边界

**Global Payments《Agentic Commerce Report 2026》**（7 国，8,027 名消费者）：

| 意愿 | 比例 |
|---|---|
| 让 AI 独立比价 | **74%** |
| 让 AI 找/研究产品 | **69%** |
| **只在本人批准下**让 AI 完成购买 | **59%** |
| 接受 AI **完全自主**购买 | **21%** |
| 舒适于自动购买（有额度上限） | **12%** |
| 说什么都不放心 | **16%** |

- 最强的信任建设手段：**每次购买前的确认步骤（34%）**
- **83%** 表示「没有任何人能看到我的真实卡号」很重要
- **30%** 希望保留能联系到人类客服的通道

**其他调研**：
- **Deloitte**（13,500 欧洲消费者）：超一半已用 AI 购物，另 27% 打算用；西班牙/波兰/匈牙利/意大利 **60%+**，英法德 48–52%（约 20 个百分点差距）
- **Bain**：约 **1/4** 网购者计划从 AI 平台开始假日购物

> **对创业的含义**：**agent-readiness 的起点是发现和比较，不是支付。** 从 checkout 开始做的商户，是在优化消费者最不信任的那一步。

---

### 4.4 用例 D：AI 声誉纠错与合规（42% 在做，供给最薄）

企业已在**人工**做「监测并纠正 AI 输出中关于自己的错误信息」，但没有可规模化的工具。

这条需求在监管压力下是刚需——虚假宣传、消费者保护、以及金融行业的投资者适当性管理。

---

## 5. 核心矛盾：可见性 ≠ 流量 ≠ 钱

**这是判断这个赛道值不值得做的唯一关键。** 正反两边的硬数据都摆出来。

### 5.1 反方：AI 渠道现在几乎不带来生意

| 研究 | 样本 | 核心结论 |
|---|---|---|
| **Marie Haynes**（2026-10-21） | 100 站，**1.45 亿 session**，12 个月 | ChatGPT 访问量 = Google 自然的 **0.62%**（全 LLM 0.73%）；ChatGPT 转化 **13.8%** vs 自然 **3.02%**（**4.5x**）；**但 Google 自然贡献 96.5% 的全部转化，是全部 LLM 合计的 27 倍** |
| **The SEO Works**（Zenodo, 2026-09-29） | 95 站，2025-09 ~ 2026-08 | 自然搜索会话量是 AI 引荐的 **39x**；AI 引荐 = 自然会话的 2.6%；AI 转化 1.18x 自然（7.18% vs 6.08%）；**B2C 1.51x / Mixed 1.46x / B2B 服务 1.21x / B2B 产品仅 0.62x**；63 个可比站里 **23 个 AI 转化比自然差**；对 paid search 只有 0.67x；**未发现「广告牌效应」**（AI 曝光未带动直接流量）；自然搜索提升 **5%** 带来的转化 > AI 引荐**翻倍** |
| **Kaiser & Schulze**（*Marketing Science* 45(4):699-715, 2026） | **973 站 / $200 亿收入** / 12 个月 / 16.4 亿笔交易 | oLLM 占总流量 **<0.2%**，约 **200 倍小于** Google 自然搜索；转化率高于付费社交、**低于其他所有传统渠道**；自然搜索转化可能性比 oLLM 高 **13%**；复杂产品品类效果更强；转化率上升但客单价下降；结论原文：「oLLM 目前服务的是**精通消费者的细分信息需求，尚不构成广泛的转化渠道**」 |
| **Kaiser & Schulze**（2026-10，ChatGPT 广告国际推广） | 1,898 店 / $160 亿 / 60 周 / 近 100 亿 session | 有机 ChatGPT 占全部访问 **0.23%**，最后 4 周 **0.40%**；转化 **1.99%** |
| **Kevin Indig**（2026-10-21） | 12 个 GA4 资产 + 632 次测试 | **无法建立** AI 可见性与后续品牌搜索/直接流量之间的可靠联系（但不排除存在，只是无法隔离） |

**一个容易被忽略的细节**：Haynes 的 100 个站里，**45 个根本没配任何转化事件**。
The SEO Works 也承认 **AI Overviews 的点击被算进自然搜索**。
这个行业一边争论十几个渠道的归因，一边有近一半的站什么归因都做不了。

### 5.2 正方：会话数看不见的东西，恰好是价值所在

**session 数结构上看不到这四件事**：

1. **读了答案但没点击**的人
2. **问了之后直接搜品牌名** → 变成 Direct / branded（模型决定了候选名单，但归因不到它）
3. **在平台内完成的购买** → 商户站根本没加载，没有 session 可数，订单在订单系统里挂在平台名下
4. **你不在答案里造成的损失** → session 表里没有「缺席」这一列

> 用一句类比：**用引荐流量衡量 AI 答案的影响力，就像用「有多少人在收银台提起这块广告牌」来衡量广告牌的效果。**

### 5.3 判断

**两边都对，但时间尺度不同。**

- **短期（12–24 个月）**：GEO 的支出是被**恐惧 + 防御性预算**驱动的。证据就在 Gartner 那组数字里——**42% 在纠错，只有 30% 在建交易能力**。纠错是防御动作，不是增长动作。
- **中期**：真正的转折点不是「AI 带来多少点击」，而是 **agent 从「协议入口」转向「像人一样直接逛站」的那个拐点**（1% → 77%）。当 agent 直接逛站，GEO 就从「营销问题」变成「基础设施问题」——那时赢的不是写软文的人，是让商品数据可被读取的人。

> **结论**：
> - 为了**短期现金流**创业 → 这个赛道的 ROI 叙事还撑不起来，除非做安全/bot 治理这种「不需要说服客户 AI 重要」的生意
> - 为了 **3 年后的位置** → 现在正是布局窗口

---

## 6. 创业机会：分层图谱

### 6.1 第一层：已红海，不要进

#### ❌ 通用可见性监测看板

**证据**：
- Peec AI 创始人自述「**曾有 131 个对手**」，gold rush 已成 bloodbath
- 10 家披露 $619M，**一家占 55%**
- Ahrefs **$199/月** vs Profound 六位数年单，中间层被两头碾
- Profound 已拿 1/3 Fortune 100，企业级 TAM 基本锁定

**唯一残余空间**：非英语市场的本土平台（Gemini / Perplexity 覆盖弱、本土平台占主导的地区）。

---

### 6.2 第二层：法律定时炸弹，别碰

#### ❌ 自动化内容投喂（批量软文）

**证据**：
- 315 已经把这条路**公开命名为「投毒」**
- 中国信通院 2026-03 启动《GEO 可信基本要求》评测
- 法律对「投喂内容是否构成广告」**尚无明确规定**——一旦定性，整个模式归零
- 模型侧必然反制（信源信誉加权、持牌权威信源权重上调、AI 生成内容识别）

> **这类「工具」不是生意，是负债。**

---

### 6.3 第三层：真正空着的四个位置

#### ★ ① Agent 可读的产品数据层（最看好）

**依据**：
- Adobe：**34% 零售产品页对 AI 系统实质不可访问**
- 原因：JS 渲染、价格库存藏在客户端状态、信息分散在多个系统

**需求方已经明确掏钱**：
- Shopify 2026-08-05 在**全部 Liquid 店面**启用 WebMCP agent tools
- Amazon 2026-03-11 Shop Direct 开放 **1 亿+ SKU / 40 万商户**
- OpenAI 2026-11-10 Business Hub（beta），让验证过的商户自己上传 feed
- Google UCP 要求商户构建集成并获批

**生意的本质不是 SEO，是中间件 / ETL**：
- 把 PIM / ERP / 电商后台的脏数据洗干净
- 映射到 ACP / UCP 的 feed schema
- 保证实时价格与库存一致性
- 做幂等、缓存、错误回滚、并发限流

**为什么现在还空着**：大厂只做了**协议和入口**，没人做「把 40 万商户的脏目录真正接进去」这件苦活。

---

#### ★ ② Agent Gateway / Agent 准入治理（现金流最快）

**依据**：
- HUMAN Security：agent 流量涨 **7,851%**，但只有 **2.31%** 到达结账页
- **97.7% 的 agent 需求被浪费在门口**

**战争已经开打**：
- Amazon 封 Meta Muse（2026-09-20）
- United Airlines 禁未授权 agent（2026-11-11）
- Walmart 推 Agent Gateway + 花费上限（2026-10-21）
- Forter：「你在封的是你最好的客户」

**要解决的问题**：
- 识别 agent 身份（vs 普通爬虫 vs 恶意 bot）
- 验证消费者授权（AP2 / FIDO / Visa Trusted Agent Protocol）
- 差异化限速与定价（pay-per-crawl）
- 差异化曝光（给 agent 看结构化 feed，给人看渲染页）
- 防提示注入
- 争议举证（dispute evidence）

**优势**：**安全预算是现成的**，不需要说服客户「AI 重要」。
**风险**：会被 Cloudflare / Akamai / HUMAN / Forter 这类吞掉（Cloudflare 已在推 pay-per-crawl）。

---

#### ★ ③ B2A（Business-to-Agent）信任与合规基础设施

**信号**：a16z 在 **2026-11-11** 发《Welcome to the B2A Economy》——顶级 VC 已经在给这个叙事定价。

**可做的具体形态**：
- **AI 输出的品牌事实核对**（42% 的企业在做，但全靠人工，没有工具）
- 侵权与虚假信息取证
- 监管报送（中国信通院评测、EU AI Act 透明性义务）

**护城河是资质和流程，不是模型**——这是「AI 声誉的审计事务所」位置。

---

#### ★ ④ 垂直 / 地理套利

**欧洲出现了一整批 €1M–€12M 的小轮**，说明地域分散确实存在，且没被 Profound 吃掉：

| 公司 | 国家 | 金额 |
|---|---|---|
| geoSurge | 英国 | $12M seed |
| Searchable | 英国 | €11.9M |
| Lemrock | 法国 | €6M |
| DOJO AI | 葡萄牙 | €5.1M |
| Querio | 英国 | €4.48M |
| GetMint | 法国 | €4M |
| Miracly | 瑞典 | €1.8M（pre-seed） |
| Obsero | 英国 | €1M（seed） |

**中国**：30 亿人民币市场、本土大厂（蓝标、浙文）刚起、信通院正在立标准。
> **标准落地期往往是「合规咨询 + 评测 + 备案」生意最好的时候。**
> 但 315 已经定性，且大厂自带媒体渠道，这是硬约束。

---

## 7. 机会排序：如果现在下注

| 方向 | 需求确定性 | 拥挤度 | 12 个月现金流 | 3 年天花板 | 评级 |
|---|---|---|---|---|---|
| **Agent 可读产品数据层** | 高（34% 页面不可访问） | 低 | 中（企业集成周期长） | 高 | **A** |
| **Agent Gateway / 准入** | 高（97.7% 到不了结账） | 中低 | 高（安全预算现成） | 中高（会被 CDN 吃） | **A−** |
| 品牌 AI 声誉核对 / 合规 | 中高（42% 在做） | 低 | 高（咨询 + 软件） | 中 | **B+** |
| 垂直 / 地理套利 | 中高 | 中 | 中 | 中 | **B** |
| 可见性监测看板 | 高但饱和 | 极高 | 低（价格战） | 低 | **C** |
| 自动化内容投喂 | 中 | 高 | 高但短命 | 归零风险 | **F** |
| 押注 llms.txt 类「技巧型」产品 | **已被证伪** | — | — | — | **F** |

**一条通用原则**：

> 凡是「依赖模型当前行为」的产品都会归零（模型一改，技巧失效）。
> 凡是「依赖数据结构和协议」的产品会累积（协议成为标准后，接入方被锁定）。

---

## 8. 一个高匹配度的细分切入点

### 金融信息的 AI 可见性与准确性核对

**为什么这个方向特别成立**：

1. **错误信息的代价最高**
   42% 的企业在纠错，但金融领域出错涉及投资者误导、适当性管理、信息披露合规——这是**硬监管**，不是营销问题。

2. **中文金融信息在 AI 里的准确率很差**
   公众号内容难以检索、搜索引擎有验证码墙、转载源滞后。AI 引用这些残缺信息源，出错是结构性的。

3. **真值源是别人没有的护城河**
   行情数据 / 财务报表 / 公告是公开但需要工程能力才能稳定获取的。**「AI 答案 vs 权威数据源」的自动核对**，99% 的 GEO 服务商不具备（他们只有 prompt 跑批，没有事实基准）。

4. **产品形态清晰**
   给定一组金融问题（「XX 基金的近三年年化」「XX 股票的市盈率」），跑多个模型，把 AI 输出与该基金的公告 / 交易所数据比对，输出：
   - 偏差报告（哪一项错了、错多少、错的方向）
   - 引用溯源（AI 引用了哪个不可靠来源）
   - 修正建议（应该引用哪个权威来源）
   - 趋势（偏差是收敛还是扩大）

5. **付费方明确**
   基金公司、券商、银行理财子、财经媒体。

**为什么这个方向比通用 GEO 更难被碾**：
标准（AI 答案的金融事实准确性）一旦建立，就是审计式的长期合同，而不是 $99/月的插件。

---

## 9. 方法论与数据局限

⚠️ 以下因素会影响结论的强度，不做粉饰。

### 9.1 厂商自报数据未经审计

| 数据 | 问题 |
|---|---|
| Profound「收入 6 个月 3x」 | 公司自述 |
| Peec AI「收入 $20M」 | 公司自述 |
| First Answer「自 4 月增长 86%」 | 明确说是 self-reported |
| Otterly「4 万+ 营销人员」 | 公司自述 |

### 9.2 口径不一致

- 融资总额：Dealroom **$472M（7 家）** vs Value Add VC **$619M（10 家）**
- Ahrefs 自己承认 28% 的 llms.txt 部署率是**「上限」**
- Common Crawl 的 68% 模板生成率与 SE Ranking 的 10.13% 部署率**样本不同**（前者是已存在的文件，后者是全部域名）

### 9.3 中国市场两个规模预测差 6 倍

易观 30 亿 vs 弗若斯特沙利文 180 亿，**均未披露口径**，无法判断哪个可信。

### 9.4 转化率研究存在系统性样本偏差

| 研究 | 偏差方向 |
|---|---|
| Marie Haynes | 100 个站是**她作为 SEO 咨询公司能接触到的客户**——本身就是「Google 有问题」才找过来的，会**系统性高估 Google 占比** |
| The SEO Works | 承认 **AI Overviews 的点击被算进自然搜索**，会**低估 AI 的作用** |
| Kaiser & Schulze | 明确说 last-click 归因，**无法捕捉上漏斗贡献** |

### 9.5 最根本的测量缺口

**所有研究都测不到**：
- 「读了答案没点击」
- 「平台内成交」
- 「不在答案里的机会成本」

所以「AI 渠道现在没用」这个结论，**在归因层面成立，在影响层面未被证伪**。

### 9.6 时效性

本文所有数据截至 **2026-11-24**。这个赛道月度级别在变（ChatGPT Instant Checkout 上线 6 个月就收缩、Muse 9 月发布 11 月就打到新加坡和澳洲），**建议 3 个月后重新核验**。

---

## 10. 参考文献

### 资本与市场

1. Dealroom — *Generative engine optimization startups: funding and exits in 2026*（2026-09-18）
   https://dealroom.co/charts/generative-engine-optimization-startups
2. Value Add VC / Trace Cohen — *AI Search Optimization (GEO/AEO) Startups 2026: Who Has Raised $619M*（2026-10-16）
   https://valueaddvc.com/blog/ai-search-optimization-startups-2026-geo-aeo-funding-investors
3. TechCrunch — *AEO startup Profound hits unicorn valuation, raises $180M Series D*（2026-09-15）
   https://techcrunch.com/2026/09/15/aeo-startup-profound-hits-unicorn-valuation-raises-180m-series-d-7-months-after-last-round/
4. Pathfounders — *"We had 131 rivals": Peec AI founder says GEO gold rush has become a bloodbath as its revenue hits $20m*
   https://pathfounders.com/p/we-had-131-rivals-peec-ai-founder-says-geo-gold-rush-has-become-a-bloodbath-as-its-revenue-hits-20m
5. Everything-PR — *Ahrefs, Semrush, Conductor vs GEO Startups*（更新于 2026-11-08）
   https://everything-pr.com/ahrefs-semrush-and-conductor-push-back-as-geo-pure-plays-raise-hundreds-of-millions
6. EU-Startups — *15 startups helping AI discover your company and product*（2026-10）
   https://www.eu-startups.com/2026/10/15-startups-helping-ai-discover-your-company-and-product/
7. EU-Startups — *London's Obsero raises €1 million*（2026-10-13）
   https://www.eu-startups.com/2026/10/londons-obsero-raises-e1-million-to-help-brands-improve-visibility-in-ai-powered-search
8. AlbionVC — *geoSurge raises $12m behind a new thesis for AI visibility*（2026-07-03）
   https://albion.vc/spotlight/news/geosurge-raises-12m-behind-a-new-thesis-for-ai-visibility/
9. Dealroom News — *First Answer adds $115K to pre-seed*（2026-11-17）
   https://dealroom.co/news/173674-first-answer-adds-115k-to-pre-seed-to-chase-ai-search-visibility/

### 中国市场与 315

10. 21 世纪经济报道 — *315 晚会曝光 AI「投毒」灰产链，暴露大模型背后算法高危漏洞*（2026-03-16）
    https://www.21jingji.com/article/20260316/herald/8cf9afdb3bc8ba06b10b2f89aef3bc17.html
11. 央视网 — *[2026 年 3·15 晚会] 谁在给 AI「投毒」*（2026-03-15）
    https://tv.cctv.com/2026/03/15/VIDEmX0VdYf9DeKI87GYEfqF260315.shtml
12. 易观分析 — *315 曝光「AI 投毒」，GEO 乱象背后的信息入口重构与治理挑战*
    https://www.analysys.cn/article/detail/20021419
13. 钛媒体 — *央视 315 曝光 AI「投毒」，我们和几位 GEO 从业者聊了聊*（2026-03-16）
    https://www.tmtpost.com/7915179.html
14. 36 氪 — *GEO 爆火，谁在给 AI 投喂「垃圾」？*
    https://m.36kr.com/p/3572397845298049
15. 投资界 — *2026 生成式引擎优化（GEO）服务商选购指南*（易观市场规模数据）
    https://m.pedaily.cn/99discoveries/142919

### llms.txt 与检索机制

16. Ahrefs — *We Analyzed 137K Sites: 97% of llms.txt Files Never Get Read*（2026-06-15）
    https://ahrefs.com/blog/llmstxt-study
17. SE Ranking — *Does LLMs.txt impact your AI visibility and citations? No, according to research*
    https://seranking.com/blog/llms-txt
18. Optimizely — *Does llms.txt work? The honest answer, with receipts*（2026-10-13）
    https://optimizely.com/field-notes/articles/does-llms-txt-work
19. Otterly.ai — *The llms.txt Experiment*
    https://otterly.ai/blog/the-llms-txt-experiment/
20. Limy — *llms.txt in 2026: The Full Guide*
    https://limy.ai/blog/llms-txt-in-2026-the-full-guide
21. Common Crawl — *A Content Analysis of llms.txt Files from the July 2026 Crawl Archive*
    https://commoncrawl.org/blog/a-content-analysis-of-llms-txt-files-from-the-july-2026-crawl-archive
22. Google Search Central — *AI Optimization Guide*（更新 2026-07-10）
    https://developers.google.com/search/docs/fundamentals/ai-optimization-guide
23. arXiv 2610.38361 — *Manifest-Assisted Retrieval in AI Search: Evidence Gaps and a Security Evaluation Framework for llms.txt*
    https://arxiv.org/html/2610.38361v1
24. Contracollective — *llms.txt for Ecommerce*（含 Adobe 34% 不可访问数据）
    https://contracollective.com/blog/llms-txt-for-ecommerce-agentic-commerce-discoverability-2026

### Agentic Commerce

25. Forter — *Agentic Transaction Data: What AI Agent Purchases Reveal*（2026-11-18）
    https://www.forter.com/blog/agentic-transaction-data/
26. ppc.land — *Agentic commerce*（含 HUMAN Security 7,851% / 2.31% 数据，2026-11-13）
    https://ppc.land/agentic-commerce
27. Digiday — *In Graphic Detail: Welcome to the agentic commerce quarter*（含 eMarketer / Gartner / Bain，2026-11-19）
    https://digiday.com/marketing/in-graphic-detail-welcome-to-the-agentic-commerce-quarter/
28. Glance — *Who Is Leading Agentic Commerce in 2026? Layer-by-Layer Map*（更新于 2026-11）
    https://glance.com/us/blogs/glanceai/business/agentic-commerce-leaders
29. Brandlight — *Agentic Commerce: What It Is and How It Works (2026 Guide)*
    https://brandlight.ai/blog/agentic-commerce
30. C9 Group — *Agentic Commerce 2026: What AI Shopping Agents Need*（事件时间线）
    https://c9group.dev/en/articles/agentic-commerce-ai-shopping-agents-store-guide
31. Global Payments / Worldpay — *The Agentic Commerce Report 2026*（7 国 8,027 人）
    https://wp-contentful-test-static-content.worldpay.com/acr/agentic-commerce-report-2026-med.pdf
32. SAPInsider — *Agentic Commerce Is Arriving: What Merchants Need to Know*
    https://sapinsider.org/map/agentic-commerce-arriving-consumer-openness-limits

### 流量与转化测量

33. Marie Haynes / SEO After AI — *ChatGPT sends 0.62% of what Google sends*（2026-10-21）
    https://seoafterai.com/ai-search/chatgpt-sends-0-62-of-what-google-sends/
34. Named / Khanex — *If ChatGPT sends almost no traffic, is AI visibility worth tracking?*（三研究对照）
    https://named.khanex.ai/blog/ai-visibility-vs-ai-traffic/
35. The SEO Works — *AI Assistant Referral Traffic and Conversion Performance Relative to Organic Search: A 12-Month Multi-Site Benchmark, 2025-2026*（Zenodo, 2026-09-29）
    https://doi.org/10.5281/zenodo.23040387
36. Kaiser & Schulze — *Frontiers: ChatGPT Referrals to E-Commerce Websites*，*Marketing Science* 45(4):699-715（2026）
    https://pubsonline.informs.org/doi/pdf/10.1287/mksc.2025.0489
37. Kaiser & Schulze — *Can Advertising Fund Free AI? Evidence from ChatGPT's International Advertising Rollout*（2026-10）
    https://ecommerceresearch.org/chatgpt-ads/Kaiser-Schulze-2026-Can-Advertising-Fund-Free-AI.pdf

---

*文档生成时间：2026-11-24 ｜ 数据截至：2026-11-24 ｜ 版本：v1.0*
