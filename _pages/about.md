---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

<div class="cv-intro">
  <p class="cv-kicker">ACADEMIC CV · 2026</p>
  <h1>高特 <span class="cv-name-en">Te Gao</span></h1>
  <p class="cv-lede">中南大学计算机科学与技术本科生，关注让语言模型更可靠地思考、检索与使用工具。</p>
  <div class="cv-actions">
    <a class="cv-button" href="mailto:marsdon.gao@mail.com">联系我 <span aria-hidden="true">↗</span></a>
    <a class="cv-text-link" href="https://github.com/GoatCsu">GitHub</a>
    <a class="cv-text-link" href="https://scholar.google.com/citations?user=fmK1DrBEd8MC&amp;hl=zh-CN">Google Scholar</a>
    <a class="cv-text-link" href="#" onclick="window.print(); return false;">打印 / 导出 PDF <span aria-hidden="true">↓</span></a>
  </div>
</div>

<div class="cv-facts">
  <div><span class="cv-label">教育</span><strong>中南大学</strong><small>计算机科学与技术 · 2024—2028</small></div>
  <div><span class="cv-label">目前</span><strong>上海交通大学 APEX 实验室</strong><small>Research Assistant · 2025.06—至今</small></div>
  <div><span class="cv-label">研究主题</span><strong>Agents · Memory · Reasoning</strong><small>Search · Tool-use · Post-training · VLM</small></div>
</div>

# 研究简介

我是 **Te Gao（高特）**，中南大学计算机科学与技术专业本科生。目前在**上海交通大学 APEX 实验室**从事研究，主要关注语言模型智能体、记忆与工具使用，也参与长视频理解和长链推理相关研究。

我喜欢把研究问题落到可复现的系统与评测上：从数据和工作流搭建，到基线复现、统计分析与结果验证。

# 近期动态

- **2026** · 参与的科研智能体与学术会议分母博弈 position paper 发表于 **ICML 2026 Position**，共同第一作者。
- **2026** · 参与的 LLM 搜索智能体综述发表于 **ACL 2026 Main Conference**。
- **2025** · 参与的 Long-CoT 综述发表于 *Science China Information Sciences*，获 LMG Best Poster。
- **2025** · 牵头 **LLMs-from-scratch-CN** 中文翻译与校对，项目累计 2.5k+ GitHub stars。

# 论文

<div class='cv-publication'>
  <div class='cv-pub-meta'><span>ACL 2026</span><span>MAIN CONFERENCE</span></div>
  <div><h3><a href="https://arxiv.org/abs/2508.05668">A Survey of Large Language Model-Based Search Agents</a></h3><p>Yunjia Xi, Jianghao Lin, …, Te Gao, …, Weinan Zhang</p><p>贡献：评测基准整理、复现统计分析与文献表格化整理。</p></div>
</div>

<div class='cv-publication'>
  <div class='cv-pub-meta'><span>ICML 2026</span><span>POSITION · CO-FIRST</span></div>
  <div><h3>Academic Conferences are Potentially Facing Denominator Gaming Caused by Fully Automated Scientific Agents</h3><p>Rong Shan*, Te Gao*, …, Jianghao Lin</p><p>贡献：实验设置对照、统计分析与结果整理。</p></div>
</div>

<div class='cv-publication'>
  <div class='cv-pub-meta'><span>SCIS</span><span>RESEARCH SURVEY</span></div>
  <div><h3><a href="https://arxiv.org/abs/2503.09567">Towards Reasoning Era: A Survey of Long Chain-of-Thought for Reasoning Large Language Models</a></h3><p>Qiguang Chen, Libo Qin, …, Te Gao, Wanxiang Che</p><p>贡献：Long-CoT 分类学整理、文献整理总结与表格维护。</p></div>
</div>

<div class='cv-publication'>
  <div class='cv-pub-meta'><span>ACM MM 2025</span><span>CCF-A</span></div>
  <div><h3><a href="https://arxiv.org/abs/2511.05034">Dynamic Residual Encoding for End-to-End WSI Representation</a></h3><p>贡献：复现与优化 Dynamic Residual Encoding，设计消融实验并完成多数据集对比。</p></div>
</div>

# 研究经历

## Multi-Agent 协作的记忆蒸馏

**上海交通大学 APEX 实验室** · Research Assistant <span class="cv-date">2025.11—至今</span>

- 设计 Multi-Teacher → Student 蒸馏范式，搭建 LangChain / Smolagents 插件化 Agent 工作流，支持任务拆解、工具规划与决策能力研究。
- 构建 Neo4j Graph RAG 与记忆模块，引入基于 entropy 的冲突过滤，提升长上下文场景的召回一致性。
- 在 GAIA Benchmark 上，Qwen2.5-7B Pass@1 从 **43.6 提升至 57.0**，Teacher 使用 GPT-4o。

## 学术会议分母博弈与科研智能体安全

**上海交通大学 APEX 实验室** · Research Assistant <span class="cv-date">2025.06—2025.11</span>

- 围绕 Agentic Denominator Gaming，分析投稿量增长、录用率稳定与科研智能体自动化之间的结构性风险。
- 参与威胁模型与论证框架设计，研究自动化生成与投稿对评审负载和学术信任的潜在影响；相关工作发表于 ICML 2026 Position。

## 长视频推理增强与多模态证据链理解

**中南大学 Text Intelligence 实验室** · Research Assistant <span class="cv-date">2024.11—2025.05</span>

- 设计两阶段推理 Pipeline：关键帧动态补全与视觉证据链构建，提升复杂长视频任务的推理深度与可解释性。
- 在 VideoEspresso 上，开源模型平均准确率提升 **3.0%**，闭源模型提升 **2.3%**。
- 相关专利：基于多模态证据链的视频理解方法及系统，申请号 **202511689594.6**。

# 开源与项目

## [LLMs-from-scratch-CN](https://github.com/MLNLP-World/LLMs-from-scratch-CN) · 项目负责人

牵头中文翻译与校对，补充论文背景和实现细节，协调项目维护；项目累计 **2.5k+ stars**。

# 荣誉与竞赛

- **全国大学生软件创新大赛二等奖** · 主要负责人 · 2025.05
- **中国大学生服务外包创新创业大赛三等奖** · 技术负责人 · 2025.06
- **LMG Best Poster** · *Science China Information Sciences* · 2025

# 技能

**Agent 与检索**　LangChain、Smolagents、Agent Workflow、FAISS、Milvus、Neo4j、Graph RAG  
**训练与推理**　PyTorch、Accelerate、verl、SFT / DPO、PPO / GRPO、bf16 / fp16、FlashAttention、vLLM、FastAPI  
**语言**　英语六级 626，英语四级 584

<div class="cv-footer-note">持续探索可信赖的智能体系统。欢迎交流研究、合作与实习机会。</div>
