# Large Language Model Based Long Context Modeling Papers and Blogs 
<!--
[![Awesome](https://camo.githubusercontent.com/64f8905651212a80869afbecbf0a9c52a5d1e70beab750dea40a994fa9a9f3c6/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](https://github.com/Xnhyacinth/Awesome-LLM-Long_Context_Modeling) [![License: MIT](https://camo.githubusercontent.com/fd551ba4b042d89480347a0e74e31af63b356b2cac1116c7b80038f41b04a581/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d677265656e2e737667)](https://opensource.org/licenses/MIT) -->
<div align="center">
 <p align="center">
 
   <a href="#1-Survey-Papers">📝 Papers</a> | <a href="https://www.notion.so/Huanxuan-Liao-s-Blog-6518cf95f0d54858829b042588ff88bb">📚 Notions</a>
 
 </p>
</div>
<div align="center">

<!-- ![Build](https://img.shields.io/appveyor/build/gruntjs/grunt) -->
[![LICENSE](https://img.shields.io/github/license/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling/blob/main/LICENSE)
![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
[![commit](https://img.shields.io/github/last-commit/Xnhyacinth/Long_Text_Modeling_Papers?color=blue)](https://github.com/Xnhyacinth/Long_Text_Modeling_Papers/commits/main)
[![PR](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/Xnhyacinth/Long_Text_Modeling_Papers/pulls)
[![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling)
<!-- ![license](https://img.shields.io/bower/l/bootstrap?style=plastic) -->

</div>

This repo includes papers and blogs about Efficient Transformers, Length Extrapolation, Long Term Memory, Retrieval Augmented Generation(RAG), and Evaluation for Long Context Modeling.

🔥 Must-read papers for LLM-based Long Context Modeling.

Thanks for all the great contributors on GitHub!🔥⚡🔥

### Contents

* [1. Survey Papers](#1-Survey-Papers)
* [2. Efficient Attention](#2-Efficient-Attention)
  * [2.1 Sparse Attention](#21-Sparse-Attention)
  * [2.2 Linear Attention](#22-Linear-Attention)
  * [2.3 Hierarchical Attention](#23-Hierarchical-Attention)
  * [2.4 IO-Aware Attention](#24-IO-Aware-Attention)
* [3. Recurrent Transformers](#3-Recurrent-Transformers)
* [4. State Space Models](#4-State-Space-Models)
* [5. Length Extrapolation](#5-Length-Extrapolation)    🔥RoPE🔥
* [6. Long Term Memory](#6-Long-Term-Memory)
* [7. RAG and ICL](#7-RAG-and-ICL)
* [8. Agent](#8-Agent)
* [9. Compress](#9-Compress)
* [10. Long Video and Image](#10-Long-Video-and-Image)
* [11. Benchmark and Evaluation](#11-Benchmark-and-Evaluation)
  * [11.1 LLM](#111-LLM)
  * [11.2 MLLM](#112-MLLM)
* [12. Long Text Generation](#12-Long-Text-Generation)
* [13. Blogs](#13-Blogs)
* [Acknowledgements](#acknowledgements)

# 📢 News

## Week Papers

- **[2024.10.30]**
    - Paper: [ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference](https://arxiv.org/abs/2410.21465)

- **[2024.10.29]**
    - Paper: [LongReward: Improving Long-context Large Language Models with AI Feedback](https://arxiv.org/abs/2410.21252)
    - Paper: [HoPE: A Novel Positional Encoding Without Long-Term Decay for Enhanced Context Awareness and Extrapolation](https://arxiv.org/abs/2410.21216)
    - Paper: [Long Sequence Modeling with Attention Tensorization: From Sequence to Tensor Learning](https://arxiv.org/abs/2410.20926)

- **[2024.10.28]**
    - Paper: [Rethinking Visual Dependency in Long-Context Reasoning for Large Vision-Language Models](https://arxiv.org/abs/2410.19732)
    - Paper: [Not All Heads Matter: A Head-Level KV Cache Compression Method with Integrated Retrieval and Reasoning](https://arxiv.org/abs/2410.19258)
    - Paper: [Two are better than one: Context window extension with multi-grained self-injection](https://arxiv.org/abs/2410.19318)

- **[2024.10.25]**
    - Paper: [Why Does the Effective Context Length of LLMs Fall Short?](https://arxiv.org/abs/2410.18745)
    - Paper: [Taipan: Efficient and Expressive State Space Language Models with Selective Attention](https://arxiv.org/abs/2410.18572)
    - Paper: [KVSharer: Efficient Inference via Layer-Wise Dissimilar KV Cache Sharing](https://arxiv.org/abs/2410.18517)
    - Paper: [LOGO -- Long cOntext aliGnment via efficient preference Optimization](https://arxiv.org/abs/2410.18533)

- **[2024.10.24]**
    - Paper: [LongRAG: A Dual-Perspective Retrieval-Augmented Generation Paradigm for Long-Context Question Answering](https://arxiv.org/abs/2410.18050)
    - Paper: [Large Language Models Still Exhibit Bias in Long Text](https://arxiv.org/abs/2410.17519)

 - **[2024.10.23]**   
    - Paper: [ETHIC: Evaluating Large Language Models on Long-Context Tasks with High Information Coverage](https://arxiv.org/abs/2410.16848)

 - **[2024.10.22]**   
    - Paper: [Lossless KV Cache Compression to 2%](https://arxiv.org/abs/2410.15252)
    - Paper: [MatryoshkaKV: Adaptive KV Compression via Trainable Orthogonal Projection](https://arxiv.org/abs/2410.14731)
    - Paper: [EPIC: Efficient Position-Independent Context Caching for Serving Large Language Models](https://arxiv.org/abs/2410.15332)
    - Paper: [MagicPIG: LSH Sampling for Efficient LLM Generation](https://arxiv.org/abs/2410.16179)
    - Paper: [Rethinking Token Reduction for State Space Models](https://arxiv.org/abs/2410.14725) EMNLP 2024
    - Paper: [Selecting Influential Samples for Long Context Alignment via Homologous Models' Guidance and Contextual Awareness Measurement](https://arxiv.org/abs/2410.15633)

- **[2024.10.21]**
    - Paper: [Style-Compress: An LLM-Based Prompt Compression Framework Considering Task-Specific Styles](https://arxiv.org/abs/2410.14042) EMNLP 2024
    - Paper: [A Systematic Study of Cross-Layer KV Sharing for Efficient LLM Inference](https://arxiv.org/abs/2410.14442)
    - Paper: [Distance between Relevant Information Pieces Causes Bias in Long-Context LLMs](https://arxiv.org/abs/2410.14641)
    - Paper: [LoGU: Long-form Generation with Uncertainty Expressions](https://arxiv.org/abs/2410.14309)

## Month Papers

<details><summary>Month Papers</summary>

- **[2024.10.18]**
    - Paper: [Enhancing Long Context Performance in LLMs Through Inner Loop Query Mechanism](https://arxiv.org/abs/2410.12859) NeurIPS 2024
    - Paper: [In-context KV-Cache Eviction for LLMs via Attention-Gate](https://arxiv.org/abs/2410.12876)
    - Paper: [SeerAttention: Learning Intrinsic Sparse Attention in Your LLMs](https://arxiv.org/abs/2410.13276)

- **[2024.10.17]**
    - Paper: [Prompt Compression for Large Language Models: A Survey](https://arxiv.org/abs/2410.12388)
    - Paper: [Holistic Reasoning with Long-Context LMs: A Benchmark for Database Operations on Massive Textual Data](https://arxiv.org/abs/2410.11996)
    - Paper: [How much do contextualized representations encode long-range context?](https://arxiv.org/abs/2410.12292)

- **[2024.10.16]**
    - Paper: [Selection-p: Self-Supervised Task-Agnostic Prompt Compression for Faithfulness and Transferability](https://arxiv.org/abs/2410.11786) EMNLP 2024
    - Paper: [Graph of Records: Boosting Retrieval Augmented Generation for Long-context Summarization with Graphs](https://arxiv.org/abs/2410.11001)
    - Paper: [Beyond Linear Approximations: A Novel Pruning Approach for Attention Matrix](https://arxiv.org/abs/2410.11261)
    - Paper: [ChuLo: Chunk-Level Key Information Representation for Long Document Processing](https://arxiv.org/abs/2410.11119)

- **[2024.10.15]**
    - Paper: [DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads](https://arxiv.org/abs/2410.10819)
    - Paper: [LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory](https://arxiv.org/abs/2410.10813)
    - Paper: [Minimum Tuning to Unlock Long Output from LLMs with High Quality Data as the Key](https://arxiv.org/abs/2410.10210)
    - Paper: [LLM×MapReduce: Simplified Long-Sequence Processing using Large Language Models](https://arxiv.org/abs/2410.09342)

- **[2024.10.14]**
    - Paper: [Extra Global Attention Designation Using Keyword Detection in Sparse Transformer Architectures](https://arxiv.org/abs/2410.08971)

- **[2024.10.11]**
    - Paper: [TurboRAG: Accelerating Retrieval-Augmented Generation with Precomputed KV Caches for Chunked Text](https://arxiv.org/abs/2410.07590)

- **[2024.10.10]**
    - Paper: [Long-Context LLMs Meet RAG: Overcoming Challenges for Long Inputs in RAG](https://arxiv.org/abs/2410.05983)
    - Paper: [Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts for Large Language Models](https://arxiv.org/abs/2410.07176)
    - Paper: [FltLM: An Intergrated Long-Context Large Language Model for Effective Context Filtering and Understanding](https://arxiv.org/abs/2410.06886) ECAI 2024
    - Paper: [Stuffed Mamba: State Collapse and State Capacity of RNN-Based Long-Context Modeling](https://arxiv.org/abs/2410.07145)
    - Paper: [SEGMENT+: Long Text Processing with Short-Context Language Models](https://arxiv.org/abs/2410.06519)

- **[2024.10.08]**
    - Paper: [Inference Scaling for Long-Context Retrieval Augmented Generation](https://arxiv.org/abs/2410.04343)
    - Paper: [MathHay: An Automated Benchmark for Long-Context Mathematical Reasoning in LLMs](https://arxiv.org/abs/2410.04698)
    - Paper: [GARLIC: LLM-Guided Dynamic Progress Control with Hierarchical Weighted Graph for Long Document QA](https://arxiv.org/abs/2410.04790)
    - Paper: [LongGenBench: Long-context Generation Benchmark](https://arxiv.org/abs/2410.04199) EMNLP 2024
    - Paper: [TidalDecode: Fast and Accurate LLM Decoding with Position Persistent Sparse Attention](https://arxiv.org/abs/2410.05076)
    - Paper: [Hyper-multi-step: The Truth Behind Difficult Long-context Tasks](https://arxiv.org/abs/2410.04422)
    - Paper: [From Reading to Compressing: Exploring the Multi-document Reader for Prompt Compression](https://arxiv.org/abs/2410.04139) EMNLP 2024
    - Paper: [Differential Transformer](https://arxiv.org/abs/2410.05258)

- **[2024.10.07]**
    - Paper: [UNComp: Uncertainty-Aware Long-Context Compressor for Efficient Large Language Model Inference](https://arxiv.org/abs/2410.03090)
    - Paper: [ALR2: A Retrieve-then-Reason Framework for Long-context Question Answering](https://arxiv.org/abs/2410.03227)
    - Paper: [LoRC: Low-Rank Compression for LLMs KV Cache with a Progressive Compression Strategy](https://arxiv.org/abs/2410.03111)

- **[2024.10.04]**
    - Paper: [HELMET: How to Evaluate Long-Context Language Models Effectively and Thoroughly](https://arxiv.org/abs/2410.02694)
    - Paper: [L-CiteEval: Do Long-Context Models Truly Leverage Context for Responding?](https://arxiv.org/abs/2410.02115)
    - Paper: [How to Train Long-Context Language Models (Effectively)](https://arxiv.org/abs/2410.02660)
    - Paper: [Selective Attention Improves Transformer](https://arxiv.org/abs/2410.02703)

- **[2024.10.03]**
    - Paper: [Locret: Enhancing Eviction in Long-Context LLM Inference with Trained Retaining Heads](https://arxiv.org/abs/2410.01805)
    - Paper: [CreDes: Causal Reasoning Enhancement and Dual-End Searching for Solving Long-Range Reasoning Problems using LLMs](https://arxiv.org/abs/2410.01696)
    - Paper: [Bridging Context Gaps: Leveraging Coreference Resolution for Long Contextual Understanding](https://arxiv.org/abs/2410.01671)
    - Paper: [Efficient Long-range Language Modeling with Self-supervised Causal Retrieval](https://arxiv.org/abs/2410.01651)
    - Paper: [InfiniPot: Infinite Context Processing on Memory-Constrained LLMs](https://arxiv.org/abs/2410.01518)
    - Paper: [A Little Goes a Long Way: Efficient Long Context Training and Inference with Partial Contexts](https://arxiv.org/abs/2410.01485)

- **[2024.10.02]**
    - Paper: [VideoCLIP-XL: Advancing Long Description Understanding for Video CLIP Models](https://arxiv.org/abs/2410.00741)
    - Paper: [KV-Compress: Paged KV-Cache Compression with Variable Compression Rates per Attention Head](https://arxiv.org/abs/2410.00161)
    
- **[2024.10.01]**
    - Paper: [PEAR: Position-Embedding-Agnostic Attention Re-weighting Enhances Retrieval-Augmented Generation with Zero Inference Overhead](https://arxiv.org/abs/2409.19745)
    - Paper: [Perception Compressor:A training-free prompt compression method in long context scenarios](https://arxiv.org/abs/2409.19272)

- **[2024.09.27]**
    - Paper: [Discovering the Gems in Early Layers: Accelerating Long-Context LLMs with 1000x Input Token Reduction](https://arxiv.org/abs/2409.17422)

- **[2024.09.26]**
    - Paper: [FineZip: Pushing the Limits of Large Language Models for Practical Lossless Text Compression](https://arxiv.org/abs/2409.17141)
    - Paper: [Multilingual Evaluation of Long Context Retrieval and Reasoning](https://arxiv.org/abs/2409.18006)

- **[2024.09.25]**
    - Paper: [Lighter And Better: Towards Flexible Context Adaptation For Retrieval Augmented Generation](https://arxiv.org/abs/2409.15699) CIKM 2024
    - Paper: [HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models](https://arxiv.org/abs/2409.16191)
    - Paper: [Parse Trees Guided LLM Prompt Compression](https://arxiv.org/abs/2409.15395)

- **[2024.09.24]**
    - Paper: [You Only Use Reactive Attention Slice For Long Context Retrieval](https://arxiv.org/abs/2409.13695)
    - Paper: [Retrieval Augmented Generation (RAG) and Beyond: A Comprehensive Survey on How to Make your LLMs use External Data More Wisely](https://arxiv.org/abs/2409.14924)
    - Paper: [SMART-RAG: Selection using Determinantal Matrices for Augmented Retrieval](https://arxiv.org/abs/2409.13992)
    - Paper: [Inference-Friendly Models With MixAttention](https://arxiv.org/abs/2409.15012)

- **[2024.09.23]**
    - Paper: [Contextual Compression in Retrieval-Augmented Generation for Large Language Models: A Survey](https://arxiv.org/abs/2409.13385)
    - Paper: [TACO-RL: Task Aware Prompt Compression Optimization with Reinforcement Learning](https://arxiv.org/abs/2409.13035)

- **[2024.09.20]**
    - Paper: [RAD-Bench: Evaluating Large Language Models Capabilities in Retrieval Augmented Dialogues](https://arxiv.org/abs/2409.12558)
    - Paper: [Familiarity-aware Evidence Compression for Retrieval Augmented Generation](https://arxiv.org/abs/2409.12468)
    - Paper: [CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs](https://arxiv.org/abs/2409.12490)
    - Paper: [Fact, Fetch, and Reason: A Unified Evaluation of Retrieval-Augmented Generation](https://arxiv.org/abs/2409.12941)
    - Paper: [Michelangelo: Long Context Evaluations Beyond Haystacks via Latent Structure Queries](https://arxiv.org/abs/2409.12640)

- **[2024.09.19]**
    - Paper: [A Controlled Study on Long Context Extension and Generalization in LLMs](https://arxiv.org/abs/2409.12181)

- **[2024.09.18]**
    - Paper: [CSKV: Training-Efficient Channel Shrinking for KV Cache in Long-Context Scenarios](https://arxiv.org/abs/2409.10593)

 </details>

# 📜 Papers

> You can directly click on the title to jump to the corresponding PDF link location

## 1. Survey Papers

1. [**Efficient Transformers: A Survey.**](https://arxiv.org/abs/2009.06732) *Yi Tay, Mostafa Dehghani, Dara Bahri, Donald Metzler.* Arxiv 2022.

2. [**A Survey on Long Text Modeling with Transformers.**](https://arxiv.org/abs/2302.14502) *Zican Dong, Tianyi Tang, Lunyi Li, Wayne Xin Zhao.* Arxiv 2023.

3. [**Neural Natural Language Processing for Long Texts: A Survey of the State-of-the-Art.**](https://arxiv.org/abs/2305.16259) *Dimitrios Tsirmpas, Ioannis Gkionis, Ioannis Mademlis, Georgios Papadopoulos.* Arxiv 2023.

4. [**Advancing Transformer Architecture in Long-Context Large Language Models: A Comprehensive Survey.**](https://arxiv.org/abs/2311.12351) *Yunpeng Huang, Jingwei Xu, Zixu Jiang, Junyu Lai, Zenan Li, Yuan Yao, Taolue Chen, Lijuan Yang, Zhou Xin, Xiaoxing Ma.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Strivin0311/long-llms-learning)](https://github.com/Strivin0311/long-llms-learning)

5. [**Length Extrapolation of Transformers: A Survey from the Perspective of Position Encoding.**](https://arxiv.org/abs/2312.17044) *Liang Zhao, Xiaocheng Feng, Xiachong Feng, Bing Qin, Ting Liu.* Arxiv 2024.

6. [**The What, Why, and How of Context Length Extension Techniques in Large Language Models -- A Detailed Survey.**](https://arxiv.org/abs/2401.07872) *Saurav Pawar, S.M Towhidul Islam Tonmoy, S M Mehedi Zaman, Vinija Jain, Aman Chadha, Amitava Das.* Arxiv 2024.

7. [**State Space Model for New-Generation Network Alternative to Transformers: A Survey.**](https://arxiv.org/abs/2404.09516) *Xiao Wang, Shiao Wang, Yuhe Ding, Yuehang Li, Wentao Wu, Yao Rong, Weizhe Kong, Ju Huang, Shihao Li, Haoxiang Yang, Ziwen Wang, Bo Jiang, Chenglong Li, Yaowei Wang, Yonghong Tian, Jin Tang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Event-AHU/Mamba_State_Space_Model_Paper_List)](https://github.com/Event-AHU/Mamba_State_Space_Model_Paper_List)

8. [**A Survey on Efficient Inference for Large Language Models.**](https://arxiv.org/abs/2404.14294) *Zixuan Zhou, Xuefei Ning, Ke Hong, Tianyu Fu, Jiaming Xu, Shiyao Li, Yuming Lou, Luning Wang, Zhihang Yuan, Xiuhong Li, Shengen Yan, Guohao Dai, Xiao-Ping Zhang, Yuhan Dong, Yu Wang.* Arxiv 2024.

9. [**A Survey on RAG Meets LLMs: Towards Retrieval-Augmented Large Language Models.**](https://arxiv.org/abs/2405.06211) *Yujuan Ding, Wenqi Fan, Liangbo Ning, Shijie Wang, Hengyun Li, Dawei Yin, Tat-Seng Chua, Qing Li.* Arxiv 2024.

10. [**Evaluation of Retrieval-Augmented Generation: A Survey.**](https://arxiv.org/abs/2405.07437) *Hao Yu, Aoran Gan, Kai Zhang, Shiwei Tong, Qi Liu, Zhaofeng Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/YHPeter/Awesome-RAG-Evaluation)](https://github.com/YHPeter/Awesome-RAG-Evaluation)

11. [**The CAP Principle for LLM Serving: A Survey of Long-Context Large Language Model Serving.**](https://arxiv.org/abs/2405.11299) *Pai Zeng, Zhenyu Ning, Jieru Zhao, Weihao Cui, Mengwei Xu, Liwei Guo, Xusheng Chen, Yizhou Shan.* Arxiv 2024.

12. [**Keep the Cost Down: A Review on Methods to Optimize LLM' s KV-Cache Consumption.**](https://arxiv.org/abs/2407.18003) *Luohe Shi, Hongyi Zhang, Yao Yao, Zuchao Li, Hai Zhao.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zcli-charlie/Awesome-KV-Cache)](https://github.com/zcli-charlie/Awesome-KV-Cache)

13. [**Contextual Compression in Retrieval-Augmented Generation for Large Language Models: A Survey.**](https://arxiv.org/abs/2409.13385) *Sourav Verma.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SrGrace/Contextual-Compression)](https://github.com/SrGrace/Contextual-Compression)

14. [**Retrieval Augmented Generation (RAG) and Beyond: A Comprehensive Survey on How to Make your LLMs use External Data More Wisely.**](https://arxiv.org/abs/2409.14924) *Siyun Zhao, Yuqing Yang, Zilong Wang, Zhiyuan He, Luna K. Qiu, Lili Qiu.* Arxiv 2024.

15. [**Prompt Compression for Large Language Models: A Survey.**](https://arxiv.org/abs/2410.12388) *Zongqian Li, Yinhong Liu, Yixuan Su, Nigel Collier.* Arxiv 2024.

## 2. Efficient Attention

### 2.1 Sparse Attention

1. [**Generating Long Sequences with Sparse Transformers.**](https://arxiv.org/abs/1904.10509) *Rewon Child, Scott Gray, Alec Radford, Ilya Sutskever.* Arxiv 2019.

2. [**Blockwise selfattention for long document understanding.**](https://aclanthology.org/2020.findings-emnlp.232/) *Jiezhong Qiu, Hao Ma, Omer Levy, Wen-tau Yih, Sinong Wang, Jie Tang.* EMNLP 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/xptree/BlockBERT)](https://github.com/xptree/BlockBERT)

3. [**Longformer: The Long-Document Transformer.**](https://arxiv.org/abs/2004.05150) *Iz Beltagy, Matthew E. Peters, Arman Cohan.* Arxiv 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/allenai/longformer)](https://github.com/allenai/longformer)

4. [**ETC: Encoding Long and Structured Inputs in Transformers.**](https://aclanthology.org/2020.emnlp-main.19/) *Joshua Ainslie, Santiago Ontanon, Chris Alberti, Vaclav Cvicek, Zachary Fisher, Philip Pham, Anirudh Ravula, Sumit Sanghai, Qifan Wang, Li Yang.* EMNLP 2020.

5. [**Big Bird: Transformers for Longer Sequences.**](https://papers.nips.cc/paper/2020/hash/c8512d142a2d849725f31a9a7a361ab9-Abstract.html) *Manzil Zaheer, Guru Guruganesh, Kumar Avinava Dubey, Joshua Ainslie, Chris Alberti, Santiago Ontanon, Philip Pham, Anirudh Ravula, Qifan Wang, Li Yang, Amr Ahmed.* NeurIPS 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/bigbird)](https://github.com/google-research/bigbird)

6. [**Reformer: The efficient transformer.**](https://arxiv.org/abs/2001.04451)  *Nikita Kitaev, Łukasz Kaiser, Anselm Levskaya.* ICLR 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/reformer-pytorch)](https://github.com/lucidrains/reformer-pytorch)

7. [**Sparse Sinkhorn Attention.**](https://arxiv.org/abs/2002.11296) *Yi Tay, Dara Bahri, Liu Yang, Donald Metzler, Da-Cheng Juan.* ICML 2020. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/sinkhorn-transformer)](https://github.com/lucidrains/sinkhorn-transformer)

8. [**Sparse and continuous attention mechanisms.**](https://arxiv.org/abs/2006.07214) *André F. T. Martins, António Farinhas, Marcos Treviso, Vlad Niculae, Pedro M. Q. Aguiar, Mário A. T. Figueiredo.* NIPS 2020. 

9. [**Efficient Content-Based Sparse Attention with Routing Transformers.**](https://aclanthology.org/2021.tacl-1.4/) *Aurko Roy, Mohammad Saffar, Ashish Vaswani, David Grangier.* TACL 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/routing-transformer)](https://github.com/lucidrains/routing-transformer)

10. [**LongT5: Efficient text-to-text transformer for long sequences.**](https://aclanthology.org/2022.findings-naacl.55/) *Mandy Guo, Joshua Ainslie, David Uthus, Santiago Ontanon, Jianmo Ni, Yun-Hsuan Sung, Yinfei Yang.* NAACL 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/longt5)](https://github.com/google-research/longt5)

11. [**Efficient Long-Text Understanding with Short-Text Models.**](https://aclanthology.org/2023.tacl-1.17/) *Maor Ivgi, Uri Shaham, Jonathan Berant.* TACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Mivg/SLED)](https://github.com/Mivg/SLED)

12. [**Parallel Context Windows for Large Language Models.**](https://aclanthology.org/2023.acl-long.352/) *Nir Ratner, Yoav Levine, Yonatan Belinkov, Ori Ram, Inbal Magar, Omri Abend, Ehud Karpas, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/AI21Labs/Parallel-Context-Windows)](https://github.com/AI21Labs/Parallel-Context-Windows)

13. [**Unlimiformer: Long-Range Transformers with Unlimited Length Input.**](https://arxiv.org/abs/2305.01625) *Amanda Bertsch, Uri Alon, Graham Neubig, Matthew R. Gormley.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/abertsch72/unlimiformer)](https://github.com/abertsch72/unlimiformer)

14. [**Landmark Attention: Random-Access Infinite Context Length for Transformers.**](https://arxiv.org/abs/2305.16300) *Amirkeivan Mohtashami, Martin Jaggi* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/epfml/landmark-attention)](https://github.com/epfml/landmark-attention)

15. [**LONGNET: Scaling Transformers to 1,000,000,000 Tokens.**](https://arxiv.org/abs/2307.02486) *Jiayu Ding, Shuming Ma, Li Dong, Xingxing Zhang, Shaohan Huang, Wenhui Wang, Nanning Zheng, Furu Wei.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/LongNet)](https://github.com/kyegomez/LongNet)

16. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) *Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

17. [**Blockwise Parallel Transformer for Long Context Large Models.**](https://arxiv.org/abs/2305.19370) *Hao Liu, Pieter Abbeel.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/Blockwise-Parallel-Transformer)](https://github.com/lhao499/llm_large_context)

18. [**MEGABYTE: Predicting Million-byte Sequences with Multiscale Transformers.**](https://arxiv.org/abs/2305.07185) *Lili Yu, Dániel Simig, Colin Flaherty, Armen Aghajanyan, Luke Zettlemoyer, Mike Lewis.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/MEGABYTE-pytorch)](https://github.com/lucidrains/MEGABYTE-pytorch)

19. [**Dynamic Context Pruning for Efficient and Interpretable Autoregressive Transformers.**](https://arxiv.org/abs/2305.15805) *Sotiris Anagnostidis, Dario Pavllo, Luca Biggio, Lorenzo Noci, Aurelien Lucchi, Thomas Hofmann.* Arxiv 2023. 

20. [**Long-range Language Modeling with Self-retrieval.**](https://arxiv.org/abs/2306.13421) *Ohad Rubin, Jonathan Berant.* Arxiv 2023. 

21. [**Max-Margin Token Selection in Attention Mechanism.**](https://arxiv.org/abs/2306.13596) *Davoud Ataee Tarzanagh, Yingcong Li, Xuechen Zhang, Samet Oymak.* Arxiv 2023. 

22. [**Chunk, Align, Select: A Simple Long-sequence Processing Method for Transformers.**](https://arxiv.org/abs/2308.13191) *Jiawen Xie, Pengyu Cheng, Xiao Liang, Yong Dai, Nan Du.* Arxiv 2023. 

23. [**Sparse Token Transformer with Attention Back Tracking.**](https://openreview.net/forum?id=VV0hSE8AxCw) *Heejun Lee, Minki Kang, Youngwan Lee, Sung Ju Hwang.* ICLR 2023. 

24. [**Empower Your Model with Longer and Better Context Comprehension.**](https://arxiv.org/pdf/2307.13365v2.pdf) *YiFei Gao, Lei Wang, Jun Fang, Longhua Hu, Jun Cheng.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yileijin/attention-transition)](https://github.com/yileijin/attention-transition)

25. [**Ring Attention with Blockwise Transformers for Near-Infinite Context.**](https://arxiv.org/pdf/2310.01889v1.pdf) *Hao Liu, Matei Zaharia, Pieter Abbeel.* Arxiv 2023.

26. [**Efficient Streaming Language Models with Attention Sinks.**](https://arxiv.org/pdf/2309.17453.pdf) *Guangxuan Xiao, Yuandong Tian, Beidi Chen, Song Han, Mike Lewis.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/streaming-llm)](https://github.com/mit-han-lab/streaming-llm)

27. [**HyperAttention: Long-context Attention in Near-Linear Time.**](https://arxiv.org/abs/2310.05869) *Insu Han, Rajesh Jayaram, Amin Karbasi, Vahab Mirrokni, David P. Woodruff, Amir Zandieh.* Arxiv 2023.

28. [**Fovea Transformer: Efficient Long-Context Modeling with Structured Fine-to-Coarse Attention.**](https://arxiv.org/pdf/2311.07102v1.pdf) *Ziwei He,Jian Yuan,Le Zhou,Jingwen Leng,Bo Jiang.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ZiweiHe/Fovea-Transformer)](https://github.com/ZiweiHe/Fovea-Transformer)

29. [**ChunkAttention: Efficient Self-Attention with Prefix-Aware KV Cache and Two-Phase Partition.**](https://arxiv.org/abs/2402.15220) *Lu Ye, Ze Tao, Yong Huang, Yang Li.* Arxiv 2024.

30. [**Training-Free Long-Context Scaling of Large Language Models.**](https://arxiv.org/abs/2402.17463) *Chenxin An, Fei Huang, Jun Zhang, Shansan Gong, Xipeng Qiu, Chang Zhou, Lingpeng Kong.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HKUNLP/ChunkLlama)](https://github.com/HKUNLP/ChunkLlama)

31. [**LongHeads: Multi-Head Attention is Secretly a Long Context Processor.**](https://arxiv.org/abs/2402.10685) *Yi Lu, Xin Zhou, Wei He, Jun Zhao, Tao Ji, Tao Gui, Qi Zhang, Xuanjing Huang.* Arxiv 2024.

32. [**Zebra: Extending Context Window with Layerwise Grouped Local-Global Attention.**](https://arxiv.org/abs/2312.08618) *Kaiqiang Song, Xiaoyang Wang, Sangwoo Cho, Xiaoman Pan, Dong Yu.* Arxiv 2023.

33. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) *Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/SnapKV)](https://github.com/FasterDecoding/SnapKV)

34. [**Sequence can Secretly Tell You What to Discard.**](https://arxiv.org/abs/2404.15949) *Jincheng Dai, Zhuowei Huang, Haiyun Jiang, Chen Chen, Deng Cai, Wei Bi, Shuming Shi.* Arxiv 2024.

35. [**SinkLoRA: Enhanced Efficiency and Chat Capabilities for Long-Context Large Language Models.**](https://arxiv.org/abs/2406.05678) *Hengyu Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Dexter-GT-86/SinkLoRA)](https://github.com/Dexter-GT-86/SinkLoRA)

36. [**HiP Attention: Sparse Sub-Quadratic Attention with Hierarchical Attention Pruning.**](https://arxiv.org/abs/2406.09827) *Heejun Lee, Geon Park, Youngwan Lee, Jina Kim, Wonyoung Jeong, Myeongjae Jeon, Sung Ju Hwang.* Arxiv 2024.

37. [**Taking a Deep Breath: Enhancing Language Modeling of Large Language Models with Sentinel Tokens.**](https://arxiv.org/abs/2406.10985) *Weiyao Luo, Suncong Zheng, Heming Xia, Weikang Wang, Yan Lei, Tianyu Liu, Shuang Chen, Zhifang Sui.* Arxiv 2024.

38. [**MoA: Mixture of Sparse Attention for Automatic Large Language Model Compression.**](https://arxiv.org/abs/2406.14909) *Weiyao Luo, Suncong Zheng, Heming Xia, Weikang Wang, Yan Lei, Tianyu Liu, Shuang Chen, Zhifang Sui.* Arxiv 2024.

39. [**Sparser is Faster and Less is More: Efficient Sparse Attention for Long-Range Transformers.**](https://arxiv.org/abs/2406.16747) *Chao Lou, Zixia Jia, Zilong Zheng, Kewei Tu.* Arxiv 2024.

40. [**Near-Lossless Acceleration of Long Context LLM Inference with Adaptive Structured Sparse Attention.**](https://arxiv.org/abs/2406.15486) *Qianchao Zhu, Jiangfei Duan, Chang Chen, Siran Liu, Xiuhong Li, Guanyu Feng, Xin Lv, Huanqi Cao, Xiao Chuanfu, Xingcheng Zhang, Dahua Lin, Chao Yang.* Arxiv 2024.

41. [**Neurocache: Efficient Vector Retrieval for Long-range Language Modeling.**](https://arxiv.org/abs/2407.02486) *Ali Safaya, Deniz Yuret.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/alisafaya/neurocache)](https://github.com/alisafaya/neurocache)

42. [**Weighted Grouped Query Attention in Transformers.**](https://arxiv.org/abs/2407.10855) *Sai Sena Chinnakonduru, Astarag Mohapatra.* Arxiv 2024.

43. [**Selective Attention Improves Transformer.**](https://arxiv.org/abs/2410.02703) *Yaniv Leviathan, Matan Kalman, Yossi Matias.* Arxiv 2024.

44. [**TidalDecode: Fast and Accurate LLM Decoding with Position Persistent Sparse Attention.**](https://arxiv.org/abs/2410.05076) *Lijie Yang, Zhihao Zhang, Zhuofu Chen, Zikun Li, Zhihao Jia.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/DerrickYLJ/TidalDecode)](https://github.com/DerrickYLJ/TidalDecode)

45. [**FltLM: An Intergrated Long-Context Large Language Model for Effective Context Filtering and Understanding.**](https://arxiv.org/abs/2410.06886) *Jingyang Deng, Zhengyang Shen, Boyang Wang, Lixin Su, Suqi Cheng, Ying Nie, Junfeng Wang, Dawei Yin, Jinwen Ma.* Arxiv 2024.

46. [**Beyond Linear Approximations: A Novel Pruning Approach for Attention Matrix.**](https://arxiv.org/abs/2410.11261) *Yingyu Liang, Jiangxuan Long, Zhenmei Shi, Zhao Song, Yufa Zhou.* Arxiv 2024.

47. [**Extra Global Attention Designation Using Keyword Detection in Sparse Transformer Architectures.**](https://arxiv.org/abs/2410.08971) *Evan Lucas, Dylan Kangas, Timothy C Havens.* Arxiv 2024.

48. [**SeerAttention: Learning Intrinsic Sparse Attention in Your LLMs.**](https://arxiv.org/abs/2410.13276) *Yizhao Gao, Zhichen Zeng, Dayou Du, Shijie Cao, Hayden Kwok-Hay So, Ting Cao, Fan Yang, Mao Yang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/SeerAttention)](https://github.com/microsoft/SeerAttention)

### 2.2 Linear Attention

1. [**Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention.**](https://arxiv.org/abs/2006.16236) *Angelos Katharopoulos, Apoorv Vyas, Nikolaos Pappas, François Fleuret.* ICML 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/idiap/fast-transformers)](https://github.com/idiap/fast-transformers)

2. [**Learning Fast Algorithms for Linear Transforms Using Butterfly Factorizations.**](https://arxiv.org/abs/1903.05895) *Tri Dao, Albert Gu, Matthew Eichhorn, Atri Rudra, Christopher Ré.* Arxiv 2019.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/butterfly)](https://github.com/HazyResearch/butterfly)

3. [**Masked language modeling for proteins via linearly scalable long-context transformers.**](https://arxiv.org/abs/2006.03555) *Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, David Belanger, Lucy Colwell, Adrian Weller.* Arxiv 2020. 

4. [**Rethinking attention with performers.**](https://arxiv.org/abs/2009.14794) *Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, Afroz Mohiuddin, Lukasz Kaiser, David Belanger, Lucy Colwell, Adrian Weller.* Arxiv 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/performer-pytorch)](https://github.com/lucidrains/performer-pytorch)

5. [**Linformer: Self-attention with linear complexity.**](https://arxiv.org/abs/2006.04768) *Sinong Wang, Belinda Z. Li, Madian Khabsa, Han Fang, Hao Ma.* Arxiv 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/linear-attention-transformer)](https://github.com/lucidrains/linear-attention-transformer)

6. [**Random Feature Attention.**](https://arxiv.org/abs/2103.02143) *Hao Peng, Nikolaos Pappas, Dani Yogatama, Roy Schwartz, Noah A. Smith, Lingpeng Kong.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Noahs-ARK/RFA)](https://github.com/Noahs-ARK/RFA)

7. [**Luna: Linear unified nested attention.**](https://arxiv.org/abs/2106.01540) *Xuezhe Ma, Xiang Kong, Sinong Wang, Chunting Zhou, Jonathan May, Hao Ma, Luke Zettlemoyer.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sooftware/luna-transformer)](https://github.com/sooftware/luna-transformer)

8. [**Fnet: Mixing tokens with fourier transforms.**](https://arxiv.org/abs/2105.03824) *James Lee-Thorp, Joshua Ainslie, Ilya Eckstein, Santiago Ontanon.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/jaketae/fnet)](https://github.com/jaketae/fnet)

9. [**Gated Linear Attention Transformers with Hardware-Efficient Training.**](https://arxiv.org/abs/2312.06635v2) *Songlin Yang, Bailin Wang, Yikang Shen, Rameswar Panda, Yoon Kim.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/berlino/gated_linear_attention)](https://github.com/berlino/gated_linear_attention)

10. [**Latent Attention for Linear Time Transformers.**](https://arxiv.org/abs/2402.17512) *Rares Dolga, Marius Cobzarenco, David Barber.* Arxiv 2024.  

11. [**Simple linear attention language models balance the recall-throughput tradeoff.**](https://arxiv.org/abs/2402.18668) *Simran Arora, Sabri Eyuboglu, Michael Zhang, Aman Timalsina, Silas Alberti, Dylan Zinsley, James Zou, Atri Rudra, Christopher Ré.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/based)](https://github.com/HazyResearch/based)

12. [**Linear Attention Sequence Parallelism.**](https://arxiv.org/abs/2404.02882) *Weigao Sun, Zhen Qin, Dong Li, Xuyang Shen, Yu Qiao, Yiran Zhong.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/LASP)](https://github.com/OpenNLPLab/LASP)

13. [**Softmax Attention with Constant Cost per Token.**](https://arxiv.org/abs/2404.05843) *Franz A. Heinsen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/glassroom/heinsen_attention](https://github.com/glassroom/heinsen_attention)

14. [**Megalodon: Efficient LLM Pretraining and Inference with Unlimited Context Length.**](https://arxiv.org/abs/2404.08801) *Xuezhe Ma, Xiaomeng Yang, Wenhan Xiong, Beidi Chen, Lili Yu, Hao Zhang, Jonathan May, Luke Zettlemoyer, Omer Levy, Chunting Zhou.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/XuezheMax/megalodon](https://github.com/XuezheMax/megalodon)

15. [**Various Lengths, Constant Speed: Efficient Language Modeling with Lightning Attention.**](https://arxiv.org/abs/2405.17381) *Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong.* Arxiv 2024.

16. [**Unlocking the Secrets of Linear Complexity Sequence Model from A Unified Perspective.**](https://arxiv.org/abs/2405.17383) *Zhen Qin, Xuyang Shen, Weigao Sun, Dong Li, Stan Birchfield, Richard Hartley, Yiran Zhong.* Arxiv 2024.

17. [**Attention as an RNN.**](https://arxiv.org/abs/2405.13956) *Leo Feng, Frederick Tung, Hossein Hajimirsadeghi, Mohamed Osama Ahmed, Yoshua Bengio, Greg Mori.* Arxiv 2024.

18. [**You Only Scan Once: Efficient Multi-dimension Sequential Modeling with LightNet.**](https://arxiv.org/abs/2405.21022) *Zhen Qin, Yuxin Mao, Xuyang Shen, Dong Li, Jing Zhang, Yuchao Dai, Yiran Zhong.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/LightNet](https://github.com/OpenNLPLab/LightNet)

19. [**When Linear Attention Meets Autoregressive Decoding: Towards More Effective and Efficient Linearized Large Language Models.**](https://arxiv.org/abs/2406.07368) *Haoran You, Yichao Fu, Zheng Wang, Amir Yazdanbakhsh, Yingyan (Celine)Lin.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/GATECH-EIC/Linearized-LLM](https://github.com/GATECH-EIC/Linearized-LLM)

20. [**Learning to (Learn at Test Time): RNNs with Expressive Hidden States.**](https://arxiv.org/abs/2407.04620) *Yu Sun, Xinhao Li, Karan Dalal, Jiarui Xu, Arjun Vikram, Genghan Zhang, Yann Dubois, Xinlei Chen, Xiaolong Wang, Sanmi Koyejo, Tatsunori Hashimoto, Carlos Guestrin.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/test-time-training/ttt-lm-pytorch](https://github.com/test-time-training/ttt-lm-pytorch)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/test-time-training/ttt-lm-jax](https://github.com/test-time-training/ttt-lm-jax)

21. [**Gated Slot Attention for Efficient Linear-Time Sequence Modeling.**](https://arxiv.org/abs/2409.07146) *Yu Zhang, Songlin Yang, Ruijie Zhu, Yue Zhang, Leyang Cui, Yiqiao Wang, Bolun Wang, Freda Shi, Bailin Wang, Wei Bi, Peng Zhou, Guohong Fu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sustcsonglin/flash-linear-attention](https://github.com/sustcsonglin/flash-linear-attention)

### 2.3 Hierarchical Attention

1. [**Neural Legal Judgment Prediction in English.**](https://aclanthology.org/P19-1424.pdf) *Ilias Chalkidis, Ion Androutsopoulos, Nikolaos Aletras.* ACL 2019. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/PolarisRisingWar/pytorch_ljp)](https://github.com/PolarisRisingWar/pytorch_ljp)

2. [**Hierarchical Neural Network Approaches for Long Document Classification.**](https://arxiv.org/abs/2201.06774) *Snehal Khandve, Vedangi Wagh, Apurva Wani, Isha Joshi, Raviraj Joshi.* ICML 2022. 

3. [**Hi-transformer: Hierarchical interactive transformer for efficient and effective long document modeling.**](https://arxiv.org/abs/2106.01040) *Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang.* ACL-IJCNLP 2021 

4. [**Erniesparse: Learning hierarchical efficient transformer through regularized self-attention.**](https://arxiv.org/abs/2203.12276) *Yang Liu, Jiaxiang Liu, Li Chen, Yuxiang Lu, Shikun Feng, Zhida Feng, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang.* Arxiv 2022.

### 2.4 IO-Aware Attention

1. [**Self-attention Does Not Need O(n^2) Memory.**](https://arxiv.org/abs/2112.05682) *Markus N. Rabe, Charles Staats.* Arxiv 2021.

2. [**Faster Causal Attention Over Large Sequences Through Sparse Flash Attention.**](https://arxiv.org/abs/2306.01160) *Matteo Pagliardini, Daniele Paliotta, Martin Jaggi, François Fleuret.* Arxiv 2023.

3. [**FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness.**](https://arxiv.org/abs/2205.14135) *Tri Dao, Daniel Y. Fu, Stefano Ermon, Atri Rudra, Christopher Ré.* Arxiv 2022.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Dao-AILab/flash-attention)](https://github.com/Dao-AILab/flash-attention)

4. [**FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning.**](https://arxiv.org/abs/2307.08691) *Tri Dao.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Dao-AILab/flash-attention)](https://github.com/Dao-AILab/flash-attention)

5. [**Efficient Memory Management for Large Language Model Serving with PagedAttention.**](https://arxiv.org/abs/2309.06180) *Woosuk Kwon, Zhuohan Li, Siyuan Zhuang, Ying Sheng, Lianmin Zheng, Cody Hao Yu, Joseph E. Gonzalez, Hao Zhang, Ion Stoica.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/vllm-project/vllm)](https://github.com/vllm-project/vllm)

6. [**TransNormerLLM: A Faster and Better Large Language Model with Improved TransNormer.**](https://arxiv.org/abs/2307.14995) *Zhen Qin, Dong Li, Weigao Sun, Weixuan Sun, Xuyang Shen, Xiaodong Han, Yunshen Wei, Baohong Lv, Xiao Luo, Yu Qiao, Yiran Zhong.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/TransnormerLLM)](https://github.com/OpenNLPLab/TransnormerLLM)

7. [**Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models.**](https://arxiv.org/abs/2401.04695) *Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention)](https://github.com/OpenNLPLab/lightning-attention)

8. [**ChunkAttention: Efficient Self-Attention with Prefix-Aware KV Cache and Two-Phase Partition.**](https://arxiv.org/abs/2402.15220) *Lu Ye, Ze Tao, Yong Huang, Yang Li.* Arxiv 2024.

9. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) *Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/SnapKV)](https://github.com/FasterDecoding/SnapKV)

10. [**Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs.**](https://openreview.net/forum?id=uNrFpDPMyo) *Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao.* ICLR 2024 Oral.

11. [**Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient Generative Inference.**](https://arxiv.org/abs/2403.09054) *Muhammad Adnan, Akhil Arunkumar, Gaurav Jain, Prashant J. Nair, Ilya Soloveychik, Purushotham Kamath.* Arxiv 2024.

12. [**Efficient LLM Inference with Kcache.**](https://arxiv.org/abs/2404.18057) *Qiaozhi He, Zhihua Wu.* Arxiv 2024.

13. [**You Only Cache Once: Decoder-Decoder Architectures for Language Models.**](https://arxiv.org/abs/2405.05254) *Yutao Sun, Li Dong, Yi Zhu, Shaohan Huang, Wenhui Wang, Shuming Ma, Quanlu Zhang, Jianyong Wang, Furu Wei.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/unilm)](https://github.com/microsoft/unilm/tree/master/YOCO)

14. [**Fast Transformer Decoding: One Write-Head is All You Need.**](https://arxiv.org/abs/1911.02150) *Noam Shazeer.* Arxiv 2019.

15. [**GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints.**](https://arxiv.org/abs/2305.13245) *Joshua Ainslie, James Lee-Thorp, Michiel de Jong, Yury Zemlyanskiy, Federico Lebrón, Sumit Sanghai.* Arxiv 2023.

16. [**DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model.**](https://arxiv.org/abs/2405.04434) *DeepSeek-AI.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2)](https://github.com/deepseek-ai/DeepSeek-V2)

17. [**Layer-Condensed KV Cache for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2405.10637) *Haoyi Wu, Kewei Tu.* ACL 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

18. [**Reducing Transformer Key-Value Cache Size with Cross-Layer Attention.**](https://arxiv.org/abs/2405.12981) *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly.* Arxiv 2024.

19. [**PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference.**](https://arxiv.org/abs/2405.12532) *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mutonix/pyramidinfer)](https://github.com/mutonix/pyramidinfer)

20. [**Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression.**](https://arxiv.org/abs/2405.12591) *Peiyu Liu, Ze-Feng Gao, Wayne Xin Zhao, Yipeng Ma, Tao Wang, Ji-Rong Wen.* Arxiv 2024.

21. [**MiniCache: KV Cache Compression in Depth Dimension for Large Language Models.**](https://arxiv.org/abs/2405.14366) *Akide Liu, Jing Liu, Zizheng Pan, Yefei He, Gholamreza Haffari, Bohan Zhuang.* NeurIPS 2024.

22. [**PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling.**](https://arxiv.org/abs/2406.02069) *Zefan Cai., Yichi Zhang, Bofei Gao, Tianyu Liu, Keming Lu, Wayne Xiong, Yue Dong, Baobao Chang, Junjie Hu, Wen Xiao.* Arxiv 2024.

23. [**Effectively Compress KV Heads for LLM.**](https://arxiv.org/abs/2406.07056) *Hao Yu, Zelan Yang, Shen Li, Yong Li, Jianxin Wu.* Arxiv 2024.

24. [**A Simple and Effective L2 Norm-Based Strategy for KV Cache Compression.**](https://arxiv.org/abs/2406.11430) *Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini.* Arxiv 2024.

25. [**Quest: Query-Aware Sparsity for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2406.10774) *Jiaming Tang, Yilong Zhao, Kan Zhu, Guangxuan Xiao, Baris Kasikci, Song Han.* ICML 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/Quest)](https://github.com/mit-han-lab/Quest)

26. [**Attention Score is not All You Need for Token Importance Indicator in KV Cache Reduction: Value Also Matters.**](https://arxiv.org/abs/2406.12335) *Zhiyu Guo, Hidetaka Kamigaito, Taro Watanabe.* Arxiv 2024.

27. [**CItruS: Chunked Instruction-aware State Eviction for Long Sequence Modeling.**](https://arxiv.org/abs/2406.12018) *Yu Bai, Xiyuan Zou, Heyan Huang, Sanxing Chen, Marc-Antoine Rondeau, Yang Gao, Jackie Chi Kit Cheung.* Arxiv 2024.

28. [**D2O: Dynamic Discriminative Operations for Efficient Generative Inference of Large Language Models.**](https://arxiv.org/abs/2406.13035) *Zhongwei Wan, Xinjian Wu, Yu Zhang, Yi Xin, Chaofan Tao, Zhihong Zhu, Xin Wang, Siqi Luo, Jing Xiong, Mi Zhang.* Arxiv 2024.

29. [**MoA: Mixture of Sparse Attention for Automatic Large Language Model Compression.**](https://arxiv.org/abs/2406.14909) *Weiyao Luo, Suncong Zheng, Heming Xia, Weikang Wang, Yan Lei, Tianyu Liu, Shuang Chen, Zhifang Sui.* Arxiv 2024.

30. [**LOOK-M: Look-Once Optimization in KV Cache for Efficient Multimodal Long-Context Inference.**](https://arxiv.org/abs/2406.18139) *Zhongwei Wan, Ziang Wu, Che Liu, Jinfa Huang, Zhihong Zhu, Peng Jin, Longyue Wang, Li Yuan.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SUSTechBruce/LOOK-M)](https://github.com/SUSTechBruce/LOOK-M)

31. [**Training-Free Exponential Extension of Sliding Window Context with Cascading KV Cache.**](https://arxiv.org/abs/2406.17808) *Jeffrey Willette, Heejun Lee, Youngwan Lee, Myeongjae Jeon, Sung Ju Hwang.* Arxiv 2024.

32. [**QuickLLaMA: Query-aware Inference Acceleration for Large Language Models.**](https://arxiv.org/abs/2406.07528) *Jingyao Li, Han Shi, Xin Jiang, Zhenguo Li, Hong Xu, Jiaya Jia.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/Q-LLM)](https://github.com/dvlab-research/Q-LLM)

33. [**MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention.**](https://arxiv.org/abs/2407.02490) *Huiqiang Jiang, Yucheng Li, Chengruidong Zhang, Qianhui Wu, Xufang Luo, Surin Ahn, Zhenhua Han, Amir H. Abdi, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://hqjiang.com/minference.html)

34. [**Model Tells You Where to Merge: Adaptive KV Cache Merging for LLMs on Long-Context Tasks.**](https://arxiv.org/abs/2407.08454) *Zheng Wang, Boxiao Jin, Zhongzhi Yu, Minjia Zhang.* Arxiv 2024.

35. [**Optimizing KV Cache Eviction in LLMs: Adaptive Allocation for Enhanced Budget Utilization.**](https://arxiv.org/abs/2407.11550) *Yuan Feng, Junlin Lv, Yukun Cao, Xike Xie, S. Kevin Zhou.* Arxiv 2024.

36. [**Beyond KV Caching: Shared Attention for Efficient LLMs.**](https://arxiv.org/abs/2407.12866) *Bingli Liao, Danilo Vasconcellos Vargas.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/metacarbon/shareAtt)](https://github.com/metacarbon/shareAtt)

37. [**PQCache: Product Quantization-based KVCache for Long Context LLM Inference.**](https://arxiv.org/abs/2407.12820) *Hailin Zhang, Xiaodong Ji, Yilin Chen, Fangcheng Fu, Xupeng Miao, Xiaonan Nie, Weipeng Chen, Bin Cui.* Arxiv 2024.

38. [**LazyLLM: Dynamic Token Pruning for Efficient Long Context LLM Inference.**](https://arxiv.org/abs/2407.14057) *Qichen Fu, Minsik Cho, Thomas Merth, Sachin Mehta, Mohammad Rastegari, Mahyar Najibi.* Arxiv 2024.

39. [**Farewell to Length Extrapolation, a Training-Free Infinite Context with Finite Attention Scope.**](https://arxiv.org/abs/2407.15176) *Xiaoran Liu, Qipeng Guo, Yuerong Song, Zhigeng Liu, Kai Lv, Hang Yan, Linlin Li, Qun Liu, Xipeng Qiu.* Arxiv 2024.

40. [**RazorAttention: Efficient KV Cache Compression Through Retrieval Heads.**](https://arxiv.org/abs/2407.15891) *Hanlin Tang, Yang Lin, Jing Lin, Qingsen Han, Shikuan Hong, Yiwu Yao, Gongyi Wang.* Arxiv 2024.

41. [**FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision.**](https://arxiv.org/abs/2407.08608) *Jay Shah, Ganesh Bikshandi, Ying Zhang, Vijay Thakkar, Pradeep Ramani, Tri Dao.* Arxiv 2024.

42. [**ThinK: Thinner Key Cache by Query-Driven Pruning.**](https://arxiv.org/abs/2407.21018) *Yuhui Xu, Zhanming Jie, Hanze Dong, Lei Wang, Xudong Lu, Aojun Zhou, Amrita Saha, Caiming Xiong, Doyen Sahoo.* Arxiv 2024.

43. [**A2SF: Accumulative Attention Scoring with Forgetting Factor for Token Pruning in Transformer Decoder.**](https://arxiv.org/abs/2407.20485) *Hyun-rae Jo, Dongkun Shin.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Dirac-Notation/A2SF)](https://github.com/Dirac-Notation/A2SF)

44. [**Cross-layer Attention Sharing for Large Language Models.**](https://arxiv.org/abs/2408.01890) *Yongyu Mu, Yuzhang Wu, Yuchun Fan, Chenglong Wang, Hengyu Li, Qiaozhi He, Murun Yang, Tong Xiao, Jingbo Zhu.* Arxiv 2024.

45. [**NACL: A General and Effective KV Cache Eviction Framework for LLMs at Inference Time.**](https://arxiv.org/abs/2408.03675) *Yilong Chen, Guoxia Wang, Junyuan Shang, Shiyao Cui, Zhenyu Zhang, Tingwen Liu, Shuohuan Wang, Yu Sun, Dianhai Yu, Hua Wu.* ACL 2024.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/PaddlePaddle/Research)](https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2024-NACL)

46. [**Tree Attention: Topology-aware Decoding for Long-Context Attention on GPU clusters.**](https://arxiv.org/abs/2408.04093) *Vasudev Shyam, Jonathan Pilault, Emily Shepperd, Quentin Anthony, Beren Millidge.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Zyphra/tree_attention)](https://github.com/Zyphra/tree_attention)

47. [**MagicDec: Breaking the Latency-Throughput Tradeoff for Long Context Generation with Speculative Decoding.**](https://arxiv.org/abs/2408.11049) *Jian Chen, Vashisth Tiwari, Ranajoy Sadhukhan, Zhuoming Chen, Jinyuan Shi, Ian En-Hsu Yen, Beidi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicDec)](https://github.com/Infini-AI-Lab/MagicDec/)

48. [**CSKV: Training-Efficient Channel Shrinking for KV Cache in Long-Context Scenarios.**](https://arxiv.org/abs/2409.10593) *Luning Wang, Shiyao Li, Xuefei Ning, Zhihang Yuan, Shengen Yan, Guohao Dai, Yu Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/wln20/cskv)](https://github.com/wln20/cskv/)

49. [**RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval.**](https://arxiv.org/abs/2409.10516) *Di Liu, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang, Qi Chen, Chengruidong Zhang, Bailu Ding, Kai Zhang, Chen Chen, Fan Yang, Yuqing Yang, Lili Qiu.* Arxiv 2024.

50. [**InstInfer: In-Storage Attention Offloading for Cost-Effective Long-Context LLM Inference.**](https://arxiv.org/abs/2409.04992) *Xiurui Pan, Endian Li, Qiao Li, Shengwen Liang, Yizhou Shan, Ke Zhou, Yingwei Luo, Xiaolin Wang, Jie Zhang.* Arxiv 2024.

51. [**CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs.**](https://arxiv.org/abs/2409.12490) *Junlin Lv, Yuan Feng, Xike Xie, Xin Jia, Qirong Peng, Guiming Xie.* Arxiv 2024.

52. [**Discovering the Gems in Early Layers: Accelerating Long-Context LLMs with 1000x Input Token Reduction.**](https://arxiv.org/abs/2409.17422) *Zhenmei Shi, Yifei Ming, Xuan-Phi Nguyen, Yingyu Liang, Shafiq Joty.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SalesforceAIResearch/GemFilter)](https://github.com/SalesforceAIResearch/GemFilter)

53. [**Inference-Friendly Models With MixAttention.**](https://arxiv.org/abs/2409.15012) *Shashank Rajput, Ying Sheng, Sean Owen, Vitaliy Chiley.* Arxiv 2024.

54. [**KV-Compress: Paged KV-Cache Compression with Variable Compression Rates per Attention Head.**](https://arxiv.org/abs/2410.00161) *Isaac Rehg.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/IsaacRe/vllm-kvcompress)](https://github.com/IsaacRe/vllm-kvcompress)

55. [**Locret: Enhancing Eviction in Long-Context LLM Inference with Trained Retaining Heads.**](https://arxiv.org/abs/2410.01805) *Yuxiang Huang, Binhang Yuan, Xu Han, Chaojun Xiao, Zhiyuan Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/huangyuxiang03/Locret)](https://github.com/huangyuxiang03/Locret)

56. [**InfiniPot: Infinite Context Processing on Memory-Constrained LLMs.**](https://arxiv.org/abs/2410.01518) *Minsoo Kim, Kyuhong Shim, Jungwook Choi, Simyung Chang.* Arxiv 2024.

57. [**UNComp: Uncertainty-Aware Long-Context Compressor for Efficient Large Language Model Inference.**](https://arxiv.org/abs/2410.03090) *Jing Xiong, Jianghan Shen, Fanghua Ye, Chaofan Tao, Zhongwei Wan, Jianqiao Lu, Xun Wu, Chuanyang Zheng, Zhijiang Guo, Lingpeng Kong, Ngai Wong.* Arxiv 2024.

58. [**LoRC: Low-Rank Compression for LLMs KV Cache with a Progressive Compression Strategy.**](https://arxiv.org/abs/2410.03111) *Rongzhi Zhang, Kuang Wang, Liyuan Liu, Shuohang Wang, Hao Cheng, Chao Zhang, Yelong Shen.* Arxiv 2024.

59. [**DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads.**](https://arxiv.org/abs/2410.10819) *Guangxuan Xiao, Jiaming Tang, Jingwei Zuo, Junxian Guo, Shang Yang, Haotian Tang, Yao Fu, Song Han.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/duo-attention)](https://github.com/mit-han-lab/duo-attention)

60. [**In-context KV-Cache Eviction for LLMs via Attention-Gate.**](https://arxiv.org/abs/2410.12876) *Zihao Zeng, Bokai Lin, Tianqi Hou, Hao Zhang, Zhijie Deng.* Arxiv 2024.

61. [**SimLayerKV: A Simple Framework for Layer-Level KV Cache Reduction.**](https://arxiv.org/abs/2410.13846) *Xuan Zhang, Cunxiao Du, Chao Du, Tianyu Pang, Wei Gao, Min Lin.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/SimLayerKV)](https://github.com/sail-sg/SimLayerKV)

62. [**A Systematic Study of Cross-Layer KV Sharing for Efficient LLM Inference.**](https://arxiv.org/abs/2410.14442) *You Wu, Haoyi Wu, Kewei Tu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

63. [**KVSharer: Efficient Inference via Layer-Wise Dissimilar KV Cache Sharing.**](https://arxiv.org/abs/2410.18517) *Yifei Yang, Zouying Cao, Qiguang Chen, Libo Qin, Dongjie Yang, Hai Zhao, Zhi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yangyifei729/KVSharer)](https://github.com/yangyifei729/KVSharer)

63. [**Lossless KV Cache Compression to 2%.**](https://arxiv.org/abs/2410.15252) *Zhen Yang, J.N.Han, Kan Wu, Ruobing Xie, An Wang, Xingwu Sun, Zhanhui Kang.* Arxiv 2024.

64. [**MatryoshkaKV: Adaptive KV Compression via Trainable Orthogonal Projection.**](https://arxiv.org/abs/2410.14731) *Bokai Lin, Zihao Zeng, Zipeng Xiao, Siqi Kou, Tianqi Hou, Xiaofeng Gao, Hao Zhang, Zhijie Deng.* Arxiv 2024.

65. [**EPIC: Efficient Position-Independent Context Caching for Serving Large Language Models.**](https://arxiv.org/abs/2410.15332) *Junhao Hu, Wenrui Huang, Haoyi Wang, Weidong Wang, Tiancheng Hu, Qin Zhang, Hao Feng, Xusheng Chen, Yizhou Shan, Tao Xie.* Arxiv 2024.

66. [**MagicPIG: LSH Sampling for Efficient LLM Generation.**](https://arxiv.org/abs/2410.16179) *Zhuoming Chen, Ranajoy Sadhukhan, Zihao Ye, Yang Zhou, Jianyu Zhang, Niklas Nolte, Yuandong Tian, Matthijs Douze, Leon Bottou, Zhihao Jia, Beidi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicPIG)](https://github.com/Infini-AI-Lab/MagicPIG)

67. [**Not All Heads Matter: A Head-Level KV Cache Compression Method with Integrated Retrieval and Reasoning.**](https://arxiv.org/abs/2410.19258) *Yu Fu, Zefan Cai, Abedelkadir Asi, Wayne Xiong, Yue Dong, Wen Xiao.* Arxiv 2024.

68. [**Long Sequence Modeling with Attention Tensorization: From Sequence to Tensor Learning.**](https://arxiv.org/abs/2410.20926) *Aosong Feng, Rex Ying, Leandros Tassiulas.* Arxiv 2024.

69. [**ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference.**](https://arxiv.org/abs/2410.21465) *Hanshi Sun, Li-Wen Chang, Wenlei Bao, Size Zheng, Ningxin Zheng, Xin Liu, Harry Dong, Yuejie Chi, Beidi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ShadowKV)](https://github.com/bytedance/ShadowKV)

## 3. Recurrent Transformers

1. [**Transformer-XL: Attentive language models beyond a fixed-length context.**](https://arxiv.org/abs/1901.02860) *Zihang Dai, Zhilin Yang, Yiming Yang, Jaime Carbonell, Quoc V. Le, Ruslan Salakhutdinov.* ACL 2019.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kimiyoung/transformer-xl)](https://github.com/kimiyoung/transformer-xl)

2. [**Compressive Transformers for Long-Range Sequence Modelling.**](https://arxiv.org/abs/1911.05507) *Jack W. Rae, Anna Potapenko, Siddhant M. Jayakumar, Timothy P. Lillicrap.* Arxiv 2019.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/compressive-transformer-pytorch)](https://github.com/lucidrains/compressive-transformer-pytorch)

3. [**Memformer: The memory-augmented transformer.**](https://arxiv.org/abs/2010.06891) *Qingyang Wu, Zhenzhong Lan, Kun Qian, Jing Gu, Alborz Geramifard, Zhou Yu.* Arxiv 2020.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/memformer)](https://github.com/lucidrains/memformer)

4. [**ERNIE-Doc: A Retrospective Long-Document Modeling Transformer.**](https://aclanthology.org/2021.acl-long.227/) *SiYu Ding, Junyuan Shang, Shuohuan Wang, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang.* ACL-IJCNLP 2021. 

5. [**Memorizing Transformers.**](https://arxiv.org/abs/2203.08913) *Yuhuai Wu, Markus N. Rabe, DeLesley Hutchins, Christian Szegedy.* Arxiv 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/memorizing-transformers-pytorch)](https://github.com/lucidrains/memorizing-transformers-pytorch)

6. [**Recurrent Attention Networks for Long-text Modeling.**](https://aclanthology.org/2023.findings-acl.188/) *Xianming Li, Zongxi Li, Xiaotian Luo, Haoran Xie, Xing Lee, Yingbin Zhao, Fu Lee Wang, Qing Li.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/4ai/ran)](https://github.com/4ai/ran)

7. [**RWKV: Reinventing RNNs for the Transformer Era.**](https://arxiv.org/abs/2305.13048) *Bo Peng, Eric Alcaide, Quentin Anthony, Alon Albalak, Samuel Arcadinho, Huanqi Cao, Xin Cheng, Michael Chung, Matteo Grella, Kranthi Kiran GV, Xuzheng He, Haowen Hou, Przemyslaw Kazienko, Jan Kocon, Jiaming Kong, Bartlomiej Koptyra, Hayden Lau, Krishna Sri Ipsit Mantri, Ferdinand Mom, Atsushi Saito, Xiangru Tang, Bolun Wang, Johan S. Wind, Stansilaw Wozniak, Ruichong Zhang, Zhenyuan Zhang, Qihang Zhao, Peng Zhou, Jian Zhu, Rui-Jie Zhu.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/BlinkDL/RWKV-LM)](https://github.com/BlinkDL/RWKV-LM)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/BlinkDL/ChatRWKV)](https://github.com/BlinkDL/ChatRWKV)

8. [**Segmented Recurrent Transformer: An Efficient Sequence-to-Sequence Model.**](https://arxiv.org/abs/2305.16340) *Yinghan Long, Sayeed Shafayet Chowdhury, Kaushik Roy.* Arxiv 2023. 

9. [**Scaling Transformer to 1M tokens and beyond with RMT.**](https://arxiv.org/abs/2304.11062) *Aydar Bulatov, Yuri Kuratov, Mikhail S. Burtsev.* Arxiv 2023. 

10. [**Block-Recurrent Transformers.**](https://arxiv.org/abs/2203.07852) *DeLesley Hutchins, Imanol Schlag, Yuhuai Wu, Ethan Dyer, Behnam Neyshabur.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/block-recurrent-transformer-pytorch)](https://github.com/lucidrains/block-recurrent-transformer-pytorch)

11. [**TRAMS: Training-free Memory Selection for Long-range Language Modeling.**](https://arxiv.org/abs/2310.15494) *Haofei Yu, Cunxiang Wang, Yue Zhang, Wei Bi.* Arxiv 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lwaekfjlk/TRAMS)](https://github.com/lwaekfjlk/TRAMS)

12. [**Griffin: Mixing Gated Linear Recurrences with Local Attention for Efficient Language Models.**](https://arxiv.org/abs/2402.19427) *Soham De, Samuel L. Smith, Anushan Fernando, Aleksandar Botev, George Cristian-Muraru, Albert Gu, Ruba Haroun, Leonard Berrada, Yutian Chen, Srivatsan Srinivasan, Guillaume Desjardins, Arnaud Doucet, David Budden, Yee Whye Teh, Razvan Pascanu, Nando De Freitas, Caglar Gulcehre.* Arxiv 2024. 

13. [**Extensible Embedding: A Flexible Multipler For LLM's Context Length.**](https://arxiv.org/abs/2402.11577) *Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

14. [**Eagle and Finch: RWKV with Matrix-Valued States and Dynamic Recurrence.**](https://arxiv.org/abs/2404.05892) *Bo Peng, Daniel Goldstein, Quentin Anthony, Alon Albalak, Eric Alcaide, Stella Biderman, Eugene Cheah, Teddy Ferdinan, Haowen Hou, Przemysław Kazienko, Kranthi Kiran GV, Jan Kocoń, Bartłomiej Koptyra, Satyapriya Krishna, Ronald McClelland Jr., Niklas Muennighoff, Fares Obeid, Atsushi Saito, Guangyu Song, Haoqin Tu, Stanisław Woźniak, Ruichong Zhang, Bingchen Zhao, Qihang Zhao, Peng Zhou, Jian Zhu, Rui-Jie Zhu.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RWKV/RWKV-LM)](https://github.com/RWKV/RWKV-LM)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RWKV/ChatRWKV)](https://github.com/RWKV/ChatRWKV)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RWKV/RWKV-infctx-trainer)](https://github.com/RWKV/RWKV-infctx-trainer)

15. [**Leave No Context Behind: Efficient Infinite Context Transformers with Infini-attention.**](https://arxiv.org/abs/2404.07143) *Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal.* Arxiv 2024. 

16. [**RecurrentGemma: Moving Past Transformers for Efficient Open Language Models.**](https://arxiv.org/abs/2404.07839) *Aleksandar Botev, Soham De, Samuel L Smith, Anushan Fernando, George-Cristian Muraru, Ruba Haroun, Leonard Berrada, Razvan Pascanu, Pier Giuseppe Sessa, Robert Dadashi, Léonard Hussenot, Johan Ferret, Sertan Girgin, Olivier Bachem, Alek Andreev, Kathleen Kenealy, Thomas Mesnard, Cassidy Hardin, Surya Bhupatiraju, Shreya Pathak, Laurent Sifre, Morgane Rivière, Mihir Sanjay Kale, Juliette Love, Pouya Tafti, Armand Joulin, Noah Fiedel, Evan Senter, Yutian Chen, Srivatsan Srinivasan, Guillaume Desjardins, David Budden, Arnaud Doucet, Sharad Vikram, Adam Paszke, Trevor Gale, Sebastian Borgeaud, Charlie Chen, Andy Brock, Antonia Paterson, Jenny Brennan, Meg Risdal, Raj Gundluru, Nesh Devanathan, Paul Mooney, Nilay Chauhan, Phil Culliton, Luiz GUStavo Martins, Elisa Bandy, David Huntsperger, Glenn Cameron, Arthur Zucker, Tris Warkentin, Ludovic Peran, Minh Giang, Zoubin Ghahramani, Clément Farabet, Koray Kavukcuoglu, Demis Hassabis, Raia Hadsell, Yee Whye Teh, Nando de Frietas.* Arxiv 2024. 

17. [**Linearizing Large Language Models.**](https://arxiv.org/abs/2405.06640) *Jean Mercat, Igor Vasiljevic, Sedrick Keh, Kushal Arora, Achal Dave, Adrien Gaidon, Thomas Kollar.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TRI-ML/linear_open_lm)](https://github.com/TRI-ML/linear_open_lm)

18. [**VisualRWKV: Exploring Recurrent Neural Networks for Visual Language Models.**](https://arxiv.org/abs/2406.13362) *Haowen Hou, Peigen Zeng, Fei Ma, Fei Richard Yu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/howard-hou/VisualRWKV)](https://github.com/howard-hou/VisualRWKV)

19. [**Just read twice: closing the recall gap for recurrent language models.**](https://arxiv.org/abs/2407.05483) *Simran Arora, Aman Timalsina, Aaryan Singhal, Benjamin Spector, Sabri Eyuboglu, Xinyi Zhao, Ashish Rao, Atri Rudra, Christopher Ré.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/prefix-linear-attention)](https://github.com/HazyResearch/prefix-linear-attention)

20. [**Associative Recurrent Memory Transformer.**](https://arxiv.org/abs/2407.04841) *Ivan Rodkin, Yuri Kuratov, Aydar Bulatov, Mikhail Burtsev.* ICML 2024 Workshop.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RodkinIvan/associative-recurrent-memory-transformer)](https://github.com/RodkinIvan/associative-recurrent-memory-transformer)

21. [**GoldFinch: High Performance RWKV/Transformer Hybrid with Linear Pre-Fill and Extreme KV-Cache Compression.**](https://arxiv.org/abs/2407.12077) *Daniel Goldstein, Fares Obeid, Eric Alcaide, Guangyu Song, Eugene Cheah.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/recursal/GoldFinch-paper)](https://github.com/recursal/GoldFinch-paper)

22. [**Analysis of Argument Structure Constructions in a Deep Recurrent Language Model.**](https://arxiv.org/abs/2408.03062) *Pegah Ramezani, Achim Schilling, Patrick Krauss.* Arxiv 2024.

## 4. State Space Models

1. [**Mamba: Linear-Time Sequence Modeling with Selective State Spaces.**](https://arxiv.org/abs/2312.00752) *Albert Gu, Tri Dao.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/state-spaces/mamba)](https://github.com/state-spaces/mamba)

2. [**MoE-Mamba: Efficient Selective State Space Models with Mixture of Experts.**](https://arxiv.org/abs/2401.04081) *Maciej Pióro, Kamil Ciebiera, Krystian Król, Jan Ludziejewski, Sebastian Jaszczur.* Arxiv 2024.

3. [**MambaByte: Token-free Selective State Space Model.**](https://arxiv.org/abs/2401.13660) *Junxiong Wang, Tushaar Gangavarapu, Jing Nathan Yan, Alexander M Rush.* Arxiv 2024.

4. [**LOCOST: State-Space Models for Long Document Abstractive Summarization.**](https://arxiv.org/abs/2401.17919) *Florian Le Bronnec, Song Duong, Mathieu Ravaut, Alexandre Allauzen, Nancy F. Chen, Vincent Guigue, Alberto Lumbreras, Laure Soulier, Patrick Gallinari.* Arxiv 2024.

5. [**State Space Models as Foundation Models: A Control Theoretic Overview.**](https://arxiv.org/abs/2403.16899) *Carmen Amo Alonso, Jerome Sieber, Melanie N. Zeilinger.* Arxiv 2024.

6. [**Jamba: A Hybrid Transformer-Mamba Language Model.**](https://arxiv.org/abs/2403.19887) *Opher Lieber, Barak Lenz, Hofit Bata, Gal Cohen, Jhonathan Osin, Itay Dalmedigos, Erez Safahi, Shaked Meirom, Yonatan Belinkov, Shai Shalev-Shwartz, Omri Abend, Raz Alon, Tomer Asida, Amir Bergman, Roman Glozman, Michael Gokhman, Avashalom Manevich, Nir Ratner, Noam Rozen, Erez Shwartz, Mor Zusman, Yoav Shoham.* Arxiv 2024.

7. [**Robustifying State-space Models for Long Sequences via Approximate Diagonalization.**](https://openreview.net/forum?id=DjeQ39QoLQ) *Annan Yu, Arnur Nigmetov, Dmitriy Morozov, Michael W. Mahoney, N. Benjamin Erichson.* ICLR 2024 Spotlight.

8. [**Zamba: A Compact 7B SSM Hybrid Model.**](https://arxiv.org/abs/2405.16712) *Paolo Glorioso, Quentin Anthony, Yury Tokpanov, James Whittington, Jonathan Pilault, Adam Ibrahim, Beren Millidge.* Arxiv 2024.

9. [**Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality.**](https://arxiv.org/abs/2405.21060) *Tri Dao, Albert Gu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/state-spaces/mamba)](https://github.com/state-spaces/mamba)

10. [**Samba: Simple Hybrid State Space Models for Efficient Unlimited Context Language Modeling.**](https://arxiv.org/abs/2406.07522) *Liliang Ren, Yang Liu, Yadong Lu, Yelong Shen, Chen Liang, Weizhu Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/Samba)](https://github.com/microsoft/Samba)

11. [**An Empirical Study of Mamba-based Language Models.**](https://arxiv.org/abs/2406.07887) *Roger Waleffe, Wonmin Byeon, Duncan Riach, Brandon Norick, Vijay Korthikanti, Tri Dao, Albert Gu, Ali Hatamizadeh, Sudhakar Singh, Deepak Narayanan, Garvit Kulshreshtha, Vartika Singh, Jared Casper, Jan Kautz, Mohammad Shoeybi, Bryan Catanzaro.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM)](https://github.com/NVIDIA/Megatron-LM/tree/ssm/examples/mamba)

12. [**B'MOJO: Hybrid State Space Realizations of Foundation Models with Eidetic and Fading Memory.**](https://arxiv.org/abs/2407.06324) *Luca Zancato, Arjun Seshadri, Yonatan Dukler, Aditya Golatkar, Yantao Shen, Benjamin Bowman, Matthew Trager, Alessandro Achille, Stefano Soatto.* Arxiv 2024.

13. [**MambaForGCN: Enhancing Long-Range Dependency with State Space Model and Kolmogorov-Arnold Networks for Aspect-Based Sentiment Analysis.**](https://arxiv.org/abs/2407.10347) *Adamu Lawan, Juhua Pu, Haruna Yunusa, Aliyu Umar, Muhammad Lawan.* Arxiv 2024.

14. [**Discrete Diffusion Language Model for Long Text Summarization.**](https://arxiv.org/abs/2407.10998) *Do Huu Dat, Do Duc Anh, Anh Tuan Luu, Wray Buntine.* Arxiv 2024.

15. [**ML-Mamba: Efficient Multi-Modal Large Language Model Utilizing Mamba-2.**](https://arxiv.org/abs/2407.19832) *Wenjun Huang, Jianguo Hu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WenjunHuang94/ML-Mamba)](https://github.com/WenjunHuang94/ML-Mamba)

16. [**Jamba-1.5: Hybrid Transformer-Mamba Models at Scale.**](https://arxiv.org/abs/2408.12570) *Jamba Team: Barak Lenz, Alan Arazi, Amir Bergman, Avshalom Manevich, Barak Peleg, Ben Aviram, Chen Almagor, Clara Fridman, Dan Padnos, Daniel Gissin, Daniel Jannai, Dor Muhlgay, Dor Zimberg, Edden M Gerber, Elad Dolev, Eran Krakovsky, Erez Safahi, Erez Schwartz, Gal Cohen, Gal Shachaf, Haim Rozenblum, Hofit Bata, Ido Blass, Inbal Magar, Itay Dalmedigos, Jhonathan Osin, Julie Fadlon, Maria Rozman, Matan Danos, Michael Gokhman, Mor Zusman, Naama Gidron, Nir Ratner, Noam Gat, Noam Rozen, Oded Fried, Ohad Leshno, Omer Antverg, Omri Abend, Opher Lieber, Or Dagan, Orit Cohavi, Raz Alon, Ro'i Belson, Roi Cohen, Rom Gilad, Roman Glozman, Shahar Lev, Shaked Meirom, Tal Delbari, Tal Ness, Tomer Asida, Tom Ben Gal, Tom Braude, Uriya Pumerantz, Yehoshua Cohen, Yonatan Belinkov, Yuval Globerson, Yuval Peleg Levy, Yoav Shoham.* Arxiv 2024.

17. [**SpikingSSMs: Learning Long Sequences with Sparse and Parallel Spiking State Space Models.**](https://arxiv.org/abs/2408.14909) *Shuaijie Shen, Chao Wang, Renzhuo Huang, Yan Zhong, Qinghai Guo, Zhichao Lu, Jianguo Zhang, Luziwei Leng.* Arxiv 2024.

18. [**ReMamba: Equip Mamba with Effective Long-Sequence Modeling.**](https://arxiv.org/abs/2408.15496) *Danlong Yuan, Jiahao Liu, Bei Li, Huishuai Zhang, Jingang Wang, Xunliang Cai, Dongyan Zhao.* Arxiv 2024.

19. [**Stuffed Mamba: State Collapse and State Capacity of RNN-Based Long-Context Modeling.**](https://arxiv.org/abs/2410.07145) *Yingfa Chen, Xinrong Zhang, Shengding Hu, Xu Han, Zhiyuan Liu, Maosong Sun.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/stuffed-mamba)](https://github.com/thunlp/stuffed-mamba)

20. [**Taipan: Efficient and Expressive State Space Language Models with Selective Attention.**](https://arxiv.org/abs/2410.18572) *Chien Van Nguyen, Huy Huu Nguyen, Thang M. Pham, Ruiyi Zhang, Hanieh Deilamsalehy, Puneet Mathur, Ryan A. Rossi, Trung Bui, Viet Dac Lai, Franck Dernoncourt, Thien Huu Nguyen.* Arxiv 2024.

21. [**Rethinking Token Reduction for State Space Models.**](https://arxiv.org/abs/2410.14725) *Zheng Zhan, Yushu Wu, Zhenglun Kong, Changdi Yang, Yifan Gong, Xuan Shen, Xue Lin, Pu Zhao, Yanzhi Wang.* EMNLP 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/wuyushuwys/ToR_SSM)](https://github.com/wuyushuwys/ToR_SSM)

## 5. Length Extrapolation

1. [**RoFormer: Enhanced Transformer with Rotary Position Embedding.**](https://arxiv.org/abs/2104.09864) *Jianlin Su, Yu Lu, Shengfeng Pan, Ahmed Murtadha, Bo Wen, Yunfeng Liu.* Arxiv 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ZhuiyiTechnology/roformer)](https://github.com/ZhuiyiTechnology/roformer)

2. [**Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation.**](https://arxiv.org/abs/2108.12409) *Ofir Press, Noah A. Smith, Mike Lewis.* ICLR 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ofirpress/attention_with_linear_biases)](https://github.com/ofirpress/attention_with_linear_biases)

3. [**KERPLE: Kernelized Relative Positional Embedding for Length Extrapolation.**](https://arxiv.org/abs/2205.09921) *Ta-Chung Chi, Ting-Han Fan, Peter J. Ramadge, Alexander I. Rudnicky.* Arxiv 2022. 

4. [**Dissecting Transformer Length Extrapolation via the Lens of Receptive Field Analysis.**](https://aclanthology.org/2023.acl-long.756/) *Ta-Chung Chi, Ting-Han Fan, Alexander I. Rudnicky, Peter J. Ramadge.* ACL 2023. 

5. [**A Length-Extrapolatable Transformer.**](https://aclanthology.org/2023.acl-long.816/) *Yutao Sun, Li Dong, Barun Patra, Shuming Ma, Shaohan Huang, Alon Benhaim, Vishrav Chaudhary, Xia Song, Furu Wei.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sunyt32/torchscale)](https://github.com/sunyt32/torchscale)

6. [**Randomized Positional Encodings Boost Length Generalization of Transformers.**](https://aclanthology.org/2023.acl-short.161/) *Anian Ruoss, Grégoire Delétang, Tim Genewein, Jordi Grau-Moya, Róbert Csordás, Mehdi Bennani, Shane Legg, Joel Veness.* ACL 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/randomized_positional_encodings)](https://github.com/google-deepmind/randomized_positional_encodings)

7. [**The Impact of Positional Encoding on Length Generalization in Transformers.**](https://arxiv.org/abs/2305.19466) *Amirhossein Kazemnejad, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Payel Das, Siva Reddy.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/McGill-NLP/length-generalization)](https://github.com/McGill-NLP/length-generalization)

8. [**Focused Transformer: Contrastive Training for Context Scaling.**](https://arxiv.org/abs/2307.03170) *Szymon Tworkowski, Konrad Staniszewski, Mikołaj Pacek, Yuhuai Wu, Henryk Michalewski, Piotr Miłoś.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/CStanKonrad/long_llama)](https://github.com/CStanKonrad/long_llama)

9. [**Extending Context Window of Large Language Models via Positional Interpolation.**](https://arxiv.org/abs/2306.15595) *Shouyuan Chen, Sherman Wong, Liangjian Chen, Yuandong Tian.* Arxiv 2023. 

10. [**Exploring Transformer Extrapolation.**](https://arxiv.org/abs/2307.10156) *Zhen Qin, Yiran Zhong, Hui Deng.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/Rpe)](https://github.com/OpenNLPLab/Rpe)

11. [**LM-Infinite: Simple On-the-Fly Length Generalization for Large Language Models.**](https://arxiv.org/pdf/2308.16137.pdf) *Chi Han, Qifan Wang, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/LM-Infinite)](https://github.com/kyegomez/LM-Infinite)

12. [**YaRN: Efficient Context Window Extension of Large Language Models.**](https://arxiv.org/abs/2309.00071) *Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/jquesnelle/yarn)](https://github.com/jquesnelle/yarn)

13. [**PoSE: Efficient Context Window Extension of LLMs via Positional Skip-wise Training.**](https://arxiv.org/abs/2309.10400) *Dawei Zhu,Nan Yang,Liang Wang,Yifan Song,Wenhao Wu,Furu Wei,Sujian Li.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/PoSE)](https://github.com/dwzhu-pku/PoSE)

14. [**LongLoRA: Efficient Fine-tuning of Long-Context Large Language Models.**](https://arxiv.org/abs/2309.12307) *Yukang Chen, Shengju Qian, Haotian Tang, Xin Lai, Zhijian Liu, Song Han, Jiaya Jia.* ICLR 2024 Oral.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/LongLoRA)](https://github.com/dvlab-research/LongLoRA)

15. [**Scaling Laws of RoPE-based Extrapolation.**](https://arxiv.org/abs/2310.05209) *Xiaoran Liu, Hang Yan, Shuo Zhang, Chenxin An, Xipeng Qiu, Dahua Lin.* Arxiv 2023.

16. [**Attention Alignment and Flexible Positional Embeddings Improve Transformer Length Extrapolation.**](https://arxiv.org/pdf/2311.00684v1.pdf) *Ta-Chung Chi,Ting-Han Fan,Alexander I. Rudnicky.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chijames/Attention-Alignment-Transformer-Length-Extrapolation)](https://github.com/chijames/Attention-Alignment-Transformer-Length-Extrapolation)

17. [**CoCA: Fusing position embedding with Collinear Constrained Attention for fine-tuning free context window extending.**](https://arxiv.org/abs/2309.08646) *Shiyi Zhu, Jing Ye, Wei Jiang, Qi Zhang, Yifan Wu, Jianguo Li.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/codefuse-ai/Collinear-Constrained-Attention)](https://github.com/codefuse-ai/Collinear-Constrained-Attention)

18. [**Structured Packing in LLM Training Improves Long Context Utilization.**](https://arxiv.org/abs/2312.17296) *Konrad Staniszewski, Szymon Tworkowski, Sebastian Jaszczur, Henryk Michalewski, Łukasz Kuciński, Piotr Miłoś.* Arxiv 2024.

19. [**LLM Maybe LongLM: Self-Extend LLM Context Window Without Tuning.**](https://arxiv.org/abs/2401.01325v1) *Hongye Jin, Xiaotian Han, Jingfeng Yang, Zhimeng Jiang, Zirui Liu, Chia-Yuan Chang, Huiyuan Chen, Xia Hu.* Arxiv 2024.

20. [**Infinite-LLM: Efficient LLM Service for Long Context with DistAttention and Distributed KVCache.**](https://arxiv.org/abs/2401.02669) *Bin Lin, Tao Peng, Chen Zhang, Minmin Sun, Lanbo Li, Hanyu Zhao, Wencong Xiao, Qi Xu, Xiafei Qiu, Shen Li, Zhigang Ji, Yong Li, Wei Lin.* Arxiv 2024.

21. [**Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models.**](https://arxiv.org/abs/2401.04695) *Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention)](https://github.com/OpenNLPLab/lightning-attention)

22. [**Extending LLMs' Context Window with 100 Samples.**](https://arxiv.org/abs/2401.07004) *Yikai Zhang, Junlong Li, Pengfei Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/Entropy-ABF)](https://github.com/GAIR-NLP/Entropy-ABF)

23. [**E^2-LLM: Efficient and Extreme Length Extension of Large Language Models.**](https://arxiv.org/abs/2401.06951) *Jiaheng Liu, Zhiqi Bai, Yuanxing Zhang, Chenchen Zhang, Yu Zhang, Ge Zhang, Jiakai Wang, Haoran Que, Yukang Chen, Wenbo Su, Tiezheng Ge, Jie Fu, Wenhu Chen, Bo Zheng.* Arxiv 2024.

24. [**With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation.**](https://arxiv.org/abs/2401.11504) *Y. Wang, D. Ma, D. Cai.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TemporaryLoRA/Temp-LoRA)](https://github.com/TemporaryLoRA/Temp-LoRA)

25. [**Two Stones Hit One Bird: Bilevel Positional Encoding for Better Length Extrapolation.**](https://arxiv.org/abs/2401.16421) *Zhenyu He, Guhao Feng, Shengjie Luo, Kai Yang, Di He, Jingjing Xu, Zhi Zhang, Hongxia Yang, Liwei Wang.* ICML 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zhenyuhe00/BiPE)](https://github.com/zhenyuhe00/BiPE)

26. [**Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens.**](https://arxiv.org/abs/2401.17377) *Jiacheng Liu, Sewon Min, Luke Zettlemoyer, Yejin Choi, Hannaneh Hajishirzi.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/liujch1998/infini-gram)](https://github.com/liujch1998/infini-gram)

27. [**LongRoPE: Extending LLM ContextWindow Beyond 2 Million Tokens.**](https://arxiv.org/abs/2402.13753) *Yiran Ding, Li Lyna Zhang, Chengruidong Zhang, Yuanyuan Xu, Ning Shang, Jiahang Xu, Fan Yang, Mao Yang.* Arxiv 2024.

28. [**Data Engineering for Scaling Language Models to 128K Context.**](https://arxiv.org/abs/2402.10171) *Yao Fu, Rameswar Panda, Xinyao Niu, Xiang Yue, Hannaneh Hajishirzi, Yoon Kim, Hao Peng.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FranxYao/Long-Context-Data-Engineering)](https://github.com/FranxYao/Long-Context-Data-Engineering)

29. [**Transformers Can Achieve Length Generalization But Not Robustly.**](https://arxiv.org/abs/2402.09371v1) *Yongchao Zhou, Uri Alon, Xinyun Chen, Xuezhi Wang, Rishabh Agarwal, Denny Zhou.* Arxiv 2024.

30. [**Long-Context Language Modeling with Parallel Context Encoding.**](https://arxiv.org/abs/2402.16617) *Howard Yen, Tianyu Gao, Danqi Chen.* ACL 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/CEPE)](https://github.com/princeton-nlp/CEPE)

31. [**CLEX: Continuous Length Extrapolation for Large Language Models.**](https://arxiv.org/abs/2310.16450) *Guanzheng Chen, Xin Li, Zaiqiao Meng, Shangsong Liang, Lidong Bing.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/DAMO-NLP-SG/CLEX)](https://github.com/DAMO-NLP-SG/CLEX)

32. [**Resonance RoPE: Improving Context Length Generalization of Large Language Models.**](https://arxiv.org/abs/2403.00071) *Suyuchen Wang, Ivan Kobyzev, Peng Lu, Mehdi Rezagholizadeh, Bang Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sheryc/resonance_rope)](https://github.com/sheryc/resonance_rope)

33. [**Can't Remember Details in Long Documents? You Need Some R&R.**](https://arxiv.org/abs/2403.05004) *Devanshu Agrawal, Shang Gao, Martin Gajek.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/casetext/r-and-r)](https://github.com/casetext/r-and-r)

34. [**Found in the Middle: How Language Models Use Long Contexts Better via Plug-and-Play Positional Encoding.**](https://arxiv.org/abs/2403.04797) *Zhenyu Zhang, Runjin Chen, Shiwei Liu, Zhewei Yao, Olatunji Ruwase, Beidi Chen, Xiaoxia Wu, Zhangyang Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/Ms-PoE)](https://github.com/VITA-Group/Ms-PoE)

35. [**InfLLM: Unveiling the Intrinsic Capacity of LLMs for Understanding Extremely Long Sequences with Training-Free Memory.**](https://arxiv.org/abs/2402.04617) *Chaojun Xiao, Pengle Zhang, Xu Han, Guangxuan Xiao, Yankai Lin, Zhengyan Zhang, Zhiyuan Liu, Song Han, Maosong Sun.* Arxiv 2024.

36. [**Naive Bayes-based Context Extension for Large Language Models.**](https://arxiv.org/abs/2403.17552) *Jianlin Su, Murtadha Ahmed, Wenbo, Luo Ao, Mingren Zhu, Yunfeng Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/amurtadha/NBCE-master)](https://github.com/amurtadha/NBCE-master)

37. [**Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient Generative Inference.**](https://arxiv.org/abs/2403.09054) *Muhammad Adnan, Akhil Arunkumar, Gaurav Jain, Prashant J. Nair, Ilya Soloveychik, Purushotham Kamath.* Arxiv 2024.

38. [**In-Context Pretraining: Language Modeling Beyond Document Boundaries.**](https://openreview.net/forum?id=LXVswInHOo) *Weijia Shi, Sewon Min, Maria Lomeli, Chunting Zhou, Margaret Li, Xi Victoria Lin, Noah A. Smith, Luke Zettlemoyer, Wen-tau Yih, Mike Lewis.* ICLR 2024 Spotlight.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/swj0419/in-context-pretraining)](https://github.com/swj0419/in-context-pretraining)

39. [**Effective Long-Context Scaling of Foundation Models.**](https://arxiv.org/abs/2309.16039) *Wenhan Xiong, Jingyu Liu, Igor Molybog, Hejia Zhang, Prajjwal Bhargava, Rui Hou, Louis Martin, Rashi Rungta, Karthik Abinav Sankararaman, Barlas Oguz, Madian Khabsa, Han Fang, Yashar Mehdad, Sharan Narang, Kshitiz Malik, Angela Fan, Shruti Bhosale, Sergey Edunov, Mike Lewis, Sinong Wang, Hao Ma.* Arxiv 2023.

40. [**Fewer Truncations Improve Language Modeling.**](https://arxiv.org/abs/2404.10830) *Hantian Ding, Zijian Wang, Giovanni Paolini, Varun Kumar, Anoop Deoras, Dan Roth, Stefano Soatto.* Arxiv 2024.

41. [**Length Generalization of Causal Transformers without Position Encoding.**](https://arxiv.org/abs/2404.12224) *Jie Wang, Tao Ji, Yuanbin Wu, Hang Yan, Tao Gui, Qi Zhang, Xuanjing Huang, Xiaoling Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/AntNLP/nope_head_scale)](https://github.com/AntNLP/nope_head_scale)

42. [**Extending Llama-3's Context Ten-Fold Overnight.**](https://arxiv.org/abs/2404.19553) *Peitian Zhang, Ninglu Shao, Zheng Liu, Shitao Xiao, Hongjin Qian, Qiwei Ye, Zhicheng Dou.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

43. [**Long Context Alignment with Short Instructions and Synthesized Positions.**](https://arxiv.org/abs/2405.03939) *Wenhao Wu, Yizhong Wang, Yao Fu, Xiang Yue, Dawei Zhu, Sujian Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nightdessert/SkipAlign)](https://github.com/nightdessert/SkipAlign)

44. [**xLSTM: Extended Long Short-Term Memory.**](https://arxiv.org/abs/2405.04517) *Maximilian Beck, Korbinian Pöppel, Markus Spanring, Andreas Auer, Oleksandra Prudnikova, Michael Kopp, Günter Klambauer, Johannes Brandstetter, Sepp Hochreiter.* Arxiv 2024.

45. [**DAPE: Data-Adaptive Positional Encoding for Length Extrapolation.**](https://arxiv.org/abs/2405.14722) *Chuanyang Zheng, Yihang Gao, Han Shi, Minbin Huang, Jingyao Li, Jing Xiong, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li.* NeurIPS 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE)](https://github.com/chuanyang-Zheng/DAPE)

46. [**Contextual Position Encoding: Learning to Count What's Important.**](https://arxiv.org/abs/2405.18719) *Olga Golovneva, Tianlu Wang, Jason Weston, Sainbayar Sukhbaatar.* Arxiv 2024.

47. [**Quest: Query-centric Data Synthesis Approach for Long-context Scaling of Large Language Model.**](https://arxiv.org/abs/2405.19846) *Chaochen Gao, Xing Wu, Qi Fu, Songlin Hu.* Arxiv 2024.

48. [**Position Coupling: Leveraging Task Structure for Improved Length Generalization of Transformers.**](https://arxiv.org/abs/2405.20671) *Hanseul Cho, Jaeyoung Cha, Pranjal Awasthi, Srinadh Bhojanapalli, Anupam Gupta, Chulhee Yun.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HanseulJo/position-coupling)](https://github.com/HanseulJo/position-coupling)

49. [**LongSkywork: A Training Recipe for Efficiently Extending Context Length in Large Language Models.**](https://arxiv.org/abs/2406.00605) *Liang Zhao, Tianwen Wei, Liang Zeng, Cheng Cheng, Liu Yang, Peng Cheng, Lijie Wang, Chenxia Li, Xuejie Wu, Bo Zhu, Yimeng Gan, Rui Hu, Shuicheng Yan, Han Fang, Yahui Zhou.* Arxiv 2024.

50. [**Explicitly Encoding Structural Symmetry is Key to Length Generalization in Arithmetic Tasks.**](https://arxiv.org/abs/2406.01895) *Mahdi Sabbaghi, George Pappas, Hamed Hassani, Surbhi Goel.* Arxiv 2024.

51. [**Never Miss A Beat: An Efficient Recipe for Context Window Extension of Large Language Models with Consistent "Middle" Enhancement.**](https://arxiv.org/abs/2406.07138) *Tong Wu, Yanpeng Zhao, Zilong Zheng.* Arxiv 2024.

52. [**3D-RPE: Enhancing Long-Context Modeling Through 3D Rotary Position Encoding.**](https://arxiv.org/abs/2406.09897) *Xindian Ma, Wenyuan Liu, Peng Zhang, Nan Xu.* Arxiv 2024.

53. [**Mixture of In-Context Experts Enhance LLMs' Long Context Awareness.**](https://arxiv.org/abs/2406.19598) *Hongzhan Lin, Ang Lv, Yuhan Chen, Chen Zhu, Yang Song, Hengshu Zhu, Rui Yan.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/p1nksnow/MoICE)](https://github.com/p1nksnow/MoICE)

54. [**Human-like Episodic Memory for Infinite Context LLMs.**](https://arxiv.org/abs/2407.09450) *Zafeirios Fountas, Martin A Benfeghoul, Adnan Oomerjee, Fenia Christopoulou, Gerasimos Lampouras, Haitham Bou-Ammar, Jun Wang.* Arxiv 2024.

55. [**Scaling Granite Code Models to 128K Context.**](https://arxiv.org/abs/2407.13739) *Matt Stallone, Vaibhav Saxena, Leonid Karlinsky, Bridget McGinn, Tim Bula, Mayank Mishra, Adriana Meza Soria, Gaoyuan Zhang, Aditya Prasad, Yikang Shen, Saptha Surendran, Shanmukha Guttula, Hima Patel, Parameswaran Selvam, Xuan-Hong Dang, Yan Koyfman, Atin Sood, Rogerio Feris, Nirmit Desai, David D. Cox, Ruchir Puri, Rameswar Panda.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ibm-granite/granite-code-models)](https://github.com/ibm-granite/granite-code-models)

56. [**ChatQA 2: Bridging the Gap to Proprietary LLMs in Long Context and RAG Capabilities.**](https://arxiv.org/abs/2407.14482) *Peng Xu, Wei Ping, Xianchao Wu, Zihan Liu, Mohammad Shoeybi, Bryan Catanzaro.* Arxiv 2024.

57. [**Efficient Solutions For An Intriguing Failure of LLMs: Long Context Window Does Not Mean LLMs Can Analyze Long Sequences Flawlessly.**](https://arxiv.org/abs/2408.01866) *Peyman Hosseini, Ignacio Castro, Iacopo Ghinassi, Matthew Purver.* Arxiv 2024.

58. [**FocusLLM: Scaling LLM's Context by Parallel Decoding.**](https://arxiv.org/abs/2408.11745) *Zhenyu Li, Yike Zhang, Tengyu Pan, Yutao Sun, Zhichao Duan, Junjie Fang, Rong Han, Zixuan Wang, Jianyong Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/leezythu/FocusLLM)](https://github.com/leezythu/FocusLLM)

59. [**LongRecipe: Recipe for Efficient Long Context Generalization in Large Language Models.**](https://arxiv.org/abs/2409.00509) *Zhiyuan Hu, Yuliang Liu, Jinman Zhao, Suyuchen Wang, Yan Wang, Wei Shen, Qing Gu, Anh Tuan Luu, See-Kiong Ng, Zhiwei Jiang, Bryan Hooi.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zhiyuanhubj/LongRecipe)](https://github.com/zhiyuanhubj/LongRecipe)

60. [**E2LLM: Encoder Elongated Large Language Models for Long-Context Understanding and Reasoning.**](https://arxiv.org/abs/2409.06679) *Zihan Liao, Jun Wang, Hang Yu, Lingxiao Wei, Jianguo Li, Jun Wang, Wei Zhang.* Arxiv 2024.

61. [**Untie the Knots: An Efficient Data Augmentation Strategy for Long-Context Pre-Training in Language Models.**](https://arxiv.org/abs/2409.04774) *Junfeng Tian, Da Zheng, Yang Cheng, Rui Wang, Colin Zhang, Debing Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/rgtjf/Untie-the-Knots)](https://github.com/rgtjf/Untie-the-Knots)

62. [**PEAR: Position-Embedding-Agnostic Attention Re-weighting Enhances Retrieval-Augmented Generation with Zero Inference Overhead.**](https://arxiv.org/abs/2409.19745) *Tao Tan, Yining Qian, Ang Lv, Hongzhan Lin, Songhao Wu, Yongbo Wang, Feng Wang, Jingtong Wu, Xin Lu, Rui Yan.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TTArch/PEAR-RAG)](https://github.com/TTArch/PEAR-RAG)

63. [**Efficient Long-range Language Modeling with Self-supervised Causal Retrieval.**](https://arxiv.org/abs/2410.01651) *Xiang Hu, Zhihao Teng, Wei Wu, Kewei Tu.* Arxiv 2024.

64. [**A Little Goes a Long Way: Efficient Long Context Training and Inference with Partial Contexts.**](https://arxiv.org/abs/2410.01485) *Suyu Ge, Xihui Lin, Yunan Zhang, Jiawei Han, Hao Peng.* Arxiv 2024.

65. [**Extending Context Window of Large Language Models from a Distributional Perspective.**](https://arxiv.org/abs/2410.01490) *Yingsheng Wu, Yuxuan Gu, Xiaocheng Feng, Weihong Zhong, Dongliang Xu, Qing Yang, Hongtao Liu, Bing Qin.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/1180301012/DPRoPE)](https://github.com/1180301012/DPRoPE)

66. [**How to Train Long-Context Language Models (Effectively).**](https://arxiv.org/abs/2410.02660) *Tianyu Gao, Alexander Wettig, Howard Yen, Danqi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/ProLong)](https://github.com/princeton-nlp/ProLong)

67. [**Differential Transformer.**](https://arxiv.org/abs/2410.05258) *Tianzhu Ye, Li Dong, Yuqing Xia, Yutao Sun, Yi Zhu, Gao Huang, Furu Wei.* Arxiv 2024.

68. [**DAPE V2: Process Attention Score as Feature Map for Length Extrapolation.**](https://arxiv.org/abs/2410.04798) *Chuanyang Zheng, Yihang Gao, Han Shi, Jing Xiong, Jiankai Sun, Jingyao Li, Minbin Huang, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE)](https://github.com/chuanyang-Zheng/DAPE)

69. [**Why Does the Effective Context Length of LLMs Fall Short?.**](https://arxiv.org/abs/2410.18745) *Chenxin An, Jun Zhang, Ming Zhong, Lei Li, Shansan Gong, Yao Luo, Jingjing Xu, Lingpeng Kong.* Arxiv 2024.

70. [**LOGO -- Long cOntext aliGnment via efficient preference Optimization.**](https://arxiv.org/abs/2410.18533) *Zecheng Tang, Zechen Sun, Juntao Li, Qiaoming Zhu, Min Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ZetangForward/LCM_Stack)](https://github.com/ZetangForward/LCM_Stack)

71. [**Selecting Influential Samples for Long Context Alignment via Homologous Models' Guidance and Contextual Awareness Measurement.**](https://arxiv.org/abs/2410.15633) *Shuzheng Si, Haozhe Zhao, Gang Chen, Yunshui Li, Kangyang Luo, Chuancheng Lv, Kaikai An, Fanchao Qi, Baobao Chang, Maosong Sun.* Arxiv 2024.

72. [**Two are better than one: Context window extension with multi-grained self-injection.**](https://arxiv.org/abs/2410.19318) *Wei Han, Pan Zhou, Soujanya Poria, Shuicheng Yan.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Clement25/SharedLLM)](https://github.com/Clement25/SharedLLM)

73. [**LongReward: Improving Long-context Large Language Models with AI Feedback.**](https://arxiv.org/abs/2410.21252) *Jiajie Zhang, Zhongni Hou, Xin Lv, Shulin Cao, Zhenyu Hou, Yilin Niu, Lei Hou, Yuxiao Dong, Ling Feng, Juanzi Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongReward)](https://github.com/THUDM/LongReward)

74. [**HoPE: A Novel Positional Encoding Without Long-Term Decay for Enhanced Context Awareness and Extrapolation.**](https://arxiv.org/abs/2410.21216) *Yuhan Chen, Ang Lv, Jian Luan, Bin Wang, Wei Liu.* Arxiv 2024.

## 6. Long Term Memory

1. [**Unleashing Infinite-Length Input Capacity for Large-scale Language Models with Self-Controlled Memory System.**](https://arxiv.org/abs/2304.13343) *Xinnian Liang, Bing Wang, Hui Huang, Shuangzhi Wu, Peihao Wu, Lu Lu, Zejun Ma, Zhoujun Li.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/wbbeyourself/SCM4LLMs)](https://github.com/wbbeyourself/SCM4LLMs)

2. [**MemoryBank: Enhancing Large Language Models with Long-Term Memory.**](https://arxiv.org/abs/2305.10250) *Wanjun Zhong, Lianghong Guo, Qiqi Gao, He Ye, Yanlin Wang.* Arxiv 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zhongwanjun/MemoryBank-SiliconFriend)](https://github.com/zhongwanjun/MemoryBank-SiliconFriend)

3. [**Improve Long-term Memory Learning Through Rescaling the Error Temporally.**](https://arxiv.org/abs/2307.11462) *Shida Wang, Zhanglu Yan.* Arxiv 2023. 

4. [**Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models.**](https://arxiv.org/abs/2308.15022) *Qingyue Wang, Liang Ding, Yanan Cao, Zhiliang Tian, Shi Wang, Dacheng Tao, Li Guo.* Arxiv 2023. 

5. [**Empowering Working Memory for Large Language Model Agents.**](https://arxiv.org/abs/2312.17259) *Jing Guo, Nan Li, Jianchuan Qi, Hang Yang, Ruiqiao Li, Yuzhen Feng, Si Zhang, Ming Xu.* Arxiv 2024. 

6. [**Evolving Large Language Model Assistant with Long-Term Conditional Memory.**](https://arxiv.org/abs/2312.17257) *Ruifeng Yuan, Shichao Sun, Zili Wang, Ziqiang Cao, Wenjie Li.* Arxiv 2024. 

7. [**Commonsense-augmented Memory Construction and Management in Long-term Conversations via Context-aware Persona Refinement.**](https://arxiv.org/abs/2401.14215) *Hana Kim, Kai Tzu-iunn Ong, Seoyeon Kim, Dongha Lee, Jinyoung Yeo.* Arxiv 2024. 

8. [**A Human-Inspired Reading Agent with Gist Memory of Very Long Contexts.**](https://arxiv.org/abs/2402.09727v1) *Kuang-Huei Lee, Xinyun Chen, Hiroki Furuta, John Canny, Ian Fischer.* Arxiv 2024. 

9. [**Steering Conversational Large Language Models for Long Emotional Support Conversations.**](https://arxiv.org/abs/2402.10453) *Navid Madani, Sougata Saha, Rohini Srihari.* Arxiv 2024. 

10. [**SPAR: Personalized Content-Based Recommendation via Long Engagement Attention.**](https://arxiv.org/abs/2402.10555) *Chiyu Zhang, Yifei Sun, Jun Chen, Jie Lei, Muhammad Abdul-Mageed, Sinong Wang, Rong Jin, Sem Park, Ning Yao, Bo Long.* Arxiv 2024. 

11. [**Compress to Impress: Unleashing the Potential of Compressive Memory in Real-World Long-Term Conversations.**](https://arxiv.org/abs/2402.11975) *Nuo Chen, Hongguang Li, Juhua Huang, Baoyuan Wang, Jia Li.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nuochenpku/COMEDY)](https://github.com/nuochenpku/COMEDY)

12. [**StreamingDialogue: Prolonged Dialogue Learning via Long Context Compression with Minimal Losses.**](https://arxiv.org/abs/2403.08312) *Jia-Nan Li, Quan Tu, Cunli Mao, Zhengtao Yu, Ji-Rong Wen, Rui Yan.* Arxiv 2024. 

13. [**Prompts As Programs: A Structure-Aware Approach to Efficient Compile-Time Prompt Optimization.**](https://arxiv.org/abs/2404.02319) *Tobias Schnabel, Jennifer Neville.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/sammo)](https://github.com/microsoft/sammo)

14. [**HMT: Hierarchical Memory Transformer for Long Context Language Processing.**](https://arxiv.org/abs/2405.06067) *Tobias Schnabel, Jennifer Neville.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OswaldHe/HMT-pytorch)](https://github.com/OswaldHe/HMT-pytorch)

15. [**SirLLM: Streaming Infinite Retentive LLM.**](https://arxiv.org/abs/2405.12528) *Yao Yao, Zuchao Li, Hai Zhao.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Zoeyyao27/SirLLM)](https://github.com/Zoeyyao27/SirLLM)

16. [**Toward Conversational Agents with Context and Time Sensitive Long-term Memory.**](https://arxiv.org/abs/2406.00057) *Nick Alonso, Tomás Figliolia, Anthony Ndirango, Beren Millidge.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Zyphra/TemporalMemoryDataset)](https://github.com/Zyphra/TemporalMemoryDataset)

17. [**Position Debiasing Fine-Tuning for Causal Perception in Long-Term Dialogue.**](https://arxiv.org/abs/2406.02002) *Shixuan Fan, Wei Wei, Wendi Li, Xian-Ling Mao, Wenfeng Xie, Dangyang Chen.* Arxiv 2024. 

18. [**Enhancing Long-Term Memory using Hierarchical Aggregate Tree for Retrieval Augmented Generation.**](https://arxiv.org/abs/2406.06124) *Aadharsh Aadhithya A, Sachin Kumar S, Soman K.P.* Arxiv 2024. 

19. [**Suri: Multi-constraint Instruction Following for Long-form Text Generation.**](https://arxiv.org/abs/2406.19371) *Chau Minh Pham, Simeng Sun, Mohit Iyyer.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chtmp223/suri)](https://github.com/chtmp223/suri)

20. [**HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model.**](https://arxiv.org/abs/2408.09559) *Mengkang Hu, Tianxing Chen, Qiguang Chen, Yao Mu, Wenqi Shao, Ping Luo.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HiAgent2024/HiAgent)](https://github.com/HiAgent2024/HiAgent)

21. [**CreDes: Causal Reasoning Enhancement and Dual-End Searching for Solving Long-Range Reasoning Problems using LLMs.**](https://arxiv.org/abs/2410.01696) *Kangsheng Wang, Xiao Zhang, Hao Liu, Songde Han, Huimin Ma, Tianyu Hu.* Arxiv 2024.

## 7. RAG and ICL

1. [**Walking Down the Memory Maze: Beyond Context Limit through Interactive Reading.**](https://arxiv.org/abs/2310.05029) *Howard Chen, Ramakanth Pasunuru, Jason Weston, Asli Celikyilmaz.* Arxiv 2023. 

2. [**Attendre: Wait To Attend By Retrieval With Evicted Queries in Memory-Based Transformers for Long Context Processing.**](https://arxiv.org/abs/2401.04881) *Zi Yang, Nan Hua.* Arxiv 2024. 

3. [**BGE Landmark Embedding: A Chunking-Free Embedding Method For Retrieval Augmented Long-Context Large Language Models.**](https://arxiv.org/abs/2402.11573) *Kun Luo, Zheng Liu, Shitao Xiao, Kang Liu.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

4. [**Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity.**](https://arxiv.org/abs/2403.14403) *Soyeong Jeong, Jinheon Baek, Sukmin Cho, Sung Ju Hwang, Jong C. Park.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/starsuzi/Adaptive-RAG)](https://github.com/starsuzi/Adaptive-RAG)

5. [**RQ-RAG: Learning to Refine Queries for Retrieval Augmented Generation.**](https://arxiv.org/abs/2404.00610) *Chi-Min Chan, Chunpu Xu, Ruibin Yuan, Hongyin Luo, Wei Xue, Yike Guo, Jie Fu.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chanchimin/RQ-RAG)](https://github.com/chanchimin/RQ-RAG)

6. [**Improving Retrieval Augmented Open-Domain Question-Answering with Vectorized Contexts.**](https://arxiv.org/abs/2404.02022) *Zhuo Chen, Xinyu Wang, Yong Jiang, Pengjun Xie, Fei Huang, Kewei Tu.* Arxiv 2024. 

7. [**Superposition Prompting: Improving and Accelerating Retrieval-Augmented Generation.**](https://arxiv.org/abs/2404.06910) *Thomas Merth, Qichen Fu, Mohammad Rastegari, Mahyar Najibi.* Arxiv 2024. 

8. [**Multi-view Content-aware Indexing for Long Document Retrieval.**](https://arxiv.org/abs/2404.15103) *Kuicai Dong, Derrick Goh Xin Deik, Yi Quan Lee, Hao Zhang, Xiangyang Li, Cong Zhang, Yong Liu.* Arxiv 2024. 

9. [**Retrieval Head Mechanistically Explains Long-Context Factuality.**](https://arxiv.org/abs/2404.15574) *Wenhao Wu, Yizhong Wang, Guangxuan Xiao, Hao Peng, Yao Fu.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nightdessert/Retrieval_Head)](https://github.com/nightdessert/Retrieval_Head)

10. [**FlashBack:Efficient Retrieval-Augmented Language Modeling for Long Context Inference.**](https://arxiv.org/abs/2405.04065) *Runheng Liu, Xingchen Xiao, Heyan Huang, Zewen Chi, Zhijing Wu.* Arxiv 2024. 

11. [**Feature-Adaptive and Data-Scalable In-Context Learning.**](https://arxiv.org/abs/2405.10738) *Jiahao Li, Quan Wang, Licheng Zhang, Guoqing Jin, Zhendong Mao.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/jiahaozhenbang/FADS-ICL)](https://github.com/jiahaozhenbang/FADS-ICL)

12. [**KG-RAG: Bridging the Gap Between Knowledge and Creativity.**](https://arxiv.org/abs/2405.12035) *Diego Sanmartin.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dsanmart/KG-RAG)](https://github.com/dsanmart/KG-RAG)

13. [**HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models.**](https://arxiv.org/abs/2405.14831) *Bernal Jiménez Gutiérrez, Yiheng Shu, Yu Gu, Michihiro Yasunaga, Yu Su.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OSU-NLP-Group/HippoRAG)](https://github.com/OSU-NLP-Group/HippoRAG)

14. [**Implicit In-context Learning.**](https://arxiv.org/abs/2405.14660) *Zhuowei Li, Zihao Xu, Ligong Han, Yunhe Gao, Song Wen, Di Liu, Hao Wang, Dimitris N. Metaxas.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/LzVv123456/I2CL)](https://github.com/LzVv123456/I2CL)

15. [**Are Long-LLMs A Necessity For Long-Context Tasks?.**](https://arxiv.org/abs/2405.15318) *Hongjin Qian, Zheng Liu, Peitian Zhang, Kelong Mao, Yujia Zhou, Xu Chen, Zhicheng Dou.* Arxiv 2024. 

16. [**Accelerating Inference of Retrieval-Augmented Generation via Sparse Context Selection.**](https://arxiv.org/abs/2405.16178) *Yun Zhu, Jia-Chen Gu, Caitlin Sikora, Ho Ko, Yinxiao Liu, Chu-Cheng Lin, Lei Shu, Liangchen Luo, Lei Meng, Bang Liu, Jindong Chen.* Arxiv 2024. 

17. [**Is In-Context Learning Sufficient for Instruction Following in LLMs?.**](https://arxiv.org/abs/2405.19874) *Hao Zhao, Maksym Andriushchenko, Francesco Croce, Nicolas Flammarion.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/tml-epfl/icl-alignment)](https://github.com/tml-epfl/icl-alignment)

18. [**FragRel: Exploiting Fragment-level Relations in the External Memory of Large Language Models.**](https://arxiv.org/abs/2406.03092) *Xihang Yue, Linchao Zhu, Yi Yang.* Arxiv 2024. 

19. [**Multi-Head RAG: Solving Multi-Aspect Problems with LLMs.**](https://arxiv.org/abs/2406.05085) *Maciej Besta, Ales Kubicek, Roman Niggli, Robert Gerstenberger, Lucas Weitzendorf, Mingyuan Chi, Patrick Iff, Joanna Gajda, Piotr Nyczyk, Jürgen Müller, Hubert Niewiadomski, Marcin Chrapek, Michał Podstawski, Torsten Hoefler.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/spcl/MRAG)](https://github.com/spcl/MRAG)

20. [**Demonstration Notebook: Finding the Most Suited In-Context Learning Example from Interactions.**](https://arxiv.org/abs/2406.10878) *Yiming Tang, Bin Dong.* Arxiv 2024. 

21. [**Retrieval Meets Reasoning: Dynamic In-Context Editing for Long-Text Understanding.**](https://arxiv.org/abs/2406.12331) *Weizhi Fei, Xueyan Niu, Guoqing Xie, Yanhua Zhang, Bo Bai, Lei Deng, Wei Han.* Arxiv 2024. 

22. [**FoRAG: Factuality-optimized Retrieval Augmented Generation for Web-enhanced Long-form Question Answering.**](https://arxiv.org/abs/2406.13779) *Tianchi Cai, Zhiwen Tan, Xierui Song, Tao Sun, Jiyan Jiang, Yunqi Xu, Yinger Zhang, Jinjie Gu.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/forag)

23. [**Can Few-shot Work in Long-Context? Recycling the Context to Generate Demonstrations.**](https://arxiv.org/abs/2406.13632) *Arie Cattan, Alon Jacovi, Alex Fabrikant, Jonathan Herzig, Roee Aharoni, Hannah Rashkin, Dror Marcus, Avinatan Hassidim, Yossi Matias, Idan Szpektor, Avi Caciularu.* Arxiv 2024. 

24. [**LongRAG: Enhancing Retrieval-Augmented Generation with Long-context LLMs.**](https://arxiv.org/abs/2406.15319) *Ziyan Jiang, Xueguang Ma, Wenhu Chen.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/LongRAG)](https://github.com/TIGER-AI-Lab/LongRAG)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://tiger-ai-lab.github.io/LongRAG/)

25. [**Multimodal Task Vectors Enable Many-Shot Multimodal In-Context Learning.**](https://arxiv.org/abs/2406.15334) *Brandon Huang, Chancharik Mitra, Assaf Arbelle, Leonid Karlinsky, Trevor Darrell, Roei Herzig.* Arxiv 2024. 

26. [**From Artificial Needles to Real Haystacks: Improving Retrieval Capabilities in LLMs by Finetuning on Synthetic Data.**](https://arxiv.org/abs/2406.19292) *Zheyang Xiong, Vasilis Papageorgiou, Kangwook Lee, Dimitris Papailiopoulos.* Arxiv 2024. 

27. [**Memory3: Language Modeling with Explicit Memory.**](https://arxiv.org/abs/2407.01178) *Hongkang Yang, Zehao Lin, Wenjin Wang, Hao Wu, Zhiyu Li, Bo Tang, Wenqiang Wei, Jinbo Wang, Zeyun Tang, Shichao Song, Chenyang Xi, Yu Yu, Kai Chen, Feiyu Xiong, Linpeng Tang, Weinan E.* Arxiv 2024. 

28. [**Speculative RAG: Enhancing Retrieval Augmented Generation through Drafting.**](https://arxiv.org/abs/2407.08223) *Zilong Wang, Zifeng Wang, Long Le, Huaixiu Steven Zheng, Swaroop Mishra, Vincent Perot, Yuwei Zhang, Anush Mattapalli, Ankur Taly, Jingbo Shang, Chen-Yu Lee, Tomas Pfister.* Arxiv 2024. 

29. [**Retrieve, Summarize, Plan: Advancing Multi-hop Question Answering with an Iterative Approach.**](https://arxiv.org/abs/2407.13101) *Zhouyu Jiang, Mengshu Sun, Lei Liang, Zhiqiang Zhang.* Arxiv 2024. 

30. [**R^2AG: Incorporating Retrieval Information into Retrieval Augmented Generation.**](https://arxiv.org/abs/2406.13249) *Fuda Ye, Shuangyin Li, Yongqi Zhang, Lei Chen.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yefd/RRAG)](https://github.com/yefd/RRAG)

31. [**Making Long-Context Language Models Better Multi-Hop Reasoners.**](https://arxiv.org/abs/2408.03246) *Yanyang Li, Shuo Liang, Michael R. Lyu, Liwei Wang.* ACL 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/LaVi-Lab/LongContextReasoner)](https://github.com/LaVi-Lab/LongContextReasoner)

32. [**Large Language Models Know What Makes Exemplary Contexts.**](https://arxiv.org/abs/2408.07505) *Quanyu Long, Jianda Chen, Wenya Wang, Sinno Jialin Pan.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ruyue0001/RL-ICL)](https://github.com/ruyue0001/RL-ICL)

33. [**RAGChecker: A Fine-grained Framework for Diagnosing Retrieval-Augmented Generation.**](https://arxiv.org/abs/2408.08067) *Dongyu Ru, Lin Qiu, Xiangkun Hu, Tianhang Zhang, Peng Shi, Shuaichen Chang, Cheng Jiayang, Cunxiang Wang, Shichao Sun, Huanyu Li, Zizhao Zhang, Binjie Wang, Jiarong Jiang, Tong He, Zhiguo Wang, Pengfei Liu, Yue Zhang, Zheng Zhang.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/amazon-science/RAGChecker)](https://github.com/amazon-science/RAGChecker)

34. [**Writing in the Margins: Better Inference Pattern for Long Context Retrieval.**](https://arxiv.org/abs/2408.14906) *Melisa Russak, Umar Jamil, Christopher Bryant, Kiran Kamble, Axel Magnuson, Mateusz Russak, Waseem AlShikh.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/writer/writing-in-the-margins)](https://github.com/writer/writing-in-the-margins)

35. [**MemLong: Memory-Augmented Retrieval for Long Text Modeling.**](https://arxiv.org/abs/2408.16967) *Weijie Liu, Zecheng Tang, Juntao Li, Kehai Chen, Min Zhang.* Arxiv 2024. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Bui1dMySea/MemLong)](https://github.com/Bui1dMySea/MemLong)

36. [**In Defense of RAG in the Era of Long-Context Language Models.**](https://arxiv.org/abs/2409.01666) *Tan Yu, Anbang Xu, Rama Akkiraju.* Arxiv 2024.

37. [**MemoRAG: Moving towards Next-Gen RAG Via Memory-Inspired Knowledge Discovery.**](https://arxiv.org/abs/2409.05591) *Hongjin Qian, Peitian Zhang, Zheng Liu, Kelong Mao, Zhicheng Dou.* Arxiv 2024.

38. [**You Only Use Reactive Attention Slice For Long Context Retrieval.**](https://arxiv.org/abs/2409.13695) *Yun Joon Soh, Hanxian Huang, Yuandong Tian, Jishen Zhao.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yjsoh/youra)](https://github.com/yjsoh/youra)

39. [**SMART-RAG: Selection using Determinantal Matrices for Augmented Retrieval.**](https://arxiv.org/abs/2409.13992) *Jiatao Li, Xinyu Hu, Xiaojun Wan.* Arxiv 2024.

40. [**Lighter And Better: Towards Flexible Context Adaptation For Retrieval Augmented Generation.**](https://arxiv.org/abs/2409.15699) *Zheng Liu, Chenyuan Wu, Ninglu Shao, Shitao Xiao, Chaozhuo Li, Defu Lian.* CIKM 2024.

41. [**Bridging Context Gaps: Leveraging Coreference Resolution for Long Contextual Understanding.**](https://arxiv.org/abs/2410.01671) *Yanming Liu, Xinyue Peng, Jiannan Cao, Shi Bo, Yanxin Shen, Xuhong Zhang, Sheng Cheng, Xun Wang, Jianwei Yin, Tianyu Du.* Arxiv 2024.

42. [**ALR2: A Retrieve-then-Reason Framework for Long-context Question Answering.**](https://arxiv.org/abs/2410.03227) *Huayang Li, Pat Verga, Priyanka Sen, Bowen Yang, Vijay Viswanathan, Patrick Lewis, Taro Watanabe, Yixuan Su.* Arxiv 2024.

43. [**Inference Scaling for Long-Context Retrieval Augmented Generation.**](https://arxiv.org/abs/2410.04343) *Zhenrui Yue, Honglei Zhuang, Aijun Bai, Kai Hui, Rolf Jagerman, Hansi Zeng, Zhen Qin, Dong Wang, Xuanhui Wang, Michael Bendersky.* Arxiv 2024.

44. [**GARLIC: LLM-Guided Dynamic Progress Control with Hierarchical Weighted Graph for Long Document QA.**](https://arxiv.org/abs/2410.04790) *Xinyu Wang, Yanzheng Xiang, Lin Gui, Yulan He.* Arxiv 2024.

45. [**Long-Context LLMs Meet RAG: Overcoming Challenges for Long Inputs in RAG.**](https://arxiv.org/abs/2410.05983) *Bowen Jin, Jinsung Yoon, Jiawei Han, Sercan O. Arik.* Arxiv 2024.

46. [**Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts for Large Language Models.**](https://arxiv.org/abs/2410.07176) *Fei Wang, Xingchen Wan, Ruoxi Sun, Jiefeng Chen, Sercan Ö. Arık.* Arxiv 2024.

47. [**SEGMENT+: Long Text Processing with Short-Context Language Models.**](https://arxiv.org/abs/2410.06519) *Wei Shi, Shuang Li, Kerun Yu, Jinglei Chen, Zujie Liang, Xinhui Wu, Yuxi Qian, Feng Wei, Bo Zheng, Jiaqing Liang, Jiangjie Chen, Yanghua Xiao.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WeiShi-9/segmentplus)](https://github.com/WeiShi-9/segmentplus)

48. [**Graph of Records: Boosting Retrieval Augmented Generation for Long-context Summarization with Graphs.**](https://arxiv.org/abs/2410.11001) *Haozhen Zhang, Tao Feng, Jiaxuan You.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ulab-uiuc/GoR)](https://github.com/ulab-uiuc/GoR)

49. [**ChuLo: Chunk-Level Key Information Representation for Long Document Processing.**](https://arxiv.org/abs/2410.11119) *Yan Li, Caren Han, Yue Dai, Feiqi Cao.* Arxiv 2024.

50. [**TurboRAG: Accelerating Retrieval-Augmented Generation with Precomputed KV Caches for Chunked Text.**](https://arxiv.org/abs/2410.07590) *Songshuo Lu, Hua Wang, Yutian Rong, Zhi Chen, Yaohua Tang.* Arxiv 2024.

51. [**LLM×MapReduce: Simplified Long-Sequence Processing using Large Language Models.**](https://arxiv.org/abs/2410.09342) *Zihan Zhou, Chong Li, Xinyi Chen, Shuo Wang, Yu Chao, Zhili Li, Haoyu Wang, Rongqiao An, Qi Shi, Zhixing Tan, Xu Han, Xiaodong Shi, Zhiyuan Liu, Maosong Sun.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/LLMxMapReduce)](https://github.com/thunlp/LLMxMapReduce)

52. [**Enhancing Long Context Performance in LLMs Through Inner Loop Query Mechanism.**](https://arxiv.org/abs/2410.12859) *Yimin Tang, Yurong Xu, Ning Yan, Masood Mortazavi.* NeurIPS 2024.

53. [**LongRAG: A Dual-Perspective Retrieval-Augmented Generation Paradigm for Long-Context Question Answering.**](https://arxiv.org/abs/2410.18050) *Qingfei Zhao, Ruobing Wang, Yukuo Cen, Daren Zha, Shicheng Tan, Yuxiao Dong, Jie Tang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/QingFei1/LongRAG)](https://github.com/QingFei1/LongRAG)

## 8. Agent

1. [**LongAgent: Scaling Language Models to 128k Context through Multi-Agent Collaboration.**](https://arxiv.org/abs/2402.11550) *Jun Zhao, Can Zu, Hao Xu, Yi Lu, Wei He, Yiwen Ding, Tao Gui, Qi Zhang, Xuanjing Huang.* Arxiv 2024.

2. [**A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis.**](https://openreview.net/forum?id=9JQtrumvg8) *Izzeddin Gur, Hiroki Furuta, Austin V Huang, Mustafa Safdari, Yutaka Matsuo, Douglas Eck, Aleksandra Faust.* ICLR 2024 Oral.

3. [**PEARL: Prompting Large Language Models to Plan and Execute Actions Over Long Documents.**](https://aclanthology.org/2024.eacl-long.29/) *Simeng Sun, Yang Liu, Shuohang Wang, Dan Iter, Chenguang Zhu, Mohit Iyyer.* EACL 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SimengSun/pearl)](https://github.com/SimengSun/pearl)

4. [**AMAGO: Scalable In-Context Reinforcement Learning for Adaptive Agents.**](https://openreview.net/forum?id=M6XWoEdmwf) *Jake Grigsby, Linxi Fan, Yuke Zhu.* ICLR 2024 Spotlight.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/UT-Austin-RPL/amago)](https://github.com/UT-Austin-RPL/amago)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ut-austin-rpl.github.io/amago/)

5. [**Chain of Agents: Large Language Models Collaborating on Long-Context Tasks.**](https://arxiv.org/abs/2406.02818) *Yusen Zhang, Ruoxi Sun, Yanfei Chen, Tomas Pfister, Rui Zhang, Sercan Ö. Arik.* Arxiv 2024.

6. [**GraphReader: Building Graph-based Agent to Enhance Long-Context Abilities of Large Language Models.**](https://arxiv.org/abs/2406.14550) *Shilong Li, Yancheng He, Hangyu Guo, Xingyuan Bu, Ge Bai, Jie Liu, Jiaheng Liu, Xingwei Qu, Yangguang Li, Wanli Ouyang, Wenbo Su, Bo Zheng.* Arxiv 2024.

7. [**Synergistic Multi-Agent Framework with Trajectory Learning for Knowledge-Intensive Tasks.**](https://arxiv.org/abs/2407.09893) *Shengbin Yue, Siyuan Wang, Wei Chen, Xuanjing Huang, Zhongyu Wei.* Arxiv 2024.

8. [**Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-Horizon Tasks.**](https://arxiv.org/abs/2408.03615) *Zaijing Li, Yuquan Xie, Rui Shao, Gongwei Chen, Dongmei Jiang, Liqiang Nie.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/JiuTian-VL/Optimus-1)](https://github.com/JiuTian-VL/Optimus-1)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://cybertronagent.github.io/Optimus-1.github.io/)

## 9. Compress

1. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) *Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

2. [**Compressing Context to Enhance Inference Efficiency of Large Language Models.**](https://arxiv.org/abs/2310.06201) *Yucheng Li, Bo Dong, Chenghua Lin, Frank Guerin.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/liyucheng09/Selective_Context)](https://github.com/liyucheng09/Selective_Context)

3. [**LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models.**](https://arxiv.org/abs/2310.05736) *Huiqiang Jiang, Qianhui Wu, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

4. [**LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression.**](https://arxiv.org/abs/2310.06839) *Huiqiang Jiang, Qianhui Wu, Xufang Luo, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

5. [**System 2 Attention (is something you might need too).**](https://arxiv.org/abs/2311.11829) *Jason Weston, Sainbayar Sukhbaatar.* Arxiv 2023.

6. [**DSFormer: Effective Compression of Text-Transformers by Dense-Sparse Weight Factorization.**](https://arxiv.org/abs/2312.13211) *Rahul Chand, Yashoteja Prabhu, Pratyush Kumar.* Arxiv 2023.

7. [**Soaring from 4K to 400K: Extending LLM's Context with Activation Beacon.**](https://arxiv.org/abs/2401.03462) *Peitian Zhang, Zheng Liu, Shitao Xiao, Ninglu Shao, Qiwei Ye, Zhicheng Dou.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

8. [**Flexibly Scaling Large Language Models Contexts Through Extensible Tokenization.**](https://arxiv.org/abs/2401.07793) *Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

9. [**Say More with Less: Understanding Prompt Learning Behaviors through Gist Compression.**](https://arxiv.org/abs/2402.16058) *Xinze Li, Zhenghao Liu, Chenyan Xiong, Shi Yu, Yukun Yan, Shuo Wang, Ge Yu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenMatch/Gist-COCO)](https://github.com/OpenMatch/Gist-COCO)

10. [**Learning to Compress Prompt in Natural Language Formats.**](https://arxiv.org/abs/2402.18700) *Yu-Neng Chuang, Tianwei Xing, Chia-Yuan Chang, Zirui Liu, Xun Chen, Xia Hu.* Arxiv 2024.

11. [**Dynamic Memory Compression: Retrofitting LLMs for Accelerated Inference.**](https://arxiv.org/abs/2403.09636) *Piotr Nawrot, Adrian Łańcucki, Marcin Chochowski, David Tarjan, Edoardo M. Ponti.* Arxiv 2024.

12. [**LLMLingua-2: Data Distillation for Efficient and Faithful Task-Agnostic Prompt Compression.**](https://arxiv.org/abs/2403.12968) *Zhuoshi Pan, Qianhui Wu, Huiqiang Jiang, Menglin Xia, Xufang Luo, Jue Zhang, Qingwei Lin, Victor Rühle, Yuqing Yang, Chin-Yew Lin, H. Vicky Zhao, Lili Qiu, Dongmei Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

13. [**PCToolkit: A Unified Plug-and-Play Prompt Compression Toolkit of Large Language Models.**](https://arxiv.org/abs/2403.17411) *Jinyi Li, Yihuai Lan, Lei Wang, Hao Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/3DAgentWorld/Toolkit-for-Prompt-Compression)](https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression)

14. [**Compressed Context Memory for Online Language Model Interaction.**](https://arxiv.org/abs/2312.03414) *Jang-Hyun Kim, Junyoung Yeom, Sangdoo Yun, Hyun Oh Song.* ICLR 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/snu-mllab/context-memory)](https://github.com/snu-mllab/context-memory)

15. [**Compressing Large Language Models by Streamlining the Unimportant Layer.**](https://arxiv.org/abs/2403.19135) *Xiaodong Chen, Yuxuan Hu, Jing Zhang.* Arxiv 2024.

16. [**PROMPT-SAW: Leveraging Relation-Aware Graphs for Textual Prompt Compression.**](https://arxiv.org/abs/2404.00489) *Muhammad Asif Ali, Zhengping Li, Shu Yang, Keyuan Cheng, Yang Cao, Tianhao Huang, Lijie Hu, Lu Yu, Di Wang.* Arxiv 2024.

17. [**Training LLMs over Neurally Compressed Text.**](https://arxiv.org/abs/2404.03626) *Brian Lester, Jaehoon Lee, Alex Alemi, Jeffrey Pennington, Adam Roberts, Jascha Sohl-Dickstein, Noah Constant.* Arxiv 2024.

18. [**Rethinking Kullback-Leibler Divergence in Knowledge Distillation for Large Language Models.**](https://arxiv.org/abs/2404.02657) *Taiqiang Wu, Chaofan Tao, Jiahao Wang, Zhe Zhao, Ngai Wong.* Arxiv 2024. 

19. [**Adapting LLMs for Efficient Context Processing through Soft Prompt Compression.**](https://arxiv.org/abs/2404.04997) *Cangqing Wang, Yutian Yang, Ruisi Li, Dan Sun, Ruicong Cai, Yuzhu Zhang, Chengqian Fu, Lillian Floyd.* Arxiv 2024.

20. [**Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs.**](https://openreview.net/forum?id=uNrFpDPMyo) *Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao.* ICLR 2024 Oral.

21. [**LLoCO: Learning Long Contexts Offline.**](https://arxiv.org/abs/2404.07979) *Sijun Tan, Xiuyu Li, Shishir Patil, Ziyang Wu, Tianjun Zhang, Kurt Keutzer, Joseph E. Gonzalez, Raluca Ada Popa.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/jeffreysijuntan/lloco)](https://github.com/jeffreysijuntan/lloco)

22. [**In-Context Learning State Vector with Inner and Momentum Optimization.**](https://arxiv.org/abs/2404.11225) *Dongfang Li, Zhenyu Liu, Xinshuo Hu, Zetian Sun, Baotian Hu, Min Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HITsz-TMG/ICL-State-Vector)](https://github.com/HITsz-TMG/ICL-State-Vector)

23. [**Compressing Long Context for Enhancing RAG with AMR-based Concept Distillation.**](https://arxiv.org/abs/2405.03085) *Kaize Shi, Xueyao Sun, Qing Li, Guandong Xu.* Arxiv 2024.

24. [**Improving Long Text Understanding with Knowledge Distilled from Summarization Model.**](https://arxiv.org/abs/2405.04955) *Yan Liu, Yazheng Yang, Xiaokang Chen.* Arxiv 2024.

25. [**OpenBA-V2: Reaching 77.3% High Compression Ratio with Fast Multi-Stage Pruning.**](https://arxiv.org/abs/2405.05957) *Dan Qiao, Yi Su, Pinzheng Wang, Jing Ye, Wenjing Xie, Yuechi Zhou, Yuyang Ding, Zecheng Tang, Jikai Wang, Yixin Ji, Yue Wang, Pei Guo, Zechen Sun, Zikang Zhang, Juntao Li, Pingfu Chao, Wenliang Chen, Guohong Fu, Guodong Zhou, Qiaoming Zhu, Min Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLG/OpenBA-v2)](https://github.com/OpenNLG/OpenBA-v2)

26. [**Feature-based Low-Rank Compression of Large Language Models via Bayesian Optimization.**](https://arxiv.org/abs/2405.10616) *Yixin Ji, Yang Xiang, Juntao Li, Wei Chen, Zhongyi Liu, Kehai Chen, Min Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Dereck0602/Bolaco)](https://github.com/Dereck0602/Bolaco)

27. [**Imagination Augmented Generation: Learning to Imagine Richer Context for Question Answering over Large Language Models.**](https://arxiv.org/abs/2403.15268) *Huanxuan Liao, Shizhu He, Yao Xu, Yuanzhe Zhang, Kang Liu, Shengping Liu, Jun Zhao.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/IAG)](https://github.com/Xnhyacinth/IAG)

28. [**Your Transformer is Secretly Linear.**](https://arxiv.org/abs/2405.12250) *Anton Razzhigaev, Matvey Mikhalchuk, Elizaveta Goncharova, Nikolai Gerasimenko, Ivan Oseledets, Denis Dimitrov, Andrey Kuznetsov.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/AIRI-Institute/LLM-Microscope)](https://github.com/AIRI-Institute/LLM-Microscope)

29. [**xRAG: Extreme Context Compression for Retrieval-augmented Generation with One Token.**](https://arxiv.org/abs/2405.13792) *Xin Cheng, Xun Wang, Xingxing Zhang, Tao Ge, Si-Qing Chen, Furu Wei, Huishuai Zhang, Dongyan Zhao.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Hannibal046/xRAG)](https://github.com/Hannibal046/xRAG)

30. [**SelfCP: Compressing Long Prompt to 1/12 Using the Frozen Large Language Model Itself.**](https://arxiv.org/abs/2405.17052) *Jun Gao.* Arxiv 2024.

31. [**Compressing Lengthy Context With UltraGist.**](https://arxiv.org/abs/2405.16635) *Peitian Zhang, Zheng Liu, Shitao Xiao, Ninglu Shao, Qiwei Ye, Zhicheng Dou.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/namespace-Pt/UltraGist)](https://github.com/namespace-Pt/UltraGist)

32. [**XL3M: A Training-free Framework for LLM Length Extension Based on Segment-wise Inference.**](https://arxiv.org/abs/2405.17755) *Shengnan Wang, Youhui Bai, Lin Zhang, Pingyi Zhou, Shixiong Zhao, Gong Zhang, Sen Wang, Renhai Chen, Hua Xu, Hongwei Sun.* Arxiv 2024.

33. [**In-context Autoencoder for Context Compression in a Large Language Model.**](https://openreview.net/forum?id=uREj4ZuGJE) *Tao Ge, Hu Jing, Lei Wang, Xun Wang, Si-Qing Chen, Furu Wei.* ICLR 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/getao/icae)](https://github.com/getao/icae)

34. [**Retaining Key Information under High Compression Ratios: Query-Guided Compressor for LLMs.**](https://arxiv.org/abs/2406.02376) *Zhiwei Cao, Qian Cao, Yu Lu, Ningxin Peng, Luyang Huang, Shanbo Cheng, Jinsong Su.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/DeepLearnXMU/QGC)](https://github.com/DeepLearnXMU/QGC)

35. [**Recurrent Context Compression: Efficiently Expanding the Context Window of LLM.**](https://arxiv.org/abs/2406.06110) *Chensen Huang, Guibo Zhu, Xuepeng Wang, Yifei Luo, Guojing Ge, Haoran Chen, Dong Yi, Jinqiao Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WUHU-G/RCC_Transformer)](https://github.com/WUHU-G/RCC_Transformer)

36. [**LoCoCo: Dropping In Convolutions for Long Context Compression.**](https://arxiv.org/abs/2406.05317) *Ruisi Cai, Yuandong Tian, Zhangyang Wang, Beidi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/LoCoCo)](https://github.com/VITA-Group/LoCoCo)

37. [**Evaluating Zero-Shot Long-Context LLM Compression.**](https://arxiv.org/abs/2406.06773) *Chenyu Wang, Yihan Wang.* Arxiv 2024.

38. [**InstructCMP: Length Control in Sentence Compression through Instruction-based Large Language Models.**](https://arxiv.org/abs/2406.11097) *Juseon-Do, Jingun Kwon, Hidetaka Kamigaito, Manabu Okumura.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/JuseonDo/InstructCMP)](https://github.com/JuseonDo/InstructCMP)

39. [**AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration.**](https://arxiv.org/abs/2306.00978) *Ji Lin, Jiaming Tang, Haotian Tang, Shang Yang, Wei-Ming Chen, Wei-Chen Wang, Guangxuan Xiao, Xingyu Dang, Chuang Gan, Song Han.* MLSys 2024 Best Paper Award.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/JuseonDo/InstructCMP)](https://github.com/JuseonDo/InstructCMP)

40. [**In-Context Former: Lightning-fast Compressing Context for Large Language Model.**](https://arxiv.org/abs/2406.13618) *Xiangfeng Wang, Zaiyi Chen, Zheyong Xie, Tong Xu, Yongyi He, Enhong Chen.* Arxiv 2024.

41. [**UIO-LLMs: Unbiased Incremental Optimization for Long-Context LLMs.**](https://arxiv.org/abs/2406.18173) *Wenhao Li, Mingbao Lin, Yunshan Zhong, Shuicheng Yan, Rongrong Ji.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/wenhaoli-xmu/UIO-LLMs)](https://github.com/wenhaoli-xmu/UIO-LLMs)

42. [**PromptIntern: Saving Inference Costs by Internalizing Recurrent Prompt during Large Language Model Fine-tuning.**](https://arxiv.org/abs/2407.02211) *Jiaru Zou, Mengyu Zhou, Tao Li, Shi Han, Dongmei Zhang.* Arxiv 2024.

43. [**Concise and Precise Context Compression for Tool-Using Language Models.**](https://arxiv.org/abs/2407.02043) *Yang Xu, Yunlong Feng, Honglin Mu, Yutai Hou, Yitong Li, Xinghao Wang, Wanjun Zhong, Zhongyang Li, Dandan Tu, Qingfu Zhu, Min Zhang, Wanxiang Che.* Arxiv 2024.

44. [**Context Embeddings for Efficient Answer Generation in RAG.**](https://arxiv.org/abs/2407.09252) *David Rau, Shuai Wang, Hervé Déjean, Stéphane Clinchant.* Arxiv 2024.

45. [**Characterizing Prompt Compression Methods for Long Context Inference.**](https://arxiv.org/abs/2407.08892) *Siddharth Jha, Lutfi Eren Erdogan, Sehoon Kim, Kurt Keutzer, Amir Gholami.* Arxiv 2024.

46. [**Fundamental Limits of Prompt Compression: A Rate-Distortion Framework for Black-Box Language Models.**](https://arxiv.org/abs/2407.15504) *Adway Girish, Alliot Nagle, Marco Bondaschi, Michael Gastpar, Ashok Vardhan Makkuva, Hyeji Kim.* Arxiv 2024.

47. [**QUITO: Accelerating Long-Context Reasoning through Query-Guided Context Compression.**](https://arxiv.org/abs/2408.00274) *Wenshan Wang, Yihang Wang, Yixing Fan, Huaming Liao, Jiafeng Guo.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Wenshansilvia/attention_compressor)](https://github.com/Wenshansilvia/attention_compressor)

48. [**SentenceVAE: Faster, Longer and More Accurate Inference with Next-sentence Prediction for Large Language Models.**](https://arxiv.org/abs/2408.00655) *Hongjun An, Yifan Chen, Xiaozhen Qiao, Zhe Sun, Xuelong Li.* Arxiv 2024.

49. [**QUITO-X: An Information Bottleneck-based Compression Algorithm with Cross-Attention.**](https://arxiv.org/abs/2408.10497) *Yihang Wang, Xu Huang, Bowen Tian, Yixing Fan, Jiafeng Guo.* Arxiv 2024.

50. [**AdaComp: Extractive Context Compression with Adaptive Predictor for Retrieval-Augmented Large Language Models.**](https://arxiv.org/abs/2409.01579) *Qianchi Zhang, Hainan Zhang, Liang Pang, Hongwei Zheng, Zhiming Zheng.* Arxiv 2024.

51. [**Prompt Compression with Context-Aware Sentence Encoding for Fast and Improved LLM Inference.**](https://arxiv.org/abs/2409.01227) *Barys Liskavets, Maxim Ushakov, Shuvendu Roy, Mark Klibanov, Ali Etemad, Shane Luke.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Workday/cpc)](https://github.com/Workday/cpc)

52. [**Familiarity-aware Evidence Compression for Retrieval Augmented Generation.**](https://arxiv.org/abs/2409.12468) *Dongwon Jung, Qin Liu, Tenghao Huang, Ben Zhou, Muhao Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/luka-group/FaviComp)](https://github.com/luka-group/FaviComp)

53. [**TACO-RL: Task Aware Prompt Compression Optimization with Reinforcement Learning.**](https://arxiv.org/abs/2409.13035) *Shivam Shandilya, Menglin Xia, Supriyo Ghosh, Huiqiang Jiang, Jue Zhang, Qianhui Wu, Victor Rühle.* Arxiv 2024.

54. [**Parse Trees Guided LLM Prompt Compression.**](https://arxiv.org/abs/2409.15395) *Wenhao Mao, Chengbin Hou, Tianyu Zhang, Xinyu Lin, Ke Tang, Hairong Lv.* Arxiv 2024.

55. [**FineZip: Pushing the Limits of Large Language Models for Practical Lossless Text Compression.**](https://arxiv.org/abs/2409.17141) *Fazal Mittu, Yihuan Bu, Akshat Gupta, Ashok Devireddy, Alp Eren Ozdarendeli, Anant Singh, Gopala Anumanchipalli.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/fazalmittu/FineZip)](https://github.com/fazalmittu/FineZip)

56. [**Perception Compressor:A training-free prompt compression method in long context scenarios.**](https://arxiv.org/abs/2409.19272) *Jiwei Tang, Jin Xu, Tingwei Lu, Hai Lin, Yiming Zhao, Hai-Tao Zheng.* Arxiv 2024.

57. [**From Reading to Compressing: Exploring the Multi-document Reader for Prompt Compression.**](https://arxiv.org/abs/2410.04139) *Eunseong Choi, Sunkyung Lee, Minjin Choi, June Park, Jongwuk Lee.* EMNLP 2024.

58. [**Selection-p: Self-Supervised Task-Agnostic Prompt Compression for Faithfulness and Transferability.**](https://arxiv.org/abs/2410.11786) *Tsz Ting Chung, Leyang Cui, Lemao Liu, Xinting Huang, Shuming Shi, Dit-Yan Yeung.* EMNLP 2024.

59. [**Style-Compress: An LLM-Based Prompt Compression Framework Considering Task-Specific Styles.**](https://arxiv.org/abs/2410.14042) *Xiao Pu, Tianxing He, Xiaojun Wan.* EMNLP 2024.

## 10. Long Video and Image

1. [**EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture.**](https://arxiv.org/abs/2405.18991) *Jiaqi Xu, Xinyi Zou, Kunzhe Huang, Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/aigc-apps/EasyAnimate)](https://github.com/aigc-apps/EasyAnimate)

2. [**VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos.**](https://arxiv.org/abs/2405.19209) *Ziyang Wang, Shoubin Yu, Elias Stengel-Eskin, Jaehong Yoon, Feng Cheng, Gedas Bertasius, Mohit Bansal.* Arxiv 2024.

3. [**PostDoc: Generating Poster from a Long Multimodal Document Using Deep Submodular Optimization.**](https://arxiv.org/abs/2405.20213) *Vijay Jaisankar, Sambaran Bandyopadhyay, Kalp Vyas, Varre Chaitanya, Shwetha Somasundaram.* Arxiv 2024.

4. [**Investigating Video Reasoning Capability of Large Language Models with Tropes in Movies.**](https://arxiv.org/abs/2406.10923) *Hung-Ting Su, Chun-Tong Chao, Ya-Ching Hsu, Xudong Lin, Yulei Niu, Hung-Yi Lee, Winston H. Hsu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ander1119/TiM)](https://github.com/ander1119/TiM)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ander1119.github.io/TiM/)

5. [**Towards Event-oriented Long Video Understanding.**](https://arxiv.org/abs/2406.14129) *Yifan Du, Kun Zhou, Yuqi Huo, Yifan Li, Wayne Xin Zhao, Haoyu Lu, Zijia Zhao, Bingning Wang, Weipeng Chen, Ji-Rong Wen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/Event-Bench)](https://github.com/RUCAIBox/Event-Bench)

6. [**An End-to-End Speech Summarization Using Large Language Model.**](https://arxiv.org/abs/2407.02005) *Hengchao Shang, Zongyao Li, Jiaxin Guo, Shaojun Li, Zhiqiang Rao, Yuanchang Luo, Daimeng Wei, Hao Yang.* Arxiv 2024.

7. [**KeyVideoLLM: Towards Large-scale Video Keyframe Selection.**](https://arxiv.org/abs/2407.03104) *Hao Liang, Jiapeng Li, Tianyi Bai, Chong Chen, Conghui He, Bin Cui, Wentao Zhang.* Arxiv 2024.

8. [**OmChat: A Recipe to Train Multimodal Language Models with Strong Long Context and Video Understanding.**](https://arxiv.org/abs/2407.04923) *Tiancheng Zhao, Qianqian Zhang, Kyusong Lee, Peng Liu, Lu Zhang, Chunxin Fang, Jiajia Liao, Kelei Jiang, Yibo Ma, Ruochen Xu.* Arxiv 2024.

9. [**MATE: Meet At The Embedding -- Connecting Images with Long Texts.**](https://arxiv.org/abs/2407.09541) *Young Kyun Jang, Junmo Kang, Yong Jae Lee, Donghyun Kim.* Arxiv 2024.

10. [**mPLUG-Owl3: Towards Long Image-Sequence Understanding in Multi-Modal Large Language Models.**](https://arxiv.org/abs/2408.04840) *Jiabo Ye, Haiyang Xu, Haowei Liu, Anwen Hu, Ming Yan, Qi Qian, Ji Zhang, Fei Huang, Jingren Zhou.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl)](https://github.com/X-PLUG/mPLUG-Owl)

11. [**LongVILA: Scaling Long-Context Visual Language Models for Long Videos.**](https://arxiv.org/abs/2408.10188) *Fuzhao Xue, Yukang Chen, Dacheng Li, Qinghao Hu, Ligeng Zhu, Xiuyu Li, Yunhao Fang, Haotian Tang, Shang Yang, Zhijian Liu, Ethan He, Hongxu Yin, Pavlo Molchanov, Jan Kautz, Linxi Fan, Yuke Zhu, Yao Lu, Song Han.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NVlabs/VILA)](https://github.com/NVlabs/VILA/blob/main/LongVILA.md)

12. [**DreamFactory: Pioneering Multi-Scene Long Video Generation with a Multi-Agent Framework.**](https://arxiv.org/abs/2408.11788) *Zhifei Xie, Daniel Tang, Dingwei Tan, Jacques Klein, Tegawend F. Bissyand, Saad Ezzini.* Arxiv 2024.

13. [**Bridging Episodes and Semantics: A Novel Framework for Long-Form Video Understanding.**](https://arxiv.org/abs/2408.17443) *Gueter Josmy Faure, Jia-Fong Yeh, Min-Hung Chen, Hung-Ting Su, Winston H. Hsu, Shang-Hong Lai.* ECCV 2024 Workshop.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/joslefaure/HERMES)](https://github.com/joslefaure/HERMES)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://joslefaure.github.io/assets/html/hermes.html)

14. [**VideoLLaMB: Long-context Video Understanding with Recurrent Memory Bridges.**](https://arxiv.org/abs/2409.01071) *Yuxuan Wang, Cihang Xie, Yang Liu, Zilong Zheng.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/VideoLLaMB)](https://github.com/bigai-nlco/VideoLLaMB)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://videollamb.github.io/)

15. [**Longer is (Not Necessarily) Stronger: Punctuated Long-Sequence Training for Enhanced Speech Recognition and Translation.**](https://arxiv.org/abs/2409.05601) *Nithin Rao Koluguri, Travis Bartley, Hainan Xu, Oleksii Hrinchuk, Jagadeesh Balam, Boris Ginsburg, Georg Kucsko.* Arxiv 2024.

16. [**LongLLaVA: Scaling Multi-modal LLMs to 1000 Images Efficiently via Hybrid Architecture.**](https://arxiv.org/abs/2409.02889) *Xidong Wang, Dingjie Song, Shunian Chen, Chen Zhang, Benyou Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FreedomIntelligence/LongLLaVA)](https://github.com/FreedomIntelligence/LongLLaVA)

17. [**VideoCLIP-XL: Advancing Long Description Understanding for Video CLIP Models.**](https://arxiv.org/abs/2410.00741) *Jiapeng Wang, Chengyu Wang, Kunzhe Huang, Jun Huang, Lianwen Jin.* Arxiv 2024.

18. [**Rethinking Visual Dependency in Long-Context Reasoning for Large Vision-Language Models.**](https://arxiv.org/abs/2410.19732) *Yucheng Zhou, Zhi Rao, Jun Wan, Jianbing Shen.* Arxiv 2024.

## 11. Benchmark and Evaluation

### 11.1 LLM

1. [**Long Range Arena : A Benchmark for Efficient Transformers.**](https://arxiv.org/abs/2011.04006) *Yi Tay, Mostafa Dehghani, Samira Abnar, Yikang Shen, Dara Bahri, Philip Pham, Jinfeng Rao, Liu Yang, Sebastian Ruder, Donald Metzler.* ICLR 2021.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/long-range-arena)](https://github.com/google-research/long-range-arena)

2. [**LOT: A Story-Centric Benchmark for Evaluating Chinese Long Text Understanding and Generation.**](https://aclanthology.org/2022.tacl-1.25.pdf) *Jian Guan, Zhuoer Feng, Yamei Chen, Ruilin He, Xiaoxi Mao, Changjie Fan, Minlie Huang.* TACL 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/thu-coai/LOT-LongLM)](https://github.com/thu-coai/LOT-LongLM)

3. [**SCROLLS: Standardized CompaRison Over Long Language Sequences.**](https://arxiv.org/abs/2201.03533) *Uri Shaham, Elad Segal, Maor Ivgi, Avia Efrat, Ori Yoran, Adi Haviv, Ankit Gupta, Wenhan Xiong, Mor Geva, Jonathan Berant, Omer Levy.* EMNLP 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/tau-nlp/scrolls)](https://github.com/tau-nlp/scrolls)

4. [**MuLD: The Multitask Long Document Benchmark.**](https://aclanthology.org/2022.lrec-1.392/) *George Hudson, Noura Al Moubayed.* LREC 2022.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ghomasHudson/muld)](https://github.com/ghomasHudson/muld)

5. [**Lost in the Middle: How Language Models Use Long Contexts.**](https://arxiv.org/abs/2307.03172) *Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nelson-liu/lost-in-the-middle)](https://github.com/nelson-liu/lost-in-the-middle)

6. [**L-Eval: Instituting Standardized Evaluation for Long Context Language Models.**](https://arxiv.org/abs/2307.11088) *Chenxin An, Shansan Gong, Ming Zhong, Mukai Li, Jun Zhang, Lingpeng Kong, Xipeng Qiu.* Arxiv 2023.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/OpenLMLab/LEval)](https://github.com/OpenLMLab/LEval)

7. [**LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding.**](https://arxiv.org/abs/2308.14508) *Yushi Bai, Xin Lv, Jiajie Zhang, Hongchang Lyu, Jiankai Tang, Zhidian Huang, Zhengxiao Du, Xiao Liu, Aohan Zeng, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li.* Arxiv 2023. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongBench)](https://github.com/THUDM/LongBench)

8. [**Content Reduction, Surprisal and Information Density Estimation for Long Documents.**](https://arxiv.org/abs/2309.06009) *Shaoxiong Ji, Wei Sun, Pekka Marttinen.* Arxiv 2023.

9. [**BAMBOO: A Comprehensive Benchmark for Evaluating Long Text Modeling Capacities of Large Language Models.**](https://arxiv.org/abs/2309.13345) *Zican Dong, Tianyi Tang, Junyi Li, Wayne Xin Zhao, Ji-Rong Wen.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/BAMBOO)](https://github.com/RUCAIBox/BAMBOO)

10. [**Retrieval meets Long Context Large Language Models.**](https://arxiv.org/abs/2309.13345) *Peng Xu, Wei Ping, Xianchao Wu, Lawrence McAfee, Chen Zhu, Zihan Liu, Sandeep Subramanian, Evelina Bakhturina, Mohammad Shoeybi, Bryan Catanzaro.* Arxiv 2023.

11. [**LooGLE: Long Context Evaluation for Long-Context Language Models.**](https://arxiv.org/pdf/2311.04939v1.pdf) *Jiaqi Li, Mengmeng Wang, Zilong Zheng, Muhan Zhang.* Arxiv 2023.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/loogle)](https://github.com/bigai-nlco/loogle)

12. [**The Impact of Reasoning Step Length on Large Language Models.**](https://arxiv.org/abs/2401.04925v1) *Mingyu Jin, Qinkai Yu, Dong shu, Haiyan Zhao, Wenyue Hua, Yanda Meng, Yongfeng Zhang, Mengnan Du.* Arxiv 2024.

13. [**DocFinQA: A Long-Context Financial Reasoning Dataset.**](https://arxiv.org/abs/2401.06915) *Varshini Reddy, Rik Koncel-Kedziorski, Viet Dac Lai, Chris Tanner.* Arxiv 2024.

14. [**LongFin: A Multimodal Document Understanding Model for Long Financial Domain Documents.**](https://arxiv.org/abs/2401.15050) *Ahmed Masry, Amir Hajian.* Arxiv 2024.

15. [**PROXYQA: An Alternative Framework for Evaluating Long-Form Text Generation with Large Language Models.**](https://arxiv.org/abs/2401.15042) *Haochen Tan, Zhijiang Guo, Zhan Shi, Lu Xu, Zhili Liu, Xiaoguang Li, Yasheng Wang, Lifeng Shang, Qun Liu, Linqi Song.* Arxiv 2024.

16. [**LongHealth: A Question Answering Benchmark with Long Clinical Documents.**](https://arxiv.org/abs/2401.14490) *Lisa Adams, Felix Busch, Tianyu Han, Jean-Baptiste Excoffier, Matthieu Ortala, Alexander Löser, Hugo JWL. Aerts, Jakob Nikolas Kather, Daniel Truhn, Keno Bressem.* Arxiv 2024.

17. [**Long-form evaluation of model editing.**](https://arxiv.org/abs/2402.09394) *Domenic Rosati, Robie Gonzales, Jinkun Chen, Xuemin Yu, Melis Erkan, Yahya Kayani, Satya Deepika Chavatapalli, Frank Rudzicz, Hassan Sajjad.* Arxiv 2024.

18. [**In Search of Needles in a 10M Haystack: Recurrent Memory Finds What LLMs Miss.**](https://arxiv.org/abs/2402.10790v1) *Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

19. [**∞Bench: Extending Long Context Evaluation Beyond 100K Tokens.**](https://arxiv.org/abs/2402.13718) *Xinrong Zhang, Yingfa Chen, Shengding Hu, Zihang Xu, Junhao Chen, Moo Khai Hao, Xu Han, Zhen Leng Thai, Shuo Wang, Zhiyuan Liu, Maosong Sun.* Arxiv 2024.

20. [**Same Task, More Tokens: the Impact of Input Length on the Reasoning Performance of Large Language Models.**](https://arxiv.org/abs/2402.14848) *Mosh Levy, Alon Jacoby, Yoav Goldberg.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/alonj/Same-Task-More-Tokens)](https://github.com/alonj/Same-Task-More-Tokens)

21. [**Evaluating Very Long-Term Conversational Memory of LLM Agents.**](https://arxiv.org/abs/2402.17753) *Adyasha Maharana, Dong-Ho Lee, Sergey Tulyakov, Mohit Bansal, Francesco Barbieri, Yuwei Fang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/snap-research/LoCoMo)](https://github.com/snap-research/LoCoMo)

22. [**Language Models as Science Tutors.**](https://arxiv.org/abs/2402.11111) *Alexis Chevalier, Jiayi Geng, Alexander Wettig, Howard Chen, Sebastian Mizera, Toni Annala, Max Jameson Aragon, Arturo Rodríguez Fanlo, Simon Frieder, Simon Machado, Akshara Prabhakar, Ellie Thieu, Jiachen T. Wang, Zirui Wang, Xindi Wu, Mengzhou Xia, Wenhan Jia, Jiatong Yu, Jun-Jie Zhu, Zhiyong Jason Ren, Sanjeev Arora, Danqi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/LM-Science-Tutor)](https://github.com/princeton-nlp/LM-Science-Tutor)

23. [**Needle in a haystack - pressure testing llms.**](https://github.com/gkamradt/LLMTest_NeedleInAHaystack) *Kamradt, G.* Github 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/gkamradt/LLMTest_NeedleInAHaystack)](https://github.com/gkamradt/LLMTest_NeedleInAHaystack)

24. [**In Search of Needles in a 11M Haystack: Recurrent Memory Finds What LLMs Miss.**](https://arxiv.org/abs/2402.10790) *Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

25. [**LV-Eval: A Balanced Long-Context Benchmark with 5 Length Levels Up to 256K.**](https://arxiv.org/abs/2402.05136) *Tao Yuan, Xuefei Ning, Dong Zhou, Zhijie Yang, Shiyao Li, Minghui Zhuang, Zheyue Tan, Zhuyu Yao, Dahua Lin, Boxun Li, Guohao Dai, Shengen Yan, Yu Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/infinigence/LVEval)](https://github.com/infinigence/LVEval)

26. [**Counting-Stars: A Simple, Efficient, and Reasonable Strategy for Evaluating Long-Context Large Language Models.**](https://arxiv.org/abs/2403.11802) *Mingyang Song, Mao Zheng, Xuan Luo.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/Counting-Stars)](https://github.com/nick7nlp/Counting-Stars)

27. [**NovelQA: A Benchmark for Long-Range Novel Question Answering.**](https://arxiv.org/abs/2403.12766) *Cunxiang Wang, Ruoxi Ning, Boqi Pan, Tonghui Wu, Qipeng Guo, Cheng Deng, Guangsheng Bao, Qian Wang, Yue Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NovelQA/novelqa.github.io)](https://github.com/NovelQA/novelqa.github.io)

28. [**Long-form factuality in large language models.**](https://arxiv.org/abs/2403.18802) *Jerry Wei, Chengrun Yang, Xinying Song, Yifeng Lu, Nathan Hu, Dustin Tran, Daiyi Peng, Ruibo Liu, Da Huang, Cosmo Du, Quoc V. Le.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/long-form-factuality)](https://github.com/google-deepmind/long-form-factuality)

29. [**LUQ: Long-text Uncertainty Quantification for LLMs.**](https://arxiv.org/abs/2403.20279) *JCaiqi Zhang, Fangyu Liu, Marco Basaldella, Nigel Collier.* Arxiv 2024.

30. [**CLongEval: A Chinese Benchmark for Evaluating Long-Context Large Language Models.**](https://arxiv.org/abs/2403.03514) *Zexuan Qiu, Jingjing Li, Shijue Huang, Wanjun Zhong, Irwin King.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zexuanqiu/CLongEval)](https://github.com/zexuanqiu/CLongEval)

31. [**Long-context LLMs Struggle with Long In-context Learning.**](https://arxiv.org/abs/2404.02060) *Tianle Li, Ge Zhang, Quy Duc Do, Xiang Yue, Wenhu Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/LongICLBench)](https://github.com/TIGER-AI-Lab/LongICLBench)

32. [**CLAPNQ: Cohesive Long-form Answers from Passages in Natural Questions for RAG systems.**](https://arxiv.org/abs/2404.02103) *Sara Rosenthal, Avirup Sil, Radu Florian, Salim Roukos.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/primeqa/clapnq)](https://github.com/primeqa/clapnq)

33. [**XL2Bench: A Benchmark for Extremely Long Context Understanding with Long-range Dependencies.**](https://arxiv.org/abs/2404.05446) *Xuanfan Ni, Hengyi Cai, Xiaochi Wei, Shuaiqiang Wang, Dawei Yin, Piji Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nuaa-nlp/XL2Bench)](https://github.com/nuaa-nlp/XL2Bench)

34. [**Never Train from Scratch: Fair Comparison of Long-Sequence Models Requires Data-Driven Priors.**](https://openreview.net/forum?id=PdaPky8MUn) *Ido Amos, Jonathan Berant, Ankit Gupta.* ICLR 2024 Oral.

35. [**Ada-LEval: Evaluating long-context LLMs with length-adaptable benchmarks.**](https://arxiv.org/abs/2404.06480) *Chonghua Wang, Haodong Duan, Songyang Zhang, Dahua Lin, Kai Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/Ada-LEval)](https://github.com/open-compass/Ada-LEval)

36. [**RULER: What's the Real Context Size of Your Long-Context Language Models?.**](https://arxiv.org/abs/2404.06654) *Cheng-Ping Hsieh, Simeng Sun, Samuel Kriman, Shantanu Acharya, Dima Rekesh, Fei Jia, Boris Ginsburg.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/hsiehjackson/RULER)](https://github.com/hsiehjackson/RULER)

37. [**LongEmbed: Extending Embedding Models for Long Context Retrieval.**](https://arxiv.org/abs/2404.12096) *Dawei Zhu, Liang Wang, Nan Yang, Yifan Song, Wenhao Wu, Furu Wei, Sujian Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/LongEmbed)](https://github.com/dwzhu-pku/LongEmbed)

38. [**Make Your LLM Fully Utilize the Context.**](https://arxiv.org/abs/2404.16811) *Shengnan An, Zexiong Ma, Zeqi Lin, Nanning Zheng, Jian-Guang Lou.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/FILM)](https://github.com/microsoft/FILM)

39. [**S3Eval: A Synthetic, Scalable, Systematic Evaluation Suite for Large Language Models.**](https://arxiv.org/abs/2310.15147) *Fangyu Lei, Qian Liu, Yiming Huang, Shizhu He, Jun Zhao, Kang Liu.* NAACL 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/lfy79001/S3Eval)](https://github.com/lfy79001/S3Eval)

40. [**In-Context Learning with Long-Context Models: An In-Depth Exploration.**](https://arxiv.org/abs/2405.00200) *Amanda Bertsch, Maor Ivgi, Uri Alon, Jonathan Berant, Matthew R. Gormley, Graham Neubig.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/abertsch72/long-context-icl)](https://github.com/abertsch72/long-context-icl)

42. [**Many-shot Jailbreaking.**](https://www-cdn.anthropic.com/af5633c94ed2beb282f6a53c595eb437e8e7b630/Many_Shot_Jailbreaking__2024_04_02_0936.pdf)  Anthropic 2024.

43. [**DOLOMITES: Domain-Specific Long-Form Methodical Tasks.**](https://arxiv.org/abs/2405.05938) *Chaitanya Malaviya, Priyanka Agrawal, Kuzman Ganchev, Pranesh Srinivasan, Fantine Huot, Jonathan Berant, Mark Yatskar, Dipanjan Das, Mirella Lapata, Chris Alberti.* Arxiv 2024.

44. [**Challenges in Deploying Long-Context Transformers: A Theoretical Peak Performance Analysis.**](https://arxiv.org/abs/2405.08944) *Yao Fu.* Arxiv 2024.

45. [**FinTextQA: A Dataset for Long-form Financial Question Answering.**](https://arxiv.org/abs/2405.09980) *Jian Chen, Peilin Zhou, Yining Hua, Yingxin Loh, Kehui Chen, Ziyuan Li, Bing Zhu, Junwei Liang.* Arxiv 2024.

46. [**A Multi-Perspective Analysis of Memorization in Large Language Models.**](https://arxiv.org/abs/2405.11577) *Bowen Chen, Namgi Han, Yusuke Miyao.* Arxiv 2024.

47. [**OLAPH: Improving Factuality in Biomedical Long-form Question Answering.**](https://arxiv.org/abs/2405.12701) *Minbyul Jeong, Hyeon Hwang, Chanwoong Yoon, Taewhoo Lee, Jaewoo Kang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dmis-lab/OLAPH)](https://github.com/dmis-lab/OLAPH)

48. [**Can LLMs Solve longer Math Word Problems Better?.**](https://arxiv.org/abs/2405.14804) *Xin Xu, Tong Xiao, Zitong Chao, Zhenya Huang, Can Yang, Yang Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/XinXU-USTC/CoLeG-Math)](https://github.com/XinXU-USTC/CoLeG-Math)

49. [**Base of RoPE Bounds Context Length.**](https://arxiv.org/abs/2405.14591) *Xin Men, Mingyu Xu, Bingning Wang, Qingyu Zhang, Hongyu Lin, Xianpei Han, Weipeng Chen.* Arxiv 2024.

50. [**Many-shot In-Context Learning.**](https://arxiv.org/abs/2404.11018) *Rishabh Agarwal, Avi Singh, Lei M. Zhang, Bernd Bohnet, Luis Rosias, Stephanie Chan, Biao Zhang, Ankesh Anand, Zaheer Abbas, Azade Nova, John D. Co-Reyes, Eric Chu, Feryal Behbahani, Aleksandra Faust, Hugo Larochelle.* Arxiv 2024.
 
51. [**Long Context is Not Long at All: A Prospector of Long-Dependency Data for Large Language Models.**](https://arxiv.org/abs/2405.17915) *Longze Chen, Ziqiang Liu, Wanwei He, Yunshui Li, Run Luo, Min Yang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/October2001/ProLong)](https://github.com/October2001/ProLong)

52. [**Language Models Need Inductive Biases to Count Inductively.**](https://arxiv.org/abs/2405.20131) *Yingshan Chang, Yonatan Bisk.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/zdxdsw/inductive_counting_with_LMs)](https://github.com/zdxdsw/inductive_counting_with_LMs)

53. [**Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding.**](https://arxiv.org/abs/2406.02472) *Zhihan Zhang, Yixin Cao, Chenchen Ye, Yunshan Ma, Lizi Liao, Tat-Seng Chua.* Arxiv 2024.

54. [**CRAG -- Comprehensive RAG Benchmark.**](https://arxiv.org/abs/2406.04744) *Xiao Yang, Kai Sun, Hao Xin, Yushi Sun, Nikita Bhalla, Xiangsen Chen, Sajal Choudhary, Rongze Daniel Gui, Ziran Will Jiang, Ziyu Jiang, Lingkun Kong, Brian Moran, Jiaqi Wang, Yifan Ethan Xu, An Yan, Chenyu Yang, Eting Yuan, Hanwen Zha, Nan Tang, Lei Chen, Nicolas Scheffer, Yue Liu, Nirav Shah, Rakesh Wanga, Anuj Kumar, Wen-tau Yih, Xin Luna Dong.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.aicrowd.com/challenges/meta-comprehensive-rag-benchmark-kdd-cup-2024)

55. [**An Empirical Study of Mamba-based Language Models.**](https://arxiv.org/abs/2406.07887) *Roger Waleffe, Wonmin Byeon, Duncan Riach, Brandon Norick, Vijay Korthikanti, Tri Dao, Albert Gu, Ali Hatamizadeh, Sudhakar Singh, Deepak Narayanan, Garvit Kulshreshtha, Vartika Singh, Jared Casper, Jan Kautz, Mohammad Shoeybi, Bryan Catanzaro.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM)](https://github.com/NVIDIA/Megatron-LM/tree/ssm/examples/mamba)

56. [**BABILong: Testing the Limits of LLMs with Long Context Reasoning-in-a-Haystack.**](https://arxiv.org/abs/2406.10149) *Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Ivan Rodkin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

57. [**Can Many-Shot In-Context Learning Help Long-Context LLM Judges? See More, Judge Better!.**](https://arxiv.org/abs/2406.11629) *Mingyang Song, Mao Zheng, Xuan Luo.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/SeeMoreJudgeBetter)](https://github.com/nick7nlp/SeeMoreJudgeBetter)

58. [**What Kinds of Tokens Benefit from Distant Text? An Analysis on Long Context Language Modeling.**](https://arxiv.org/abs/2406.11238) *Yutong Hu, Quzhe Huang, Kangcheng Luo, Yansong Feng.* Arxiv 2024.

59. [**Understanding the RoPE Extensions of Long-Context LLMs: An Attention Perspective.**](https://arxiv.org/abs/2406.13282) *Meizhi Zhong, Chen Zhang, Yikun Lei, Xikai Liu, Yan Gao, Yao Hu, Kehai Chen, Min Zhang.* Arxiv 2024.

60. [**Can Long-Context Language Models Subsume Retrieval, RAG, SQL, and More?.**](https://arxiv.org/abs/2406.13121) *Jinhyuk Lee, Anthony Chen, Zhuyun Dai, Dheeru Dua, Devendra Singh Sachan, Michael Boratko, Yi Luan, Sébastien M. R. Arnold, Vincent Perot, Siddharth Dalmia, Hexiang Hu, Xudong Lin, Panupong Pasupat, Aida Amini, Jeremy R. Cole, Sebastian Riedel, Iftekhar Naim, Ming-Wei Chang, Kelvin Guu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/loft)](https://github.com/google-deepmind/loft)

61. [**Insights into LLM Long-Context Failures: When Transformers Know but Don't Tell.**](https://arxiv.org/abs/2406.14673) *Taiming Lu, Muhan Gao, Kuai Yu, Adam Byerly, Daniel Khashabi.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TaiMingLu/know-dont-tell)](https://github.com/TaiMingLu/know-dont-tell)

62. [**MedOdyssey: A Medical Domain Benchmark for Long Context Evaluation Up to 200K Tokens.**](https://arxiv.org/abs/2406.15019) *Yongqi Fan, Hongli Sun, Kui Xue, Xiaofan Zhang, Shaoting Zhang, Tong Ruan.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/JOHNNY-fans/MedOdyssey)](https://github.com/JOHNNY-fans/MedOdyssey)

63. [**USDC: A Dataset of $\underline{U}$ser $\underline{S}$tance and $\underline{D}$ogmatism in Long $\underline{C}$onversations.**](https://arxiv.org/abs/2406.16833) *Mounika Marreddy, Subba Reddy Oota, Venkata Charan Chinni, Manish Gupta, Lucie Flek.* Arxiv 2024.

64. [**Found in the Middle: Calibrating Positional Attention Bias Improves Long Context Utilization.**](https://arxiv.org/abs/2406.16008) *Cheng-Yu Hsieh, Yung-Sung Chuang, Chun-Liang Li, Zifeng Wang, Long T. Le, Abhishek Kumar, James Glass, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister.* Arxiv 2024.

65. [**One Thousand and One Pairs: A "novel" challenge for long-context language models.**](https://arxiv.org/abs/2406.16264) *Marzena Karpinska, Katherine Thai, Kyle Lo, Tanya Goyal, Mohit Iyyer.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/marzenakrp/nocha)](https://github.com/marzenakrp/nocha/)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://novelchallenge.github.io/)

66. [**LongIns: A Challenging Long-context Instruction-based Exam for LLMs.**](https://arxiv.org/abs/2406.17588) *Shawn Gavin, Tuney Zheng, Jiaheng Liu, Quehry Que, Noah Wang, Jian Yang, Chenchen Zhang, Wenhao Huang, Wenhu Chen, Ge Zhang.* Arxiv 2024.

67. [**Leave No Document Behind: Benchmarking Long-Context LLMs with Extended Multi-Doc QA.**](https://arxiv.org/abs/2406.17419) *Minzheng Wang, Longze Chen, Cheng Fu, Shengyi Liao, Xinghua Zhang, Bingli Wu, Haiyang Yu, Nan Xu, Lei Zhang, Run Luo, Yunshui Li, Min Yang, Fei Huang, Yongbin Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MozerWang/Loong)](https://github.com/MozerWang/Loong)

68. [**VERISCORE: Evaluating the factuality of verifiable claims in long-form text generation.**](https://arxiv.org/abs/2406.19276) *Yixiao Song, Yekyung Kim, Mohit Iyyer.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Yixiao-Song/VeriScore)](https://github.com/Yixiao-Song/VeriScore)

69. [**ToolBeHonest: A Multi-level Hallucination Diagnostic Benchmark for Tool-Augmented Large Language Models.**](https://arxiv.org/abs/2406.20015) *Yuxiang Zhang, Jing Chen, Junjie Wang, Yaxin Liu, Cheng Yang, Chufan Shi, Xinyu Zhu, Zihao Lin, Hanwen Wan, Yujiu Yang, Tetsuya Sakai, Tian Feng, Hayato Yamana.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ToolBeHonest/ToolBeHonest)](https://github.com/ToolBeHonest/ToolBeHonest)

70. [**KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches.**](https://arxiv.org/abs/2407.01527) *Jiayi Yuan, Hongyi Liu, Shaochen (Henry)Zhong, Yu-Neng Chuang, Songchen Li, Guanchu Wang, Duy Le, Hongye Jin, Vipin Chaudhary, Zhaozhuo Xu, Zirui Liu, Xia Hu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/henryzhongsc/longctx_bench)](https://github.com/henryzhongsc/longctx_bench)

71. [**Is It Really Long Context if All You Need Is Retrieval? Towards Genuinely Difficult Long Context NLP.**](https://arxiv.org/abs/2407.00402) *Omer Goldman, Alon Jacovi, Aviv Slobodkin, Aviya Maimon, Ido Dagan, Reut Tsarfaty.* Arxiv 2024.

72. [**Summary of a Haystack: A Challenge to Long-Context LLMs and RAG Systems.**](https://arxiv.org/abs/2407.01370) *Philippe Laban, Alexander R. Fabbri, Caiming Xiong, Chien-Sheng Wu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/salesforce/summary-of-a-haystack)](https://github.com/salesforce/summary-of-a-haystack)

73. [**Entity-Level Sentiment: More than the Sum of Its Parts.**](https://arxiv.org/abs/2407.03916) *Egil Rønningstad, Roman Klinger, Erik Velldal, Lilja Øvrelid.* Arxiv 2024.

74. [**Evaluating Language Model Context Windows: A "Working Memory" Test and Inference-time Correction.**](https://arxiv.org/abs/2407.03651) *Amanda Dsouza, Christopher Glaze, Changho Shin, Frederic Sala.* Arxiv 2024.

75. [**RAG vs. Long Context: Examining Frontier Large Language Models for Environmental Review Document Comprehension.**](https://arxiv.org/abs/2407.07321) *Hung Phan, Anurag Acharya, Sarthak Chaturvedi, Shivam Sharma, Mike Parker, Dan Nally, Ali Jannesari, Karl Pazdernik, Mahantesh Halappanavar, Sai Munikoti, Sameera Horawalavithana.* Arxiv 2024.

76. [**Attribute or Abstain: Large Language Models as Long Document Assistants.**](https://arxiv.org/abs/2407.07799) *Jan Buchmann, Xiao Liu, Iryna Gurevych.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/UKPLab/arxiv2024-attribute-or-abstain)](https://github.com/UKPLab/arxiv2024-attribute-or-abstain)

77. [**How Well Can a Long Sequence Model Model Long Sequences? Comparing Architechtural Inductive Biases on Long-Context Abilities.**](https://arxiv.org/abs/2407.08112) *Jerry Huang.* Arxiv 2024.

78. [**DOCBENCH: A Benchmark for Evaluating LLM-based Document Reading Systems.**](https://arxiv.org/abs/2407.10701) *Anni Zou, Wenhao Yu, Hongming Zhang, Kaixin Ma, Deng Cai, Zhuosheng Zhang, Hai Zhao, Dong Yu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Anni-Zou/DocBench)](https://github.com/Anni-Zou/DocBench)

79. [**NeedleBench: Can LLMs Do Retrieval and Reasoning in 1 Million Context Window?.**](https://arxiv.org/abs/2407.11963) *Mo Li, Songyang Zhang, Yunxin Liu, Kai Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/opencompass)](https://github.com/open-compass/opencompass)

80. [**LongLaMP: A Benchmark for Personalized Long-form Text Generation.**](https://arxiv.org/abs/2407.11016) *Ishita Kumar, Snigdha Viswanathan, Sushrita Yerra, Alireza Salemi, Ryan A. Rossi, Franck Dernoncourt, Hanieh Deilamsalehy, Xiang Chen, Ruiyi Zhang, Shubham Agarwal, Nedim Lipka, Hamed Zamani.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://longlamp-benchmark.github.io/)

81. [**RAG-QA Arena: Evaluating Domain Robustness for Long-form Retrieval Augmented Question Answering.**](https://arxiv.org/abs/2407.13998) *Rujun Han, Yuhao Zhang, Peng Qi, Yumo Xu, Jenyuan Wang, Lan Liu, William Yang Wang, Bonan Min, Vittorio Castelli.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/awslabs/rag-qa-arena)](https://github.com/awslabs/rag-qa-arena)

82. [**Attention Is All You Need But You Don't Need All Of It For Inference of Large Language Models.**](https://arxiv.org/abs/2407.15516) *Georgy Tyukin, Gbetondji J-S Dovonon, Jean Kaddour, Pasquale Minervini.* ICML 2024 TF2M workshop.

83. [**Stress-Testing Long-Context Language Models with Lifelong ICL and Task Haystack.**](https://arxiv.org/abs/2407.16695) *Xiaoyue Xu, Qinyuan Ye, Xiang Ren.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/INK-USC/Lifelong-ICL)](https://github.com/INK-USC/Lifelong-ICL)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://inklab.usc.edu/lifelong-icl/)

84. [**WildHallucinations: Evaluating Long-form Factuality in LLMs with Real-World Entity Queries.**](https://arxiv.org/abs/2407.17468) *Wenting Zhao, Tanya Goyal, Yu Ying Chiu, Liwei Jiang, Benjamin Newman, Abhilasha Ravichander, Khyathi Chandu, Ronan Le Bras, Claire Cardie, Yuntian Deng, Yejin Choi.* Arxiv 2024.

85. [**Retrieval Augmented Generation or Long-Context LLMs? A Comprehensive Study and Hybrid Approach.**](https://arxiv.org/abs/2407.16833) *Zhuowan Li, Cheng Li, Mingyang Zhang, Qiaozhu Mei, Michael Bendersky.* Arxiv 2024.

86. [**Evaluating Long Range Dependency Handling in Code Generation Models using Multi-Step Key Retrieval.**](https://arxiv.org/abs/2407.21049) *Yannick Assogba, Donghao Ren.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/apple/ml-key-retrieval-code-tasks)](https://github.com/apple/ml-key-retrieval-code-tasks)

87. [**Long Input Benchmark for Russian Analysis.**](https://arxiv.org/abs/2408.02439) *Igor Churin, Murat Apishev, Maria Tikhonova, Denis Shevelev, Aydar Bulatov, Yuri Kuratov, Sergej Averkiev, Alena Fenogenova.* Arxiv 2024.

88. [**CoverBench: A Challenging Benchmark for Complex Claim Verification.**](https://arxiv.org/abs/2408.03325) *Alon Jacovi, Moran Ambar, Eyal Ben-David, Uri Shaham, Amir Feder, Mor Geva, Dror Marcus, Avi Caciularu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/datasets/google/coverbench)

89. [**LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs.**](https://arxiv.org/abs/2408.07055) *Yushi Bai, Jiajie Zhang, Xin Lv, Linzhi Zheng, Siqi Zhu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongWriter)](https://github.com/THUDM/LongWriter)

90. [**Multilingual Needle in a Haystack: Investigating Long-Context Behavior of Multilingual Large Language Models.**](https://arxiv.org/abs/2408.10151) *Amey Hengle, Prasoon Bajpai, Soham Dan, Tanmoy Chakraborty.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/AmeyHengle/multilingual-needle-in-a-haystack)](https://github.com/AmeyHengle/multilingual-needle-in-a-haystack)

91. [**LongGenBench: Benchmarking Long-Form Generation in Long Context LLMs.**](https://arxiv.org/abs/2409.02076) *Yuhao Wu, Ming Shan Hee, Zhiqing Hu, Roy Ka-Wei Lee.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mozhu621/LongGenBench)](https://github.com/mozhu621/LongGenBench/)

92. [**What are the Essential Factors in Crafting Effective Long Context Multi-Hop Instruction Datasets? Insights and Best Practices.**](https://arxiv.org/abs/2409.01893) *Zhi Chen, Qiguang Chen, Libo Qin, Qipeng Guo, Haijun Lv, Yicheng Zou, Wanxiang Che, Hang Yan, Kai Chen, Dahua Lin.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/WowCZ/LongMIT)](https://github.com/WowCZ/LongMIT)

93. [**Retrieval Or Holistic Understanding? Dolce: Differentiate Our Long Context Evaluation Tasks.**](https://arxiv.org/abs/2409.06338) *Zi Yang.* Arxiv 2024.

94. [**A Controlled Study on Long Context Extension and Generalization in LLMs.**](https://arxiv.org/abs/2409.12181) *Yi Lu, Jing Nathan Yan, Songlin Yang, Justin T. Chiu, Siyu Ren, Fei Yuan, Wenting Zhao, Zhiyong Wu, Alexander M. Rush.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Leooyii/LCEG)](https://github.com/Leooyii/LCEG)

95. [**RAD-Bench: Evaluating Large Language Models Capabilities in Retrieval Augmented Dialogues.**](https://arxiv.org/abs/2409.12558) *Tzu-Lin Kuo, Feng-Ting Liao, Mu-Wei Hsieh, Fu-Chieh Chang, Po-Chun Hsu, Da-Shan Shiu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mtkresearch/RAD-Bench)](https://github.com/mtkresearch/RAD-Bench)

96. [**Fact, Fetch, and Reason: A Unified Evaluation of Retrieval-Augmented Generation.**](https://arxiv.org/abs/2409.12941) *Satyapriya Krishna, Kalpesh Krishna, Anhad Mohananey, Steven Schwarcz, Adam Stambler, Shyam Upadhyay, Manaal Faruqui.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/datasets/google/frames-benchmark)

97. [**Michelangelo: Long Context Evaluations Beyond Haystacks via Latent Structure Queries.**](https://arxiv.org/abs/2409.12640) *Kiran Vodrahalli, Santiago Ontanon, Nilesh Tripuraneni, Kelvin Xu, Sanil Jain, Rakesh Shivanna, Jeffrey Hui, Nishanth Dikkala, Mehran Kazemi, Bahare Fatemi, Rohan Anil, Ethan Dyer, Siamak Shakeri, Roopali Vij, Harsh Mehta, Vinay Ramasesh, Quoc Le, Ed Chi, Yifeng Lu, Orhan Firat, Angeliki Lazaridou, Jean-Baptiste Lespiau, Nithya Attaluri, Kate Olszewska.* Arxiv 2024.

98. [**DetectiveQA: Evaluating Long-Context Reasoning on Detective Novels.**](https://arxiv.org/abs/2409.02465) *Zhe Xu, Jiasheng Ye, Xiangyang Liu, Tianxiang Sun, Xiaoran Liu, Qipeng Guo, Linlin Li, Qun Liu, Xuanjing Huang, Xipeng Qiu.* Arxiv 2024.

99. [**LongCite: Enabling LLMs to Generate Fine-grained Citations in Long-context QA.**](https://arxiv.org/abs/2409.02897) *Jiajie Zhang, Yushi Bai, Xin Lv, Wanjun Gu, Danqing Liu, Minhao Zou, Shulin Cao, Lei Hou, Yuxiao Dong, Ling Feng, Juanzi Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongCite)](https://github.com/THUDM/LongCite)

100. [**HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models.**](https://arxiv.org/abs/2409.16191) *Haoran Que, Feiyu Duan, Liqun He, Yutao Mou, Wangchunshu Zhou, Jiaheng Liu, Wenge Rong, Zekun Moore Wang, Jian Yang, Ge Zhang, Junran Peng, Zhaoxiang Zhang, Songyang Zhang, Kai Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Tintri/hello-bench)](https://github.com/Tintri/hello-bench)

101. [**Multilingual Evaluation of Long Context Retrieval and Reasoning.**](https://arxiv.org/abs/2409.18006) *Ameeta Agrawal, Andy Dang, Sina Bagheri Nezhad, Rhitabrat Pokharel, Russell Scheinberg.* Arxiv 2024.
  
102. [**L-CiteEval: Do Long-Context Models Truly Leverage Context for Responding?**](https://arxiv.org/abs/2410.02115) *Zecheng Tang, Keyan Zhou, Juntao Li, Baibei Ji, Jianye Hou, Min Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/ZetangForward/L-CITEEVAL)](https://github.com/ZetangForward/L-CITEEVAL)

103. [**HELMET: How to Evaluate Long-Context Language Models Effectively and Thoroughly.**](https://arxiv.org/abs/2410.02694) *Howard Yen, Tianyu Gao, Minmin Hou, Ke Ding, Daniel Fleischer, Peter Izasak, Moshe Wasserblat, Danqi Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/HELMET)](https://github.com/princeton-nlp/HELMET)

104. [**MathHay: An Automated Benchmark for Long-Context Mathematical Reasoning in LLMs.**](https://arxiv.org/abs/2410.04698) *Lei Wang, Shan Dong, Yuhui Xu, Hanze Dong, Yalu Wang, Amrita Saha, Ee-Peng Lim, Caiming Xiong, Doyen Sahoo.* Arxiv 2024.

105. [**LongGenBench: Long-context Generation Benchmark.**](https://arxiv.org/abs/2410.04199) *Xiang Liu, Peijie Dong, Xuming Hu, Xiaowen Chu.* EMNLP 2024.

106. [**Hyper-multi-step: The Truth Behind Difficult Long-context Tasks.**](https://arxiv.org/abs/2410.04422) *Yijiong Yu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/yuyijiong/hard_retrieval_for_llm)](https://github.com/yuyijiong/hard_retrieval_for_llm)

107. [**Holistic Reasoning with Long-Context LMs: A Benchmark for Database Operations on Massive Textual Data.**](https://arxiv.org/abs/2410.11996) *Seiji Maekawa, Hayate Iso, Nikita Bhutani.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/megagonlabs/holobench)](https://github.com/megagonlabs/holobench)

108. [**How much do contextualized representations encode long-range context?.**](https://arxiv.org/abs/2410.12292) *Simeng Sun, Cheng-Ping Hsieh.* Arxiv 2024.

109. [**LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory.**](https://arxiv.org/abs/2410.10813) *Di Wu, Hongwei Wang, Wenhao Yu, Yuwei Zhang, Kai-Wei Chang, Dong Yu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/xiaowu0162/LongMemEval)](https://github.com/xiaowu0162/LongMemEval)

110. [**When Attention Sink Emerges in Language Models: An Empirical View.**](https://arxiv.org/abs/2410.10781) *Xiangming Gu, Tianyu Pang, Chao Du, Qian Liu, Fengzhuo Zhang, Cunxiao Du, Ye Wang, Min Lin.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/Attention-Sink)](https://github.com/sail-sg/Attention-Sink)

111. [**Minimum Tuning to Unlock Long Output from LLMs with High Quality Data as the Key.**](https://arxiv.org/abs/2410.10210) *Yingda Chen, Xingjun Wang, Jintao Huang, Yunlin Mao, Daoze Zhang, Yuze Zhao.* Arxiv 2024.

112. [**Distance between Relevant Information Pieces Causes Bias in Long-Context LLMs.**](https://arxiv.org/abs/2410.14641) *Runchu Tian, Yanghao Li, Yuepeng Fu, Siyang Deng, Qinyu Luo, Cheng Qian, Shuo Wang, Xin Cong, Zhong Zhang, Yesai Wu, Yankai Lin, Huadong Wang, Xiaojiang Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Rachum-thu/LongPiBench)](https://github.com/Rachum-thu/LongPiBench)

113. [**ETHIC: Evaluating Large Language Models on Long-Context Tasks with High Information Coverage.**](https://arxiv.org/abs/2410.16848) *Taewhoo Lee, Chanwoong Yoon, Kyochul Jang, Donghyeon Lee, Minju Song, Hyunjae Kim, Jaewoo Kang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/dmis-lab/ETHIC)](https://github.com/dmis-lab/ETHIC)

### 11.2 MLLM

1. [**MileBench: Benchmarking MLLMs in Long Context.**](https://arxiv.org/abs/2404.18532) *Dingjie Song, Shunian Chen, Guiming Hardy Chen, Fei Yu, Xiang Wan, Benyou Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MileBench/MileBench)](https://github.com/MileBench/MileBench)

2. [**Many-Shot In-Context Learning in Multimodal Foundation Models.**](https://arxiv.org/abs/2405.09798) *Yixing Jiang, Jeremy Irvin, Ji Hun Wang, Muhammad Ahmed Chaudhry, Jonathan H. Chen, Andrew Y. Ng.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/stanfordmlgroup/ManyICL)](https://github.com/stanfordmlgroup/ManyICL)

3. [**MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding.**](https://arxiv.org/abs/2406.04264) *Junjie Zhou, Yan Shu, Bo Zhao, Boya Wu, Shitao Xiao, Xi Yang, Yongping Xiong, Bo Zhang, Tiejun Huang, Zheng Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding/tree/master/MLVU)

4. [**RepoQA: Evaluating Long Context Code Understanding.**](https://arxiv.org/abs/2406.06025) *Jiawei Liu, Jia Le Tian, Vijay Daita, Yuxiang Wei, Yifeng Ding, Yuhan Katherine Wang, Jun Yang, Lingming Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/evalplus/repoqa)](https://github.com/evalplus/repoqa)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://evalplus.github.io/repoqa.html)

5. [**Short Film Dataset (SFD): A Benchmark for Story-Level Video Understanding.**](https://arxiv.org/abs/2406.10221) *Ridouane Ghermi, Xi Wang, Vicky Kalogeiton, Ivan Laptev.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/shortfilmdataset/ShortFilmDataset)](https://github.com/shortfilmdataset/ShortFilmDataset)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://shortfilmdataset.github.io/)

6. [**Multimodal Needle in a Haystack: Benchmarking Long-Context Capability of Multimodal Large Language Models.**](https://arxiv.org/abs/2406.11230) *Hengyi Wang, Haizhou Shi, Shiwei Tan, Weiyi Qin, Wenyuan Wang, Tunyu Zhang, Akshay Nambi, Tanuja Ganu, Hao Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/Wang-ML-Lab/multimodal-needle-in-a-haystack)](https://github.com/Wang-ML-Lab/multimodal-needle-in-a-haystack)

7. [**Losing Visual Needles in Image Haystacks: Vision Language Models are Easily Distracted in Short and Long Contexts.**](https://arxiv.org/abs/2406.16851) *Aditya Sharma, Michael Saxon, William Yang Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://locovqa.github.io/)

8. [**MMLongBench-Doc: Benchmarking Long-context Document Understanding with Visualizations.**](https://arxiv.org/abs/2407.01523) *Yubo Ma, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, Ziyu Liu, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-Gang Jiang, Jiaqi Wang, Yixin Cao, Aixin Sun.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mayubo2333/MMLongBench-Doc)](https://github.com/mayubo2333/MMLongBench-Doc)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://mayubo2333.github.io/MMLongBench-Doc/)

9. [**InternLM-XComposer-2.5: A Versatile Large Vision Language Model Supporting Long-Contextual Input and Output.**](https://arxiv.org/abs/2407.03320) *Pan Zhang, Xiaoyi Dong, Yuhang Zang, Yuhang Cao, Rui Qian, Lin Chen, Qipeng Guo, Haodong Duan, Bin Wang, Linke Ouyang, Songyang Zhang, Wenwei Zhang, Yining Li, Yang Gao, Peng Sun, Xinyue Zhang, Wei Li, Jingwen Li, Wenhai Wang, Hang Yan, Conghui He, Xingcheng Zhang, Kai Chen, Jifeng Dai, Yu Qiao, Dahua Lin, Jiaqi Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/InternLM-XComposer)](https://github.com/InternLM/InternLM-XComposer)

10. [**Stark: Social Long-Term Multi-Modal Conversation with Persona Commonsense Knowledge.**](https://arxiv.org/abs/2407.03958) *Young-Jun Lee, Dokyong Lee, Junyoung Youn, Kyeongjin Oh, Byungsoo Ko, Jonghwan Hyeon, Ho-Jin Choi.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/passing2961/Stark)](https://github.com/passing2961/Stark)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://stark-dataset.github.io/)

11. [**SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers.**](https://arxiv.org/abs/2407.09413) *Shraman Pramanick, Rama Chellappa, Subhashini Venugopalan.* Arxiv 2024.

12. [**LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding.**](https://arxiv.org/abs/2407.15754) *Haoning Wu, Dongxu Li, Bei Chen, Junnan Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/longvideobench/LongVideoBench)](https://github.com/longvideobench/LongVideoBench)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://longvideobench.github.io/)

13. [**mGTE: Generalized Long-Context Text Representation and Reranking Models for Multilingual Text Retrieval.**](https://arxiv.org/abs/2407.19669) *Xin Zhang, Yanzhao Zhang, Dingkun Long, Wen Xie, Ziqi Dai, Jialong Tang, Huan Lin, Baosong Yang, Pengjun Xie, Fei Huang, Meishan Zhang, Wenjie Li, Min Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/Alibaba-NLP/gte-multilingual-base)

14. [**MovieSum: An Abstractive Summarization Dataset for Movie Screenplays.**](https://arxiv.org/abs/2408.06281) *Rohit Saxena, Frank Keller.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/saxenarohit/MovieSum)](https://github.com/saxenarohit/MovieSum)

15. [**SEED-Story: Multimodal Long Story Generation with Large Language Model.**](https://arxiv.org/abs/2407.08683) *Shuai Yang, Yuying Ge, Yang Li, Yukang Chen, Yixiao Ge, Ying Shan, Yingcong Chen.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/TencentARC/SEED-Story)](https://github.com/TencentARC/SEED-Story)

## 12. Long Text Generation

1. [**Integrating Planning into Single-Turn Long-Form Text Generation.**](https://arxiv.org/abs/2410.06203) *Yi Liang, You Wu, Honglei Zhuang, Li Chen, Jiaming Shen, Yiling Jia, Zhen Qin, Sumit Sanghai, Xuanhui Wang, Carl Yang, Michael Bendersky.* Arxiv 2024.

2. [**Minimum Tuning to Unlock Long Output from LLMs with High Quality Data as the Key.**](https://arxiv.org/abs/2410.10210) *Yingda Chen, Xingjun Wang, Jintao Huang, Yunlin Mao, Daoze Zhang, Yuze Zhao.* Arxiv 2024.

3. [**LongGenBench: Long-context Generation Benchmark.**](https://arxiv.org/abs/2410.04199) *Xiang Liu, Peijie Dong, Xuming Hu, Xiaowen Chu.* EMNLP 2024.

4. [**LoGU: Long-form Generation with Uncertainty Expressions.**](https://arxiv.org/abs/2410.14309) *Ruihan Yang, Caiqi Zhang, Zhisong Zhang, Xinting Huang, Sen Yang, Nigel Collier, Dong Yu, Deqing Yang.* Arxiv 2024.

5. [**Large Language Models Still Exhibit Bias in Long Text.**](https://arxiv.org/abs/2410.17519) *Wonje Jeung, Dongjae Jeon, Ashkan Yousefpour, Jonghyun Choi.* Arxiv 2024.

## 13. Blogs

1. [**Extending Context is Hard…but not Impossible†.**](https://kaiokendev.github.io/context) *kaiokendev.* 2023.

2. [**NTK-Aware Scaled RoPE.**](https://www.reddit.com/r/LocalLLaMA/comments/14lz7j5/ntkaware_scaled_rope_allows_llama_models_to_have/) *u/bloc97
.* 2023.

3. [**The Secret Sauce behind 100K context window in LLMs: all tricks in one place.**](https://blog.gopenai.com/how-to-speed-up-llms-and-use-100k-context-window-all-tricks-in-one-place-ffd40577b4c) *Galina Alperovich.* 2023.

4. [**Transformer升级之路：7、长度外推性与局部注意力.**](https://kexue.fm/archives/9431) *苏剑林(Jianlin Su).* 2023.

5. [**Transformer升级之路：9、一种全局长度外推的新思路.**](https://kexue.fm/archives/9603) *苏剑林(Jianlin Su).* 2023.

6. [**Transformer升级之路：12、无限外推的ReRoPE.**](https://kexue.fm/archives/9708) *苏剑林(Jianlin Su).* 2023.

7. [**Transformer升级之路：14、当HWFA遇见ReRoPE.**](https://kexue.fm/archives/9731) *苏剑林(Jianlin Su).* 2023.

8. [**Transformer升级之路：15、Key归一化助力长度外推.**](https://kexue.fm/archives/9859) *苏剑林(Jianlin Su).* 2023.

9. [**Transformer升级之路：16、“复盘”长度外推技术.**](https://kexue.fm/archives/9948) *苏剑林(Jianlin Su).* 2024.

10. [**Introducing RAG 2.0.**](https://contextual.ai/introducing-rag2/) *Contextual AI Team.* 2024.

11. [**How Do Language Models put Attention Weights over Long Context?.**](https://yaofu.notion.site/How-Do-Language-Models-put-Attention-Weights-over-Long-Context-10250219d5ce42e8b465087c383a034e) *Yao Fu.* 2024.

12. [**An open-source and open-access RAG platform.**](https://openrag.notion.site/Open-RAG-c41b2a4dcdea4527a7c1cd998e763595) *Yunfan Gao.* 2024.

13. [**Many-shot Jailbreaking.**](https://www.anthropic.com/research/many-shot-jailbreaking) *Anthropic.* 2024.

14. [**Full Stack Transformer Inference Optimization Season 2: Deploying Long-Context Models.**](https://yaofu.notion.site/Full-Stack-Transformer-Inference-Optimization-Season-2-Deploying-Long-Context-Models-ee25d3a77ba14f73b8ae19147f77d5e2) *Yao Fu.* 2024.

15. [**缓存与效果的极限拉扯：从MHA、MQA、GQA到MLA.**](https://spaces.ac.cn/archives/10091) *苏剑林(Jianlin Su).* 2024.

16. [**Towards 100x Speedup: Full Stack Transformer Inference Optimization.**](https://yaofu.notion.site/Towards-100x-Speedup-Full-Stack-Transformer-Inference-Optimization-43124c3688e14cffaf2f1d6cbdf26c6c) *Yao Fu.* 2024.

17. [**2024.5 A Side-by-Side Comparison of the Long Context of Various LLMs (128k articles).**](https://zhuanlan.zhihu.com/p/699926343) *SomeoneKong.* 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SomeoneKong/llm_long_context_bench202405)](https://github.com/SomeoneKong/llm_long_context_bench202405)

18. [**2024.5 A Side-by-Side Comparison of the Long Context of Various LLMs (32k articles).**](https://zhuanlan.zhihu.com/p/700378183) *SomeoneKong.* 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SomeoneKong/llm_long_context_bench202405)](https://github.com/SomeoneKong/llm_long_context_bench202405)

19. [**Transformer升级之路：18、RoPE的底数设计原则.**](https://kexue.fm/archives/10122) *苏剑林(Jianlin Su).* 2024.

20. [**Generalizing an LLM from 8k to 1M Context using Qwen-Agent.**](https://qwenlm.github.io/zh/blog/qwen-agent-2405/) *Qwen Team.* 2024.

21. [**FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision.**](https://tridao.me/blog/2024/flash3/) *Jay Shah, Ganesh Bikshandi, Ying Zhang, Vijay Thakkar, Pradeep Ramani, Tri Dao.* 2024.

## Acknowledgements
Please contact me if I miss your names in the list, I will add you back ASAP!
