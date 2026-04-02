# 📝 Publications

**Note**: I attach repo / dataset / model / blog links below only when a public artifact can be confirmed reliably.

## 🤖 Coding Agents & Code Intelligence

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/paper_c3bench.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Evaluating and Achieving Controllable Code Completion in Code LLM**](https://arxiv.org/abs/2601.15879) \\
**Jiajun Zhang**, Zeyu Cui, Lei Zhang, Jian Yang, Jiaxi Yang, Qiang Liu, Zilei Wang, Binyuan Hui, Liang Wang, Junyang Lin

- **TL;DR**: We present C3-Bench, the first instruction-guided code completion benchmark with 2,195 tasks, revealing substantial gaps in instruction-following capabilities between open-source and proprietary models during code completion.
- **Overview**: This paper studies a practical but underexplored question in code completion: whether models can reliably follow explicit user control signals such as editing intent, coding style, structural constraints, and local context requirements. To answer this, we introduce a large-scale benchmark and analyze both evaluation and training strategies for controllable completion.
- **Highlights**: Beyond benchmarking, the work explores how controllability can be improved in real developer scenarios, showing that strong raw completion ability does not automatically translate to strong instruction following during tab-completion style generation.

[![arXiv](https://img.shields.io/badge/arXiv-2601.15879-b31b1b.svg)](https://arxiv.org/abs/2601.15879)

<details><summary>📖 BibTeX</summary>
<pre>
@article{zhang2026c3bench,
  title     = {Evaluating and Achieving Controllable Code Completion in Code LLM},
  author    = {Jiajun Zhang and Zeyu Cui and Lei Zhang and Jian Yang and Jiaxi Yang and Qiang Liu and Zilei Wang and Binyuan Hui and Liang Wang and Junyang Lin},
  journal   = {arXiv preprint arXiv:2601.15879},
  year      = {2026}
}
</pre>
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/paper_sri.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**From Completion to Editing: Unlocking Context-Aware Code Infilling via Search-and-Replace Instruction Tuning**](https://arxiv.org/abs/2601.13384) \\
**Jiajun Zhang**, Zeyu Cui, Jiaxi Yang, Lei Zhang, Yuheng Jing, Zeyao Ma, Tianyi Bai, Binyuan Hui, Qiang Liu, Zilei Wang, Liang Wang, Junyang Lin

- **TL;DR**: We propose Search-and-Replace Infilling (SRI), a framework that internalizes agentic verification-and-editing into a single-pass inference process, enabling Chat models to surpass the completion performance of their Base counterparts with minimal data.
- **Overview**: Instead of treating code infilling as a narrow span-filling problem, this work reframes it as context-aware editing with explicit search-and-replace operations. The resulting formulation better matches realistic coding workflows, where developers revise existing code under structural and semantic constraints rather than filling isolated blanks.
- **Highlights**: The paper shows that lightweight instruction tuning on carefully designed editing data can unlock much stronger infilling behavior, improve robustness under long-context settings, and better align the model with real IDE-assisted development patterns.

[![arXiv](https://img.shields.io/badge/arXiv-2601.13384-b31b1b.svg)](https://arxiv.org/abs/2601.13384)

<details><summary>📖 BibTeX</summary>
<pre>
@article{zhang2026sri,
  title     = {From Completion to Editing: Unlocking Context-Aware Code Infilling via Search-and-Replace Instruction Tuning},
  author    = {Jiajun Zhang and Zeyu Cui and Jiaxi Yang and Lei Zhang and Yuheng Jing and Zeyao Ma and Tianyi Bai and Binyuan Hui and Qiang Liu and Zilei Wang and Liang Wang and Junyang Lin},
  journal   = {arXiv preprint arXiv:2601.13384},
  year      = {2026}
}
</pre>
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/qwen_logo.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Scaling Agentic Verifier for Competitive Coding**](https://arxiv.org/abs/2602.04254) \\
Zeyao Ma, Jing Zhang, Xiaokang Zhang, Jiaxi Yang, Zongmeng Zhang, **Jiajun Zhang**, Yuheng Jing, Lei Zhang, Hao Zheng, Wenting Zhao, Junyang Lin, Binyuan Hui

- **TL;DR**: We study how to scale verifier-style agents for competitive coding and improve reliable solution selection through stronger execution-aware and agentic verification pipelines.
- **Overview**: Competitive coding is a demanding setting for LLM systems because correctness must be established under hidden tests rather than surface-level plausibility. This work focuses on verifier scaling, aiming to build stronger systems for candidate filtering, validation, and test-driven reasoning.
- **Highlights**: The paper is closely related to coding-agent training and evaluation, with practical implications for high-reliability code generation and automated programming competitions.

[![arXiv](https://img.shields.io/badge/arXiv-2602.04254-b31b1b.svg)](https://arxiv.org/abs/2602.04254)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/paper_sweflow.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**ExecRepoBench: Multi-level Executable Code Completion Evaluation**](https://arxiv.org/abs/2412.11990) \\
Jian Yang, **Jiajun Zhang**, Jiaxi Yang, Ke Jin, Lei Zhang, Qiyao Peng, Ken Deng, Yibo Miao, Tianyu Liu, Zeyu Cui, Binyuan Hui, Junyang Lin

- **TL;DR**: We introduce ExecRepoBench, an executable benchmark for repository-level code completion that evaluates models under more realistic completion settings than function-level static benchmarks.
- **Overview**: Repository-scale code completion requires models to reason over project context, dependencies, and executable behavior. This benchmark emphasizes multi-level evaluation and executable validation, making it more faithful to real developer usage.
- **Highlights**: The benchmark provides a stronger testbed for studying practical code completion systems, especially those designed for IDE workflows and repository-aware coding assistants.

[![arXiv](https://img.shields.io/badge/arXiv-2412.11990-b31b1b.svg)](https://arxiv.org/abs/2412.11990)
[![](https://img.shields.io/badge/Type-Benchmark-informational)](#)

</div>
</div>

## 📊 Visualization & Chart Generation

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/paper_plotcraft.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**RealChart2Code: Advancing Chart-to-Code Generation with Real Data and Multi-Task Evaluation**](https://arxiv.org/abs/2603.25804) \\
**Jiajun Zhang**, Yuying Li, Zhixun Li, Xingyu Guo, Jingzhuo Wu, Leqi Zheng, Yiran Yang, Jianke Zhang, Qingbin Li, Shannan Yan, Zhetong Li, Changguo Jia, Junfei Wu, Zilei Wang, Qiang Liu, Liang Wang

- **TL;DR**: We introduce RealChart2Code, a large-scale benchmark with more than 2,800 real-data chart generation tasks that evaluates both direct chart synthesis and multi-turn code refinement for complex visualizations.
- **Overview**: This work studies chart-to-code generation under realistic conditions, where models must reproduce intricate multi-panel visualizations from authentic datasets instead of simplified synthetic chart templates. The benchmark emphasizes analytical intent, real data grounding, and iterative refinement in conversational settings.
- **Highlights**: Our evaluation of 14 leading VLMs reveals a large gap between current capabilities and real-world visualization demands, especially on complex plot structures, raw-data-driven charting, and multi-turn correction scenarios.

[![arXiv](https://img.shields.io/badge/arXiv-2603.25804-b31b1b.svg)](https://arxiv.org/abs/2603.25804)
[![](https://img.shields.io/badge/Type-Benchmark-informational)](#)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/paper_plotcraft.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**PlotCraft: Pushing the Limits of LLMs for Complex and Interactive Data Visualization**](https://arxiv.org/abs/2511.00010) \\
**Jiajun Zhang**, Jianke Zhang, Zeyu Cui, Jiaxi Yang, Lei Zhang, Binyuan Hui, Qiang Liu, Zilei Wang, Liang Wang, Junyang Lin

- **TL;DR**: We introduce PlotCraft, a benchmark with 1k challenging visualization tasks across 48 chart types, and develop PlotCraftor, a compact model achieving performance comparable to leading proprietary approaches with over 50% improvement on hard tasks.
- **Overview**: PlotCraft targets a difficult frontier for multimodal code generation: producing complex, interactive, and aesthetically coherent visualization code from user intent. The benchmark emphasizes realistic chart authoring challenges, including diverse plotting grammars, intricate layout requirements, and interaction-heavy scenarios that are poorly covered by existing datasets.
- **Highlights**: In addition to defining the benchmark, the paper presents a practical modeling pipeline for chart-code generation and demonstrates that carefully curated task design plus domain-focused training can push open models much closer to high-end proprietary systems.

[![arXiv](https://img.shields.io/badge/arXiv-2511.00010-b31b1b.svg)](https://arxiv.org/abs/2511.00010)
[![](https://img.shields.io/github/stars/Speakn0w/PlotCraft-Benchmark?style=social&label=Repo)](https://github.com/Speakn0w/PlotCraft-Benchmark)

</div>
</div>

## 🛠️ Software Engineering & Infrastructure

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/paper_sweflow.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SWE-Flow: Synthesizing Software Engineering Data in a Test-Driven Manner**](https://arxiv.org/abs/2506.09003) \\
Lei Zhang, Jiaxi Yang, Min Yang, Jian Yang, Mouxiang Chen, **Jiajun Zhang**, Zeyu Cui, Binyuan Hui, Junyang Lin

- **TL;DR**: We present SWE-Flow, a TDD-grounded data synthesis framework that constructs Runtime Dependency Graphs to generate step-by-step development tasks, producing 16k training instances from real-world GitHub projects with significant fine-tuning gains.
- **Overview**: This work addresses the scarcity of high-quality software engineering supervision for LLMs by synthesizing executable development trajectories from real repositories. By grounding task construction in tests, runtime dependencies, and realistic implementation steps, SWE-Flow moves beyond static instruction data toward process-aware engineering data.
- **Highlights**: The framework is especially valuable for training coding agents and SWE-oriented models, because it captures the sequential structure of debugging, implementation, and verification rather than only final code outputs.

[![arXiv](https://img.shields.io/badge/arXiv-2506.09003-b31b1b.svg)](https://arxiv.org/abs/2506.09003)
[![](https://img.shields.io/badge/Type-Data%20Synthesis-informational)](#)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/qwen_logo.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MegaFlow: Large-Scale Distributed Orchestration System for the Agentic Era**](https://arxiv.org/abs/2601.07526) \\
Lei Zhang, Mouxiang Chen, Ruisheng Cao, Jiawei Chen, Fan Zhou, Yiheng Xu, Jiaxi Yang, Liang Chen, Changwei Luo, Kai Zhang, Fan Yan, KaShun Shum, **Jiajun Zhang**, Zeyu Cui, Hu Feng, Junyang Lin, Binyuan Hui, Min Yang

- **TL;DR**: We present MegaFlow, a large-scale distributed orchestration system designed for the agentic era, supporting scalable multi-agent execution, coordination, and workflow management.
- **Overview**: As coding agents grow more capable, their supporting infrastructure becomes a central bottleneck. MegaFlow addresses this systems challenge by providing orchestration mechanisms for large-scale agent execution and task coordination.
- **Highlights**: The work complements model-centric research by focusing on the infrastructure layer required to run agentic systems at scale in realistic engineering environments.

[![arXiv](https://img.shields.io/badge/arXiv-2601.07526-b31b1b.svg)](https://arxiv.org/abs/2601.07526)

</div>
</div>

## 🔍 Retrieval, Recommendation & Information Systems

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/paper_citation.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**What Should I Cite? A RAG Benchmark for Academic Citation Prediction**](https://arxiv.org/abs/2601.14949) \\
Leqi Zheng, **Jiajun Zhang**, Canzhi Chen, Chaokun Wang, Hongwei Li, Yuying Li, Yaoxin Mao, Shannan Yan, Zixin Song, Zhiyuan Feng, Zhaolu Kang, Zirong Chen, Hang Zhang, Qiang Liu, Liang Wang, Ziyang Liu

- **TL;DR**: We build a benchmark for academic citation prediction and study how retrieval-augmented generation can recommend faithful and relevant references, using multi-level retrieval and specialized citation generators that reduce hallucinated citations from 17.4% to 4.9%.
- **Overview**: Citation prediction is a challenging academic assistant task that requires both document understanding and trustworthy retrieval. This paper formalizes the problem under a RAG setting, where systems must identify suitable references for a given scientific context while avoiding fabricated or weakly grounded citations.
- **Highlights**: The study provides both a benchmark and strong baselines for evaluating faithfulness in scholarly assistance, making it relevant to academic search, scientific writing copilots, and evidence-grounded long-form generation.

[![arXiv](https://img.shields.io/badge/arXiv-2601.14949-b31b1b.svg)](https://arxiv.org/abs/2601.14949)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/paper_sdcgcl.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Negative Feedback Really Matters: Signed Dual-Channel Graph Contrastive Learning Framework for Recommendation**](https://openreview.net/forum?id=eQ79kT0QY1) \\
Leqi Zheng, Chaokun Wang, Zixin Song, Cheng Wu, Shannan Yan, **Jiajun Zhang**, Ziyang Liu

- **TL;DR**: We propose SDCGCL, a model-agnostic signed dual-channel graph contrastive learning framework that effectively leverages negative feedback for recommendation, consistently outperforming 22 SOTA baselines.
- **Overview**: Most recommendation models primarily exploit positive user-item interactions, while negative signals are either discarded or used only superficially. This paper argues that negative feedback carries essential structural information and designs a signed graph contrastive framework to model it explicitly.
- **Highlights**: The result is a general recommendation approach that improves representation quality and ranking effectiveness, while also providing a cleaner perspective on how contrastive learning should be adapted when user preferences include both attraction and rejection signals.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 Findings</div><img src='images/paper_lagcl4rec.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**LAGCL4Rec: When LLMs Activate Interactions Potential in Graph Contrastive Learning for Recommendation**](https://aclanthology.org/2025.findings-emnlp.61/) \\
Leqi Zheng, Chaokun Wang, Canzhi Chen, **Jiajun Zhang**, Cheng Wu, Zixin Song, Shannan Yan, Ziyang Liu, Hongwei Li

- **TL;DR**: We propose LAGCL4Rec, a progressive activation pipeline that leverages LLMs to activate interaction potential in graph contrastive learning for recommendation at data, rank, and rerank levels.
- **Overview**: This work investigates how LLMs can serve as more than text generators in recommender systems. Instead, they are used as high-level reasoning modules that enrich graph-based recommendation pipelines through data activation, candidate refinement, and reranking.
- **Highlights**: The paper connects LLM reasoning with graph representation learning in a practical recommendation setting, showing how language priors can complement sparse interaction graphs and improve downstream recommendation quality.

</div>
</div>

## 🌐 Multimodal, Vision & Agents

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src='images/paper_plotcraft.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**VLM4VLA: Revisiting Vision-Language-Models in Vision-Language-Action Models**](https://openreview.net/) \\
Jianke Zhang, Xiaoyu Chen, Qiuyue Wang, Mingsheng Li, Yanjiang Guo, Yucheng Hu, **Jiajun Zhang**, Shuai Bai, Junyang Lin, Jianyu Chen

- **TL;DR**: We revisit the role of vision-language models in vision-language-action systems and study how VLM components affect embodied policy learning.
- **Overview**: This work connects multimodal representation learning with downstream action-oriented systems, asking how much modern VLMs can contribute when integrated into VLA pipelines.
- **Highlights**: The paper is relevant to embodied intelligence, multimodal reasoning, and the transfer of VLM capabilities into agentic decision-making settings.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/paper_plotcraft.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Learning Cross-View Object Correspondence via Cycle-Consistent Mask Prediction**](https://openaccess.thecvf.com/) \\
Shannan Yan, Leqi Zheng, Keyu Lv, Jingchen Ni, Hongyang Wei, **Jiajun Zhang**, Guangting Wang, Jing Lyu, Chun Yuan, Fengyun Rao

- **TL;DR**: We study cross-view object correspondence through cycle-consistent mask prediction to improve robust geometric and semantic matching across views.
- **Overview**: The paper targets a core vision problem: aligning objects seen from different viewpoints with stronger consistency constraints.
- **Highlights**: The method combines structural reasoning and mask-level correspondence learning to improve cross-view matching quality.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2026</div><img src='images/paper_citation.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SAMAS: A Spectrum-Guided Multi-Agent System for Achieving Style Fidelity in Literary Translation**](https://ieeexplore.ieee.org/) \\
Jingzhuo Wu, **Jiajun Zhang**, Keyan Jin, Dehua Ma, Junbo Wang

- **TL;DR**: We propose SAMAS, a multi-agent system for literary translation that explicitly balances semantic faithfulness and stylistic fidelity.
- **Overview**: Literary translation requires more than literal correctness; it also demands style preservation. SAMAS uses a spectrum-guided multi-agent formulation to coordinate translation quality along these dimensions.
- **Highlights**: The work brings multi-agent methodology into translation and style-sensitive generation, extending LLM systems beyond coding and retrieval tasks.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/paper_citation.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**AdaMem: Adaptive User-Centric Memory for Long-Horizon Dialogue Agents**](#) \\
Shannan Yan, Jingchen Ni, Leqi Zheng, **Jiajun Zhang**, Peng Wu, Deying Yin, Jing Lyu, Chun Yuan, Fengyun Rao

- **TL;DR**: We study adaptive user-centric memory for dialogue agents to support longer-horizon personalization and contextual coherence.
- **Overview**: Long-horizon dialogue systems require memory mechanisms that can track user preferences and conversational state over time without drifting or overfitting.
- **Highlights**: This work explores memory design for agentic dialogue systems, a direction that complements your broader interest in practical and reliable LLM agents.

</div>
</div>

## 📰 Information Integrity

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/paper_fade.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Evolving to the Future: Unseen Event Adaptive Fake News Detection on Social Media**](https://arxiv.org/abs/2403.00037) \\
**Jiajun Zhang**, Zhixun Li, Qiang Liu, Shu Wu, Liang Wang

- **TL;DR**: We introduce FADE, a future-adaptive fake news detection framework that leverages adaptive augmentation and graph contrastive learning to generalize to unseen events on social media.
- **Overview**: Fake news detectors often overfit to event-specific patterns and degrade sharply when facing emerging topics. FADE tackles this challenge by explicitly modeling event shift and improving generalization to previously unseen news events.
- **Highlights**: The paper combines adaptation and graph learning to strengthen robustness under temporal and topical drift, making it a practical step toward more deployable misinformation detection systems.

[![arXiv](https://img.shields.io/badge/arXiv-2403.00037-b31b1b.svg)](https://arxiv.org/abs/2403.00037)

</div>
</div>

## 📊 Technical Reports & Surveys

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/qwen_logo.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Qwen3-Coder-Next Technical Report**](https://arxiv.org/abs/2603.00729) \\
Qwen Team, with **Jiajun Zhang (Speakn0w)** as a major contributor

- **TL;DR**: We present Qwen3-Coder-Next, an open-weight coding-agent model trained with large-scale verifiable coding tasks, executable environments, mid-training, and reinforcement learning.
- **Overview**: This report describes the data, training pipeline, and agent-oriented evaluation behind Qwen3-Coder-Next, focusing on strong real-world coding performance and scalable open release.
- **Highlights**: As a major contributor under the handle **Speakn0w**, I contributed to the report release, open-source repository, and model ecosystem around this launch.

[![arXiv](https://img.shields.io/badge/arXiv-2603.00729-b31b1b.svg)](https://arxiv.org/abs/2603.00729)
[![](https://img.shields.io/github/stars/QwenLM/Qwen3-Coder?style=social&label=Repo)](https://github.com/QwenLM/Qwen3-Coder/)
[![Model](https://img.shields.io/badge/🤗-Qwen3--Coder--Next-yellow)](https://huggingface.co/Qwen/Qwen3-Coder-Next)
[![Blog](https://img.shields.io/badge/Blog-Qwen3--Coder--Next-blue)](https://qwen.ai/blog?id=qwen3-coder-next)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/paper_ci_survey.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**From Code Foundation Models to Agents and Applications: A Comprehensive Survey and Practical Guide to Code Intelligence**](https://arxiv.org/abs/2511.18538) \\
Jian Yang, ..., **Jiajun Zhang**, ..., and 70+ authors

- **TL;DR**: A comprehensive synthesis and practical guide about code LLMs, systematically examining the complete model life cycle from data curation through advanced prompting, code pre-training, SFT, RL, and autonomous coding agents.
- **Overview**: This survey provides a broad map of the rapidly evolving code intelligence landscape, connecting foundation models, coding assistants, evaluation, training recipes, and agentic systems in a single framework.
- **Highlights**: It is designed not only as a literature review, but also as a practical guide for researchers and practitioners who want to understand how modern code LLM systems are built, evaluated, and deployed.

[![arXiv](https://img.shields.io/badge/arXiv-2511.18538-b31b1b.svg)](https://arxiv.org/abs/2511.18538)
[![](https://img.shields.io/badge/Type-Survey-informational)](#)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2024</div><img src='images/paper_qwen25coder.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Qwen2.5-Coder Technical Report**](https://arxiv.org/abs/2409.12186) \\
Binyuan Hui\*, Jian Yang\*, Zeyu Cui, Jiaxi Yang, Dayiheng Liu, Lei Zhang, Tianyu Liu, **Jiajun Zhang**, Bowen Yu, Keming Lu, Kai Dang, Yang Fan, Yichang Zhang, An Yang, Rui Men, Fei Huang, Bo Zheng, Yibo Miao, Shanghaoran Quan, Yunlong Feng, Xingzhang Ren, Xuancheng Ren, Jingren Zhou, Junyang Lin

- **TL;DR**: We introduce the Qwen2.5-Coder series (0.5B to 32B), built upon Qwen2.5 with 5.5T tokens of code data, achieving SOTA performance across 10+ code benchmarks including generation, completion, reasoning, and repair.
- **Overview**: This technical report describes the design and training of the Qwen2.5-Coder family, covering model scaling, code-centric data construction, training strategy, and broad benchmark evaluation across major coding tasks.
- **Highlights**: The report demonstrates how large-scale code pretraining plus strong evaluation discipline can produce open coding models that are competitive across generation, completion, reasoning, and repair.

[![arXiv](https://img.shields.io/badge/arXiv-2409.12186-b31b1b.svg)](https://arxiv.org/abs/2409.12186)
[![](https://img.shields.io/badge/Type-Technical%20Report-informational)](#)

</div>
</div>
