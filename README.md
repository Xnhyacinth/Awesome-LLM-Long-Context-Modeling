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

- **[2025.08.22]**

  - Paper: [Conflict-Aware Soft Prompting for Retrieval-Augmented Generation](https://arxiv.org/abs/2508.15253) EMNLP 2025
  - Paper: [SparK: Query-Aware Unstructured Sparsity with Recoverable KV Cache Channel Pruning](https://arxiv.org/abs/2508.15212)

- **[2025.08.21]**

  - Paper: [NVIDIA Nemotron Nano 2: An Accurate and Efficient Hybrid Mamba-Transformer Reasoning Model](https://arxiv.org/abs/2508.14444)

- **[2025.08.20]**

  - Paper: [One Shot vs. Iterative: Rethinking Pruning Strategies for Model Compression](https://arxiv.org/abs/2508.13836)

- **[2025.08.19]**

  - Paper: [Sparse Attention across Multiple-context KV Cache](https://arxiv.org/abs/2508.11661)
  - Paper: [Fast, Slow, and Tool-augmented Thinking for LLMs: A Review](https://arxiv.org/abs/2508.12265)
  - Paper: [SSPO: Self-traced Step-wise Preference Optimization for Process Supervision and Reasoning Compression](https://arxiv.org/abs/2508.12604)
  - Paper: [OptimalThinkingBench: Evaluating Over and Underthinking in LLMs](https://arxiv.org/abs/2508.13141)

- **[2025.08.18]**

  - Paper: [Aware First, Think Less: Dynamic Boundary Self-Awareness Drives Extreme Reasoning Efficiency in Large Language Models](https://arxiv.org/abs/2508.11582)
  - Paper: [LLM Compression: How Far Can We Go in Balancing Size and Performance?](https://arxiv.org/abs/2508.11318)


- **[2025.08.15]**

  - Paper: [SABER: Switchable and Balanced Training for Efficient LLM Reasoning](https://arxiv.org/abs/2508.10026)
  - Paper: [XQuant: Breaking the Memory Wall for LLM Inference with KV Cache Rematerialization](https://arxiv.org/abs/2508.10395)

- **[2025.08.14]**

  - Paper: [Speed Always Wins: A Survey on Efficient Architectures for Large Language Models](https://arxiv.org/abs/2508.09834)
  - Paper: [PRELUDE: A Benchmark Designed to Require Global Comprehension and Reasoning over Long Contexts](https://arxiv.org/abs/2508.09848)
  - Paper: [Sample More to Think Less: Group Filtered Policy Optimization for Concise Reasoning](https://arxiv.org/abs/2508.09726)
  - Paper: [Episodic Memory Representation for Long-form Video Understanding](https://arxiv.org/abs/2508.09486)

- **[2025.08.13]**

  - Paper: [Retrospective Sparse Attention for Efficient Long-Context Generation](https://arxiv.org/abs/2508.09001)
  - Paper: [Train Long, Think Short: Curriculum Learning for Efficient Reasoning](https://arxiv.org/abs/2508.08940)

- **[2025.08.12]**

  - Paper: [Less Is More: Training-Free Sparse Attention with Global Locality for Efficient Reasoning](https://arxiv.org/abs/2508.07101)

### Month Papers

<details><summary>Month Papers</summary>

- **[2025.08.11]**

  - Paper: [DynImg: Key Frames with Visual Prompts are Good Representation for Multi-Modal Video Understanding](https://arxiv.org/abs/2507.15569) ICCV 2025
  - Paper: [Growing a Twig to Accelerate Large Vision-Language Models](https://arxiv.org/abs/2503.14075) ICCV 2025
  - Paper: [LVBench: An Extreme Long Video Understanding Benchmark](https://arxiv.org/abs/2406.08035) ICCV 2025
  - Paper: [VFlowOpt: A Token Pruning Framework for LMMs with Visual Information Flow-Guided Optimization](https://arxiv.org/abs/2508.05211) ICCV 2025
  - Paper: [SlimInfer: Accelerating Long-Context LLM Inference via Dynamic Token Pruning](https://arxiv.org/abs/2508.06447)
  - Paper: [Pruning the Unsurprising: Efficient Code Reasoning via First-Token Surprisal](https://arxiv.org/abs/2508.05988)
  - Paper: [AdaptInfer: Adaptive Token Pruning for Vision-Language Model Inference with Dynamical Text Guidance](https://arxiv.org/abs/2508.06084)
  - Paper: [Fourier-VLM: Compressing Vision Tokens in the Frequency Domain for Large Vision-Language Models](https://arxiv.org/abs/2508.06038)

- **[2025.08.07]**

  - Paper: [KVSink: Understanding and Enhancing the Preservation of Attention Sinks in KV Cache Quantization for LLMs](https://arxiv.org/abs/2508.04257) COLM 2025
  - Paper: [TSPO: Temporal Sampling Policy Optimization for Long-form Video Language Understanding](https://arxiv.org/abs/2508.04369)
  - Paper: [Thinking With Videos: Multimodal Tool-Augmented Reinforcement Learning for Long Video Reasoning](https://arxiv.org/abs/2508.04416)

- **[2025.08.05]**

  - Paper: [CompressKV: Semantic Retrieval Heads Know What Tokens are Not Important Before Generation](https://arxiv.org/abs/2508.02401)
  - Paper: [LeanK: Learnable K Cache Channel Pruning for Efficient Decoding](https://arxiv.org/abs/2508.02215)
  - Paper: [ProCut: LLM Prompt Compression via Attribution Estimation](https://arxiv.org/abs/2508.02053)
  - Paper: [Trainable Dynamic Mask Sparse Attention](https://arxiv.org/abs/2508.02124)
  - Paper: [A Glimpse to Compress: Dynamic Visual Token Pruning for Large Vision-Language Models](https://arxiv.org/abs/2508.01548)
  - Paper: [E-VRAG: Enhancing Long Video Understanding with Resource-Efficient Retrieval Augmented Generation](https://arxiv.org/abs/2508.01546)
  - Paper: [Free-MoRef: Instantly Multiplexing Context Perception Capabilities of Video-MLLMs within Single Inference](https://arxiv.org/abs/2508.02134) ICCV 2025

- **[2025.08.04]**

  - Paper: [HiPrune: Training-Free Visual Token Pruning via Hierarchical Attention in Vision-Language Models](https://arxiv.org/abs/2508.00553)
  - Paper: [Representation Shift: Unifying Token Compression with FlashAttention](https://arxiv.org/abs/2508.00367) ICCV 2025

- **[2025.07.31]**

  - Paper: [NeedleChain: Measuring Intact Long-Context Reasoning Capability of Large Language Models](https://arxiv.org/abs/2507.22411)

- **[2025.07.30]**

  - Paper: [TriangleMix: A Lossless and Efficient Attention Pattern for Long Context Prefilling](https://arxiv.org/abs/2507.21526)

- **[2025.07.29]**

  - Paper: [CaliDrop: KV Cache Compression with Calibration](https://arxiv.org/abs/2507.19906)
  - Paper: [HCAttention: Extreme KV Cache Compression via Heterogeneous Attention Computing for LLMs](https://arxiv.org/abs/2507.19823)
  - Paper: [FAEDKV: Infinite-Window Fourier Transform for Unbiased KV Cache Compression](https://arxiv.org/abs/2507.20030)
  - Paper: [SmallThinker: A Family of Efficient Large Language Models Natively Trained for Local Deployment](https://arxiv.org/abs/2507.20984)
  - Paper: [Kimi K2: Open Agentic Intelligence](https://arxiv.org/abs/2507.20534)

- **[2025.07.28]**

  - Paper: [Step-3 is Large yet Affordable: Model-system Co-design for Cost-effective Decoding](https://arxiv.org/abs/2507.19427)

- **[2025.07.22]**

  - Paper: [LaCache: Ladder-Shaped KV Caching for Efficient Long-Context Modeling of Large Language Models](https://arxiv.org/abs/2507.14204) ICML 2025
  - Paper: [LAPO: Internalizing Reasoning Efficiency via Length-Adaptive Policy Optimization](https://arxiv.org/abs/2507.15758)
  - Paper: [Hierarchical Budget Policy Optimization for Adaptive Reasoning](https://arxiv.org/abs/2507.15844)

- **[2025.07.21]**

  - Paper: [LoopServe: An Adaptive Dual-phase LLM Inference Acceleration System for Multi-Turn Dialogues](https://arxiv.org/abs/2507.13681)

- **[2025.07.17]**

  - Paper: [DAC: A Dynamic Attention-aware Approach for Task-Agnostic Prompt Compression](https://arxiv.org/abs/2507.11942) ACL 2025

- **[2025.07.15]**

  - Paper: [Think Clearly: Improving Reasoning via Redundant Token Pruning](https://arxiv.org/abs/2507.08806)
  - Paper: [Ref-Long: Benchmarking the Long-context Referencing Capability of Long-context Language Models](https://arxiv.org/abs/2507.09506) ACL 2025

- **[2025.07.14]**

  - Paper: [Krul: Efficient State Restoration for Multi-turn Conversations with Dynamic Cross-layer KV Sharing](https://arxiv.org/abs/2507.08045)
  - Paper: [Compactor: Calibrated Query-Agnostic KV Cache Compression with Approximate Leverage Scores](https://arxiv.org/abs/2507.08143)

- **[2025.07.10]**

  - Paper: [Gemini 2.5: Pushing the Frontier with Advanced Reasoning, Multimodality, Long Context, and Next Generation Agentic Capabilities](https://arxiv.org/abs/2507.06261)
  - Paper: [A Systematic Analysis of Hybrid Linear Attention](https://arxiv.org/abs/2507.06457)
  - Paper: [Adaptive Termination for Multi-round Parallel Reasoning: An Universal Semantic Entropy-Guided Framework](https://arxiv.org/abs/2507.06829)
  - Paper: [SpindleKV: A Novel KV Cache Reduction Method Balancing Both Shallow and Deep Layers](https://arxiv.org/abs/2507.06517) ACL 2025

- **[2025.07.09]**

  - Paper: [SARA: Selective and Adaptive Retrieval-augmented Generation with Context Compression](https://arxiv.org/abs/2507.05633)

- **[2025.07.08]**

  - Paper: [OrthoRank: Token Selection via Sink Token Orthogonality for Efficient LLM inference](https://arxiv.org/abs/2507.03865) ICML 2025
  - Paper: [DyCoke: Dynamic Compression of Tokens for Fast Video Large Language Models](https://arxiv.org/abs/2411.15024v3) ICCV 2025
  - Paper: [Q-Frame: Query-aware Frame Selection and Multi-Resolution Adaptation for Video-LLMs](https://arxiv.org/abs/2506.22139) ICCV 2025
  - Paper: [LOOM-Scope: a comprehensive and efficient LOng-cOntext Model evaluation framework](https://arxiv.org/abs/2507.04723)
  - Paper: [LLMThinkBench: Towards Basic Math Reasoning and Overthinking in Large Language Models](https://arxiv.org/abs/2507.04023)

- **[2025.07.04]**

  - Paper: [Fast and Simplex: 2-Simplicial Attention in Triton](https://arxiv.org/abs/2507.02754)

- **[2025.07.03]**

  - Paper: [MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent](https://arxiv.org/abs/2507.02259)

- **[2025.07.02]**

  - Paper: [GLM-4.1V-Thinking: Towards Versatile Multimodal Reasoning with Scalable Reinforcement Learning](https://arxiv.org/abs/2507.01006)

- **[2025.07.01]**

  - Paper: [Do Thinking Tokens Help or Trap? Towards More Efficient Large Reasoning Model](https://arxiv.org/abs/2506.23840)

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

34. [**Speed Always Wins: A Survey on Efficient Architectures for Large Language Models.**](https://arxiv.org/abs/2508.09834) _Weigao Sun, Jiaxi Hu, Yucheng Zhou, Jusen Du, Disen Lan, Kexin Wang, Tong Zhu, Xiaoye Qu, Yu Zhang, Xiaoyu Mo, Daizong Liu, Yuxuan Liang, Wenliang Chen, Guoqi Li, Yu Cheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/weigao266/Awesome-Efficient-Arch)](https://github.com/weigao266/Awesome-Efficient-Arch)

35. [**Speed Always Wins: A Survey on Efficient Architectures for Large Language Models.**](https://arxiv.org/abs/2508.12265) _Xinda Jia, Jinpeng Li, Zezhong Wang, Jingjing Li, Xingshan Zeng, Yasheng Wang, Weinan Zhang, Yong Yu, Weiwen Liu._ Arxiv 2025.

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

36. [**HiP Attention: Sparse Sub-Quadratic Attention with Hierarchical Attention Pruning.**](https://arxiv.org/abs/2406.09827) _Heejun Lee, Geon Park, Youngwan Lee, Jina Kim, Wonyoung Jeong, Myeongjae Jeon, Sung Ju Hwang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DeepAuto-AI/hip-attention)](https://github.com/DeepAuto-AI/hip-attention)

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

66. [**HATA: Trainable and Hardware-Efficient Hash-Aware Top-k Attention for Scalable Large Model Inference.**](https://arxiv.org/abs/2506.02572) _Ping Gong, Jiawei Yi, Shengnan Wang, Juncheng Zhang, Zewen Jin, Ouxiang Zhou, Ruibo Liu, Guanbin Xu, Youhui Bai, Bowen Ye, Kun Yuan, Tong Yang, Gong Zhang, Renhai Chen, Feng Wu, Cheng Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/gpzlx1/HATA)](https://github.com/gpzlx1/HATA)

67. [**Rectified Sparse Attention.**](https://arxiv.org/abs/2506.04108) _Yutao Sun, Tianzhu Ye, Li Dong, Yuqing Xia, Jian Chen, Yizhao Gao, Shijie Cao, Jianyong Wang, Furu Wei._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/unilm)](https://github.com/microsoft/unilm/tree/master/ReSA/)

68. [**SeerAttention-R: Sparse Attention Adaptation for Long Reasoning.**](https://arxiv.org/abs/2506.08889) _Yizhao Gao, Shuming Guo, Shijie Cao, Yuqing Xia, Yu Cheng, Lei Wang, Lingxiao Ma, Yutao Sun, Tianzhu Ye, Li Dong, Hayden Kwok-Hay So, Yu Hua, Ting Cao, Fan Yang, Mao Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/SeerAttention)](https://github.com/microsoft/SeerAttention)

69. [**Lag-Relative Sparse Attention In Long Context Training.**](https://arxiv.org/abs/2506.11498) _Manlai Liang, Wanyi Huang, Mandi Liu, Huaijun Li, Jinlong Li._ Arxiv 2025.

70. [**DAM: Dynamic Attention Mask for Long-Context Large Language Model Inference Acceleration.**](https://arxiv.org/abs/2506.11104) _Hanzhi Zhang, Heng Fan, Kewei Sha, Yan Huang, Yunhe Feng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/HanzhiZhang-Ulrica/DAM)](https://github.com/HanzhiZhang-Ulrica/DAM)

71. [**GTA: Grouped-head latenT Attention.**](https://arxiv.org/abs/2506.17286) _Luoyang Sun, Jiwen Jiang, Cheng Deng, Xinjian Wu, Haifeng Zhang, Lei Chen, Lionel Ni, Jun Wang._ Arxiv 2025.

72. [**Fast and Simplex: 2-Simplicial Attention in Triton.**](https://arxiv.org/abs/2507.02754) _Aurko Roy, Timothy Chou, Sai Surya Duvvuri, Sijia Chen, Jiecao Yu, Xiaodong Wang, Manzil Zaheer, Rohan Anil._ Arxiv 2025.

73. [**TriangleMix: A Lossless and Efficient Attention Pattern for Long Context Prefilling.**](https://arxiv.org/abs/2507.21526) _Zhiyuan He, Yike Zhang, Chengruidong Zhang, Huiqiang Jiang, Yuqing Yang, Lili Qiu._ Arxiv 2025.

74. [**Trainable Dynamic Mask Sparse Attention.**](https://arxiv.org/abs/2508.02124) _Jingze Shi, Yifan Wu, Bingheng Wu, Yiran Peng, Liangdong Wang, Guang Liu, Yuyu Luo._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SmallDoges/flash-dmattn)](https://github.com/SmallDoges/flash-dmattn)

75. [**Less Is More: Training-Free Sparse Attention with Global Locality for Efficient Reasoning.**](https://arxiv.org/abs/2508.07101) _Lijie Yang, Zhihao Zhang, Arti Jain, Shijie Cao, Baihong Yuan, Yiwei Chen, Zhihao Jia, Ravi Netravali._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DerrickYLJ/LessIsMore)](https://github.com/DerrickYLJ/LessIsMore)

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

116. [**InfiniteHiP: Extending Language Model Context Up to 3 Million Tokens on a Single GPU.**](https://arxiv.org/abs/2502.08910) _Heejun Lee, Geon Park, Jaduk Suh, Sung Ju Hwang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DeepAuto-AI/hip-attention)](https://github.com/DeepAuto-AI/hip-attention)

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

183. [**AhaKV: Adaptive Holistic Attention-Driven KV Cache Eviction for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2506.03762) _Yifeng Gu, Zicong Jiang, Jianxiu Jin, Kailing Guo, Ziyang Zhang, Xiangmin Xu._ Arxiv 2025.

184. [**Inference-Time Hyper-Scaling with KV Cache Compression.**](https://arxiv.org/abs/2506.05345) _Adrian Łańcucki, Konrad Staniszewski, Piotr Nawrot, Edoardo M. Ponti._ Arxiv 2025.

185. [**TaDA: Training-free recipe for Decoding with Adaptive KV Cache Compression and Mean-centering.**](https://arxiv.org/abs/2506.04642) _Vinay Joshi, Pratik Prabhanjan Brahma, Zicheng Liu, Emad Barsoum._ Arxiv 2025.

186. [**Homogeneous Keys, Heterogeneous Values: Exploiting Local KV Cache Asymmetry for Long-Context LLMs.**](https://arxiv.org/abs/2506.05410) _Wanyun Cui, Mingwei Xu._ Arxiv 2025.

187. [**Paged Attention Meets FlexAttention: Unlocking Long-Context Efficiency in Deployed Inference.**](https://arxiv.org/abs/2506.07311) _Thomas Joshi, Herman Saini, Neil Dhillon, Antoni Viros i Martin, Kaoutar El Maghraoui._ Arxiv 2025.

188. [**KVmix: Gradient-Based Layer Importance-Aware Mixed-Precision Quantization for KV Cache.**](https://arxiv.org/abs/2506.08018) _Fei Li, Song Liu, Weiguo Wu, Shiqiang Nie, Jinyu Wang._ Arxiv 2025.

189. [**Efficient Long-Context LLM Inference via KV Cache Clustering.**](https://arxiv.org/abs/2506.11418) _Jie Hu, Shengnan Wang, Yutong He, Ping Gong, Jiawei Yi, Juncheng Zhang, Youhui Bai, Renhai Chen, Gong Zhang, Cheng Li, Kun Yuan._ Arxiv 2025.

190. [**Beyond Homogeneous Attention: Memory-Efficient LLMs via Fourier-Approximated KV Cache.**](https://arxiv.org/abs/2506.11886) _Xiaoran Liu, Siyang He, Qiqi Wang, Ruixiao Li, Yuerong Song, Zhigeng Liu, Linlin Li, Qun Liu, Zengfeng Huang, Qipeng Guo, Ziwei He, Xipeng Qiu._ Arxiv 2025.

191. [**Latent Multi-Head Attention for Small Language Models.**](https://arxiv.org/abs/2506.09342) _Sushant Mehta, Raj Dandekar, Rajat Dandekar, Sreedath Panat._ Arxiv 2025.

192. [**Multipole Attention for Efficient Long Context Reasoning.**](https://arxiv.org/abs/2506.13059) _Coleman Hooper, Sebastian Zhao, Luca Manolache, Sehoon Kim, Michael W. Mahoney, Yakun Sophia Shao, Kurt Keutzer, Amir Gholami._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SqueezeAILab/MultipoleAttention)](https://github.com/SqueezeAILab/MultipoleAttention)

193. [**Mixture of Weight-shared Heterogeneous Group Attention Experts for Dynamic Token-wise KV Optimization.**](https://arxiv.org/abs/2506.13541v1) _Guanghui Song, Dongping Liao, Yiren Zhao, Kejiang Ye, Cheng-zhong Xu, Xitong Gao._ Arxiv 2025.

194. [**Cache Me If You Can: How Many KVs Do You Need for Effective Long-Context LMs?.**](https://arxiv.org/abs/2506.17121) _Adithya Bhaskar, Alexander Wettig, Tianyu Gao, Yihe Dong, Danqi Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-pli/PruLong)](https://github.com/princeton-pli/PruLong)

195. [**LazyEviction: Lagged KV Eviction with Attention Pattern Observation for Efficient Long Reasoning.**](https://arxiv.org/abs/2506.15969) _Haoyue Zhang, Hualei Zhang, Xiaosong Ma, Jie Zhang, Song Guo._ Arxiv 2025.

196. [**CommVQ: Commutative Vector Quantization for KV Cache Compression.**](https://arxiv.org/abs/2506.18879) _Junyan Li, Yang Zhang, Muhammad Yusuf Hassan, Talha Chafekar, Tianle Cai, Zhile Ren, Pengsheng Guo, Foroozan Karimzadeh, Colorado Reed, Chong Wang, Chuang Gan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UMass-Embodied-AGI/CommVQ)](https://github.com/UMass-Embodied-AGI/CommVQ)

197. [**SpindleKV: A Novel KV Cache Reduction Method Balancing Both Shallow and Deep Layers.**](https://arxiv.org/abs/2507.06517) _Zicong Tang, Shi Luohe, Zuchao Li, Baoyuan Qi, Guoming Liu, Lefei Zhang, Ping Wang._ ACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/tyxqc/SpindleKV)](https://github.com/tyxqc/SpindleKV)

198. [**Krul: Efficient State Restoration for Multi-turn Conversations with Dynamic Cross-layer KV Sharing.**](https://arxiv.org/abs/2507.08045) _Junyi Wen, Junyuan Liang, Zicong Hong, Wuhui Chen, Zibin Zheng._ Arxiv 2025.

199. [**Compactor: Calibrated Query-Agnostic KV Cache Compression with Approximate Leverage Scores.**](https://arxiv.org/abs/2507.08143) _Vivek Chari, Benjamin Van Durme._ Arxiv 2025.

200. [**Think Clearly: Improving Reasoning via Redundant Token Pruning.**](https://arxiv.org/abs/2507.08806) _Daewon Choi, Jimin Lee, Jihoon Tack, Woomin Song, Saket Dingliwal, Sai Muralidhar Jayanthi, Bhavana Ganesh, Jinwoo Shin, Aram Galstyan, Sravan Babu Bodapati._ Arxiv 2025.

201. [**AlayaDB: The Data Foundation for Efficient and Effective Long-context LLM Inference**](https://dl.acm.org/doi/10.1145/3722212.3724428) _Yangshen Deng, Zhengxin You, Long Xiang, Qilong Li, Peiqi Yuan, Zhaoyang Hong, Yitao Zheng, Wanting Li, Runzhong Li, Haotian Liu, Kyriakos Mouratidis, Man Lung Yiu, Huan Li, Qiaomu Shen, Rui Mao, Bo Tang._ SIGMOD 2025.

202. [**LoopServe: An Adaptive Dual-phase LLM Inference Acceleration System for Multi-Turn Dialogues.**](https://arxiv.org/abs/2507.13681) _Haoyang Li, Zhanchao Xu, Yiming Li, Xuejia Chen, Darian Li, Anxin Tian, Qingfa Xiao, Cheng Deng, Jun Wang, Qing Li, Lei Chen, Mingxuan Yuan._ Arxiv 2025.

203. [**LaCache: Ladder-Shaped KV Caching for Efficient Long-Context Modeling of Large Language Models.**](https://arxiv.org/abs/2507.14204) _Dachuan Shi, Yonggan Fu, Xiangchi Yuan, Zhongzhi Yu, Haoran You, Sixu Li, Xin Dong, Jan Kautz, Pavlo Molchanov, Yingyan (Celine)Lin._ ICML 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/tGATECH-EIC/LaCache)](https://github.com/GATECH-EIC/LaCache)

204. [**CaliDrop: KV Cache Compression with Calibration.**](https://arxiv.org/abs/2507.19906) _Yi Su, Quantong Qiu, Yuechi Zhou, Juntao Li, Qingrong Xia, Ping Li, Xinyu Duan, Zhefeng Wang, Min Zhang._ Arxiv 2025.

205. [**HCAttention: Extreme KV Cache Compression via Heterogeneous Attention Computing for LLMs.**](https://arxiv.org/abs/2507.19823) _Dongquan Yang, Yifan Yang, Xiaotian Yu, Xianbiao Qi, Rong Xiao._ Arxiv 2025.

206. [**FAEDKV: Infinite-Window Fourier Transform for Unbiased KV Cache Compression.**](https://arxiv.org/abs/2507.20030) _Runchao Li, Yao Fu, Mu Sheng, Xianxuan Long, Haotian Yu, Pan Li._ Arxiv 2025.

207. [**CompressKV: Semantic Retrieval Heads Know What Tokens are Not Important Before Generation.**](https://arxiv.org/abs/2508.02401) _Xiaolin Lin, Jingcun Wang, Olga Kondrateva, Yiyu Shi, Bing Li, Grace Li Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/TUDa-HWAI/CompressKV)](https://github.com/TUDa-HWAI/CompressKV)

208. [**LeanK: Learnable K Cache Channel Pruning for Efficient Decoding.**](https://arxiv.org/abs/2508.02215) _Yike Zhang, Zhiyuan He, Huiqiang Jiang, Chengruidong Zhang, Yuqing Yang, Jianyong Wang, Lili Qiu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference/tree/main/LeanK)

209. [**KVSink: Understanding and Enhancing the Preservation of Attention Sinks in KV Cache Quantization for LLMs.**](https://arxiv.org/abs/2508.04257) _Zunhai Su, Kehong Yuan._ COLM 2025.

210. [**SlimInfer: Accelerating Long-Context LLM Inference via Dynamic Token Pruning.**](https://arxiv.org/abs/2508.06447) _Lingkun Long, Rubing Yang, Yushi Huang, Desheng Hui, Ao Zhou, Jianlei Yang._ Arxiv 2025.

211. [**Retrospective Sparse Attention for Efficient Long-Context Generation.**](https://arxiv.org/abs/2508.09001) _Seonghwan Choi, Beomseok Kang, Dongwon Jo, Jae-Joon Kim._ Arxiv 2025.
