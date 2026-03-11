<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-03-02 ~ 2026-03-11
- 运行时间：2026-03-11 07:26:52 UTC
- 运行状态：成功
- 本次总论文数：26
- 精读区：15
- 速读区：11

### 今日简报（AI）
本期日报精选 26 篇前沿成果，深度拆解 LLM 压缩、量化与高效训练的最新技术路径。
重点关注 3BASiL 的稀疏加低秩压缩框架与 FreeAct 激活量化方案，两者均获满分评价，是模型轻量化的必读之作。
建议从自适应深度与低秩注意力机制入手，探索如何在有限算力下实现更高效的模型推理与部署。
- 详情：[/20260302-20260311/README](/20260302-20260311/README)

### 精读区论文标签
1. [3BASiL: An Algorithmic Framework for Sparse plus Low-Rank Compression of LLMs](/20260302-20260311/2603.01376v1-3basil-an-algorithmic-framework-for-sparse-plus-low-rank-compression-of-llms)  
   标签：评分：10.0/10、query:llm-cp
   evidence：大语言模型的稀疏加低秩分解压缩
2. [FreeAct: Freeing Activations for LLM Quantization](/20260302-20260311/2603.01776v1-freeact-freeing-activations-for-llm-quantization)  
   标签：评分：10.0/10、query:llm-cp
   evidence：针对LLM和多模态LLM的动态激活量化
3. [MASQuant: Modality-Aware Smoothing Quantization for Multimodal Large Language Models](/20260302-20260311/2603.04800v1-masquant-modality-aware-smoothing-quantization-for-multimodal-large-language-models)  
   标签：评分：10.0/10、query:llm-cp
   evidence：多模态大语言模型的训练后量化 (PTQ)
4. [WaterSIC: information-theoretically (near) optimal linear layer quantization](/20260302-20260311/2603.04956v1-watersic-information-theoretically-near-optimal-linear-layer-quantization)  
   标签：评分：10.0/10、query:llm-cp
   evidence：针对Llama和Qwen模型的线性层最优量化
5. [Sparse-BitNet: 1.58-bit LLMs are Naturally Friendly to Semi-Structured Sparsity](/20260302-20260311/2603.05168v1-sparse-bitnet-158-bit-llms-are-naturally-friendly-to-semi-structured-sparsity)  
   标签：评分：10.0/10、query:llm-cp
   evidence：结合了1.58比特量化与动态N:M稀疏化
6. [SlideSparse: Fast and Flexible (2N-2):2N Structured Sparsity](/20260302-20260311/2603.05232v1-slidesparse-fast-and-flexible-2n-22n-structured-sparsity)  
   标签：评分：10.0/10、query:llm-cp
   evidence：具有硬件加速的大模型结构化稀疏
7. [Deterministic Differentiable Structured Pruning for Large Language Models](/20260302-20260311/2603.08065v1-deterministic-differentiable-structured-pruning-for-large-language-models)  
   标签：评分：10.0/10、query:llm-cp
   evidence：大模型的确定性可微结构化剪枝
8. [SERQ: Saliency-Aware Low-Rank Error Reconstruction for LLM Quantization](/20260302-20260311/2603.08185v1-serq-saliency-aware-low-rank-error-reconstruction-for-llm-quantization)  
   标签：评分：10.0/10、query:llm-cp
   evidence：带有低秩误差重构的训练后量化
9. [Token Reduction via Local and Global Contexts Optimization for Efficient Video Large Language Models](/20260302-20260311/2603.01400v1-token-reduction-via-local-and-global-contexts-optimization-for-efficient-video-large-language-models)  
   标签：评分：9.0/10、query:llm-cp
   evidence：视频大语言模型的Token削减与剪枝
10. [Understanding the Physics of Key-Value Cache Compression for LLMs through Attention Dynamics](/20260302-20260311/2603.01426v1-understanding-the-physics-of-key-value-cache-compression-for-llms-through-attention-dynamics)  
   标签：评分：9.0/10、query:llm-cp
   evidence：用于高效LLM推理的KV缓存压缩
11. [FreeAct: Freeing Activations for LLM Quantization](/20260302-20260311/2603.01776v2-freeact-freeing-activations-for-llm-quantization)  
   标签：评分：9.0/10、query:llm-cp
   evidence：针对动态激活差异的量化框架
12. [Cross-Family Speculative Prefill: Training-Free Long-Context Compression with Small Draft Models](/20260302-20260311/2603.02631v1-cross-family-speculative-prefill-training-free-long-context-compression-with-small-draft-models)  
   标签：评分：9.0/10、query:llm-cp
   evidence：无需训练的提示词压缩以实现高效推理
