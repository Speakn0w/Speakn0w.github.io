# 📝 Publications

## 🖥️ Code Intelligence

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2026</div><img src='images/paper_plotcraft.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**RealChart2Code: Advancing Chart-to-Code Generation with Real Data and Multi-Task Evaluation**](https://arxiv.org/abs/2603.25804) \
**Jiajun Zhang**, Yuying Li, Zhixun Li, Xingyu Guo, Jingzhuo Wu, Leqi Zheng, Yiran Yang, Jianke Zhang, Qingbin Li, Shannan Yan, Zhetong Li, Changguo Jia, Junfei Wu, Zilei Wang, Qiang Liu, Liang Wang

- **TL;DR**: We introduce RealChart2Code, a large-scale benchmark with more than 2,800 real-data chart generation tasks that evaluates both direct chart synthesis and multi-turn code refinement for complex visualizations.
- **Overview**: This work studies chart-to-code generation under realistic conditions, where models must reproduce intricate multi-panel visualizations from authentic datasets instead of simplified synthetic chart templates. The benchmark emphasizes analytical intent, real data grounding, and iterative refinement in conversational settings.
- **Highlights**: Our evaluation of 14 leading VLMs reveals a large gap between current capabilities and real-world visualization demands, especially on complex plot structures, raw-data-driven charting, and multi-turn correction scenarios.

