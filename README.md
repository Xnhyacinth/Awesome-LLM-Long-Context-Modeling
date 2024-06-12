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
* [12. Blogs](#12-Blogs)
* [Acknowledgements](#acknowledgements)

# 📢 News

- **[2024.06.12]**
    - Paper: [Samba: Simple Hybrid State Space Models for Efficient Unlimited Context Language Modeling](https://arxiv.org/abs/2406.07522)
    - Paper: [When Linear Attention Meets Autoregressive Decoding: Towards More Effective and Efficient Linearized Large Language Models](https://arxiv.org/abs/2406.07368)
    - Paper: [Effectively Compress KV Heads for LLM](https://arxiv.org/abs/2406.07056)
    - Paper: [Evaluating Zero-Shot Long-Context LLM Compression](https://arxiv.org/abs/2406.06773)
    - Paper: [Never Miss A Beat: An Efficient Recipe for Context Window Extension of Large Language Models with Consistent "Middle" Enhancement](https://arxiv.org/abs/2406.07138)

- **[2024.06.11]**
    - Paper: [Enhancing Long-Term Memory using Hierarchical Aggregate Tree for Retrieval Augmented Generation](https://arxiv.org/abs/2406.06124)
    - Paper: [SinkLoRA: Enhanced Efficiency and Chat Capabilities for Long-Context Large Language Models](https://arxiv.org/abs/2406.05678)
    - Paper: [Recurrent Context Compression: Efficiently Expanding the Context Window of LLM](https://arxiv.org/abs/2406.06110)
    - Paper: [RepoQA: Evaluating Long Context Code Understanding](https://arxiv.org/abs/2406.06025)
    - Paper: [LoCoCo: Dropping In Convolutions for Long Context Compression](https://arxiv.org/abs/2406.05317)
    - Blog: [Generalizing an LLM from 8k to 1M Context using Qwen-Agent](https://qwenlm.github.io/zh/blog/qwen-agent-2405/)

- **[2024.06.10]**
    - Paper: [Multi-Head RAG: Solving Multi-Aspect Problems with LLMs](https://arxiv.org/abs/2406.05085)
    - Paper: [CRAG -- Comprehensive RAG Benchmark](https://arxiv.org/abs/2406.04744)

- **[2024.06.07]**
    - Paper: [MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding](https://arxiv.org/abs/2406.04264)

- **[2024.06.06]**
    - Paper: [Chain of Agents: Large Language Models Collaborating on Long-Context Tasks](https://arxiv.org/abs/2406.02818)
    - Paper: [FragRel: Exploiting Fragment-level Relations in the External Memory of Large Language Models](https://arxiv.org/abs/2406.03092)
    - Paper: [PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling](https://arxiv.org/abs/2406.02069)

- **[2024.06.05]**
    - Paper: [Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding](https://arxiv.org/abs/2406.02472)
    - Paper: [Retaining Key Information under High Compression Ratios: Query-Guided Compressor for LLMs](https://arxiv.org/abs/2406.02376)
    - Paper: [PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling](https://arxiv.org/abs/2406.02069)
    - Paper: [Position Debiasing Fine-Tuning for Causal Perception in Long-Term Dialogue](https://arxiv.org/abs/2406.02002)
    - Paper: [Explicitly Encoding Structural Symmetry is Key to Length Generalization in Arithmetic Tasks](https://arxiv.org/abs/2406.01895)

- **[2024.06.04]**
    - Paper: [LongSkywork: A Training Recipe for Efficiently Extending Context Length in Large Language Models](https://arxiv.org/abs/2406.00605)
    - Paper: [Toward Conversational Agents with Context and Time Sensitive Long-term Memory](https://arxiv.org/abs/2406.00057)

- **[2024.06.03]**
    - Paper: [In-context Autoencoder for Context Compression in a Large Language Model](https://openreview.net/forum?id=uREj4ZuGJE) ICLR 2024
    - Paper: [You Only Scan Once: Efficient Multi-dimension Sequential Modeling with LightNet](https://arxiv.org/abs/2405.21022)
    - Paper: [Position Coupling: Leveraging Task Structure for Improved Length Generalization of Transformers](https://arxiv.org/abs/2405.20671)
    - Paper: [Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality](https://arxiv.org/abs/2405.21060)

- **[2024.05.31]**
    - Paper: [Language Models Need Inductive Biases to Count Inductively](https://arxiv.org/abs/2405.20131)
    - Paper: [The CAP Principle for LLM Serving: A Survey of Long-Context Large Language Model Serving](https://arxiv.org/abs/2405.11299)
    - Paper: [Is In-Context Learning Sufficient for Instruction Following in LLMs?](https://arxiv.org/abs/2405.19874)
    - Paper: [Quest: Query-centric Data Synthesis Approach for Long-context Scaling of Large Language Model](https://arxiv.org/abs/2405.19846)
    - Paper: [PostDoc: Generating Poster from a Long Multimodal Document Using Deep Submodular Optimization](https://arxiv.org/abs/2405.20213)

- **[2024.05.30]**
    - Paper: [Contextual Position Encoding: Learning to Count What's Important](https://arxiv.org/abs/2405.18719)
    - Paper: [EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture](https://arxiv.org/abs/2405.18991)
    - Paper: [VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos](https://arxiv.org/abs/2405.19209)
    - Blog: [Transformer升级之路：18、RoPE的底数设计原则](https://kexue.fm/archives/10122)

- **[2024.05.29]**
    - Paper: [Long Context is Not Long at All: A Prospector of Long-Dependency Data for Large Language Models](https://arxiv.org/abs/2405.17915)
    - Paper: [XL3M: A Training-free Framework for LLM Length Extension Based on Segment-wise Inference](https://arxiv.org/abs/2405.17755)
    - Blog: [2024.5 A Side-by-Side Comparison of the Long Context of Various LLMs (32k articles)](https://zhuanlan.zhihu.com/p/700378183)

- **[2024.05.28]**
    - Paper: [Zamba: A Compact 7B SSM Hybrid Model](https://arxiv.org/abs/2405.16712)
    - Paper: [SelfCP: Compressing Long Prompt to 1/12 Using the Frozen Large Language Model Itself](https://arxiv.org/abs/2405.17052)
    - Paper: [Various Lengths, Constant Speed: Efficient Language Modeling with Lightning Attention](https://arxiv.org/abs/2405.17381)
    - Paper: [Compressing Lengthy Context With UltraGist](https://arxiv.org/abs/2405.16635)
    - Paper: [Unlocking the Secrets of Linear Complexity Sequence Model from A Unified Perspective](https://arxiv.org/abs/2405.17383)
    - Paper: [Accelerating Inference of Retrieval-Augmented Generation via Sparse Context Selection](https://arxiv.org/abs/2405.16178)
    - Paper: [Attention as an RNN](https://arxiv.org/abs/2405.13956)

- **[2024.05.27]**
    - Paper: [Are Long-LLMs A Necessity For Long-Context Tasks?](https://arxiv.org/abs/2405.15318)
    - Blog: [2024.5 A Side-by-Side Comparison of the Long Context of Various LLMs (128k articles)](https://zhuanlan.zhihu.com/p/699926343)

- **[2024.05.24]**
    - Paper: [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831)
    - Paper: [Can LLMs Solve longer Math Word Problems Better?](https://arxiv.org/abs/2405.14804)
    - Paper: [CAPE: Context-Adaptive Positional Encoding for Length Extrapolation](https://arxiv.org/abs/2405.14722)
    - Paper: [Base of RoPE Bounds Context Length](https://arxiv.org/abs/2405.14591)
    - Paper: [MiniCache: KV Cache Compression in Depth Dimension for Large Language Models](https://arxiv.org/abs/2405.14366)
    - Paper: [xRAG: Extreme Context Compression for Retrieval-augmented Generation with One Token](https://arxiv.org/abs/2405.13792)
    - Paper: [Implicit In-context Learning](https://arxiv.org/abs/2405.14660)

- **[2024.05.22]**
    - Paper: [Your Transformer is Secretly Linear](https://arxiv.org/abs/2405.12250)
    - Paper: [Reducing Transformer Key-Value Cache Size with Cross-Layer Attentionr](https://arxiv.org/abs/2405.12981)
    - Paper: [PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference](https://arxiv.org/abs/2405.12532)
    - Paper: [SirLLM: Streaming Infinite Retentive LLM](https://arxiv.org/abs/2405.12528)
    - Paper: [Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression](https://arxiv.org/abs/2405.12591)
    - Paper: [OLAPH: Improving Factuality in Biomedical Long-form Question Answering](https://arxiv.org/abs/2405.12701)

- **[2024.05.17]**
    - Paper: [KG-RAG: Bridging the Gap Between Knowledge and Creativity](https://arxiv.org/abs/2405.12035)
    - Paper: [A Multi-Perspective Analysis of Memorization in Large Language Models](https://arxiv.org/abs/2405.11577)
    - Paper: [Imagination Augmented Generation: Learning to Imagine Richer Context for Question Answering over Large Language Models](https://arxiv.org/abs/2403.15268)

- **[2024.05.17]**
    - Paper: [DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model](https://arxiv.org/abs/2405.04434)
    - Paper: [Layer-Condensed KV Cache for Efficient Inference of Large Language Models](https://arxiv.org/abs/2405.10637)
    - Paper: [Feature-Adaptive and Data-Scalable In-Context Learning](https://arxiv.org/abs/2405.10738)
    - Blog: [缓存与效果的极限拉扯：从MHA、MQA、GQA到MLA](https://spaces.ac.cn/archives/10091)
    - Blog: [Towards 100x Speedup: Full Stack Transformer Inference Optimization](https://yaofu.notion.site/Towards-100x-Speedup-Full-Stack-Transformer-Inference-Optimization-43124c3688e14cffaf2f1d6cbdf26c6c)

- **[2024.05.19]**
    - Blog: [Full Stack Transformer Inference Optimization Season 2: Deploying Long-Context Models](https://yaofu.notion.site/Full-Stack-Transformer-Inference-Optimization-Season-2-Deploying-Long-Context-Models-ee25d3a77ba14f73b8ae19147f77d5e2)

- **[2024.05.17]**
    - Paper: [Many-Shot In-Context Learning in Multimodal Foundation Models](https://arxiv.org/abs/2405.09798)
    - Paper: [FinTextQA: A Dataset for Long-form Financial Question Answering](https://arxiv.org/abs/2405.09980)

- **[2024.05.16]**
    - Paper: [Challenges in Deploying Long-Context Transformers: A Theoretical Peak Performance Analysis](https://arxiv.org/abs/2405.08944)

- **[2024.05.14]**
    - Paper: [Evaluation of Retrieval-Augmented Generation: A Survey](https://arxiv.org/abs/2405.07437)

- **[2024.05.13]**
    - Paper: [Linearizing Large Language Models](https://arxiv.org/abs/2405.06640)
    - Paper: [A Survey on RAG Meets LLMs: Towards Retrieval-Augmented Large Language Models](https://arxiv.org/abs/2405.06211)
    - Paper: [HMT: Hierarchical Memory Transformer for Long Context Language Processing](https://arxiv.org/abs/2405.06067)
 
---

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

17. [**Layer-Condensed KV Cache for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2405.10637) *Haoyi Wu, Kewei Tu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

18. [**Reducing Transformer Key-Value Cache Size with Cross-Layer Attention.**](https://arxiv.org/abs/2405.12981) *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly.* Arxiv 2024.

19. [**PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference.**](https://arxiv.org/abs/2405.12532) *William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/mutonix/pyramidinfer)](https://github.com/mutonix/pyramidinfer)

20. [**Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression.**](https://arxiv.org/abs/2405.12591) *Peiyu Liu, Ze-Feng Gao, Wayne Xin Zhao, Yipeng Ma, Tao Wang, Ji-Rong Wen.* Arxiv 2024.

21. [**MiniCache: KV Cache Compression in Depth Dimension for Large Language Models.**](https://arxiv.org/abs/2405.14366) *Akide Liu, Jing Liu, Zizheng Pan, Yefei He, Gholamreza Haffari, Bohan Zhuang.* Arxiv 2024.

22. [**PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling.**](https://arxiv.org/abs/2406.02069) *Zefan Cai., Yichi Zhang, Bofei Gao, Tianyu Liu, Keming Lu, Wayne Xiong, Yue Dong, Baobao Chang, Junjie Hu, Wen Xiao.* Arxiv 2024.

23. [**Effectively Compress KV Heads for LLM.**](https://arxiv.org/abs/2406.07056) *Hao Yu, Zelan Yang, Shen Li, Yong Li, Jianxin Wu.* Arxiv 2024.

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

30. [**Long-Context Language Modeling with Parallel Context Encoding.**](https://arxiv.org/abs/2402.16617) *Howard Yen, Tianyu Gao, Danqi Chen.* Arxiv 2024.

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

45. [**CAPE: Context-Adaptive Positional Encoding for Length Extrapolation.**](https://arxiv.org/abs/2405.14722) *Chuanyang Zheng, Yihang Gao, Han Shi, Minbin Huang, Jingyao Li, Jing Xiong, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/CAPE)](https://github.com/chuanyang-Zheng/CAPE)

46. [**Contextual Position Encoding: Learning to Count What's Important.**](https://arxiv.org/abs/2405.18719) *Olga Golovneva, Tianlu Wang, Jason Weston, Sainbayar Sukhbaatar.* Arxiv 2024.

47. [**Quest: Query-centric Data Synthesis Approach for Long-context Scaling of Large Language Model.**](https://arxiv.org/abs/2405.19846) *Chaochen Gao, Xing Wu, Qi Fu, Songlin Hu.* Arxiv 2024.

48. [**Position Coupling: Leveraging Task Structure for Improved Length Generalization of Transformers.**](https://arxiv.org/abs/2405.20671) *Hanseul Cho, Jaeyoung Cha, Pranjal Awasthi, Srinadh Bhojanapalli, Anupam Gupta, Chulhee Yun.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/HanseulJo/position-coupling)](https://github.com/HanseulJo/position-coupling)

49. [**LongSkywork: A Training Recipe for Efficiently Extending Context Length in Large Language Models.**](https://arxiv.org/abs/2406.00605) *Liang Zhao, Tianwen Wei, Liang Zeng, Cheng Cheng, Liu Yang, Peng Cheng, Lijie Wang, Chenxia Li, Xuejie Wu, Bo Zhu, Yimeng Gan, Rui Hu, Shuicheng Yan, Han Fang, Yahui Zhou.* Arxiv 2024.

50. [**Explicitly Encoding Structural Symmetry is Key to Length Generalization in Arithmetic Tasks.**](https://arxiv.org/abs/2406.01895) *Mahdi Sabbaghi, George Pappas, Hamed Hassani, Surbhi Goel.* Arxiv 2024.

51. [**Never Miss A Beat: An Efficient Recipe for Context Window Extension of Large Language Models with Consistent "Middle" Enhancement.**](https://arxiv.org/abs/2406.07138) *Tong Wu, Yanpeng Zhao, Zilong Zheng.* Arxiv 2024.

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

16. [**Position Debiasing Fine-Tuning for Causal Perception in Long-Term Dialogue.**](https://arxiv.org/abs/2406.02002) *Shixuan Fan, Wei Wei, Wendi Li, Xian-Ling Mao, Wenfeng Xie, Dangyang Chen.* Arxiv 2024. 

17. [**Enhancing Long-Term Memory using Hierarchical Aggregate Tree for Retrieval Augmented Generation.**](https://arxiv.org/abs/2406.06124) *Aadharsh Aadhithya A, Sachin Kumar S, Soman K.P.* Arxiv 2024. 

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

## 8. Agent

1. [**LongAgent: Scaling Language Models to 128k Context through Multi-Agent Collaboration.**](https://arxiv.org/abs/2402.11550) *Jun Zhao, Can Zu, Hao Xu, Yi Lu, Wei He, Yiwen Ding, Tao Gui, Qi Zhang, Xuanjing Huang.* Arxiv 2024.

2. [**A Real-World WebAgent with Planning, Long Context Understanding, and Program Synthesis.**](https://openreview.net/forum?id=9JQtrumvg8) *Izzeddin Gur, Hiroki Furuta, Austin V Huang, Mustafa Safdari, Yutaka Matsuo, Douglas Eck, Aleksandra Faust.* ICLR 2024 Oral.

3. [**PEARL: Prompting Large Language Models to Plan and Execute Actions Over Long Documents.**](https://aclanthology.org/2024.eacl-long.29/) *Simeng Sun, Yang Liu, Shuohang Wang, Dan Iter, Chenguang Zhu, Mohit Iyyer.* EACL 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SimengSun/pearl)](https://github.com/SimengSun/pearl)

4. [**AMAGO: Scalable In-Context Reinforcement Learning for Adaptive Agents.**](https://openreview.net/forum?id=M6XWoEdmwf) *Jake Grigsby, Linxi Fan, Yuke Zhu.* ICLR 2024 Spotlight.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/UT-Austin-RPL/amago)](https://github.com/UT-Austin-RPL/amago)
[![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ut-austin-rpl.github.io/amago/)

5. [**Chain of Agents: Large Language Models Collaborating on Long-Context Tasks.**](https://arxiv.org/abs/2406.02818) *Yusen Zhang, Ruoxi Sun, Yanfei Chen, Tomas Pfister, Rui Zhang, Sercan Ö. Arik.* Arxiv 2024.

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

## 10. Long Video and Image

1. [**EasyAnimate: A High-Performance Long Video Generation Method based on Transformer Architecture.**](https://arxiv.org/abs/2405.18991) *Jiaqi Xu, Xinyi Zou, Kunzhe Huang, Yunkuo Chen, Bo Liu, MengLi Cheng, Xing Shi, Jun Huang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/aigc-apps/EasyAnimate)](https://github.com/aigc-apps/EasyAnimate)

2. [**VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos.**](https://arxiv.org/abs/2405.19209) *Ziyang Wang, Shoubin Yu, Elias Stengel-Eskin, Jaehong Yoon, Feng Cheng, Gedas Bertasius, Mohit Bansal.* Arxiv 2024.

3. [**PostDoc: Generating Poster from a Long Multimodal Document Using Deep Submodular Optimization.**](https://arxiv.org/abs/2405.20213) *Vijay Jaisankar, Sambaran Bandyopadhyay, Kalp Vyas, Varre Chaitanya, Shwetha Somasundaram.* Arxiv 2024.

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

[![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.aicrowd.com/challenges/meta-comprehensive-rag-benchmark-kdd-cup-2024)

### 11.2 MLLM

1. [**MileBench: Benchmarking MLLMs in Long Context.**](https://arxiv.org/abs/2404.18532) *Dingjie Song, Shunian Chen, Guiming Hardy Chen, Fei Yu, Xiang Wan, Benyou Wang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/MileBench/MileBench)](https://github.com/MileBench/MileBench)

2. [**Many-Shot In-Context Learning in Multimodal Foundation Models.**](https://arxiv.org/abs/2405.09798) *Yixing Jiang, Jeremy Irvin, Ji Hun Wang, Muhammad Ahmed Chaudhry, Jonathan H. Chen, Andrew Y. Ng.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/stanfordmlgroup/ManyICL)](https://github.com/stanfordmlgroup/ManyICL)

3. [**MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding.**](https://arxiv.org/abs/2406.04264) *Junjie Zhou, Yan Shu, Bo Zhao, Boya Wu, Shitao Xiao, Xi Yang, Yongping Xiong, Bo Zhang, Tiejun Huang, Zheng Liu.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding/tree/master/MLVU)

4. [**RepoQA: Evaluating Long Context Code Understanding.**](https://arxiv.org/abs/2406.06025) *Jiawei Liu, Jia Le Tian, Vijay Daita, Yuxiang Wei, Yifeng Ding, Yuhan Katherine Wang, Jun Yang, Lingming Zhang.* Arxiv 2024.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/evalplus/repoqa)](https://github.com/evalplus/repoqa)
[![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://evalplus.github.io/repoqa.html)

## 12. Blogs

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

## Acknowledgements
Please contact me if I miss your names in the list, I will add you back ASAP!
