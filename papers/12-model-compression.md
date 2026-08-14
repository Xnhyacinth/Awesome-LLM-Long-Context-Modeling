# 12. Model Compression for Long Context

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [12.1 Quantization](#121-quantization)
- [12.2 Distillation / Pruning](#122-distillation--pruning)
<!-- /chapter-toc -->

#### 12.1 Quantization

1. [**AWQ: Activation-aware Weight Quantization for LLM Compression and Acceleration.**](https://arxiv.org/abs/2306.00978) _Ji Lin, Jiaming Tang, Haotian Tang, Shang Yang, Wei-Ming Chen, Wei-Chen Wang, Guangxuan Xiao, Xingyu Dang, Chuang Gan, Song Han._ MLSys 2024 Best Paper Award. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/llm-awq)](https://github.com/mit-han-lab/llm-awq)

2. [**Hyper Compressed Fine-Tuning of Large Foundation Models with Quantum Inspired Adapters.**](https://arxiv.org/abs/2502.06916) _Snehal Raj, Brian Coyle._ Arxiv 2025.

3. [**NestQuant: Nested Lattice Quantization for Matrix Products and LLMs.**](https://arxiv.org/abs/2502.09720) _Semyon Savkin, Eitan Porat, Or Ordentlich, Yury Polyanskiy._ Arxiv 2025.

4. [**1bit-Merging: Dynamic Quantized Merging for Large Language Models.**](https://arxiv.org/abs/2502.10743) _Shuqi Liu, Han Wu, Bowei He, Zehua Liu, Xiongwei Han, Mingxuan Yuan, Linqi Song._ Arxiv 2025.
5. [**Compression Scaling Laws: Unifying Sparsity and Quantization.**](https://arxiv.org/abs/2502.16440) _Elias Frantar, Utku Evci, Wonpyo Park, Neil Houlsby, Dan Alistarh._ Arxiv 2025.

6. [**QuEST: Stable Training of LLMs with 1-Bit Weights and Activations.**](https://arxiv.org/abs/2502.05003) _Andrei Panferov, Jiale Chen, Soroush Tabesh, Roberto L. Castro, Mahdi Nikdan, Dan Alistarh._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/IST-DASLab/QuEST)](https://github.com/IST-DASLab/QuEST)

7. [**70% Size, 100% Accuracy: Lossless LLM Compression for Efficient GPU Inference via Dynamic-Length Float.**](https://arxiv.org/abs/2504.11651) _Tianyi Zhang, Yang Sui, Shaochen Zhong, Vipin Chaudhary, Xia Hu, Anshumali Shrivastava._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LeanModels/DFloat11)](https://github.com/LeanModels/DFloat11)

#### 12.2 Distillation / Pruning

1. [**DSFormer: Effective Compression of Text-Transformers by Dense-Sparse Weight Factorization.**](https://arxiv.org/abs/2312.13211) _Rahul Chand, Yashoteja Prabhu, Pratyush Kumar._ Arxiv 2023.

2. [**LLM-Pruner: On the Structural Pruning of Large Language Models.**](https://openreview.net/forum?id=J8Ajf9WfXP1) _Xinyin Ma, Gongfan Fang, Xinchao Wang._ NeurIPS 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/LLM-Pruner)](https://github.com/horseee/LLM-Pruner)

3. [**Compressing Large Language Models by Streamlining the Unimportant Layer.**](https://arxiv.org/abs/2403.19135) _Xiaodong Chen, Yuxuan Hu, Jing Zhang._ Arxiv 2024.

4. [**Feature-based Low-Rank Compression of Large Language Models via Bayesian Optimization.**](https://arxiv.org/abs/2405.10616) _Yixin Ji, Yang Xiang, Juntao Li, Wei Chen, Zhongyi Liu, Kehai Chen, Min Zhang._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Dereck0602/Bolaco)](https://github.com/Dereck0602/Bolaco)

5. [**Your Transformer is Secretly Linear.**](https://arxiv.org/abs/2405.12250) _Anton Razzhigaev, Matvey Mikhalchuk, Elizaveta Goncharova, Nikolai Gerasimenko, Ivan Oseledets, Denis Dimitrov, Andrey Kuznetsov._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AIRI-Institute/LLM-Microscope)](https://github.com/AIRI-Institute/LLM-Microscope)

6. [**Merging Feed-Forward Sublayers for Compressed Transformers.**](https://arxiv.org/abs/2501.06126) _Neha Verma, Kenton Murray, Kevin Duh._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nverma1/merging-ffs-compression)](https://github.com/nverma1/merging-ffs-compression/)

7. [**FlexiGPT: Pruning and Extending Large Language Models with Low-Rank Weight Sharing.**](https://arxiv.org/abs/2501.14713) _James Seale Smith, Chi-Heng Lin, Shikhar Tuli, Haris Jeelani, Shangqian Gao, Yilin Shen, Hongxia Jin, Yen-Chang Hsu._ NAACL 2025.

8. [**TensorLLM: Tensorising Multi-Head Attention for Enhanced Reasoning and Compression in LLMs.**](https://arxiv.org/abs/2501.15674) _Yuxuan Gu, Wuyang Zhou, Giorgos Iacovides, Danilo Mandic._ Arxiv 2025.

9. [**You Only Prune Once: Designing Calibration-Free Model Compression With Policy Learning.**](https://arxiv.org/abs/2501.15296) _Ayan Sengupta, Siddhant Chaudhary, Tanmoy Chakraborty._ ICLR 2025.

10. [**Mamba-Shedder: Post-Transformer Compression for Efficient Selective Structured State Space Models.**](https://arxiv.org/abs/2501.17088) _J. Pablo Muñoz, Jinjie Yuan, Nilesh Jain._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/IntelLabs/Hardware-Aware-Automated-Machine-Learning)](https://github.com/IntelLabs/Hardware-Aware-Automated-Machine-Learning)

11. [**TAID: Temporally Adaptive Interpolated Distillation for Efficient Knowledge Transfer in Language Models.**](https://arxiv.org/abs/2501.16937) _Makoto Shing, Kou Misaki, Han Bao, Sho Yokoi, Takuya Akiba._ ICLR 2025.

12. [**AdaSVD: Adaptive Singular Value Decomposition for Large Language Models.**](https://arxiv.org/abs/2502.01403) _Zhiteng Li, Mingyuan Xia, Jingyuan Zhang, Zheng Hui, Linghe Kong, Yulun Zhang, Xiaokang Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ZHITENGLI/AdaSVD)](https://github.com/ZHITENGLI/AdaSVD)

13. [**Activation-Informed Merging of Large Language Models.**](https://arxiv.org/abs/2502.02421) _Amin Heyrani Nobari, Kaveh Alimohammadi, Ali ArjomandBigdeli, Akash Srivastava, Faez Ahmed, Navid Azizan._ Arxiv 2025.

14. [**Adapt-Pruner: Adaptive Structural Pruning for Efficient Small Language Model Training.**](https://arxiv.org/abs/2502.03460) _Boyao Wang, Rui Pan, Shizhe Diao, Xingyuan Pan, Jipeng Zhang, Renjie Pi, Tong Zhang._ Arxiv 2025.

15. [**DarwinLM: Evolutionary Structured Pruning of Large Language Models.**](https://arxiv.org/abs/2502.07780) _Shengkun Tang, Oliver Sieberling, Eldar Kurtic, Zhiqiang Shen, Dan Alistarh._ Arxiv 2025.

16. [**Contextual Compression Encoding for Large Language Models: A Novel Framework for Multi-Layered Parameter Space Pruning.**](https://arxiv.org/abs/2502.08323) _Barnaby Schmitt, Alistair Grosvenor, Matthias Cunningham, Clementine Walsh, Julius Pembrokeshire, Jonathan Teel._ Arxiv 2025.

17. [**Forget the Data and Fine-Tuning! Just Fold the Network to Compress.**](https://arxiv.org/abs/2502.10216) _Dong Wang, Haris Šikić, Lothar Thiele, Olga Saukh._ ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nanguoyu/model-folding-universal)](https://github.com/nanguoyu/model-folding-universal)

18. [**Every Expert Matters: Towards Effective Knowledge Distillation for Mixture-of-Experts Language Models.**](https://arxiv.org/abs/2502.12947) _Gyeongman Kim, Gyouk Chu, Eunho Yang._ Arxiv 2025.

19. [**When Compression Meets Model Compression: Memory-Efficient Double Compression for Large Language Models.**](https://arxiv.org/abs/2502.15443) _Weilan Wang, Yu Mao, Dongdong Tang, Hongchao Du, Nan Guan, Chun Jason Xue._ Arxiv 2025.

20. [**Optimizing Singular Spectrum for Large Language Model Compression.**](https://arxiv.org/abs/2502.15092) _Dengjie Li, Tiancheng Shen, Yao Zhou, Baisong Yang, Zhongying Liu, Masheng Yang, Bernard Ghanem, Yibo Yang, Yujie Zhong, Ming-Hsuan Yang._ Arxiv 2025.

21. [**Delta Decompression for MoE-based LLMs Compression.**](https://arxiv.org/abs/2502.17298) _Hao Gu, Wei Li, Lujun Li, Qiyuan Zhu, Mark Lee, Shengjie Sun, Wei Xue, Yike Guo._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lliai/D2MoE)](https://github.com/lliai/D2MoE)

22. [**The Lottery LLM Hypothesis, Rethinking What Abilities Should LLM Compression Preserve?.**](https://arxiv.org/abs/2502.17535) _Zhenheng Tang, Xiang Liu, Qian Wang, Peijie Dong, Bingsheng He, Xiaowen Chu, Bo Li._ ICLR 2025.

23. [**Compressing Language Models for Specialized Domains.**](https://arxiv.org/abs/2502.18424) _Miles Williams, George Chrysostomou, Vitor Jeronymo, Nikolaos Aletras._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mlsw/domain-compression)](https://github.com/mlsw/domain-compression)

24. [**DeRS: Towards Extremely Efficient Upcycled Mixture-of-Experts Models.**](https://arxiv.org/abs/2503.01359) _Yongqi Huang, Peng Ye, Chenyu Huang, Jianjian Cao, Lin Zhang, Baopu Li, Gang Yu, Tao Chen._ CVPR 2025.

25. [**Efficiently Editing Mixture-of-Experts Models with Compressed Experts.**](https://arxiv.org/abs/2503.00634) _Yifei He, Yang Liu, Chen Liang, Hany Hassan Awadalla._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/yifei-he/Compressed-Experts)](https://github.com/yifei-he/Compressed-Experts)

26. [**IDEA Prune: An Integrated Enlarge-and-Prune Pipeline in Generative Language Model Pretraining.**](https://arxiv.org/abs/2503.05920) _Yixiao Li, Xianzhi Du, Ajay Jaiswal, Tao Lei, Tuo Zhao, Chong Wang, Jianyu Wang._ Arxiv 2025.

27. [**Towards Extreme Pruning of LLMs with Plug-and-Play Mixed Sparsity.**](https://arxiv.org/abs/2503.11164) _Chi Xu, Gefei Zhang, Yantong Zhu, Luca Benini, Guosheng Hu, Yawei Li, Zhihong Zhang._ Arxiv 2025.

28. [**SVD-LLM V2: Optimizing Singular Value Truncation for Large Language Model Compression.**](https://arxiv.org/abs/2503.12340) _Xin Wang, Samiul Alam, Zhongwei Wan, Hui Shen, Mi Zhang._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AIoT-MLSys-Lab/SVD-LLM)](https://github.com/AIoT-MLSys-Lab/SVD-LLM)

29. [**ClusComp: A Simple Paradigm for Model Compression and Efficient Finetuning.**](https://arxiv.org/abs/2503.13089) _Baohao Liao, Christian Herold, Seyyed Hadi Hashemi, Stefan Vasilev, Shahram Khadivi, Christof Monz._ Arxiv 2025.

30. [**Large Language Model Compression via the Nested Activation-Aware Decomposition.**](https://arxiv.org/abs/2503.17101) _Jun Lu, Tianyi Xu, Bill Ding, David Li, Yu Kang._ Arxiv 2025.

31. [**Compression Laws for Large Language Models.**](https://arxiv.org/abs/2504.04342) _Ayan Sengupta, Siddhant Chaudhary, Tanmoy Chakraborty._ Arxiv 2025.

32. [**Thanos: A Block-wise Pruning Algorithm for Efficient Large Language Model Compression.**](https://arxiv.org/abs/2504.05346) _Ivan Ilin, Peter Richtarik._ Arxiv 2025.

33. [**Efficient Hybrid Language Model Compression through Group-Aware SSM Pruning.**](https://arxiv.org/abs/2504.11409) _Ali Taghibakhshi, Sharath Turuvekere Sreenivas, Saurav Muralidharan, Marcin Chochowski, Yashaswi Karnati, Raviraj Joshi, Ameya Sunil Mahabaleshwarkar, Zijia Chen, Yoshi Suhara, Oluwatobi Olabiyi, Daniel Korzekwa, Mostofa Patwary, Mohammad Shoeybi, Jan Kautz, Bryan Catanzaro, Ashwath Aithal, Nima Tajbakhsh, Pavlo Molchanov._ Arxiv 2025.

34. [**From Large to Super-Tiny: End-to-End Optimization for Cost-Efficient LLMs.**](https://arxiv.org/abs/2504.13471) _Jiliang Ni, Jiachen Pu, Zhongyi Yang, Kun Zhou, Hui Wang, Xiaoliang Xiao, Dakui Wang, Xin Li, Jingfeng Luo, Conggang Hu._ Arxiv 2025.

35. [**ImPart: Importance-Aware Delta-Sparsification for Improved Model Compression and Merging in LLMs.**](https://arxiv.org/abs/2504.13237) _Yan Yang, Yixia Li, Hongru Wang, Xuetao Wei, Jianqiao Yu, Yun Chen, Guanhua Chen._ Arxiv 2025.

36. [**Efficient LLMs with AMP: Attention Heads and MLP Pruning.**](https://arxiv.org/abs/2504.21174) _Leandro Giusti Mugnaini, Bruno Lopes Yamamoto, Lucas Lauton de Alcantara, Victor Zacarias, Edson Bollis, Lucas Pellicer, Anna Helena Reali Costa, Artur Jordao._ IJCNN 2025.

37. [**ParamΔ for Direct Weight Mixing: Post-Train Large Language Model at Zero Cost.**](https://arxiv.org/abs/2504.21023) _Sheng Cao, Mingrui Wu, Karthik Prasad, Yuandong Tian, Zechun Liu._ ICLR 2025.

38. [**ReplaceMe: Network Simplification via Layer Pruning and Linear Transformations.**](https://arxiv.org/abs/2505.02819) _Dmitriy Shopkhoev, Ammar Ali, Magauiya Zhussip, Valentin Malykh, Stamatios Lefkimmiatis, Nikos Komodakis, Sergey Zagoruyko._ Arxiv 2025.

39. [**Activation-Guided Consensus Merging for Large Language Models.**](https://arxiv.org/abs/2505.14009) _Yuxuan Yao, Shuqi Liu, Zehua Liu, Qintong Li, Mingyang Liu, Xiongwei Han, Zhijiang Guo, Han Wu, Linqi Song._ Arxiv 2025.

40. [**Breaking the Compression Ceiling: Data-Free Pipeline for Ultra-Efficient Delta Compression.**](https://arxiv.org/abs/2505.13563) _Xiaohui Wang, Peng Ye, Chenyu Huang, Shenghe Zheng, Bo Zhang, Wanli Ouyang, Tao Chen._ Arxiv 2025.

41. [**LLM Compression: How Far Can We Go in Balancing Size and Performance?.**](https://arxiv.org/abs/2508.11318) _Sahil Sk, Debasish Dhal, Sonal Khosla, Sk Shahid, Sambit Shekhar, Akash Dhaka, Shantipriya Parida, Dilip K. Prasad, Ondřej Bojar._ Arxiv 2025.

42. [**One Shot vs. Iterative: Rethinking Pruning Strategies for Model Compression.**](https://arxiv.org/abs/2508.13836) _Mikołaj Janusz, Tomasz Wojnar, Yawei Li, Luca Benini, Kamil Adamczewski._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/janumiko/pruning-benchmark)](https://github.com/janumiko/pruning-benchmark)

43. [**The Thinking Spectrum: An Empirical Study of Tunable Reasoning in LLMs through Model Merging.**](https://arxiv.org/abs/2509.22034) _Xiaochong Lan, Yu Zheng, Shiteng Cao, Yong Li._ Arxiv 2025.

44. [**E3-Pruner: Towards Efficient, Economical, and Effective Layer Pruning for Large Language Models.**](https://arxiv.org/abs/2511.17205) _Tao Yuan, Haoli Bai, Yinfei Pan, Xuyang Cao, Tianyu Zhang, Lu Hou, Ting Hu, Xianzhi Yu._ Arxiv 2025.

45. [**Optimizing LLMs for Resource-Constrained Environments: A Survey of Model Compression Techniques.**](https://arxiv.org/abs/2505.02309) _Sanjay Surendranath Girija, Shashank Kapoor, Lakshit Arora, Dipen Pradhan, Aman Raj, Ankit Shetgaonkar._ IEEE COMPSAC 2025.

46. [**OpenBA-V2: Reaching 77.3% High Compression Ratio with Fast Multi-Stage Pruning.**](https://arxiv.org/abs/2405.05957) _Dan Qiao, Yi Su, Pinzheng Wang, Jing Ye, Wenjing Xie, Yuechi Zhou, Yuyang Ding, Zecheng Tang, Jikai Wang, Yixin Ji, Yue Wang, Pei Guo, Zechen Sun, Zikang Zhang, Juntao Li, Pingfu Chao, Wenliang Chen, Guohong Fu, Guodong Zhou, Qiaoming Zhu, Min Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLG/OpenBA-v2)](https://github.com/OpenNLG/OpenBA-v2)

47. [**Rethinking Kullback-Leibler Divergence in Knowledge Distillation for Large Language Models.**](https://arxiv.org/abs/2404.02657) _Taiqiang Wu, Chaofan Tao, Jiahao Wang, Zhe Zhao, Ngai Wong._ Arxiv 2024.
