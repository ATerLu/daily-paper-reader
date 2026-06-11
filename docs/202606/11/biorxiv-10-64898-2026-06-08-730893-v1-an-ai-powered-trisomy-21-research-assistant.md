---
title: An AI-Powered Trisomy 21 Research Assistant
title_zh: 人工智能驱动的21三体综合征研究助手
authors: "NANDI, S., Sundararajan, Z., Subirana-Granes, M., Espinosa, J. M., Pividori, M., Sullivan, K. D., Galbraith, M. D., Costello, J."
date: 2026-06-11
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.08.730893v1.full.pdf"
tags: ["query:rag-llm"]
score: 8.0
evidence: 对短文不同部分加权以优先实验证据的RAG方法
tldr: 唐氏综合征（21三体）相关文献累计超3.4万篇，信息过载严重，通用AI模型难以提供循证回答，而标准RAG等同处理论文章节，易受背景内容干扰。为此，我们开发了T21研究助手，一种章节感知RAG系统，通过优先检索结果章节与权重调整，聚焦实验证据，仅用1789篇PMC开放获取论文构建知识库。系统采用查询验证、重排序、引文验证等多阶段流程，基于NVIDIA Nemotron生成带引用的结构化回答。专家评估验证，BERTScore F1达0.712，召回0.758，性能超越主流模型，为生物医学研究提供可靠、可溯源的AI工具。
source: biorxiv
selection_source: fresh_fetch
motivation: 唐氏综合征文献迅速膨胀，通用AI缺乏循证，传统RAG未区分论文章节重要性易引入噪声。
method: 构建章节感知RAG系统，优先检索论文结果章节，仅用1789篇PMC开放获取文献，集成查询验证、重排序与引文验证多阶段流程。
result: 专家评估获BERTScore F1 0.712、召回0.758，效果媲美或超越主流模型。
conclusion: T21研究助手为唐氏综合征研究提供了高效、可溯源的循证AI工具，显著提升了信息检索与回答的可靠性。
---

## 摘要
唐氏综合征由21三体引起，增加了多种并发疾病的风险。截至2026年初，PubMed索引的相关出版物超过34,000篇，跟踪不断扩展的文献颇具挑战。通用大语言模型虽广泛用于信息检索，却常依赖宽泛的训练数据而非特定证据。检索增强生成（RAG）通过将模型输出链接至源文本，提高了回答的严谨性和可靠性。在研究中，源文本即同行评审文章。标准实现对所有稿件章节同等对待，使得背景文本可能与实验结果一样排名靠前。为使模型输出聚焦于实验支持的回答，我们开发了T21 Research Assistant，一个区分章节的RAG系统，优先使用“结果”章节，以主要实验证据为基础生成回答。该系统仅利用PubMed Central中1,789篇开放获取的唐氏综合征出版物，包括327项NIH INCLUDE资助的研究，并采用多阶段流程用于查询验证、检索、重排序、综合和引文验证。系统基于NVIDIA Nemotron模型构建，生成结构化、带引文的回答。使用专家策划的问题进行评估，表现出强劲性能，BERTScore F1达到0.712，召回率0.758，可比肩甚至超越领先的专有和开源模型。T21 Research Assistant访问地址：https://bioinformatics.cuanschutz.edu/t21-res-assi/

## Abstract
Down syndrome, caused by trisomy 21, increases the risk of diverse co-occurring conditions. With more than 34,000 related publications indexed in PubMed as of early 2026, keeping pace with this expanding literature is challenging. While general-purpose large language models are widely used for information retrieval, they often rely on broad training data rather than specific evidence. Retrieval-augmented generation (RAG) improves rigor and reliability of responses by linking model outputs to source texts. In research, source texts are peer-reviewed articles. Standard implementations treat all manuscript sections equally, allowing background text to rank as highly as experimental results. To focus model outputs on experimentally supported responses, we developed the T21 Research Assistant, a section-aware RAG system that prioritizes Results sections to ground responses in primary experimental evidence. The system draws exclusively from 1,789 open-access Down syndrome publications from PubMed Central, including 327 NIH INCLUDE-funded studies, and uses a multistage pipeline for query validation, retrieval, reranking, synthesis, and citation verification. Built on NVIDIA Nemotron models, it generates structured, cited responses. Evaluation using expert-curated questions demonstrated strong performance, achieving a BERTScore F1 of 0.712 and recall of 0.758, comparable to or exceeding leading proprietary and open-source models. T21 Research Assistant is available at: https://bioinformatics.cuanschutz.edu/t21-res-assi/