13. [Dissecting Quantization Error: A Concentration-Alignment Perspective](/20260302-20260311/2603.04359v1-dissecting-quantization-error-a-concentration-alignment-perspective)  
   标签：评分：9.0/10、query:llm-cp
   evidence：训练后量化误差分析
14. [VSPrefill: Vertical-Slash Sparse Attention with Lightweight Indexing for Long-Context Prefilling](/20260302-20260311/2603.04460v1-vsprefill-vertical-slash-sparse-attention-with-lightweight-indexing-for-long-context-prefilling)  
   标签：评分：9.0/10、query:llm-cp
   evidence：用于长文本LLM推理的稀疏注意力
15. [LooComp: Leverage Leave-One-Out Strategy to Encoder-only Transformer for Efficient Query-aware Context Compression](/20260302-20260311/2603.09222v1-loocomp-leverage-leave-one-out-strategy-to-encoder-only-transformer-for-efficient-query-aware-context-compression)  
   标签：评分：9.0/10、query:llm-cp
   evidence：基于查询感知的上下文剪枝以实现高效推理

### 速读区论文标签
1. [AdaPonderLM: Gated Pondering Language Models with Token-Wise Adaptive Depth](/20260302-20260311/2603.01914v1-adaponderlm-gated-pondering-language-models-with-token-wise-adaptive-depth)  
   标签：评分：8.0/10、query:llm-cp
   evidence：逐标记自适应深度和早期退出以实现高效推理
2. [Multi-Head Low-Rank Attention](/20260302-20260311/2603.02188v1-multi-head-low-rank-attention)  
   标签：评分：8.0/10、query:llm-cp
   evidence：低秩注意力以减少KV缓存大小
3. [NuMuon: Nuclear-Norm-Constrained Muon for Compressible LLM Training](/20260302-20260311/2603.03597v1-numuon-nuclear-norm-constrained-muon-for-compressible-llm-training)  
   标签：评分：8.0/10、query:llm-cp
   evidence：通过低秩结构训练使大模型更易于压缩
4. [EvoPrune: Early-Stage Visual Token Pruning for Efficient MLLMs](/20260302-20260311/2603.03681v1-evoprune-early-stage-visual-token-pruning-for-efficient-mllms)  
   标签：评分：8.0/10、query:llm-cp
   evidence：高效多模态大模型的视觉标记剪枝
5. [Boosting Entropy with Bell Box Quantization](/20260302-20260311/2603.01599v1-boosting-entropy-with-bell-box-quantization)  
   标签：评分：7.0/10、query:llm-cp
   evidence：针对计算高效数据类型的量化感知预训练
6. [ByteFlow: Language Modeling through Adaptive Byte Compression without a Tokenizer](/20260302-20260311/2603.03583v1-byteflow-language-modeling-through-adaptive-byte-compression-without-a-tokenizer)  
   标签：评分：7.0/10、query:llm-cp
   evidence：无分词器的压缩驱动分割
7. [Hardware-Software Co-design for 3D-DRAM-based LLM Serving Accelerator](/20260302-20260311/2603.04797v1-hardware-software-co-design-for-3d-dram-based-llm-serving-accelerator)  
   标签：评分：7.0/10、query:llm-cp
   evidence：大模型推理加速器的软硬件协同设计
8. [Balancing Coverage and Draft Latency in Vocabulary Trimming for Faster Speculative Decoding](/20260302-20260311/2603.05210v1-balancing-coverage-and-draft-latency-in-vocabulary-trimming-for-faster-speculative-decoding)  
   标签：评分：7.0/10、query:llm-cp
   evidence：词表裁剪以加速投机采样
9. [Beyond Scattered Acceptance: Fast and Coherent Inference for DLMs via Longest Stable Prefixes](/20260302-20260311/2603.05454v1-beyond-scattered-acceptance-fast-and-coherent-inference-for-dlms-via-longest-stable-prefixes)  
   标签：评分：6.0/10、query:llm-cp
   evidence：扩散语言模型的高效推理
10. [Mozart: Modularized and Efficient MoE Training on 3.5D Wafer-Scale Chiplet Architectures](/20260302-20260311/2603.07006v1-mozart-modularized-and-efficient-moe-training-on-35d-wafer-scale-chiplet-architectures)  
   标签：评分：6.0/10、query:llm-cp
   evidence：大模型的高效MoE训练
11. [Compression as Adaptation: Implicit Visual Representation with Diffusion Foundation Models](/20260302-20260311/2603.07615v1-compression-as-adaptation-implicit-visual-representation-with-diffusion-foundation-models)  
   标签：评分：6.0/10、query:llm-cp
   evidence：使用低秩适配进行视觉表示压缩


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
