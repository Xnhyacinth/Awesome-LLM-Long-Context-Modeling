# Large Language Model Based Long Context Modeling Papers and Blogs

<!--
[![Awesome](https://camo.githubusercontent.com/64f8905651212a80869afbecbf0a9c52a5d1e70beab750dea40a994fa9a9f3c6/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](https://github.com/Xnhyacinth/Awesome-LLM-Long_Context_Modeling) [![License: MIT](https://camo.githubusercontent.com/fd551ba4b042d89480347a0e74e31af63b356b2cac1116c7b80038f41b04a581/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d677265656e2e737667)](https://opensource.org/licenses/MIT) -->
<div align="center">
 <p align="center">

<a href="https://arxiv.org/abs/2503.17407">📝 Paper</a> | <a href="#1-Survey-Papers">📄 List</a> | <a href="https://www.notion.so/Huanxuan-Liao-s-Blog-6518cf95f0d54858829b042588ff88bb">📚 Notions</a>

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

This repository includes papers and blogs about Efficient Transformers, KV Cache, Length Extrapolation, Long-Term Memory, Retrieval-Augmented Generation (RAG), Compress, Long Text Generation, Long Video, Long CoT and Evaluation for Long Context Modeling.

🔥 Must-read papers for LLM-based Long Context Modeling.

🔥⚡🔥 Thanks for all the great contributors on GitHub!

🚀🤝🚀 I have the privilege of joining [**LCLM-Horizon**] and collaborating with them on providing a very complete and comprehensive scholarly survey \([A Comprehensive Survey on Long Context Language Modeling](https://arxiv.org/abs/2503.17407)\) and repository \([A-Comprehensive-Survey-For-Long-Context-Language-Modeling](https://github.com/LCLM-Horizon/A-Comprehensive-Survey-For-Long-Context-Language-Modeling)\) dedicated to **Long Context Language Modeling**. I look forward to collaborating with them to advance research and deepen understanding in this area!

<!--Thanks to [**LCLM-Horizon**]\([A-Comprehensive-Survey-For-Long-Context-Language-Modeling](https://github.com/LCLM-Horizon/A-Comprehensive-Survey-For-Long-Context-Language-Modeling)\) for providing a very complete and comprehensive scholarly survey \([A Comprehensive Survey on Long Context Language Modeling]()\) of the field of Long Context Language Modeling. I have joined them and we will collaborate to further research and understanding in this area!-->

If you find our repository and survey useful for your research, please consider citing the following paper:

```bibtex
@article{liu2025comprehensive,
  title={A Comprehensive Survey on Long Context Language Modeling},
  author={Liu, Jiaheng and Zhu, Dawei and Bai, Zhiqi and He, Yancheng and Liao, Huanxuan and Que, Haoran and Wang, Zekun and Zhang, Chenchen and Zhang, Ge and Zhang, Jiebin and others},
  journal={arXiv preprint arXiv:2503.17407},
  year={2025}
}
```

## Contents

- [Large Language Model Based Long Context Modeling Papers and Blogs](#large-language-model-based-long-context-modeling-papers-and-blogs)
  - [Contents](#contents)
  - [📢 News](#-news)
    - [Week Papers](#week-papers)
    - [Month Papers](#month-papers)
  - [📜 Papers](#-papers)
    - [1. Survey Papers](#1-survey-papers)
    - [2. Efficient Attention](#2-efficient-attention)
      - [2.1 Sparse Attention](#21-sparse-attention)
      - [2.2 Linear Attention](#22-linear-attention)
      - [2.3 Hierarchical Attention](#23-hierarchical-attention)
      - [2.4 IO-Aware Attention](#24-io-aware-attention)
    - [3. Recurrent Transformers](#3-recurrent-transformers)
    - [4. State Space Models](#4-state-space-models)
    - [5. Length Extrapolation](#5-length-extrapolation)
    - [6. Long Term Memory](#6-long-term-memory)
    - [7. RAG and ICL](#7-rag-and-icl)
    - [8. Agent](#8-agent)
    - [9. Compress](#9-compress)
      - [9.1 Context](#91-context)
      - [9.2 Model](#92-model)
      - [9.3 Long CoT](#93-long-cot)
    - [10. Long Video and Image](#10-long-video-and-image)
    - [11. Benchmark and Evaluation](#11-benchmark-and-evaluation)
      - [11.1 LLM](#111-llm)
      - [11.2 MLLM](#112-mllm)
    - [12. Long Text Generation](#12-long-text-generation)
    - [13. Long CoT](#13-long-cot)
      - [13.1 LLM](#131-llm)
      - [13.2 MLLM](#132-mllm)
    - [14. Speculative Decoding](#14-speculative-decoding)
    - [15. Technical Report](#15-technical-report)
    - [16. Blogs](#16-blogs)
  - [Acknowledgements](#acknowledgements)
    - [Contributors](#contributors)
    - [Star History](#star-history)

## 📢 News

### Week Papers

- **[2025.06.03]**

  - Paper: [Lossless Token Sequence Compression via Meta-Tokens](https://arxiv.org/abs/2506.00307)
  - Paper: [Compress, Gather, and Recompute: REFORMing Long-Context Processing in Transformers](https://arxiv.org/abs/2506.01215)
  - Paper: [Dynamic Chunking and Selection for Reading Comprehension of Ultra-Long Context in Large Language Models](https://arxiv.org/abs/2506.00773)
  - Paper: [ExpertLongBench: Benchmarking Language Models on Expert-Level Long-Form Generation Tasks with Structured Checklists](https://arxiv.org/abs/2506.01241)

- **[2025.06.02]**

  - Paper: [AlphaOne: Reasoning Models Thinking Slow and Fast at Test Time](https://arxiv.org/abs/2505.24863)
  - Paper: [R-KV: Redundancy-aware KV Cache Compression for Training-Free Reasoning Models Acceleration](https://arxiv.org/abs/2505.24133)
  - Paper: [A*-Thought: Efficient Reasoning via Bidirectional Compression for Low-Resource Settings](https://arxiv.org/abs/2505.24550)
  - Paper: [SwingArena: Competitive Programming Arena for Long-context GitHub Issue Solving](https://arxiv.org/abs/2505.23932)
  - Paper: [ScaleLong: A Multi-Timescale Benchmark for Long Video Understanding](https://arxiv.org/abs/2505.23922)
  - Paper: [ReCalKV: Low-Rank KV Cache Compression via Head Reordering and Offline Calibration](https://arxiv.org/abs/2505.24357)

- **[2025.05.30]**

  - Paper: [VScan: Rethinking Visual Token Reduction for Efficient Large Vision-Language Models](https://arxiv.org/abs/2505.22654)
  - Paper: [LoLA: Low-Rank Linear Attention With Sparse Caching](https://arxiv.org/abs/2505.23666)
  - Paper: [KVzip: Query-Agnostic KV Cache Compression with Context Reconstruction](https://arxiv.org/abs/2505.23416)
  - Paper: [Mustafar: Promoting Unstructured Sparsity for KV Cache Pruning in LLM Inference](https://arxiv.org/abs/2505.22913)
  - Paper: [Sentinel: Attention Probing of Proxy Models for LLM Context Compression with an Understanding Perspective](https://arxiv.org/abs/2505.23277)

- **[2025.05.29]**

  - Paper: [THINK-Bench: Evaluating Thinking Efficiency and Chain-of-Thought Quality of Large Reasoning Models](https://arxiv.org/abs/2505.22113)
  - Paper: [AutoL2S: Auto Long-Short Reasoning for Efficient Large Language Models](https://arxiv.org/abs/2505.22662)
  - Paper: [Skywork Open Reasoner 1 Technical Report](https://arxiv.org/abs/2505.22312)

- **[2025.05.28]**

  - Paper: [Walk Before You Run! Concise LLM Reasoning via Reinforcement Learning](https://arxiv.org/abs/2505.21178)
  - Paper: [Self-Route: Automatic Mode Switching via Capability Estimation for Efficient Reasoning](https://arxiv.org/abs/2505.20664)
  - Paper: [SpecExtend: A Drop-in Enhancement for Speculative Decoding of Long Sequences](https://arxiv.org/abs/2505.20776)
  - Paper: [Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query](https://arxiv.org/abs/2505.20334)
  - Paper: [Hardware-Efficient Attention for Fast Decoding](https://arxiv.org/abs/2505.21487)
  - Paper: [Accelerating Diffusion Language Model Inference via Efficient KV Caching and Guided Diffusion](https://arxiv.org/abs/2505.21467)
  - Paper: [SageAttention2++: A More Efficient Implementation of SageAttention2](https://arxiv.org/abs/2505.21136)
  - Paper: [Accelerating Diffusion Language Model Inference via Efficient KV Caching and Guided Diffusion](https://arxiv.org/abs/2505.21467)

- **[2025.05.27]**

  - Paper: [PM-KVQ: Progressive Mixed-precision KV Cache Quantization for Long-CoT LLMs](https://arxiv.org/abs/2505.18610)
  - Paper: [Efficient Long CoT Reasoning in Small Language Models](https://arxiv.org/abs/2505.18440)
  - Paper: [TailorKV: A Hybrid Framework for Long-Context Inference via Tailored KV Cache Optimization](https://arxiv.org/abs/2505.19586)
  - Paper: [Does quantization affect models' performance on long-context tasks?](https://arxiv.org/abs/2505.20276)
  - Paper: [ARM: Adaptive Reasoning Model](https://arxiv.org/abs/2505.20258)
  - Paper: [Efficient Reasoning via Chain of Unconscious Thought](https://arxiv.org/abs/2505.19756)
  - Paper: [Hybrid Latent Reasoning via Reinforcement Learning](https://arxiv.org/abs/2505.18454)
  - Paper: [Think or Not? Exploring Thinking Efficiency in Large Reasoning Models via an Information-Theoretic Lens](https://arxiv.org/abs/2505.18237)
  - Paper: [System-1.5 Reasoning: Traversal in Language and Latent Spaces with Dynamic Shortcuts](https://arxiv.org/abs/2505.18962)
  - Paper: [Shifting AI Efficiency From Model-Centric to Data-Centric Compression](https://arxiv.org/abs/2505.19147)
  - Paper: [Adaptive Deep Reasoning: Triggering Deep Thinking When Needed](https://arxiv.org/abs/2505.20101)
  - Paper: [Thinking Fast and Right: Balancing Accuracy and Reasoning Length with Adaptive Rewards](https://arxiv.org/abs/2505.18298)
  - Paper: [MiniLongBench: The Low-cost Long Context Understanding Benchmark for Large Language Models](https://arxiv.org/abs/2505.19959) ACL 2025
  - Paper: [100-LongBench: Are de facto Long-Context Benchmarks Literally Evaluating Long-Context Ability?](https://arxiv.org/abs/2505.19293)
  - Paper: [Route to Reason: Adaptive Routing for LLM and Reasoning Strategy Selection](https://arxiv.org/abs/2505.19435)
  - Paper: [Thinking Fast and Right: Balancing Accuracy and Reasoning Length with Adaptive Rewards](https://arxiv.org/abs/2505.18298)

- **[2025.05.26]**

  - Paper: [Not All Tokens Are What You Need In Thinking](https://arxiv.org/abs/2505.17827)
  - Paper: [QwenLong-L1: Towards Long-Context Large Reasoning Models with Reinforcement Learning](https://arxiv.org/abs/2505.17667)
  - Paper: [TrimR: Verifier-based Training-Free Thinking Compression for Efficient Test-Time Scaling](https://arxiv.org/abs/2505.17155)
  - Paper: [L-MTP: Leap Multi-Token Prediction Beyond Adjacent Context for Large Language Models](https://arxiv.org/abs/2505.17505)
  - Paper: [Amplify Adjacent Token Differences: Enhancing Long Chain-of-Thought Reasoning with Shift-FFN](https://arxiv.org/abs/2505.17153)
  - Paper: [Longer Context, Deeper Thinking: Uncovering the Role of Long-Context Ability in Reasoning](https://arxiv.org/abs/2505.17315)
  - Paper: [QwenLong-CPRS: Towards ∞-LLMs with Dynamic Context Optimization](https://arxiv.org/abs/2505.18092)
  - Paper: [Don't Overthink it. Preferring Shorter Thinking Chains for Improved LLM Reasoning](https://arxiv.org/abs/2505.17813)
  - Paper: [SELF: Self-Extend the Context Length With Logistic Growth Function](https://arxiv.org/abs/2505.17296)
  - Paper: [Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding](https://arxiv.org/abs/2505.18079)
  - Paper: [Scale-invariant Attention](https://arxiv.org/abs/2505.17083)
  - Paper: [Zebra-Llama: Towards Extremely Efficient Hybrid Models](https://arxiv.org/abs/2505.17272)

### Month Papers

<details><summary>Month Papers</summary>

- **[2025.05.22]**

  - Paper: [dKV-Cache: The Cache for Diffusion Language Models](https://arxiv.org/abs/2505.15781)
  - Paper: [Beyond Hard and Soft: Hybrid Context Compression for Balancing Local and Global Information Retention](https://arxiv.org/abs/2505.15774)
  - Paper: [Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning](https://arxiv.org/abs/2505.15154)
  - Paper: [Soft Thinking: Unlocking the Reasoning Potential of LLMs in Continuous Concept Space](https://arxiv.org/abs/2505.15778)
  - Paper: [Too Long, Didn't Model: Decomposing LLM Long-Context Understanding With Novels](https://arxiv.org/abs/2505.14925)
  - Paper: [ThinkLess: A Training-Free Inference-Efficient Method for Reducing Reasoning Redundancy](https://arxiv.org/abs/2505.15684)
  - Paper: [When to Continue Thinking: Adaptive Thinking Mode Switching for Efficient Reasoning](https://arxiv.org/abs/2505.15400)
  - Paper: [Learn to Reason Efficiently with Adaptive Length-based Reward Shaping](https://arxiv.org/abs/2505.15612)

- **[2025.05.21]**

  - Paper: [MMLongBench: Benchmarking Long-Context Vision-Language Models Effectively and Thoroughly](https://arxiv.org/abs/2505.10610)
  - Paper: [DRP: Distilled Reasoning Pruning with Skill-aware Step Decomposition for Efficient Large Reasoning Models](https://arxiv.org/abs/2505.13975)
  - Paper: [Reasoning Path Compression: Compressing Generation Trajectories for Efficient LLM Reasoning](https://arxiv.org/abs/2505.13866)
  - Paper: [Can Pruning Improve Reasoning? Revisiting Long-CoT Compression with Capability in Mind for Better Reasoning](https://arxiv.org/abs/2505.14582)
  - Paper: [FlashThink: An Early Exit Method For Efficient Reasoning](https://arxiv.org/abs/2505.13949)
  - Paper: [Reinforcement Learning vs. Distillation: Understanding Accuracy and Capability in LLM Reasoning](https://arxiv.org/abs/2505.14216)
  - Paper: [Activation-Guided Consensus Merging for Large Language Models](https://arxiv.org/abs/2505.14009)
  - Paper: [ThinkSwitcher: When to Think Hard, When to Think Fast](https://arxiv.org/abs/2505.14183)
  - Paper: [Multi-head Temporal Latent Attention](https://arxiv.org/abs/2505.13544)
  - Paper: [Breaking the Compression Ceiling: Data-Free Pipeline for Ultra-Efficient Delta Compression](https://arxiv.org/abs/2505.13563)
  - Paper: [Video Compression Commander: Plug-and-Play Inference Acceleration for Video Large Language Models](https://arxiv.org/abs/2505.14183)

- **[2025.05.07]**

  - Paper: [Think on your Feet: Adaptive Thinking via Reinforcement Learning for Social Agents](https://arxiv.org/abs/2505.02156)

- **[2025.05.06]**

  - Paper: [RM-R1: Reward Modeling as Reasoning](https://arxiv.org/abs/2505.02387)
  - Paper: [A Survey on Inference Engines for Large Language Models: Perspectives on Optimization and Efficiency](https://arxiv.org/abs/2505.01658)
  - Paper: [Optimizing LLMs for Resource-Constrained Environments: A Survey of Model Compression Techniques](https://arxiv.org/abs/2505.02309)
  - Paper: [ReplaceMe: Network Simplification via Layer Pruning and Linear Transformations](https://arxiv.org/abs/2505.02819)

- **[2025.05.05]**

  - Paper: [Llama-Nemotron: Efficient Reasoning Models](https://arxiv.org/abs/2505.00949)

- **[2025.05.02]**

  - Paper: [Mixture of Sparse Attention: Content-Based Learnable Sparse Attention via Expert-Choice Routing](https://arxiv.org/abs/2505.00315)
  - Paper: [Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs](https://arxiv.org/abs/2505.00127)
  - Paper: [An Empirical Study on Prompt Compression for Large Language Models](https://arxiv.org/abs/2505.00019) ICLR 2025
  - Paper: [FreqKV: Frequency Domain Key-Value Compression for Efficient Context Window Extension](https://arxiv.org/abs/2505.00570)

- **[2025.05.01]**

  - Paper: [Phi-4-Mini-Reasoning: Exploring the Limits of Small Reasoning Language Models in Math](https://arxiv.org/abs/2504.21233)
  - Paper: [Phi-4-reasoning Technical Report](https://arxiv.org/abs/2504.21318)
  - Paper: [RWKV-X: A Linear Complexity Hybrid Language Model](https://arxiv.org/abs/2504.21463)
  - Paper: [AdaR1: From Long-CoT to Hybrid-CoT via Bi-Level Adaptive Reasoning Optimization](https://arxiv.org/abs/2504.21659)
  - Paper: [Efficient LLMs with AMP: Attention Heads and MLP Pruning](https://arxiv.org/abs/2504.21174)
  - Paper: [ParamΔ for Direct Weight Mixing: Post-Train Large Language Model at Zero Cost](https://arxiv.org/abs/2504.21023) ICLR 2025

 </details>

## 📜 Papers

> You can directly click on the title to jump to the corresponding PDF link location

### 1. Survey Papers

1. [**Efficient Transformers: A Survey.**](https://arxiv.org/abs/2009.06732) _Yi Tay, Mostafa Dehghani, Dara Bahri, Donald Metzler._ Arxiv 2022.

2. [**A Survey on Long Text Modeling with Transformers.**](https://arxiv.org/abs/2302.14502) _Zican Dong, Tianyi Tang, Lunyi Li, Wayne Xin Zhao._ Arxiv 2023.

3. [**Neural Natural Language Processing for Long Texts: A Survey of the State-of-the-Art.**](https://arxiv.org/abs/2305.16259) _Dimitrios Tsirmpas, Ioannis Gkionis, Ioannis Mademlis, Georgios Papadopoulos._ Arxiv 2023.

4. [**Advancing Transformer Architecture in Long-Context Large Language Models: A Comprehensive Survey.**](https://arxiv.org/abs/2311.12351) _Yunpeng Huang, Jingwei Xu, Zixu Jiang, Junyu Lai, Zenan Li, Yuan Yao, Taolue Chen, Lijuan Yang, Zhou Xin, Xiaoxing Ma._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/Strivin0311/long-llms-learning)](https://github.com/Strivin0311/long-llms-learning)

5. [**Length Extrapolation of Transformers: A Survey from the Perspective of Position Encoding.**](https://arxiv.org/abs/2312.17044) _Liang Zhao, Xiaocheng Feng, Xiachong Feng, Bing Qin, Ting Liu._ Arxiv 2024.

6. [**The What, Why, and How of Context Length Extension Techniques in Large Language Models -- A Detailed Survey.**](https://arxiv.org/abs/2401.07872) _Saurav Pawar, S.M Towhidul Islam Tonmoy, S M Mehedi Zaman, Vinija Jain, Aman Chadha, Amitava Das._ Arxiv 2024.

7. [**State Space Model for New-Generation Network Alternative to Transformers: A Survey.**](https://arxiv.org/abs/2404.09516) _Xiao Wang, Shiao Wang, Yuhe Ding, Yuehang Li, Wentao Wu, Yao Rong, Weizhe Kong, Ju Huang, Shihao Li, Haoxiang Yang, Ziwen Wang, Bo Jiang, Chenglong Li, Yaowei Wang, Yonghong Tian, Jin Tang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Event-AHU/Mamba_State_Space_Model_Paper_List)](https://github.com/Event-AHU/Mamba_State_Space_Model_Paper_List)

8. [**A Survey on Efficient Inference for Large Language Models.**](https://arxiv.org/abs/2404.14294) _Zixuan Zhou, Xuefei Ning, Ke Hong, Tianyu Fu, Jiaming Xu, Shiyao Li, Yuming Lou, Luning Wang, Zhihang Yuan, Xiuhong Li, Shengen Yan, Guohao Dai, Xiao-Ping Zhang, Yuhan Dong, Yu Wang._ Arxiv 2024.

9. [**A Survey on RAG Meets LLMs: Towards Retrieval-Augmented Large Language Models.**](https://arxiv.org/abs/2405.06211) _Yujuan Ding, Wenqi Fan, Liangbo Ning, Shijie Wang, Hengyun Li, Dawei Yin, Tat-Seng Chua, Qing Li._ Arxiv 2024.

10. [**Evaluation of Retrieval-Augmented Generation: A Survey.**](https://arxiv.org/abs/2405.07437) _Hao Yu, Aoran Gan, Kai Zhang, Shiwei Tong, Qi Liu, Zhaofeng Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/YHPeter/Awesome-RAG-Evaluation)](https://github.com/YHPeter/Awesome-RAG-Evaluation)

11. [**The CAP Principle for LLM Serving: A Survey of Long-Context Large Language Model Serving.**](https://arxiv.org/abs/2405.11299) _Pai Zeng, Zhenyu Ning, Jieru Zhao, Weihao Cui, Mengwei Xu, Liwei Guo, Xusheng Chen, Yizhou Shan._ Arxiv 2024.

12. [**Keep the Cost Down: A Review on Methods to Optimize LLM' s KV-Cache Consumption.**](https://arxiv.org/abs/2407.18003) _Luohe Shi, Hongyi Zhang, Yao Yao, Zuchao Li, Hai Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zcli-charlie/Awesome-KV-Cache)](https://github.com/zcli-charlie/Awesome-KV-Cache)

13. [**Contextual Compression in Retrieval-Augmented Generation for Large Language Models: A Survey.**](https://arxiv.org/abs/2409.13385) _Sourav Verma._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SrGrace/Contextual-Compression)](https://github.com/SrGrace/Contextual-Compression)

14. [**Retrieval Augmented Generation (RAG) and Beyond: A Comprehensive Survey on How to Make your LLMs use External Data More Wisely.**](https://arxiv.org/abs/2409.14924) _Siyun Zhao, Yuqing Yang, Zilong Wang, Zhiyuan He, Luna K. Qiu, Lili Qiu._ Arxiv 2024.

15. [**Prompt Compression for Large Language Models: A Survey.**](https://arxiv.org/abs/2410.12388) _Zongqian Li, Yinhong Liu, Yixuan Su, Nigel Collier._ Arxiv 2024.

16. [**A Survey of RWKV.**](https://arxiv.org/abs/2412.14847) _Zhiyuan Li, Tingyu Xia, Yi Chang, Yuan Wu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/MLGroupJLU/RWKV-Survey)](https://github.com/MLGroupJLU/RWKV-Survey)

17. [**A Survey on Large Language Model Acceleration based on KV Cache Management.**](https://arxiv.org/abs/2412.19442) _Haoyang Li, Yiming Li, Anxin Tian, Tianhao Tang, Zhanchao Xu, Xuejia Chen, Nicole Hu, Wei Dong, Qing Li, Lei Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TreeAI-Lab/Awesome-KV-Cache-Management)](https://github.com/TreeAI-Lab/Awesome-KV-Cache-Management)

18. [**A Survey on Mamba Architecture for Vision Applications.**](https://arxiv.org/abs/2502.07161) _Fady Ibrahim, Guangjun Liu, Guanghui Wang._ Arxiv 2025.

19. [**Thus Spake Long-Context Large Language Model.**](https://arxiv.org/abs/2502.17129) _Xiaoran Liu, Ruixiao Li, Mianqiu Huang, Zhigeng Liu, Yuerong Song, Qipeng Guo, Siyang He, Qiqi Wang, Linlin Li, Qun Liu, Yaqian Zhou, Xuanjing Huang, Xipeng Qiu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenMOSS/Thus-Spake-Long-Context-LLM)](https://github.com/OpenMOSS/Thus-Spake-Long-Context-LLM)

20. [**Towards Reasoning Era: A Survey of Long Chain-of-Thought for Reasoning Large Language Models.**](https://arxiv.org/abs/2503.09567) _Qiguang Chen, Libo Qin, Jinhao Liu, Dengyun Peng, Jiannan Guan, Peng Wang, Mengkang Hu, Yuhang Zhou, Te Gao, Wanxiang Che._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LightChen233/Awesome-Long-Chain-of-Thought-Reasoning)](https://github.com/LightChen233/Awesome-Long-Chain-of-Thought-Reasoning)

21. [**A Comprehensive Survey on Long Context Language Modeling.**](https://arxiv.org/abs/2503.17407) _Jiaheng Liu, Dawei Zhu, Zhiqi Bai, Yancheng He, Huanxuan Liao, Haoran Que, Zekun Wang, Chenchen Zhang, Ge Zhang, Jiebin Zhang, Yuanxing Zhang, Zhuo Chen, Hangyu Guo, Shilong Li, Ziqiang Liu, Yong Shan, Yifan Song, Jiayi Tian, Wenhao Wu, Zhejian Zhou, Ruijie Zhu, Junlan Feng, Yang Gao, Shizhu He, Zhoujun Li, Tianyu Liu, Fanyu Meng, Wenbo Su, Yingshui Tan, Zili Wang, Jian Yang, Wei Ye, Bo Zheng, Wangchunshu Zhou, Wenhao Huang, Sujian Li, Zhaoxiang Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LCLM-Horizon/A-Comprehensive-Survey-For-Long-Context-Language-Modeling)](https://github.com/LCLM-Horizon/A-Comprehensive-Survey-For-Long-Context-Language-Modeling)

22. [**Technologies on Effectiveness and Efficiency: A Survey of State Spaces Models.**](https://arxiv.org/abs/2503.11224) _Xingtai Lv, Youbang Sun, Kaiyan Zhang, Shang Qu, Xuekai Zhu, Yuchen Fan, Yi Wu, Ermo Hua, Xinwei Long, Ning Ding, Bowen Zhou._ Arxiv 2025.

23. [**A Survey on Knowledge-Oriented Retrieval-Augmented Generation.**](https://arxiv.org/abs/2503.10677) _Mingyue Cheng, Yucong Luo, Jie Ouyang, Qi Liu, Huijie Liu, Li Li, Shuo Yu, Bohou Zhang, Jiawei Cao, Jie Ma, Daoyu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/USTCAGI/Awesome-Papers-Retrieval-Augmented-Generation)](https://github.com/USTCAGI/Awesome-Papers-Retrieval-Augmented-Generation)

24. [**Key, Value, Compress: A Systematic Exploration of KV Cache Compression Techniques.**](https://arxiv.org/abs/2503.11816) _Neusha Javidnia, Bita Darvish Rouhani, Farinaz Koushanfar._ Arxiv 2025.

25. [**A Survey on Transformer Context Extension: Approaches and Evaluation.**](https://arxiv.org/abs/2503.13299) _Yijun Liu, Jinzheng Yu, Yang Xu, Zhongyang Li, Qingfu Zhu._ Arxiv 2025.

26. [**Stop Overthinking: A Survey on Efficient Reasoning for Large Language Models.**](https://arxiv.org/abs/2503.16419) _Yang Sui, Yu-Neng Chuang, Guanchu Wang, Jiamu Zhang, Tianyi Zhang, Jiayi Yuan, Hongyi Liu, Andrew Wen, Shaochen Zhong, Hanjie Chen, Xia Hu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Eclipsess/Awesome-Efficient-Reasoning-LLMs)](https://github.com/Eclipsess/Awesome-Efficient-Reasoning-LLMs)

27. [**A Survey on Structured State Space Sequence (S4) Models.**](https://arxiv.org/abs/2503.18970) _Shriyank Somvanshi, Md Monzurul Islam, Mahmuda Sultana Mimi, Sazzad Bin Bashar Polock, Gaurab Chhetri, Subasish Das._ Arxiv 2025.

28. [**A Survey of Efficient Reasoning for Large Reasoning Models: Language, Multimodality, and Beyond.**](https://arxiv.org/abs/2503.21614) _Xiaoye Qu, Yafu Li, Zhaochen Su, Weigao Sun, Jianhao Yan, Dongrui Liu, Ganqu Cui, Daizong Liu, Shuxian Liang, Junxian He, Peng Li, Wei Wei, Jing Shao, Chaochao Lu, Yue Zhang, Xian-Sheng Hua, Bowen Zhou, Yu Cheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/XiaoYee/Awesome_Efficient_LRM_Reasoning)](https://github.com/XiaoYee/Awesome_Efficient_LRM_Reasoning)

29. [**Harnessing the Reasoning Economy: A Survey of Efficient Reasoning for Large Language Models.**](https://arxiv.org/abs/2503.24377) _Rui Wang, Hongru Wang, Boyang Xue, Jianhui Pang, Shudong Liu, Yi Chen, Jiahao Qiu, Derek Fai Wong, Heng Ji, Kam-Fai Wong._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DevoAllen/Awesome-Reasoning-Economy-Paper)](https://github.com/DevoAllen/Awesome-Reasoning-Economy-Papers)

30. [**Efficient Inference for Large Reasoning Models: A Survey.**](https://arxiv.org/abs/2503.23077) _Yue Liu, Jiaying Wu, Yufei He, Hongcheng Gao, Hongyu Chen, Baolong Bi, Jiaheng Zhang, Zhiqi Huang, Bryan Hooi._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/yueliu1999/Awesome-Efficient-Inference-for-LRMs)](https://github.com/yueliu1999/Awesome-Efficient-Inference-for-LRMs)

31. [**A Survey on Inference Engines for Large Language Models: Perspectives on Optimization and Efficiency.**](https://arxiv.org/abs/2505.01658) _Sihyeong Park, Sungryeol Jeon, Chaelyn Lee, Seokhun Jeon, Byung-Soo Kim, Jemin Lee._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/sihyeong/Awesome-LLM-Inference-Engine)](https://github.com/sihyeong/Awesome-LLM-Inference-Engine)

32. [**Optimizing LLMs for Resource-Constrained Environments: A Survey of Model Compression Techniques.**](https://arxiv.org/abs/2505.02309) _Sanjay Surendranath Girija, Shashank Kapoor, Lakshit Arora, Dipen Pradhan, Aman Raj, Ankit Shetgaonkar._ IEEE COMPSAC 2025.

33. [**Shifting AI Efficiency From Model-Centric to Data-Centric Compression.**](https://arxiv.org/abs/2505.19147) _Xuyang Liu, Zichen Wen, Shaobo Wang, Junjie Chen, Zhishan Tao, Yubo Wang, Xiangqi Jin, Chang Zou, Yiyu Wang, Chenfei Liao, Xu Zheng, Honggang Chen, Weijia Li, Xuming Hu, Conghui He, Linfeng Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/xuyang-liu16/Awesome-Token-level-Model-Compression)](https://github.com/xuyang-liu16/Awesome-Token-level-Model-Compression)

### 2. Efficient Attention

#### 2.1 Sparse Attention

1. [**Generating Long Sequences with Sparse Transformers.**](https://arxiv.org/abs/1904.10509) _Rewon Child, Scott Gray, Alec Radford, Ilya Sutskever._ Arxiv 2019.

2. [**Blockwise selfattention for long document understanding.**](https://aclanthology.org/2020.findings-emnlp.232/) _Jiezhong Qiu, Hao Ma, Omer Levy, Wen-tau Yih, Sinong Wang, Jie Tang._ EMNLP 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/xptree/BlockBERT)](https://github.com/xptree/BlockBERT)

3. [**Longformer: The Long-Document Transformer.**](https://arxiv.org/abs/2004.05150) _Iz Beltagy, Matthew E. Peters, Arman Cohan._ Arxiv 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/allenai/longformer)](https://github.com/allenai/longformer)

4. [**ETC: Encoding Long and Structured Inputs in Transformers.**](https://aclanthology.org/2020.emnlp-main.19/) _Joshua Ainslie, Santiago Ontanon, Chris Alberti, Vaclav Cvicek, Zachary Fisher, Philip Pham, Anirudh Ravula, Sumit Sanghai, Qifan Wang, Li Yang._ EMNLP 2020.

5. [**Big Bird: Transformers for Longer Sequences.**](https://papers.nips.cc/paper/2020/hash/c8512d142a2d849725f31a9a7a361ab9-Abstract.html) _Manzil Zaheer, Guru Guruganesh, Kumar Avinava Dubey, Joshua Ainslie, Chris Alberti, Santiago Ontanon, Philip Pham, Anirudh Ravula, Qifan Wang, Li Yang, Amr Ahmed._ NeurIPS 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/bigbird)](https://github.com/google-research/bigbird)

6. [**Reformer: The efficient transformer.**](https://arxiv.org/abs/2001.04451) _Nikita Kitaev, Łukasz Kaiser, Anselm Levskaya._ ICLR 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/reformer-pytorch)](https://github.com/lucidrains/reformer-pytorch)

7. [**Sparse Sinkhorn Attention.**](https://arxiv.org/abs/2002.11296) _Yi Tay, Dara Bahri, Liu Yang, Donald Metzler, Da-Cheng Juan._ ICML 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/sinkhorn-transformer)](https://github.com/lucidrains/sinkhorn-transformer)

8. [**Sparse and continuous attention mechanisms.**](https://arxiv.org/abs/2006.07214) _André F. T. Martins, António Farinhas, Marcos Treviso, Vlad Niculae, Pedro M. Q. Aguiar, Mário A. T. Figueiredo._ NIPS 2020.

9. [**Efficient Content-Based Sparse Attention with Routing Transformers.**](https://aclanthology.org/2021.tacl-1.4/) _Aurko Roy, Mohammad Saffar, Ashish Vaswani, David Grangier._ TACL 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/routing-transformer)](https://github.com/lucidrains/routing-transformer)

10. [**LongT5: Efficient text-to-text transformer for long sequences.**](https://aclanthology.org/2022.findings-naacl.55/) _Mandy Guo, Joshua Ainslie, David Uthus, Santiago Ontanon, Jianmo Ni, Yun-Hsuan Sung, Yinfei Yang._ NAACL 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/longt5)](https://github.com/google-research/longt5)

11. [**Efficient Long-Text Understanding with Short-Text Models.**](https://aclanthology.org/2023.tacl-1.17/) _Maor Ivgi, Uri Shaham, Jonathan Berant._ TACL 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/Mivg/SLED)](https://github.com/Mivg/SLED)

12. [**Parallel Context Windows for Large Language Models.**](https://aclanthology.org/2023.acl-long.352/) _Nir Ratner, Yoav Levine, Yonatan Belinkov, Ori Ram, Inbal Magar, Omri Abend, Ehud Karpas, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham._ ACL 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/AI21Labs/Parallel-Context-Windows)](https://github.com/AI21Labs/Parallel-Context-Windows)

13. [**Unlimiformer: Long-Range Transformers with Unlimited Length Input.**](https://arxiv.org/abs/2305.01625) _Amanda Bertsch, Uri Alon, Graham Neubig, Matthew R. Gormley._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/abertsch72/unlimiformer)](https://github.com/abertsch72/unlimiformer)

14. [**Landmark Attention: Random-Access Infinite Context Length for Transformers.**](https://arxiv.org/abs/2305.16300) _Amirkeivan Mohtashami, Martin Jaggi_ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/epfml/landmark-attention)](https://github.com/epfml/landmark-attention)

15. [**LONGNET: Scaling Transformers to 1,000,000,000 Tokens.**](https://arxiv.org/abs/2307.02486) _Jiayu Ding, Shuming Ma, Li Dong, Xingxing Zhang, Shaohan Huang, Wenhui Wang, Nanning Zheng, Furu Wei._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/LongNet)](https://github.com/kyegomez/LongNet)

16. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) _Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

17. [**Blockwise Parallel Transformer for Long Context Large Models.**](https://arxiv.org/abs/2305.19370) _Hao Liu, Pieter Abbeel._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/Blockwise-Parallel-Transformer)](https://github.com/lhao499/llm_large_context)

18. [**MEGABYTE: Predicting Million-byte Sequences with Multiscale Transformers.**](https://arxiv.org/abs/2305.07185) _Lili Yu, Dániel Simig, Colin Flaherty, Armen Aghajanyan, Luke Zettlemoyer, Mike Lewis._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/MEGABYTE-pytorch)](https://github.com/lucidrains/MEGABYTE-pytorch)

19. [**Dynamic Context Pruning for Efficient and Interpretable Autoregressive Transformers.**](https://arxiv.org/abs/2305.15805) _Sotiris Anagnostidis, Dario Pavllo, Luca Biggio, Lorenzo Noci, Aurelien Lucchi, Thomas Hofmann._ Arxiv 2023.

20. [**Long-range Language Modeling with Self-retrieval.**](https://arxiv.org/abs/2306.13421) _Ohad Rubin, Jonathan Berant._ Arxiv 2023.

21. [**Max-Margin Token Selection in Attention Mechanism.**](https://arxiv.org/abs/2306.13596) _Davoud Ataee Tarzanagh, Yingcong Li, Xuechen Zhang, Samet Oymak._ Arxiv 2023.

22. [**Chunk, Align, Select: A Simple Long-sequence Processing Method for Transformers.**](https://arxiv.org/abs/2308.13191) _Jiawen Xie, Pengyu Cheng, Xiao Liang, Yong Dai, Nan Du._ Arxiv 2023.

23. [**Sparse Token Transformer with Attention Back Tracking.**](https://openreview.net/forum?id=VV0hSE8AxCw) _Heejun Lee, Minki Kang, Youngwan Lee, Sung Ju Hwang._ ICLR 2023.

24. [**Empower Your Model with Longer and Better Context Comprehension.**](https://arxiv.org/pdf/2307.13365v2.pdf) _YiFei Gao, Lei Wang, Jun Fang, Longhua Hu, Jun Cheng._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/yileijin/attention-transition)](https://github.com/yileijin/attention-transition)

25. [**Ring Attention with Blockwise Transformers for Near-Infinite Context.**](https://arxiv.org/pdf/2310.01889v1.pdf) _Hao Liu, Matei Zaharia, Pieter Abbeel._ Arxiv 2023.

26. [**Efficient Streaming Language Models with Attention Sinks.**](https://arxiv.org/pdf/2309.17453.pdf) _Guangxuan Xiao, Yuandong Tian, Beidi Chen, Song Han, Mike Lewis._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/streaming-llm)](https://github.com/mit-han-lab/streaming-llm)

27. [**HyperAttention: Long-context Attention in Near-Linear Time.**](https://arxiv.org/abs/2310.05869) _Insu Han, Rajesh Jayaram, Amin Karbasi, Vahab Mirrokni, David P. Woodruff, Amir Zandieh._ Arxiv 2023.

28. [**Fovea Transformer: Efficient Long-Context Modeling with Structured Fine-to-Coarse Attention.**](https://arxiv.org/pdf/2311.07102v1.pdf) _Ziwei He,Jian Yuan,Le Zhou,Jingwen Leng,Bo Jiang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/ZiweiHe/Fovea-Transformer)](https://github.com/ZiweiHe/Fovea-Transformer)

29. [**ChunkAttention: Efficient Self-Attention with Prefix-Aware KV Cache and Two-Phase Partition.**](https://arxiv.org/abs/2402.15220) _Lu Ye, Ze Tao, Yong Huang, Yang Li._ Arxiv 2024.

30. [**Training-Free Long-Context Scaling of Large Language Models.**](https://arxiv.org/abs/2402.17463) _Chenxin An, Fei Huang, Jun Zhang, Shansan Gong, Xipeng Qiu, Chang Zhou, Lingpeng Kong._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HKUNLP/ChunkLlama)](https://github.com/HKUNLP/ChunkLlama)

31. [**LongHeads: Multi-Head Attention is Secretly a Long Context Processor.**](https://arxiv.org/abs/2402.10685) _Yi Lu, Xin Zhou, Wei He, Jun Zhao, Tao Ji, Tao Gui, Qi Zhang, Xuanjing Huang._ Arxiv 2024.

32. [**Zebra: Extending Context Window with Layerwise Grouped Local-Global Attention.**](https://arxiv.org/abs/2312.08618) _Kaiqiang Song, Xiaoyang Wang, Sangwoo Cho, Xiaoman Pan, Dong Yu._ Arxiv 2023.

33. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) _Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/SnapKV)](https://github.com/FasterDecoding/SnapKV)

34. [**Sequence can Secretly Tell You What to Discard.**](https://arxiv.org/abs/2404.15949) _Jincheng Dai, Zhuowei Huang, Haiyun Jiang, Chen Chen, Deng Cai, Wei Bi, Shuming Shi._ Arxiv 2024.

35. [**SinkLoRA: Enhanced Efficiency and Chat Capabilities for Long-Context Large Language Models.**](https://arxiv.org/abs/2406.05678) _Hengyu Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Dexter-GT-86/SinkLoRA)](https://github.com/Dexter-GT-86/SinkLoRA)

36. [**HiP Attention: Sparse Sub-Quadratic Attention with Hierarchical Attention Pruning.**](https://arxiv.org/abs/2406.09827) _Heejun Lee, Geon Park, Youngwan Lee, Jina Kim, Wonyoung Jeong, Myeongjae Jeon, Sung Ju Hwang._ Arxiv 2024.

37. [**Taking a Deep Breath: Enhancing Language Modeling of Large Language Models with Sentinel Tokens.**](https://arxiv.org/abs/2406.10985) _Weiyao Luo, Suncong Zheng, Heming Xia, Weikang Wang, Yan Lei, Tianyu Liu, Shuang Chen, Zhifang Sui._ Arxiv 2024.

38. [**MoA: Mixture of Sparse Attention for Automatic Large Language Model Compression.**](https://arxiv.org/abs/2406.14909) _Weiyao Luo, Suncong Zheng, Heming Xia, Weikang Wang, Yan Lei, Tianyu Liu, Shuang Chen, Zhifang Sui._ Arxiv 2024.

39. [**Sparser is Faster and Less is More: Efficient Sparse Attention for Long-Range Transformers.**](https://arxiv.org/abs/2406.16747) _Chao Lou, Zixia Jia, Zilong Zheng, Kewei Tu._ Arxiv 2024.

40. [**Near-Lossless Acceleration of Long Context LLM Inference with Adaptive Structured Sparse Attention.**](https://arxiv.org/abs/2406.15486) _Qianchao Zhu, Jiangfei Duan, Chang Chen, Siran Liu, Xiuhong Li, Guanyu Feng, Xin Lv, Huanqi Cao, Xiao Chuanfu, Xingcheng Zhang, Dahua Lin, Chao Yang._ Arxiv 2024.

41. [**Neurocache: Efficient Vector Retrieval for Long-range Language Modeling.**](https://arxiv.org/abs/2407.02486) _Ali Safaya, Deniz Yuret._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alisafaya/neurocache)](https://github.com/alisafaya/neurocache)

42. [**Weighted Grouped Query Attention in Transformers.**](https://arxiv.org/abs/2407.10855) _Sai Sena Chinnakonduru, Astarag Mohapatra._ Arxiv 2024.

43. [**Selective Attention Improves Transformer.**](https://arxiv.org/abs/2410.02703) _Yaniv Leviathan, Matan Kalman, Yossi Matias._ Arxiv 2024.

44. [**TidalDecode: Fast and Accurate LLM Decoding with Position Persistent Sparse Attention.**](https://arxiv.org/abs/2410.05076) _Lijie Yang, Zhihao Zhang, Zhuofu Chen, Zikun Li, Zhihao Jia._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DerrickYLJ/TidalDecode)](https://github.com/DerrickYLJ/TidalDecode)

45. [**FltLM: An Intergrated Long-Context Large Language Model for Effective Context Filtering and Understanding.**](https://arxiv.org/abs/2410.06886) _Jingyang Deng, Zhengyang Shen, Boyang Wang, Lixin Su, Suqi Cheng, Ying Nie, Junfeng Wang, Dawei Yin, Jinwen Ma._ Arxiv 2024.

46. [**Beyond Linear Approximations: A Novel Pruning Approach for Attention Matrix.**](https://arxiv.org/abs/2410.11261) _Yingyu Liang, Jiangxuan Long, Zhenmei Shi, Zhao Song, Yufa Zhou._ Arxiv 2024.

47. [**Extra Global Attention Designation Using Keyword Detection in Sparse Transformer Architectures.**](https://arxiv.org/abs/2410.08971) _Evan Lucas, Dylan Kangas, Timothy C Havens._ Arxiv 2024.

48. [**SeerAttention: Learning Intrinsic Sparse Attention in Your LLMs.**](https://arxiv.org/abs/2410.13276) _Yizhao Gao, Zhichen Zeng, Dayou Du, Shijie Cao, Hayden Kwok-Hay So, Ting Cao, Fan Yang, Mao Yang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/SeerAttention)](https://github.com/microsoft/SeerAttention)

49. [**Selective Attention: Enhancing Transformer through Principled Context Control.**](https://arxiv.org/abs/2411.12892) _Xuechen Zhang, Xiangyu Chang, Mingchen Li, Amit Roy-Chowdhury, Jiasi Chen, Samet Oymak._ NeurIPS 2024.

50. [**Core Context Aware Attention for Long Context Language Modeling.**](https://arxiv.org/abs/2412.12465) _Yaofo Chen, Zeng You, Shuhai Zhang, Haokun Li, Yirui Li, Yaowei Wang, Mingkui Tan._ Arxiv 2024.

51. [**Inference-time sparse attention with asymmetric indexing.**](https://arxiv.org/abs/2502.08246) _Pierre-Emmanuel Mazaré, Gergely Szilvasy, Maria Lomeli, Francisco Massa, Naila Murray, Hervé Jégou, Matthijs Douze._ Arxiv 2025.

52. [**Top-Theta Attention: Sparsifying Transformers by Compensated Thresholding.**](https://arxiv.org/abs/2502.08363) _Konstantin Berestizshevsky, Renzo Andri, Lukas Cavigelli._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/kostyanoob/top-theta-attention)](https://github.com/kostyanoob/top-theta-attention)

53. [**MoBA: Mixture of Block Attention for Long-Context LLMs.**](https://arxiv.org/abs/2502.13189) _Enzhe Lu, Zhejun Jiang, Jingyuan Liu, Yulun Du, Tao Jiang, Chao Hong, Shaowei Liu, Weiran He, Enming Yuan, Yuzhi Wang, Zhiqi Huang, Huan Yuan, Suting Xu, Xinran Xu, Guokun Lai, Yanru Chen, Huabin Zheng, Junjie Yan, Jianlin Su, Yuxin Wu, Neo Y. Zhang, Zhilin Yang, Xinyu Zhou, Mingxing Zhang, Jiezhong Qiu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MoonshotAI/MoBA)](https://github.com/MoonshotAI/MoBA)

54. [**Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention.**](https://arxiv.org/abs/2502.11089) _Jingyang Yuan, Huazuo Gao, Damai Dai, Junyu Luo, Liang Zhao, Zhengyan Zhang, Zhenda Xie, Y. X. Wei, Lean Wang, Zhiping Xiao, Yuqing Wang, Chong Ruan, Ming Zhang, Wenfeng Liang, Wangding Zeng._ Arxiv 2025.

55. [**Neural Attention Search.**](https://arxiv.org/abs/2502.13251) _Difan Deng, Marius Lindauer._ Arxiv 2025.

56. [**PowerAttention: Exponentially Scaling of Receptive Fields for Effective Sparse Attention.**](https://arxiv.org/abs/2503.03588) _Lida Chen, Dong Xu, Chenxin An, Xintao Wang, Yikai Zhang, Jiangjie Chen, Zujie Liang, Feng Wei, Jiaqing Liang, Yanghua Xiao, Wei Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/w568w/PowerAttention)](https://github.com/w568w/PowerAttention)

57. [**Cost-Optimal Grouped-Query Attention for Long-Context LLMs.**](https://arxiv.org/abs/2503.09579) _Yingfa Chen, Yutong Wu, Xu Han, Zhiyuan Liu, Maosong Sun._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/THUNLP/cost-optimal-gqa)](https://github.com/THUNLP/cost-optimal-gqa)

58. [**X-EcoMLA: Upcycling Pre-Trained Attention into MLA for Efficient and Extreme KV Compression.**](https://arxiv.org/abs/2503.11132) _Guihong Li, Mehdi Rezagholizadeh, Mingyu Yang, Vikram Appia, Emad Barsoum._ Arxiv 2025.

59. [**OmniKV: Dynamic Context Selection for Efficient Long-Context LLMs**](https://openreview.net/forum?id=ulCAPXYXfa) _Jitai Hao, Yuke Zhu, Tian Wang, Jun Yu, Xin Xin, Bo Zheng, Zhaochun Ren, Sheng Guo._ ICLR 2025.

60. [**XAttention: Block Sparse Attention with Antidiagonal Scoring.**](https://arxiv.org/abs/2503.16428) _Ruyi Xu, Guangxuan Xiao, Haofeng Huang, Junxian Guo, Song Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/x-attention)](https://github.com/mit-han-lab/x-attention)

61. [**The Sparse Frontier: Sparse Attention Trade-offs in Transformer LLMs.**](https://arxiv.org/pdf/2504.17768) _Piotr Nawrot, Robert Li, Renjie Huang, Sebastian Ruder, Kelly Marchisio, Edoardo M. Ponti._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/PiotrNawrot/sparse-frontier)](https://github.com/PiotrNawrot/sparse-frontier)

62. [**Mixture of Sparse Attention: Content-Based Learnable Sparse Attention via Expert-Choice Routing.**](https://arxiv.org/abs/2505.00315) _Piotr Piękos, Róbert Csordás, Jürgen Schmidhuber._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/piotrpiekos/MoSA)](https://github.com/piotrpiekos/MoSA)

63. [**Multi-head Temporal Latent Attention.**](https://arxiv.org/abs/2505.13544) _Keqi Deng, Philip C. Woodland._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/D-Keqi/mtla)](https://github.com/D-Keqi/mtla)

64. [**Scale-invariant Attention.**](https://arxiv.org/abs/2505.17083) _Ben Anson, Xi Wang, Laurence Aitchison._ Arxiv 2025.

65. [**SageAttention2++: A More Efficient Implementation of SageAttention2.**](https://arxiv.org/abs/2505.21136) _Jintao Zhang, Xiaoming Xu, Jia Wei, Haofeng Huang, Pengle Zhang, Chendong Xiang, Jun Zhu, Jianfei Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/thu-ml/SageAttention)](https://github.com/thu-ml/SageAttention)

#### 2.2 Linear Attention

1. [**Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention.**](https://arxiv.org/abs/2006.16236) _Angelos Katharopoulos, Apoorv Vyas, Nikolaos Pappas, François Fleuret._ ICML 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/idiap/fast-transformers)](https://github.com/idiap/fast-transformers)

2. [**Learning Fast Algorithms for Linear Transforms Using Butterfly Factorizations.**](https://arxiv.org/abs/1903.05895) _Tri Dao, Albert Gu, Matthew Eichhorn, Atri Rudra, Christopher Ré._ Arxiv 2019. [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/butterfly)](https://github.com/HazyResearch/butterfly)

3. [**Masked language modeling for proteins via linearly scalable long-context transformers.**](https://arxiv.org/abs/2006.03555) _Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, David Belanger, Lucy Colwell, Adrian Weller._ Arxiv 2020.

4. [**Rethinking attention with performers.**](https://arxiv.org/abs/2009.14794) _Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, Afroz Mohiuddin, Lukasz Kaiser, David Belanger, Lucy Colwell, Adrian Weller._ Arxiv 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/performer-pytorch)](https://github.com/lucidrains/performer-pytorch)

5. [**Linformer: Self-attention with linear complexity.**](https://arxiv.org/abs/2006.04768) _Sinong Wang, Belinda Z. Li, Madian Khabsa, Han Fang, Hao Ma._ Arxiv 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/linear-attention-transformer)](https://github.com/lucidrains/linear-attention-transformer)

6. [**Random Feature Attention.**](https://arxiv.org/abs/2103.02143) _Hao Peng, Nikolaos Pappas, Dani Yogatama, Roy Schwartz, Noah A. Smith, Lingpeng Kong._ Arxiv 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/Noahs-ARK/RFA)](https://github.com/Noahs-ARK/RFA)

7. [**Luna: Linear unified nested attention.**](https://arxiv.org/abs/2106.01540) _Xuezhe Ma, Xiang Kong, Sinong Wang, Chunting Zhou, Jonathan May, Hao Ma, Luke Zettlemoyer._ Arxiv 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/sooftware/luna-transformer)](https://github.com/sooftware/luna-transformer)

8. [**Fnet: Mixing tokens with fourier transforms.**](https://arxiv.org/abs/2105.03824) _James Lee-Thorp, Joshua Ainslie, Ilya Eckstein, Santiago Ontanon._ Arxiv 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/jaketae/fnet)](https://github.com/jaketae/fnet)

9. [**Gated Linear Attention Transformers with Hardware-Efficient Training.**](https://arxiv.org/abs/2312.06635v2) _Songlin Yang, Bailin Wang, Yikang Shen, Rameswar Panda, Yoon Kim._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/berlino/gated_linear_attention)](https://github.com/berlino/gated_linear_attention)

10. [**Latent Attention for Linear Time Transformers.**](https://arxiv.org/abs/2402.17512) _Rares Dolga, Marius Cobzarenco, David Barber._ Arxiv 2024.

11. [**Simple linear attention language models balance the recall-throughput tradeoff.**](https://arxiv.org/abs/2402.18668) _Simran Arora, Sabri Eyuboglu, Michael Zhang, Aman Timalsina, Silas Alberti, Dylan Zinsley, James Zou, Atri Rudra, Christopher Ré._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/based)](https://github.com/HazyResearch/based)

12. [**Linear Attention Sequence Parallelism.**](https://arxiv.org/abs/2404.02882) _Weigao Sun, Zhen Qin, Dong Li, Xuyang Shen, Yu Qiao, Yiran Zhong._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/LASP)](https://github.com/OpenNLPLab/LASP)

13. [**Softmax Attention with Constant Cost per Token.**](https://arxiv.org/abs/2404.05843) _Franz A. Heinsen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/glassroom/heinsen_attention](https://github.com/glassroom/heinsen_attention)

14. [**Megalodon: Efficient LLM Pretraining and Inference with Unlimited Context Length.**](https://arxiv.org/abs/2404.08801) _Xuezhe Ma, Xiaomeng Yang, Wenhan Xiong, Beidi Chen, Lili Yu, Hao Zhang, Jonathan May, Luke Zettlemoyer, Omer Levy, Chunting Zhou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/XuezheMax/megalodon](https://github.com/XuezheMax/megalodon)

15. [**Various Lengths, Constant Speed: Efficient Language Modeling with Lightning Attention.**](https://arxiv.org/abs/2405.17381) _Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong._ Arxiv 2024.

16. [**Unlocking the Secrets of Linear Complexity Sequence Model from A Unified Perspective.**](https://arxiv.org/abs/2405.17383) _Zhen Qin, Xuyang Shen, Weigao Sun, Dong Li, Stan Birchfield, Richard Hartley, Yiran Zhong._ Arxiv 2024.

17. [**Attention as an RNN.**](https://arxiv.org/abs/2405.13956) _Leo Feng, Frederick Tung, Hossein Hajimirsadeghi, Mohamed Osama Ahmed, Yoshua Bengio, Greg Mori._ Arxiv 2024.

18. [**You Only Scan Once: Efficient Multi-dimension Sequential Modeling with LightNet.**](https://arxiv.org/abs/2405.21022) _Zhen Qin, Yuxin Mao, Xuyang Shen, Dong Li, Jing Zhang, Yuchao Dai, Yiran Zhong._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/LightNet](https://github.com/OpenNLPLab/LightNet)

19. [**When Linear Attention Meets Autoregressive Decoding: Towards More Effective and Efficient Linearized Large Language Models.**](https://arxiv.org/abs/2406.07368) _Haoran You, Yichao Fu, Zheng Wang, Amir Yazdanbakhsh, Yingyan (Celine)Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/GATECH-EIC/Linearized-LLM](https://github.com/GATECH-EIC/Linearized-LLM)

20. [**Learning to (Learn at Test Time): RNNs with Expressive Hidden States.**](https://arxiv.org/abs/2407.04620) _Yu Sun, Xinhao Li, Karan Dalal, Jiarui Xu, Arjun Vikram, Genghan Zhang, Yann Dubois, Xinlei Chen, Xiaolong Wang, Sanmi Koyejo, Tatsunori Hashimoto, Carlos Guestrin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/test-time-training/ttt-lm-pytorch](https://github.com/test-time-training/ttt-lm-pytorch)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/test-time-training/ttt-lm-jax](https://github.com/test-time-training/ttt-lm-jax)

21. [**Gated Slot Attention for Efficient Linear-Time Sequence Modeling.**](https://arxiv.org/abs/2409.07146) _Yu Zhang, Songlin Yang, Ruijie Zhu, Yue Zhang, Leyang Cui, Yiqiao Wang, Bolun Wang, Freda Shi, Bailin Wang, Wei Bi, Peng Zhou, Guohong Fu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sustcsonglin/flash-linear-attention](https://github.com/sustcsonglin/flash-linear-attention)

22. [**LASP-2: Rethinking Sequence Parallelism for Linear Attention and Its Hybrid.**](https://arxiv.org/abs/2502.07563) _Weigao Sun, Disen Lan, Yiran Zhong, Xiaoye Qu, Yu Cheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenSparseLLMs/Linear-MoE](https://github.com/OpenSparseLLMs/Linear-MoE)

23. [**MoM: Linear Sequence Modeling with Mixture-of-Memories.**](https://arxiv.org/abs/2502.13685) _Jusen Du, Weigao Sun, Disen Lan, Jiaxi Hu, Yu Cheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenSparseLLMs/MoM](https://github.com/OpenSparseLLMs/MoM)

24. [**EDiT: Efficient Diffusion Transformers with Linear Compressed Attention.**](https://arxiv.org/abs/2503.16726) _Philipp Becker, Abhinav Mehrotra, Ruchika Chavhan, Malcolm Chadwick, Luca Morreale, Mehdi Noroozi, Alberto Gil Ramos, Sourav Bhattacharya._ Arxiv 2025.

25. [**LoLA: Low-Rank Linear Attention With Sparse Caching.**](https://arxiv.org/abs/2505.23666) _Luke McDermott, Robert W. Heath Jr., Rahul Parhi._ Arxiv 2025.

#### 2.3 Hierarchical Attention

1. [**Neural Legal Judgment Prediction in English.**](https://aclanthology.org/P19-1424.pdf) _Ilias Chalkidis, Ion Androutsopoulos, Nikolaos Aletras._ ACL 2019. [![GitHub Repo stars](https://img.shields.io/github/stars/PolarisRisingWar/pytorch_ljp)](https://github.com/PolarisRisingWar/pytorch_ljp)

2. [**Hierarchical Neural Network Approaches for Long Document Classification.**](https://arxiv.org/abs/2201.06774) _Snehal Khandve, Vedangi Wagh, Apurva Wani, Isha Joshi, Raviraj Joshi._ ICML 2022.

3. [**Hi-transformer: Hierarchical interactive transformer for efficient and effective long document modeling.**](https://arxiv.org/abs/2106.01040) _Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang._ ACL-IJCNLP 2021

4. [**Erniesparse: Learning hierarchical efficient transformer through regularized self-attention.**](https://arxiv.org/abs/2203.12276) _Yang Liu, Jiaxiang Liu, Li Chen, Yuxiang Lu, Shikun Feng, Zhida Feng, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang._ Arxiv 2022.

#### 2.4 IO-Aware Attention

1. [**Self-attention Does Not Need O(n^2) Memory.**](https://arxiv.org/abs/2112.05682) _Markus N. Rabe, Charles Staats._ Arxiv 2021.

2. [**Faster Causal Attention Over Large Sequences Through Sparse Flash Attention.**](https://arxiv.org/abs/2306.01160) _Matteo Pagliardini, Daniele Paliotta, Martin Jaggi, François Fleuret._ Arxiv 2023.

3. [**FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness.**](https://arxiv.org/abs/2205.14135) _Tri Dao, Daniel Y. Fu, Stefano Ermon, Atri Rudra, Christopher Ré._ Arxiv 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/Dao-AILab/flash-attention)](https://github.com/Dao-AILab/flash-attention)

4. [**FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning.**](https://arxiv.org/abs/2307.08691) _Tri Dao._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/Dao-AILab/flash-attention)](https://github.com/Dao-AILab/flash-attention)

5. [**Efficient Memory Management for Large Language Model Serving with PagedAttention.**](https://arxiv.org/abs/2309.06180) _Woosuk Kwon, Zhuohan Li, Siyuan Zhuang, Ying Sheng, Lianmin Zheng, Cody Hao Yu, Joseph E. Gonzalez, Hao Zhang, Ion Stoica._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/vllm-project/vllm)](https://github.com/vllm-project/vllm)

6. [**TransNormerLLM: A Faster and Better Large Language Model with Improved TransNormer.**](https://arxiv.org/abs/2307.14995) _Zhen Qin, Dong Li, Weigao Sun, Weixuan Sun, Xuyang Shen, Xiaodong Han, Yunshen Wei, Baohong Lv, Xiao Luo, Yu Qiao, Yiran Zhong._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/TransnormerLLM)](https://github.com/OpenNLPLab/TransnormerLLM)

7. [**Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models.**](https://arxiv.org/abs/2401.04695) _Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention)](https://github.com/OpenNLPLab/lightning-attention)

8. [**ChunkAttention: Efficient Self-Attention with Prefix-Aware KV Cache and Two-Phase Partition.**](https://arxiv.org/abs/2402.15220) _Lu Ye, Ze Tao, Yong Huang, Yang Li._ Arxiv 2024.

9. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) _Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/SnapKV)](https://github.com/FasterDecoding/SnapKV)

10. [**Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs.**](https://openreview.net/forum?id=uNrFpDPMyo) _Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao._ ICLR 2024 Oral.

11. [**Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient Generative Inference.**](https://arxiv.org/abs/2403.09054) _Muhammad Adnan, Akhil Arunkumar, Gaurav Jain, Prashant J. Nair, Ilya Soloveychik, Purushotham Kamath._ Arxiv 2024.

12. [**Efficient LLM Inference with Kcache.**](https://arxiv.org/abs/2404.18057) _Qiaozhi He, Zhihua Wu._ Arxiv 2024.

13. [**You Only Cache Once: Decoder-Decoder Architectures for Language Models.**](https://arxiv.org/abs/2405.05254) _Yutao Sun, Li Dong, Yi Zhu, Shaohan Huang, Wenhui Wang, Shuming Ma, Quanlu Zhang, Jianyong Wang, Furu Wei._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/unilm)](https://github.com/microsoft/unilm/tree/master/YOCO)

14. [**Fast Transformer Decoding: One Write-Head is All You Need.**](https://arxiv.org/abs/1911.02150) _Noam Shazeer._ Arxiv 2019.

15. [**GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints.**](https://arxiv.org/abs/2305.13245) _Joshua Ainslie, James Lee-Thorp, Michiel de Jong, Yury Zemlyanskiy, Federico Lebrón, Sumit Sanghai._ Arxiv 2023.

16. [**DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model.**](https://arxiv.org/abs/2405.04434) _DeepSeek-AI._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2)](https://github.com/deepseek-ai/DeepSeek-V2)

17. [**Layer-Condensed KV Cache for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2405.10637) _Haoyi Wu, Kewei Tu._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

18. [**Reducing Transformer Key-Value Cache Size with Cross-Layer Attention.**](https://arxiv.org/abs/2405.12981) _William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly._ Arxiv 2024.

19. [**PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference.**](https://arxiv.org/abs/2405.12532) _William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mutonix/pyramidinfer)](https://github.com/mutonix/pyramidinfer)

20. [**Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression.**](https://arxiv.org/abs/2405.12591) _Peiyu Liu, Ze-Feng Gao, Wayne Xin Zhao, Yipeng Ma, Tao Wang, Ji-Rong Wen._ Arxiv 2024.

21. [**MiniCache: KV Cache Compression in Depth Dimension for Large Language Models.**](https://arxiv.org/abs/2405.14366) _Akide Liu, Jing Liu, Zizheng Pan, Yefei He, Gholamreza Haffari, Bohan Zhuang._ NeurIPS 2024.

22. [**PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling.**](https://arxiv.org/abs/2406.02069) _Zefan Cai., Yichi Zhang, Bofei Gao, Tianyu Liu, Keming Lu, Wayne Xiong, Yue Dong, Baobao Chang, Junjie Hu, Wen Xiao._ Arxiv 2024.

23. [**Effectively Compress KV Heads for LLM.**](https://arxiv.org/abs/2406.07056) _Hao Yu, Zelan Yang, Shen Li, Yong Li, Jianxin Wu._ Arxiv 2024.

24. [**A Simple and Effective L2 Norm-Based Strategy for KV Cache Compression.**](https://arxiv.org/abs/2406.11430) _Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini._ Arxiv 2024.

25. [**Quest: Query-Aware Sparsity for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2406.10774) _Jiaming Tang, Yilong Zhao, Kan Zhu, Guangxuan Xiao, Baris Kasikci, Song Han._ ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/Quest)](https://github.com/mit-han-lab/Quest)

26. [**Attention Score is not All You Need for Token Importance Indicator in KV Cache Reduction: Value Also Matters.**](https://arxiv.org/abs/2406.12335) _Zhiyu Guo, Hidetaka Kamigaito, Taro Watanabe._ Arxiv 2024.

27. [**CItruS: Chunked Instruction-aware State Eviction for Long Sequence Modeling.**](https://arxiv.org/abs/2406.12018) _Yu Bai, Xiyuan Zou, Heyan Huang, Sanxing Chen, Marc-Antoine Rondeau, Yang Gao, Jackie Chi Kit Cheung._ Arxiv 2024.

28. [**D2O: Dynamic Discriminative Operations for Efficient Generative Inference of Large Language Models.**](https://arxiv.org/abs/2406.13035) _Zhongwei Wan, Xinjian Wu, Yu Zhang, Yi Xin, Chaofan Tao, Zhihong Zhu, Xin Wang, Siqi Luo, Jing Xiong, Mi Zhang._ Arxiv 2024.

29. [**MoA: Mixture of Sparse Attention for Automatic Large Language Model Compression.**](https://arxiv.org/abs/2406.14909) _Weiyao Luo, Suncong Zheng, Heming Xia, Weikang Wang, Yan Lei, Tianyu Liu, Shuang Chen, Zhifang Sui._ Arxiv 2024.

30. [**LOOK-M: Look-Once Optimization in KV Cache for Efficient Multimodal Long-Context Inference.**](https://arxiv.org/abs/2406.18139) _Zhongwei Wan, Ziang Wu, Che Liu, Jinfa Huang, Zhihong Zhu, Peng Jin, Longyue Wang, Li Yuan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SUSTechBruce/LOOK-M)](https://github.com/SUSTechBruce/LOOK-M)

31. [**Training-Free Exponential Extension of Sliding Window Context with Cascading KV Cache.**](https://arxiv.org/abs/2406.17808) _Jeffrey Willette, Heejun Lee, Youngwan Lee, Myeongjae Jeon, Sung Ju Hwang._ Arxiv 2024.

32. [**QuickLLaMA: Query-aware Inference Acceleration for Large Language Models.**](https://arxiv.org/abs/2406.07528) _Jingyao Li, Han Shi, Xin Jiang, Zhenguo Li, Hong Xu, Jiaya Jia._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/Q-LLM)](https://github.com/dvlab-research/Q-LLM)

33. [**MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention.**](https://arxiv.org/abs/2407.02490) _Huiqiang Jiang, Yucheng Li, Chengruidong Zhang, Qianhui Wu, Xufang Luo, Surin Ahn, Zhenhua Han, Amir H. Abdi, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://hqjiang.com/minference.html)

34. [**Model Tells You Where to Merge: Adaptive KV Cache Merging for LLMs on Long-Context Tasks.**](https://arxiv.org/abs/2407.08454) _Zheng Wang, Boxiao Jin, Zhongzhi Yu, Minjia Zhang._ Arxiv 2024.

35. [**Optimizing KV Cache Eviction in LLMs: Adaptive Allocation for Enhanced Budget Utilization.**](https://arxiv.org/abs/2407.11550) _Yuan Feng, Junlin Lv, Yukun Cao, Xike Xie, S. Kevin Zhou._ Arxiv 2024.

36. [**Beyond KV Caching: Shared Attention for Efficient LLMs.**](https://arxiv.org/abs/2407.12866) _Bingli Liao, Danilo Vasconcellos Vargas._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/metacarbon/shareAtt)](https://github.com/metacarbon/shareAtt)

37. [**PQCache: Product Quantization-based KVCache for Long Context LLM Inference.**](https://arxiv.org/abs/2407.12820) _Hailin Zhang, Xiaodong Ji, Yilin Chen, Fangcheng Fu, Xupeng Miao, Xiaonan Nie, Weipeng Chen, Bin Cui._ Arxiv 2024.

38. [**LazyLLM: Dynamic Token Pruning for Efficient Long Context LLM Inference.**](https://arxiv.org/abs/2407.14057) _Qichen Fu, Minsik Cho, Thomas Merth, Sachin Mehta, Mohammad Rastegari, Mahyar Najibi._ Arxiv 2024.

39. [**Farewell to Length Extrapolation, a Training-Free Infinite Context with Finite Attention Scope.**](https://arxiv.org/abs/2407.15176) _Xiaoran Liu, Qipeng Guo, Yuerong Song, Zhigeng Liu, Kai Lv, Hang Yan, Linlin Li, Qun Liu, Xipeng Qiu._ Arxiv 2024.

40. [**RazorAttention: Efficient KV Cache Compression Through Retrieval Heads.**](https://arxiv.org/abs/2407.15891) _Hanlin Tang, Yang Lin, Jing Lin, Qingsen Han, Shikuan Hong, Yiwu Yao, Gongyi Wang._ Arxiv 2024.

41. [**FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision.**](https://arxiv.org/abs/2407.08608) _Jay Shah, Ganesh Bikshandi, Ying Zhang, Vijay Thakkar, Pradeep Ramani, Tri Dao._ Arxiv 2024.

42. [**ThinK: Thinner Key Cache by Query-Driven Pruning.**](https://arxiv.org/abs/2407.21018) _Yuhui Xu, Zhanming Jie, Hanze Dong, Lei Wang, Xudong Lu, Aojun Zhou, Amrita Saha, Caiming Xiong, Doyen Sahoo._ ICLR 2025.

43. [**A2SF: Accumulative Attention Scoring with Forgetting Factor for Token Pruning in Transformer Decoder.**](https://arxiv.org/abs/2407.20485) _Hyun-rae Jo, Dongkun Shin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Dirac-Notation/A2SF)](https://github.com/Dirac-Notation/A2SF)

44. [**Cross-layer Attention Sharing for Large Language Models.**](https://arxiv.org/abs/2408.01890) _Yongyu Mu, Yuzhang Wu, Yuchun Fan, Chenglong Wang, Hengyu Li, Qiaozhi He, Murun Yang, Tong Xiao, Jingbo Zhu._ Arxiv 2024.

45. [**NACL: A General and Effective KV Cache Eviction Framework for LLMs at Inference Time.**](https://arxiv.org/abs/2408.03675) _Yilong Chen, Guoxia Wang, Junyuan Shang, Shiyao Cui, Zhenyu Zhang, Tingwen Liu, Shuohuan Wang, Yu Sun, Dianhai Yu, Hua Wu._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/PaddlePaddle/Research)](https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2024-NACL)

46. [**Tree Attention: Topology-aware Decoding for Long-Context Attention on GPU clusters.**](https://arxiv.org/abs/2408.04093) _Vasudev Shyam, Jonathan Pilault, Emily Shepperd, Quentin Anthony, Beren Millidge._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Zyphra/tree_attention)](https://github.com/Zyphra/tree_attention)

47. [**MagicDec: Breaking the Latency-Throughput Tradeoff for Long Context Generation with Speculative Decoding.**](https://arxiv.org/abs/2408.11049) _Jian Chen, Vashisth Tiwari, Ranajoy Sadhukhan, Zhuoming Chen, Jinyuan Shi, Ian En-Hsu Yen, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicDec)](https://github.com/Infini-AI-Lab/MagicDec/)

48. [**CSKV: Training-Efficient Channel Shrinking for KV Cache in Long-Context Scenarios.**](https://arxiv.org/abs/2409.10593) _Luning Wang, Shiyao Li, Xuefei Ning, Zhihang Yuan, Shengen Yan, Guohao Dai, Yu Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/wln20/cskv)](https://github.com/wln20/cskv/)

49. [**RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval.**](https://arxiv.org/abs/2409.10516) _Di Liu, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang, Qi Chen, Chengruidong Zhang, Bailu Ding, Kai Zhang, Chen Chen, Fan Yang, Yuqing Yang, Lili Qiu._ Arxiv 2024.

50. [**InstInfer: In-Storage Attention Offloading for Cost-Effective Long-Context LLM Inference.**](https://arxiv.org/abs/2409.04992) _Xiurui Pan, Endian Li, Qiao Li, Shengwen Liang, Yizhou Shan, Ke Zhou, Yingwei Luo, Xiaolin Wang, Jie Zhang._ Arxiv 2024.

51. [**CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs.**](https://arxiv.org/abs/2409.12490) _Junlin Lv, Yuan Feng, Xike Xie, Xin Jia, Qirong Peng, Guiming Xie._ Arxiv 2024.

52. [**Discovering the Gems in Early Layers: Accelerating Long-Context LLMs with 1000x Input Token Reduction.**](https://arxiv.org/abs/2409.17422) _Zhenmei Shi, Yifei Ming, Xuan-Phi Nguyen, Yingyu Liang, Shafiq Joty._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SalesforceAIResearch/GemFilter)](https://github.com/SalesforceAIResearch/GemFilter)

53. [**Inference-Friendly Models With MixAttention.**](https://arxiv.org/abs/2409.15012) _Shashank Rajput, Ying Sheng, Sean Owen, Vitaliy Chiley._ Arxiv 2024.

54. [**KV-Compress: Paged KV-Cache Compression with Variable Compression Rates per Attention Head.**](https://arxiv.org/abs/2410.00161) _Isaac Rehg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/IsaacRe/vllm-kvcompress)](https://github.com/IsaacRe/vllm-kvcompress)

55. [**Locret: Enhancing Eviction in Long-Context LLM Inference with Trained Retaining Heads.**](https://arxiv.org/abs/2410.01805) _Yuxiang Huang, Binhang Yuan, Xu Han, Chaojun Xiao, Zhiyuan Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/huangyuxiang03/Locret)](https://github.com/huangyuxiang03/Locret)

56. [**InfiniPot: Infinite Context Processing on Memory-Constrained LLMs.**](https://arxiv.org/abs/2410.01518) _Minsoo Kim, Kyuhong Shim, Jungwook Choi, Simyung Chang._ Arxiv 2024.

57. [**UNComp: Uncertainty-Aware Long-Context Compressor for Efficient Large Language Model Inference.**](https://arxiv.org/abs/2410.03090) _Jing Xiong, Jianghan Shen, Fanghua Ye, Chaofan Tao, Zhongwei Wan, Jianqiao Lu, Xun Wu, Chuanyang Zheng, Zhijiang Guo, Lingpeng Kong, Ngai Wong._ Arxiv 2024.

58. [**LoRC: Low-Rank Compression for LLMs KV Cache with a Progressive Compression Strategy.**](https://arxiv.org/abs/2410.03111) _Rongzhi Zhang, Kuang Wang, Liyuan Liu, Shuohang Wang, Hao Cheng, Chao Zhang, Yelong Shen._ Arxiv 2024.

59. [**DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads.**](https://arxiv.org/abs/2410.10819) _Guangxuan Xiao, Jiaming Tang, Jingwei Zuo, Junxian Guo, Shang Yang, Haotian Tang, Yao Fu, Song Han._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/duo-attention)](https://github.com/mit-han-lab/duo-attention)

60. [**In-context KV-Cache Eviction for LLMs via Attention-Gate.**](https://arxiv.org/abs/2410.12876) _Zihao Zeng, Bokai Lin, Tianqi Hou, Hao Zhang, Zhijie Deng._ Arxiv 2024.

61. [**SimLayerKV: A Simple Framework for Layer-Level KV Cache Reduction.**](https://arxiv.org/abs/2410.13846) _Xuan Zhang, Cunxiao Du, Chao Du, Tianyu Pang, Wei Gao, Min Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/SimLayerKV)](https://github.com/sail-sg/SimLayerKV)

62. [**A Systematic Study of Cross-Layer KV Sharing for Efficient LLM Inference.**](https://arxiv.org/abs/2410.14442) _You Wu, Haoyi Wu, Kewei Tu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

63. [**KVSharer: Efficient Inference via Layer-Wise Dissimilar KV Cache Sharing.**](https://arxiv.org/abs/2410.18517) _Yifei Yang, Zouying Cao, Qiguang Chen, Libo Qin, Dongjie Yang, Hai Zhao, Zhi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yangyifei729/KVSharer)](https://github.com/yangyifei729/KVSharer)

64. [**Lossless KV Cache Compression to 2%.**](https://arxiv.org/abs/2410.15252) _Zhen Yang, J.N.Han, Kan Wu, Ruobing Xie, An Wang, Xingwu Sun, Zhanhui Kang._ Arxiv 2024.

65. [**MatryoshkaKV: Adaptive KV Compression via Trainable Orthogonal Projection.**](https://arxiv.org/abs/2410.14731) _Bokai Lin, Zihao Zeng, Zipeng Xiao, Siqi Kou, Tianqi Hou, Xiaofeng Gao, Hao Zhang, Zhijie Deng._ Arxiv 2024.

66. [**EPIC: Efficient Position-Independent Context Caching for Serving Large Language Models.**](https://arxiv.org/abs/2410.15332) _Junhao Hu, Wenrui Huang, Haoyi Wang, Weidong Wang, Tiancheng Hu, Qin Zhang, Hao Feng, Xusheng Chen, Yizhou Shan, Tao Xie._ Arxiv 2024.

67. [**MagicPIG: LSH Sampling for Efficient LLM Generation.**](https://arxiv.org/abs/2410.16179) _Zhuoming Chen, Ranajoy Sadhukhan, Zihao Ye, Yang Zhou, Jianyu Zhang, Niklas Nolte, Yuandong Tian, Matthijs Douze, Leon Bottou, Zhihao Jia, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicPIG)](https://github.com/Infini-AI-Lab/MagicPIG)

68. [**Not All Heads Matter: A Head-Level KV Cache Compression Method with Integrated Retrieval and Reasoning.**](https://arxiv.org/abs/2410.19258) _Yu Fu, Zefan Cai, Abedelkadir Asi, Wayne Xiong, Yue Dong, Wen Xiao._ Arxiv 2024.

69. [**Long Sequence Modeling with Attention Tensorization: From Sequence to Tensor Learning.**](https://arxiv.org/abs/2410.20926) _Aosong Feng, Rex Ying, Leandros Tassiulas._ Arxiv 2024.

70. [**ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference.**](https://arxiv.org/abs/2410.21465) _Hanshi Sun, Li-Wen Chang, Wenlei Bao, Size Zheng, Ningxin Zheng, Xin Liu, Harry Dong, Yuejie Chi, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ShadowKV)](https://github.com/bytedance/ShadowKV)

71. [**BUZZ: Beehive-structured Sparse KV Cache with Segmented Heavy Hitters for Efficient LLM Inference.**](https://arxiv.org/abs/2410.23079) _Junqi Zhao, Zhijin Fang, Shu Li, Shaohui Yang, Shichao He._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JunqiZhao888/buzz-llm)](https://github.com/JunqiZhao888/buzz-llm)

72. [**VL-Cache: Sparsity and Modality-Aware KV Cache Compression for Vision-Language Model Inference Acceleration.**](https://arxiv.org/abs/2410.23317) _Dezhan Tu, Danylo Vashchilenko, Yuzhe Lu, Panpan Xu._ Arxiv 2024.

73. [**TokenSelect: Efficient Long-Context Inference and Length Extrapolation for LLMs via Dynamic Token-Level KV Cache Selection.**](https://arxiv.org/abs/2411.02886) _Wei Wu, Zhuoshi Pan, Chao Wang, Liyi Chen, Yunchu Bai, Kun Fu, Zheng Wang, Hui Xiong._ Arxiv 2024.

74. [**Recycled Attention: Efficient inference for long-context language models.**](https://arxiv.org/abs/2411.05787) _Fangyuan Xu, Tanya Goyal, Eunsol Choi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/carriex/recycled-attention)](https://github.com/carriex/recycled-attention)

75. [**Squeezed Attention: Accelerating Long Context Length LLM Inference.**](https://arxiv.org/abs/2411.09688) _Coleman Hooper, Sehoon Kim, Hiva Mohammadzadeh, Monishwaran Maheswaran, June Paik, Michael W. Mahoney, Kurt Keutzer, Amir Gholami._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SqueezeAILab/SqueezedAttention)](https://github.com/SqueezeAILab/SqueezedAttention)

76. [**When Precision Meets Position: BFloat16 Breaks Down RoPE in Long-Context Training.**](https://arxiv.org/abs/2411.13476) _Haonan Wang, Qian Liu, Chao Du, Tongyao Zhu, Cunxiao Du, Kenji Kawaguchi, Tianyu Pang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/haonan3/AnchorContext)](https://github.com/haonan3/AnchorContext)

77. [**Star Attention: Efficient LLM Inference over Long Sequences.**](https://arxiv.org/pdf/2411.17116) _Shantanu Acharya, Fei Jia, Boris Ginsburg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Star-Attention)](https://github.com/NVIDIA/Star-Attention)

78. [**Pushing the Limits of LLM Inference via 2-Bit Layer-Discriminative KV Cache.**](https://arxiv.org/abs/2411.18077) _Akshat Sharma, Hangliang Ding, Jianping Li, Neel Dani, Minjia Zhang._ Arxiv 2024.

79. [**Dynamic-LLaVA: Efficient Multimodal Large Language Models via Dynamic Vision-language Context Sparsification.**](https://arxiv.org/abs/2412.00876) _Wenxuan Huang, Zijie Zhai, Yunhang Shen, Shaoshen Cao, Fei Zhao, Xiangfeng Xu, Zheyu Ye, Shaohui Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Osilly/dynamic_llava)](https://github.com/Osilly/dynamic_llava)

80. [**Compressing KV Cache for Long-Context LLM Inference with Inter-Layer Attention Similarity.**](https://arxiv.org/abs/2412.02252) _Da Ma, Lu Chen, Situo Zhang, Yuxun Miao, Su Zhu, Zhi Chen, Hongshen Xu, Hanqi Li, Shuai Fan, Lei Pan, Kai Yu._ Arxiv 2024.

81. [**AIM: Adaptive Inference of Multi-Modal LLMs via Token Merging and Pruning.**](https://arxiv.org/abs/2412.03248) _Yiwu Zhong, Zhuoming Liu, Yin Li, Liwei Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/LaVi-Lab/AIM)](https://github.com/LaVi-Lab/AIM)

82. [**ClusterKV: Manipulating LLM KV Cache in Semantic Space for Recallable Compression.**](https://arxiv.org/abs/2412.03213) _Guangda Liu, Chengwei Li, Jieru Zhao, Chenqi Zhang, Minyi Guo._ Arxiv 2024.

83. [**BatchLLM: Optimizing Large Batched LLM Inference with Global Prefix Sharing and Throughput-oriented Token Batching.**](https://arxiv.org/abs/2412.03594) _Zhen Zheng, Xin Ji, Taosong Fang, Fanghao Zhou, Chuanjie Liu, Gang Peng._ Arxiv 2024.

84. [**Cross-Self KV Cache Pruning for Efficient Vision-Language Inference.**](https://arxiv.org/abs/2412.04652) _Xiaohuan Pei, Tao Huang, Chang Xu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TerryPei/CSP)](https://github.com/TerryPei/CSP)

85. [**Ltri-LLM: Streaming Long Context Inference for LLMs with Training-Free Dynamic Triangular Attention Pattern.**](https://arxiv.org/abs/2412.04757) _Hongyin Tang, Di Xiu, Lanrui Wang, Xiurui Geng, Jingang Wang, Xunliang Cai._ Arxiv 2024.

86. [**XKV: Personalized KV Cache Memory Reduction for Long-Context LLM Inference.**](https://arxiv.org/abs/2412.05896) _Weizhuo Li, Zhigang Wang, Yu Gu, Ge Yu._ Arxiv 2024.

87. [**SparseAccelerate: Efficient Long-Context Inference for Mid-Range GPUs.**](https://arxiv.org/abs/2412.06198) _James Vo._ Arxiv 2024.

88. [**EMS: Adaptive Evict-then-Merge Strategy for Head-wise KV Cache Compression Based on Global-Local Importance.**](https://arxiv.org/abs/2412.08521) _Yingxin Li, Ye Li, Yuan Meng, Xinzhu Ma, Zihan Geng, Shutao Xia, Zhi Wang._ Arxiv 2024.

89. [**ZigZagkv: Dynamic KV Cache Compression for Long-context Modeling based on Layer Uncertainty.**](https://arxiv.org/abs/2412.09036) _Meizhi Zhong, Xikai Liu, Chen Zhang, Yikun Lei, Yan Gao, Yao Hu, Kehai Chen, Min Zhang._ Arxiv 2024.

90. [**SepLLM: Accelerate Large Language Models by Compressing One Segment into One Separator.**](https://arxiv.org/abs/2412.12094) _Guoxuan Chen, Han Shi, Jiawei Li, Yihang Gao, Xiaozhe Ren, Yimeng Chen, Xin Jiang, Zhenguo Li, Weiyang Liu, Chao Huang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/SepLLM)](https://github.com/HKUDS/SepLLM)

91. [**More Tokens, Lower Precision: Towards the Optimal Token-Precision Trade-off in KV Cache Compression.**](https://arxiv.org/abs/2412.12706) _Jiebin Zhang, Dawei Zhu, Yifan Song, Wenhao Wu, Chuqiao Kuang, Xiaoguang Li, Lifeng Shang, Qun Liu, Sujian Li._ Arxiv 2024.

92. [**Boosting Long-Context Information Seeking via Query-Guided Activation Refilling.**](https://arxiv.org/abs/2412.12486) _Hongjin Qian, Zheng Liu, Peitian Zhang, Zhicheng Dou, Defu Lian._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/qhjqhj00/activation_refilling)](https://github.com/qhjqhj00/activation_refilling)

93. [**SCOPE: Optimizing Key-Value Cache Compression in Long-context Generation.**](https://arxiv.org/abs/2412.13649) _Jialong Wu, Zhenglin Wang, Linhai Zhang, Yilong Lai, Yulan He, Deyu Zhou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Linking-ai/SCOPE)](https://github.com/Linking-ai/SCOPE)

94. [**DynamicKV: Task-Aware Adaptive KV Cache Compression for Long Context LLMs.**](https://arxiv.org/abs/2412.14838) _Xiabin Zhou, Wenbin Wang, Minyan Zeng, Jiaxian Guo, Xuebo Liu, Li Shen, Min Zhang, Liang Ding._ Arxiv 2024.

95. [**HashEvict: A Pre-Attention KV Cache Eviction Strategy using Locality-Sensitive Hashing.**](https://arxiv.org/abs/2412.16187) _Minghui Liu, Tahseen Rabbani, Tony O'Halloran, Ananth Sankaralingam, Mary-Anne Hartley, Brian Gravelle, Furong Huang, Cornelia Fermüller, Yiannis Aloimonos._ Arxiv 2024.

96. [**AdaSkip: Adaptive Sublayer Skipping for Accelerating Long-Context LLM Inference.**](https://arxiv.org/abs/2501.02336) _Zhuomin He, Yizhen Yao, Pengfei Zuo, Bin Gao, Qinya Li, Zhenzhe Zheng, Fan Wu._ AAAI 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ASISys/AdaSkip)](https://github.com/ASISys/AdaSkip)

97. [**TreeKV: Smooth Key-Value Cache Compression with Tree Structures.**](https://arxiv.org/abs/2501.04987) _Ziwei He, Jian Yuan, Haoli Bai, Jingwen Leng, Bo Jiang._ Arxiv 2025.

98. [**Dynamic Memory Compression: Retrofitting LLMs for Accelerated Inference.**](https://arxiv.org/abs/2403.09636) _Piotr Nawrot, Adrian Łańcucki, Marcin Chochowski, David Tarjan, Edoardo M. Ponti._ Arxiv 2024.

99. [**DeepSeek-V3 Technical Report.**](https://arxiv.org/abs/2412.19437) _DeepSeek-AI, Aixin Liu, Bei Feng, Bing Xue, Bingxuan Wang, Bochao Wu, Chengda Lu, Chenggang Zhao, Chengqi Deng, Chenyu Zhang, Chong Ruan, Damai Dai, Daya Guo, Dejian Yang, Deli Chen, Dongjie Ji, Erhang Li, Fangyun Lin, Fucong Dai, Fuli Luo, Guangbo Hao, Guanting Chen, Guowei Li, H. Zhang, Han Bao, Hanwei Xu, Haocheng Wang, Haowei Zhang, Honghui Ding, Huajian Xin, Huazuo Gao, Hui Li, Hui Qu, J.L. Cai, Jian Liang, Jianzhong Guo, Jiaqi Ni, Jiashi Li, Jiawei Wang, Jin Chen, Jingchang Chen, Jingyang Yuan, Junjie Qiu, Junlong Li, Junxiao Song, Kai Dong, Kai Hu, Kaige Gao, Kang Guan, Kexin Huang, Kuai Yu, Lean Wang, Lecong Zhang, Lei Xu, Leyi Xia, Liang Zhao, Litong Wang, Liyue Zhang, Meng Li, Miaojun Wang, Mingchuan Zhang, Minghua Zhang, Minghui Tang, Mingming Li, Ning Tian, Panpan Huang, Peiyi Wang, Peng Zhang, Qiancheng Wang, Qihao Zhu, Qinyu Chen, Qiushi Du, R.J. Chen, R.L. Jin, Ruiqi Ge, Ruisong Zhang, Ruizhe Pan, Runji Wang, Runxin Xu, Ruoyu Zhang, Ruyi Chen, S.S. Li, Shanghao Lu, Shangyan Zhou, Shanhuang Chen, Shaoqing Wu, Shengfeng Ye, Shengfeng Ye, Shirong Ma, Shiyu Wang, Shuang Zhou, Shuiping Yu, Shunfeng Zhou, Shuting Pan, T. Wang, Tao Yun, Tian Pei, Tianyu Sun, W.L. Xiao, Wangding Zeng et al. (100 additional authors not shown)._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V3)](https://github.com/deepseek-ai/DeepSeek-V3)

100. [**Tensor Product Attention Is All You Need.**](https://arxiv.org/abs/2501.06425) _Yifan Zhang, Yifeng Liu, Huizhuo Yuan, Zhen Qin, Yang Yuan, Quanquan Gu, Andrew Chi-Chih Yao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/tensorgi/T6)](https://github.com/tensorgi/T6)

101. [**Sigma: Differential Rescaling of Query, Key and Value for Efficient Language Models.**](https://arxiv.org/abs/2501.13629) _Zhenghao Lin, Zihao Tang, Xiao Liu, Yeyun Gong, Yi Cheng, Qi Chen, Hang Li, Ying Xin, Ziyue Yang, Kailai Yang, Yu Yan, Xiao Liang, Shuai Lu, Yiming Huang, Zheheng Luo, Lei Qu, Xuan Feng, Yaoxiang Wang, Yuqing Xia, Feiyang Chen, Yuting Jiang, Yasen Hu, Hao Ni, Binyang Li, Guoshuai Zhao, Jui-Hao Chiang, Zhongxin Guo, Chen Lin, Kun Kuang, Wenjie Li, Yelong Shen, Jian Jiao, Peng Cheng, Mao Yang._ Arxiv 2025.

102. [**CAKE: Cascading and Adaptive KV Cache Eviction with Layer Preferences.**](https://openreview.net/forum?id=EQgEMAD4kv) _Ziran Qin, Yuchen Cao, Mingbao Lin, Wen Hu, Shixuan Fan, Ke Cheng, Weiyao Lin, Jianguo Li._ ICLR 2025.

103. [**AKVQ-VL: Attention-Aware KV Cache Adaptive 2-Bit Quantization for Vision-Language Models.**](https://arxiv.org/abs/2501.15021) _Zunhai Su, Wang Shen, Linge Li, Zhe Chen, Hanyu Wei, Huangqi Yu, Kehong Yuan._ Arxiv 2025.

104. [**ChunkKV: Semantic-Preserving KV Cache Compression for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2502.00299) _Xiang Liu, Zhenheng Tang, Peijie Dong, Zeyu Li, Bo Li, Xuming Hu, Xiaowen Chu._ Arxiv 2025.

105. [**FastKV: KV Cache Compression for Fast Long-Context Processing with Token-Selective Propagation.**](https://arxiv.org/abs/2502.01068) _Dongwon Jo, Jiwon Song, Yulhwa Kim, Jae-Joon Kim._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/dongwonjo/FastKV)](https://github.com/dongwonjo/FastKV)

106. [**Can LLMs Maintain Fundamental Abilities under KV Cache Compression?.**](https://arxiv.org/abs/2502.01941) _Xiang Liu, Zhenheng Tang, Hong Chen, Peijie Dong, Zeyu Li, Xiuze Zhou, Bo Li, Xuming Hu, Xiaowen Chu._ Arxiv 2025.

107. [**Speculative Prefill: Turbocharging TTFT with Lightweight and Training-Free Token Importance Estimation.**](https://arxiv.org/abs/2502.02789) _Jingyu Liu, Beidi Chen, Ce Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Jingyu6/speculative_prefill)](https://github.com/Jingyu6/speculative_prefill)

108. [**Twilight: Adaptive Attention Sparsity with Hierarchical Top-p Pruning.**](https://arxiv.org/abs/2502.02770) _Chaofan Lin, Jiaming Tang, Shuo Yang, Hanshuo Wang, Tian Tang, Boyu Tian, Ion Stoica, Song Han, Mingyu Gao._ Arxiv 2025.

109. [**AttentionPredictor: Temporal Pattern Matters for Efficient LLM Inference.**](https://arxiv.org/abs/2502.04077) _Qingyue Yang, Jie Wang, Xing Li, Zhihai Wang, Chen Chen, Lei Chen, Xianzhi Yu, Wulong Liu, Jianye Hao, Mingxuan Yuan, Bin Li._ Arxiv 2025.

110. [**Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective.**](https://arxiv.org/abs/2502.03805) _Yuan Feng, Junlin Lv, Yukun Cao, Xike Xie, S Kevin Zhou._ Arxiv 2025.

111. [**KVTuner: Sensitivity-Aware Layer-wise Mixed Precision KV Cache Quantization for Efficient and Nearly Lossless LLM Inference.**](https://arxiv.org/abs/2502.04420) _Xing Li, Zeyu Xing, Yiming Li, Linping Qu, Hui-Ling Zhen, Wulong Liu, Yiwu Yao, Sinno Jialin Pan, Mingxuan Yuan._ Arxiv 2025.

112. [**Exploiting Sparsity for Long Context Inference: Million Token Contexts on Commodity GPUs.**](https://arxiv.org/abs/2502.06766) _Ryan Synk, Monte Hoover, John Kirchenbauer, Neel Jain, Alex Stein, Manli Shu, Josue Melendez Sanchez, Ramani Duraiswami, Tom Goldstein._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ryansynk/topk-decoding)](https://github.com/ryansynk/topk-decoding)

113. [**Online Scheduling for LLM Inference with KV Cache Constraints.**](https://arxiv.org/abs/2502.07115) _Patrick Jaillet, Jiashuo Jiang, Chara Podimata, Zijie Zhou._ Arxiv 2025.

114. [**BalanceKV: KV Cache Compression through Discrepancy Theory.**](https://arxiv.org/abs/2502.07861) _Insu Han, Michael Kapralov, Ekaterina Kochetkova, Kshiteej Sheth, Amir Zandieh._ Arxiv 2025.

115. [**TransMLA: Multi-Head Latent Attention Is All You Need.**](https://arxiv.org/abs/2502.07864) _Fanxu Meng, Zengwei Yao, Muhan Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/fxmeng/TransMLA)](https://github.com/fxmeng/TransMLA)

116. [**InfiniteHiP: Extending Language Model Context Up to 3 Million Tokens on a Single GPU.**](https://arxiv.org/abs/2502.08910) _Heejun Lee, Geon Park, Jaduk Suh, Sung Ju Hwang._ Arxiv 2025.

117. [**RoSTE: An Efficient Quantization-Aware Supervised Fine-Tuning Approach for Large Language Models.**](https://arxiv.org/abs/2502.09003) _Quan Wei, Chung-Yiu Yau, Hoi-To Wai, Yang (Katie)Zhao, Dongyeop Kang, Youngsuk Park, Mingyi Hong._ Arxiv 2025.

118. [**Native Sparse Attention: Hardware-Aligned and Natively Trainable Sparse Attention.**](https://arxiv.org/abs/2502.11089) _Jingyang Yuan, Huazuo Gao, Damai Dai, Junyu Luo, Liang Zhao, Zhengyan Zhang, Zhenda Xie, Y. X. Wei, Lean Wang, Zhiping Xiao, Yuqing Wang, Chong Ruan, Ming Zhang, Wenfeng Liang, Wangding Zeng._ Arxiv 2025.

119. [**QuantSpec: Self-Speculative Decoding with Hierarchical Quantized KV Cache.**](https://arxiv.org/abs/2502.10424) _Rishabh Tiwari, Haocheng Xi, Aditya Tomar, Coleman Hooper, Sehoon Kim, Maxwell Horton, Mahyar Najibi, Michael W. Mahoney, Kurt Keutzer, Amir Gholami._ Arxiv 2025.

120. [**APB: Accelerating Distributed Long-Context Inference by Passing Compressed Context Blocks across GPUs.**](https://arxiv.org/abs/2502.12085) _Yuxiang Huang, Mingye Li, Xu Han, Chaojun Xiao, Weilin Zhao, Sun Ao, Hao Zhou, Jie Zhou, Zhiyuan Liu, Maosong Sun._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/APB)](https://github.com/thunlp/APB)

121. [**AdaSplash: Adaptive Sparse Flash Attention.**](https://arxiv.org/abs/2502.12082) _Nuno Gonçalves, Marcos Treviso, André F. T. Martins._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/deep-spin/adasplash)](https://github.com/deep-spin/adasplash)

122. [**Tactic: Adaptive Sparse Attention with Clustering and Distribution Fitting for Long-Context LLMs.**](https://arxiv.org/abs/2502.12216) _Kan Zhu, Tian Tang, Qinyu Xu, Yile Gu, Zhichen Zeng, Rohan Kadekodi, Liangyu Zhao, Ang Li, Arvind Krishnamurthy, Baris Kasikci._ Arxiv 2025.

123. [**HeadInfer: Memory-Efficient LLM Inference by Head-wise Offloading.**](https://arxiv.org/abs/2502.12574) _Cheng Luo, Zefan Cai, Hanshi Sun, Jinqi Xiao, Bo Yuan, Wen Xiao, Junjie Hu, Jiawei Zhao, Beidi Chen, Anima Anandkumar._ Arxiv 2025.

124. [**A2ATS: Retrieval-Based KV Cache Reduction via Windowed Rotary Position Embedding and Query-Aware Vector Quantization.**](https://arxiv.org/abs/2502.12665) _Junhui He, Junna Xing, Nan Wang, Rui Xu, Shangyu Wu, Peng Zhou, Qiang Liu, Chun Jason Xue, Qingan Li._ Arxiv 2025.

125. [**BaKlaVa -- Budgeted Allocation of KV cache for Long-context Inference.**](https://arxiv.org/abs/2502.13176) _Ahmed Burak Gulhan, Krishna Teja Chitty-Venkata, Murali Emani, Mahmut Kandemir, Venkatram Vishwanath._ Arxiv 2025.

126. [**Activation-aware Probe-Query: Effective Key-Value Retrieval for Long-Context LLMs Inference.**](https://arxiv.org/abs/2502.13542) _Qingfa Xiao, Jiachuan Wang, Haoyang Li, Cheng Deng, Jiaqi Tang, Shuangyin Li, Yongqi Zhang, Jun Wang, Lei Chen._ Arxiv 2025.

127. [**RocketKV: Accelerating Long-Context LLM Inference via Two-Stage KV Cache Compression.**](https://arxiv.org/abs/2502.14051) _Payman Behnam, Yaosheng Fu, Ritchie Zhao, Po-An Tsai, Zhiding Yu, Alexey Tumanov._ Arxiv 2025.

128. [**LServe: Efficient Long-sequence LLM Serving with Unified Sparse Attention.**](https://arxiv.org/abs/2502.14866) _Shang Yang, Junxian Guo, Haotian Tang, Qinghao Hu, Guangxuan Xiao, Jiaming Tang, Yujun Lin, Zhijian Liu, Yao Lu, Song Han._ MLSys 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/omniserve)](https://github.com/mit-han-lab/omniserve)

129. [**Unshackling Context Length: An Efficient Selective Attention Approach through Query-Key Compression.**](https://arxiv.org/abs/2502.14477) _Haoyu Wang, Tong Teng, Tianyu Guo, An Xiao, Duyu Tang, Hanting Chen, Yunhe Wang._ Arxiv 2025.

130. [**Towards Economical Inference: Enabling DeepSeek's Multi-Head Latent Attention in Any Transformer-based LLMs.**](https://arxiv.org/abs/2502.14837) _Tao Ji, Bin Guo, Yuanbin Wu, Qipeng Guo, Lixing Shen, Zhan Chen, Xipeng Qiu, Qi Zhang, Tao Gui._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/JT-Ushio/MHA2MLA)](https://github.com/JT-Ushio/MHA2MLA)

131. [**SVDq: 1.25-bit and 410x Key Cache Compression for LLM Attention.**](https://arxiv.org/abs/2502.15304) _Hong Yankun, Li Xing, Zhen Hui-Ling, Yu Xianzhi, Liu Wulong, Yuan Mingxuan._ Arxiv 2025.

132. [**Round Attention: A Novel Round-Level Attention Mechanism to Accelerate LLM Inference.**](https://arxiv.org/abs/2502.15294) _Yaohua Tang, Zhicheng Hu, Kun Cheng, Fan Mo, Qiheng Lv, Hua Wang, Zhi Chen._ Arxiv 2025.

133. [**DBudgetKV: Dynamic Budget in KV Cache Compression for Ensuring Optimal Performance.**](https://arxiv.org/abs/2502.16886) _Xuanfan Ni, Liyan Xu, Chenyang Lyu, Longyue Wang, Mo Yu, Lemao Liu, Fandong Meng, Jie Zhou, Piji Li._ Arxiv 2025.

134. [**KVLink: Accelerating Large Language Models via Efficient KV Cache Reuse.**](https://arxiv.org/abs/2502.16002) _Jingbo Yang, Bairu Hou, Wei Wei, Yujia Bao, Shiyu Changi._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UCSB-NLP-Chang/KVLink)](https://github.com/UCSB-NLP-Chang/KVLink)

135. [**FairKV: Balancing Per-Head KV Cache for Fast Multi-GPU Inference.**](https://arxiv.org/abs/2502.15804) _Bingzhe Zhao, Ke Cheng, Aomufei Yuan, Yuxuan Tian, Ruiguang Zhong, Chengchen Hu, Tong Yang, Lian Yu._ Arxiv 2025.

136. [**CoKV: Optimizing KV Cache Allocation via Cooperative Game.**](https://arxiv.org/abs/2502.17501) _Qiheng Sun, Hongwei Zhang, Haocheng Xia, Jiayao Zhang, Jinfei Liu, Kui Ren._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nawei1010/CoKV)](https://github.com/nawei1010/CoKV)

137. [**MEDA: Dynamic KV Cache Allocation for Efficient Multimodal Long-Context Inference.**](https://arxiv.org/abs/2502.17599) _Zhongwei Wan, Hui Shen, Xin Wang, Che Liu, Zheda Mai, Mi Zhang._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AIoT-MLSys-Lab/MEDA)](https://github.com/AIoT-MLSys-Lab/MEDA)

138. [**FlexPrefill: A Context-Aware Sparse Attention Mechanism for Efficient Long-Sequence Inference.**](https://arxiv.org/abs/2502.20766) _Xunhao Lai, Jianqiao Lu, Yao Luo, Yiyuan Ma, Xun Zhou._ ICLR 2025 Oral.

139. [**WeightedKV: Attention Scores Weighted Key-Value Cache Merging for Large Language Models.**](https://arxiv.org/abs/2503.01330) _Jian Yuan, Ziwei He, Haoli Bai, Jingwen Leng, Bo Jiang._ ICASSP 2025.

140. [**Dialogue Without Limits: Constant-Sized KV Caches for Extended Responses in LLMs.**](https://arxiv.org/abs/2503.00979) _Ravi Ghadia, Avinash Kumar, Gaurav Jain, Prashant Nair, Poulami Das._ Arxiv 2025.

141. [**KVCrush: Key value cache size-reduction using similarity in head-behaviour.**](https://arxiv.org/abs/2503.00022) _Gopi Krishna Jha, Sameh Gobriel, Liubov Talamanova, Alexander Kozlov, Nilesh Jain._ Arxiv 2025.

142. [**EliteKV: Scalable KV Cache Compression via RoPE Frequency Selection and Joint Low-Rank Projection.**](https://arxiv.org/abs/2503.01586) _Yuhao Zhou, Sirui Song, Boyang Liu, Zhiheng Xi, Senjie Jin, Xiaoran Fan, Zhihao Zhang, Wei Li, Xuanjing Huang._ Arxiv 2025.

143. [**Progressive Sparse Attention: Algorithm and System Co-design for Efficient Attention in LLM Serving.**](https://arxiv.org/abs/2503.00392) _Qihui Zhou, Peiqi Yin, Pengfei Zuo, James Cheng._ Arxiv 2025.

144. [**Q-Filters: Leveraging QK Geometry for Efficient KV Cache Compression.**](https://arxiv.org/abs/2503.02812) _Nathan Godey, Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini, Éric de la Clergerie, Benoît Sagot._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NathanGodey/qfilters)](https://github.com/NathanGodey/qfilters)

145. [**TokenButler: Token Importance is Predictable.**](https://arxiv.org/abs/2503.07518) _Yash Akhauri, Ahmed F AbouElhamayed, Yifei Gao, Chi-Chih Chang, Nilesh Jain, Mohamed S. Abdelfattah._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/abdelfattah-lab/TokenButler)](https://github.com/abdelfattah-lab/TokenButler)

146. [**Slim attention: cut your context memory in half without loss of accuracy -- K-cache is all you need for MHA.**](https://arxiv.org/abs/2503.05840) _Nils Graef, Andrew Wasielewski._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenMachine-ai/transformer-tricks)](https://github.com/OpenMachine-ai/transformer-tricks)

147. [**LLMs Know What to Drop: Self-Attention Guided KV Cache Eviction for Efficient Long-Context Inference.**](https://arxiv.org/abs/2503.08879) _Guangtao Wang, Shubhangi Upasani, Chen Wu, Darshan Gandhi, Jonathan Li, Changran Hu, Bo Li, Urmish Thakker._ ICLR 2025.

148. [**KV-Distill: Nearly Lossless Learnable Context Compression for LLMs.**](https://arxiv.org/abs/2503.10337) _Vivek Chari, Guanghui Qin, Benjamin Van Durme._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/vnchari/kv-distill)](https://github.com/vnchari/kv-distill)

149. [**Radar: Fast Long-Context Decoding for Any Transformer.**](https://arxiv.org/abs/2503.10571) _Yongchang Hao, Mengyao Zhai, Hossein Hajimirsadeghi, Sepidehsadat Hosseini, Frederick Tung._ ICLR 2025.

150. [**ZeroMerge: Parameter-Free KV Cache Compression for Memory-Efficient Long-Context LLMs.**](https://arxiv.org/abs/2503.10714) _Xin Liu, Pei Liu, Guoming Tang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SusCom-Lab/ZeroMerge)](https://github.com/SusCom-Lab/ZeroMerge)

151. [**Exploring the Limits of KV Cache Compression in Visual Autoregressive Transformers.**](https://arxiv.org/abs/2503.14881) _Bo Chen, Xiaoyu Li, Yekun Ke, Yingyu Liang, Zhenmei Shi, Zhao Song._ Arxiv 2025.

152. [**SpeCache: Speculative Key-Value Caching for Efficient Generation of LLMs.**](https://arxiv.org/abs/2503.16163) _Shibo Jie, Yehui Tang, Kai Han, Zhi-Hong Deng, Jing Han._ Arxiv 2025.

153. [**KVShare: Semantic-Aware Key-Value Cache Sharing for Efficient Large Language Model Inference.**](https://arxiv.org/abs/2503.16525) _Huan Yang, Renji Zhang, Deyu Zhang._ Arxiv 2025.

154. [**xKV: Cross-Layer SVD for KV-Cache Compression.**](https://arxiv.org/abs/2503.18893) _Chi-Chih Chang, Chien-Yu Lin, Yash Akhauri, Wei-Cheng Lin, Kai-Chiang Wu, Luis Ceze, Mohamed S. Abdelfattah._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/abdelfattah-lab/xKV)](https://github.com/abdelfattah-lab/xKV)

155. [**WindowKV: Task-Adaptive Group-Wise KV Cache Window Selection for Efficient LLM Inference.**](https://arxiv.org/abs/2503.17922) _Youhui Zuo, Sibo Wei, Chen Zhang, Zhuorui Liu, Wenpeng Lu, Dawei Song._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/optim996/WindowKV)](https://github.com/optim996/WindowKV)

156. [**BitDecoding: Unlocking Tensor Cores for Long-Context LLMs Decoding with Low-Bit KV Cache.**](https://arxiv.org/abs/2503.18773) _Dayou Du, Shijie Cao, Jianyi Cheng, Ting Cao, Mao Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DD-DuDa/BitDecoding)](https://github.com/DD-DuDa/BitDecoding)

157. [**Oaken: Fast and Efficient LLM Serving with Online-Offline Hybrid KV Cache Quantization.**](https://arxiv.org/abs/2503.18599) _Minsu Kim, Seongmin Hong, RyeoWook Ko, Soongyu Choi, Hunjong Lee, Junsoo Kim, Joo-Young Kim, Jongse Park._ Arxiv 2025.

158. [**LogQuant: Log-Distributed 2-Bit Quantization of KV Cache with Superior Accuracy Preservation.**](https://arxiv.org/abs/2503.19950) _Han Chen, Zicong Jiang, Zining Zhang, Bingsheng He, Pingyi Luo, Mian Lu, Yuqiang Chen._ ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Concyclics/LogQuantKV)](https://github.com/Concyclics/LogQuantKV)

159. [**Cocktail: Chunk-Adaptive Mixed-Precision Quantization for Long-Context LLM Inference.**](https://arxiv.org/abs/2503.23294) _Wei Tao, Bin Zhang, Xiaoyang Qu, Jiguang Wan, Jianzong Wang._ DATE 2025.

160. [**PromptDistill: Query-based Selective Token Retention in Intermediate Layers for Efficient Large Language Model Inference.**](https://arxiv.org/abs/2503.23274) _Weisheng Jin, Maojia Song, Tej Deep Pala, Yew Ken Chia, Amir Zadeh, Chuan Li, Soujanya Poria._ Arxiv 2025.

161. [**SQuat: Subspace-orthogonal KV Cache Quantization.**](https://arxiv.org/abs/2503.24358) _Hao Wang, Ligong Han, Kai Xu, Akash Srivastava._ Arxiv 2025.

162. [**Rethinking Key-Value Cache Compression Techniques for Large Language Model Serving.**](https://arxiv.org/abs/2503.24000) _Wei Gao, Xinyu Zhou, Peng Sun, Tianwei Zhang, Yonggang Wen._ MLSys 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LLMkvsys/rethink-kv-compression)](https://github.com/LLMkvsys/rethink-kv-compression)

163. [**SentenceKV: Efficient LLM Inference via Sentence-Level Semantic KV Caching.**](https://arxiv.org/abs/2504.00970) _Yuxuan Zhu, Ali Falahati, David H. Yang, Mohammad Mohammadi Amiri._ Arxiv 2025.

164. [**LagKV: Lag-Relative Information of the KV Cache Tells Which Tokens Are Important.**](https://arxiv.org/abs/2504.04704) _Manlai Liang, JiaMing Zhang, Xiong Li, Jinlong Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AI-Lab-China-Merchants-Bank/LagKV)](https://github.com/AI-Lab-China-Merchants-Bank/LagKV)

165. [**FlowKV: A Disaggregated Inference Framework with Low-Latency KV Cache Transfer and Load-Aware Scheduling.**](https://arxiv.org/abs/2504.03775) _Weiqing Li, Guochao Jiang, Xiangyong Ding, Zhangcheng Tao, Chuzhan Hao, Chenfeng Xu, Yuewei Zhang, Hao Wang._ Arxiv 2025.

166. [**Apt-Serve: Adaptive Request Scheduling on Hybrid Cache for Scalable LLM Inference Serving.**](https://arxiv.org/abs/2504.07494) _Shihong Gao, Xin Zhang, Yanyan Shen, Lei Chen._ Arxiv 2025.

167. [**KeepKV: Eliminating Output Perturbation in KV Cache Compression for Efficient LLMs Inference.**](https://arxiv.org/abs/2504.09936) _Yuxuan Tian, Zihan Wang, Yebo Peng, Aomufei Yuan, Zhiming Wang, Bairen Yi, Xin Liu, Yong Cui, Tong Yang._ Arxiv 2025.

168. [**MOM: Memory-Efficient Offloaded Mini-Sequence Inference for Long Context Language Models.**](https://arxiv.org/abs/2504.12526) _Junyang Zhang, Tianyi Zhu, Cheng Luo, Anima Anandkumar._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/TianyiZhu877/MOM)](https://github.com/TianyiZhu877/MOM)

169. [**CAOTE: KV Caching through Attention Output Error based Token Eviction.**](https://arxiv.org/abs/2504.14051) _Raghavv Goel, Junyoung Park, Mukul Gagrani, Dalton Jones, Matthew Morse, Harper Langston, Mingu Lee, Chris Lott._ Arxiv 2025.

170. [**SlimPipe: Memory-Thrifty and Efficient Pipeline Parallelism for Long-Context LLM Training.**](https://arxiv.org/abs/2504.14519) _Zhouyang Li, Yuliang Liu, Wei Zhang, Tailing Yuan, Bin Chen, Chengru Song, Di Zhang._ Arxiv 2025.

171. [**FreqKV: Frequency Domain Key-Value Compression for Efficient Context Window Extension.**](https://arxiv.org/abs/2505.00570) _Jushi Kai, Boyi Zeng, Yixuan Wang, Haoli Bai, Bo Jiang, Zhouhan Lin._ Arxiv 2025.

172. [**dKV-Cache: The Cache for Diffusion Language Models.**](https://arxiv.org/abs/2505.15781) _Xinyin Ma, Runpeng Yu, Gongfan Fang, Xinchao Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/dKV-Cache)](https://github.com/horseee/dKV-Cache)

173. [**PM-KVQ: Progressive Mixed-precision KV Cache Quantization for Long-CoT LLMs.**](https://arxiv.org/abs/2505.18610) _Tengxuan Liu, Shiyao Li, Jiayi Yang, Tianchen Zhao, Feng Zhou, Xiaohui Song, Guohao Dai, Shengen Yan, Huazhong Yang, Yu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/thu-nics/PM-KVQ)](https://github.com/thu-nics/PM-KVQ)

174. [**TailorKV: A Hybrid Framework for Long-Context Inference via Tailored KV Cache Optimization.**](https://arxiv.org/abs/2505.19586) _Dingyu Yao, Bowen Shen, Zheng Lin, Wei Liu, Jian Luan, Bin Wang, Weiping Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ydyhello/TailorKV)](https://github.com/ydyhello/TailorKV)

175. [**R-KV: Redundancy-aware KV Cache Compression for Training-Free Reasoning Models Acceleration.**](https://arxiv.org/abs/2505.24133) _Zefan Cai, Wen Xiao, Hanshi Sun, Cheng Luo, Yikai Zhang, Ke Wan, Yucheng Li, Yeyang Zhou, Li-Wen Chang, Jiuxiang Gu, Zhen Dong, Anima Anandkumar, Abedelkadir Asi, Junjie Hu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Zefan-Cai/R-KV)](https://github.com/Zefan-Cai/R-KV)

176. [**ReCalKV: Low-Rank KV Cache Compression via Head Reordering and Offline Calibration.**](https://arxiv.org/abs/2505.24357) _Xianglong Yan, Zhiteng Li, Tianao Zhang, Linghe Kong, Yulun Zhang, Xiaokang Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/XIANGLONGYAN/ReCalKV)](https://github.com/XIANGLONGYAN/ReCalKV)

177. [**VScan: Rethinking Visual Token Reduction for Efficient Large Vision-Language Models.**](https://arxiv.org/abs/2505.22654) _Ce Zhang, Kaixin Ma, Tianqing Fang, Wenhao Yu, Hongming Zhang, Zhisong Zhang, Yaqi Xie, Katia Sycara, Haitao Mi, Dong Yu._ Arxiv 2025.

178. [**KVzip: Query-Agnostic KV Cache Compression with Context Reconstruction.**](https://arxiv.org/abs/2505.23416) _Jang-Hyun Kim, Jinuk Kim, Sangwoo Kwon, Jae W. Lee, Sangdoo Yun, Hyun Oh Song._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/snu-mllab/KVzip)](https://github.com/snu-mllab/KVzip)

179. [**Mustafar: Promoting Unstructured Sparsity for KV Cache Pruning in LLM Inference.**](https://arxiv.org/abs/2505.22913) _Donghyeon Joo, Helya Hosseini, Ramyad Hadidi, Bahar Asgari._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/dhjoo98/mustafar)](https://github.com/dhjoo98/mustafar)

180. [**Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query.**](https://arxiv.org/abs/2505.20334) _Yixuan Wang, Shiyu Ji, Yijun Liu, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che._ Arxiv 2025.

181. [**Hardware-Efficient Attention for Fast Decoding.**](https://arxiv.org/abs/2505.21487) _Ted Zadouri, Hubert Strauss, Tri Dao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Dao-AILab/grouped-latent-attention)](https://github.com/Dao-AILab/grouped-latent-attention)

182. [**Accelerating Diffusion Language Model Inference via Efficient KV Caching and Guided Diffusion.**](https://arxiv.org/abs/2505.21467) _Zhanqiu Hu, Jian Meng, Yash Akhauri, Mohamed S. Abdelfattah, Jae-sun Seo, Zhiru Zhang, Udit Gupta._ Arxiv 2025.

### 3. Recurrent Transformers

1. [**Transformer-XL: Attentive language models beyond a fixed-length context.**](https://arxiv.org/abs/1901.02860) _Zihang Dai, Zhilin Yang, Yiming Yang, Jaime Carbonell, Quoc V. Le, Ruslan Salakhutdinov._ ACL 2019. [![GitHub Repo stars](https://img.shields.io/github/stars/kimiyoung/transformer-xl)](https://github.com/kimiyoung/transformer-xl)

2. [**Compressive Transformers for Long-Range Sequence Modelling.**](https://arxiv.org/abs/1911.05507) _Jack W. Rae, Anna Potapenko, Siddhant M. Jayakumar, Timothy P. Lillicrap._ Arxiv 2019. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/compressive-transformer-pytorch)](https://github.com/lucidrains/compressive-transformer-pytorch)

3. [**Memformer: The memory-augmented transformer.**](https://arxiv.org/abs/2010.06891) _Qingyang Wu, Zhenzhong Lan, Kun Qian, Jing Gu, Alborz Geramifard, Zhou Yu._ Arxiv 2020. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/memformer)](https://github.com/lucidrains/memformer)

4. [**ERNIE-Doc: A Retrospective Long-Document Modeling Transformer.**](https://aclanthology.org/2021.acl-long.227/) _SiYu Ding, Junyuan Shang, Shuohuan Wang, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang._ ACL-IJCNLP 2021.

5. [**Memorizing Transformers.**](https://arxiv.org/abs/2203.08913) _Yuhuai Wu, Markus N. Rabe, DeLesley Hutchins, Christian Szegedy._ Arxiv 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/memorizing-transformers-pytorch)](https://github.com/lucidrains/memorizing-transformers-pytorch)

6. [**Recurrent Attention Networks for Long-text Modeling.**](https://aclanthology.org/2023.findings-acl.188/) _Xianming Li, Zongxi Li, Xiaotian Luo, Haoran Xie, Xing Lee, Yingbin Zhao, Fu Lee Wang, Qing Li._ ACL 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/4ai/ran)](https://github.com/4ai/ran)

7. [**RWKV: Reinventing RNNs for the Transformer Era.**](https://arxiv.org/abs/2305.13048) _Bo Peng, Eric Alcaide, Quentin Anthony, Alon Albalak, Samuel Arcadinho, Huanqi Cao, Xin Cheng, Michael Chung, Matteo Grella, Kranthi Kiran GV, Xuzheng He, Haowen Hou, Przemyslaw Kazienko, Jan Kocon, Jiaming Kong, Bartlomiej Koptyra, Hayden Lau, Krishna Sri Ipsit Mantri, Ferdinand Mom, Atsushi Saito, Xiangru Tang, Bolun Wang, Johan S. Wind, Stansilaw Wozniak, Ruichong Zhang, Zhenyuan Zhang, Qihang Zhao, Peng Zhou, Jian Zhu, Rui-Jie Zhu._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/BlinkDL/RWKV-LM)](https://github.com/BlinkDL/RWKV-LM)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/BlinkDL/ChatRWKV)](https://github.com/BlinkDL/ChatRWKV)

8. [**Segmented Recurrent Transformer: An Efficient Sequence-to-Sequence Model.**](https://arxiv.org/abs/2305.16340) _Yinghan Long, Sayeed Shafayet Chowdhury, Kaushik Roy._ Arxiv 2023.

9. [**Scaling Transformer to 1M tokens and beyond with RMT.**](https://arxiv.org/abs/2304.11062) _Aydar Bulatov, Yuri Kuratov, Mikhail S. Burtsev._ Arxiv 2023.

10. [**Block-Recurrent Transformers.**](https://arxiv.org/abs/2203.07852) _DeLesley Hutchins, Imanol Schlag, Yuhuai Wu, Ethan Dyer, Behnam Neyshabur._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/lucidrains/block-recurrent-transformer-pytorch)](https://github.com/lucidrains/block-recurrent-transformer-pytorch)

11. [**TRAMS: Training-free Memory Selection for Long-range Language Modeling.**](https://arxiv.org/abs/2310.15494) _Haofei Yu, Cunxiang Wang, Yue Zhang, Wei Bi._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/lwaekfjlk/TRAMS)](https://github.com/lwaekfjlk/TRAMS)

12. [**Griffin: Mixing Gated Linear Recurrences with Local Attention for Efficient Language Models.**](https://arxiv.org/abs/2402.19427) _Soham De, Samuel L. Smith, Anushan Fernando, Aleksandar Botev, George Cristian-Muraru, Albert Gu, Ruba Haroun, Leonard Berrada, Yutian Chen, Srivatsan Srinivasan, Guillaume Desjardins, Arnaud Doucet, David Budden, Yee Whye Teh, Razvan Pascanu, Nando De Freitas, Caglar Gulcehre._ Arxiv 2024.

13. [**Extensible Embedding: A Flexible Multipler For LLM's Context Length.**](https://arxiv.org/abs/2402.11577) _Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

14. [**Eagle and Finch: RWKV with Matrix-Valued States and Dynamic Recurrence.**](https://arxiv.org/abs/2404.05892) _Bo Peng, Daniel Goldstein, Quentin Anthony, Alon Albalak, Eric Alcaide, Stella Biderman, Eugene Cheah, Teddy Ferdinan, Haowen Hou, Przemysław Kazienko, Kranthi Kiran GV, Jan Kocoń, Bartłomiej Koptyra, Satyapriya Krishna, Ronald McClelland Jr., Niklas Muennighoff, Fares Obeid, Atsushi Saito, Guangyu Song, Haoqin Tu, Stanisław Woźniak, Ruichong Zhang, Bingchen Zhao, Qihang Zhao, Peng Zhou, Jian Zhu, Rui-Jie Zhu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/RWKV/RWKV-LM)](https://github.com/RWKV/RWKV-LM)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RWKV/ChatRWKV)](https://github.com/RWKV/ChatRWKV)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/RWKV/RWKV-infctx-trainer)](https://github.com/RWKV/RWKV-infctx-trainer)

15. [**Leave No Context Behind: Efficient Infinite Context Transformers with Infini-attention.**](https://arxiv.org/abs/2404.07143) _Tsendsuren Munkhdalai, Manaal Faruqui, Siddharth Gopal._ Arxiv 2024.

16. [**RecurrentGemma: Moving Past Transformers for Efficient Open Language Models.**](https://arxiv.org/abs/2404.07839) _Aleksandar Botev, Soham De, Samuel L Smith, Anushan Fernando, George-Cristian Muraru, Ruba Haroun, Leonard Berrada, Razvan Pascanu, Pier Giuseppe Sessa, Robert Dadashi, Léonard Hussenot, Johan Ferret, Sertan Girgin, Olivier Bachem, Alek Andreev, Kathleen Kenealy, Thomas Mesnard, Cassidy Hardin, Surya Bhupatiraju, Shreya Pathak, Laurent Sifre, Morgane Rivière, Mihir Sanjay Kale, Juliette Love, Pouya Tafti, Armand Joulin, Noah Fiedel, Evan Senter, Yutian Chen, Srivatsan Srinivasan, Guillaume Desjardins, David Budden, Arnaud Doucet, Sharad Vikram, Adam Paszke, Trevor Gale, Sebastian Borgeaud, Charlie Chen, Andy Brock, Antonia Paterson, Jenny Brennan, Meg Risdal, Raj Gundluru, Nesh Devanathan, Paul Mooney, Nilay Chauhan, Phil Culliton, Luiz GUStavo Martins, Elisa Bandy, David Huntsperger, Glenn Cameron, Arthur Zucker, Tris Warkentin, Ludovic Peran, Minh Giang, Zoubin Ghahramani, Clément Farabet, Koray Kavukcuoglu, Demis Hassabis, Raia Hadsell, Yee Whye Teh, Nando de Frietas._ Arxiv 2024.

17. [**Linearizing Large Language Models.**](https://arxiv.org/abs/2405.06640) _Jean Mercat, Igor Vasiljevic, Sedrick Keh, Kushal Arora, Achal Dave, Adrien Gaidon, Thomas Kollar._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TRI-ML/linear_open_lm)](https://github.com/TRI-ML/linear_open_lm)

18. [**VisualRWKV: Exploring Recurrent Neural Networks for Visual Language Models.**](https://arxiv.org/abs/2406.13362) _Haowen Hou, Peigen Zeng, Fei Ma, Fei Richard Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/howard-hou/VisualRWKV)](https://github.com/howard-hou/VisualRWKV)

19. [**Just read twice: closing the recall gap for recurrent language models.**](https://arxiv.org/abs/2407.05483) _Simran Arora, Aman Timalsina, Aaryan Singhal, Benjamin Spector, Sabri Eyuboglu, Xinyi Zhao, Ashish Rao, Atri Rudra, Christopher Ré._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HazyResearch/prefix-linear-attention)](https://github.com/HazyResearch/prefix-linear-attention)

20. [**Associative Recurrent Memory Transformer.**](https://arxiv.org/abs/2407.04841) _Ivan Rodkin, Yuri Kuratov, Aydar Bulatov, Mikhail Burtsev._ ICML 2024 Workshop. [![GitHub Repo stars](https://img.shields.io/github/stars/RodkinIvan/associative-recurrent-memory-transformer)](https://github.com/RodkinIvan/associative-recurrent-memory-transformer)

21. [**GoldFinch: High Performance RWKV/Transformer Hybrid with Linear Pre-Fill and Extreme KV-Cache Compression.**](https://arxiv.org/abs/2407.12077) _Daniel Goldstein, Fares Obeid, Eric Alcaide, Guangyu Song, Eugene Cheah._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/recursal/GoldFinch-paper)](https://github.com/recursal/GoldFinch-paper)

22. [**Analysis of Argument Structure Constructions in a Deep Recurrent Language Model.**](https://arxiv.org/abs/2408.03062) _Pegah Ramezani, Achim Schilling, Patrick Krauss._ Arxiv 2024.

23. [**xLSTM 7B: A Recurrent LLM for Fast and Efficient Inference.**](https://arxiv.org/abs/2503.13427) _Maximilian Beck, Korbinian Pöppel, Phillip Lippe, Richard Kurle, Patrick M. Blies, Günter Klambauer, Sebastian Böck, Sepp Hochreiter._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NX-AI/xlstm)](https://github.com/NX-AI/xlstm)

### 4. State Space Models

1. [**Mamba: Linear-Time Sequence Modeling with Selective State Spaces.**](https://arxiv.org/abs/2312.00752) _Albert Gu, Tri Dao._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/state-spaces/mamba)](https://github.com/state-spaces/mamba)

2. [**MoE-Mamba: Efficient Selective State Space Models with Mixture of Experts.**](https://arxiv.org/abs/2401.04081) _Maciej Pióro, Kamil Ciebiera, Krystian Król, Jan Ludziejewski, Sebastian Jaszczur._ Arxiv 2024.

3. [**MambaByte: Token-free Selective State Space Model.**](https://arxiv.org/abs/2401.13660) _Junxiong Wang, Tushaar Gangavarapu, Jing Nathan Yan, Alexander M Rush._ Arxiv 2024.

4. [**LOCOST: State-Space Models for Long Document Abstractive Summarization.**](https://arxiv.org/abs/2401.17919) _Florian Le Bronnec, Song Duong, Mathieu Ravaut, Alexandre Allauzen, Nancy F. Chen, Vincent Guigue, Alberto Lumbreras, Laure Soulier, Patrick Gallinari._ Arxiv 2024.

5. [**State Space Models as Foundation Models: A Control Theoretic Overview.**](https://arxiv.org/abs/2403.16899) _Carmen Amo Alonso, Jerome Sieber, Melanie N. Zeilinger._ Arxiv 2024.

6. [**Jamba: A Hybrid Transformer-Mamba Language Model.**](https://arxiv.org/abs/2403.19887) _Opher Lieber, Barak Lenz, Hofit Bata, Gal Cohen, Jhonathan Osin, Itay Dalmedigos, Erez Safahi, Shaked Meirom, Yonatan Belinkov, Shai Shalev-Shwartz, Omri Abend, Raz Alon, Tomer Asida, Amir Bergman, Roman Glozman, Michael Gokhman, Avashalom Manevich, Nir Ratner, Noam Rozen, Erez Shwartz, Mor Zusman, Yoav Shoham._ Arxiv 2024.

7. [**Robustifying State-space Models for Long Sequences via Approximate Diagonalization.**](https://openreview.net/forum?id=DjeQ39QoLQ) _Annan Yu, Arnur Nigmetov, Dmitriy Morozov, Michael W. Mahoney, N. Benjamin Erichson._ ICLR 2024 Spotlight.

8. [**Zamba: A Compact 7B SSM Hybrid Model.**](https://arxiv.org/abs/2405.16712) _Paolo Glorioso, Quentin Anthony, Yury Tokpanov, James Whittington, Jonathan Pilault, Adam Ibrahim, Beren Millidge._ Arxiv 2024.

9. [**Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality.**](https://arxiv.org/abs/2405.21060) _Tri Dao, Albert Gu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/state-spaces/mamba)](https://github.com/state-spaces/mamba)

10. [**Samba: Simple Hybrid State Space Models for Efficient Unlimited Context Language Modeling.**](https://arxiv.org/abs/2406.07522) _Liliang Ren, Yang Liu, Yadong Lu, Yelong Shen, Chen Liang, Weizhu Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/Samba)](https://github.com/microsoft/Samba)

11. [**An Empirical Study of Mamba-based Language Models.**](https://arxiv.org/abs/2406.07887) _Roger Waleffe, Wonmin Byeon, Duncan Riach, Brandon Norick, Vijay Korthikanti, Tri Dao, Albert Gu, Ali Hatamizadeh, Sudhakar Singh, Deepak Narayanan, Garvit Kulshreshtha, Vartika Singh, Jared Casper, Jan Kautz, Mohammad Shoeybi, Bryan Catanzaro._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM)](https://github.com/NVIDIA/Megatron-LM/tree/ssm/examples/mamba)

12. [**B'MOJO: Hybrid State Space Realizations of Foundation Models with Eidetic and Fading Memory.**](https://arxiv.org/abs/2407.06324) _Luca Zancato, Arjun Seshadri, Yonatan Dukler, Aditya Golatkar, Yantao Shen, Benjamin Bowman, Matthew Trager, Alessandro Achille, Stefano Soatto._ Arxiv 2024.

13. [**MambaForGCN: Enhancing Long-Range Dependency with State Space Model and Kolmogorov-Arnold Networks for Aspect-Based Sentiment Analysis.**](https://arxiv.org/abs/2407.10347) _Adamu Lawan, Juhua Pu, Haruna Yunusa, Aliyu Umar, Muhammad Lawan._ Arxiv 2024.

14. [**Discrete Diffusion Language Model for Long Text Summarization.**](https://arxiv.org/abs/2407.10998) _Do Huu Dat, Do Duc Anh, Anh Tuan Luu, Wray Buntine._ Arxiv 2024.

15. [**ML-Mamba: Efficient Multi-Modal Large Language Model Utilizing Mamba-2.**](https://arxiv.org/abs/2407.19832) _Wenjun Huang, Jianguo Hu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WenjunHuang94/ML-Mamba)](https://github.com/WenjunHuang94/ML-Mamba)

16. [**Jamba-1.5: Hybrid Transformer-Mamba Models at Scale.**](https://arxiv.org/abs/2408.12570) _Jamba Team: Barak Lenz, Alan Arazi, Amir Bergman, Avshalom Manevich, Barak Peleg, Ben Aviram, Chen Almagor, Clara Fridman, Dan Padnos, Daniel Gissin, Daniel Jannai, Dor Muhlgay, Dor Zimberg, Edden M Gerber, Elad Dolev, Eran Krakovsky, Erez Safahi, Erez Schwartz, Gal Cohen, Gal Shachaf, Haim Rozenblum, Hofit Bata, Ido Blass, Inbal Magar, Itay Dalmedigos, Jhonathan Osin, Julie Fadlon, Maria Rozman, Matan Danos, Michael Gokhman, Mor Zusman, Naama Gidron, Nir Ratner, Noam Gat, Noam Rozen, Oded Fried, Ohad Leshno, Omer Antverg, Omri Abend, Opher Lieber, Or Dagan, Orit Cohavi, Raz Alon, Ro'i Belson, Roi Cohen, Rom Gilad, Roman Glozman, Shahar Lev, Shaked Meirom, Tal Delbari, Tal Ness, Tomer Asida, Tom Ben Gal, Tom Braude, Uriya Pumerantz, Yehoshua Cohen, Yonatan Belinkov, Yuval Globerson, Yuval Peleg Levy, Yoav Shoham._ Arxiv 2024.

17. [**SpikingSSMs: Learning Long Sequences with Sparse and Parallel Spiking State Space Models.**](https://arxiv.org/abs/2408.14909) _Shuaijie Shen, Chao Wang, Renzhuo Huang, Yan Zhong, Qinghai Guo, Zhichao Lu, Jianguo Zhang, Luziwei Leng._ Arxiv 2024.

18. [**ReMamba: Equip Mamba with Effective Long-Sequence Modeling.**](https://arxiv.org/abs/2408.15496) _Danlong Yuan, Jiahao Liu, Bei Li, Huishuai Zhang, Jingang Wang, Xunliang Cai, Dongyan Zhao._ Arxiv 2024.

19. [**Stuffed Mamba: State Collapse and State Capacity of RNN-Based Long-Context Modeling.**](https://arxiv.org/abs/2410.07145) _Yingfa Chen, Xinrong Zhang, Shengding Hu, Xu Han, Zhiyuan Liu, Maosong Sun._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/stuffed-mamba)](https://github.com/thunlp/stuffed-mamba)

20. [**Taipan: Efficient and Expressive State Space Language Models with Selective Attention.**](https://arxiv.org/abs/2410.18572) _Chien Van Nguyen, Huy Huu Nguyen, Thang M. Pham, Ruiyi Zhang, Hanieh Deilamsalehy, Puneet Mathur, Ryan A. Rossi, Trung Bui, Viet Dac Lai, Franck Dernoncourt, Thien Huu Nguyen._ Arxiv 2024.

21. [**Rethinking Token Reduction for State Space Models.**](https://arxiv.org/abs/2410.14725) _Zheng Zhan, Yushu Wu, Zhenglun Kong, Changdi Yang, Yifan Gong, Xuan Shen, Xue Lin, Pu Zhao, Yanzhi Wang._ EMNLP 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/wuyushuwys/ToR_SSM)](https://github.com/wuyushuwys/ToR_SSM)

22. [**Attamba: Attending To Multi-Token States.**](https://arxiv.org/abs/2411.17685) _Yash Akhauri, Safeen Huda, Mohamed S. Abdelfattah._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/abdelfattah-lab/attamba)](https://github.com/abdelfattah-lab/attamba)

23. [**Gated Delta Networks: Improving Mamba2 with Delta Rule.**](https://arxiv.org/abs/2412.06464) _Songlin Yang, Jan Kautz, Ali Hatamizadeh._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NVlabs/GatedDeltaNet)](https://github.com/NVlabs/GatedDeltaNet)

24. [**SSMLoRA: Enhancing Low-Rank Adaptation with State Space Model.**](https://arxiv.org/abs/2502.04958) _Jiayang Yu, Yihang Zhang, Bin Wang, Peiqin Lin, Yongkang Liu, Shi Feng._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/yuhkalhic/SSMLoRA)](https://github.com/yuhkalhic/SSMLoRA)

25. [**S2TX: Cross-Attention Multi-Scale State-Space Transformer for Time Series Forecasting.**](https://arxiv.org/abs/2502.11340) _Zihao Wu, Juncheng Dong, Haoming Yang, Vahid Tarokh._ Arxiv 2025.

26. [**CacheMamba: Popularity Prediction for Mobile Edge Caching Networks via Selective State Spaces.**](https://arxiv.org/abs/2502.15746) _Ghazaleh Kianfar, Zohreh Hajiakhondi-Meybodi, Arash Mohammadi._ Arxiv 2025.

27. [**M1: Towards Scalable Test-Time Compute with Mamba Reasoning Models.**](https://arxiv.org/abs/2504.10449) _Junxiong Wang, Wen-Ding Li, Daniele Paliotta, Daniel Ritter, Alexander M. Rush, Tri Dao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/jxiw/M1)](https://github.com/jxiw/M1)

28. [**LongMamba: Enhancing Mamba's Long Context Capabilities via Training-Free Receptive Field Enlargement.**](https://arxiv.org/abs/2504.16053) _Zhifan Ye, Kejing Xia, Yonggan Fu, Xin Dong, Jihoon Hong, Xiangchi Yuan, Shizhe Diao, Jan Kautz, Pavlo Molchanov, Yingyan Celine Lin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/GATECH-EIC/LongMamba)](https://github.com/GATECH-EIC/LongMamba)

29. [**RWKV-X: A Linear Complexity Hybrid Language Model.**](https://arxiv.org/abs/2504.21463) _Haowen Hou, Zhiyi Huang, Kaifeng Tan, Rongchang Lu, Fei Richard Yu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/howard-hou/RWKV-X)](https://github.com/howard-hou/RWKV-X)

30. [**Zebra-Llama: Towards Extremely Efficient Hybrid Models.**](https://arxiv.org/abs/2505.17272) _Mingyu Yang, Mehdi Rezagholizadeh, Guihong Li, Vikram Appia, Emad Barsoum._ Arxiv 2025.

31. [**Sparsified State-Space Models are Efficient Highway Networks.**](https://arxiv.org/abs/2505.20698) _Woomin Song, Jihoon Tack, Sangwoo Mo, Seunghyuk Oh, Jinwoo Shin._ TMLR 2025.

### 5. Length Extrapolation

1. [**RoFormer: Enhanced Transformer with Rotary Position Embedding.**](https://arxiv.org/abs/2104.09864) _Jianlin Su, Yu Lu, Shengfeng Pan, Ahmed Murtadha, Bo Wen, Yunfeng Liu._ Arxiv 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/ZhuiyiTechnology/roformer)](https://github.com/ZhuiyiTechnology/roformer)

2. [**Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation.**](https://arxiv.org/abs/2108.12409) _Ofir Press, Noah A. Smith, Mike Lewis._ ICLR 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/ofirpress/attention_with_linear_biases)](https://github.com/ofirpress/attention_with_linear_biases)

3. [**KERPLE: Kernelized Relative Positional Embedding for Length Extrapolation.**](https://arxiv.org/abs/2205.09921) _Ta-Chung Chi, Ting-Han Fan, Peter J. Ramadge, Alexander I. Rudnicky._ Arxiv 2022.

4. [**Dissecting Transformer Length Extrapolation via the Lens of Receptive Field Analysis.**](https://aclanthology.org/2023.acl-long.756/) _Ta-Chung Chi, Ting-Han Fan, Alexander I. Rudnicky, Peter J. Ramadge._ ACL 2023.

5. [**A Length-Extrapolatable Transformer.**](https://aclanthology.org/2023.acl-long.816/) _Yutao Sun, Li Dong, Barun Patra, Shuming Ma, Shaohan Huang, Alon Benhaim, Vishrav Chaudhary, Xia Song, Furu Wei._ ACL 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/sunyt32/torchscale)](https://github.com/sunyt32/torchscale)

6. [**Randomized Positional Encodings Boost Length Generalization of Transformers.**](https://aclanthology.org/2023.acl-short.161/) _Anian Ruoss, Grégoire Delétang, Tim Genewein, Jordi Grau-Moya, Róbert Csordás, Mehdi Bennani, Shane Legg, Joel Veness._ ACL 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/randomized_positional_encodings)](https://github.com/google-deepmind/randomized_positional_encodings)

7. [**The Impact of Positional Encoding on Length Generalization in Transformers.**](https://arxiv.org/abs/2305.19466) _Amirhossein Kazemnejad, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Payel Das, Siva Reddy._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/McGill-NLP/length-generalization)](https://github.com/McGill-NLP/length-generalization)

8. [**Focused Transformer: Contrastive Training for Context Scaling.**](https://arxiv.org/abs/2307.03170) _Szymon Tworkowski, Konrad Staniszewski, Mikołaj Pacek, Yuhuai Wu, Henryk Michalewski, Piotr Miłoś._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/CStanKonrad/long_llama)](https://github.com/CStanKonrad/long_llama)

9. [**Extending Context Window of Large Language Models via Positional Interpolation.**](https://arxiv.org/abs/2306.15595) _Shouyuan Chen, Sherman Wong, Liangjian Chen, Yuandong Tian._ Arxiv 2023.

10. [**Exploring Transformer Extrapolation.**](https://arxiv.org/abs/2307.10156) _Zhen Qin, Yiran Zhong, Hui Deng._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/Rpe)](https://github.com/OpenNLPLab/Rpe)

11. [**LM-Infinite: Simple On-the-Fly Length Generalization for Large Language Models.**](https://arxiv.org/pdf/2308.16137.pdf) _Chi Han, Qifan Wang, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/LM-Infinite)](https://github.com/kyegomez/LM-Infinite)

12. [**YaRN: Efficient Context Window Extension of Large Language Models.**](https://arxiv.org/abs/2309.00071) _Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/jquesnelle/yarn)](https://github.com/jquesnelle/yarn)

13. [**PoSE: Efficient Context Window Extension of LLMs via Positional Skip-wise Training.**](https://arxiv.org/abs/2309.10400) _Dawei Zhu,Nan Yang,Liang Wang,Yifan Song,Wenhao Wu,Furu Wei,Sujian Li._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/PoSE)](https://github.com/dwzhu-pku/PoSE)

14. [**LongLoRA: Efficient Fine-tuning of Long-Context Large Language Models.**](https://arxiv.org/abs/2309.12307) _Yukang Chen, Shengju Qian, Haotian Tang, Xin Lai, Zhijian Liu, Song Han, Jiaya Jia._ ICLR 2024 Oral. [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/LongLoRA)](https://github.com/dvlab-research/LongLoRA)

15. [**Scaling Laws of RoPE-based Extrapolation.**](https://arxiv.org/abs/2310.05209) _Xiaoran Liu, Hang Yan, Shuo Zhang, Chenxin An, Xipeng Qiu, Dahua Lin._ Arxiv 2023.

16. [**Attention Alignment and Flexible Positional Embeddings Improve Transformer Length Extrapolation.**](https://arxiv.org/pdf/2311.00684v1.pdf) _Ta-Chung Chi,Ting-Han Fan,Alexander I. Rudnicky._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/chijames/Attention-Alignment-Transformer-Length-Extrapolation)](https://github.com/chijames/Attention-Alignment-Transformer-Length-Extrapolation)

17. [**CoCA: Fusing position embedding with Collinear Constrained Attention for fine-tuning free context window extending.**](https://arxiv.org/abs/2309.08646) _Shiyi Zhu, Jing Ye, Wei Jiang, Qi Zhang, Yifan Wu, Jianguo Li._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/codefuse-ai/Collinear-Constrained-Attention)](https://github.com/codefuse-ai/Collinear-Constrained-Attention)

18. [**Structured Packing in LLM Training Improves Long Context Utilization.**](https://arxiv.org/abs/2312.17296) _Konrad Staniszewski, Szymon Tworkowski, Sebastian Jaszczur, Henryk Michalewski, Łukasz Kuciński, Piotr Miłoś._ Arxiv 2024.

19. [**LLM Maybe LongLM: Self-Extend LLM Context Window Without Tuning.**](https://arxiv.org/abs/2401.01325v1) _Hongye Jin, Xiaotian Han, Jingfeng Yang, Zhimeng Jiang, Zirui Liu, Chia-Yuan Chang, Huiyuan Chen, Xia Hu._ Arxiv 2024.

20. [**Infinite-LLM: Efficient LLM Service for Long Context with DistAttention and Distributed KVCache.**](https://arxiv.org/abs/2401.02669) _Bin Lin, Tao Peng, Chen Zhang, Minmin Sun, Lanbo Li, Hanyu Zhao, Wencong Xiao, Qi Xu, Xiafei Qiu, Shen Li, Zhigang Ji, Yong Li, Wei Lin._ Arxiv 2024.

21. [**Lightning Attention-2: A Free Lunch for Handling Unlimited Sequence Lengths in Large Language Models.**](https://arxiv.org/abs/2401.04695) _Zhen Qin, Weigao Sun, Dong Li, Xuyang Shen, Weixuan Sun, Yiran Zhong._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/lightning-attention)](https://github.com/OpenNLPLab/lightning-attention)

22. [**Extending LLMs' Context Window with 100 Samples.**](https://arxiv.org/abs/2401.07004) _Yikai Zhang, Junlong Li, Pengfei Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/Entropy-ABF)](https://github.com/GAIR-NLP/Entropy-ABF)

23. [**E^2-LLM: Efficient and Extreme Length Extension of Large Language Models.**](https://arxiv.org/abs/2401.06951) _Jiaheng Liu, Zhiqi Bai, Yuanxing Zhang, Chenchen Zhang, Yu Zhang, Ge Zhang, Jiakai Wang, Haoran Que, Yukang Chen, Wenbo Su, Tiezheng Ge, Jie Fu, Wenhu Chen, Bo Zheng._ Arxiv 2024.

24. [**With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation.**](https://arxiv.org/abs/2401.11504) _Y. Wang, D. Ma, D. Cai._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TemporaryLoRA/Temp-LoRA)](https://github.com/TemporaryLoRA/Temp-LoRA)

25. [**Two Stones Hit One Bird: Bilevel Positional Encoding for Better Length Extrapolation.**](https://arxiv.org/abs/2401.16421) _Zhenyu He, Guhao Feng, Shengjie Luo, Kai Yang, Di He, Jingjing Xu, Zhi Zhang, Hongxia Yang, Liwei Wang._ ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zhenyuhe00/BiPE)](https://github.com/zhenyuhe00/BiPE)

26. [**Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens.**](https://arxiv.org/abs/2401.17377) _Jiacheng Liu, Sewon Min, Luke Zettlemoyer, Yejin Choi, Hannaneh Hajishirzi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/liujch1998/infini-gram)](https://github.com/liujch1998/infini-gram)

27. [**LongRoPE: Extending LLM ContextWindow Beyond 2 Million Tokens.**](https://arxiv.org/abs/2402.13753) _Yiran Ding, Li Lyna Zhang, Chengruidong Zhang, Yuanyuan Xu, Ning Shang, Jiahang Xu, Fan Yang, Mao Yang._ Arxiv 2024.

28. [**Data Engineering for Scaling Language Models to 128K Context.**](https://arxiv.org/abs/2402.10171) _Yao Fu, Rameswar Panda, Xinyao Niu, Xiang Yue, Hannaneh Hajishirzi, Yoon Kim, Hao Peng._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FranxYao/Long-Context-Data-Engineering)](https://github.com/FranxYao/Long-Context-Data-Engineering)

29. [**Transformers Can Achieve Length Generalization But Not Robustly.**](https://arxiv.org/abs/2402.09371v1) _Yongchao Zhou, Uri Alon, Xinyun Chen, Xuezhi Wang, Rishabh Agarwal, Denny Zhou._ Arxiv 2024.

30. [**Long-Context Language Modeling with Parallel Context Encoding.**](https://arxiv.org/abs/2402.16617) _Howard Yen, Tianyu Gao, Danqi Chen._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/CEPE)](https://github.com/princeton-nlp/CEPE)

31. [**CLEX: Continuous Length Extrapolation for Large Language Models.**](https://arxiv.org/abs/2310.16450) _Guanzheng Chen, Xin Li, Zaiqiao Meng, Shangsong Liang, Lidong Bing._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/DAMO-NLP-SG/CLEX)](https://github.com/DAMO-NLP-SG/CLEX)

32. [**Resonance RoPE: Improving Context Length Generalization of Large Language Models.**](https://arxiv.org/abs/2403.00071) _Suyuchen Wang, Ivan Kobyzev, Peng Lu, Mehdi Rezagholizadeh, Bang Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sheryc/resonance_rope)](https://github.com/sheryc/resonance_rope)

33. [**Can't Remember Details in Long Documents? You Need Some R&R.**](https://arxiv.org/abs/2403.05004) _Devanshu Agrawal, Shang Gao, Martin Gajek._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/casetext/r-and-r)](https://github.com/casetext/r-and-r)

34. [**Found in the Middle: How Language Models Use Long Contexts Better via Plug-and-Play Positional Encoding.**](https://arxiv.org/abs/2403.04797) _Zhenyu Zhang, Runjin Chen, Shiwei Liu, Zhewei Yao, Olatunji Ruwase, Beidi Chen, Xiaoxia Wu, Zhangyang Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/Ms-PoE)](https://github.com/VITA-Group/Ms-PoE)

35. [**InfLLM: Unveiling the Intrinsic Capacity of LLMs for Understanding Extremely Long Sequences with Training-Free Memory.**](https://arxiv.org/abs/2402.04617) _Chaojun Xiao, Pengle Zhang, Xu Han, Guangxuan Xiao, Yankai Lin, Zhengyan Zhang, Zhiyuan Liu, Song Han, Maosong Sun._ Arxiv 2024.

36. [**Naive Bayes-based Context Extension for Large Language Models.**](https://arxiv.org/abs/2403.17552) _Jianlin Su, Murtadha Ahmed, Wenbo, Luo Ao, Mingren Zhu, Yunfeng Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/amurtadha/NBCE-master)](https://github.com/amurtadha/NBCE-master)

37. [**Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient Generative Inference.**](https://arxiv.org/abs/2403.09054) _Muhammad Adnan, Akhil Arunkumar, Gaurav Jain, Prashant J. Nair, Ilya Soloveychik, Purushotham Kamath._ Arxiv 2024.

38. [**In-Context Pretraining: Language Modeling Beyond Document Boundaries.**](https://openreview.net/forum?id=LXVswInHOo) _Weijia Shi, Sewon Min, Maria Lomeli, Chunting Zhou, Margaret Li, Xi Victoria Lin, Noah A. Smith, Luke Zettlemoyer, Wen-tau Yih, Mike Lewis._ ICLR 2024 Spotlight. [![GitHub Repo stars](https://img.shields.io/github/stars/swj0419/in-context-pretraining)](https://github.com/swj0419/in-context-pretraining)

39. [**Effective Long-Context Scaling of Foundation Models.**](https://arxiv.org/abs/2309.16039) _Wenhan Xiong, Jingyu Liu, Igor Molybog, Hejia Zhang, Prajjwal Bhargava, Rui Hou, Louis Martin, Rashi Rungta, Karthik Abinav Sankararaman, Barlas Oguz, Madian Khabsa, Han Fang, Yashar Mehdad, Sharan Narang, Kshitiz Malik, Angela Fan, Shruti Bhosale, Sergey Edunov, Mike Lewis, Sinong Wang, Hao Ma._ Arxiv 2023.

40. [**Fewer Truncations Improve Language Modeling.**](https://arxiv.org/abs/2404.10830) _Hantian Ding, Zijian Wang, Giovanni Paolini, Varun Kumar, Anoop Deoras, Dan Roth, Stefano Soatto._ Arxiv 2024.

41. [**Length Generalization of Causal Transformers without Position Encoding.**](https://arxiv.org/abs/2404.12224) _Jie Wang, Tao Ji, Yuanbin Wu, Hang Yan, Tao Gui, Qi Zhang, Xuanjing Huang, Xiaoling Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AntNLP/nope_head_scale)](https://github.com/AntNLP/nope_head_scale)

42. [**Extending Llama-3's Context Ten-Fold Overnight.**](https://arxiv.org/abs/2404.19553) _Peitian Zhang, Ninglu Shao, Zheng Liu, Shitao Xiao, Hongjin Qian, Qiwei Ye, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

43. [**Long Context Alignment with Short Instructions and Synthesized Positions.**](https://arxiv.org/abs/2405.03939) _Wenhao Wu, Yizhong Wang, Yao Fu, Xiang Yue, Dawei Zhu, Sujian Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nightdessert/SkipAlign)](https://github.com/nightdessert/SkipAlign)

44. [**xLSTM: Extended Long Short-Term Memory.**](https://arxiv.org/abs/2405.04517) _Maximilian Beck, Korbinian Pöppel, Markus Spanring, Andreas Auer, Oleksandra Prudnikova, Michael Kopp, Günter Klambauer, Johannes Brandstetter, Sepp Hochreiter._ Arxiv 2024.

45. [**DAPE: Data-Adaptive Positional Encoding for Length Extrapolation.**](https://arxiv.org/abs/2405.14722) _Chuanyang Zheng, Yihang Gao, Han Shi, Minbin Huang, Jingyao Li, Jing Xiong, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE)](https://github.com/chuanyang-Zheng/DAPE)

46. [**Contextual Position Encoding: Learning to Count What's Important.**](https://arxiv.org/abs/2405.18719) _Olga Golovneva, Tianlu Wang, Jason Weston, Sainbayar Sukhbaatar._ Arxiv 2024.

47. [**Quest: Query-centric Data Synthesis Approach for Long-context Scaling of Large Language Model.**](https://arxiv.org/abs/2405.19846) _Chaochen Gao, Xing Wu, Qi Fu, Songlin Hu._ Arxiv 2024.

48. [**Position Coupling: Improving Length Generalization of Arithmetic Transformers Using Task Structure.**](https://openreview.net/forum?id=5cIRdGM1uG) _Hanseul Cho, Jaeyoung Cha, Pranjal Awasthi, Srinadh Bhojanapalli, Anupam Gupta, Chulhee Yun._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HanseulJo/position-coupling)](https://github.com/HanseulJo/position-coupling)

49. [**LongSkywork: A Training Recipe for Efficiently Extending Context Length in Large Language Models.**](https://arxiv.org/abs/2406.00605) _Liang Zhao, Tianwen Wei, Liang Zeng, Cheng Cheng, Liu Yang, Peng Cheng, Lijie Wang, Chenxia Li, Xuejie Wu, Bo Zhu, Yimeng Gan, Rui Hu, Shuicheng Yan, Han Fang, Yahui Zhou._ Arxiv 2024.

50. [**Explicitly Encoding Structural Symmetry is Key to Length Generalization in Arithmetic Tasks.**](https://arxiv.org/abs/2406.01895) _Mahdi Sabbaghi, George Pappas, Hamed Hassani, Surbhi Goel._ Arxiv 2024.

51. [**An Efficient Recipe for Long Context Extension via Middle-Focused Positional Encoding.**](https://arxiv.org/abs/2406.07138) _Tong Wu, Yanpeng Zhao, Zilong Zheng._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/cream)](https://github.com/bigai-nlco/cream)

52. [**3D-RPE: Enhancing Long-Context Modeling Through 3D Rotary Position Encoding.**](https://arxiv.org/abs/2406.09897) _Xindian Ma, Wenyuan Liu, Peng Zhang, Nan Xu._ Arxiv 2024.

53. [**Mixture of In-Context Experts Enhance LLMs' Long Context Awareness.**](https://arxiv.org/abs/2406.19598) _Hongzhan Lin, Ang Lv, Yuhan Chen, Chen Zhu, Yang Song, Hengshu Zhu, Rui Yan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/p1nksnow/MoICE)](https://github.com/p1nksnow/MoICE)

54. [**Human-like Episodic Memory for Infinite Context LLMs.**](https://arxiv.org/abs/2407.09450) _Zafeirios Fountas, Martin A Benfeghoul, Adnan Oomerjee, Fenia Christopoulou, Gerasimos Lampouras, Haitham Bou-Ammar, Jun Wang._ Arxiv 2024.

55. [**Scaling Granite Code Models to 128K Context.**](https://arxiv.org/abs/2407.13739) _Matt Stallone, Vaibhav Saxena, Leonid Karlinsky, Bridget McGinn, Tim Bula, Mayank Mishra, Adriana Meza Soria, Gaoyuan Zhang, Aditya Prasad, Yikang Shen, Saptha Surendran, Shanmukha Guttula, Hima Patel, Parameswaran Selvam, Xuan-Hong Dang, Yan Koyfman, Atin Sood, Rogerio Feris, Nirmit Desai, David D. Cox, Ruchir Puri, Rameswar Panda._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ibm-granite/granite-code-models)](https://github.com/ibm-granite/granite-code-models)

56. [**ChatQA 2: Bridging the Gap to Proprietary LLMs in Long Context and RAG Capabilities.**](https://arxiv.org/abs/2407.14482) _Peng Xu, Wei Ping, Xianchao Wu, Zihan Liu, Mohammad Shoeybi, Bryan Catanzaro._ Arxiv 2024.

57. [**Efficient Solutions For An Intriguing Failure of LLMs: Long Context Window Does Not Mean LLMs Can Analyze Long Sequences Flawlessly.**](https://arxiv.org/abs/2408.01866) _Peyman Hosseini, Ignacio Castro, Iacopo Ghinassi, Matthew Purver._ Arxiv 2024.

58. [**FocusLLM: Scaling LLM's Context by Parallel Decoding.**](https://arxiv.org/abs/2408.11745) _Zhenyu Li, Yike Zhang, Tengyu Pan, Yutao Sun, Zhichao Duan, Junjie Fang, Rong Han, Zixuan Wang, Jianyong Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/leezythu/FocusLLM)](https://github.com/leezythu/FocusLLM)

59. [**LongRecipe: Recipe for Efficient Long Context Generalization in Large Language Models.**](https://arxiv.org/abs/2409.00509) _Zhiyuan Hu, Yuliang Liu, Jinman Zhao, Suyuchen Wang, Yan Wang, Wei Shen, Qing Gu, Anh Tuan Luu, See-Kiong Ng, Zhiwei Jiang, Bryan Hooi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zhiyuanhubj/LongRecipe)](https://github.com/zhiyuanhubj/LongRecipe)

60. [**E2LLM: Encoder Elongated Large Language Models for Long-Context Understanding and Reasoning.**](https://arxiv.org/abs/2409.06679) _Zihan Liao, Jun Wang, Hang Yu, Lingxiao Wei, Jianguo Li, Jun Wang, Wei Zhang._ Arxiv 2024.

61. [**Untie the Knots: An Efficient Data Augmentation Strategy for Long-Context Pre-Training in Language Models.**](https://arxiv.org/abs/2409.04774) _Junfeng Tian, Da Zheng, Yang Cheng, Rui Wang, Colin Zhang, Debing Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/rgtjf/Untie-the-Knots)](https://github.com/rgtjf/Untie-the-Knots)

62. [**PEAR: Position-Embedding-Agnostic Attention Re-weighting Enhances Retrieval-Augmented Generation with Zero Inference Overhead.**](https://arxiv.org/abs/2409.19745) _Tao Tan, Yining Qian, Ang Lv, Hongzhan Lin, Songhao Wu, Yongbo Wang, Feng Wang, Jingtong Wu, Xin Lu, Rui Yan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TTArch/PEAR-RAG)](https://github.com/TTArch/PEAR-RAG)

63. [**Efficient Long-range Language Modeling with Self-supervised Causal Retrieval.**](https://arxiv.org/abs/2410.01651) _Xiang Hu, Zhihao Teng, Wei Wu, Kewei Tu._ Arxiv 2024.

64. [**A Little Goes a Long Way: Efficient Long Context Training and Inference with Partial Contexts.**](https://arxiv.org/abs/2410.01485) _Suyu Ge, Xihui Lin, Yunan Zhang, Jiawei Han, Hao Peng._ Arxiv 2024.

65. [**Extending Context Window of Large Language Models from a Distributional Perspective.**](https://arxiv.org/abs/2410.01490) _Yingsheng Wu, Yuxuan Gu, Xiaocheng Feng, Weihong Zhong, Dongliang Xu, Qing Yang, Hongtao Liu, Bing Qin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/1180301012/DPRoPE)](https://github.com/1180301012/DPRoPE)

66. [**How to Train Long-Context Language Models (Effectively).**](https://arxiv.org/abs/2410.02660) _Tianyu Gao, Alexander Wettig, Howard Yen, Danqi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/ProLong)](https://github.com/princeton-nlp/ProLong)

67. [**Differential Transformer.**](https://arxiv.org/abs/2410.05258) _Tianzhu Ye, Li Dong, Yuqing Xia, Yutao Sun, Yi Zhu, Gao Huang, Furu Wei._ Arxiv 2024.

68. [**DAPE V2: Process Attention Score as Feature Map for Length Extrapolation.**](https://arxiv.org/abs/2410.04798) _Chuanyang Zheng, Yihang Gao, Han Shi, Jing Xiong, Jiankai Sun, Jingyao Li, Minbin Huang, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE)](https://github.com/chuanyang-Zheng/DAPE)

69. [**Why Does the Effective Context Length of LLMs Fall Short?.**](https://arxiv.org/abs/2410.18745) _Chenxin An, Jun Zhang, Ming Zhong, Lei Li, Shansan Gong, Yao Luo, Jingjing Xu, Lingpeng Kong._ Arxiv 2024.

70. [**LOGO -- Long cOntext aliGnment via efficient preference Optimization.**](https://arxiv.org/abs/2410.18533) _Zecheng Tang, Zechen Sun, Juntao Li, Qiaoming Zhu, Min Zhang._ [ICML 2025]. [![GitHub Repo stars](https://img.shields.io/github/stars/ZetangForward/LCM_Stack)](https://github.com/ZetangForward/LCM_Stack)

71. [**Selecting Influential Samples for Long Context Alignment via Homologous Models' Guidance and Contextual Awareness Measurement.**](https://arxiv.org/abs/2410.15633) _Shuzheng Si, Haozhe Zhao, Gang Chen, Yunshui Li, Kangyang Luo, Chuancheng Lv, Kaikai An, Fanchao Qi, Baobao Chang, Maosong Sun._ Arxiv 2024.

72. [**Two are better than one: Context window extension with multi-grained self-injection.**](https://arxiv.org/abs/2410.19318) _Wei Han, Pan Zhou, Soujanya Poria, Shuicheng Yan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Clement25/SharedLLM)](https://github.com/Clement25/SharedLLM)

73. [**LongReward: Improving Long-context Large Language Models with AI Feedback.**](https://arxiv.org/abs/2410.21252) _Jiajie Zhang, Zhongni Hou, Xin Lv, Shulin Cao, Zhenyu Hou, Yilin Niu, Lei Hou, Yuxiao Dong, Ling Feng, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongReward)](https://github.com/THUDM/LongReward)

74. [**HoPE: A Novel Positional Encoding Without Long-Term Decay for Enhanced Context Awareness and Extrapolation.**](https://arxiv.org/abs/2410.21216) _Yuhan Chen, Ang Lv, Jian Luan, Bin Wang, Wei Liu._ Arxiv 2024.

75. [**What is Wrong with Perplexity for Long-context Language Modeling?.**](https://arxiv.org/abs/2410.23771) _Lizhe Fang, Yifei Wang, Zhaoyang Liu, Chenheng Zhang, Stefanie Jegelka, Jinyang Gao, Bolin Ding, Yisen Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/PKU-ML/LongPPL)](https://github.com/PKU-ML/LongPPL)

76. [**Circuit Complexity Bounds for RoPE-based Transformer Architecture.**](https://arxiv.org/abs/2411.07602) _Bo Chen, Xiaoyu Li, Yingyu Liang, Jiangxuan Long, Zhenmei Shi, Zhao Song._ Arxiv 2024.

77. [**Large Language Models Can Self-Improve in Long-context Reasoning.**](https://arxiv.org/abs/2411.08147) _Siheng Li, Cheng Yang, Zesen Cheng, Lemao Liu, Mo Yu, Yujiu Yang, Wai Lam._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SihengLi99/SEALONG)](https://github.com/SihengLi99/SEALONG)

78. [**Transformers Can Do Arithmetic with the Right Embeddings.**](https://openreview.net/forum?id=cBFsFt1nDW) _Sean Michael McLeish, Arpit Bansal, Alex Stein, Neel Jain, John Kirchenbauer, Brian R. Bartoldson, Bhavya Kailkhura, Abhinav Bhatele, Jonas Geiping, Avi Schwarzschild, Tom Goldstein._ NeurIPS 2024.

79. [**Arithmetic Transformers Can Length-Generalize in Both Operand Length and Count.**](https://arxiv.org/abs/2410.15787) _Hanseul Cho, Jaeyoung Cha, Srinadh Bhojanapalli, Chulhee Yun._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HanseulJo/position-coupling)](https://github.com/HanseulJo/position-coupling)

80. [**Breaking the Stage Barrier: A Novel Single-Stage Approach to Long Context Extension for Large Language Models.**](https://arxiv.org/abs/2412.07171) _Haoran Lian, Junmin Chen, Wei Huang, Yizhe Xiong, Wenping Hu, Guiguang Ding, Hui Chen, Jianwei Niu, Zijia Lin, Fuzheng Zhang, Di Zhang._ Arxiv 2024.

81. [**Attention Entropy is a Key Factor: An Analysis of Parallel Context Encoding with Full-attention-based Pre-trained Language Models.**](https://arxiv.org/abs/2412.16545) _Zhisong Zhang, Yan Wang, Xinting Huang, Tianqing Fang, Hongming Zhang, Chenlong Deng, Shuaiyi Li, Dong Yu._ Arxiv 2024.

82. [**DCIS: Efficient Length Extrapolation of LLMs via Divide-and-Conquer Scaling Factor Search.**](https://arxiv.org/abs/2412.18811) _Lei Yang, Shaoyang Xu, Deyi Xiong._ Arxiv 2024.

83. [**Adjoint sharding for very long context training of state space models.**](https://arxiv.org/abs/2501.00692) _Xingzi Xu, Amir Tavanaei, Kavosh Asadi, Karim Bouyarmane._ Arxiv 2025.

84. [**Information Entropy Invariance: Enhancing Length Extrapolation in Attention Mechanisms.**](https://arxiv.org/abs/2501.08570) _Kewei Li, Yanwen Kong, Yiping Xu, Lan Huang, Ruochi Zhang, Fengfeng Zhou._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/HT-NEKO/InfoScale)](https://github.com/HT-NEKO/InfoScale)

85. [**LeMo: Enabling LEss Token Involvement for MOre Context Fine-tuning.**](https://arxiv.org/abs/2501.09767) _Tuowei Wang, Xingyu Chen, Kun Li, Ting Cao, Ju Ren, Yaoxue Zhang._ Arxiv 2025.

86. [**NExtLong: Toward Effective Long-Context Training without Long Documents.**](https://arxiv.org/abs/2501.12766) _Chaochen Gao, Xing Wu, Zijia Lin, Debing Zhang, Songlin Hu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/caskcsg/longcontext)](https://github.com/caskcsg/longcontext/tree/main/NExtLong)

87. [**SEAL: Scaling to Emphasize Attention for Long-Context Retrieval.**](https://arxiv.org/abs/2501.15225) _Changhun Lee, Jun-gyu Jin, Younghyun Cho, Eunhyeok Park._ Arxiv 2025.

88. [**DINT Transformer.**](https://arxiv.org/abs/2501.17486) _Yueyang Cang, Yuhang Liu, Xiaoteng Zhang, Erlu Zhao, Li Shi._ Arxiv 2025.

89. [**Scalable-Softmax Is Superior for Attention.**](https://arxiv.org/abs/2501.19399) _Ken M. Nakanishi._ Arxiv 2025.

90. [**Rope to Nope and Back Again: A New Hybrid Attention Strategy.**](https://arxiv.org/abs/2501.18795) _Bowen Yang, Bharat Venkitesh, Dwarak Talupuru, Hangyu Lin, David Cairuz, Phil Blunsom, Acyr Locatelli._ Arxiv 2025.

91. [**A Training-Free Length Extrapolation Approach for LLMs: Greedy Attention Logit Interpolation (GALI).**](https://arxiv.org/abs/2502.02659) _Yan Li, Tianyi Zhang, Zechuan Li, Soyeon Caren Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AcademyCityL/GALI)](https://github.com/AcademyCityL/GALI)

92. [**LongReD: Mitigating Short-Text Degradation of Long-Context Large Language Models via Restoration Distillation.**](https://arxiv.org/abs/2502.07365) _Zican Dong, Junyi Li, Jinhao Jiang, Mingyu Xu, Wayne Xin Zhao, Bingning Wang, Weipeng Chen._ Arxiv 2025.

93. [**Unveiling Simplicities of Attention: Adaptive Long-Context Head Identification.**](https://arxiv.org/abs/2502.09647) _Konstantin Donhauser, Charles Arnal, Mohammad Pezeshki, Vivien Cabannes, David Lopez-Paz, Kartik Ahuja._ Arxiv 2025.

94. [**The Rotary Position Embedding May Cause Dimension Inefficiency in Attention Heads for Long-Distance Retrieval.**](https://arxiv.org/abs/2502.11276) _Ting-Rui Chiang, Dani Yogatama._ Arxiv 2025.

95. [**LongFaith: Enhancing Long-Context Reasoning in LLMs with Faithful Synthetic Data.**](https://arxiv.org/abs/2502.12583) _Cehao Yang, Xueyuan Lin, Chengjin Xu, Xuhui Jiang, Shengjie Ma, Aofan Liu, Hui Xiong, Jian Guo._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/IDEA-FinAI/LongFaith)](https://github.com/IDEA-FinAI/LongFaith)

96. [**LongPO: Long Context Self-Evolution of Large Language Models through Short-to-Long Preference Optimization.**](https://arxiv.org/abs/2502.13922) _Guanzheng Chen, Xin Li, Michael Qizhe Shieh, Lidong Bing._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DAMO-NLP-SG/LongPO)](https://github.com/DAMO-NLP-SG/LongPO)

97. [**ParallelComp: Parallel Long-Context Compressor for Length Extrapolation.**](https://arxiv.org/abs/2502.14317) _Jing Xiong, Jianghan Shen, Chuanyang Zheng, Zhongwei Wan, Chenyang Zhao, Chiwun Yang, Fanghua Ye, Hongxia Yang, Lingpeng Kong, Ngai Wong._ Arxiv 2025.

98. [**Generalizing From Short to Long: Effective Data Synthesis for Long-Context Instruction Tuning.**](https://arxiv.org/abs/2502.15592) _Wenhao Zhu, Pinzhen Chen, Hanxu Hu, Shujian Huang, Fei Yuan, Jiajun Chen, Alexandra Birch._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NJUNLP/context-synthesis)](https://github.com/NJUNLP/context-synthesis)

99. [**LongAttn: Selecting Long-context Training Data via Token-level Attention.**](https://arxiv.org/abs/2502.16860) _Longyun Wu, Dawei Zhu, Guangxiang Zhao, Zhuocheng Yu, Junfeng Ran, Xiangyu Wong, Lin Sun, Sujian Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Lyun0912-wu/LongAttn)](https://github.com/Lyun0912-wu/LongAttn)

100. [**WildLong: Synthesizing Realistic Long-Context Instruction Data at Scale.**](https://arxiv.org/abs/2502.16684) _Jiaxi Li, Xingxing Zhang, Xun Wang, Xiaolong Huang, Li Dong, Liang Wang, Si-Qing Chen, Wei Lu, Furu Wei._ Arxiv 2025.

101. [**Sliding Window Attention Training for Efficient Large Language Models.**](https://arxiv.org/abs/2502.18845) _Zichuan Fu, Wentao Song, Yejing Wang, Xian Wu, Yefeng Zheng, Yingying Zhang, Derong Xu, Xuetao Wei, Tong Xu, Xiangyu Zhao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Lyun0912-wu/LongAttn)](https://anonymous.4open.science/r/SWAT-attention/README.md)

102. [**LongRoPE2: Near-Lossless LLM Context Window Scaling.**](https://arxiv.org/abs/2502.20082) _Ning Shang, Li Lyna Zhang, Siyuan Wang, Gaokai Zhang, Gilsinia Lopez, Fan Yang, Weizhu Chen, Mao Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LongRoPE)](https://github.com/microsoft/LongRoPE)

103. [**ByteScale: Efficient Scaling of LLM Training with a 2048K Context Length on More Than 12,000 GPUs.**](https://arxiv.org/abs/2502.21231) _Hao Ge, Junda Feng, Qi Huang, Fangcheng Fu, Xiaonan Nie, Lei Zuo, Haibin Lin, Bin Cui, Xin Liu._ Arxiv 2025.

104. [**Pause-Tuning for Long-Context Comprehension: A Lightweight Approach to LLM Attention Recalibration.**](https://arxiv.org/abs/2502.20405) _James Begin, Namit Agrawal, Eshan Singh, Yicheng Fu, Sean O'Brien, Vasu Sharma, Kevin Zhu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LongRoPE)](https://anonymous.4open.science/r/LITM-PauseTokens-7357)

105. [**LADM: Long-context Training Data Selection with Attention-based Dependency Measurement for LLMs.**](https://arxiv.org/abs/2503.02502) _Jianghao Chen, Junhong Wu, Yangyifan Xu, Jiajun Zhang._ Arxiv 2025.

106. [**Forgetting Transformer: Softmax Attention with a Forget Gate.**](https://arxiv.org/abs/2503.02130) _Zhixuan Lin, Evgenii Nikishin, Xu Owen He, Aaron Courville._ ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zhixuan-lin/forgetting-transformer)](https://github.com/zhixuan-lin/forgetting-transformer)

107. [**Layer-Specific Scaling of Positional Encodings for Superior Long-Context Modeling.**](https://arxiv.org/abs/2503.04355) _Zhenghua Wang, Yiran Ding, Changze Lv, Zhibo Xu, Tianlong Li, Tianyuan Shi, Xiaoqing Zheng, Xuanjing Huang._ Arxiv 2025.

108. [**Token Weighting for Long-Range Language Modeling.**](https://arxiv.org/abs/2503.09202) _Falko Helm, Nico Daheim, Iryna Gurevych._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UKPLab/naacl2025-token-weighting)](https://github.com/UKPLab/naacl2025-token-weighting)

109. [**From 128K to 4M: Efficient Training of Ultra-Long Context Large Language Models.**](https://arxiv.org/abs/2504.06214) _Chejian Xu, Wei Ping, Peng Xu, Zihan Liu, Boxin Wang, Mohammad Shoeybi, Bo Li, Bryan Catanzaro._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ultralong.github.io/)

110. [**SWAN-GPT: An Efficient and Scalable Approach for Long-Context Language Modeling.**](https://arxiv.org/abs/2504.08719) _Krishna C. Puvvada, Faisal Ladhak, Santiago Akle Serrano, Cheng-Ping Hsieh, Shantanu Acharya, Somshubra Majumdar, Fei Jia, Samuel Kriman, Simeng Sun, Dima Rekesh, Boris Ginsburg._ Arxiv 2025.

111. [**Scaling Instruction-Tuned LLMs to Million-Token Contexts via Hierarchical Synthetic Data Generation.**](https://arxiv.org/abs/2504.12637) _Linda He, Jue Wang, Maurice Weber, Shang Zhu, Ben Athiwaratkun, Ce Zhang._ Arxiv 2025.

112. [**Effective Length Extrapolation via Dimension-Wise Positional Embeddings Manipulation.**](https://arxiv.org/abs/2504.18857) _Yi Lu, Wanxu Zhao, Xin Zhou, Chenxin An, Chenglong Wang, Shuo Li, Yuming Yang, Jun Zhao, Tao Ji, Tao Gui, Qi Zhang, Xuanjing Huang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LuLuLuyi/DPE)](https://github.com/LuLuLuyi/DPE)

113. [**SELF: Self-Extend the Context Length With Logistic Growth Function.**](https://arxiv.org/abs/2505.17296) _Phat Thanh Dang, Saahil Thoppay, Wang Yang, Qifan Wang, Vipin Chaudhary, Xiaotian Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/alexeipc/SELF-LLM)](https://github.com/alexeipc/SELF-LLM)

114. [**Hierarchical Context Merging: Better Long Context Understanding for Pre-trained LLMs.**](https://arxiv.org/abs/2404.10308) _Woomin Song, Seunghyuk Oh, Sangwoo Mo, Jaehyung Kim, Sukmin Yun, Jung-Woo Ha, Jinwoo Shin._ ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alinlab/HOMER)](https://github.com/alinlab/HOMER)

115. [**Compress, Gather, and Recompute: REFORMing Long-Context Processing in Transformers.**](https://arxiv.org/abs/2506.01215) _Woomin Song, Sai Muralidhar Jayanthi, Srikanth Ronanki, Kanthashree Mysore Sathyendra, Jinwoo Shin, Aram Galstyan, Shubham Katiyar, Sravan Babu Bodapati._ Arxiv 2025.

### 6. Long Term Memory

1. [**Unleashing Infinite-Length Input Capacity for Large-scale Language Models with Self-Controlled Memory System.**](https://arxiv.org/abs/2304.13343) _Xinnian Liang, Bing Wang, Hui Huang, Shuangzhi Wu, Peihao Wu, Lu Lu, Zejun Ma, Zhoujun Li._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/wbbeyourself/SCM4LLMs)](https://github.com/wbbeyourself/SCM4LLMs)

2. [**MemoryBank: Enhancing Large Language Models with Long-Term Memory.**](https://arxiv.org/abs/2305.10250) _Wanjun Zhong, Lianghong Guo, Qiqi Gao, He Ye, Yanlin Wang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/zhongwanjun/MemoryBank-SiliconFriend)](https://github.com/zhongwanjun/MemoryBank-SiliconFriend)

3. [**Improve Long-term Memory Learning Through Rescaling the Error Temporally.**](https://arxiv.org/abs/2307.11462) _Shida Wang, Zhanglu Yan._ Arxiv 2023.

4. [**Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models.**](https://arxiv.org/abs/2308.15022) _Qingyue Wang, Liang Ding, Yanan Cao, Zhiliang Tian, Shi Wang, Dacheng Tao, Li Guo._ Arxiv 2023.

5. [**Empowering Working Memory for Large Language Model Agents.**](https://arxiv.org/abs/2312.17259) _Jing Guo, Nan Li, Jianchuan Qi, Hang Yang, Ruiqiao Li, Yuzhen Feng, Si Zhang, Ming Xu._ Arxiv 2024.

6. [**Evolving Large Language Model Assistant with Long-Term Conditional Memory.**](https://arxiv.org/abs/2312.17257) _Ruifeng Yuan, Shichao Sun, Zili Wang, Ziqiang Cao, Wenjie Li._ Arxiv 2024.

7. [**Commonsense-augmented Memory Construction and Management in Long-term Conversations via Context-aware Persona Refinement.**](https://arxiv.org/abs/2401.14215) _Hana Kim, Kai Tzu-iunn Ong, Seoyeon Kim, Dongha Lee, Jinyoung Yeo._ Arxiv 2024.

8. [**A Human-Inspired Reading Agent with Gist Memory of Very Long Contexts.**](https://arxiv.org/abs/2402.09727v1) _Kuang-Huei Lee, Xinyun Chen, Hiroki Furuta, John Canny, Ian Fischer._ Arxiv 2024.

9. [**Steering Conversational Large Language Models for Long Emotional Support Conversations.**](https://arxiv.org/abs/2402.10453) _Navid Madani, Sougata Saha, Rohini Srihari._ Arxiv 2024.

10. [**SPAR: Personalized Content-Based Recommendation via Long Engagement Attention.**](https://arxiv.org/abs/2402.10555) _Chiyu Zhang, Yifei Sun, Jun Chen, Jie Lei, Muhammad Abdul-Mageed, Sinong Wang, Rong Jin, Sem Park, Ning Yao, Bo Long._ Arxiv 2024.

11. [**Compress to Impress: Unleashing the Potential of Compressive Memory in Real-World Long-Term Conversations.**](https://arxiv.org/abs/2402.11975) _Nuo Chen, Hongguang Li, Juhua Huang, Baoyuan Wang, Jia Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nuochenpku/COMEDY)](https://github.com/nuochenpku/COMEDY)

12. [**StreamingDialogue: Prolonged Dialogue Learning via Long Context Compression with Minimal Losses.**](https://arxiv.org/abs/2403.08312) _Jia-Nan Li, Quan Tu, Cunli Mao, Zhengtao Yu, Ji-Rong Wen, Rui Yan._ Arxiv 2024.

13. [**Prompts As Programs: A Structure-Aware Approach to Efficient Compile-Time Prompt Optimization.**](https://arxiv.org/abs/2404.02319) _Tobias Schnabel, Jennifer Neville._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/sammo)](https://github.com/microsoft/sammo)

14. [**HMT: Hierarchical Memory Transformer for Long Context Language Processing.**](https://arxiv.org/abs/2405.06067) _Tobias Schnabel, Jennifer Neville._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OswaldHe/HMT-pytorch)](https://github.com/OswaldHe/HMT-pytorch)

15. [**SirLLM: Streaming Infinite Retentive LLM.**](https://arxiv.org/abs/2405.12528) _Yao Yao, Zuchao Li, Hai Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Zoeyyao27/SirLLM)](https://github.com/Zoeyyao27/SirLLM)

16. [**Toward Conversational Agents with Context and Time Sensitive Long-term Memory.**](https://arxiv.org/abs/2406.00057) _Nick Alonso, Tomás Figliolia, Anthony Ndirango, Beren Millidge._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Zyphra/TemporalMemoryDataset)](https://github.com/Zyphra/TemporalMemoryDataset)

17. [**Position Debiasing Fine-Tuning for Causal Perception in Long-Term Dialogue.**](https://arxiv.org/abs/2406.02002) _Shixuan Fan, Wei Wei, Wendi Li, Xian-Ling Mao, Wenfeng Xie, Dangyang Chen._ Arxiv 2024.

18. [**Enhancing Long-Term Memory using Hierarchical Aggregate Tree for Retrieval Augmented Generation.**](https://arxiv.org/abs/2406.06124) _Aadharsh Aadhithya A, Sachin Kumar S, Soman K.P._ Arxiv 2024.

19. [**Suri: Multi-constraint Instruction Following for Long-form Text Generation.**](https://arxiv.org/abs/2406.19371) _Chau Minh Pham, Simeng Sun, Mohit Iyyer._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chtmp223/suri)](https://github.com/chtmp223/suri)

20. [**HiAgent: Hierarchical Working Memory Management for Solving Long-Horizon Agent Tasks with Large Language Model.**](https://arxiv.org/abs/2408.09559) _Mengkang Hu, Tianxing Chen, Qiguang Chen, Yao Mu, Wenqi Shao, Ping Luo._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HiAgent2024/HiAgent)](https://github.com/HiAgent2024/HiAgent)

21. [**CreDes: Causal Reasoning Enhancement and Dual-End Searching for Solving Long-Range Reasoning Problems using LLMs.**](https://arxiv.org/abs/2410.01696) _Kangsheng Wang, Xiao Zhang, Hao Liu, Songde Han, Huimin Ma, Tianyu Hu._ Arxiv 2024.

22. [**CarMem: Enhancing Long-Term Memory in LLM Voice Assistants through Category-Bounding.**](https://arxiv.org/abs/2501.09645) _Johannes Kirmayr, Lukas Stappen, Phillip Schneider, Florian Matthes, Elisabeth André._ COLING 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/johanneskirmayr/CarMem)](https://github.com/johanneskirmayr/CarMem)

23. [**M+: Extending MemoryLLM with Scalable Long-Term Memory.**](https://arxiv.org/abs/2502.00592) _Yu Wang, Dmitry Krotov, Yuanzhe Hu, Yifan Gao, Wangchunshu Zhou, Julian McAuley, Dan Gutfreund, Rogerio Feris, Zexue He._ Arxiv 2025.

24. [**LM2: Large Memory Models.**](https://arxiv.org/abs/2502.06049) _Jikun Kang, Wenqi Wu, Filippos Christianos, Alex J. Chan, Fraser Greenlee, George Thomas, Marvin Purtorab, Andy Toulis._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/convergence-ai/lm2)](https://github.com/convergence-ai/lm2)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://convergence.ai/)

25. [**Position: Episodic Memory is the Missing Piece for Long-Term LLM Agents.**](https://arxiv.org/abs/2502.06975) _Mathis Pink, Qinyuan Wu, Vy Ai Vo, Javier Turek, Jianing Mu, Alexander Huth, Mariya Toneva._ Arxiv 2025.

26. [**MEMORYLLM: Towards Self-Updatable Large Language Models.**](https://arxiv.org/abs/2402.04624) _Yu Wang, Yifan Gao, Xiusi Chen, Haoming Jiang, Shiyang Li, Jingfeng Yang, Qingyu Yin, Zheng Li, Xian Li, Bing Yin, Jingbo Shang, Julian McAuley._ ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/wangyu-ustc/MemoryLLM)](https://github.com/wangyu-ustc/MemoryLLM)

27. [**Towards LifeSpan Cognitive Systems.**](https://arxiv.org/abs/2409.13265) _Yu Wang, Chi Han, Tongtong Wu, Xiaoxin He, Wangchunshu Zhou, Nafis Sadeq, Xiusi Chen, Zexue He, Wei Wang, Gholamreza Haffari, Heng Ji, Julian McAuley._ TMLR 2024.

28. [**EpMAN: Episodic Memory AttentioN for Generalizing to Longer Contexts.**](https://arxiv.org/abs/2502.14280) _Subhajit Chaudhury, Payel Das, Sarathkrishna Swaminathan, Georgios Kollias, Elliot Nelson, Khushbu Pahwa, Tejaswini Pedapati, Igor Melnyk, Matthew Riemer._ Arxiv 2025.

29. [**Can Memory-Augmented Language Models Generalize on Reasoning-in-a-Haystack Tasks?.**](https://arxiv.org/abs/2503.07903) _Payel Das, Ching-Yun Ko, Sihui Dai, Georgios Kollias, Subhajit Chaudhury, Aurelie Lozano._ Arxiv 2025.

30. [**InfiniteICL: Breaking the Limit of Context Window Size via Long Short-term Memory Transformation.**](https://arxiv.org/abs/2504.01707) _Bowen Cao, Deng Cai, Wai Lam._ Arxiv 2025.

31. [**Cognitive Memory in Large Language Models.**](https://arxiv.org/abs/2504.02441) _Lianlei Shan, Shixian Luo, Zezhou Zhu, Yu Yuan, Yong Wu._ Arxiv 2025.

### 7. RAG and ICL

1. [**Walking Down the Memory Maze: Beyond Context Limit through Interactive Reading.**](https://arxiv.org/abs/2310.05029) _Howard Chen, Ramakanth Pasunuru, Jason Weston, Asli Celikyilmaz._ Arxiv 2023.

2. [**Attendre: Wait To Attend By Retrieval With Evicted Queries in Memory-Based Transformers for Long Context Processing.**](https://arxiv.org/abs/2401.04881) _Zi Yang, Nan Hua._ Arxiv 2024.

3. [**BGE Landmark Embedding: A Chunking-Free Embedding Method For Retrieval Augmented Long-Context Large Language Models.**](https://arxiv.org/abs/2402.11573) _Kun Luo, Zheng Liu, Shitao Xiao, Kang Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

4. [**Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity.**](https://arxiv.org/abs/2403.14403) _Soyeong Jeong, Jinheon Baek, Sukmin Cho, Sung Ju Hwang, Jong C. Park._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/starsuzi/Adaptive-RAG)](https://github.com/starsuzi/Adaptive-RAG)

5. [**RQ-RAG: Learning to Refine Queries for Retrieval Augmented Generation.**](https://arxiv.org/abs/2404.00610) _Chi-Min Chan, Chunpu Xu, Ruibin Yuan, Hongyin Luo, Wei Xue, Yike Guo, Jie Fu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chanchimin/RQ-RAG)](https://github.com/chanchimin/RQ-RAG)

6. [**Improving Retrieval Augmented Open-Domain Question-Answering with Vectorized Contexts.**](https://arxiv.org/abs/2404.02022) _Zhuo Chen, Xinyu Wang, Yong Jiang, Pengjun Xie, Fei Huang, Kewei Tu._ Arxiv 2024.

7. [**Superposition Prompting: Improving and Accelerating Retrieval-Augmented Generation.**](https://arxiv.org/abs/2404.06910) _Thomas Merth, Qichen Fu, Mohammad Rastegari, Mahyar Najibi._ Arxiv 2024.

8. [**Multi-view Content-aware Indexing for Long Document Retrieval.**](https://arxiv.org/abs/2404.15103) _Kuicai Dong, Derrick Goh Xin Deik, Yi Quan Lee, Hao Zhang, Xiangyang Li, Cong Zhang, Yong Liu._ Arxiv 2024.

9. [**Retrieval Head Mechanistically Explains Long-Context Factuality.**](https://arxiv.org/abs/2404.15574) _Wenhao Wu, Yizhong Wang, Guangxuan Xiao, Hao Peng, Yao Fu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nightdessert/Retrieval_Head)](https://github.com/nightdessert/Retrieval_Head)

10. [**FlashBack:Efficient Retrieval-Augmented Language Modeling for Long Context Inference.**](https://arxiv.org/abs/2405.04065) _Runheng Liu, Xingchen Xiao, Heyan Huang, Zewen Chi, Zhijing Wu._ Arxiv 2024.

11. [**Feature-Adaptive and Data-Scalable In-Context Learning.**](https://arxiv.org/abs/2405.10738) _Jiahao Li, Quan Wang, Licheng Zhang, Guoqing Jin, Zhendong Mao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/jiahaozhenbang/FADS-ICL)](https://github.com/jiahaozhenbang/FADS-ICL)

12. [**KG-RAG: Bridging the Gap Between Knowledge and Creativity.**](https://arxiv.org/abs/2405.12035) _Diego Sanmartin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dsanmart/KG-RAG)](https://github.com/dsanmart/KG-RAG)

13. [**HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models.**](https://arxiv.org/abs/2405.14831) _Bernal Jiménez Gutiérrez, Yiheng Shu, Yu Gu, Michihiro Yasunaga, Yu Su._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OSU-NLP-Group/HippoRAG)](https://github.com/OSU-NLP-Group/HippoRAG)

14. [**Implicit In-context Learning.**](https://arxiv.org/abs/2405.14660) _Zhuowei Li, Zihao Xu, Ligong Han, Yunhe Gao, Song Wen, Di Liu, Hao Wang, Dimitris N. Metaxas._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/LzVv123456/I2CL)](https://github.com/LzVv123456/I2CL)

15. [**Are Long-LLMs A Necessity For Long-Context Tasks?.**](https://arxiv.org/abs/2405.15318) _Hongjin Qian, Zheng Liu, Peitian Zhang, Kelong Mao, Yujia Zhou, Xu Chen, Zhicheng Dou._ Arxiv 2024.

16. [**Accelerating Inference of Retrieval-Augmented Generation via Sparse Context Selection.**](https://arxiv.org/abs/2405.16178) _Yun Zhu, Jia-Chen Gu, Caitlin Sikora, Ho Ko, Yinxiao Liu, Chu-Cheng Lin, Lei Shu, Liangchen Luo, Lei Meng, Bang Liu, Jindong Chen._ Arxiv 2024.

17. [**Is In-Context Learning Sufficient for Instruction Following in LLMs?.**](https://arxiv.org/abs/2405.19874) _Hao Zhao, Maksym Andriushchenko, Francesco Croce, Nicolas Flammarion._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/tml-epfl/icl-alignment)](https://github.com/tml-epfl/icl-alignment)

18. [**FragRel: Exploiting Fragment-level Relations in the External Memory of Large Language Models.**](https://arxiv.org/abs/2406.03092) _Xihang Yue, Linchao Zhu, Yi Yang._ Arxiv 2024.

19. [**Multi-Head RAG: Solving Multi-Aspect Problems with LLMs.**](https://arxiv.org/abs/2406.05085) _Maciej Besta, Ales Kubicek, Roman Niggli, Robert Gerstenberger, Lucas Weitzendorf, Mingyuan Chi, Patrick Iff, Joanna Gajda, Piotr Nyczyk, Jürgen Müller, Hubert Niewiadomski, Marcin Chrapek, Michał Podstawski, Torsten Hoefler._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/spcl/MRAG)](https://github.com/spcl/MRAG)

20. [**Demonstration Notebook: Finding the Most Suited In-Context Learning Example from Interactions.**](https://arxiv.org/abs/2406.10878) _Yiming Tang, Bin Dong._ Arxiv 2024.

21. [**Retrieval Meets Reasoning: Dynamic In-Context Editing for Long-Text Understanding.**](https://arxiv.org/abs/2406.12331) _Weizhi Fei, Xueyan Niu, Guoqing Xie, Yanhua Zhang, Bo Bai, Lei Deng, Wei Han._ Arxiv 2024.

22. [**FoRAG: Factuality-optimized Retrieval Augmented Generation for Web-enhanced Long-form Question Answering.**](https://arxiv.org/abs/2406.13779) _Tianchi Cai, Zhiwen Tan, Xierui Song, Tao Sun, Jiyan Jiang, Yunqi Xu, Yinger Zhang, Jinjie Gu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/forag)

23. [**Can Few-shot Work in Long-Context? Recycling the Context to Generate Demonstrations.**](https://arxiv.org/abs/2406.13632) _Arie Cattan, Alon Jacovi, Alex Fabrikant, Jonathan Herzig, Roee Aharoni, Hannah Rashkin, Dror Marcus, Avinatan Hassidim, Yossi Matias, Idan Szpektor, Avi Caciularu._ Arxiv 2024.

24. [**LongRAG: Enhancing Retrieval-Augmented Generation with Long-context LLMs.**](https://arxiv.org/abs/2406.15319) _Ziyan Jiang, Xueguang Ma, Wenhu Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/LongRAG)](https://github.com/TIGER-AI-Lab/LongRAG)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://tiger-ai-lab.github.io/LongRAG/)

25. [**Multimodal Task Vectors Enable Many-Shot Multimodal In-Context Learning.**](https://arxiv.org/abs/2406.15334) _Brandon Huang, Chancharik Mitra, Assaf Arbelle, Leonid Karlinsky, Trevor Darrell, Roei Herzig._ Arxiv 2024.

26. [**From Artificial Needles to Real Haystacks: Improving Retrieval Capabilities in LLMs by Finetuning on Synthetic Data.**](https://arxiv.org/abs/2406.19292) _Zheyang Xiong, Vasilis Papageorgiou, Kangwook Lee, Dimitris Papailiopoulos._ Arxiv 2024.

27. [**Memory3: Language Modeling with Explicit Memory.**](https://arxiv.org/abs/2407.01178) _Hongkang Yang, Zehao Lin, Wenjin Wang, Hao Wu, Zhiyu Li, Bo Tang, Wenqiang Wei, Jinbo Wang, Zeyun Tang, Shichao Song, Chenyang Xi, Yu Yu, Kai Chen, Feiyu Xiong, Linpeng Tang, Weinan E._ Arxiv 2024.

28. [**Speculative RAG: Enhancing Retrieval Augmented Generation through Drafting.**](https://arxiv.org/abs/2407.08223) _Zilong Wang, Zifeng Wang, Long Le, Huaixiu Steven Zheng, Swaroop Mishra, Vincent Perot, Yuwei Zhang, Anush Mattapalli, Ankur Taly, Jingbo Shang, Chen-Yu Lee, Tomas Pfister._ Arxiv 2024.

29. [**Retrieve, Summarize, Plan: Advancing Multi-hop Question Answering with an Iterative Approach.**](https://arxiv.org/abs/2407.13101) _Zhouyu Jiang, Mengshu Sun, Lei Liang, Zhiqiang Zhang._ Arxiv 2024.

30. [**R^2AG: Incorporating Retrieval Information into Retrieval Augmented Generation.**](https://arxiv.org/abs/2406.13249) _Fuda Ye, Shuangyin Li, Yongqi Zhang, Lei Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yefd/RRAG)](https://github.com/yefd/RRAG)

31. [**Making Long-Context Language Models Better Multi-Hop Reasoners.**](https://arxiv.org/abs/2408.03246) _Yanyang Li, Shuo Liang, Michael R. Lyu, Liwei Wang._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/LaVi-Lab/LongContextReasoner)](https://github.com/LaVi-Lab/LongContextReasoner)

32. [**Large Language Models Know What Makes Exemplary Contexts.**](https://arxiv.org/abs/2408.07505) _Quanyu Long, Jianda Chen, Wenya Wang, Sinno Jialin Pan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ruyue0001/RL-ICL)](https://github.com/ruyue0001/RL-ICL)

33. [**RAGChecker: A Fine-grained Framework for Diagnosing Retrieval-Augmented Generation.**](https://arxiv.org/abs/2408.08067) _Dongyu Ru, Lin Qiu, Xiangkun Hu, Tianhang Zhang, Peng Shi, Shuaichen Chang, Cheng Jiayang, Cunxiang Wang, Shichao Sun, Huanyu Li, Zizhao Zhang, Binjie Wang, Jiarong Jiang, Tong He, Zhiguo Wang, Pengfei Liu, Yue Zhang, Zheng Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/amazon-science/RAGChecker)](https://github.com/amazon-science/RAGChecker)

34. [**Writing in the Margins: Better Inference Pattern for Long Context Retrieval.**](https://arxiv.org/abs/2408.14906) _Melisa Russak, Umar Jamil, Christopher Bryant, Kiran Kamble, Axel Magnuson, Mateusz Russak, Waseem AlShikh._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/writer/writing-in-the-margins)](https://github.com/writer/writing-in-the-margins)

35. [**MemLong: Memory-Augmented Retrieval for Long Text Modeling.**](https://arxiv.org/abs/2408.16967) _Weijie Liu, Zecheng Tang, Juntao Li, Kehai Chen, Min Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Bui1dMySea/MemLong)](https://github.com/Bui1dMySea/MemLong)

36. [**In Defense of RAG in the Era of Long-Context Language Models.**](https://arxiv.org/abs/2409.01666) _Tan Yu, Anbang Xu, Rama Akkiraju._ Arxiv 2024.

37. [**MemoRAG: Moving towards Next-Gen RAG Via Memory-Inspired Knowledge Discovery.**](https://arxiv.org/abs/2409.05591) _Hongjin Qian, Peitian Zhang, Zheng Liu, Kelong Mao, Zhicheng Dou._ Arxiv 2024.

38. [**You Only Use Reactive Attention Slice For Long Context Retrieval.**](https://arxiv.org/abs/2409.13695) _Yun Joon Soh, Hanxian Huang, Yuandong Tian, Jishen Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yjsoh/youra)](https://github.com/yjsoh/youra)

39. [**SMART-RAG: Selection using Determinantal Matrices for Augmented Retrieval.**](https://arxiv.org/abs/2409.13992) _Jiatao Li, Xinyu Hu, Xiaojun Wan._ Arxiv 2024.

40. [**Lighter And Better: Towards Flexible Context Adaptation For Retrieval Augmented Generation.**](https://arxiv.org/abs/2409.15699) _Zheng Liu, Chenyuan Wu, Ninglu Shao, Shitao Xiao, Chaozhuo Li, Defu Lian._ CIKM 2024.

41. [**Bridging Context Gaps: Leveraging Coreference Resolution for Long Contextual Understanding.**](https://arxiv.org/abs/2410.01671) _Yanming Liu, Xinyue Peng, Jiannan Cao, Shi Bo, Yanxin Shen, Xuhong Zhang, Sheng Cheng, Xun Wang, Jianwei Yin, Tianyu Du._ Arxiv 2024.

42. [**ALR2: A Retrieve-then-Reason Framework for Long-context Question Answering.**](https://arxiv.org/abs/2410.03227) _Huayang Li, Pat Verga, Priyanka Sen, Bowen Yang, Vijay Viswanathan, Patrick Lewis, Taro Watanabe, Yixuan Su._ Arxiv 2024.

43. [**Inference Scaling for Long-Context Retrieval Augmented Generation.**](https://arxiv.org/abs/2410.04343) _Zhenrui Yue, Honglei Zhuang, Aijun Bai, Kai Hui, Rolf Jagerman, Hansi Zeng, Zhen Qin, Dong Wang, Xuanhui Wang, Michael Bendersky._ Arxiv 2024.

44. [**GARLIC: LLM-Guided Dynamic Progress Control with Hierarchical Weighted Graph for Long Document QA.**](https://arxiv.org/abs/2410.04790) _Xinyu Wang, Yanzheng Xiang, Lin Gui, Yulan He._ Arxiv 2024.

45. [**Long-Context LLMs Meet RAG: Overcoming Challenges for Long Inputs in RAG.**](https://arxiv.org/abs/2410.05983) _Bowen Jin, Jinsung Yoon, Jiawei Han, Sercan O. Arik._ Arxiv 2024.

46. [**Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts for Large Language Models.**](https://arxiv.org/abs/2410.07176) _Fei Wang, Xingchen Wan, Ruoxi Sun, Jiefeng Chen, Sercan Ö. Arık._ Arxiv 2024.

47. [**SEGMENT+: Long Text Processing with Short-Context Language Models.**](https://arxiv.org/abs/2410.06519) _Wei Shi, Shuang Li, Kerun Yu, Jinglei Chen, Zujie Liang, Xinhui Wu, Yuxi Qian, Feng Wei, Bo Zheng, Jiaqing Liang, Jiangjie Chen, Yanghua Xiao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WeiShi-9/segmentplus)](https://github.com/WeiShi-9/segmentplus)

48. [**Graph of Records: Boosting Retrieval Augmented Generation for Long-context Summarization with Graphs.**](https://arxiv.org/abs/2410.11001) _Haozhen Zhang, Tao Feng, Jiaxuan You._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ulab-uiuc/GoR)](https://github.com/ulab-uiuc/GoR)

49. [**ChuLo: Chunk-Level Key Information Representation for Long Document Processing.**](https://arxiv.org/abs/2410.11119) _Yan Li, Caren Han, Yue Dai, Feiqi Cao._ Arxiv 2024.

50. [**TurboRAG: Accelerating Retrieval-Augmented Generation with Precomputed KV Caches for Chunked Text.**](https://arxiv.org/abs/2410.07590) _Songshuo Lu, Hua Wang, Yutian Rong, Zhi Chen, Yaohua Tang._ Arxiv 2024.

51. [**LLM×MapReduce: Simplified Long-Sequence Processing using Large Language Models.**](https://arxiv.org/abs/2410.09342) _Zihan Zhou, Chong Li, Xinyi Chen, Shuo Wang, Yu Chao, Zhili Li, Haoyu Wang, Rongqiao An, Qi Shi, Zhixing Tan, Xu Han, Xiaodong Shi, Zhiyuan Liu, Maosong Sun._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/LLMxMapReduce)](https://github.com/thunlp/LLMxMapReduce)

52. [**Enhancing Long Context Performance in LLMs Through Inner Loop Query Mechanism.**](https://arxiv.org/abs/2410.12859) _Yimin Tang, Yurong Xu, Ning Yan, Masood Mortazavi._ NeurIPS 2024.

53. [**LongRAG: A Dual-Perspective Retrieval-Augmented Generation Paradigm for Long-Context Question Answering.**](https://arxiv.org/abs/2410.18050) _Qingfei Zhao, Ruobing Wang, Yukuo Cen, Daren Zha, Shicheng Tan, Yuxiao Dong, Jie Tang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/QingFei1/LongRAG)](https://github.com/QingFei1/LongRAG)

54. [**Reducing Distraction in Long-Context Language Models by Focused Learning.**](https://arxiv.org/abs/2411.05928) _Zijun Wu, Bingyuan Liu, Ran Yan, Lei Chen, Thomas Delteil._ Arxiv 2024.

55. [**Sliding Windows Are Not the End: Exploring Full Ranking with Long-Context Large Language Models.**](https://arxiv.org/abs/2412.14574) _Wenhan Liu, Xinyu Ma, Yutao Zhu, Ziliang Zhao, Shuaiqiang Wang, Dawei Yin, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/8421BCD/fullrank)](https://github.com/8421BCD/fullrank)

56. [**Revisiting In-Context Learning with Long Context Language Models.**](https://arxiv.org/abs/2412.16926) _Jinheon Baek, Sun Jae Lee, Prakhar Gupta, Geunseob (GS)Oh, Siddharth Dalmia, Prateek Kolhar._ Arxiv 2024.

57. [**Eliciting In-context Retrieval and Reasoning for Long-context Large Language Models.**](https://arxiv.org/abs/2501.08248) _Yifu Qiu, Varun Embar, Yizhe Zhang, Navdeep Jaitly, Shay B. Cohen, Benjamin Han._ Arxiv 2024.

58. [**CacheFocus: Dynamic Cache Re-Positioning for Efficient Retrieval-Augmented Generation.**](https://arxiv.org/abs/2502.11101) _Kun-Hui Lee, Eunhwan Park, Donghoon Han, Seung-Hoon Na._ Arxiv 2025.

59. [**Lost in the Passage: Passage-level In-context Learning Does Not Necessarily Need a "Passage".**](https://arxiv.org/abs/2502.10634) _Hao Sun, Chenming Tang, Gengyang Li, Yunfang Wu._ Arxiv 2025.

60. [**MuDAF: Long-Context Multi-Document Attention Focusing through Contrastive Learning on Attention Heads.**](https://arxiv.org/abs/2502.13963) _Weihao Liu, Ning Wu, Shiping Yang, Wenbiao Ding, Shining Liang, Ming Gong, Dongmei Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NeosKnight233/MuDAF)](https://github.com/NeosKnight233/MuDAF)

61. [**Cache-Craft: Managing Chunk-Caches for Efficient Retrieval-Augmented Generation.**](https://arxiv.org/abs/2502.15734) _Shubham Agarwal, Sai Sundaresan, Subrata Mitra, Debabrata Mahapatra, Archit Gupta, Rounak Sharma, Nirmal Joshua Kapu, Tong Yu, Shiv Saini._ SIGMOD 2025.

62. [**OkraLong: A Flexible Retrieval-Augmented Framework for Long-Text Query Processing.**](https://arxiv.org/abs/2503.02603) _Yulong Hui, Yihao Liu, Yao Lu, Huanchen Zhang._ Arxiv 2025.

63. [**Beyond RAG: Task-Aware KV Cache Compression for Comprehensive Knowledge Reasoning.**](https://arxiv.org/abs/2503.04973) _Giulio Corallo, Orion Weller, Fabio Petroni, Paolo Papotti._ Arxiv 2025.

64. [**Efficient Many-Shot In-Context Learning with Dynamic Block-Sparse Attention.**](https://arxiv.org/abs/2503.08640) _Emily Xiao, Chin-Jou Li, Yilin Zhang, Graham Neubig, Amanda Bertsch._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/millix19/dbsa)](https://github.com/millix19/dbsa)

65. [**Long Context Modeling with Ranked Memory-Augmented Retrieval.**](https://arxiv.org/abs/2503.14800) _Ghadir Alselwi, Hao Xue, Shoaib Jameel, Basem Suleiman, Flora D. Salim, Imran Razzak._ Arxiv 2025.

66. [**Tuning LLMs by RAG Principles: Towards LLM-native Memory.**](https://arxiv.org/abs/2503.16071) _Jiale Wei, Shuchi Wu, Ruochen Liu, Xiang Ying, Jingbo Shang, Fangbo Tao._ Arxiv 2025.

67. [**ReaRAG: Knowledge-guided Reasoning Enhances Factuality of Large Reasoning Models with Iterative Retrieval Augmented Generation.**](https://arxiv.org/abs/2503.21729) _Zhicheng Lee, Shulin Cao, Jinxin Liu, Jiajie Zhang, Weichuan Liu, Xiaoyin Che, Lei Hou, Juanzi Li._ Arxiv 2025.

68. [**Focus Directions Make Your Language Models Pay More Attention to Relevant Contexts.**](https://arxiv.org/abs/2503.23306) _Youxiang Zhu, Ruochen Li, Danqing Wang, Daniel Haehn, Xiaohui Liang._ Arxiv 2025.

69. [**FReM: A Flexible Reasoning Mechanism for Balancing Quick and Slow Thinking in Long-Context Question Answering.**](https://arxiv.org/abs/2503.22985) _Zhengyi Zhao, Shubo Zhang, Zezhong Wang, Bin Liang, Binyang Li, Kam-Fai Wong._ Arxiv 2025.

70. [**Dynamic Chunking and Selection for Reading Comprehension of Ultra-Long Context in Large Language Models.**](https://arxiv.org/abs/2506.00773) _Boheng Sheng, Jiacheng Yao, Meicong Zhang, Guoxiu He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ECNU-Text-Computing/DCS)](https://github.com/ECNU-Text-Computing/DCS)

### 8. Agent

1. [**LongAgent: Scaling Language Models to 128k Context through Multi-Agent Collaboration.**](https://arxiv.org/abs/2402.11550) _Jun Zhao, Can Zu, Hao Xu, Yi Lu, Wei He, Yiwen Ding, Tao Gui, Qi Zhang, Xuanjing Huang._ Arxiv 2024.

2. [**A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis.**](https://openreview.net/forum?id=9JQtrumvg8) _Izzeddin Gur, Hiroki Furuta, Austin V Huang, Mustafa Safdari, Yutaka Matsuo, Douglas Eck, Aleksandra Faust._ ICLR 2024 Oral.

3. [**PEARL: Prompting Large Language Models to Plan and Execute Actions Over Long Documents.**](https://aclanthology.org/2024.eacl-long.29/) _Simeng Sun, Yang Liu, Shuohang Wang, Dan Iter, Chenguang Zhu, Mohit Iyyer._ EACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SimengSun/pearl)](https://github.com/SimengSun/pearl)

4. [**AMAGO: Scalable In-Context Reinforcement Learning for Adaptive Agents.**](https://openreview.net/forum?id=M6XWoEdmwf) _Jake Grigsby, Linxi Fan, Yuke Zhu._ ICLR 2024 Spotlight. [![GitHub Repo stars](https://img.shields.io/github/stars/UT-Austin-RPL/amago)](https://github.com/UT-Austin-RPL/amago)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ut-austin-rpl.github.io/amago/)

5. [**Chain of Agents: Large Language Models Collaborating on Long-Context Tasks.**](https://arxiv.org/abs/2406.02818) _Yusen Zhang, Ruoxi Sun, Yanfei Chen, Tomas Pfister, Rui Zhang, Sercan Ö. Arik._ Arxiv 2024.

6. [**GraphReader: Building Graph-based Agent to Enhance Long-Context Abilities of Large Language Models.**](https://arxiv.org/abs/2406.14550) _Shilong Li, Yancheng He, Hangyu Guo, Xingyuan Bu, Ge Bai, Jie Liu, Jiaheng Liu, Xingwei Qu, Yangguang Li, Wanli Ouyang, Wenbo Su, Bo Zheng._ Arxiv 2024.

7. [**Synergistic Multi-Agent Framework with Trajectory Learning for Knowledge-Intensive Tasks.**](https://arxiv.org/abs/2407.09893) _Shengbin Yue, Siyuan Wang, Wei Chen, Xuanjing Huang, Zhongyu Wei._ Arxiv 2024.

8. [**Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-Horizon Tasks.**](https://arxiv.org/abs/2408.03615) _Zaijing Li, Yuquan Xie, Rui Shao, Gongwei Chen, Dongmei Jiang, Liqiang Nie._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JiuTian-VL/Optimus-1)](https://github.com/JiuTian-VL/Optimus-1)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://cybertronagent.github.io/Optimus-1.github.io/)

### 9. Compress

#### 9.1 Context

1. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) _Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

2. [**Compressing Context to Enhance Inference Efficiency of Large Language Models.**](https://arxiv.org/abs/2310.06201) _Yucheng Li, Bo Dong, Chenghua Lin, Frank Guerin._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/liyucheng09/Selective_Context)](https://github.com/liyucheng09/Selective_Context)

3. [**LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models.**](https://arxiv.org/abs/2310.05736) _Huiqiang Jiang, Qianhui Wu, Chin-Yew Lin, Yuqing Yang, Lili Qiu._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

4. [**LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression.**](https://arxiv.org/abs/2310.06839) _Huiqiang Jiang, Qianhui Wu, Xufang Luo, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

5. [**System 2 Attention (is something you might need too).**](https://arxiv.org/abs/2311.11829) _Jason Weston, Sainbayar Sukhbaatar._ Arxiv 2023.

6. [**Soaring from 4K to 400K: Extending LLM's Context with Activation Beacon.**](https://arxiv.org/abs/2401.03462) _Peitian Zhang, Zheng Liu, Shitao Xiao, Ninglu Shao, Qiwei Ye, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

7. [**Flexibly Scaling Large Language Models Contexts Through Extensible Tokenization.**](https://arxiv.org/abs/2401.07793) _Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

8. [**Say More with Less: Understanding Prompt Learning Behaviors through Gist Compression.**](https://arxiv.org/abs/2402.16058) _Xinze Li, Zhenghao Liu, Chenyan Xiong, Shi Yu, Yukun Yan, Shuo Wang, Ge Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenMatch/Gist-COCO)](https://github.com/OpenMatch/Gist-COCO)

9. [**Learning to Compress Prompt in Natural Language Formats.**](https://arxiv.org/abs/2402.18700) _Yu-Neng Chuang, Tianwei Xing, Chia-Yuan Chang, Zirui Liu, Xun Chen, Xia Hu._ Arxiv 2024.

10. [**Dynamic Memory Compression: Retrofitting LLMs for Accelerated Inference.**](https://arxiv.org/abs/2403.09636) _Piotr Nawrot, Adrian Łańcucki, Marcin Chochowski, David Tarjan, Edoardo M. Ponti._ Arxiv 2024.

11. [**LLMLingua-2: Data Distillation for Efficient and Faithful Task-Agnostic Prompt Compression.**](https://arxiv.org/abs/2403.12968) _Zhuoshi Pan, Qianhui Wu, Huiqiang Jiang, Menglin Xia, Xufang Luo, Jue Zhang, Qingwei Lin, Victor Rühle, Yuqing Yang, Chin-Yew Lin, H. Vicky Zhao, Lili Qiu, Dongmei Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

12. [**PCToolkit: A Unified Plug-and-Play Prompt Compression Toolkit of Large Language Models.**](https://arxiv.org/abs/2403.17411) _Jinyi Li, Yihuai Lan, Lei Wang, Hao Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/3DAgentWorld/Toolkit-for-Prompt-Compression)](https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression)

13. [**Compressed Context Memory for Online Language Model Interaction.**](https://arxiv.org/abs/2312.03414) _Jang-Hyun Kim, Junyoung Yeom, Sangdoo Yun, Hyun Oh Song._ ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/snu-mllab/context-memory)](https://github.com/snu-mllab/context-memory)

14. [**PROMPT-SAW: Leveraging Relation-Aware Graphs for Textual Prompt Compression.**](https://arxiv.org/abs/2404.00489) _Muhammad Asif Ali, Zhengping Li, Shu Yang, Keyuan Cheng, Yang Cao, Tianhao Huang, Lijie Hu, Lu Yu, Di Wang._ Arxiv 2024.

15. [**Training LLMs over Neurally Compressed Text.**](https://arxiv.org/abs/2404.03626) _Brian Lester, Jaehoon Lee, Alex Alemi, Jeffrey Pennington, Adam Roberts, Jascha Sohl-Dickstein, Noah Constant._ Arxiv 2024.

16. [**Rethinking Kullback-Leibler Divergence in Knowledge Distillation for Large Language Models.**](https://arxiv.org/abs/2404.02657) _Taiqiang Wu, Chaofan Tao, Jiahao Wang, Zhe Zhao, Ngai Wong._ Arxiv 2024.

17. [**Adapting LLMs for Efficient Context Processing through Soft Prompt Compression.**](https://arxiv.org/abs/2404.04997) _Cangqing Wang, Yutian Yang, Ruisi Li, Dan Sun, Ruicong Cai, Yuzhu Zhang, Chengqian Fu, Lillian Floyd._ Arxiv 2024.

18. [**Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs.**](https://openreview.net/forum?id=uNrFpDPMyo) _Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao._ ICLR 2024 Oral.

19. [**LLoCO: Learning Long Contexts Offline.**](https://arxiv.org/abs/2404.07979) _Sijun Tan, Xiuyu Li, Shishir Patil, Ziyang Wu, Tianjun Zhang, Kurt Keutzer, Joseph E. Gonzalez, Raluca Ada Popa._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/jeffreysijuntan/lloco)](https://github.com/jeffreysijuntan/lloco)

20. [**In-Context Learning State Vector with Inner and Momentum Optimization.**](https://arxiv.org/abs/2404.11225) _Dongfang Li, Zhenyu Liu, Xinshuo Hu, Zetian Sun, Baotian Hu, Min Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HITsz-TMG/ICL-State-Vector)](https://github.com/HITsz-TMG/ICL-State-Vector)

21. [**Compressing Long Context for Enhancing RAG with AMR-based Concept Distillation.**](https://arxiv.org/abs/2405.03085) _Kaize Shi, Xueyao Sun, Qing Li, Guandong Xu._ Arxiv 2024.

22. [**Improving Long Text Understanding with Knowledge Distilled from Summarization Model.**](https://arxiv.org/abs/2405.04955) _Yan Liu, Yazheng Yang, Xiaokang Chen._ Arxiv 2024.

23. [**OpenBA-V2: Reaching 77.3% High Compression Ratio with Fast Multi-Stage Pruning.**](https://arxiv.org/abs/2405.05957) _Dan Qiao, Yi Su, Pinzheng Wang, Jing Ye, Wenjing Xie, Yuechi Zhou, Yuyang Ding, Zecheng Tang, Jikai Wang, Yixin Ji, Yue Wang, Pei Guo, Zechen Sun, Zikang Zhang, Juntao Li, Pingfu Chao, Wenliang Chen, Guohong Fu, Guodong Zhou, Qiaoming Zhu, Min Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLG/OpenBA-v2)](https://github.com/OpenNLG/OpenBA-v2)

24. [**Imagination Augmented Generation: Learning to Imagine Richer Context for Question Answering over Large Language Models.**](https://arxiv.org/abs/2403.15268) _Huanxuan Liao, Shizhu He, Yao Xu, Yuanzhe Zhang, Kang Liu, Shengping Liu, Jun Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/IAG)](https://github.com/Xnhyacinth/IAG)

25. [**xRAG: Extreme Context Compression for Retrieval-augmented Generation with One Token.**](https://arxiv.org/abs/2405.13792) _Xin Cheng, Xun Wang, Xingxing Zhang, Tao Ge, Si-Qing Chen, Furu Wei, Huishuai Zhang, Dongyan Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Hannibal046/xRAG)](https://github.com/Hannibal046/xRAG)

26. [**SelfCP: Compressing Long Prompt to 1/12 Using the Frozen Large Language Model Itself.**](https://arxiv.org/abs/2405.17052) _Jun Gao._ Arxiv 2024.

27. [**Compressing Lengthy Context With UltraGist.**](https://arxiv.org/abs/2405.16635) _Peitian Zhang, Zheng Liu, Shitao Xiao, Ninglu Shao, Qiwei Ye, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/namespace-Pt/UltraGist)](https://github.com/namespace-Pt/UltraGist)

28. [**XL3M: A Training-free Framework for LLM Length Extension Based on Segment-wise Inference.**](https://arxiv.org/abs/2405.17755) _Shengnan Wang, Youhui Bai, Lin Zhang, Pingyi Zhou, Shixiong Zhao, Gong Zhang, Sen Wang, Renhai Chen, Hua Xu, Hongwei Sun._ Arxiv 2024.

29. [**In-context Autoencoder for Context Compression in a Large Language Model.**](https://openreview.net/forum?id=uREj4ZuGJE) _Tao Ge, Hu Jing, Lei Wang, Xun Wang, Si-Qing Chen, Furu Wei._ ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/getao/icae)](https://github.com/getao/icae)

30. [**Retaining Key Information under High Compression Ratios: Query-Guided Compressor for LLMs.**](https://arxiv.org/abs/2406.02376) _Zhiwei Cao, Qian Cao, Yu Lu, Ningxin Peng, Luyang Huang, Shanbo Cheng, Jinsong Su._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DeepLearnXMU/QGC)](https://github.com/DeepLearnXMU/QGC)

31. [**Recurrent Context Compression: Efficiently Expanding the Context Window of LLM.**](https://arxiv.org/abs/2406.06110) _Chensen Huang, Guibo Zhu, Xuepeng Wang, Yifei Luo, Guojing Ge, Haoran Chen, Dong Yi, Jinqiao Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WUHU-G/RCC_Transformer)](https://github.com/WUHU-G/RCC_Transformer)

32. [**LoCoCo: Dropping In Convolutions for Long Context Compression.**](https://arxiv.org/abs/2406.05317) _Ruisi Cai, Yuandong Tian, Zhangyang Wang, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/LoCoCo)](https://github.com/VITA-Group/LoCoCo)

33. [**InstructCMP: Length Control in Sentence Compression through Instruction-based Large Language Models.**](https://arxiv.org/abs/2406.11097) _Juseon-Do, Jingun Kwon, Hidetaka Kamigaito, Manabu Okumura._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JuseonDo/InstructCMP)](https://github.com/JuseonDo/InstructCMP)

34. [**In-Context Former: Lightning-fast Compressing Context for Large Language Model.**](https://arxiv.org/abs/2406.13618) _Xiangfeng Wang, Zaiyi Chen, Zheyong Xie, Tong Xu, Yongyi He, Enhong Chen._ Arxiv 2024.

35. [**UIO-LLMs: Unbiased Incremental Optimization for Long-Context LLMs.**](https://arxiv.org/abs/2406.18173) _Wenhao Li, Mingbao Lin, Yunshan Zhong, Shuicheng Yan, Rongrong Ji._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/wenhaoli-xmu/UIO-LLMs)](https://github.com/wenhaoli-xmu/UIO-LLMs)

36. [**PromptIntern: Saving Inference Costs by Internalizing Recurrent Prompt during Large Language Model Fine-tuning.**](https://arxiv.org/abs/2407.02211) _Jiaru Zou, Mengyu Zhou, Tao Li, Shi Han, Dongmei Zhang._ Arxiv 2024.

37. [**Concise and Precise Context Compression for Tool-Using Language Models.**](https://arxiv.org/abs/2407.02043) _Yang Xu, Yunlong Feng, Honglin Mu, Yutai Hou, Yitong Li, Xinghao Wang, Wanjun Zhong, Zhongyang Li, Dandan Tu, Qingfu Zhu, Min Zhang, Wanxiang Che._ Arxiv 2024.

38. [**Context Embeddings for Efficient Answer Generation in RAG.**](https://arxiv.org/abs/2407.09252) _David Rau, Shuai Wang, Hervé Déjean, Stéphane Clinchant._ Arxiv 2024.

39. [**Characterizing Prompt Compression Methods for Long Context Inference.**](https://arxiv.org/abs/2407.08892) _Siddharth Jha, Lutfi Eren Erdogan, Sehoon Kim, Kurt Keutzer, Amir Gholami._ Arxiv 2024.

40. [**Fundamental Limits of Prompt Compression: A Rate-Distortion Framework for Black-Box Language Models.**](https://arxiv.org/abs/2407.15504) _Adway Girish, Alliot Nagle, Marco Bondaschi, Michael Gastpar, Ashok Vardhan Makkuva, Hyeji Kim._ Arxiv 2024.

41. [**QUITO: Accelerating Long-Context Reasoning through Query-Guided Context Compression.**](https://arxiv.org/abs/2408.00274) _Wenshan Wang, Yihang Wang, Yixing Fan, Huaming Liao, Jiafeng Guo._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Wenshansilvia/attention_compressor)](https://github.com/Wenshansilvia/attention_compressor)

42. [**SentenceVAE: Faster, Longer and More Accurate Inference with Next-sentence Prediction for Large Language Models.**](https://arxiv.org/abs/2408.00655) _Hongjun An, Yifan Chen, Xiaozhen Qiao, Zhe Sun, Xuelong Li._ Arxiv 2024.

43. [**QUITO-X: An Information Bottleneck-based Compression Algorithm with Cross-Attention.**](https://arxiv.org/abs/2408.10497) _Yihang Wang, Xu Huang, Bowen Tian, Yixing Fan, Jiafeng Guo._ Arxiv 2024.

44. [**AdaComp: Extractive Context Compression with Adaptive Predictor for Retrieval-Augmented Large Language Models.**](https://arxiv.org/abs/2409.01579) _Qianchi Zhang, Hainan Zhang, Liang Pang, Hongwei Zheng, Zhiming Zheng._ Arxiv 2024.

45. [**Prompt Compression with Context-Aware Sentence Encoding for Fast and Improved LLM Inference.**](https://arxiv.org/abs/2409.01227) _Barys Liskavets, Maxim Ushakov, Shuvendu Roy, Mark Klibanov, Ali Etemad, Shane Luke._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Workday/cpc)](https://github.com/Workday/cpc)

46. [**Familiarity-aware Evidence Compression for Retrieval Augmented Generation.**](https://arxiv.org/abs/2409.12468) _Dongwon Jung, Qin Liu, Tenghao Huang, Ben Zhou, Muhao Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/luka-group/FaviComp)](https://github.com/luka-group/FaviComp)

47. [**TACO-RL: Task Aware Prompt Compression Optimization with Reinforcement Learning.**](https://arxiv.org/abs/2409.13035) _Shivam Shandilya, Menglin Xia, Supriyo Ghosh, Huiqiang Jiang, Jue Zhang, Qianhui Wu, Victor Rühle._ Arxiv 2024.

48. [**Parse Trees Guided LLM Prompt Compression.**](https://arxiv.org/abs/2409.15395) _Wenhao Mao, Chengbin Hou, Tianyu Zhang, Xinyu Lin, Ke Tang, Hairong Lv._ Arxiv 2024.

49. [**FineZip: Pushing the Limits of Large Language Models for Practical Lossless Text Compression.**](https://arxiv.org/abs/2409.17141) _Fazal Mittu, Yihuan Bu, Akshat Gupta, Ashok Devireddy, Alp Eren Ozdarendeli, Anant Singh, Gopala Anumanchipalli._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/fazalmittu/FineZip)](https://github.com/fazalmittu/FineZip)

50. [**Perception Compressor:A training-free prompt compression method in long context scenarios.**](https://arxiv.org/abs/2409.19272) _Jiwei Tang, Jin Xu, Tingwei Lu, Hai Lin, Yiming Zhao, Hai-Tao Zheng._ Arxiv 2024.

51. [**From Reading to Compressing: Exploring the Multi-document Reader for Prompt Compression.**](https://arxiv.org/abs/2410.04139) _Eunseong Choi, Sunkyung Lee, Minjin Choi, June Park, Jongwuk Lee._ EMNLP 2024.

52. [**Selection-p: Self-Supervised Task-Agnostic Prompt Compression for Faithfulness and Transferability.**](https://arxiv.org/abs/2410.11786) _Tsz Ting Chung, Leyang Cui, Lemao Liu, Xinting Huang, Shuming Shi, Dit-Yan Yeung._ EMNLP 2024.

53. [**Style-Compress: An LLM-Based Prompt Compression Framework Considering Task-Specific Styles.**](https://arxiv.org/abs/2410.14042) _Xiao Pu, Tianxing He, Xiaojun Wan._ EMNLP 2024.

54. [**SpeechPrune: Context-aware Token Pruning for Speech Information Retrieval.**](https://arxiv.org/abs/2412.12009) _Yueqian Lin, Yuzhe Fu, Jingyang Zhang, Yudong Liu, Jianyi Zhang, Jingwei Sun, Hai "Helen" Li, Yiran Chen._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://speechprune.github.io/)

55. [**FTP: A Fine-grained Token-wise Pruner for Large Language Models via Token Routing.**](https://arxiv.org/abs/2412.11494) _Zekai Li, Jintu Zheng, Ji Liu, Han Liu, Haowei Zhu, Zeping Li, Fuwei Yang, Haiduo Huang, Jinzhang Peng, Dong Li, Lu Tian, Emad Barsoum._ Arxiv 2024.

56. [**CSR:Achieving 1 Bit Key-Value Cache via Sparse Representation.**](https://arxiv.org/abs/2412.11741) _Hongxuan Zhang, Yao Zhao, Jiaqi Zheng, Chenyi Zhuang, Jinjie Gu, Guihai Chen._ AAAI 2025.

57. [**EXIT: Context-Aware Extractive Compression for Enhancing Retrieval-Augmented Generation.**](https://arxiv.org/abs/2412.12559) _Taeho Hwang, Sukmin Cho, Soyeong Jeong, Hoyun Song, SeungYoon Han, Jong C. Park._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ThisIsHwang/EXIT)](https://github.com/ThisIsHwang/EXIT)

58. [**A Silver Bullet or a Compromise for Full Attention? A Comprehensive Study of Gist Token-based Context Compression.**](https://arxiv.org/abs/2412.17483) _Chenlong Deng, Zhisong Zhang, Kelong Mao, Shuaiyi Li, Xinting Huang, Dong Yu, Zhicheng Dou._ Arxiv 2024.

59. [**Layer- and Timestep-Adaptive Differentiable Token Compression Ratios for Efficient Diffusion Transformers.**](https://arxiv.org/abs/2412.16822) _Haoran You, Connelly Barnes, Yuqian Zhou, Yan Kang, Zhenbang Du, Wei Zhou, Lingzhi Zhang, Yotam Nitzan, Xiaoyang Liu, Zhe Lin, Eli Shechtman, Sohrab Amirghodsi, Yingyan Celine Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/GATECH-EIC/DiffRatio-MoD)](https://github.com/GATECH-EIC/DiffRatio-MoD)

60. [**Efficient Prompt Compression with Evaluator Heads for Long-Context Transformer Inference.**](https://arxiv.org/abs/2501.12959) _Weizhi Fei, Xueyan Niu, Guoqing Xie, Yingqing Liu, Bo Bai, Wei Han._ Arxiv 2025.

61. [**PISCO: Pretty Simple Compression for Retrieval-Augmented Generation.**](https://arxiv.org/abs/2501.16075) _Maxime Louis, Hervé Déjean, Stéphane Clinchant._ Arxiv 2025.

62. [**Provence: efficient and robust context pruning for retrieval-augmented generation.**](https://arxiv.org/abs/2501.16214) _Nadezhda Chirkova, Thibault Formal, Vassilina Nikoulina, Stéphane Clinchant._ ICLR 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/naver/provence-reranker-debertav3-v1)

63. [**Knowing When to Stop: Dynamic Context Cutoff for Large Language Models.**](https://arxiv.org/abs/2502.01025) _Roy Xie, Junlin Wang, Paul Rosu, Chunyuan Deng, Bolun Sun, Zihao Lin, Bhuwan Dhingra._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ruoyuxie/when-to-stop)](https://github.com/ruoyuxie/when-to-stop)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://royxie.com/when-to-stop-project/)

64. [**LCIRC: A Recurrent Compression Approach for Efficient Long-form Context and Query Dependent Modeling in LLMs.**](https://arxiv.org/abs/2502.06139) _Sumin An, Junyoung Sung, Wonpyo Park, Chanjun Park, Paul Hongsuck Seo._ NAACL 2025.

65. [**DAST: Context-Aware Compression in LLMs via Dynamic Allocation of Soft Tokens.**](https://arxiv.org/abs/2502.11493) _Shaoshen Chen, Yangning Li, Zishan Xu, Yinghui Li, Xin Su, Zifei Shan, Hai-tao Zheng._ Arxiv 2025.

66. [**Token Pruning in Multimodal Large Language Models: Are We Solving the Right Problem?.**](https://arxiv.org/abs/2502.11501) _Zichen Wen, Yifeng Gao, Weijia Li, Conghui He, Linfeng Zhang._ Arxiv 2025.

67. [**Cramming 1568 Tokens into a Single Vector and Back Again: Exploring the Limits of Embedding Space Capacity.**](https://arxiv.org/abs/2502.13063) _Yuri Kuratov, Mikhail Arkhipov, Aydar Bulatov, Mikhail Burtsev._ Arxiv 2025.

68. [**FCoT-VL:Advancing Text-oriented Large Vision-Language Models with Efficient Visual Token Compression.**](https://arxiv.org/abs/2502.18512) _Jianjian Li, Junquan Fan, Feng Tang, Gang Huang, Shitao Zhu, Songlin Liu, Nian Xie, Wulong Liu, Yong Liao._ Arxiv 2025.

69. [**DivPrune: Diversity-based Visual Token Pruning for Large Multimodal Models.**](https://arxiv.org/abs/2503.02175) _Saeed Ranjbar Alvar, Gursimran Singh, Mohammad Akbari, Yong Zhang._ Arxiv 2025.

70. [**EFPC: Towards Efficient and Flexible Prompt Compression.**](https://arxiv.org/abs/2503.07956) _Yun-Hao Cao, Yangsong Wang, Shuzheng Hao, Zhenxing Li, Chengjun Zhan, Sichao Liu, Yi-Qi Hu._ Arxiv 2025.

71. [**AttentionRAG: Attention-Guided Context Pruning in Retrieval-Augmented Generation.**](https://arxiv.org/abs/2503.10720) _Yixiong Fang, Tianran Sun, Yuling Shi, Xiaodong Gu._ Arxiv 2025.

72. [**Limits of KV Cache Compression for Tensor Attention based Autoregressive Transformers.**](https://arxiv.org/abs/2503.11108) _Yifang Chen, Xiaoyu Li, Yingyu Liang, Zhenmei Shi, Zhao Song, Yu Tian._ Arxiv 2025.

73. [**Hybrid-Level Instruction Injection for Video Token Compression in Multi-modal Large Language Models.**](https://arxiv.org/abs/2503.16036) _Zhihang Liu, Chen-Wei Xie, Pandeng Li, Liming Zhao, Longxiang Tang, Yun Zheng, Chuanbin Liu, Hongtao Xie._ CVPR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lntzm/HICom)](https://github.com/lntzm/HICom)

74. [**Token Dynamics: Towards Efficient and Dynamic Video Token Representation for Video Large Language Models.**](https://arxiv.org/abs/2503.16980) _Haichao Zhang, Zhuowei Li, Dimitris Metaxas, Yun Fu._ Arxiv 2025.

75. [**Understanding and Improving Information Preservation in Prompt Compression for LLMs.**](https://arxiv.org/abs/2503.19114) _Weronika Łajewska, Momchil Hardalov, Laura Aina, Neha Anna John, Hang Su, Lluís Màrquezu._ Arxiv 2025.

76. [**Fwd2Bot: LVLM Visual Token Compression with Double Forward Bottleneck.**](https://arxiv.org/abs/2503.21757) _Adrian Bulat, Yassine Ouali, Georgios Tzimiropoulos._ Arxiv 2025.

77. [**Efficient Dynamic Clustering-Based Document Compression for Retrieval-Augmented-Generation.**](https://arxiv.org/abs/2504.03165) _Weitao Li, Kaiming Liu, Xiangyu Zhang, Xuanyu Lei, Weizhi Ma, Yang Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tsinghua-dhy/EDC-2-RAG)](https://github.com/Tsinghua-dhy/EDC-2-RAG)

78. [**Saliency-driven Dynamic Token Pruning for Large Language Models.**](https://arxiv.org/abs/2504.04514) _Yao Tao, Yehui Tang, Yun Wang, Mingjian Zhu, Hailin Hu, Yunhe Wang._ Arxiv 2025.

79. [**Dynamic Compressing Prompts for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2504.11004) _Jinwu Hu, Wei Zhang, Yufeng Wang, Yu Hu, Bin Xiao, Mingkui Tan, Qing Du._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Fhujinwu/DCP)](https://github.com/Fhujinwu/DCP)

80. [**ACoRN: Noise-Robust Abstractive Compression in Retrieval-Augmented Language Models.**](https://arxiv.org/abs/2504.12673) _Singon Kim, Gunho Jung, Seong-Whan Lee._ Arxiv 2025.

81. [**MOOSComp: Improving Lightweight Long-Context Compressor via Mitigating Over-Smoothing and Incorporating Outlier Scores.**](https://arxiv.org/abs/2504.16786) _Fengwei Zhou, Jiafei Song, Wenjin Jason Li, Gengjian Xue, Zhikang Zhao, Yichao Lu, Bailin Na._ Arxiv 2025.

82. [**Token Sequence Compression for Efficient Multimodal Computing.**](https://arxiv.org/abs/2504.17892) _Yasmine Omri, Parth Shroff, Thierry Tambe._ Arxiv 2025.

83. [**An Empirical Study on Prompt Compression for Large Language Models.**](https://arxiv.org/abs/2505.00019) _Zheng Zhang, Jinyi Li, Yihuai Lan, Xiang Wang, Hao Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/3DAgentWorld/Toolkit-for-Prompt-Compression)](https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression)

84. [**Video Compression Commander: Plug-and-Play Inference Acceleration for Video Large Language Models.**](https://arxiv.org/abs/2505.14454) _Xuyang Liu, Yiyu Wang, Junpeng Ma, Linfeng Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/xuyang-liu16/VidCom2)](https://github.com/xuyang-liu16/VidCom2)

85. [**Beyond Hard and Soft: Hybrid Context Compression for Balancing Local and Global Information Retention.**](https://arxiv.org/abs/2505.15774) _Huanxuan Liao, Wen Hu, Yao Xu, Shizhu He, Jun Zhao, Kang Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/HyCo2)](https://github.com/Xnhyacinth/HyCo2)

86. [**QwenLong-CPRS: Towards ∞-LLMs with Dynamic Context Optimization.**](https://arxiv.org/abs/2505.18092) _Weizhou Shen, Chenliang Li, Fanqi Wan, Shengyi Liao, Shaopeng Lai, Bo Zhang, Yingcheng Shi, Yuning Wu, Gang Fu, Zhansheng Li, Bin Yang, Ji Zhang, Fei Huang, Jingren Zhou, Ming Yan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongyi-Zhiwen/QwenLong-CPRS)](https://github.com/Tongyi-Zhiwen/QwenLong-CPRS)

87. [**Lossless Token Sequence Compression via Meta-Tokens.**](https://arxiv.org/abs/2506.00307) _John Harvill, Ziwei Fan, Hao Wang, Yizhou Sun, Hao Ding, Luke Huan, Anoop Deoras._ Arxiv 2025.

88. [**Sentinel: Attention Probing of Proxy Models for LLM Context Compression with an Understanding Perspective.**](https://arxiv.org/abs/2505.23277) _Yong Zhang, Yanwen Huang, Ning Cheng, Yang Guo, Yun Zhu, Yanmeng Wang, Shaojun Wang, Jing Xiao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/yzhangchuck/Sentinel)](https://github.com/yzhangchuck/Sentinel)

#### 9.2 Model

1. [**DSFormer: Effective Compression of Text-Transformers by Dense-Sparse Weight Factorization.**](https://arxiv.org/abs/2312.13211) _Rahul Chand, Yashoteja Prabhu, Pratyush Kumar._ Arxiv 2023.

2. [**LLM-Pruner: On the Structural Pruning of Large Language Models.**](https://openreview.net/forum?id=J8Ajf9WfXP1) _Xinyin Ma, Gongfan Fang, Xinchao Wang._ NeurIPS 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/LLM-Pruner)](https://github.com/horseee/LLM-Pruner)

3. [**Compressing Large Language Models by Streamlining the Unimportant Layer.**](https://arxiv.org/abs/2403.19135) _Xiaodong Chen, Yuxuan Hu, Jing Zhang._ Arxiv 2024.

4. [**Feature-based Low-Rank Compression of Large Language Models via Bayesian Optimization.**](https://arxiv.org/abs/2405.10616) _Yixin Ji, Yang Xiang, Juntao Li, Wei Chen, Zhongyi Liu, Kehai Chen, Min Zhang._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Dereck0602/Bolaco)](https://github.com/Dereck0602/Bolaco)

5. [**Your Transformer is Secretly Linear.**](https://arxiv.org/abs/2405.12250) _Anton Razzhigaev, Matvey Mikhalchuk, Elizaveta Goncharova, Nikolai Gerasimenko, Ivan Oseledets, Denis Dimitrov, Andrey Kuznetsov._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AIRI-Institute/LLM-Microscope)](https://github.com/AIRI-Institute/LLM-Microscope)

6. [**Evaluating Zero-Shot Long-Context LLM Compression.**](https://arxiv.org/abs/2406.06773) _Chenyu Wang, Yihan Wang._ Arxiv 2024.

7. [**AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration.**](https://arxiv.org/abs/2306.00978) _Ji Lin, Jiaming Tang, Haotian Tang, Shang Yang, Wei-Ming Chen, Wei-Chen Wang, Guangxuan Xiao, Xingyu Dang, Chuang Gan, Song Han._ MLSys 2024 Best Paper Award. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/llm-awq)](https://github.com/mit-han-lab/llm-awq)

8. [**Merging Feed-Forward Sublayers for Compressed Transformers.**](https://arxiv.org/abs/2501.06126) _Neha Verma, Kenton Murray, Kevin Duh._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nverma1/merging-ffs-compression)](https://github.com/nverma1/merging-ffs-compression/)

9. [**FlexiGPT: Pruning and Extending Large Language Models with Low-Rank Weight Sharing.**](https://arxiv.org/abs/2501.14713) _James Seale Smith, Chi-Heng Lin, Shikhar Tuli, Haris Jeelani, Shangqian Gao, Yilin Shen, Hongxia Jin, Yen-Chang Hsu._ NAACL 2025.

10. [**TensorLLM: Tensorising Multi-Head Attention for Enhanced Reasoning and Compression in LLMs.**](https://arxiv.org/abs/2501.15674) _Yuxuan Gu, Wuyang Zhou, Giorgos Iacovides, Danilo Mandic._ Arxiv 2025.

11. [**You Only Prune Once: Designing Calibration-Free Model Compression With Policy Learning.**](https://arxiv.org/abs/2501.15296) _Ayan Sengupta, Siddhant Chaudhary, Tanmoy Chakraborty._ ICLR 2025.

12. [**Mamba-Shedder: Post-Transformer Compression for Efficient Selective Structured State Space Models.**](https://arxiv.org/abs/2501.17088) _J. Pablo Muñoz, Jinjie Yuan, Nilesh Jain._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/IntelLabs/Hardware-Aware-Automated-Machine-Learning)](https://github.com/IntelLabs/Hardware-Aware-Automated-Machine-Learning)

13. [**TAID: Temporally Adaptive Interpolated Distillation for Efficient Knowledge Transfer in Language Models.**](https://arxiv.org/abs/2501.16937) _Makoto Shing, Kou Misaki, Han Bao, Sho Yokoi, Takuya Akiba._ ICLR 2025.

14. [**AdaSVD: Adaptive Singular Value Decomposition for Large Language Models.**](https://arxiv.org/abs/2502.01403) _Zhiteng Li, Mingyuan Xia, Jingyuan Zhang, Zheng Hui, Linghe Kong, Yulun Zhang, Xiaokang Yang._ Arixv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ZHITENGLI/AdaSVD)](https://github.com/ZHITENGLI/AdaSVD)

15. [**Activation-Informed Merging of Large Language Models.**](https://arxiv.org/abs/2502.02421) _Amin Heyrani Nobari, Kaveh Alimohammadi, Ali ArjomandBigdeli, Akash Srivastava, Faez Ahmed, Navid Azizan._ Arixv 2025.

16. [**Adapt-Pruner: Adaptive Structural Pruning for Efficient Small Language Model Training.**](https://arxiv.org/abs/2502.03460) _Boyao Wang, Rui Pan, Shizhe Diao, Xingyuan Pan, Jipeng Zhang, Renjie Pi, Tong Zhang._ Arixv 2025.

17. [**QuEST: Stable Training of LLMs with 1-Bit Weights and Activations.**](https://arxiv.org/abs/2502.05003) _Andrei Panferov, Jiale Chen, Soroush Tabesh, Roberto L. Castro, Mahdi Nikdan, Dan Alistarh._ Arixv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/IST-DASLab/QuEST)](https://github.com/IST-DASLab/QuEST)

18. [**DarwinLM: Evolutionary Structured Pruning of Large Language Models.**](https://arxiv.org/abs/2502.07780) _Shengkun Tang, Oliver Sieberling, Eldar Kurtic, Zhiqiang Shen, Dan Alistarh._ Arixv 2025.

19. [**Hyper Compressed Fine-Tuning of Large Foundation Models with Quantum Inspired Adapters.**](https://arxiv.org/abs/2502.06916) _Snehal Raj, Brian Coyle._ Arixv 2025.

20. [**Contextual Compression Encoding for Large Language Models: A Novel Framework for Multi-Layered Parameter Space Pruning.**](https://arxiv.org/abs/2502.08323) _Barnaby Schmitt, Alistair Grosvenor, Matthias Cunningham, Clementine Walsh, Julius Pembrokeshire, Jonathan Teel._ Arixv 2025.

21. [**Forget the Data and Fine-Tuning! Just Fold the Network to Compress.**](https://arxiv.org/abs/2502.10216) _Dong Wang, Haris Šikić, Lothar Thiele, Olga Saukh._ ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nanguoyu/model-folding-universal)](https://github.com/nanguoyu/model-folding-universal)

22. [**NestQuant: Nested Lattice Quantization for Matrix Products and LLMs.**](https://arxiv.org/abs/2502.09720) _Semyon Savkin, Eitan Porat, Or Ordentlich, Yury Polyanskiy._ Arixv 2025.

23. [**1bit-Merging: Dynamic Quantized Merging for Large Language Models.**](hhttps://arxiv.org/abs/2502.10743) _Shuqi Liu, Han Wu, Bowei He, Zehua Liu, Xiongwei Han, Mingxuan Yuan, Linqi Song._ Arixv 2025.

24. [**Every Expert Matters: Towards Effective Knowledge Distillation for Mixture-of-Experts Language Models.**](https://arxiv.org/abs/2502.12947) _Gyeongman Kim, Gyouk Chu, Eunho Yang._ Arixv 2025.

25. [**NestQuant: Nested Lattice Quantization for Matrix Products and LLMs.**](https://arxiv.org/abs/2502.09720) _Semyon Savkin, Eitan Porat, Or Ordentlich, Yury Polyanskiy._ Arixv 2025.

26. [**When Compression Meets Model Compression: Memory-Efficient Double Compression for Large Language Models.**](https://arxiv.org/abs/2502.15443) _Weilan Wang, Yu Mao, Dongdong Tang, Hongchao Du, Nan Guan, Chun Jason Xue._ Arixv 2025.

27. [**Optimizing Singular Spectrum for Large Language Model Compression.**](https://arxiv.org/abs/2502.15092) _Dengjie Li, Tiancheng Shen, Yao Zhou, Baisong Yang, Zhongying Liu, Masheng Yang, Bernard Ghanem, Yibo Yang, Yujie Zhong, Ming-Hsuan Yang._ Arixv 2025.

28. [**Rotate, Clip, and Partition: Towards W2A4KV4 Quantization by Integrating Rotation and Learnable Non-uniform Quantizer.**](https://arxiv.org/abs/2502.15779) _Euntae Choi, Sumin Song, Woosang Lim, Sungjoo Yoo._ Arixv 2025.

29. [**Delta Decompression for MoE-based LLMs Compression.**](https://arxiv.org/abs/2502.17298) _Hao Gu, Wei Li, Lujun Li, Qiyuan Zhu, Mark Lee, Shengjie Sun, Wei Xue, Yike Guo._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lliai/D2MoE)](https://github.com/lliai/D2MoE)

30. [**The Lottery LLM Hypothesis, Rethinking What Abilities Should LLM Compression Preserve?.**](https://arxiv.org/abs/2502.17535) _Zhenheng Tang, Xiang Liu, Qian Wang, Peijie Dong, Bingsheng He, Xiaowen Chu, Bo Li._ ICLR 2025.

31. [**Compressing Language Models for Specialized Domains.**](https://arxiv.org/abs/2502.18424) _Miles Williams, George Chrysostomou, Vitor Jeronymo, Nikolaos Aletras._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mlsw/domain-compression)](https://github.com/mlsw/domain-compression)

32. [**Thinking Slow, Fast: Scaling Inference Compute with Distilled Reasoners.**](https://arxiv.org/abs/2502.20339) _Daniele Paliotta, Junxiong Wang, Matteo Pagliardini, Kevin Y. Li, Aviv Bick, J. Zico Kolter, Albert Gu, François Fleuret, Tri Dao._ Arxiv 2025.

33. [**DeRS: Towards Extremely Efficient Upcycled Mixture-of-Experts Models.**](https://arxiv.org/abs/2503.01359) _Yongqi Huang, Peng Ye, Chenyu Huang, Jianjian Cao, Lin Zhang, Baopu Li, Gang Yu, Tao Chen._ CVPR 2025.

34. [**Efficiently Editing Mixture-of-Experts Models with Compressed Experts.**](https://arxiv.org/abs/2503.00634) _Yifei He, Yang Liu, Chen Liang, Hany Hassan Awadalla._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/yifei-he/Compressed-Experts)](https://github.com/yifei-he/Compressed-Experts)

35. [**IDEA Prune: An Integrated Enlarge-and-Prune Pipeline in Generative Language Model Pretraining.**](https://arxiv.org/abs/2503.05920) _Yixiao Li, Xianzhi Du, Ajay Jaiswal, Tao Lei, Tuo Zhao, Chong Wang, Jianyu Wang._ Arxiv 2025.

36. [**Position-Aware Depth Decay Decoding (D3): Boosting Large Language Model Inference Efficiency.**](https://arxiv.org/abs/2503.08524) _Siqi Fan, Xuezhi Fang, Xingrun Xing, Peng Han, Shuo Shang, Yequan Wang._ Arxiv 2025.

37. [**Towards Extreme Pruning of LLMs with Plug-and-Play Mixed Sparsity.**](https://arxiv.org/abs/2503.11164) _Chi Xu, Gefei Zhang, Yantong Zhu, Luca Benini, Guosheng Hu, Yawei Li, Zhihong Zhang._ Arxiv 2025.

38. [**SVD-LLM V2: Optimizing Singular Value Truncation for Large Language Model Compression.**](https://arxiv.org/abs/2503.12340) _Xin Wang, Samiul Alam, Zhongwei Wan, Hui Shen, Mi Zhang._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AIoT-MLSys-Lab/SVD-LLM)](https://github.com/AIoT-MLSys-Lab/SVD-LLM)

39. [**ClusComp: A Simple Paradigm for Model Compression and Efficient Finetuning.**](https://arxiv.org/abs/2503.13089) _Baohao Liao, Christian Herold, Seyyed Hadi Hashemi, Stefan Vasilev, Shahram Khadivi, Christof Monz._ Arxiv 2025.

40. [**Large Language Model Compression via the Nested Activation-Aware Decomposition.**](https://arxiv.org/abs/2503.17101) _Jun Lu, Tianyi Xu, Bill Ding, David Li, Yu Kang._ Arxiv 2025.

41. [**When Reasoning Meets Compression: Benchmarking Compressed Large Reasoning Models on Complex Reasoning Tasks.**](https://arxiv.org/abs/2504.02010) _Nan Zhang, Yusen Zhang, Prasenjit Mitra, Rui Zhang._ Arxiv 2025.

42. [**Compression Laws for Large Language Models.**](https://arxiv.org/abs/2504.04342) _Ayan Sengupta, Siddhant Chaudhary, Tanmoy Chakraborty._ Arxiv 2025.

43. [**Thanos: A Block-wise Pruning Algorithm for Efficient Large Language Model Compression.**](https://arxiv.org/abs/2504.05346) _Ivan Ilin, Peter Richtarik._ Arxiv 2025.

44. [**Efficient Hybrid Language Model Compression through Group-Aware SSM Pruning.**](https://arxiv.org/abs/2504.11409) _Ali Taghibakhshi, Sharath Turuvekere Sreenivas, Saurav Muralidharan, Marcin Chochowski, Yashaswi Karnati, Raviraj Joshi, Ameya Sunil Mahabaleshwarkar, Zijia Chen, Yoshi Suhara, Oluwatobi Olabiyi, Daniel Korzekwa, Mostofa Patwary, Mohammad Shoeybi, Jan Kautz, Bryan Catanzaro, Ashwath Aithal, Nima Tajbakhsh, Pavlo Molchanov
._ Arxiv 2025.

45. [**70% Size, 100% Accuracy: Lossless LLM Compression for Efficient GPU Inference via Dynamic-Length Float.**](https://arxiv.org/abs/2504.11651) _Tianyi Zhang, Yang Sui, Shaochen Zhong, Vipin Chaudhary, Xia Hu, Anshumali Shrivastava._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LeanModels/DFloat11)](https://github.com/LeanModels/DFloat11)

46. [**From Large to Super-Tiny: End-to-End Optimization for Cost-Efficient LLMs.**](https://arxiv.org/abs/2504.13471) _Jiliang Ni, Jiachen Pu, Zhongyi Yang, Kun Zhou, Hui Wang, Xiaoliang Xiao, Dakui Wang, Xin Li, Jingfeng Luo, Conggang Hu._ Arxiv 2025.

47. [**ImPart: Importance-Aware Delta-Sparsification for Improved Model Compression and Merging in LLMs.**](https://arxiv.org/abs/2504.13237) _Yan Yang, Yixia Li, Hongru Wang, Xuetao Wei, Jianqiao Yu, Yun Chen, Guanhua Chen._ Arxiv 2025.

48. [**On-Device Qwen2.5: Efficient LLM Inference with Model Compression and Hardware Acceleration.**](https://arxiv.org/abs/2504.17376) _Maoyang Xiang, Ramesh Fernando, Bo Wang._ Arxiv 2025.

49. [**Efficient LLMs with AMP: Attention Heads and MLP Pruning.**](https://arxiv.org/abs/2504.21174) _Leandro Giusti Mugnaini, Bruno Lopes Yamamoto, Lucas Lauton de Alcantara, Victor Zacarias, Edson Bollis, Lucas Pellicer, Anna Helena Reali Costa, Artur Jordao._ IJCNN 2025.

50. [**ParamΔ for Direct Weight Mixing: Post-Train Large Language Model at Zero Cost.**](https://arxiv.org/abs/2504.21023) _Sheng Cao, Mingrui Wu, Karthik Prasad, Yuandong Tian, Zechun Liu._ ICLR 2025.

51. [**ReplaceMe: Network Simplification via Layer Pruning and Linear Transformations.**](https://arxiv.org/abs/2505.02819) _Dmitriy Shopkhoev, Ammar Ali, Magauiya Zhussip, Valentin Malykh, Stamatios Lefkimmiatis, Nikos Komodakis, Sergey Zagoruyko._ Arxiv 2025.

52. [**Activation-Guided Consensus Merging for Large Language Models.**](https://arxiv.org/abs/2505.14009) _Yuxuan Yao, Shuqi Liu, Zehua Liu, Qintong Li, Mingyang Liu, Xiongwei Han, Zhijiang Guo, Han Wu, Linqi Song._ Arxiv 2025.

53. [**Breaking the Compression Ceiling: Data-Free Pipeline for Ultra-Efficient Delta Compression.**](https://arxiv.org/abs/2505.13563) _Xiaohui Wang, Peng Ye, Chenyu Huang, Shenghe Zheng, Bo Zhang, Wanli Ouyang, Tao Chen._ Arxiv 2025.

#### 9.3 Long CoT

1. [**Reasoning Path Compression: Compressing Generation Trajectories for Efficient LLM Reasoning.**](https://arxiv.org/abs/2505.13866) _Jiwon Song, Dongwon Jo, Yulhwa Kim, Jae-Joon Kim._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/jiwonsong-dev/ReasoningPathCompression)](https://github.com/jiwonsong-dev/ReasoningPathCompression)

2. [**Can Pruning Improve Reasoning? Revisiting Long-CoT Compression with Capability in Mind for Better Reasoning.**](https://arxiv.org/abs/2505.14582) _Shangziqi Zhao, Jiahao Yuan, Guisong Yang, Usman Naseem._ Arxiv 2025.

3. [**FlashThink: An Early Exit Method For Efficient Reasoning.**](https://arxiv.org/abs/2505.13949) _Guochao Jiang, Guofeng Quan, Zepeng Ding, Ziqin Luo, Dixuan Wang, Zheng Hu._ Arxiv 2025.

4. [**Not All Tokens Are What You Need In Thinking.**](https://arxiv.org/abs/2505.17827) _Hang Yuan, Bin Yu, Haotian Li, Shijun Yang, Christina Dan Wang, Zhou Yu, Xueyin Xu, Weizhen Qi, Kai Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Faustrazor/Not-All-Thinking-Tokens)](https://github.com/Faustrazor/Not-All-Thinking-Tokens)

5. [**TrimR: Verifier-based Training-Free Thinking Compression for Efficient Test-Time Scaling.**](https://arxiv.org/abs/2505.17155) _Weizhe Lin, Xing Li, Zhiyuan Yang, Xiaojin Fu, Hui-Ling Zhen, Yaoyuan Wang, Xianzhi Yu, Wulong Liu, Xiaosong Li, Mingxuan Yuan._ Arxiv 2025.

6. [**Efficient Long CoT Reasoning in Small Language Models.**](https://arxiv.org/abs/2505.18440) _Zhaoyang Wang, Jinqi Jiang, Tian Qiu, Hui Liu, Xianfeng Tang, Huaxiu Yao._ Arxiv 2025.

7. [**Efficient Reasoning via Chain of Unconscious Thought.**](https://arxiv.org/abs/2505.19756) _Ruihan Gong, Yue Liu, Wenjie Qu, Mingzhe Du, Yufei He, Yingwei Ma, Yulin Chen, Xiang Liu, Yi Wen, Xinfeng Li, Ruidong Wang, Xinzhong Zhu, Bryan Hooi, Jiaheng Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Rohan-GRH/CoUT)](https://github.com/Rohan-GRH/CoUT)

8. [**Hybrid Latent Reasoning via Reinforcement Learning.**](https://arxiv.org/abs/2505.18454) _Zhenrui Yue, Bowen Jin, Huimin Zeng, Honglei Zhuang, Zhen Qin, Jinsung Yoon, Lanyu Shang, Jiawei Han, Dong Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Yueeeeeeee/HRPO)](https://github.com/Yueeeeeeee/HRPO)


9. [**System-1.5 Reasoning: Traversal in Language and Latent Spaces with Dynamic Shortcuts.**](https://arxiv.org/abs/2505.18962) _Xiaoqiang Wang, Suyuchen Wang, Yun Zhu, Bang Liu._ Arxiv 2025.

### 10. Long Video and Image

1. [**EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture.**](https://arxiv.org/abs/2405.18991) _Jiaqi Xu, Xinyi Zou, Kunzhe Huang, Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/aigc-apps/EasyAnimate)](https://github.com/aigc-apps/EasyAnimate)

2. [**VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos.**](https://arxiv.org/abs/2405.19209) _Ziyang Wang, Shoubin Yu, Elias Stengel-Eskin, Jaehong Yoon, Feng Cheng, Gedas Bertasius, Mohit Bansal._ Arxiv 2024.

3. [**PostDoc: Generating Poster from a Long Multimodal Document Using Deep Submodular Optimization.**](https://arxiv.org/abs/2405.20213) _Vijay Jaisankar, Sambaran Bandyopadhyay, Kalp Vyas, Varre Chaitanya, Shwetha Somasundaram._ Arxiv 2024.

4. [**Investigating Video Reasoning Capability of Large Language Models with Tropes in Movies.**](https://arxiv.org/abs/2406.10923) _Hung-Ting Su, Chun-Tong Chao, Ya-Ching Hsu, Xudong Lin, Yulei Niu, Hung-Yi Lee, Winston H. Hsu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ander1119/TiM)](https://github.com/ander1119/TiM)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ander1119.github.io/TiM/)

5. [**Towards Event-oriented Long Video Understanding.**](https://arxiv.org/abs/2406.14129) _Yifan Du, Kun Zhou, Yuqi Huo, Yifan Li, Wayne Xin Zhao, Haoyu Lu, Zijia Zhao, Bingning Wang, Weipeng Chen, Ji-Rong Wen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/Event-Bench)](https://github.com/RUCAIBox/Event-Bench)

6. [**An End-to-End Speech Summarization Using Large Language Model.**](https://arxiv.org/abs/2407.02005) _Hengchao Shang, Zongyao Li, Jiaxin Guo, Shaojun Li, Zhiqiang Rao, Yuanchang Luo, Daimeng Wei, Hao Yang._ Arxiv 2024.

7. [**KeyVideoLLM: Towards Large-scale Video Keyframe Selection.**](https://arxiv.org/abs/2407.03104) _Hao Liang, Jiapeng Li, Tianyi Bai, Chong Chen, Conghui He, Bin Cui, Wentao Zhang._ Arxiv 2024.

8. [**OmChat: A Recipe to Train Multimodal Language Models with Strong Long Context and Video Understanding.**](https://arxiv.org/abs/2407.04923) _Tiancheng Zhao, Qianqian Zhang, Kyusong Lee, Peng Liu, Lu Zhang, Chunxin Fang, Jiajia Liao, Kelei Jiang, Yibo Ma, Ruochen Xu._ Arxiv 2024.

9. [**MATE: Meet At The Embedding -- Connecting Images with Long Texts.**](https://arxiv.org/abs/2407.09541) _Young Kyun Jang, Junmo Kang, Yong Jae Lee, Donghyun Kim._ Arxiv 2024.

10. [**mPLUG-Owl3: Towards Long Image-Sequence Understanding in Multi-Modal Large Language Models.**](https://arxiv.org/abs/2408.04840) _Jiabo Ye, Haiyang Xu, Haowei Liu, Anwen Hu, Ming Yan, Qi Qian, Ji Zhang, Fei Huang, Jingren Zhou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl)](https://github.com/X-PLUG/mPLUG-Owl)

11. [**LongVILA: Scaling Long-Context Visual Language Models for Long Videos.**](https://arxiv.org/abs/2408.10188) _Fuzhao Xue, Yukang Chen, Dacheng Li, Qinghao Hu, Ligeng Zhu, Xiuyu Li, Yunhao Fang, Haotian Tang, Shang Yang, Zhijian Liu, Ethan He, Hongxu Yin, Pavlo Molchanov, Jan Kautz, Linxi Fan, Yuke Zhu, Yao Lu, Song Han._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NVlabs/VILA)](https://github.com/NVlabs/VILA/blob/main/LongVILA.md)

12. [**DreamFactory: Pioneering Multi-Scene Long Video Generation with a Multi-Agent Framework.**](https://arxiv.org/abs/2408.11788) _Zhifei Xie, Daniel Tang, Dingwei Tan, Jacques Klein, Tegawend F. Bissyand, Saad Ezzini._ Arxiv 2024.

13. [**Bridging Episodes and Semantics: A Novel Framework for Long-Form Video Understanding.**](https://arxiv.org/abs/2408.17443) _Gueter Josmy Faure, Jia-Fong Yeh, Min-Hung Chen, Hung-Ting Su, Winston H. Hsu, Shang-Hong Lai._ ECCV 2024 Workshop. [![GitHub Repo stars](https://img.shields.io/github/stars/joslefaure/HERMES)](https://github.com/joslefaure/HERMES)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://joslefaure.github.io/assets/html/hermes.html)

14. [**VideoLLaMB: Long-context Video Understanding with Recurrent Memory Bridges.**](https://arxiv.org/abs/2409.01071) _Yuxuan Wang, Cihang Xie, Yang Liu, Zilong Zheng._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/VideoLLaMB)](https://github.com/bigai-nlco/VideoLLaMB)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://videollamb.github.io/)

15. [**Longer is (Not Necessarily) Stronger: Punctuated Long-Sequence Training for Enhanced Speech Recognition and Translation.**](https://arxiv.org/abs/2409.05601) _Nithin Rao Koluguri, Travis Bartley, Hainan Xu, Oleksii Hrinchuk, Jagadeesh Balam, Boris Ginsburg, Georg Kucsko._ Arxiv 2024.

16. [**LongLLaVA: Scaling Multi-modal LLMs to 1000 Images Efficiently via Hybrid Architecture.**](https://arxiv.org/abs/2409.02889) _Xidong Wang, Dingjie Song, Shunian Chen, Chen Zhang, Benyou Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FreedomIntelligence/LongLLaVA)](https://github.com/FreedomIntelligence/LongLLaVA)

17. [**VideoCLIP-XL: Advancing Long Description Understanding for Video CLIP Models.**](https://arxiv.org/abs/2410.00741) _Jiapeng Wang, Chengyu Wang, Kunzhe Huang, Jun Huang, Lianwen Jin._ Arxiv 2024.

18. [**Rethinking Visual Dependency in Long-Context Reasoning for Large Vision-Language Models.**](https://arxiv.org/abs/2410.19732) _Yucheng Zhou, Zhi Rao, Jun Wan, Jianbing Shen._ Arxiv 2024.

19. [**SlowFast-VGen: Slow-Fast Learning for Action-Driven Long Video Generation.**](https://arxiv.org/abs/2410.23277) _Yining Hong, Beide Liu, Maxine Wu, Yuanhao Zhai, Kai-Wei Chang, Lingjie Li, Kevin Lin, Chung-Ching Lin, Jianfeng Wang, Zhengyuan Yang, Yingnian Wu, Lijuan Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/slowfast-vgen/slowfast-vgen)](https://github.com/slowfast-vgen/slowfast-vgen)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://slowfast-vgen.github.io/)

20. [**LLM2CLIP: Powerful Language Model Unlock Richer Visual Representation.**](https://arxiv.org/abs/2411.04997) _Weiquan Huang, Aoqi Wu, Yifan Yang, Xufang Luo, Yuqing Yang, Liang Hu, Qi Dai, Xiyang Dai, Dongdong Chen, Chong Luo, Lili Qiu._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLM2CLIP/)](https://github.com/microsoft/LLM2CLIP/)

21. [**ReVisionLLM: Recursive Vision-Language Model for Temporal Grounding in Hour-Long Videos.**](https://arxiv.org/abs/2411.14901) _Tanveer Hannan, Md Mohaiminul Islam, Jindong Gu, Thomas Seidl, Gedas Bertasius._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Tanveer81/ReVisionLLM)](https://github.com/Tanveer81/ReVisionLLM)

22. [**T2Vid: Translating Long Text into Multi-Image is the Catalyst for Video-LLMs.**](https://arxiv.org/abs/2411.19951) _Shukang Yin, Chaoyou Fu, Sirui Zhao, Yunhang Shen, Chunjiang Ge, Yan Yang, Zuwei Long, Yuhan Dai, Tong Xu, Xing Sun, Ran He, Caifeng Shan, Enhong Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/xjtupanda/T2Vid)](https://github.com/xjtupanda/T2Vid)

23. [**Owl-1: Omni World Model for Consistent Long Video Generation.**](https://arxiv.org/abs/2412.09600) _Yuanhui Huang, Wenzhao Zheng, Yuan Gao, Xin Tao, Pengfei Wan, Di Zhang, Jie Zhou, Jiwen Lu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/huang-yh/Owl)](https://github.com/huang-yh/Owl)

24. [**VCA: Video Curious Agent for Long Video Understanding.**](https://arxiv.org/abs/2412.10471) _Zeyuan Yang, Delin Chen, Xueyang Yu, Maohao Shen, Chuang Gan._ Arxiv 2024.

25. [**Enhancing Multi-Text Long Video Generation Consistency without Tuning: Time-Frequency Analysis, Prompt Alignment, and Theory.**](https://arxiv.org/abs/2412.17254) _Xingyao Li, Fengzhuo Zhang, Jiachun Pan, Yunlong Hou, Vincent Y. F. Tan, Zhuoran Yang._ Arxiv 2024.

26. [**ReTaKe: Reducing Temporal and Knowledge Redundancy for Long Video Understanding.**](https://arxiv.org/abs/2412.20504) _Xiao Wang, Qingyi Si, Jianlong Wu, Shiyu Zhu, Li Cao, Liqiang Nie._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SCZwangxiao/video-ReTaKe)](https://github.com/SCZwangxiao/video-ReTaKe)

27. [**LLaVA-Mini: Efficient Image and Video Large Multimodal Models with One Vision Token.**](https://arxiv.org/abs/2501.03895) _Shaolei Zhang, Qingkai Fang, Zhe Yang, Yang Feng._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SCZwangxiao/video-ReTaKe)](https://github.com/SCZwangxiao/video-ReTaKe)

28. [**Temporal Preference Optimization for Long-Form Video Understanding.**](https://arxiv.org/abs/2501.13919) _Rui Li, Xiaohan Wang, Yuhui Zhang, Zeyu Wang, Serena Yeung-Levy._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ruili33/TPO)](https://github.com/ruili33/TPO)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ruili33.github.io/tpo_website/)

29. [**Latent Swap Joint Diffusion for Long-Form Audio Generation.**](https://arxiv.org/abs/2502.05130) _Yusheng Dai, Chenxi Wang, Chang Li, Chen Wang, Jun Du, Kewei Li, Ruoyu Wang, Jiefeng Ma, Lei Sun, Jianqing Gao._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://swapforward.github.io/)

30. [**MALT Diffusion: Memory-Augmented Latent Transformers for Any-Length Video Generation.**](https://arxiv.org/abs/2502.12632) _Sihyun Yu, Meera Hahn, Dan Kondratyuk, Jinwoo Shin, Agrim Gupta, José Lezama, Irfan Essa, David Ross, Jonathan Huang._ Arxiv 2025.

31. [**VideoRoPE: What Makes for Good Video Rotary Position Embedding?.**](https://arxiv.org/abs/2502.05173) _Xilin Wei, Xiaoran Liu, Yuhang Zang, Xiaoyi Dong, Pan Zhang, Yuhang Cao, Jian Tong, Haodong Duan, Qipeng Guo, Jiaqi Wang, Xipeng Qiu, Dahua Lin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Wiselnn570/VideoRoPE)](https://github.com/Wiselnn570/VideoRoPE)

32. [**Adaptive Keyframe Sampling for Long Video Understanding.**](https://arxiv.org/abs/2502.21271) _Xi Tang, Jihao Qiu, Lingxi Xie, Yunjie Tian, Jianbin Jiao, Qixiang Ye._ CVPR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ncTimTang/AKS)](https://github.com/ncTimTang/AKS)

33. [**Keyframe-oriented Vision Token Pruning: Enhancing Efficiency of Large Vision Language Models on Long-Form Video Processing.**](https://arxiv.org/abs/2503.10742) _Yudong Liu, Jingwei Sun, Yueqian Lin, Jingyang Zhang, Ming Yin, Qinsi Wang, Jianyi Zhang, Hai Li, Yiran Chen._ Arxiv 2025.

34. [**Logic-in-Frames: Dynamic Keyframe Search via Visual Semantic-Logical Verification for Long Video Understanding.**](https://arxiv.org/abs/2503.13139) _Weiyu Guo, Ziyang Chen, Shaoguang Wang, Jianxiang He, Yijie Xu, Jinhui Ye, Ying Sun, Hui Xiong._ Arxiv 2025.

35. [**AdaReTaKe: Adaptive Redundancy Reduction to Perceive Longer for Video-language Understanding.**](https://arxiv.org/abs/2503.12559) _Xiao Wang, Qingyi Si, Jianlong Wu, Shiyu Zhu, Li Cao, Liqiang Nie._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SCZwangxiao/video-FlexReduc)](https://github.com/SCZwangxiao/video-FlexReduc)

36. [**Atlas: Multi-Scale Attention Improves Long Context Image Modeling.**](https://arxiv.org/abs/2503.12355) _Kumar Krishna Agrawal, Long Lian, Longchao Liu, Natalia Harguindeguy, Boyi Li, Alexander Bick, Maggie Chung, Trevor Darrell, Adam Yala._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/yalalab/atlas)](https://github.com/yalalab/atlas)

37. [**Multimodal Long Video Modeling Based on Temporal Dynamic Context.**](https://arxiv.org/abs/2504.10443) _Haoran Hao, Jiaming Han, Yiyuan Zhang, Xiangyu Yue._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Hoar012/TDC-Video)](https://github.com/Hoar012/TDC-Video)

38. [**Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding.**](https://arxiv.org/abs/2505.18079) _Xiaoyi Zhang, Zhaoyang Jia, Zongyu Guo, Jiahao Li, Bin Li, Houqiang Li, Yan Lu._ Arxiv 2025.

### 11. Benchmark and Evaluation

#### 11.1 LLM

1. [**Long Range Arena : A Benchmark for Efficient Transformers.**](https://arxiv.org/abs/2011.04006) _Yi Tay, Mostafa Dehghani, Samira Abnar, Yikang Shen, Dara Bahri, Philip Pham, Jinfeng Rao, Liu Yang, Sebastian Ruder, Donald Metzler._ ICLR 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/long-range-arena)](https://github.com/google-research/long-range-arena)

2. [**LOT: A Story-Centric Benchmark for Evaluating Chinese Long Text Understanding and Generation.**](https://aclanthology.org/2022.tacl-1.25.pdf) _Jian Guan, Zhuoer Feng, Yamei Chen, Ruilin He, Xiaoxi Mao, Changjie Fan, Minlie Huang._ TACL 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/thu-coai/LOT-LongLM)](https://github.com/thu-coai/LOT-LongLM)

3. [**SCROLLS: Standardized CompaRison Over Long Language Sequences.**](https://arxiv.org/abs/2201.03533) _Uri Shaham, Elad Segal, Maor Ivgi, Avia Efrat, Ori Yoran, Adi Haviv, Ankit Gupta, Wenhan Xiong, Mor Geva, Jonathan Berant, Omer Levy._ EMNLP 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/tau-nlp/scrolls)](https://github.com/tau-nlp/scrolls)

4. [**MuLD: The Multitask Long Document Benchmark.**](https://aclanthology.org/2022.lrec-1.392/) _George Hudson, Noura Al Moubayed._ LREC 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/ghomasHudson/muld)](https://github.com/ghomasHudson/muld)

5. [**Lost in the Middle: How Language Models Use Long Contexts.**](https://arxiv.org/abs/2307.03172) _Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/nelson-liu/lost-in-the-middle)](https://github.com/nelson-liu/lost-in-the-middle)

6. [**L-Eval: Instituting Standardized Evaluation for Long Context Language Models.**](https://arxiv.org/abs/2307.11088) _Chenxin An, Shansan Gong, Ming Zhong, Mukai Li, Jun Zhang, Lingpeng Kong, Xipeng Qiu._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenLMLab/LEval)](https://github.com/OpenLMLab/LEval)

7. [**LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding.**](https://arxiv.org/abs/2308.14508) _Yushi Bai, Xin Lv, Jiajie Zhang, Hongchang Lyu, Jiankai Tang, Zhidian Huang, Zhengxiao Du, Xiao Liu, Aohan Zeng, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongBench)](https://github.com/THUDM/LongBench)

8. [**Content Reduction, Surprisal and Information Density Estimation for Long Documents.**](https://arxiv.org/abs/2309.06009) _Shaoxiong Ji, Wei Sun, Pekka Marttinen._ Arxiv 2023.

9. [**BAMBOO: A Comprehensive Benchmark for Evaluating Long Text Modeling Capacities of Large Language Models.**](https://arxiv.org/abs/2309.13345) _Zican Dong, Tianyi Tang, Junyi Li, Wayne Xin Zhao, Ji-Rong Wen._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/BAMBOO)](https://github.com/RUCAIBox/BAMBOO)

10. [**Retrieval meets Long Context Large Language Models.**](https://arxiv.org/abs/2309.13345) _Peng Xu, Wei Ping, Xianchao Wu, Lawrence McAfee, Chen Zhu, Zihan Liu, Sandeep Subramanian, Evelina Bakhturina, Mohammad Shoeybi, Bryan Catanzaro._ Arxiv 2023.

11. [**LooGLE: Long Context Evaluation for Long-Context Language Models.**](https://arxiv.org/pdf/2311.04939v1.pdf) _Jiaqi Li, Mengmeng Wang, Zilong Zheng, Muhan Zhang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/loogle)](https://github.com/bigai-nlco/loogle)

12. [**The Impact of Reasoning Step Length on Large Language Models.**](https://arxiv.org/abs/2401.04925v1) _Mingyu Jin, Qinkai Yu, Dong shu, Haiyan Zhao, Wenyue Hua, Yanda Meng, Yongfeng Zhang, Mengnan Du._ Arxiv 2024.

13. [**DocFinQA: A Long-Context Financial Reasoning Dataset.**](https://arxiv.org/abs/2401.06915) _Varshini Reddy, Rik Koncel-Kedziorski, Viet Dac Lai, Chris Tanner._ Arxiv 2024.

14. [**LongFin: A Multimodal Document Understanding Model for Long Financial Domain Documents.**](https://arxiv.org/abs/2401.15050) _Ahmed Masry, Amir Hajian._ Arxiv 2024.

15. [**PROXYQA: An Alternative Framework for Evaluating Long-Form Text Generation with Large Language Models.**](https://arxiv.org/abs/2401.15042) _Haochen Tan, Zhijiang Guo, Zhan Shi, Lu Xu, Zhili Liu, Xiaoguang Li, Yasheng Wang, Lifeng Shang, Qun Liu, Linqi Song._ Arxiv 2024.

16. [**LongHealth: A Question Answering Benchmark with Long Clinical Documents.**](https://arxiv.org/abs/2401.14490) _Lisa Adams, Felix Busch, Tianyu Han, Jean-Baptiste Excoffier, Matthieu Ortala, Alexander Löser, Hugo JWL. Aerts, Jakob Nikolas Kather, Daniel Truhn, Keno Bressem._ Arxiv 2024.

17. [**Long-form evaluation of model editing.**](https://arxiv.org/abs/2402.09394) _Domenic Rosati, Robie Gonzales, Jinkun Chen, Xuemin Yu, Melis Erkan, Yahya Kayani, Satya Deepika Chavatapalli, Frank Rudzicz, Hassan Sajjad._ Arxiv 2024.

18. [**In Search of Needles in a 10M Haystack: Recurrent Memory Finds What LLMs Miss.**](https://arxiv.org/abs/2402.10790v1) _Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

19. [**∞Bench: Extending Long Context Evaluation Beyond 100K Tokens.**](https://arxiv.org/abs/2402.13718) _Xinrong Zhang, Yingfa Chen, Shengding Hu, Zihang Xu, Junhao Chen, Moo Khai Hao, Xu Han, Zhen Leng Thai, Shuo Wang, Zhiyuan Liu, Maosong Sun._ Arxiv 2024.

20. [**Same Task, More Tokens: the Impact of Input Length on the Reasoning Performance of Large Language Models.**](https://arxiv.org/abs/2402.14848) _Mosh Levy, Alon Jacoby, Yoav Goldberg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alonj/Same-Task-More-Tokens)](https://github.com/alonj/Same-Task-More-Tokens)

21. [**Evaluating Very Long-Term Conversational Memory of LLM Agents.**](https://arxiv.org/abs/2402.17753) _Adyasha Maharana, Dong-Ho Lee, Sergey Tulyakov, Mohit Bansal, Francesco Barbieri, Yuwei Fang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/snap-research/LoCoMo)](https://github.com/snap-research/LoCoMo)

22. [**Language Models as Science Tutors.**](https://arxiv.org/abs/2402.11111) _Alexis Chevalier, Jiayi Geng, Alexander Wettig, Howard Chen, Sebastian Mizera, Toni Annala, Max Jameson Aragon, Arturo Rodríguez Fanlo, Simon Frieder, Simon Machado, Akshara Prabhakar, Ellie Thieu, Jiachen T. Wang, Zirui Wang, Xindi Wu, Mengzhou Xia, Wenhan Jia, Jiatong Yu, Jun-Jie Zhu, Zhiyong Jason Ren, Sanjeev Arora, Danqi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/LM-Science-Tutor)](https://github.com/princeton-nlp/LM-Science-Tutor)

23. [**Needle in a haystack - pressure testing llms.**](https://github.com/gkamradt/LLMTest_NeedleInAHaystack) _Kamradt, G._ Github 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/gkamradt/LLMTest_NeedleInAHaystack)](https://github.com/gkamradt/LLMTest_NeedleInAHaystack)

24. [**In Search of Needles in a 11M Haystack: Recurrent Memory Finds What LLMs Miss.**](https://arxiv.org/abs/2402.10790) _Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

25. [**LV-Eval: A Balanced Long-Context Benchmark with 5 Length Levels Up to 256K.**](https://arxiv.org/abs/2402.05136) _Tao Yuan, Xuefei Ning, Dong Zhou, Zhijie Yang, Shiyao Li, Minghui Zhuang, Zheyue Tan, Zhuyu Yao, Dahua Lin, Boxun Li, Guohao Dai, Shengen Yan, Yu Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/infinigence/LVEval)](https://github.com/infinigence/LVEval)

26. [**Counting-Stars: A Simple, Efficient, and Reasonable Strategy for Evaluating Long-Context Large Language Models.**](https://arxiv.org/abs/2403.11802) _Mingyang Song, Mao Zheng, Xuan Luo._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/Counting-Stars)](https://github.com/nick7nlp/Counting-Stars)

27. [**NovelQA: A Benchmark for Long-Range Novel Question Answering.**](https://arxiv.org/abs/2403.12766) _Cunxiang Wang, Ruoxi Ning, Boqi Pan, Tonghui Wu, Qipeng Guo, Cheng Deng, Guangsheng Bao, Qian Wang, Yue Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NovelQA/novelqa.github.io)](https://github.com/NovelQA/novelqa.github.io)

28. [**Long-form factuality in large language models.**](https://arxiv.org/abs/2403.18802) _Jerry Wei, Chengrun Yang, Xinying Song, Yifeng Lu, Nathan Hu, Dustin Tran, Daiyi Peng, Ruibo Liu, Da Huang, Cosmo Du, Quoc V. Le._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/long-form-factuality)](https://github.com/google-deepmind/long-form-factuality)

29. [**LUQ: Long-text Uncertainty Quantification for LLMs.**](https://arxiv.org/abs/2403.20279) _JCaiqi Zhang, Fangyu Liu, Marco Basaldella, Nigel Collier._ Arxiv 2024.

30. [**CLongEval: A Chinese Benchmark for Evaluating Long-Context Large Language Models.**](https://arxiv.org/abs/2403.03514) _Zexuan Qiu, Jingjing Li, Shijue Huang, Wanjun Zhong, Irwin King._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zexuanqiu/CLongEval)](https://github.com/zexuanqiu/CLongEval)

31. [**Long-context LLMs Struggle with Long In-context Learning.**](https://arxiv.org/abs/2404.02060) _Tianle Li, Ge Zhang, Quy Duc Do, Xiang Yue, Wenhu Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/LongICLBench)](https://github.com/TIGER-AI-Lab/LongICLBench)

32. [**CLAPNQ: Cohesive Long-form Answers from Passages in Natural Questions for RAG systems.**](https://arxiv.org/abs/2404.02103) _Sara Rosenthal, Avirup Sil, Radu Florian, Salim Roukos._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/primeqa/clapnq)](https://github.com/primeqa/clapnq)

33. [**XL2Bench: A Benchmark for Extremely Long Context Understanding with Long-range Dependencies.**](https://arxiv.org/abs/2404.05446) _Xuanfan Ni, Hengyi Cai, Xiaochi Wei, Shuaiqiang Wang, Dawei Yin, Piji Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nuaa-nlp/XL2Bench)](https://github.com/nuaa-nlp/XL2Bench)

34. [**Never Train from Scratch: Fair Comparison of Long-Sequence Models Requires Data-Driven Priors.**](https://openreview.net/forum?id=PdaPky8MUn) _Ido Amos, Jonathan Berant, Ankit Gupta._ ICLR 2024 Oral.

35. [**Ada-LEval: Evaluating long-context LLMs with length-adaptable benchmarks.**](https://arxiv.org/abs/2404.06480) _Chonghua Wang, Haodong Duan, Songyang Zhang, Dahua Lin, Kai Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/Ada-LEval)](https://github.com/open-compass/Ada-LEval)

36. [**RULER: What's the Real Context Size of Your Long-Context Language Models?.**](https://arxiv.org/abs/2404.06654) _Cheng-Ping Hsieh, Simeng Sun, Samuel Kriman, Shantanu Acharya, Dima Rekesh, Fei Jia, Boris Ginsburg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/hsiehjackson/RULER)](https://github.com/hsiehjackson/RULER)

37. [**LongEmbed: Extending Embedding Models for Long Context Retrieval.**](https://arxiv.org/abs/2404.12096) _Dawei Zhu, Liang Wang, Nan Yang, Yifan Song, Wenhao Wu, Furu Wei, Sujian Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/LongEmbed)](https://github.com/dwzhu-pku/LongEmbed)

38. [**Make Your LLM Fully Utilize the Context.**](https://arxiv.org/abs/2404.16811) _Shengnan An, Zexiong Ma, Zeqi Lin, Nanning Zheng, Jian-Guang Lou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/FILM)](https://github.com/microsoft/FILM)

39. [**S3Eval: A Synthetic, Scalable, Systematic Evaluation Suite for Large Language Models.**](https://arxiv.org/abs/2310.15147) _Fangyu Lei, Qian Liu, Yiming Huang, Shizhu He, Jun Zhao, Kang Liu._ NAACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/lfy79001/S3Eval)](https://github.com/lfy79001/S3Eval)

40. [**In-Context Learning with Long-Context Models: An In-Depth Exploration.**](https://arxiv.org/abs/2405.00200) _Amanda Bertsch, Maor Ivgi, Uri Alon, Jonathan Berant, Matthew R. Gormley, Graham Neubig._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/abertsch72/long-context-icl)](https://github.com/abertsch72/long-context-icl)

41. [**Many-shot Jailbreaking.**](https://www-cdn.anthropic.com/af5633c94ed2beb282f6a53c595eb437e8e7b630/Many_Shot_Jailbreaking__2024_04_02_0936.pdf) Anthropic 2024.

42. [**DOLOMITES: Domain-Specific Long-Form Methodical Tasks.**](https://arxiv.org/abs/2405.05938) _Chaitanya Malaviya, Priyanka Agrawal, Kuzman Ganchev, Pranesh Srinivasan, Fantine Huot, Jonathan Berant, Mark Yatskar, Dipanjan Das, Mirella Lapata, Chris Alberti._ Arxiv 2024.

43. [**Challenges in Deploying Long-Context Transformers: A Theoretical Peak Performance Analysis.**](https://arxiv.org/abs/2405.08944) _Yao Fu._ Arxiv 2024.

44. [**FinTextQA: A Dataset for Long-form Financial Question Answering.**](https://arxiv.org/abs/2405.09980) _Jian Chen, Peilin Zhou, Yining Hua, Yingxin Loh, Kehui Chen, Ziyuan Li, Bing Zhu, Junwei Liang._ Arxiv 2024.

45. [**A Multi-Perspective Analysis of Memorization in Large Language Models.**](https://arxiv.org/abs/2405.11577) _Bowen Chen, Namgi Han, Yusuke Miyao._ Arxiv 2024.

46. [**OLAPH: Improving Factuality in Biomedical Long-form Question Answering.**](https://arxiv.org/abs/2405.12701) _Minbyul Jeong, Hyeon Hwang, Chanwoong Yoon, Taewhoo Lee, Jaewoo Kang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dmis-lab/OLAPH)](https://github.com/dmis-lab/OLAPH)

47. [**Can LLMs Solve longer Math Word Problems Better?.**](https://arxiv.org/abs/2405.14804) _Xin Xu, Tong Xiao, Zitong Chao, Zhenya Huang, Can Yang, Yang Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/XinXU-USTC/CoLeG-Math)](https://github.com/XinXU-USTC/CoLeG-Math)

48. [**Base of RoPE Bounds Context Length.**](https://arxiv.org/abs/2405.14591) _Xin Men, Mingyu Xu, Bingning Wang, Qingyu Zhang, Hongyu Lin, Xianpei Han, Weipeng Chen._ Arxiv 2024.

49. [**Many-shot In-Context Learning.**](https://arxiv.org/abs/2404.11018) _Rishabh Agarwal, Avi Singh, Lei M. Zhang, Bernd Bohnet, Luis Rosias, Stephanie Chan, Biao Zhang, Ankesh Anand, Zaheer Abbas, Azade Nova, John D. Co-Reyes, Eric Chu, Feryal Behbahani, Aleksandra Faust, Hugo Larochelle._ Arxiv 2024.

50. [**Long Context is Not Long at All: A Prospector of Long-Dependency Data for Large Language Models.**](https://arxiv.org/abs/2405.17915) _Longze Chen, Ziqiang Liu, Wanwei He, Yunshui Li, Run Luo, Min Yang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/October2001/ProLong)](https://github.com/October2001/ProLong)

51. [**Language Models Need Inductive Biases to Count Inductively.**](https://arxiv.org/abs/2405.20131) _Yingshan Chang, Yonatan Bisk._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zdxdsw/inductive_counting_with_LMs)](https://github.com/zdxdsw/inductive_counting_with_LMs)

52. [**Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding.**](https://arxiv.org/abs/2406.02472) _Zhihan Zhang, Yixin Cao, Chenchen Ye, Yunshan Ma, Lizi Liao, Tat-Seng Chua._ Arxiv 2024.

53. [**CRAG -- Comprehensive RAG Benchmark.**](https://arxiv.org/abs/2406.04744) _Xiao Yang, Kai Sun, Hao Xin, Yushi Sun, Nikita Bhalla, Xiangsen Chen, Sajal Choudhary, Rongze Daniel Gui, Ziran Will Jiang, Ziyu Jiang, Lingkun Kong, Brian Moran, Jiaqi Wang, Yifan Ethan Xu, An Yan, Chenyu Yang, Eting Yuan, Hanwen Zha, Nan Tang, Lei Chen, Nicolas Scheffer, Yue Liu, Nirav Shah, Rakesh Wanga, Anuj Kumar, Wen-tau Yih, Xin Luna Dong._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.aicrowd.com/challenges/meta-comprehensive-rag-benchmark-kdd-cup-2024)

54. [**An Empirical Study of Mamba-based Language Models.**](https://arxiv.org/abs/2406.07887) _Roger Waleffe, Wonmin Byeon, Duncan Riach, Brandon Norick, Vijay Korthikanti, Tri Dao, Albert Gu, Ali Hatamizadeh, Sudhakar Singh, Deepak Narayanan, Garvit Kulshreshtha, Vartika Singh, Jared Casper, Jan Kautz, Mohammad Shoeybi, Bryan Catanzaro._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Megatron-LM)](https://github.com/NVIDIA/Megatron-LM/tree/ssm/examples/mamba)

55. [**BABILong: Testing the Limits of LLMs with Long Context Reasoning-in-a-Haystack.**](https://arxiv.org/abs/2406.10149) _Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Ivan Rodkin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

56. [**Can Many-Shot In-Context Learning Help Long-Context LLM Judges? See More, Judge Better!.**](https://arxiv.org/abs/2406.11629) _Mingyang Song, Mao Zheng, Xuan Luo._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/SeeMoreJudgeBetter)](https://github.com/nick7nlp/SeeMoreJudgeBetter)

57. [**What Kinds of Tokens Benefit from Distant Text? An Analysis on Long Context Language Modeling.**](https://arxiv.org/abs/2406.11238) _Yutong Hu, Quzhe Huang, Kangcheng Luo, Yansong Feng._ Arxiv 2024.

58. [**Understanding the RoPE Extensions of Long-Context LLMs: An Attention Perspective.**](https://arxiv.org/abs/2406.13282) _Meizhi Zhong, Chen Zhang, Yikun Lei, Xikai Liu, Yan Gao, Yao Hu, Kehai Chen, Min Zhang._ Arxiv 2024.

59. [**Can Long-Context Language Models Subsume Retrieval, RAG, SQL, and More?.**](https://arxiv.org/abs/2406.13121) _Jinhyuk Lee, Anthony Chen, Zhuyun Dai, Dheeru Dua, Devendra Singh Sachan, Michael Boratko, Yi Luan, Sébastien M. R. Arnold, Vincent Perot, Siddharth Dalmia, Hexiang Hu, Xudong Lin, Panupong Pasupat, Aida Amini, Jeremy R. Cole, Sebastian Riedel, Iftekhar Naim, Ming-Wei Chang, Kelvin Guu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/loft)](https://github.com/google-deepmind/loft)

60. [**Insights into LLM Long-Context Failures: When Transformers Know but Don't Tell.**](https://arxiv.org/abs/2406.14673) _Taiming Lu, Muhan Gao, Kuai Yu, Adam Byerly, Daniel Khashabi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TaiMingLu/know-dont-tell)](https://github.com/TaiMingLu/know-dont-tell)

61. [**MedOdyssey: A Medical Domain Benchmark for Long Context Evaluation Up to 200K Tokens.**](https://arxiv.org/abs/2406.15019) _Yongqi Fan, Hongli Sun, Kui Xue, Xiaofan Zhang, Shaoting Zhang, Tong Ruan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JOHNNY-fans/MedOdyssey)](https://github.com/JOHNNY-fans/MedOdyssey)

62. [**USDC: A Dataset of $\underline{U}$ser $\underline{S}$tance and $\underline{D}$ogmatism in Long $\underline{C}$onversations.**](https://arxiv.org/abs/2406.16833) _Mounika Marreddy, Subba Reddy Oota, Venkata Charan Chinni, Manish Gupta, Lucie Flek._ Arxiv 2024.

63. [**Found in the Middle: Calibrating Positional Attention Bias Improves Long Context Utilization.**](https://arxiv.org/abs/2406.16008) _Cheng-Yu Hsieh, Yung-Sung Chuang, Chun-Liang Li, Zifeng Wang, Long T. Le, Abhishek Kumar, James Glass, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister._ Arxiv 2024.

64. [**One Thousand and One Pairs: A "novel" challenge for long-context language models.**](https://arxiv.org/abs/2406.16264) _Marzena Karpinska, Katherine Thai, Kyle Lo, Tanya Goyal, Mohit Iyyer._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/marzenakrp/nocha)](https://github.com/marzenakrp/nocha/)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://novelchallenge.github.io/)

65. [**LongIns: A Challenging Long-context Instruction-based Exam for LLMs.**](https://arxiv.org/abs/2406.17588) _Shawn Gavin, Tuney Zheng, Jiaheng Liu, Quehry Que, Noah Wang, Jian Yang, Chenchen Zhang, Wenhao Huang, Wenhu Chen, Ge Zhang._ Arxiv 2024.

66. [**Leave No Document Behind: Benchmarking Long-Context LLMs with Extended Multi-Doc QA.**](https://arxiv.org/abs/2406.17419) _Minzheng Wang, Longze Chen, Cheng Fu, Shengyi Liao, Xinghua Zhang, Bingli Wu, Haiyang Yu, Nan Xu, Lei Zhang, Run Luo, Yunshui Li, Min Yang, Fei Huang, Yongbin Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/MozerWang/Loong)](https://github.com/MozerWang/Loong)

67. [**VERISCORE: Evaluating the factuality of verifiable claims in long-form text generation.**](https://arxiv.org/abs/2406.19276) _Yixiao Song, Yekyung Kim, Mohit Iyyer._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Yixiao-Song/VeriScore)](https://github.com/Yixiao-Song/VeriScore)

68. [**ToolBeHonest: A Multi-level Hallucination Diagnostic Benchmark for Tool-Augmented Large Language Models.**](https://arxiv.org/abs/2406.20015) _Yuxiang Zhang, Jing Chen, Junjie Wang, Yaxin Liu, Cheng Yang, Chufan Shi, Xinyu Zhu, Zihao Lin, Hanwen Wan, Yujiu Yang, Tetsuya Sakai, Tian Feng, Hayato Yamana._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ToolBeHonest/ToolBeHonest)](https://github.com/ToolBeHonest/ToolBeHonest)

69. [**KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches.**](https://arxiv.org/abs/2407.01527) _Jiayi Yuan, Hongyi Liu, Shaochen (Henry)Zhong, Yu-Neng Chuang, Songchen Li, Guanchu Wang, Duy Le, Hongye Jin, Vipin Chaudhary, Zhaozhuo Xu, Zirui Liu, Xia Hu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/henryzhongsc/longctx_bench)](https://github.com/henryzhongsc/longctx_bench)

70. [**Is It Really Long Context if All You Need Is Retrieval? Towards Genuinely Difficult Long Context NLP.**](https://arxiv.org/abs/2407.00402) _Omer Goldman, Alon Jacovi, Aviv Slobodkin, Aviya Maimon, Ido Dagan, Reut Tsarfaty._ Arxiv 2024.

71. [**Summary of a Haystack: A Challenge to Long-Context LLMs and RAG Systems.**](https://arxiv.org/abs/2407.01370) _Philippe Laban, Alexander R. Fabbri, Caiming Xiong, Chien-Sheng Wu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/salesforce/summary-of-a-haystack)](https://github.com/salesforce/summary-of-a-haystack)

72. [**Entity-Level Sentiment: More than the Sum of Its Parts.**](https://arxiv.org/abs/2407.03916) _Egil Rønningstad, Roman Klinger, Erik Velldal, Lilja Øvrelid._ Arxiv 2024.

73. [**Evaluating Language Model Context Windows: A "Working Memory" Test and Inference-time Correction.**](https://arxiv.org/abs/2407.03651) _Amanda Dsouza, Christopher Glaze, Changho Shin, Frederic Sala._ Arxiv 2024.

74. [**RAG vs. Long Context: Examining Frontier Large Language Models for Environmental Review Document Comprehension.**](https://arxiv.org/abs/2407.07321) _Hung Phan, Anurag Acharya, Sarthak Chaturvedi, Shivam Sharma, Mike Parker, Dan Nally, Ali Jannesari, Karl Pazdernik, Mahantesh Halappanavar, Sai Munikoti, Sameera Horawalavithana._ Arxiv 2024.

75. [**Attribute or Abstain: Large Language Models as Long Document Assistants.**](https://arxiv.org/abs/2407.07799) _Jan Buchmann, Xiao Liu, Iryna Gurevych._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/UKPLab/arxiv2024-attribute-or-abstain)](https://github.com/UKPLab/arxiv2024-attribute-or-abstain)

76. [**How Well Can a Long Sequence Model Model Long Sequences? Comparing Architechtural Inductive Biases on Long-Context Abilities.**](https://arxiv.org/abs/2407.08112) _Jerry Huang._ Arxiv 2024.

77. [**DOCBENCH: A Benchmark for Evaluating LLM-based Document Reading Systems.**](https://arxiv.org/abs/2407.10701) _Anni Zou, Wenhao Yu, Hongming Zhang, Kaixin Ma, Deng Cai, Zhuosheng Zhang, Hai Zhao, Dong Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Anni-Zou/DocBench)](https://github.com/Anni-Zou/DocBench)

78. [**NeedleBench: Can LLMs Do Retrieval and Reasoning in 1 Million Context Window?.**](https://arxiv.org/abs/2407.11963) _Mo Li, Songyang Zhang, Yunxin Liu, Kai Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/opencompass)](https://github.com/open-compass/opencompass)

79. [**LongLaMP: A Benchmark for Personalized Long-form Text Generation.**](https://arxiv.org/abs/2407.11016) _Ishita Kumar, Snigdha Viswanathan, Sushrita Yerra, Alireza Salemi, Ryan A. Rossi, Franck Dernoncourt, Hanieh Deilamsalehy, Xiang Chen, Ruiyi Zhang, Shubham Agarwal, Nedim Lipka, Hamed Zamani._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://longlamp-benchmark.github.io/)

80. [**RAG-QA Arena: Evaluating Domain Robustness for Long-form Retrieval Augmented Question Answering.**](https://arxiv.org/abs/2407.13998) _Rujun Han, Yuhao Zhang, Peng Qi, Yumo Xu, Jenyuan Wang, Lan Liu, William Yang Wang, Bonan Min, Vittorio Castelli._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/awslabs/rag-qa-arena)](https://github.com/awslabs/rag-qa-arena)

81. [**Attention Is All You Need But You Don't Need All Of It For Inference of Large Language Models.**](https://arxiv.org/abs/2407.15516) _Georgy Tyukin, Gbetondji J-S Dovonon, Jean Kaddour, Pasquale Minervini._ ICML 2024 TF2M workshop.

82. [**Stress-Testing Long-Context Language Models with Lifelong ICL and Task Haystack.**](https://arxiv.org/abs/2407.16695) _Xiaoyue Xu, Qinyuan Ye, Xiang Ren._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/INK-USC/Lifelong-ICL)](https://github.com/INK-USC/Lifelong-ICL)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://inklab.usc.edu/lifelong-icl/)

83. [**WildHallucinations: Evaluating Long-form Factuality in LLMs with Real-World Entity Queries.**](https://arxiv.org/abs/2407.17468) _Wenting Zhao, Tanya Goyal, Yu Ying Chiu, Liwei Jiang, Benjamin Newman, Abhilasha Ravichander, Khyathi Chandu, Ronan Le Bras, Claire Cardie, Yuntian Deng, Yejin Choi._ Arxiv 2024.

84. [**Retrieval Augmented Generation or Long-Context LLMs? A Comprehensive Study and Hybrid Approach.**](https://arxiv.org/abs/2407.16833) _Zhuowan Li, Cheng Li, Mingyang Zhang, Qiaozhu Mei, Michael Bendersky._ Arxiv 2024.

85. [**Evaluating Long Range Dependency Handling in Code Generation Models using Multi-Step Key Retrieval.**](https://arxiv.org/abs/2407.21049) _Yannick Assogba, Donghao Ren._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/apple/ml-key-retrieval-code-tasks)](https://github.com/apple/ml-key-retrieval-code-tasks)

86. [**Long Input Benchmark for Russian Analysis.**](https://arxiv.org/abs/2408.02439) _Igor Churin, Murat Apishev, Maria Tikhonova, Denis Shevelev, Aydar Bulatov, Yuri Kuratov, Sergej Averkiev, Alena Fenogenova._ Arxiv 2024.

87. [**CoverBench: A Challenging Benchmark for Complex Claim Verification.**](https://arxiv.org/abs/2408.03325) _Alon Jacovi, Moran Ambar, Eyal Ben-David, Uri Shaham, Amir Feder, Mor Geva, Dror Marcus, Avi Caciularu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/datasets/google/coverbench)

88. [**LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs.**](https://arxiv.org/abs/2408.07055) _Yushi Bai, Jiajie Zhang, Xin Lv, Linzhi Zheng, Siqi Zhu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongWriter)](https://github.com/THUDM/LongWriter)

89. [**Multilingual Needle in a Haystack: Investigating Long-Context Behavior of Multilingual Large Language Models.**](https://arxiv.org/abs/2408.10151) _Amey Hengle, Prasoon Bajpai, Soham Dan, Tanmoy Chakraborty._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AmeyHengle/multilingual-needle-in-a-haystack)](https://github.com/AmeyHengle/multilingual-needle-in-a-haystack)

90. [**LongGenBench: Benchmarking Long-Form Generation in Long Context LLMs.**](https://arxiv.org/abs/2409.02076) _Yuhao Wu, Ming Shan Hee, Zhiqing Hu, Roy Ka-Wei Lee._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mozhu621/LongGenBench)](https://github.com/mozhu621/LongGenBench/)

91. [**What are the Essential Factors in Crafting Effective Long Context Multi-Hop Instruction Datasets? Insights and Best Practices.**](https://arxiv.org/abs/2409.01893) _Zhi Chen, Qiguang Chen, Libo Qin, Qipeng Guo, Haijun Lv, Yicheng Zou, Wanxiang Che, Hang Yan, Kai Chen, Dahua Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WowCZ/LongMIT)](https://github.com/WowCZ/LongMIT)

92. [**Retrieval Or Holistic Understanding? Dolce: Differentiate Our Long Context Evaluation Tasks.**](https://arxiv.org/abs/2409.06338) _Zi Yang._ Arxiv 2024.

93. [**A Controlled Study on Long Context Extension and Generalization in LLMs.**](https://arxiv.org/abs/2409.12181) _Yi Lu, Jing Nathan Yan, Songlin Yang, Justin T. Chiu, Siyu Ren, Fei Yuan, Wenting Zhao, Zhiyong Wu, Alexander M. Rush._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Leooyii/LCEG)](https://github.com/Leooyii/LCEG)

94. [**RAD-Bench: Evaluating Large Language Models Capabilities in Retrieval Augmented Dialogues.**](https://arxiv.org/abs/2409.12558) _Tzu-Lin Kuo, Feng-Ting Liao, Mu-Wei Hsieh, Fu-Chieh Chang, Po-Chun Hsu, Da-Shan Shiu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mtkresearch/RAD-Bench)](https://github.com/mtkresearch/RAD-Bench)

95. [**Fact, Fetch, and Reason: A Unified Evaluation of Retrieval-Augmented Generation.**](https://arxiv.org/abs/2409.12941) _Satyapriya Krishna, Kalpesh Krishna, Anhad Mohananey, Steven Schwarcz, Adam Stambler, Shyam Upadhyay, Manaal Faruqui._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/datasets/google/frames-benchmark)

96. [**Michelangelo: Long Context Evaluations Beyond Haystacks via Latent Structure Queries.**](https://arxiv.org/abs/2409.12640) _Kiran Vodrahalli, Santiago Ontanon, Nilesh Tripuraneni, Kelvin Xu, Sanil Jain, Rakesh Shivanna, Jeffrey Hui, Nishanth Dikkala, Mehran Kazemi, Bahare Fatemi, Rohan Anil, Ethan Dyer, Siamak Shakeri, Roopali Vij, Harsh Mehta, Vinay Ramasesh, Quoc Le, Ed Chi, Yifeng Lu, Orhan Firat, Angeliki Lazaridou, Jean-Baptiste Lespiau, Nithya Attaluri, Kate Olszewska._ Arxiv 2024.

97. [**DetectiveQA: Evaluating Long-Context Reasoning on Detective Novels.**](https://arxiv.org/abs/2409.02465) _Zhe Xu, Jiasheng Ye, Xiangyang Liu, Tianxiang Sun, Xiaoran Liu, Qipeng Guo, Linlin Li, Qun Liu, Xuanjing Huang, Xipeng Qiu._ Arxiv 2024.

98. [**LongCite: Enabling LLMs to Generate Fine-grained Citations in Long-context QA.**](https://arxiv.org/abs/2409.02897) _Jiajie Zhang, Yushi Bai, Xin Lv, Wanjun Gu, Danqing Liu, Minhao Zou, Shulin Cao, Lei Hou, Yuxiao Dong, Ling Feng, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongCite)](https://github.com/THUDM/LongCite)

99. [**HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models.**](https://arxiv.org/abs/2409.16191) _Haoran Que, Feiyu Duan, Liqun He, Yutao Mou, Wangchunshu Zhou, Jiaheng Liu, Wenge Rong, Zekun Moore Wang, Jian Yang, Ge Zhang, Junran Peng, Zhaoxiang Zhang, Songyang Zhang, Kai Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Tintri/hello-bench)](https://github.com/Tintri/hello-bench)

100. [**Multilingual Evaluation of Long Context Retrieval and Reasoning.**](https://arxiv.org/abs/2409.18006) _Ameeta Agrawal, Andy Dang, Sina Bagheri Nezhad, Rhitabrat Pokharel, Russell Scheinberg._ Arxiv 2024.

101. [**L-CiteEval: Do Long-Context Models Truly Leverage Context for Responding?**](https://arxiv.org/abs/2410.02115) _Zecheng Tang, Keyan Zhou, Juntao Li, Baibei Ji, Jianye Hou, Min Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ZetangForward/L-CITEEVAL)](https://github.com/ZetangForward/L-CITEEVAL)

102. [**HELMET: How to Evaluate Long-Context Language Models Effectively and Thoroughly.**](https://arxiv.org/abs/2410.02694) _Howard Yen, Tianyu Gao, Minmin Hou, Ke Ding, Daniel Fleischer, Peter Izasak, Moshe Wasserblat, Danqi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/HELMET)](https://github.com/princeton-nlp/HELMET)

103. [**MathHay: An Automated Benchmark for Long-Context Mathematical Reasoning in LLMs.**](https://arxiv.org/abs/2410.04698) _Lei Wang, Shan Dong, Yuhui Xu, Hanze Dong, Yalu Wang, Amrita Saha, Ee-Peng Lim, Caiming Xiong, Doyen Sahoo._ Arxiv 2024.

104. [**LongGenBench: Long-context Generation Benchmark.**](https://arxiv.org/abs/2410.04199) _Xiang Liu, Peijie Dong, Xuming Hu, Xiaowen Chu._ EMNLP 2024.

105. [**Hyper-multi-step: The Truth Behind Difficult Long-context Tasks.**](https://arxiv.org/abs/2410.04422) _Yijiong Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yuyijiong/hard_retrieval_for_llm)](https://github.com/yuyijiong/hard_retrieval_for_llm)

106. [**Holistic Reasoning with Long-Context LMs: A Benchmark for Database Operations on Massive Textual Data.**](https://arxiv.org/abs/2410.11996) _Seiji Maekawa, Hayate Iso, Nikita Bhutani._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/megagonlabs/holobench)](https://github.com/megagonlabs/holobench)

107. [**How much do contextualized representations encode long-range context?.**](https://arxiv.org/abs/2410.12292) _Simeng Sun, Cheng-Ping Hsieh._ Arxiv 2024.

108. [**LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory.**](https://arxiv.org/abs/2410.10813) _Di Wu, Hongwei Wang, Wenhao Yu, Yuwei Zhang, Kai-Wei Chang, Dong Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/xiaowu0162/LongMemEval)](https://github.com/xiaowu0162/LongMemEval)

109. [**When Attention Sink Emerges in Language Models: An Empirical View.**](https://arxiv.org/abs/2410.10781) _Xiangming Gu, Tianyu Pang, Chao Du, Qian Liu, Fengzhuo Zhang, Cunxiao Du, Ye Wang, Min Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/Attention-Sink)](https://github.com/sail-sg/Attention-Sink)

110. [**Minimum Tuning to Unlock Long Output from LLMs with High Quality Data as the Key.**](https://arxiv.org/abs/2410.10210) _Yingda Chen, Xingjun Wang, Jintao Huang, Yunlin Mao, Daoze Zhang, Yuze Zhao._ Arxiv 2024.

111. [**Distance between Relevant Information Pieces Causes Bias in Long-Context LLMs.**](https://arxiv.org/abs/2410.14641) _Runchu Tian, Yanghao Li, Yuepeng Fu, Siyang Deng, Qinyu Luo, Cheng Qian, Shuo Wang, Xin Cong, Zhong Zhang, Yesai Wu, Yankai Lin, Huadong Wang, Xiaojiang Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Rachum-thu/LongPiBench)](https://github.com/Rachum-thu/LongPiBench)

112. [**ETHIC: Evaluating Large Language Models on Long-Context Tasks with High Information Coverage.**](https://arxiv.org/abs/2410.16848) _Taewhoo Lee, Chanwoong Yoon, Kyochul Jang, Donghyeon Lee, Minju Song, Hyunjae Kim, Jaewoo Kang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dmis-lab/ETHIC)](https://github.com/dmis-lab/ETHIC)

113. [**Long2RAG: Evaluating Long-Context & Long-Form Retrieval-Augmented Generation with Key Point Recall.**](https://arxiv.org/abs/2410.23000) _Zehan Qi, Rongwu Xu, Zhijiang Guo, Cunxiang Wang, Hao Zhang, Wei Xu._ EMNLP 2024.

114. [**Needle Threading: Can LLMs Follow Threads through Near-Million-Scale Haystacks?.**](https://arxiv.org/abs/2411.05000) _Jonathan Roberts, Kai Han, Samuel Albanie._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/jonathan-roberts1/needle-threading)](https://github.com/jonathan-roberts1/needle-threading)

115. [**Retrieval or Global Context Understanding? On Many-Shot In-Context Learning for Long-Context Evaluation.**](https://arxiv.org/abs/2411.07130) _Kaijian Zou, Muhammad Khalifa, Lu Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/launchnlp/ManyICLBench)](https://github.com/launchnlp/ManyICLBench)

116. [**LIFBench: Evaluating the Instruction Following Performance and Stability of Large Language Models in Long-Context Scenarios.**](https://arxiv.org/abs/2411.07037) _Xiaodong Wu, Minhao Wang, Yichen Liu, Xiaoming Shi, He Yan, Xiangju Lu, Junmin Zhu, Wei Zhang._ Arxiv 2024.

117. [**Spider 2.0: Evaluating Language Models on Real-World Enterprise Text-to-SQL Workflows.**](https://arxiv.org/abs/2411.07763) _Fangyu Lei, Jixuan Chen, Yuxiao Ye, Ruisheng Cao, Dongchan Shin, Hongjin Su, Zhaoqing Suo, Hongcheng Gao, Wenjing Hu, Pengcheng Yin, Victor Zhong, Caiming Xiong, Ruoxi Sun, Qian Liu, Sida Wang, Tao Yu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://spider2-sql.github.io/)
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/Spider2)](https://github.com/xlang-ai/Spider2)

118. [**A Benchmark for Long-Form Medical Question Answering.**](https://arxiv.org/abs/2411.09834) _Pedram Hosseini, Jessica M. Sin, Bing Ren, Bryceton G. Thomas, Elnaz Nouri, Ali Farahanchi, Saeed Hassanpour._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/lavita-ai/medical-eval-sphere)](https://github.com/lavita-ai/medical-eval-sphere)

119. [**DENIAHL: In-Context Features Influence LLM Needle-In-A-Haystack Abilities.**](https://arxiv.org/abs/2411.19360) _Hui Dai, Dan Pechi, Xinyi Yang, Garvit Banga, Raghav Mantri._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ameliadai/DENIAHL)](https://github.com/ameliadai/DENIAHL)

120. [**LCFO: Long Context and Long Form Output Dataset and Benchmarking.**](https://arxiv.org/abs/2412.08268) _Marta R. Costa-jussà, Pierre Andrews, Mariano Coria Meglioli, Joy Chen, Joe Chuang, David Dale, Christophe Ropers, Alexandre Mourachko, Eduardo Sánchez, Holger Schwenk, Tuan Tran, Arina Turkatenko, Carleigh Wood._ Arxiv 2024.

121. [**SCBench: A KV Cache-Centric Analysis of Long-Context Methods.**](https://arxiv.org/abs/2412.10319) _Yucheng Li, Huiqiang Jiang, Qianhui Wu, Xufang Luo, Surin Ahn, Chengruidong Zhang, Amir H. Abdi, Dongsheng Li, Jianfeng Gao, Yuqing Yang, Lili Qiu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://hqjiang.com/scbench.html)

122. [**LongBench v2: Towards Deeper Understanding and Reasoning on Realistic Long-context Multitasks.**](https://arxiv.org/abs/2412.15204) _Yushi Bai, Shangqing Tu, Jiajie Zhang, Hao Peng, Xiaozhi Wang, Xin Lv, Shulin Cao, Jiazheng Xu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongBench)](https://github.com/THUDM/LongBench)

123. [**XRAG: eXamining the Core -- Benchmarking Foundational Components in Advanced Retrieval-Augmented Generation.**](https://arxiv.org/abs/2412.15529) _Qianren Mao, Yangyifei Luo, Jinlong Zhang, Hanwen Hao, Zhilong Cao, Xiaolong Wang, Xiao Guan, Zhenting Huang, Weifeng Jiang, Shuyu Guo, Zhentao Han, Qili Zhang, Siyuan Tao, Yujie Liu, Junnan Liu, Zhixing Tan, Jie Sun, Bo Li, Xudong Liu, Richong Zhang, Jianxin Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DocAILab/XRAG)](https://github.com/DocAILab/XRAG)

124. [**RepoTransBench: A Real-World Benchmark for Repository-Level Code Translation.**](https://arxiv.org/abs/2412.17744) _Yanli Wang, Yanlin Wang, Suiquan Wang, Daya Guo, Jiachi Chen, John Grundy, Xilin Liu, Yuchi Ma, Mingzhi Mao, Hongyu Zhang, Zibin Zheng._ Arxiv 2024.

125. [**Long Context vs. RAG for LLMs: An Evaluation and Revisits.**](https://arxiv.org/abs/2501.01880) _Xinze Li, Yixin Cao, Yubo Ma, Aixin Sun._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lixinze777/LC_VS_RAG)](https://github.com/lixinze777/LC_VS_RAG)

126. [**The FACTS Grounding Leaderboard: Benchmarking LLMs' Ability to Ground Responses to Long-Form Input.**](https://arxiv.org/abs/2501.03200) _Alon Jacovi, Andrew Wang, Chris Alberti, Connie Tao, Jon Lipovetz, Kate Olszewska, Lukas Haas, Michelle Liu, Nate Keating, Adam Bloniarz, Carl Saroufim, Corey Fry, Dror Marcus, Doron Kukliansky, Gaurav Singh Tomar, James Swirhun, Jinwei Xing, Lily Wang, Madhu Gurumurthy, Michael Aaron, Moran Ambar, Rachana Fellinger, Rui Wang, Zizhao Zhang, Sasha Goldshtein, Dipanjan Das._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.kaggle.com/facts-leaderboard)

127. [**MTRAG: A Multi-Turn Conversational Benchmark for Evaluating Retrieval-Augmented Generation Systems.**](https://arxiv.org/abs/2501.03468) _Yannis Katsis, Sara Rosenthal, Kshitij Fadnis, Chulaka Gunasekara, Young-Suk Lee, Lucian Popa, Vraj Shah, Huaiyu Zhu, Danish Contractor, Marina Danilevsky._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ibm/mt-rag-benchmark)](https://github.com/ibm/mt-rag-benchmark)

128. [**ComplexFuncBench: Exploring Multi-Step and Constrained Function Calling under Long-Context Scenario.**](https://arxiv.org/abs/2501.10132) _Lucen Zhong, Zhengxiao Du, Xiaohan Zhang, Haiyi Hu, Jie Tang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/ComplexFuncBench)](https://github.com/THUDM/ComplexFuncBench)

129. [**RedStar: Does Scaling Long-CoT Data Unlock Better Slow-Reasoning Systems?.**](https://arxiv.org/abs/2501.11284) _Haotian Xu, Xing Wu, Weinong Wang, Zhongzhi Li, Da Zheng, Boyuan Chen, Yi Hu, Shijia Kang, Jiaming Ji, Yingying Zhang, Zhijiang Guo, Yaodong Yang, Muhan Zhang, Debing Zhang._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/RedStar-Reasoning)

130. [**LongReason: A Synthetic Long-Context Reasoning Benchmark via Context Expansion.**](https://arxiv.org/abs/2501.15089) _Zhan Ling, Kang Liu, Kai Yan, Yifan Yang, Weijian Lin, Ting-Han Fan, Lingfeng Shen, Zhengyin Du, Jiecao Chen._ Arxiv 2025.

131. [**Explaining Context Length Scaling and Bounds for Language Models.**](https://arxiv.org/abs/2502.01481) _Jingzhe Shi, Qinwei Ma, Hongyi Liu, Hang Zhao, Jeng-Neng Hwang, Serge Belongie, Lei Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/JingzheShi/NLPCtlScalingAndBounds)](https://github.com/JingzheShi/NLPCtlScalingAndBounds)

132. [**Attention Sinks and Outlier Features: A 'Catch, Tag, and Release' Mechanism for Embeddings.**](https://arxiv.org/abs/2502.00919) _Stephen Zhang, Mustafa Khan, Vardan Papyan._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://catch-tag-release.github.io/)

133. [**Demystifying Long Chain-of-Thought Reasoning in LLMs.**](https://arxiv.org/abs/2502.03373) _Edward Yeo, Yuxuan Tong, Morry Niu, Graham Neubig, Xiang Yue._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/eddycmu/demystify-long-cot)](https://github.com/eddycmu/demystify-long-cot)

134. [**BOLT: Bootstrap Long Chain-of-Thought in Language Models without Distillation.**](https://arxiv.org/abs/2502.03860) _Bo Pang, Hanze Dong, Jiacheng Xu, Silvio Savarese, Yingbo Zhou, Caiming Xiong._ Arxiv 2025.

135. [**NoLiMa: Long-Context Evaluation Beyond Literal Matching.**](https://arxiv.org/abs/2502.05167) _Ali Modarressi, Hanieh Deilamsalehy, Franck Dernoncourt, Trung Bui, Ryan A. Rossi, Seunghyun Yoon, Hinrich Schütze._ Arxiv 2025.

136. [**Technical Debt in In-Context Learning: Diminishing Efficiency in Long Context.**](https://arxiv.org/abs/2502.04580) _Taejong Joo, Diego Klabjan._ Arxiv 2025.

137. [**Demystifying Long Chain-of-Thought Reasoning in LLMs.**](https://arxiv.org/abs/2502.03373) _Edward Yeo, Yuxuan Tong, Morry Niu, Graham Neubig, Xiang Yue._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/gsm)](https://github.com/Infini-AI-Lab/gsm)
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://infini-ai-lab.github.io/gsm_infinite/)

138. [**DebateBench: A Challenging Long Context Reasoning Benchmark For Large Language Models.**](https://arxiv.org/abs/2502.06279) _Utkarsh Tiwari, Aryan Seth, Adi Mukherjee, Kaavya Mer, Kavish, Dhruv Kumar._ Arxiv 2025.

139. [**CLOVER: A Test Case Generation Benchmark with Coverage, Long-Context, and Verification.**](https://arxiv.org/abs/2502.08806) _Jiacheng Xu, Bo Pang, Jin Qu, Hiroaki Hayashi, Caiming Xiong, Yingbo Zhou._ Arxiv 2025.

140. [**MIR-Bench: Benchmarking LLM's Long-Context Intelligence via Many-Shot In-Context Inductive Reasoning.**](https://arxiv.org/abs/2502.09933) _Kai Yan, Zhan Ling, Kang Liu, Yifan Yang, Ting-Han Fan, Lingfeng Shen, Zhengyin Du, Jiecao Chen._ Arxiv 2025.

141. [**LaRA: Benchmarking Retrieval-Augmented Generation and Long-Context LLMs - No Silver Bullet for LC or RAG Routing.**](https://arxiv.org/abs/2502.09977) _Kuan Li, Liwen Zhang, Yong Jiang, Pengjun Xie, Fei Huang, Shuai Wang, Minhao Cheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/likuanppd/LaRA)](https://github.com/likuanppd/LaRA)

142. [**Does RAG Really Perform Bad For Long-Context Processing?.**](https://arxiv.org/abs/2502.11444) _Kun Luo, Zheng Liu, Peitian Zhang, Hongjin Qian, Jun Zhao, Kang Liu._ Arxiv 2025.

143. [**SQLong: Enhanced NL2SQL for Longer Contexts with LLMs.**](https://arxiv.org/abs/2502.16747) _Dai Quoc Nguyen, Cong Duy Vu Hoang, Duy Vu, Gioacchino Tangari, Thanh Tien Vu, Don Dharmasiri, Yuan-Fang Li, Long Duong._ Arxiv 2025.

144. [**LongSafety: Evaluating Long-Context Safety of Large Language Models.**](https://arxiv.org/abs/2502.16971) _Yida Lu, Jiale Cheng, Zhexin Zhang, Shiyao Cui, Cunxiang Wang, Xiaotao Gu, Yuxiao Dong, Jie Tang, Hongning Wang, Minlie Huang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/thu-coai/LongSafety)](https://github.com/thu-coai/LongSafety)

145. [**LR2Bench: Evaluating Long-chain Reflective Reasoning Capabilities of Large Language Models via Constraint Satisfaction Problems.**](https://arxiv.org/abs/2502.17848) _Jianghao Chen, Zhenlin Wei, Zhenjiang Ren, Ziyong Li, Jiajun Zhang._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/spaces/UltraRonin/LR2Bench)

146. [**DocPuzzle: A Process-Aware Benchmark for Evaluating Realistic Long-Context Reasoning Capabilities.**](https://arxiv.org/abs/2502.17807) _Tianyi Zhuang, Chuqiao Kuang, Xiaoguang Li, Yihua Teng, Jihao Wu, Yasheng Wang, Lifeng Shang._ Arxiv 2025.

147. [**Chain-of-Thought Matters: Improving Long-Context Language Models with Reasoning Path Supervision.**](https://arxiv.org/abs/2502.20790) _Dawei Zhu, Xiyu Wei, Guangxiang Zhao, Wenhao Wu, Haosheng Zou, Junfeng Ran, Xun Wang, Lin Sun, Xiangzheng Zhang, Sujian Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lemon-prog123/LongRePS)](https://github.com/lemon-prog123/LongRePS)

148. [**U-NIAH: Unified RAG and LLM Evaluation for Long Context Needle-In-A-Haystack.**](https://arxiv.org/abs/2503.00353) _Yunfan Gao, Yun Xiong, Wenlong Wu, Zijing Huang, Bohan Li, Haofen WangYunfan Gao, Yun Xiong, Wenlong Wu, Zijing Huang, Bohan Li, Haofen Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongji-KGLLM/U-NIAH)](https://github.com/Tongji-KGLLM/U-NIAH)

149. [**L2M: Mutual Information Scaling Law for Long-Context Language Modeling.**](https://arxiv.org/abs/2503.04725) _Zhuo Chen, Oriol Mayné i Comas, Zhuotao Jin, Di Luo, Marin Soljačić._ Arxiv 2025.

150. [**CURIE: Evaluating LLMs On Multitask Scientific Long Context Understanding and Reasoning.**](https://arxiv.org/abs/2503.13517) _Hao Cui, Zahra Shamsi, Gowoon Cheon, Xuejian Ma, Shutong Li, Maria Tikhanovskaya, Peter Norgaard, Nayantara Mudur, Martyna Plomecka, Paul Raccuglia, Yasaman Bahri, Victor V. Albert, Pranesh Srinivasan, Haining Pan, Philippe Faist, Brian Rohr, Michael J. Statt, Dan Morris, Drew Purves, Elise Kleeman, Ruth Alcantara, Matthew Abraham, Muqthar Mohammad, Ean Phing VanLee, Chenfei Jiang, Elizabeth Dorfman, Eun-Ah Kim, Michael P Brenner, Viren Jain, Sameera Ponda, Subhashini Venugopalan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/google/curie)](https://github.com/google/curie)

151. [**Can LLMs reason over extended multilingual contexts? Towards long-context evaluation beyond retrieval and haystacks.**](https://arxiv.org/abs/2504.12845) _Amey Hengle, Prasoon Bajpai, Soham Dan, Tanmoy Chakraborty._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AmeyHengle/multilingual-long-context-reasoning)](https://github.com/AmeyHengle/multilingual-long-context-reasoning)

152. [**Too Long, Didn't Model: Decomposing LLM Long-Context Understanding With Novels.**](https://arxiv.org/abs/2505.14925) _Sil Hamilton, Rebecca M. M. Hicke, Matthew Wilkens, David MimnoSil Hamilton, Rebecca M. M. Hicke, Matthew Wilkens, David Mimno._ Arxiv 2025.

153. [**Longer Context, Deeper Thinking: Uncovering the Role of Long-Context Ability in Reasoning.**](https://arxiv.org/abs/2505.17315) _Wang Yang, Zirui Liu, Hongye Jin, Qingyu Yin, Vipin Chaudhary, Xiaotian Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/uservan/LCTMerge)](https://github.com/uservan/LCTMerge)

154. [**Does quantization affect models' performance on long-context tasks?.**](https://arxiv.org/abs/2505.20276) _Anmol Mekala, Anirudh Atmakuru, Yixiao Song, Marzena Karpinska, Mohit Iyyer._ Arxiv 2025.

155. [**SwingArena: Competitive Programming Arena for Long-context GitHub Issue Solving.**](https://arxiv.org/abs/2505.23932) Wendong Xu, Jing Xiong, Chenyang Zhao, Qiujiang Chen, Haoran Wang, Hui Shen, Zhongwei Wan, Jianbo Dai, Taiqiang Wu, He Xiao, Chaofan Tao, Z. Morley Mao, Ying Sheng, Zhijiang Guo, Hongxia Yang, Bei Yu, Lingpeng Kong, Quanquan Gu, Ngai Wong._ Arxiv 2025.

156. [**THINK-Bench: Evaluating Thinking Efficiency and Chain-of-Thought Quality of Large Reasoning Models.**](https://arxiv.org/abs/2505.22113) _Zhiyuan Li, Yi Chang, Yuan Wu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ZhiyuanLi218/Think-Bench)](https://github.com/ZhiyuanLi218/Think-Bench)

157. [**MiniLongBench: The Low-cost Long Context Understanding Benchmark for Large Language Models.**](https://arxiv.org/abs/2505.19959) _Zhongzhan Huang, Guoming Ling, Shanshan Zhong, Hefeng Wu, Liang Lin._ ACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MilkThink-Lab/MiniLongBench)](https://github.com/MilkThink-Lab/MiniLongBench)

158. [**100-LongBench: Are de facto Long-Context Benchmarks Literally Evaluating Long-Context Ability?.**](https://arxiv.org/abs/2505.19293) _Wang Yang, Hongye Jin, Shaochen Zhong, Song Jiang, Qifan Wang, Vipin Chaudhary, Xiaotian Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/uservan/100-LongBench)](https://github.com/uservan/100-LongBench)

159. [**ExpertLongBench: Benchmarking Language Models on Expert-Level Long-Form Generation Tasks with Structured Checklists.**](https://arxiv.org/abs/2506.01241) _Jie Ruan, Inderjeet Nair, Shuyang Cao, Amy Liu, Sheza Munir, Micah Pollens-Dempsey, Tiffany Chiang, Lucy Kates, Nicholas David, Sihan Chen, Ruxin Yang, Yuqian Yang, Jasmine Gump, Tessa Bialek, Vivek Sankaran, Margo Schlanger, Lu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/launchnlp/ExpertLongBench)](https://github.com/launchnlp/ExpertLongBench)

#### 11.2 MLLM

1. [**MileBench: Benchmarking MLLMs in Long Context.**](https://arxiv.org/abs/2404.18532) _Dingjie Song, Shunian Chen, Guiming Hardy Chen, Fei Yu, Xiang Wan, Benyou Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/MileBench/MileBench)](https://github.com/MileBench/MileBench)

2. [**Many-Shot In-Context Learning in Multimodal Foundation Models.**](https://arxiv.org/abs/2405.09798) _Yixing Jiang, Jeremy Irvin, Ji Hun Wang, Muhammad Ahmed Chaudhry, Jonathan H. Chen, Andrew Y. Ng._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/stanfordmlgroup/ManyICL)](https://github.com/stanfordmlgroup/ManyICL)

3. [**MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding.**](https://arxiv.org/abs/2406.04264) _Junjie Zhou, Yan Shu, Bo Zhao, Boya Wu, Shitao Xiao, Xi Yang, Yongping Xiong, Bo Zhang, Tiejun Huang, Zheng Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding/tree/master/MLVU)

4. [**RepoQA: Evaluating Long Context Code Understanding.**](https://arxiv.org/abs/2406.06025) _Jiawei Liu, Jia Le Tian, Vijay Daita, Yuxiang Wei, Yifeng Ding, Yuhan Katherine Wang, Jun Yang, Lingming Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/evalplus/repoqa)](https://github.com/evalplus/repoqa)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://evalplus.github.io/repoqa.html)

5. [**Short Film Dataset (SFD): A Benchmark for Story-Level Video Understanding.**](https://arxiv.org/abs/2406.10221) _Ridouane Ghermi, Xi Wang, Vicky Kalogeiton, Ivan Laptev._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/shortfilmdataset/ShortFilmDataset)](https://github.com/shortfilmdataset/ShortFilmDataset)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://shortfilmdataset.github.io/)

6. [**Multimodal Needle in a Haystack: Benchmarking Long-Context Capability of Multimodal Large Language Models.**](https://arxiv.org/abs/2406.11230) _Hengyi Wang, Haizhou Shi, Shiwei Tan, Weiyi Qin, Wenyuan Wang, Tunyu Zhang, Akshay Nambi, Tanuja Ganu, Hao Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Wang-ML-Lab/multimodal-needle-in-a-haystack)](https://github.com/Wang-ML-Lab/multimodal-needle-in-a-haystack)

7. [**Losing Visual Needles in Image Haystacks: Vision Language Models are Easily Distracted in Short and Long Contexts.**](https://arxiv.org/abs/2406.16851) _Aditya Sharma, Michael Saxon, William Yang Wang._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://locovqa.github.io/)

8. [**MMLongBench-Doc: Benchmarking Long-context Document Understanding with Visualizations.**](https://arxiv.org/abs/2407.01523) _Yubo Ma, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, Ziyu Liu, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-Gang Jiang, Jiaqi Wang, Yixin Cao, Aixin Sun._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mayubo2333/MMLongBench-Doc)](https://github.com/mayubo2333/MMLongBench-Doc)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://mayubo2333.github.io/MMLongBench-Doc/)

9. [**InternLM-XComposer-2.5: A Versatile Large Vision Language Model Supporting Long-Contextual Input and Output.**](https://arxiv.org/abs/2407.03320) _Pan Zhang, Xiaoyi Dong, Yuhang Zang, Yuhang Cao, Rui Qian, Lin Chen, Qipeng Guo, Haodong Duan, Bin Wang, Linke Ouyang, Songyang Zhang, Wenwei Zhang, Yining Li, Yang Gao, Peng Sun, Xinyue Zhang, Wei Li, Jingwen Li, Wenhai Wang, Hang Yan, Conghui He, Xingcheng Zhang, Kai Chen, Jifeng Dai, Yu Qiao, Dahua Lin, Jiaqi Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/InternLM/InternLM-XComposer)](https://github.com/InternLM/InternLM-XComposer)

10. [**Stark: Social Long-Term Multi-Modal Conversation with Persona Commonsense Knowledge.**](https://arxiv.org/abs/2407.03958) _Young-Jun Lee, Dokyong Lee, Junyoung Youn, Kyeongjin Oh, Byungsoo Ko, Jonghwan Hyeon, Ho-Jin Choi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/passing2961/Stark)](https://github.com/passing2961/Stark)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://stark-dataset.github.io/)

11. [**SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers.**](https://arxiv.org/abs/2407.09413) _Shraman Pramanick, Rama Chellappa, Subhashini Venugopalan._ Arxiv 2024.

12. [**LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding.**](https://arxiv.org/abs/2407.15754) _Haoning Wu, Dongxu Li, Bei Chen, Junnan Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/longvideobench/LongVideoBench)](https://github.com/longvideobench/LongVideoBench)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://longvideobench.github.io/)

13. [**mGTE: Generalized Long-Context Text Representation and Reranking Models for Multilingual Text Retrieval.**](https://arxiv.org/abs/2407.19669) _Xin Zhang, Yanzhao Zhang, Dingkun Long, Wen Xie, Ziqi Dai, Jialong Tang, Huan Lin, Baosong Yang, Pengjun Xie, Fei Huang, Meishan Zhang, Wenjie Li, Min Zhang._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/Alibaba-NLP/gte-multilingual-base)

14. [**MovieSum: An Abstractive Summarization Dataset for Movie Screenplays.**](https://arxiv.org/abs/2408.06281) _Rohit Saxena, Frank Keller._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/saxenarohit/MovieSum)](https://github.com/saxenarohit/MovieSum)

15. [**SEED-Story: Multimodal Long Story Generation with Large Language Model.**](https://arxiv.org/abs/2407.08683) _Shuai Yang, Yuying Ge, Yang Li, Yukang Chen, Yixiao Ge, Ying Shan, Yingcong Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TencentARC/SEED-Story)](https://github.com/TencentARC/SEED-Story)

16. [**M-Longdoc: A Benchmark For Multimodal Super-Long Document Understanding And A Retrieval-Aware Tuning Framework.**](https://arxiv.org/abs/2411.06176) _Yew Ken Chia, Liying Cheng, Hou Pong Chan, Chaoqun Liu, Maojia Song, Sharifah Mahani Aljunied, Soujanya Poria, Lidong Bing._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://multimodal-documents.github.io/)

17. [**LongVALE: Vision-Audio-Language-Event Benchmark Towards Time-Aware Omni-Modal Perception of Long Videos.**](https://arxiv.org/abs/2411.19772) _Tiantian Geng, Jinrui Zhang, Qingni Wang, Teng Wang, Jinming Duan, Feng Zheng._ Arxiv 2024.

18. [**LMAct: A Benchmark for In-Context Imitation Learning with Long Multimodal Demonstrations.**](https://arxiv.org/abs/2412.01441) _Anian Ruoss, Fabio Pardo, Harris Chan, Bonnie Li, Volodymyr Mnih, Tim Genewein._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/lm_act)](https://github.com/google-deepmind/lm_act)

19. [**Neptune: The Long Orbit to Benchmarking Long Video Understanding.**](https://arxiv.org/abs/2412.09582) _Arsha Nagrani, Mingda Zhang, Ramin Mehran, Rachel Hornung, Nitesh Bharadwaj Gundavarapu, Nilpa Jha, Austin Myers, Xingyi Zhou, Boqing Gong, Cordelia Schmid, Mikhail Sirotenko, Yukun Zhu, Tobias Weyand._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/neptune)](https://github.com/google-deepmind/neptune)

20. [**VisDoM: Multi-Document QA with Visually Rich Elements Using Multimodal Retrieval-Augmented Generation.**](https://arxiv.org/abs/2412.10704) _Manan Suri, Puneet Mathur, Franck Dernoncourt, Kanika Goswami, Ryan A. Rossi, Dinesh Manocha._ Arxiv 2024.

21. [**Is Your World Simulator a Good Story Presenter? A Consecutive Events-Based Benchmark for Future Long Video Generation.**](https://arxiv.org/abs/2412.16211) _Yiping Wang, Xuehai He, Kuan Wang, Luyao Ma, Jianwei Yang, Shuohang Wang, Simon Shaolei Du, Yelong Shen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ypwang61/StoryEval)](https://github.com/ypwang61/StoryEval)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ypwang61.github.io/project/StoryEval/)

22. [**LongDocURL: a Comprehensive Multimodal Long Document Benchmark Integrating Understanding, Reasoning, and Locating.**](https://arxiv.org/abs/2412.18424) _Chao Deng, Jiale Yuan, Pi Bu, Peijie Wang, Zhong-Zhi Li, Jian Xu, Xiao-Hui Li, Yuan Gao, Jun Song, Bo Zheng, Cheng-Lin Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/neptune)](https://github.com/google-deepmind/neptune)

23. [**HLV-1K: A Large-scale Hour-Long Video Benchmark for Time-Specific Long Video Understanding.**](https://arxiv.org/abs/2501.01645) _Heqing Zou, Tianze Luo, Guiyang Xie, Victor (Xiao Jie)Zhang, Fengmao Lv, Guangcong Wang, Junyang Chen, Zhuochen Wang, Hansheng Zhang, Huaijian Zhang._ Arxiv 2025.

24. [**MMDocIR: Benchmarking Multi-Modal Retrieval for Long Documents.**](https://arxiv.org/abs/2501.08828) _Kuicai Dong, Yujing Chang, Xin Deik Goh, Dexun Li, Ruiming Tang, Yong Liu._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/MMDocIR)

25. [**EnigmaEval: A Benchmark of Long Multimodal Reasoning Challenges.**](https://arxiv.org/abs/2502.08859) _Clinton J. Wang, Dean Lee, Cristina Menghini, Johannes Mols, Jack Doughty, Adam Khoja, Jayson Lynch, Sean Hendryx, Summer Yue, Dan Hendrycks._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://scale.com/leaderboard/enigma_eval)

26. [**MomentSeeker: A Comprehensive Benchmark and A Strong Baseline For Moment Retrieval Within Long Videos.**](https://arxiv.org/abs/2502.12558) _Huaying Yuan, Jian Ni, Yueze Wang, Junjie Zhou, Zhengyang Liang, Zheng Liu, Zhao Cao, Zhicheng Dou, Ji-Rong Wen._ Arxiv 2025.

27. [**Compression Scaling Laws:Unifying Sparsity and Quantization.**](https://arxiv.org/abs/2502.16440) _Elias Frantar, Utku Evci, Wonpyo Park, Neil Houlsby, Dan Alistarh._ Arxiv 2025.

28. [**One ruler to measure them all: Benchmarking multilingual long-context language models.**](https://arxiv.org/abs/2503.01996) _Yekyung Kim, Jenna Russell, Marzena Karpinska, Mohit Iyyer._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mungg/OneRuler)](https://github.com/mungg/OneRuler)

29. [**LVLM-Compress-Bench: Benchmarking the Broader Impact of Large Vision-Language Model Compression.**](https://arxiv.org/abs/2503.04982) _Souvik Kundu, Anahita Bhiwandiwalla, Sungduk Yu, Phillip Howard, Tiep Le, Sharath Nittur Sridhar, David Cobbley, Hao Kang, Vasudev Lal._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/opengear-project/LVLM-compress-bench)](https://github.com/opengear-project/LVLM-compress-bench)

30. [**NeedleInATable: Exploring Long-Context Capability of Large Language Models towards Long-Structured Tables.**](https://arxiv.org/abs/2504.06560) _Lanrui Wang, Mingyu Zheng, Hongyin Tang, Zheng Lin, Yanan Cao, Jingang Wang, Xunliang Cai, Weiping Wang._ Arxiv 2025.

31. [**LiveLongBench: Tackling Long-Context Understanding for Spoken Texts from Live Streams.**](https://arxiv.org/abs/2504.17366) _Yongxuan Wu, Runyu Chen, Peiyu Liu, Hongjin Qian._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Yarayx/livelongbench)](https://github.com/Yarayx/livelongbench)

32. [**MMLongBench: Benchmarking Long-Context Vision-Language Models Effectively and Thoroughly.**](https://arxiv.org/abs/2505.10610) _Zhaowei Wang, Wenhao Yu, Xiyu Ren, Jipeng Zhang, Yu Zhao, Rohit Saxena, Liang Cheng, Ginny Wong, Simon See, Pasquale Minervini, Yangqiu Song, Mark Steedman._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/EdinburghNLP/MMLongBench)](https://github.com/EdinburghNLP/MMLongBench)

33. [**ScaleLong: A Multi-Timescale Benchmark for Long Video Understanding.**](https://arxiv.org/abs/2505.23922) _David Ma, Huaqing Yuan, Xingjian Wang, Qianbo Zang, Tianci Liu, Xinyang He, Yanbin Wei, Jiawei Guo, Ni Jiahui, Zhenzhu Yang, Meng Cao, Shanghaoran Quan, Yizhi Li, Wangchunshu Zhou, Jiaheng Liu, Wenhao Huang, Ge Zhang, Shiwen Ni, Xiaojie Jin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/multimodal-art-projection/ScaleLong)](https://github.com/multimodal-art-projection/ScaleLong)

### 12. Long Text Generation

1. [**Integrating Planning into Single-Turn Long-Form Text Generation.**](https://arxiv.org/abs/2410.06203) _Yi Liang, You Wu, Honglei Zhuang, Li Chen, Jiaming Shen, Yiling Jia, Zhen Qin, Sumit Sanghai, Xuanhui Wang, Carl Yang, Michael Bendersky._ Arxiv 2024.

2. [**Minimum Tuning to Unlock Long Output from LLMs with High Quality Data as the Key.**](https://arxiv.org/abs/2410.10210) _Yingda Chen, Xingjun Wang, Jintao Huang, Yunlin Mao, Daoze Zhang, Yuze Zhao._ Arxiv 2024.

3. [**LongGenBench: Long-context Generation Benchmark.**](https://arxiv.org/abs/2410.04199) _Xiang Liu, Peijie Dong, Xuming Hu, Xiaowen Chu._ EMNLP 2024.

4. [**LoGU: Long-form Generation with Uncertainty Expressions.**](https://arxiv.org/abs/2410.14309) _Ruihan Yang, Caiqi Zhang, Zhisong Zhang, Xinting Huang, Sen Yang, Nigel Collier, Dong Yu, Deqing Yang._ Arxiv 2024.

5. [**Large Language Models Still Exhibit Bias in Long Text.**](https://arxiv.org/abs/2410.17519) _Wonje Jeung, Dongjae Jeon, Ashkan Yousefpour, Jonghyun Choi._ Arxiv 2024.

6. [**Suri: Multi-constraint Instruction Following for Long-form Text Generation.**](https://arxiv.org/abs/2406.19371) _Chau Minh Pham, Simeng Sun, Mohit Iyyer._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chtmp223/suri)](https://github.com/chtmp223/suri)

7. [**LongWriter: Unleashing 10,000+ Word Generation from Long Context LLMs.**](https://arxiv.org/abs/2408.07055) _Yushi Bai, Jiajie Zhang, Xin Lv, Linzhi Zheng, Siqi Zhu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongWriter)](https://github.com/THUDM/LongWriter)

8. [**Language Models can Self-Lengthen to Generate Long Texts.**](https://arxiv.org/abs/2410.23933) _Shanghaoran Quan, Tianyi Tang, Bowen Yu, An Yang, Dayiheng Liu, Bofei Gao, Jianhong Tu, Yichang Zhang, Jingren Zhou, Junyang Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/QwenLM/Self-Lengthen)](https://github.com/QwenLM/Self-Lengthen)

9. [**Generating Long-form Story Using Dynamic Hierarchical Outlining with Memory-Enhancement.**](https://arxiv.org/abs/2412.13575) _Qianyue Wang, Jinwu Hu, Zhengping Li, Yufeng Wang, daiyuan li, Yu Hu, Mingkui Tan._ Arxiv 2024.

10. [**Beyond Factual Accuracy: Evaluating Coverage of Diverse Factual Information in Long-form Text Generation.**](https://arxiv.org/abs/2501.03545) _Chris Samarinas, Alexander Krubner, Alireza Salemi, Youngwoo Kim, Hamed Zamani._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/algoprog/ICAT)](https://github.com/algoprog/ICAT)

11. [**The FACTS Grounding Leaderboard: Benchmarking LLMs' Ability to Ground Responses to Long-Form Input.**](https://arxiv.org/abs/2501.03200) _Alon Jacovi, Andrew Wang, Chris Alberti, Connie Tao, Jon Lipovetz, Kate Olszewska, Lukas Haas, Michelle Liu, Nate Keating, Adam Bloniarz, Carl Saroufim, Corey Fry, Dror Marcus, Doron Kukliansky, Gaurav Singh Tomar, James Swirhun, Jinwei Xing, Lily Wang, Madhu Gurumurthy, Michael Aaron, Moran Ambar, Rachana Fellinger, Rui Wang, Zizhao Zhang, Sasha Goldshtein, Dipanjan Das._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.kaggle.com/facts-leaderboard)

12. [**LongProc: Benchmarking Long-Context Language Models on Long Procedural Generation.**](https://arxiv.org/abs/2501.05414) _Xi Ye, Fangcong Yin, Yinghui He, Joie Zhang, Howard Yen, Tianyu Gao, Greg Durrett, Danqi Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-pli/LongProc)](https://github.com/princeton-pli/LongProc)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://princeton-pli.github.io/LongProc/)

13. [**ExPerT: Effective and Explainable Evaluation of Personalized Long-Form Text Generation.**](https://arxiv.org/abs/2501.14956) _Alireza Salemi, Julian Killingback, Hamed Zamani._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/alirezasalemi7/ExPerT)](https://github.com/alirezasalemi7/ExPerT)

14. [**LongDPO: Unlock Better Long-form Generation Abilities for LLMs via Critique-augmented Stepwise Information.**](https://arxiv.org/abs/2502.02095) _Bowen Ping, Jiali Zeng, Fandong Meng, Shuo Wang, Jie Zhou, Shanghang Zhang._ Arxiv 2025.

15. [**Context-Preserving Gradient Modulation for Large Language Models: A Novel Approach to Semantic Consistency in Long-Form Text Generation.**](https://arxiv.org/abs/2502.03643) _Nirola Kobanov, Edmund Weatherstone, Zachary Vanderpoel, Orlando Wetherby._ Arxiv 2025.

16. [**A Cognitive Writing Perspective for Constrained Long-Form Text Generation.**](https://arxiv.org/abs/2502.12568) _Kaiyang Wan, Honglin Mu, Rui Hao, Haoran Luo, Tianle Gu, Xiuying Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/KaiyangWan/CogWriter)](https://github.com/KaiyangWan/CogWriter)

17. [**CLIPPER: Compression enables long-context synthetic data generation.**](https://arxiv.org/abs/2502.14854) _Chau Minh Pham, Yapei Chang, Mohit Iyyer._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/chtmp223/CLIPPER)](https://github.com/chtmp223/CLIPPER)

18. [**LongWriter-V: Enabling Ultra-Long and High-Fidelity Generation in Vision-Language Models.**](https://arxiv.org/abs/2502.14834) _Shangqing Tu, Yucheng Wang, Daniel Zhang-Li, Yushi Bai, Jifan Yu, Yuhao Wu, Lei Hou, Huiqin Liu, Zhiyuan Liu, Bin Xu, Juanzi Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/THU-KEG/LongWriter-V)](https://github.com/THU-KEG/LongWriter-V)

19. [**LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm.**](https://arxiv.org/abs/2502.19103) _Siwei Wu, Yizhi Li, Xingwei Qu, Rishi Ravikumar, Yucheng Li, Tyler Loakman Shanghaoran Quan Xiaoyong Wei, Riza Batista-Navarro, Chenghua Lin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Wusiwei0410/LongEval)](https://github.com/Wusiwei0410/LongEval)

20. [**From Hours to Minutes: Lossless Acceleration of Ultra Long Sequence Generation up to 100K Tokens.**](https://arxiv.org/abs/2502.18890) _Tong Wu, Junzhe Shen, Zixia Jia, Yuxuan Wang, Zilong Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/TokenSwift)](https://github.com/bigai-nlco/TokenSwift)

21. [**RAPID: Efficient Retrieval-Augmented Long Text Generation with Writing Planning and Information Discovery.**](https://arxiv.org/abs/2503.00751) _Hongchao Gu, Dexun Li, Kuicai Dong, Hao Zhang, Hang Lv, Hao Wang, Defu Lian, Yong Liu, Enhong Chen._ Arxiv 2025.

22. [**DeFine: A Decomposed and Fine-Grained Annotated Dataset for Long-form Article Generation.**](https://arxiv.org/abs/2503.07170) _Ming Wang, Fang Wang, Minghao Hu, Li He, Haiyang Wang, Jun Zhang, Tianwei Yan, Li Li, Zhunchen Luo, Wei Luo, Xiaoying Bai, Guotong Geng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DeFine-LFAG/DeFine_Dataset)](https://github.com/DeFine-LFAG/DeFine_Dataset)

23. [**Lost-in-the-Middle in Long-Text Generation: Synthetic Dataset, Evaluation Framework, and Mitigation.**](https://arxiv.org/abs/2503.06868) _Junhao Zhang, Richong Zhang, Fanshuang Kong, Ziyang Miao, Yanhan Ye, Yaowei Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OnlyAR/RAL-Writer)](https://github.com/OnlyAR/RAL-Writer)

24. [**Beyond Outlining: Heterogeneous Recursive Planning for Adaptive Long-form Writing with Language Models.**](https://arxiv.org/abs/2503.08275) _Ruibin Xiong, Yimeng Chen, Dmitrii Khizbullin, Jürgen Schmidhuber._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/principia-ai/heterogeneous-recursive-planning)](https://github.com/principia-ai/heterogeneous-recursive-planning)

25. [**Learning to Reason for Long-Form Story Generation.**](https://arxiv.org/abs/2503.22828) _Alexander Gurung, Mirella Lapata._ Arxiv 2025.

26. [**ThinkPrune: Pruning Long Chain-of-Thought of LLMs via Reinforcement Learning.**](https://arxiv.org/abs/2504.01296) _Bairu Hou, Yang Zhang, Jiabao Ji, Yujian Liu, Kaizhi Qian, Jacob Andreas, Shiyu Chang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UCSB-NLP-Chang/ThinkPrune)](https://github.com/UCSB-NLP-Chang/ThinkPrune)

27. [**Think When You Need: Self-Adaptive Chain-of-Thought Learning.**](https://arxiv.org/abs/2504.03234) _Junjie Yang, Ke Lin, Xing Yu._ Arxiv 2025.

28. [**LLM×MapReduce-V2: Entropy-Driven Convolutional Test-Time Scaling for Generating Long-Form Articles from Extremely Long Resources.**](https://arxiv.org/abs/2504.05732) _Haoyu Wang, Yujia Fu, Zhu Zhang, Shuo Wang, Zirui Ren, Xiaorong Wang, Zhili Li, Chaoqun He, Bo An, Zhiyuan Liu, Maosong Sun._ Arxiv 2025.

### 13. Long CoT

#### 13.1 LLM

1. [**When More is Less: Understanding Chain-of-Thought Length in LLMs.**](https://arxiv.org/abs/2502.07266) _Yuyang Wu, Yifei Wang, Tianqi Du, Stefanie Jegelka, Yisen Wang._ Arxiv 2025.

2. [**LLMs Can Easily Learn to Reason from Demonstrations Structure, not content, is what matters!.**](https://arxiv.org/abs/2502.07374) _Dacheng Li, Shiyi Cao, Tyler Griggs, Shu Liu, Xiangxi Mo, Shishir G. Patil, Matei Zaharia, Joseph E. Gonzalez, Ion Stoica._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NovaSky-AI/SkyThought)](https://github.com/NovaSky-AI/SkyThought)

3. [**Monte Carlo Tree Diffusion for System 2 Planning.**](https://arxiv.org/abs/2502.07202) _Jaesik Yoon, Hyeonseo Cho, Doojin Baek, Yoshua Bengio, Sungjin Ahn._ Arxiv 2025.

4. [**Enhancing Auto-regressive Chain-of-Thought through Loop-Aligned Reasoning.**](https://arxiv.org/abs/2502.08482) _Qifan Yu, Zhenyu He, Sijie Li, Xun Zhou, Jun Zhang, Jingjing Xu, Di He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/qifanyu/RELAY)](https://github.com/qifanyu/RELAY)

5. [**CoT-Valve: Length-Compressible Chain-of-Thought Tuning.**](https://arxiv.org/abs/2502.09601) _Xinyin Ma, Guangnian Wan, Runpeng Yu, Gongfan Fang, Xinchao Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/CoT-Valve)](https://github.com/horseee/CoT-Valve)

6. [**Efficient Long-Decoding Inference with Reasoning-Aware Attention Sparsity.**](https://arxiv.org/abs/2502.11147) _Junhao Hu, Wenrui Huang, Weidong Wang, Zhenwen Li, Tiancheng Hu, Zhixia Liu, Xusheng Chen, Tao Xie, Yizhou Shan._ Arxiv 2025.

7. [**DRT: Deep Reasoning Translation via Long Chain-of-Thought.**](https://arxiv.org/abs/2412.17498) _Jiaan Wang, Fandong Meng, Yunlong Liang, Jie Zhou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/krystalan/DRT-o1)](https://github.com/krystalan/DRT-o1)

8. [**Do NOT Think That Much for 2+3=? On the Overthinking of o1-Like LLMs.**](https://arxiv.org/abs/2412.21187) _Xingyu Chen, Jiahao Xu, Tian Liang, Zhiwei He, Jianhui Pang, Dian Yu, Linfeng Song, Qiuzhi Liu, Mengfei Zhou, Zhuosheng Zhang, Rui Wang, Zhaopeng Tu, Haitao Mi, Dong Yu._ Arxiv 2024.

9. [**O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple Distillation, Big Progress or Bitter Lesson?.**](https://arxiv.org/abs/2411.16489) _Zhen Huang, Haoyang Zou, Xuefeng Li, Yixiu Liu, Yuxiang Zheng, Ethan Chern, Shijie Xia, Yiwei Qin, Weizhe Yuan, Pengfei Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey)](https://github.com/GAIR-NLP/O1-Journey)

10. [**OpenRFT: Adapting Reasoning Foundation Model for Domain-specific Tasks with Reinforcement Fine-Tuning.**](https://arxiv.org/abs/2412.16849) _Yuxiang Zhang, Yuqi Yang, Jiangming Shu, Yuhang Wang, Jinlin Xiao, Jitao Sang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ADaM-BJTU/OpenRFT)](https://github.com/ADaM-BJTU/OpenRFT)

11. [**Dynamic Chain-of-Thought: Towards Adaptive Deep Reasoning.**](https://arxiv.org/abs/2502.10428) _Libo Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/brucewang123456789/GeniusTrail)](https://github.com/brucewang123456789/GeniusTrail/tree/main/Dynamic%20CoT)

12. [**SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities.**](https://arxiv.org/abs/2502.12025) _Fengqing Jiang, Zhangchen Xu, Yuetai Li, Luyao Niu, Zhen Xiang, Bo Li, Bill Yuchen Lin, Radha Poovendran._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://safe-chain.github.io/)

13. [**Leveraging Constrained Monte Carlo Tree Search to Generate Reliable Long Chain-of-Thought for Mathematical Reasoning.**](https://arxiv.org/abs/2502.11169) _Qingwen Lin, Boyan Xu, Zijian Li, Zhifeng Hao, Keli Zhang, Ruichu Cai._ Arxiv 2025.

14. [**Revisiting the Test-Time Scaling of o1-like Models: Do they Truly Possess Test-Time Scaling Capabilities?.**](https://arxiv.org/abs/2502.12215) _Zhiyuan Zeng, Qinyuan Cheng, Zhangyue Yin, Yunhua Zhou, Xipeng Qiu._ Arxiv 2025.

15. [**TokenSkip: Controllable Chain-of-Thought Compression in LLMs.**](https://arxiv.org/abs/2502.12067) _Heming Xia, Yongqi Li, Chak Tou Leong, Wenjie Wang, Wenjie Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hemingkx/TokenSkip)](https://github.com/hemingkx/TokenSkip)

16. [**LightThinker: Thinking Step-by-Step Compression.**](https://arxiv.org/abs/2502.15589) _Jintian Zhang, Yuqi Zhu, Mengshu Sun, Yujie Luo, Shuofei Qiao, Lun Du, Da Zheng, Huajun Chen, Ningyu Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zjunlp/LightThinker)](https://github.com/zjunlp/LightThinker)

17. [**Towards Thinking-Optimal Scaling of Test-Time Compute for LLM Reasoning.**](https://arxiv.org/abs/2502.18080) _Wenkai Yang, Shuming Ma, Yankai Lin, Furu Wei._ Arxiv 2025.

18. [**Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?.**](https://arxiv.org/abs/2502.19361) _Yancheng He, Shilong Li, Jiaheng Liu, Weixun Wang, Xingyuan Bu, Ge Zhang, Zhongyuan Peng, Zhaoxiang Zhang, Zhicheng Zheng, Wenbo Su, Bo Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenStellarTeam/DeltaBench)](https://github.com/OpenStellarTeam/DeltaBench)

19. [**Towards Widening The Distillation Bottleneck for Reasoning Models.**](https://arxiv.org/abs/2503.01461) _Huifeng Yin, Yu Zhao, Minghao Wu, Xuanfan Ni, Bo Zeng, Hao Wang, Tianqi Shi, Liangying Shao, Chenyang Lyu, Longyue Wang, Weihua Luo, Kaifu Zhang._ Arxiv 2025.

20. [**What's Behind PPO's Collapse in Long-CoT? Value Optimization Holds the Secret.**](https://arxiv.org/abs/2503.01491) _Yufeng Yuan, Yu Yue, Ruofei Zhu, Tiantian Fan, Lin Yan._ Arxiv 2025.

21. [**MA-LoT: Multi-Agent Lean-based Long Chain-of-Thought Reasoning enhances Formal Theorem Proving.**](https://arxiv.org/abs/2503.03205) _Ruida Wang, Rui Pan, Yuxin Li, Jipeng Zhang, Yizhen Jia, Shizhe Diao, Renjie Pi, Junjie Hu, Tong Zhang._ Arxiv 2025.

22. [**START: Self-taught Reasoner with Tools.**](https://arxiv.org/abs/2503.04625) _Chengpeng Li, Mingfeng Xue, Zhenru Zhang, Jiaxi Yang, Beichen Zhang, Xiang Wang, Bowen Yu, Binyuan Hui, Junyang Lin, Dayiheng Liu._ Arxiv 2025.

23. [**L1: Controlling How Long A Reasoning Model Thinks With Reinforcement Learning.**](https://arxiv.org/abs/2503.04697) _Pranjal Aggarwal, Sean Welleck._ Arxiv 2025.

24. [**InftyThink: Breaking the Length Limits of Long-Context Reasoning in Large Language Models.**](https://arxiv.org/abs/2503.06692) _Yuchen Yan, Yongliang Shen, Yang Liu, Jin Jiang, Mengdi Zhang, Jian Shao, Yueting Zhuang._ Arxiv 2025.

25. [**Attention Reveals More Than Tokens: Training-Free Long-Context Reasoning with Attention-guided Retrieval.**](https://arxiv.org/abs/2503.09819) _Yuwei Zhang, Jayanth Srinivasa, Gaowen Liu, Jingbo Shang._ Arxiv 2025.

26. [**"Well, Keep Thinking": Enhancing LLM Reasoning with Adaptive Injection Decoding.**](https://arxiv.org/abs/2503.10167) _Hyunbin Jin, Je Won Yeom, Seunghyun Bae, Taesup Kim._ Arxiv 2025.

27. [**Light-R1: Curriculum SFT, DPO and RL for Long COT from Scratch and Beyond.**](https://arxiv.org/abs/2503.10460) _Liang Wen, Yunke Cai, Fenrui Xiao, Xin He, Qi An, Zhenyu Duan, Yimin Du, Junchen Liu, Lifu Tang, Xiaowei Lv, Haosheng Zou, Yongchao Deng, Shousheng Jia, Xiangzheng Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Qihoo360/Light-R1)](https://github.com/Qihoo360/Light-R1)

28. [**Unlocking General Long Chain-of-Thought Reasoning Capabilities of Large Language Models via Representation Engineering.**](https://arxiv.org/abs/2503.11314) _Xinyu Tang, Xiaolei Wang, Zhihao Lv, Yingqian Min, Wayne Xin Zhao, Binbin Hu, Ziqi Liu, Zhiqiang Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/txy77/GLoRE)](https://github.com/txy77/GLoRE)

29. [**Large Reasoning Models in Agent Scenarios: Exploring the Necessity of Reasoning Capabilities.**](https://arxiv.org/abs/2503.11074) _Xueyang Zhou, Guiyao Tie, Guowen Zhang, Weidong Wang, Zhigang Zuo, Di Wu, Duanfeng Chu, Pan Zhou, Lichao Sun, Neil Zhenqiang Gong._ Arxiv 2025.

30. [**PENCIL: Long Thoughts with Short Memory.**](https://arxiv.org/abs/2503.14337) _Chenxiao Yang, Nathan Srebro, David McAllester, Zhiyuan Li._ Arxiv 2025.

31. [**Long Is More Important Than Difficult for Training Reasoning Models.**](https://arxiv.org/abs/2503.17407) _Si Shen, Fei Huang, Zhixiao Zhao, Chang Liu, Tiansheng Zheng, Danhao Zhu._ Arxiv 2025.

32. [**SimpleRL-Zoo: Investigating and Taming Zero Reinforcement Learning for Open Base Models in the Wild.**](https://arxiv.org/abs/2503.18892) _Weihao Zeng, Yuzhen Huang, Qian Liu, Wei Liu, Keqing He, Zejun Ma, Junxian He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hkust-nlp/simpleRL-reason)](https://github.com/hkust-nlp/simpleRL-reason)

33. [**TwT: Thinking without Tokens by Habitual Reasoning Distillation with Multi-Teachers' Guidance.**](https://arxiv.org/abs/2503.24198) _Jingxian Xu, Mengyu Zhou, Weichang Liu, Hanbing Liu, Shi Han, Dongmei Zhang._ Arxiv 2025.

34. [**SKIntern: Internalizing Symbolic Knowledge for Distilling Better CoT Capabilities into Small Language Models.**](https://aclanthology.org/2025.coling-main.215/) _Huanxuan Liao, Shizhu He, Yupu Hao, Xiang Li, Yuanzhe Zhang, Jun Zhao, Kang Liu._ COLING 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/SKIntern)](https://github.com/Xnhyacinth/SKIntern)

35. [**ReTool: Reinforcement Learning for Strategic Tool Use in LLMs.**](https://arxiv.org/abs/2504.11536) _Jiazhan Feng, Shijue Huang, Xingwei Qu, Ge Zhang, Yujia Qin, Baoquan Zhong, Chengquan Jiang, Jinxin Chi, Wanjun Zhong._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ReTool-RL/ReTool)](https://github.com/ReTool-RL/ReTool)

36. [**Thought Manipulation: External Thought Can Be Efficient for Large Reasoning Models.**](https://arxiv.org/abs/2504.13626) _Yule Liu, Jingyi Zheng, Zhen Sun, Zifan Peng, Wenhan Dong, Zeyang Sha, Shiwen Cui, Weiqiang Wang, Xinlei He._ Arxiv 2025.

37. [**THOUGHTTERMINATOR: Benchmarking, Calibrating, and Mitigating Overthinking in Reasoning Models.**](https://arxiv.org/abs/2504.13367) _Xiao Pu, Michael Saxon, Wenyue Hua, William Yang Wang._ Arxiv 2025.

38. [**Dynamic Early Exit in Reasoning Models.**](https://arxiv.org/abs/2504.13367) _Chenxu Yang, Qingyi Si, Yongjie Duan, Zheliang Zhu, Chenyu Zhu, Zheng Lin, Li Cao, Weiping Wang._ Arxiv 2025.

39. [**Process Reward Models That Think.**](https://arxiv.org/abs/2504.16828) _Muhammad Khalifa, Rishabh Agarwal, Lajanugen Logeswaran, Jaekyeom Kim, Hao Peng, Moontae Lee, Honglak Lee, Lu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mukhal/thinkprm)](https://github.com/mukhal/thinkprm)

40. [**AdaR1: From Long-CoT to Hybrid-CoT via Bi-Level Adaptive Reasoning Optimization.**](https://arxiv.org/abs/2504.21659) _Haotian Luo, Haiying He, Yibo Wang, Jinluan Yang, Rui Liu, Naiqiang Tan, Xiaochun Cao, Dacheng Tao, Li Shen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/StarDewXXX/AdaR1)](https://github.com/StarDewXXX/AdaR1)

41. [**Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs.**](https://arxiv.org/abs/2505.00127) _Jinyan Su, Jennifer Healey, Preslav Nakov, Claire Cardie._ Arxiv 2025.

42. [**Llama-Nemotron: Efficient Reasoning Models.**](https://arxiv.org/abs/2505.00949) _Jinyan Su, Jennifer Healey, Preslav Nakov, Claire Cardie._ Arxiv 2025.

43. [**RM-R1: Reward Modeling as Reasoning.**](https://arxiv.org/abs/2505.02387) _Xiusi Chen, Gaotang Li, Ziqi Wang, Bowen Jin, Cheng Qian, Yu Wang, Hongru Wang, Yu Zhang, Denghui Zhang, Tong Zhang, Hanghang Tong, Heng Ji._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/RM-R1-UIUC/RM-R1)](https://github.com/RM-R1-UIUC/RM-R1)

44. [**Think on your Feet: Adaptive Thinking via Reinforcement Learning for Social Agents.**](https://arxiv.org/abs/2505.02156) _Minzheng Wang, Yongbin Li, Haobo Wang, Xinghua Zhang, Nan Xu, Bingli Wu, Fei Huang, Haiyang Yu, Wenji Mao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MozerWang/AMPO)](https://github.com/MozerWang/AMPO)

45. [**DRP: Distilled Reasoning Pruning with Skill-aware Step Decomposition for Efficient Large Reasoning Models.**](https://arxiv.org/abs/2505.13975) _Yuxuan Jiang, Dawei Li, Frank Ferraro._ Arxiv 2025.

46. [**Reinforcement Learning vs. Distillation: Understanding Accuracy and Capability in LLM Reasoning.**](https://arxiv.org/abs/2505.14216) _Minwu Kim, Anubhav Shrestha, Safal Shrestha, Aadim Nepal, Keith Ross._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/minwukim/RLvsDistillation)](https://github.com/minwukim/RLvsDistillation)

47. [**ThinkSwitcher: When to Think Hard, When to Think Fast.**](https://arxiv.org/abs/2505.14183) _Guosheng Liang, Longguang Zhong, Ziyi Yang, Xiaojun Quan._ Arxiv 2025.

48. [**Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning.**](https://arxiv.org/abs/2505.15154) _Jinghui Lu, Haiyang Yu, Siliang Xu, Shiwei Ran, Guozhi Tang, Siqi Wang, Bin Shan, Teng Fu, Hao Feng, Jingqun Tang, Han Wang, Can Huang._ Arxiv 2025.

49. [**Soft Thinking: Unlocking the Reasoning Potential of LLMs in Continuous Concept Space.**](https://arxiv.org/abs/2505.15778) _Zhen Zhang, Xuehai He, Weixiang Yan, Ao Shen, Chenyang Zhao, Shuohang Wang, Yelong Shen, Xin Eric Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/eric-ai-lab/Soft-Thinking)](https://github.com/eric-ai-lab/Soft-Thinking)

50. [**ThinkLess: A Training-Free Inference-Efficient Method for Reducing Reasoning Redundancy.**](https://arxiv.org/abs/2505.15684) _Gengyang Li, Yifeng Gao, Yuming Li, Yunfang Wu._ Arxiv 2025.

51. [**Learn to Reason Efficiently with Adaptive Length-based Reward Shaping.**](https://arxiv.org/abs/2505.15612) _Wei Liu, Ruochen Zhou, Yiyun Deng, Yuzhen Huang, Junteng Liu, Yuntian Deng, Yizhe Zhang, Junxian He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hkust-nlp/Laser)](https://github.com/hkust-nlp/Laser)

52. [**When to Continue Thinking: Adaptive Thinking Mode Switching for Efficient Reasoning.**](https://arxiv.org/abs/2505.15400) _Xiaoyun Zhang, Jingqing Ruan, Xing Ma, Yawen Zhu, Haodong Zhao, Hao Li, Jiansong Chen, Ke Zeng, Xunliang Cai._ Arxiv 2025.

53. [**QwenLong-L1: Towards Long-Context Large Reasoning Models with Reinforcement Learning.**](https://arxiv.org/abs/2505.17667) _Fanqi Wan, Weizhou Shen, Shengyi Liao, Yingcheng Shi, Chenliang Li, Ziyi Yang, Ji Zhang, Fei Huang, Jingren Zhou, Ming Yan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongyi-Zhiwen/QwenLong-L1)](https://github.com/Tongyi-Zhiwen/QwenLong-L1)

54. [**Amplify Adjacent Token Differences: Enhancing Long Chain-of-Thought Reasoning with Shift-FFN.**](https://arxiv.org/abs/2505.17153) _Yao Xu, Mingyu Xu, Fangyu Lei, Wangtao Sun, Xiangrong Zeng, Bingning Wang, Guang Liu, Shizhu He, Jun Zhao, Kang Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongyi-Zhiwen/Shift-FFN)](https://anonymous.4open.science/r/Shift-FFN)

55. [**Don't Overthink it. Preferring Shorter Thinking Chains for Improved LLM Reasoning.**](https://arxiv.org/abs/2505.17813) _Michael Hassid, Gabriel Synnaeve, Yossi Adi, Roy Schwartz._ Arxiv 2025.

56. [**ARM: Adaptive Reasoning Model.**](https://arxiv.org/abs/2505.20258) _Siye Wu, Jian Xie, Yikai Zhang, Aili Chen, Kai Zhang, Yu Su, Yanghua Xiao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/TEAM-ARM/ARM)](https://github.com/TEAM-ARM/ARM)

57. [**Think or Not? Exploring Thinking Efficiency in Large Reasoning Models via an Information-Theoretic Lens.**](https://arxiv.org/abs/2505.18237) _Xixian Yong, Xiao Zhou, Yingying Zhang, Jinlin Li, Yefeng Zheng, Xian Wu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/chicosirius/think-or-not)](https://github.com/chicosirius/think-or-not)

58. [**AlphaOne: Reasoning Models Thinking Slow and Fast at Test Time.**](https://arxiv.org/abs/2505.24863) _Junyu Zhang, Runpei Dong, Han Wang, Xuying Ning, Haoran Geng, Peihao Li, Xialin He, Yutong Bai, Jitendra Malik, Saurabh Gupta, Huan Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ASTRAL-Group/AlphaOne)](https://github.com/ASTRAL-Group/AlphaOne)

59. [**A*-Thought: Efficient Reasoning via Bidirectional Compression for Low-Resource Settings.**](https://arxiv.org/abs/2505.24550) _Xiaoang Xu, Shuo Wang, Xu Han, Zhenghao Liu, Huijia Wu, Peipei Li, Zhiyuan Liu, Maosong Sun, Zhaofeng He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AI9Stars/AStar-Thought)](https://github.com/AI9Stars/AStar-Thought)

60. [**AutoL2S: Auto Long-Short Reasoning for Efficient Large Language Models.**](https://arxiv.org/abs/2505.22662) _Feng Luo, Yu-Neng Chuang, Guanchu Wang, Hoang Anh Duy Le, Shaochen Zhong, Hongyi Liu, Jiayi Yuan, Yang Sui, Vladimir Braverman, Vipin Chaudhary, Xia Hu._ Arxiv 2025.

61. [**Walk Before You Run! Concise LLM Reasoning via Reinforcement Learning.**](https://arxiv.org/abs/2505.21178) _Mingyang Song, Mao Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/ConciseR)](https://github.com/nick7nlp/ConciseR)

62. [**Self-Route: Automatic Mode Switching via Capability Estimation for Efficient Reasoning.**](https://arxiv.org/abs/2505.20664) _Yang He, Xiao Ding, Bibo Cai, Yufei Zhang, Kai Xiong, Zhouhao Sun, Bing Qin, Ting Liu._ Arxiv 2025.

63. [**Adaptive Deep Reasoning: Triggering Deep Thinking When Needed.**](https://arxiv.org/abs/2505.20101) _Yunhao Wang, Yuhao Zhang, Tinghao Yu, Can Xu, Feng Zhang, Fengzong Lian._ Arxiv 2025.

64. [**Thinking Fast and Right: Balancing Accuracy and Reasoning Length with Adaptive Rewards.**](https://arxiv.org/abs/2505.18298) _Jinyan Su, Claire Cardie._ Arxiv 2025.

65. [**Route to Reason: Adaptive Routing for LLM and Reasoning Strategy Selection.**](https://arxiv.org/abs/2505.19435) _Zhihong Pan, Kai Zhang, Yuze Zhao, Yupeng Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/goodmanpzh/Route-To-Reason)](https://github.com/goodmanpzh/Route-To-Reason)

#### 13.2 MLLM

1. [**Mitigating Visual Forgetting via Take-along Visual Conditioning for Multi-modal Long CoT Reasoning.**](https://arxiv.org/abs/2503.13360) _Hai-Long Sun, Zhun Sun, Houwen Peng, Han-Jia Ye._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/sun-hailong/TVC)](https://github.com/sun-hailong/TVC)

2. [**LongPerceptualThoughts: Distilling System-2 Reasoning for System-1 Perception.**](https://arxiv.org/abs/2504.15362) _Yuan-Hong Liao, Sven Elflein, Liu He, Laura Leal-Taixé, Yejin Choi, Sanja Fidler, David Acuna._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/andrewliao11/LongPerceptualThoughts)](https://github.com/andrewliao11/LongPerceptualThoughts)

### 14. Speculative Decoding

1. [**LongSpec: Long-Context Speculative Decoding with Efficient Drafting and Verification.**](https://arxiv.org/abs/2502.17421) _Penghui Yang, Cunxiao Du, Fengzhuo Zhang, Haonan Wang, Tianyu Pang, Chao Du, Bo An._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/LongSpec)](https://github.com/sail-sg/LongSpec)

2. [**Long-Context Inference with Retrieval-Augmented Speculative Decoding.**](https://arxiv.org/abs/2502.20330) _Guanzheng Chen, Qilong Feng, Jinjie Ni, Xin Li, Michael Qizhe Shieh._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/John-AI-Lab/RAPID)](https://github.com/John-AI-Lab/RAPID)

3. [**Efficient Reasoning for LLMs through Speculative Chain-of-Thought.**](https://arxiv.org/abs/2504.19095) _Jikai Wang, Juntao Li, Lijun Wu, Min Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Jikai0Wang/Speculative_CoT)](https://github.com/Jikai0Wang/Speculative_CoT)

4. [**L-MTP: Leap Multi-Token Prediction Beyond Adjacent Context for Large Language Models.**](https://arxiv.org/abs/2505.17505) _Xiaohao Liu, Xiaobo Xia, Weixiang Zhao, Manyi Zhang, Xianzhi Yu, Xiu Su, Shuo Yang, See-Kiong Ng, Tat-Seng Chua._ Arxiv 2025.

5. [**SpecExtend: A Drop-in Enhancement for Speculative Decoding of Long Sequences.**](https://arxiv.org/abs/2505.20776) _Jungyoub Cha, Hyunjong Kim, Sungzoon Cho._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/jycha98/SpecExtend)](https://github.com/jycha98/SpecExtend)

6. [**Mamba Drafters for Speculative Decoding.**](https://arxiv.org/abs/2506.01206) _Daewon Choi, Seunghyuk Oh, Saket Dingliwal, Jihoon Tack, Kyuyoung Kim, Woomin Song, Seojin Kim, Insu Han, Jinwoo Shin, Aram Galstyan, Shubham Katiyar, Sravan Babu Bodapati._ Arxiv 2025.

### 15. Technical Report

1. [**DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model.**](https://arxiv.org/abs/2405.04434) _DeepSeek-AI._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2)](https://github.com/deepseek-ai/DeepSeek-V2)

2. [**Qwen2.5 Technical Report.**](https://arxiv.org/abs/2412.15115) _Qwen: An Yang, Baosong Yang, Beichen Zhang, Binyuan Hui, Bo Zheng, Bowen Yu, Chengyuan Li, Dayiheng Liu, Fei Huang, Haoran Wei, Huan Lin, Jian Yang, Jianhong Tu, Jianwei Zhang, Jianxin Yang, Jiaxi Yang, Jingren Zhou, Junyang Lin, Kai Dang, Keming Lu, Keqin Bao, Kexin Yang, Le Yu, Mei Li, Mingfeng Xue, Pei Zhang, Qin Zhu, Rui Men, Runji Lin, Tianhao Li, Tianyi Tang, Tingyu Xia, Xingzhang Ren, Xuancheng Ren, Yang Fan, Yang Su, Yichang Zhang, Yu Wan, Yuqiong Liu, Zeyu Cui, Zhenru Zhang, Zihan Qiu (additional authors not shown)._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/QwenLM/Qwen2.5)](https://github.com/QwenLM/Qwen2.5)

3. [**DeepSeek-V3 Technical Report.**](https://arxiv.org/abs/2412.19437) _DeepSeek-AI, Aixin Liu, Bei Feng, Bing Xue, Bingxuan Wang, Bochao Wu, Chengda Lu, Chenggang Zhao, Chengqi Deng, Chenyu Zhang, Chong Ruan, Damai Dai, Daya Guo, Dejian Yang, Deli Chen, Dongjie Ji, Erhang Li, Fangyun Lin, Fucong Dai, Fuli Luo, Guangbo Hao, Guanting Chen, Guowei Li, H. Zhang, Han Bao, Hanwei Xu, Haocheng Wang, Haowei Zhang, Honghui Ding, Huajian Xin, Huazuo Gao, Hui Li, Hui Qu, J.L. Cai, Jian Liang, Jianzhong Guo, Jiaqi Ni, Jiashi Li, Jiawei Wang, Jin Chen, Jingchang Chen, Jingyang Yuan, Junjie Qiu, Junlong Li, Junxiao Song, Kai Dong, Kai Hu, Kaige Gao, Kang Guan, Kexin Huang, Kuai Yu, Lean Wang, Lecong Zhang, Lei Xu, Leyi Xia, Liang Zhao, Litong Wang, Liyue Zhang, Meng Li, Miaojun Wang, Mingchuan Zhang, Minghua Zhang, Minghui Tang, Mingming Li, Ning Tian, Panpan Huang, Peiyi Wang, Peng Zhang, Qiancheng Wang, Qihao Zhu, Qinyu Chen, Qiushi Du, R.J. Chen, R.L. Jin, Ruiqi Ge, Ruisong Zhang, Ruizhe Pan, Runji Wang, Runxin Xu, Ruoyu Zhang, Ruyi Chen, S.S. Li, Shanghao Lu, Shangyan Zhou, Shanhuang Chen, Shaoqing Wu, Shengfeng Ye, Shengfeng Ye, Shirong Ma, Shiyu Wang, Shuang Zhou, Shuiping Yu, Shunfeng Zhou, Shuting Pan, T. Wang, Tao Yun, Tian Pei, Tianyu Sun, W.L. Xiao, Wangding Zeng et al. (100 additional authors not shown)._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V3)](https://github.com/deepseek-ai/DeepSeek-V3)

4. [**MiniMax-01: Scaling Foundation Models with Lightning Attention.**](https://arxiv.org/abs/2501.08313) _MiniMax, Aonian Li, Bangwei Gong, Bo Yang, Boji Shan, Chang Liu, Cheng Zhu, Chunhao Zhang, Congchao Guo, Da Chen, Dong Li, Enwei Jiao, Gengxin Li, Guojun Zhang, Haohai Sun, Houze Dong, Jiadai Zhu, Jiaqi Zhuang, Jiayuan Song, Jin Zhu, Jingtao Han, Jingyang Li, Junbin Xie, Junhao Xu, Junjie Yan, Kaishun Zhang, Kecheng Xiao, Kexi Kang, Le Han, Leyang Wang, Lianfei Yu, Liheng Feng, Lin Zheng, Linbo Chai, Long Xing, Meizhi Ju, Mingyuan Chi, Mozhi Zhang, Peikai Huang, Pengcheng Niu, Pengfei Li, Pengyu Zhao, Qi Yang, Qidi Xu, Qiexiang Wang, Qin Wang, Qiuhui Li, Ruitao Leng, Shengmin Shi, Shuqi Yu, Sichen Li, Songquan Zhu, Tao Huang, Tianrun Liang, Weigao Sun, Weixuan Sun, Weiyu Cheng, Wenkai Li, Xiangjun Song, Xiao Su, Xiaodong Han, Xinjie Zhang, Xinzhu Hou, Xu Min, Xun Zou, Xuyang Shen, Yan Gong, Yingjie Zhu, Yipeng Zhou, Yiran Zhong, Yongyi Hu, Yuanxiang Fan, Yue Yu, Yufeng Yang, Yuhao Li, Yunan Huang, Yunji Li, Yunpeng Huang, Yunzhi Xu, Yuxin Mao, Zehan Li, Zekang Li, Zewei Tao, Zewen Ying, Zhaoyang Cong, Zhen Qin, Zhenhua Fan, Zhihang Yu, Zhuo Jiang, Zijia Wu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MiniMax-AI/MiniMax-01)](https://github.com/MiniMax-AI/MiniMax-01)

5. [**Qwen2.5-1M Technical Report.**](https://arxiv.org/abs/2501.15383) _An Yang, Bowen Yu, Chengyuan Li, Dayiheng Liu, Fei Huang, Haoyan Huang, Jiandong Jiang, Jianhong Tu, Jianwei Zhang, Jingren Zhou, Junyang Lin, Kai Dang, Kexin Yang, Le Yu, Mei Li, Minmin Sun, Qin Zhu, Rui Men, Tao He, Weijia Xu, Wenbiao Yin, Wenyuan Yu, Xiafei Qiu, Xingzhang Ren, Xinlong Yang, Yong Li, Zhiying Xu, Zipeng Zhang._ Arxiv 2025.

6. [**Phi-4-Mini Technical Report: Compact yet Powerful Multimodal Language Models via Mixture-of-LoRAs.**](https://arxiv.org/abs/2503.01743) _Abdelrahman Abouelenin, Atabak Ashfaq, Adam Atkinson, Hany Awadalla, Nguyen Bach, Jianmin Bao, Alon Benhaim, Martin Cai, Vishrav Chaudhary, Congcong Chen, Dong Chen, Dongdong Chen, Junkun Chen, Weizhu Chen, Yen-Chun Chen, Yi-ling Chen, Qi Dai, Xiyang Dai, Ruchao Fan, Mei Gao, Min Gao, Amit Garg, Abhishek Goswami, Junheng Hao, Amr Hendy, Yuxuan Hu, Xin Jin, Mahmoud Khademi, Dongwoo Kim, Young Jin Kim, Gina Lee, Jinyu Li, Yunsheng Li, Chen Liang, Xihui Lin, Zeqi Lin, Mengchen Liu, Yang Liu, Gilsinia Lopez, Chong Luo, Piyush Madan, Vadim Mazalov, Ali Mousavi, Anh Nguyen, Jing Pan, Daniel Perez-Becker, Jacob Platin, Thomas Portet, Kai Qiu, Bo Ren, Liliang Ren, Sambuddha Roy, Ning Shang, Yelong Shen, Saksham Singhal, Subhojit Som, Xia Song, Tetyana Sych, Praneetha Vaddamanu, Shuohang Wang, Yiming Wang, Zhenghao Wang, Haibin Wu, Haoran Xu, Weijian Xu, Yifan Yang, Ziyi Yang, Donghan Yu, Ishmam Zabir, Jianwen Zhang, Li Lyna Zhang, Yunan Zhang, Xiren Zhou._ Arxiv 2025.

7. [**EXAONE Deep: Reasoning Enhanced Language Models.**](https://arxiv.org/abs/2503.12524) _LG AI Research, Kyunghoon Bae, Eunbi Choi, Kibong Choi, Stanley Jungkyu Choi, Yemuk Choi, Seokhee Hong, Junwon Hwang, Hyojin Jeon, Kijeong Jeon, Gerrard Jeongwon Jo, Hyunjik Jo, Jiyeon Jung, Hyosang Kim, Joonkee Kim, Seonghwan Kim, Soyeon Kim, Sunkyoung Kim, Yireun Kim, Yongil Kim, Youchul Kim, Edward Hwayoung Lee, Haeju Lee, Honglak Lee, Jinsik Lee, Kyungmin Lee, Sangha Park, Yongmin Park, Sihoon Yang, Heuiyeen Yeen, Sihyuk Yi, Hyeongu Yun._ Arxiv 2025.

8. [**Gemma 3 Technical Report.**](https://arxiv.org/abs/2503.19786) _Gemma Team: Aishwarya Kamath, Johan Ferret, Shreya Pathak, Nino Vieillard, Ramona Merhej, Sarah Perrin, Tatiana Matejovicova, Alexandre Ramé, Morgane Rivière, Louis Rouillard, Thomas Mesnard, Geoffrey Cideron, Jean-bastien Grill, Sabela Ramos, Edouard Yvinec, Michelle Casbon, Etienne Pot, Ivo Penchev, Gaël Liu, Francesco Visin, Kathleen Kenealy, Lucas Beyer, Xiaohai Zhai, Anton Tsitsulin, Robert Busa-Fekete, Alex Feng, Noveen Sachdeva, Benjamin Coleman, Yi Gao, Basil Mustafa, Iain Barr, Emilio Parisotto, David Tian, Matan Eyal, Colin Cherry, Jan-Thorsten Peter, Danila Sinopalnikov, Surya Bhupatiraju, Rishabh Agarwal, Mehran Kazemi, Dan Malkin, Ravin Kumar, David Vilar, Idan Brusilovsky, Jiaming Luo, Andreas Steiner, Abe Friesen, Abhanshu Sharma, Abheesht Sharma, Adi Mayrav Gilady, Adrian Goedeckemeyer, Alaa Saade, Alex Feng, Alexander Kolesnikov, Alexei Bendebury, Alvin Abdagic, Amit Vadi, András György, André Susano Pinto, Anil Das, Ankur Bapna, Antoine Miech, Antoine Yang, Antonia Paterson, Ashish Shenoy, Ayan Chakrabarti, Bilal Piot, Bo Wu, Bobak Shahriari, Bryce Petrini, Charlie Chen, Charline Le Lan, Christopher A. Choquette-Choo, CJ Carey, Cormac Brick, Daniel Deutsch, Danielle Eisenbud, Dee Cattle, Derek Cheng, Dimitris Paparas, Divyashree Shivakumar Sreepathihalli, Doug Reid, Dustin Tran, Dustin Zelle, Eric Noland, Erwin Huizenga, Eugene Kharitonov, Frederick Liu, Gagik Amirkhanyan, Glenn Cameron, Hadi Hashemi, Hanna Klimczak-Plucińska, Harman Singh, Harsh Mehta, Harshal Tushar Lehri, Hussein Hazimeh, Ian Ballantyne, Idan Szpektor, Ivan Nardini et al.._ Arxiv 2025.

9. [**Phi-4-Mini-Reasoning: Exploring the Limits of Small Reasoning Language Models in Math.**](https://arxiv.org/abs/2504.21233) _Haoran Xu, Baolin Peng, Hany Awadalla, Dongdong Chen, Yen-Chun Chen, Mei Gao, Young Jin Kim, Yunsheng Li, Liliang Ren, Yelong Shen, Shuohang Wang, Weijian Xu, Jianfeng Gao, Weizhu Chen._ Arxiv 2025.

10. [**Phi-4-reasoning Technical Report.**](https://arxiv.org/abs/2504.21318) _Marah Abdin, Sahaj Agarwal, Ahmed Awadallah, Vidhisha Balachandran, Harkirat Behl, Lingjiao Chen, Gustavo de Rosa, Suriya Gunasekar, Mojan Javaheripi, Neel Joshi, Piero Kauffmann, Yash Lara, Caio César Teodoro Mendes, Arindam Mitra, Besmira Nushi, Dimitris Papailiopoulos, Olli Saarikivi, Shital Shah, Vaishnavi Shrivastava, Vibhav Vineet, Yue Wu, Safoora Yousefi, Guoqing Zheng._ Arxiv 2025.

11. [**Llama-Nemotron: Efficient Reasoning Models.**](https://arxiv.org/abs/2505.00949) _Akhiad Bercovich, Itay Levy, Izik Golan, Mohammad Dabbah, Ran El-Yaniv, Omri Puny, Ido Galil, Zach Moshe, Tomer Ronen, Najeeb Nabwani, Ido Shahaf, Oren Tropp, Ehud Karpas, Ran Zilberstein, Jiaqi Zeng, Soumye Singhal, Alexander Bukharin, Yian Zhang, Tugrul Konuk, Gerald Shen, Ameya Sunil Mahabaleshwarkar, Bilal Kartal, Yoshi Suhara, Olivier Delalleau, Zijia Chen, Zhilin Wang, David Mosallanezhad, Adi Renduchintala, Haifeng Qian, Dima Rekesh, Fei Jia, Somshubra Majumdar, Vahid Noroozi, Wasi Uddin Ahmad, Sean Narenthiran, Aleksander Ficek, Mehrzad Samadi, Jocelyn Huang, Siddhartha Jain, Igor Gitman, Ivan Moshkov, Wei Du, Shubham Toshniwal, George Armstrong, Branislav Kisacanin, Matvei Novikov, Daria Gitman, Evelina Bakhturina, Jane Polak Scowcroft, John Kamalu, Dan Su, Kezhi Kong, Markus Kliegl, Rabeeh Karimi, Ying Lin, Sanjeev Satheesh, Jupinder Parmar, Pritam Gundecha, Brandon Norick, Joseph Jennings, Shrimai Prabhumoye, Syeda Nahida Akter, Mostofa Patwary, Abhinav Khattar, Deepak Narayanan, Roger Waleffe, Jimmy Zhang, Bor-Yiing Su, Guyue Huang, Terry Kong, Parth Chadha, Sahil Jain, Christine Harvey, Elad Segal, Jining Huang, Sergey Kashirsky, Robert McQueen, Izzy Putterman, George Lam, Arun Venkatesan, Sherry Wu, Vinh Nguyen, Manoj Kilaru, Andrew Wang, Anna Warno, Abhilash Somasamudramath, Sandip Bhaskar, Maka Dong, Nave Assaf, Shahar Mor, Omer Ullman Argov, Scot Junkin, Oleksandr Romanenko, Pedro Larroy, Monika Katariya, Marco Rovinelli, Viji Balas, Nicholas Edelman, Anahita Bhiwandiwalla, Muthu Subramaniam et al.._ Arxiv 2025.

12. [**Skywork Open Reasoner 1 Technical Report.**](https://arxiv.org/abs/2505.22312) _Jujie He, Jiacai Liu, Chris Yuhao Liu, Rui Yan, Chaojie Wang, Peng Cheng, Xiaoyu Zhang, Fuxiang Zhang, Jiacheng Xu, Wei Shen, Siyuan Li, Liang Zeng, Tianwen Wei, Cheng Cheng, Bo An, Yang Liu, Yahui Zhou._ Arxiv 2025.

### 16. Blogs

1. [**Extending Context is Hard…but not Impossible†.**](https://kaiokendev.github.io/context) _kaiokendev._ 2023.

2. [**NTK-Aware Scaled RoPE.**](https://www.reddit.com/r/LocalLLaMA/comments/14lz7j5/ntkaware_scaled_rope_allows_llama_models_to_have/) _u/bloc97
   ._ 2023.

3. [**The Secret Sauce behind 100K context window in LLMs: all tricks in one place.**](https://blog.gopenai.com/how-to-speed-up-llms-and-use-100k-context-window-all-tricks-in-one-place-ffd40577b4c) _Galina Alperovich._ 2023.

4. [**Transformer升级之路：7、长度外推性与局部注意力.**](https://kexue.fm/archives/9431) _苏剑林(Jianlin Su)._ 2023.

5. [**Transformer升级之路：9、一种全局长度外推的新思路.**](https://kexue.fm/archives/9603) _苏剑林(Jianlin Su)._ 2023.

6. [**Transformer升级之路：12、无限外推的ReRoPE.**](https://kexue.fm/archives/9708) _苏剑林(Jianlin Su)._ 2023.

7. [**Transformer升级之路：14、当HWFA遇见ReRoPE.**](https://kexue.fm/archives/9731) _苏剑林(Jianlin Su)._ 2023.

8. [**Transformer升级之路：15、Key归一化助力长度外推.**](https://kexue.fm/archives/9859) _苏剑林(Jianlin Su)._ 2023.

9. [**Transformer升级之路：16、“复盘”长度外推技术.**](https://kexue.fm/archives/9948) _苏剑林(Jianlin Su)._ 2024.

10. [**Introducing RAG 2.0.**](https://contextual.ai/introducing-rag2/) _Contextual AI Team._ 2024.

11. [**How Do Language Models put Attention Weights over Long Context?.**](https://yaofu.notion.site/How-Do-Language-Models-put-Attention-Weights-over-Long-Context-10250219d5ce42e8b465087c383a034e) _Yao Fu._ 2024.

12. [**An open-source and open-access RAG platform.**](https://openrag.notion.site/Open-RAG-c41b2a4dcdea4527a7c1cd998e763595) _Yunfan Gao._ 2024.

13. [**Many-shot Jailbreaking.**](https://www.anthropic.com/research/many-shot-jailbreaking) _Anthropic._ 2024.

14. [**Full Stack Transformer Inference Optimization Season 2: Deploying Long-Context Models.**](https://yaofu.notion.site/Full-Stack-Transformer-Inference-Optimization-Season-2-Deploying-Long-Context-Models-ee25d3a77ba14f73b8ae19147f77d5e2) _Yao Fu._ 2024.

15. [**缓存与效果的极限拉扯：从MHA、MQA、GQA到MLA.**](https://spaces.ac.cn/archives/10091) _苏剑林(Jianlin Su)._ 2024.

16. [**Towards 100x Speedup: Full Stack Transformer Inference Optimization.**](https://yaofu.notion.site/Towards-100x-Speedup-Full-Stack-Transformer-Inference-Optimization-43124c3688e14cffaf2f1d6cbdf26c6c) _Yao Fu._ 2024.

17. [**2024.5 A Side-by-Side Comparison of the Long Context of Various LLMs (128k articles).**](https://zhuanlan.zhihu.com/p/699926343) _SomeoneKong._ 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SomeoneKong/llm_long_context_bench202405)](https://github.com/SomeoneKong/llm_long_context_bench202405)

18. [**2024.5 A Side-by-Side Comparison of the Long Context of Various LLMs (32k articles).**](https://zhuanlan.zhihu.com/p/700378183) _SomeoneKong._ 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SomeoneKong/llm_long_context_bench202405)](https://github.com/SomeoneKong/llm_long_context_bench202405)

19. [**Transformer升级之路：18、RoPE的底数设计原则.**](https://kexue.fm/archives/10122) _苏剑林(Jianlin Su)._ 2024.

20. [**Generalizing an LLM from 8k to 1M Context using Qwen-Agent.**](https://qwenlm.github.io/zh/blog/qwen-agent-2405/) _Qwen Team._ 2024.

21. [**FlashAttention-3: Fast and Accurate Attention with Asynchrony and Low-precision.**](https://tridao.me/blog/2024/flash3/) _Jay Shah, Ganesh Bikshandi, Ying Zhang, Vijay Thakkar, Pradeep Ramani, Tri Dao._ 2024.

<!-- ### Other Awesome Lists

* **[LCLM-Survey](https://github.com/LCLM-Space/LCLM-Survey)**  A collection of papers and resources related to Long Context Language Modeling. -->

## Acknowledgements

Please contact me if I miss your names in the list, I will add you back ASAP!

### Contributors

<a href="https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Xnhyacinth/Awesome-LLM-Long-Context-Modeling" alt="Contributors"/>
</a>

### Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Xnhyacinth/Awesome-LLM-Long-Context-Modeling&type=Timeline)](https://github.com/Xnhyacinth/Awesome-LLM-Long-Context-Modeling/stargazers)
