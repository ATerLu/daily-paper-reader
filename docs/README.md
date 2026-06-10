<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-10
- 运行时间：2026-06-10 22:18:39 UTC
- 运行状态：成功
- 本次总论文数：16
- 精读区：6
- 速读区：10

### 今日简报（AI）
1) 今日精读+速读16篇论文，重点拆解了长文档问答的记忆代理框架与多模态检索的效率优化方案。  
2) 最值得看的方向：MARDoc与Trace Only What You Need提出的结构感知按需记忆，为长文档QA开辟代理式动态记忆新路径；MM-Matryoshka的预算弹性视觉检索和miniReranker的稀疏重排序，则直击视觉文档理解中的成本效率痛点。  
3) 建议读者优先实验两类记忆机制在图文混排长文档上的效果，再用DataEvolver自动化数据准备降低适配门槛。
- 详情：[/202606/10/README](/202606/10/README)

### 精读区论文标签
1. [MARDoc: A Memory-Aware Refinement Agent Framework for Multimodal Long Document QA](/202606/10/2606.05749v1-mardoc-a-memory-aware-refinement-agent-framework-for-multimodal-long-document-qa)  
   标签：评分：10.0/10、query:rag-llm
   evidence：面向多模态长文档问答的迭代检索-推理智能体框架
2. [Trace Only What You Need: Structure-Aware On-Demand Hypergraph Memory for Long-Document Question Answering](/202606/10/2606.10921v1-trace-only-what-you-need-structure-aware-on-demand-hypergraph-memory-for-long-document-question-answering)  
   标签：评分：10.0/10、query:rag-llm
   evidence：提出DocTrace多智能体RAG框架，利用按需超图记忆和文档结构。
3. [QO-Bench: Diagnosing Query-Operator-Preserving Retrieval over Typed Event Tuples](/202606/10/2606.04646v1-qo-bench-diagnosing-query-operator-preserving-retrieval-over-typed-event-tuples)  
   标签：评分：9.0/10、query:rag-llm
   evidence：提出一个面向检索增强生成系统的基准，测试检索是否保持查询操作，直接评估RAG性能。
4. [STORM: Stepwise Token Optimization with Reward-Guided Beam Search](/202606/10/2606.10621v1-storm-stepwise-token-optimization-with-reward-guided-beam-search)  
   标签：评分：9.0/10、query:rag-llm
   evidence：通过奖励引导束搜索的逐步令牌优化进行词汇查询扩展
5. [Improving the Efficiency and Effectiveness of LLM Knowledge Distillation for Conversational Search](/202606/10/2606.04650v1-improving-the-efficiency-and-effectiveness-of-llm-knowledge-distillation-for-conversational-search)  
   标签：评分：8.0/10、query:rag-llm
   evidence：对话搜索中LLM查询改写的知识蒸馏，提高效率与效果
6. [Evaluating RAG Reliability under Clean, Misleading, and Mixed Retrieval](/202606/10/2606.07783v1-evaluating-rag-reliability-under-clean-misleading-and-mixed-retrieval)  
   标签：评分：8.0/10、query:rag-llm
   evidence：提出评估协议，测试RAG在误导性检索下的可靠性

### 速读区论文标签
1. [DataEvolver: Automatic Data Preparation for Large Language Models through Multi-Level Self-Evolving](/202606/10/2606.07001v1-dataevolver-automatic-data-preparation-for-large-language-models-through-multi-level-self-evolving)  
   标签：评分：8.0/10、query:rag-llm
   evidence：提出自我进化系统自动构建大语言模型数据预处理流水线
2. [MM-Matryoshka: Towards Budget-Elastic Visual Document Retrieval via a 2D Multimodal Matryoshka Training Framework](/202606/10/2606.07654v1-mm-matryoshka-towards-budget-elastic-visual-document-retrieval-via-a-2d-multimodal-matryoshka-training-framework)  
   标签：评分：8.0/10、query:rag-llm
   evidence：提出二维套娃训练用于密集视觉文档检索，实现预算弹性的多向量检索。
3. [miniReranker: Efficient Multimodal Reranking through Visual Cache Reuse and Interaction Sparsity](/202606/10/2606.10759v1-minireranker-efficient-multimodal-reranking-through-visual-cache-reuse-and-interaction-sparsity)  
   标签：评分：8.0/10、query:rag-llm
   evidence：利用多模态大语言模型进行高效重排序，通过视觉缓存重用和稀疏注意力提升效率
4. [When Should Queries Be Decomposed? A Stage-Aware Study of Query Decomposition for Multi-Condition Retrieval](/202606/10/2606.08577v1-when-should-queries-be-decomposed-a-stage-aware-study-of-query-decomposition-for-multi-condition-retrieval)  
   标签：评分：7.0/10、query:rag-llm
   evidence：实证研究查询分解在不同检索阶段的效果并提出分阶段分解框架
5. [EviProp: Seeded Relevance Diffusion on Chunk-Page Graphs for Long Multimodal Document Retrieval](/202606/10/2606.08979v1-eviprop-seeded-relevance-diffusion-on-chunk-page-graphs-for-long-multimodal-document-retrieval)  
   标签：评分：7.0/10、query:rag-llm
   evidence：提出一种基于图的检索方法，利用密集视觉先验和稀疏块种子进行文档检索。
6. [Closing the Indexing-Decoding Gap in Multimodal Generative Retrieval via Prefix Retention Optimization](/202606/10/2606.09241v1-closing-the-indexing-decoding-gap-in-multimodal-generative-retrieval-via-prefix-retention-optimization)  
   标签：评分：7.0/10、query:rag-llm
   evidence：解决生成式检索中标识符学习与解码之间的差距，提出前缀保留方法。
7. [Closing the Indexing-Decoding Gap in Multimodal Generative Retrieval via Prefix Retention Optimization](/202606/10/2606.09241v2-closing-the-indexing-decoding-gap-in-multimodal-generative-retrieval-via-prefix-retention-optimization)  
   标签：评分：7.0/10、query:rag-llm
   evidence：理论表征生成式检索中前缀可判别性并优化以避免假阴性检索
8. [Fast LLM-Based Semantic Filtering: From a Unified Framework to an Adaptive Two-Phase Method](/202606/10/2606.08090v1-fast-llm-based-semantic-filtering-from-a-unified-framework-to-an-adaptive-two-phase-method)  
   标签：评分：6.0/10、query:rag-llm
   evidence：利用密集检索代理与LLM级联实现高效语义过滤
9. [Co-Evolving Skill Generation and Policy Optimization](/202606/10/2606.08755v1-co-evolving-skill-generation-and-policy-optimization)  
   标签：评分：6.0/10、query:rag-llm
   evidence：通过LLM生成技能并更新检索库为语言智能体提供技能检索
10. [Robust Active Learning for Few-Shot Example Selection in Text-to-SQL](/202606/10/2606.10125v1-robust-active-learning-for-few-shot-example-selection-in-text-to-sql)  
   标签：评分：6.0/10、query:rag-llm
   evidence：LLM文生SQL的主动示例选择


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