[![arXiv](https://img.shields.io/badge/arXiv-2603.25804-b31b1b.svg)](https://arxiv.org/abs/2603.25804)

<details><summary>📖 BibTeX</summary>
<pre>
@article{zhang2026realchart2code,
  title     = {RealChart2Code: Advancing Chart-to-Code Generation with Real Data and Multi-Task Evaluation},
  author    = {Jiajun Zhang and Yuying Li and Zhixun Li and Xingyu Guo and Jingzhuo Wu and Leqi Zheng and Yiran Yang and Jianke Zhang and Qingbin Li and Shannan Yan and Zhetong Li and Changguo Jia and Junfei Wu and Zilei Wang and Qiang Liu and Liang Wang},
  journal   = {arXiv preprint arXiv:2603.25804},
  year      = {2026}
}
</pre>
</details>

</div>
</div>

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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/paper_plotcraft.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**PlotCraft: Pushing the Limits of LLMs for Complex and Interactive Data Visualization**](https://arxiv.org/abs/2511.00010) \\
**Jiajun Zhang**, Jianke Zhang, Zeyu Cui, Jiaxi Yang, Lei Zhang, Binyuan Hui, Qiang Liu, Zilei Wang, Liang Wang, Junyang Lin

- **TL;DR**: We introduce PlotCraft, a benchmark with 1k challenging visualization tasks across 48 chart types, and develop PlotCraftor, a compact model achieving performance comparable to leading proprietary approaches with over 50% improvement on hard tasks.
- **Overview**: PlotCraft targets a difficult frontier for multimodal code generation: producing complex, interactive, and aesthetically coherent visualization code from user intent. The benchmark emphasizes realistic chart authoring challenges, including diverse plotting grammars, intricate layout requirements, and interaction-heavy scenarios that are poorly covered by existing datasets.
- **Highlights**: In addition to defining the benchmark, the paper presents a practical modeling pipeline for chart-code generation and demonstrates that carefully curated task design plus domain-focused training can push open models much closer to high-end proprietary systems.

[![arXiv](https://img.shields.io/badge/arXiv-2511.00010-b31b1b.svg)](https://arxiv.org/abs/2511.00010)
[![](https://img.shields.io/github/stars/Speakn0w/PlotCraft-Benchmark?style=social&label=Repo)](https://github.com/Speakn0w/PlotCraft-Benchmark)

<details><summary>📖 BibTeX</summary>
<pre>
@article{zhang2025plotcraft,
  title     = {PlotCraft: Pushing the Limits of LLMs for Complex and Interactive Data Visualization},
  author    = {Jiajun Zhang and Jianke Zhang and Zeyu Cui and Jiaxi Yang and Lei Zhang and Binyuan Hui and Qiang Liu and Zilei Wang and Liang Wang and Junyang Lin},
  journal   = {arXiv preprint arXiv:2511.00010},
  year      = {2025}
}
</pre>
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/paper_sweflow.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SWE-Flow: Synthesizing Software Engineering Data in a Test-Driven Manner**](https://arxiv.org/abs/2506.09003) \\
Lei Zhang, Jiaxi Yang, Min Yang, Jian Yang, Mouxiang Chen, **Jiajun Zhang**, Zeyu Cui, Binyuan Hui, Junyang Lin

- **TL;DR**: We present SWE-Flow, a TDD-grounded data synthesis framework that constructs Runtime Dependency Graphs to generate step-by-step development tasks, producing 16k training instances from real-world GitHub projects with significant fine-tuning gains.
- **Overview**: This work addresses the scarcity of high-quality software engineering supervision for LLMs by synthesizing executable development trajectories from real repositories. By grounding task construction in tests, runtime dependencies, and realistic implementation steps, SWE-Flow moves beyond static instruction data toward process-aware engineering data.
- **Highlights**: The framework is especially valuable for training coding agents and SWE-oriented models, because it captures the sequential structure of debugging, implementation, and verification rather than only final code outputs.

[![arXiv](https://img.shields.io/badge/arXiv-2506.09003-b31b1b.svg)](https://arxiv.org/abs/2506.09003)

<details><summary>📖 BibTeX</summary>
<pre>
@inproceedings{zhang2025sweflow,
  title     = {SWE-Flow: Synthesizing Software Engineering Data in a Test-Driven Manner},
  author    = {Lei Zhang and Jiaxi Yang and Min Yang and Jian Yang and Mouxiang Chen and Jiajun Zhang and Zeyu Cui and Binyuan Hui and Junyang Lin},
  booktitle = {Proceedings of the 42nd International Conference on Machine Learning (ICML)},
  year      = {2025}
}
</pre>
</details>

</div>
</div>

## 🔍 Search and Graph

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src='images/paper_citation.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**What Should I Cite? A RAG Benchmark for Academic Citation Prediction**](https://arxiv.org/abs/2601.14949) \\
Leqi Zheng, **Jiajun Zhang**, Canzhi Chen, Chaokun Wang, Hongwei Li, Yuying Li, Yaoxin Mao, Shannan Yan, Zixin Song, Zhiyuan Feng, Zhaolu Kang, Zirong Chen, Hang Zhang, Qiang Liu, Liang Wang, Ziyang Liu

- **TL;DR**: We build a benchmark for academic citation prediction and study how retrieval-augmented generation can recommend faithful and relevant references, using multi-level retrieval and specialized citation generators that reduce hallucinated citations from 17.4% to 4.9%.
- **Overview**: Citation prediction is a challenging academic assistant task that requires both document understanding and trustworthy retrieval. This paper formalizes the problem under a RAG setting, where systems must identify suitable references for a given scientific context while avoiding fabricated or weakly grounded citations.
- **Highlights**: The study provides both a benchmark and strong baselines for evaluating faithfulness in scholarly assistance, making it relevant to academic search, scientific writing copilots, and evidence-grounded long-form generation.

[![arXiv](https://img.shields.io/badge/arXiv-2601.14949-b31b1b.svg)](https://arxiv.org/abs/2601.14949)

<details><summary>📖 BibTeX</summary>
<pre>
@article{zheng2026citation,
  title     = {What Should I Cite? A RAG Benchmark for Academic Citation Prediction},
  author    = {Leqi Zheng and Jiajun Zhang and Canzhi Chen and Ziyang Liu},
  journal   = {arXiv preprint arXiv:2601.14949},
  year      = {2026}
}
</pre>
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='images/paper_sdcgcl.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Negative Feedback Really Matters: Signed Dual-Channel Graph Contrastive Learning Framework for Recommendation**](https://openreview.net/forum?id=eQ79kT0QY1) \\
Leqi Zheng, Chaokun Wang, Zixin Song, Cheng Wu, Shannan Yan, **Jiajun Zhang**, Ziyang Liu

- **TL;DR**: We propose SDCGCL, a model-agnostic signed dual-channel graph contrastive learning framework that effectively leverages negative feedback for recommendation, consistently outperforming 22 SOTA baselines.
- **Overview**: Most recommendation models primarily exploit positive user-item interactions, while negative signals are either discarded or used only superficially. This paper argues that negative feedback carries essential structural information and designs a signed graph contrastive framework to model it explicitly.
- **Highlights**: The result is a general recommendation approach that improves representation quality and ranking effectiveness, while also providing a cleaner perspective on how contrastive learning should be adapted when user preferences include both attraction and rejection signals.

<details><summary>📖 BibTeX</summary>
<pre>
@inproceedings{zheng2025sdcgcl,
  title     = {Negative Feedback Really Matters: Signed Dual-Channel Graph Contrastive Learning Framework for Recommendation},
  author    = {Leqi Zheng and Chaokun Wang and Zixin Song and Cheng Wu and Shannan Yan and Jiajun Zhang and Ziyang Liu},
  booktitle = {Advances in Neural Information Processing Systems (NeurIPS)},
  year      = {2025}
}
</pre>
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025 Findings</div><img src='images/paper_lagcl4rec.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**LAGCL4Rec: When LLMs Activate Interactions Potential in Graph Contrastive Learning for Recommendation**](https://aclanthology.org/2025.findings-emnlp.61/) \\
Leqi Zheng, Chaokun Wang, Canzhi Chen, **Jiajun Zhang**, Cheng Wu, Zixin Song, Shannan Yan, Ziyang Liu, Hongwei Li

- **TL;DR**: We propose LAGCL4Rec, a progressive activation pipeline that leverages LLMs to activate interaction potential in graph contrastive learning for recommendation at data, rank, and rerank levels.
- **Overview**: This work investigates how LLMs can serve as more than text generators in recommender systems. Instead, they are used as high-level reasoning modules that enrich graph-based recommendation pipelines through data activation, candidate refinement, and reranking.
- **Highlights**: The paper connects LLM reasoning with graph representation learning in a practical recommendation setting, showing how language priors can complement sparse interaction graphs and improve downstream recommendation quality.

<details><summary>📖 BibTeX</summary>
<pre>
@inproceedings{zheng2025lagcl4rec,
  title     = {LAGCL4Rec: When LLMs Activate Interactions Potential in Graph Contrastive Learning for Recommendation},
  author    = {Leqi Zheng and Chaokun Wang and Canzhi Chen and Jiajun Zhang and Cheng Wu and Zixin Song and Shannan Yan and Ziyang Liu and Hongwei Li},
  booktitle = {Findings of the Association for Computational Linguistics: EMNLP 2025},
  year      = {2025}
}
</pre>
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2024</div><img src='images/paper_fade.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Evolving to the Future: Unseen Event Adaptive Fake News Detection on Social Media**](https://arxiv.org/abs/2403.00037) \\
**Jiajun Zhang**, Zhixun Li, Qiang Liu, Shu Wu, Liang Wang

- **TL;DR**: We introduce FADE, a future-adaptive fake news detection framework that leverages adaptive augmentation and graph contrastive learning to generalize to unseen events on social media.
- **Overview**: Fake news detectors often overfit to event-specific patterns and degrade sharply when facing emerging topics. FADE tackles this challenge by explicitly modeling event shift and improving generalization to previously unseen news events.
- **Highlights**: The paper combines adaptation and graph learning to strengthen robustness under temporal and topical drift, making it a practical step toward more deployable misinformation detection systems.

[![arXiv](https://img.shields.io/badge/arXiv-2403.00037-b31b1b.svg)](https://arxiv.org/abs/2403.00037)

<details><summary>📖 BibTeX</summary>
<pre>
@inproceedings{zhang2024fade,
  title     = {Evolving to the Future: Unseen Event Adaptive Fake News Detection on Social Media},
  author    = {Jiajun Zhang and Zhixun Li and Qiang Liu and Shu Wu and Liang Wang},
  booktitle = {Proceedings of the 33rd ACM International Conference on Information and Knowledge Management (CIKM)},
  year      = {2024}
}
</pre>
</details>

</div>
</div>

## 📊 Technical Reports & Surveys

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint 2025</div><img src='images/paper_ci_survey.png' alt="paper image" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**From Code Foundation Models to Agents and Applications: A Comprehensive Survey and Practical Guide to Code Intelligence**](https://arxiv.org/abs/2511.18538) \\
Jian Yang, ..., **Jiajun Zhang**, ..., and 70+ authors

- **TL;DR**: A comprehensive synthesis and practical guide about code LLMs, systematically examining the complete model life cycle from data curation through advanced prompting, code pre-training, SFT, RL, and autonomous coding agents.
- **Overview**: This survey provides a broad map of the rapidly evolving code intelligence landscape, connecting foundation models, coding assistants, evaluation, training recipes, and agentic systems in a single framework.
- **Highlights**: It is designed not only as a literature review, but also as a practical guide for researchers and practitioners who want to understand how modern code LLM systems are built, evaluated, and deployed.

[![arXiv](https://img.shields.io/badge/arXiv-2511.18538-b31b1b.svg)](https://arxiv.org/abs/2511.18538)

<details><summary>📖 BibTeX</summary>
<pre>
@article{yang2025codeintelligence,
  title     = {From Code Foundation Models to Agents and Applications: A Comprehensive Survey and Practical Guide to Code Intelligence},
  author    = {Jian Yang and Xianglong Liu and Weifeng Lv and others},
  journal   = {arXiv preprint arXiv:2511.18538},
  year      = {2025}
}
</pre>
</details>

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

<details><summary>📖 BibTeX</summary>
<pre>
@article{hui2024qwen25coder,
  title     = {Qwen2.5-Coder Technical Report},
  author    = {Binyuan Hui and Jian Yang and Zeyu Cui and Jiaxi Yang and Dayiheng Liu and Lei Zhang and Tianyu Liu and Jiajun Zhang and Bowen Yu and Keming Lu and Kai Dang and Yang Fan and Yichang Zhang and An Yang and Rui Men and Fei Huang and Bo Zheng and Yibo Miao and Shanghaoran Quan and Yunlong Feng and Xingzhang Ren and Xuancheng Ren and Jingren Zhou and Junyang Lin},
  journal   = {arXiv preprint arXiv:2409.12186},
  year      = {2024}
}
</pre>
</details>

</div>
</div>
