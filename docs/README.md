<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-21
- 运行时间：2026-06-21 21:23:35 UTC
- 运行状态：成功
- 本次总论文数：6
- 精读区：4
- 速读区：2

### 今日简报（AI）
今天精读了两篇RAG前沿研究，发现了多模态问答中证据首因偏差，以及缓存感知的排序优化能大幅提升效率。  
最值得关注的是“首位证据”对答案准确性的致命误导，以及通过原子事实构建简洁记忆体为Agent提效的思路。  
建议读者优先试验证据顺序策略：将关键信息前置并控制证据量，可显著改善你的RAG应用表现。
- 详情：[/202606/21/README](/202606/21/README)

### 精读区论文标签
1. [Lost at the End: Primacy Bias in Multimodal Retrieval-Augmented Question Answering](/202606/21/2606.16494v1-lost-at-the-end-primacy-bias-in-multimodal-retrieval-augmented-question-answering)  
   标签：评分：10.0/10、query:rag-llm
   evidence：首个控制性探究多模态检索增强问答中位置依赖性，揭示首因偏差（仅使用检索上下文开头）。
2. [CacheWeaver: Cache-Aware Evidence Ordering for Efficient Grounded RAG Inference](/202606/21/2606.19667v1-cacheweaver-cache-aware-evidence-ordering-for-efficient-grounded-rag-inference)  
   标签：评分：9.0/10、query:rag-llm
   evidence：缓存感知的证据排序降低RAG推理成本
3. [When Global Gating Is Enough: Admission-Time Hubness Control in Anisotropic Vector Retrieval Systems](/202606/21/2606.19692v1-when-global-gating-is-enough-admission-time-hubness-control-in-anisotropic-vector-retrieval-systems)  
   标签：评分：9.0/10、query:rag-llm
   evidence：通过入站时中枢控制防止RAG向量检索中的投毒风险
4. [Navigating Unreliable Parametric and Contextual Knowledge: Explicit Knowledge Conflict Resolution for LLM Inference](/202606/21/2606.20245v1-navigating-unreliable-parametric-and-contextual-knowledge-explicit-knowledge-conflict-resolution-for-llm-inference)  
   标签：评分：8.0/10、query:rag-llm
   evidence：解决集成外部上下文的LLM中的知识冲突，提出显式冲突解决机制以提升推理可靠性；与结合检索的LLM直接相关。

### 速读区论文标签
1. [AtomMem: Building Simple and Effective Memory System for LLM Agents via Atomic Facts](/202606/21/2606.19847v1-atommem-building-simple-and-effective-memory-system-for-llm-agents-via-atomic-facts)  
   标签：评分：7.0/10、query:rag-llm
   evidence：构建从交互中提取原子事实的记忆系统，实现LLM智能体的知识检索
2. [Encode Errors: Representational Retrieval of In-Context Demonstrations for Multilingual Grammatical Error Correction](/202606/21/2606.15416v1-encode-errors-representational-retrieval-of-in-context-demonstrations-for-multilingual-grammatical-error-correction)  
   标签：评分：6.0/10、query:rag-llm
   evidence：通过LLM内部语法错误表征检索上下文示例


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
