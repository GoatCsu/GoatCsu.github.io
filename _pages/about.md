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

I am **Te Gao (高特)**, an undergraduate student in Computer Science and Technology at **Central South University**. My research focuses on **LLM Agents** including search, memory, tool-use, and workflow, together with **post-training**, **LLM reasoning**, and **vision-language models**.

I am currently a Research Assistant at **SJTU APEX Lab**, where I work on multi-agent memory distillation. I was also a research assistant in **Text Intelligence**, advised by LiBo Qin, working on long-video understanding and long chain-of-thought reasoning.

**Research interests:** LLM Agents, Search Agents, Memory Distillation, Tool-use, Agent Workflow, Post-training, Long-CoT Reasoning, VLM, Graph RAG.

# 🔥 News
- *2026*: One paper accepted to **ACL 2026 Main Conference**.
- *2026*: One co-first position paper accepted to **ICML 2026 Position**.
- *2025*: One paper accepted to **ACM Multimedia 2025**.
- *2025*: Long-CoT survey received **LMG Best Poster** at Science China Information Sciences.
- *2025*: Led the Chinese translation and review project **LLMs-from-scratch-CN**, which received **2.5k+ GitHub stars**.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026 Main</div><img src='images/search-agents.svg' alt="Search agents overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Survey of LLM-Based Search Agents](https://arxiv.org/abs/2508.05668)

**ACL 2026 Main Conference**, Accepted.

[**arXiv**](https://arxiv.org/abs/2508.05668)

- Contributions: benchmark organization; reproduction and statistical analysis; literature crawling, screening, and table-based summarization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/agent-science.svg' alt="Automated scientific agents" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Position: Denominator Gaming by Automated Scientific Agents

**ICML 2026 Position**, Accepted. **Co-first author**.

- Contributions: experiment setup and controls; statistical analysis; experiment framework collaboration and result organization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/wsi-dre.svg' alt="Dynamic residual encoding for WSI" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamic Residual Encoding for End-to-End WSI Representation](https://arxiv.org/abs/2511.05034)

**ACM Multimedia 2025**, CCF-A, Accepted.

[**arXiv**](https://arxiv.org/abs/2511.05034)

- Contributions: reproduced and optimized Dynamic Residual Encoding; designed ablation studies and completed multi-dataset comparisons.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SCIS</div><img src='images/long-cot.svg' alt="Long chain-of-thought reasoning survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Reasoning Era: Long-CoT Survey](https://arxiv.org/abs/2503.09567)

**Science China Information Sciences**, LMG Best Poster.

[**arXiv**](https://arxiv.org/abs/2503.09567) / [**Project**](https://long-cot.github.io/) / [**Code**](https://github.com/LightChen233/Awesome-Long-Chain-of-Thought-Reasoning)

- Impact: 100+ Google Scholar citations.
- Contributions: Long-CoT taxonomy; literature summary and table maintenance; updated 250+ references.
</div>
</div>

# 🔬 Research Experience

## Shanghai Jiao Tong University APEX Lab · Research Assistant
*2025.06 - Present*  
**Multi-Agent collaborative memory distillation: Multi-Teacher → Student**

- Designed a Multi-Teacher → Student distillation paradigm where multiple teacher LLMs collaboratively generate reasoning trajectories to improve student capabilities in task decomposition, tool planning, and decision-making.
- Built a plugin-style agent workflow with LangChain and Smolagents for retrieval, trajectory generation, filtering, replay, and evaluation, supporting rapid replacement of teachers, students, tools, and task configurations.
- Constructed a Neo4j Graph RAG memory module with entropy-based conflict filtering to improve recall consistency and memory retention in long-context scenarios.
- On GAIA Benchmark, improved Qwen2.5-7B without fine-tuning from Pass@1 43.6 to 57.0 (+13.4), using GPT-4o as teacher.

## Text Intelligence · LiBo Qin Group
*2024.11 - 2025.05*  
**Long-video understanding, reasoning enhancement, and long chain-of-thought**

- Designed a two-stage reasoning pipeline with dynamic keyframe completion and visual evidence-chain construction to improve reasoning depth and interpretability for complex long-video tasks.
- Aligned fine-grained visual features with textual logic chains to reduce hallucination and detail conflicts in long-video analysis.
- Improved average accuracy on **VideoEspresso** by **+3.0%** for open-source models and **+2.3%** for closed-source models.

# 💻 Open Source and Projects

## [LLMs-from-scratch-CN](https://github.com/MLNLP-World/LLMs-from-scratch-CN) · Project Lead
*2025.01 - 2025.04*

Led the Chinese translation and review of *LLM From Scratch*, supplemented paper background and implementation details, and coordinated project maintenance. The project has received **2.5k+ stars**.

# 🎖 Honors and Awards
- *2025.06* National Third Prize, Service Outsourcing Innovation and Entrepreneurship Competition, Technical Lead.
- *2025.05* National Final Second Prize, National College Student Software Innovation Competition, Team Leader.
- *2025* LMG Best Poster, Science China Information Sciences.

# 📖 Education
- *2024.09 - 2028.06 expected*, **Central South University** (985 / Double First-Class), B.S. in Computer Science and Technology.

# 🛠 Skills
- **Training and Alignment:** PyTorch, Transformers, Accelerate, verl, TRL, SFT, DPO, PPO, GRPO, gradient checkpointing, bf16/fp16, FlashAttention.
- **Inference and Serving:** vLLM offline batch inference, online serving, agent backend, FastAPI.
- **Agents and RAG:** LangChain, Smolagents, agent workflow orchestration, tool-use, FAISS, Milvus, Neo4j, Graph RAG, HF Datasets, WebDataset, data cleaning, deduplication, synthetic data, instruction construction, rule-based and LLM labeling.
- **Evaluation and Engineering:** GAIA, MMLU, GSM8K, HumanEval, MT-Bench, Arena, Ray, Linux, Git, Docker, refusal and safety filtering, prompt templating, OpenClaude application and modification, C++, Java.
- **Languages:** CET-4 **584**, CET-6 **626**.

# 📫 Contact
- Email: [marsdon.gao@mail.com](mailto:marsdon.gao@mail.com) / [8208241315@csu.edu.cn](mailto:8208241315@csu.edu.cn)
- GitHub: [github.com/GoatCsu](https://github.com/GoatCsu)
