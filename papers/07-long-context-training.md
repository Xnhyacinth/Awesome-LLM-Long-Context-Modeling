# 7. Long-Context Training

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [7.1 Continual Pretraining / Long-SFT](#71-continual-pretraining--long-sft)
  - [7.1.1 Continual Pretraining & Context Extension](#711-continual-pretraining--context-extension)
  - [7.1.2 Long-SFT / Data Synthesis / Alignment](#712-long-sft--data-synthesis--alignment)
- [7.2 Adaptation & RL for Long Context](#72-adaptation--rl-for-long-context)
- [7.3 Mid-Training: Data, Recipes & Scaling](#73-mid-training-data-recipes--scaling)
<!-- /chapter-toc -->

#### 7.1 Continual Pretraining / Long-SFT

##### 7.1.1 Continual Pretraining & Context Extension

1. [**Focused Transformer: Contrastive Training for Context Scaling.**](https://arxiv.org/abs/2307.03170) _Szymon Tworkowski, Konrad Staniszewski, Mikołaj Pacek, Yuhuai Wu, Henryk Michalewski, Piotr Miłoś._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/CStanKonrad/long_llama)](https://github.com/CStanKonrad/long_llama)

2. [**PoSE: Efficient Context Window Extension of LLMs via Positional Skip-wise Training.**](https://arxiv.org/abs/2309.10400) _Dawei Zhu,Nan Yang,Liang Wang,Yifan Song,Wenhao Wu,Furu Wei,Sujian Li._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/PoSE)](https://github.com/dwzhu-pku/PoSE)

3. [**Structured Packing in LLM Training Improves Long Context Utilization.**](https://arxiv.org/abs/2312.17296) _Konrad Staniszewski, Szymon Tworkowski, Sebastian Jaszczur, Henryk Michalewski, Łukasz Kuciński, Piotr Miłoś._ Arxiv 2024.

4. [**Extending LLMs' Context Window with 100 Samples.**](https://arxiv.org/abs/2401.07004) _Yikai Zhang, Junlong Li, Pengfei Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/Entropy-ABF)](https://github.com/GAIR-NLP/Entropy-ABF)

5. [**E^2-LLM: Efficient and Extreme Length Extension of Large Language Models.**](https://arxiv.org/abs/2401.06951) _Jiaheng Liu, Zhiqi Bai, Yuanxing Zhang, Chenchen Zhang, Yu Zhang, Ge Zhang, Jiakai Wang, Haoran Que, Yukang Chen, Wenbo Su, Tiezheng Ge, Jie Fu, Wenhu Chen, Bo Zheng._ Arxiv 2024.

6. [**Long-Context Language Modeling with Parallel Context Encoding.**](https://arxiv.org/abs/2402.16617) _Howard Yen, Tianyu Gao, Danqi Chen._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/CEPE)](https://github.com/princeton-nlp/CEPE)

7. [**In-Context Pretraining: Language Modeling Beyond Document Boundaries.**](https://openreview.net/forum?id=LXVswInHOo) _Weijia Shi, Sewon Min, Maria Lomeli, Chunting Zhou, Margaret Li, Xi Victoria Lin, Noah A. Smith, Luke Zettlemoyer, Wen-tau Yih, Mike Lewis._ ICLR 2024 Spotlight. [![GitHub Repo stars](https://img.shields.io/github/stars/swj0419/in-context-pretraining)](https://github.com/swj0419/in-context-pretraining)

8. [**Effective Long-Context Scaling of Foundation Models.**](https://arxiv.org/abs/2309.16039) _Wenhan Xiong, Jingyu Liu, Igor Molybog, Hejia Zhang, Prajjwal Bhargava, Rui Hou, Louis Martin, Rashi Rungta, Karthik Abinav Sankararaman, Barlas Oguz, Madian Khabsa, Han Fang, Yashar Mehdad, Sharan Narang, Kshitiz Malik, Angela Fan, Shruti Bhosale, Sergey Edunov, Mike Lewis, Sinong Wang, Hao Ma._ Arxiv 2023.

9. [**Fewer Truncations Improve Language Modeling.**](https://arxiv.org/abs/2404.10830) _Hantian Ding, Zijian Wang, Giovanni Paolini, Varun Kumar, Anoop Deoras, Dan Roth, Stefano Soatto._ Arxiv 2024.

10. [**Extending Llama-3's Context Ten-Fold Overnight.**](https://arxiv.org/abs/2404.19553) _Peitian Zhang, Ninglu Shao, Zheng Liu, Shitao Xiao, Hongjin Qian, Qiwei Ye, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

11. [**LongSkywork: A Training Recipe for Efficiently Extending Context Length in Large Language Models.**](https://arxiv.org/abs/2406.00605) _Liang Zhao, Tianwen Wei, Liang Zeng, Cheng Cheng, Liu Yang, Peng Cheng, Lijie Wang, Chenxia Li, Xuejie Wu, Bo Zhu, Yimeng Gan, Rui Hu, Shuicheng Yan, Han Fang, Yahui Zhou._ Arxiv 2024.

12. [**Scaling Granite Code Models to 128K Context.**](https://arxiv.org/abs/2407.13739) _Matt Stallone, Vaibhav Saxena, Leonid Karlinsky, Bridget McGinn, Tim Bula, Mayank Mishra, Adriana Meza Soria, Gaoyuan Zhang, Aditya Prasad, Yikang Shen, Saptha Surendran, Shanmukha Guttula, Hima Patel, Parameswaran Selvam, Xuan-Hong Dang, Yan Koyfman, Atin Sood, Rogerio Feris, Nirmit Desai, David D. Cox, Ruchir Puri, Rameswar Panda._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ibm-granite/granite-code-models)](https://github.com/ibm-granite/granite-code-models)

13. [**LongRecipe: Recipe for Efficient Long Context Generalization in Large Language Models.**](https://arxiv.org/abs/2409.00509) _Zhiyuan Hu, Yuliang Liu, Jinman Zhao, Suyuchen Wang, Yan Wang, Wei Shen, Qing Gu, Anh Tuan Luu, See-Kiong Ng, Zhiwei Jiang, Bryan Hooi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zhiyuanhubj/LongRecipe)](https://github.com/zhiyuanhubj/LongRecipe)

14. [**E2LLM: Encoder Elongated Large Language Models for Long-Context Understanding and Reasoning.**](https://arxiv.org/abs/2409.06679) _Zihan Liao, Jun Wang, Hang Yu, Lingxiao Wei, Jianguo Li, Jun Wang, Wei Zhang._ Arxiv 2024.

15. [**A Little Goes a Long Way: Efficient Long Context Training and Inference with Partial Contexts.**](https://arxiv.org/abs/2410.01485) _Suyu Ge, Xihui Lin, Yunan Zhang, Jiawei Han, Hao Peng._ Arxiv 2024.

16. [**How to Train Long-Context Language Models (Effectively).**](https://arxiv.org/abs/2410.02660) _Tianyu Gao, Alexander Wettig, Howard Yen, Danqi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/ProLong)](https://github.com/princeton-nlp/ProLong)

17. [**Breaking the Stage Barrier: A Novel Single-Stage Approach to Long Context Extension for Large Language Models.**](https://arxiv.org/abs/2412.07171) _Haoran Lian, Junmin Chen, Wei Huang, Yizhe Xiong, Wenping Hu, Guiguang Ding, Hui Chen, Jianwei Niu, Zijia Lin, Fuzheng Zhang, Di Zhang._ Arxiv 2024.

18. [**Adjoint sharding for very long context training of state space models.**](https://arxiv.org/abs/2501.00692) _Xingzi Xu, Amir Tavanaei, Kavosh Asadi, Karim Bouyarmane._ Arxiv 2025.

19. [**Sliding Window Attention Training for Efficient Large Language Models.**](https://arxiv.org/abs/2502.18845) _Zichuan Fu, Wentao Song, Yejing Wang, Xian Wu, Yefeng Zheng, Yingying Zhang, Derong Xu, Xuetao Wei, Tong Xu, Xiangyu Zhao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Lyun0912-wu/LongAttn](https://anonymous.4open.science/r/SWAT-attention/README.md)

20. [**ByteScale: Efficient Scaling of LLM Training with a 2048K Context Length on More Than 12,000 GPUs.**](https://arxiv.org/abs/2502.21231) _Hao Ge, Junda Feng, Qi Huang, Fangcheng Fu, Xiaonan Nie, Lei Zuo, Haibin Lin, Bin Cui, Xin Liu._ Arxiv 2025.

21. [**Token Weighting for Long-Range Language Modeling.**](https://arxiv.org/abs/2503.09202) _Falko Helm, Nico Daheim, Iryna Gurevych._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UKPLab/naacl2025-token-weighting)](https://github.com/UKPLab/naacl2025-token-weighting)

22. [**From 128K to 4M: Efficient Training of Ultra-Long Context Large Language Models.**](https://arxiv.org/abs/2504.06214) _Chejian Xu, Wei Ping, Peng Xu, Zihan Liu, Boxin Wang, Mohammad Shoeybi, Bo Li, Bryan Catanzaro._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ultralong.github.io/)

23. [**Arctic Long Sequence Training: Scalable And Efficient Training For Multi-Million Token Sequences.**](https://arxiv.org/abs/2506.13996) _Stas Bekman, Samyam Rajbhandari, Michael Wyatt, Jeff Rasley, Tunji Ruwase, Zhewei Yao, Aurick Qiao, Yuxiong He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/snowflakedb/ArcticTraining)](https://github.com/snowflakedb/ArcticTraining/blob/main/projects/sequence-parallelism/README.md)

24. [**Heterogeneous Parallelism for Multimodal Large Language Model Training.**](https://arxiv.org/abs/2605.27678) _Yashaswi Karnati, Kamran Jafari, Akash Mehra, Li Ding, Pranav Prashant Thombre, Ali Roshan Ghias, Shifang Xu, Parth Mannan, Yu Yao, Hao Wu, Eric Harper, Ashwath Aithal, Nima Tajbakhsh._ Arxiv 2026.

25. [**Long-Context Fine-Tuning with Limited VRAM.**](https://arxiv.org/abs/2607.15105) _Vladimir Fedosov, Aleksandr Sazhin, Artemiy Grinenko, Frank Woernle._ Arxiv 2026.

26. [**Information Abundance Paradox: Long-Context Training Undermines Parametric Knowledge.**](https://arxiv.org/abs/2608.12218) _Arda Uzunoglu, Benjamin Van Durme, Daniel Khashabi._ Arxiv 2026.

27. [**Cracks in the Foundation: Seemingly Minor Architectural Choices Impact Long Context Extension.**](https://arxiv.org/abs/2608.10296) _Amanda Bertsch, Luca Soldaini, Matthew R. Gormley, Graham Neubig, Hannaneh Hajishirzi, Kyle Lo, Dirk Groeneveld._ COLM 2026.

28. [**OctoLong: Mid-Training On Cross-Repository Code Contexts Enhances Long-Context Modeling.**](https://arxiv.org/abs/2608.05141) _Indraneil Paul, Falko Helm, Goran Glavaš, Iryna Gurevych._ Arxiv 2026.

29. [**Don't Stop Long-Context Continual Pre-Training Too Early: An Empirical Scaling Law.**](https://arxiv.org/abs/2610.29352) _Ziqing Qiao, Xiaoyue Xu, Sikui Zhang, Yinuo Xu, Bingxiang He, Chaojun Xiao, Xu Han._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/dont-stop-lccp)](https://github.com/thunlp/dont-stop-lccp)

30. [**Beyond Length: Quantifying Long-Range Information for Long-Context LLM Pretraining Data.**](https://arxiv.org/abs/2510.25804) _Haoran Deng, Yingyu Lin, Zhenghao Lin, Xiao Liu, Yizhou Sun, Yi-An Ma, Yeyun Gong._ Arxiv 2025.

31. [**Out of the Memory Barrier: A Highly Memory Efficient Training System for LLMs with Million-Token Contexts.**](https://arxiv.org/abs/2602.02108) _Wenhao Li, Daohai Yu, Gen Luo, Yuxin Zhang, Fei Chao, Rongrong Ji, Yifan Wu, Jiaxin Liu, Ziyang Gong, Zimu Liao._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/wenhaoli-xmu/OOMB)](https://github.com/wenhaoli-xmu/OOMB)

32. [**Revealing the Learning Dynamics of Long-Context Continual Pre-training.**](https://arxiv.org/abs/2604.02650) _Yupu Liang, Shuang Chen, Guanwei Zhang, Shaolei Wang, Suncong Zheng._ Arxiv 2026.

33. [**Long-Context Aware Upcycling: A New Frontier for Hybrid LLM Scaling.**](https://arxiv.org/abs/2604.24715) _Parsa Ashrafi Fashi, Utkarsh Saxena, Mehdi Rezagholizadeh, Aref Jafari, Akash Haridas, Mingyu Yang, Vansh Bhatia, Guihong Li, Vikram Appia, Emad Barsoum._ Arxiv 2026.

34. [**Long Context Pre-Training with Lighthouse Attention.**](https://arxiv.org/abs/2605.06554) _Bowen Peng, Subho Ghosh, Jeffrey Quesnelle._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/ighoshsubho/lighthouse-attention)](https://github.com/ighoshsubho/lighthouse-attention)

35. [**Training Long-Context Vision-Language Models Effectively with Generalization Beyond 128K Context.**](https://arxiv.org/abs/2605.13831) _Zhaowei Wang, Lishu Luo, Haodong Duan, Weiwei Liu, Sijin Wu, Ji Luo, Shen Yan, Shuai Peng, Sihang Yuan, Chaoyi Huang, Yi Lin, Yangqiu Song._ NeurIPS 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/zhaowei-wang-nlp/MMProLong)](https://github.com/zhaowei-wang-nlp/MMProLong)

36. [**Which Long Documents Matter? A Controlled Study of Data Selection for Context Extension.**](https://arxiv.org/abs/2610.24469) _Junlong Jia, Jiang Zhou, Xing Wu, Chaochen Gao, Tinghao Yu, Feng Zhang, Lilin Wang._ Arxiv 2026.

##### 7.1.2 Long-SFT / Data Synthesis / Alignment

1. [**LongLoRA: Efficient Fine-tuning of Long-Context Large Language Models.**](https://arxiv.org/abs/2309.12307) _Yukang Chen, Shengju Qian, Haotian Tang, Xin Lai, Zhijian Liu, Song Han, Jiaya Jia._ ICLR 2024 Oral. [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/LongLoRA)](https://github.com/dvlab-research/LongLoRA)

2. [**Data Engineering for Scaling Language Models to 128K Context.**](https://arxiv.org/abs/2402.10171) _Yao Fu, Rameswar Panda, Xinyao Niu, Xiang Yue, Hannaneh Hajishirzi, Yoon Kim, Hao Peng._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FranxYao/Long-Context-Data-Engineering)](https://github.com/FranxYao/Long-Context-Data-Engineering)

3. [**Long Context Alignment with Short Instructions and Synthesized Positions.**](https://arxiv.org/abs/2405.03939) _Wenhao Wu, Yizhong Wang, Yao Fu, Xiang Yue, Dawei Zhu, Sujian Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nightdessert/SkipAlign)](https://github.com/nightdessert/SkipAlign)

4. [**Quest: Query-centric Data Synthesis Approach for Long-context Scaling of Large Language Model.**](https://arxiv.org/abs/2405.19846) _Chaochen Gao, Xing Wu, Qi Fu, Songlin Hu._ Arxiv 2024.

5. [**ChatQA 2: Bridging the Gap to Proprietary LLMs in Long Context and RAG Capabilities.**](https://arxiv.org/abs/2407.14482) _Peng Xu, Wei Ping, Xianchao Wu, Zihan Liu, Mohammad Shoeybi, Bryan Catanzaro._ Arxiv 2024.

6. [**Untie the Knots: An Efficient Data Augmentation Strategy for Long-Context Pre-Training in Language Models.**](https://arxiv.org/abs/2409.04774) _Junfeng Tian, Da Zheng, Yang Cheng, Rui Wang, Colin Zhang, Debing Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/rgtjf/Untie-the-Knots)](https://github.com/rgtjf/Untie-the-Knots)

7. [**Selecting Influential Samples for Long Context Alignment via Homologous Models' Guidance and Contextual Awareness Measurement.**](https://arxiv.org/abs/2410.15633) _Shuzheng Si, Haozhe Zhao, Gang Chen, Yunshui Li, Kangyang Luo, Chuancheng Lv, Kaikai An, Fanchao Qi, Baobao Chang, Maosong Sun._ Arxiv 2024.

8. [**Large Language Models Can Self-Improve in Long-context Reasoning.**](https://arxiv.org/abs/2411.08147) _Siheng Li, Cheng Yang, Zesen Cheng, Lemao Liu, Mo Yu, Yujiu Yang, Wai Lam._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SihengLi99/SEALONG)](https://github.com/SihengLi99/SEALONG)

9. [**LeMo: Enabling LEss Token Involvement for MOre Context Fine-tuning.**](https://arxiv.org/abs/2501.09767) _Tuowei Wang, Xingyu Chen, Kun Li, Ting Cao, Ju Ren, Yaoxue Zhang._ Arxiv 2025.

10. [**NExtLong: Toward Effective Long-Context Training without Long Documents.**](https://arxiv.org/abs/2501.12766) _Chaochen Gao, Xing Wu, Zijia Lin, Debing Zhang, Songlin Hu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/caskcsg/longcontext)](https://github.com/caskcsg/longcontext/tree/main/NExtLong)

11. [**LongReD: Mitigating Short-Text Degradation of Long-Context Large Language Models via Restoration Distillation.**](https://arxiv.org/abs/2502.07365) _Zican Dong, Junyi Li, Jinhao Jiang, Mingyu Xu, Wayne Xin Zhao, Bingning Wang, Weipeng Chen._ Arxiv 2025.

12. [**LongFaith: Enhancing Long-Context Reasoning in LLMs with Faithful Synthetic Data.**](https://arxiv.org/abs/2502.12583) _Cehao Yang, Xueyuan Lin, Chengjin Xu, Xuhui Jiang, Shengjie Ma, Aofan Liu, Hui Xiong, Jian Guo._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/IDEA-FinAI/LongFaith)](https://github.com/IDEA-FinAI/LongFaith)

13. [**Generalizing From Short to Long: Effective Data Synthesis for Long-Context Instruction Tuning.**](https://arxiv.org/abs/2502.15592) _Wenhao Zhu, Pinzhen Chen, Hanxu Hu, Shujian Huang, Fei Yuan, Jiajun Chen, Alexandra Birch._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NJUNLP/context-synthesis)](https://github.com/NJUNLP/context-synthesis)

14. [**LongAttn: Selecting Long-context Training Data via Token-level Attention.**](https://arxiv.org/abs/2502.16860) _Longyun Wu, Dawei Zhu, Guangxiang Zhao, Zhuocheng Yu, Junfeng Ran, Xiangyu Wong, Lin Sun, Sujian Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Lyun0912-wu/LongAttn)](https://github.com/Lyun0912-wu/LongAttn)

15. [**WildLong: Synthesizing Realistic Long-Context Instruction Data at Scale.**](https://arxiv.org/abs/2502.16684) _Jiaxi Li, Xingxing Zhang, Xun Wang, Xiaolong Huang, Li Dong, Liang Wang, Si-Qing Chen, Wei Lu, Furu Wei._ Arxiv 2025.

16. [**Pause-Tuning for Long-Context Comprehension: A Lightweight Approach to LLM Attention Recalibration.**](https://arxiv.org/abs/2502.20405) _James Begin, Namit Agrawal, Eshan Singh, Yicheng Fu, Sean O'Brien, Vasu Sharma, Kevin Zhu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LongRoPE](https://anonymous.4open.science/r/LITM-PauseTokens-7357)

17. [**LADM: Long-context Training Data Selection with Attention-based Dependency Measurement for LLMs.**](https://arxiv.org/abs/2503.02502) _Jianghao Chen, Junhong Wu, Yangyifan Xu, Jiajun Zhang._ Arxiv 2025.

18. [**Scaling Instruction-Tuned LLMs to Million-Token Contexts via Hierarchical Synthetic Data Generation.**](https://arxiv.org/abs/2504.12637) _Linda He, Jue Wang, Maurice Weber, Shang Zhu, Ben Athiwaratkun, Ce Zhang._ Arxiv 2025.

19. [**Long-Short Alignment for Effective Long-Context Modeling in LLMs.**](https://arxiv.org/abs/2506.11769) _Tianqi Du, Haotian Huang, Yifei Wang, Yisen Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/PKU-ML/LongShortAlignment)](https://github.com/PKU-ML/LongShortAlignment)

20. [**Make Your LLM Fully Utilize the Context.**](https://arxiv.org/abs/2404.16811) _Shengnan An, Zexiong Ma, Zeqi Lin, Nanning Zheng, Jian-Guang Lou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/FILM)](https://github.com/microsoft/FILM)

21. [**ACC: Compiling Agent Trajectories for Long-Context Training.**](https://arxiv.org/abs/2605.21850) _Qisheng Su, Zhen Fang, Shiting Huang, Yu Zeng, Yiming Zhao, Kou Shi, Ziao Zhang, Lin Chen, Zehui Chen, Lijun Wu, Feng Zhao._ Arxiv 2026.

22. [**LongCrafter: Towards Diverse Long-Context Understanding via Evidence-Graph-Guided Instruction Synthesis.**](https://arxiv.org/abs/2607.06160) _Chenhao Yuan, Yinhao Xu, Shuwen Xu, Xizhi Yang, Jiaxiang Liu, Chenxi Zhou, Shaoping Huang, Haolin Ren, Pengfei Cao, Jun Zhao, Kang Liu._ Arxiv 2026.

23. [**LongForge: Measuring and Improving Long-Context Instruction Data via Evidence-Assertion Reasoning Graphs.**](https://arxiv.org/abs/2610.23167) _Ziyang Chen, Junlong Jia, Xing Wu, Tinghao Yu, Songlin Hu._ Arxiv 2026.

#### 7.2 Adaptation & RL for Long Context

1. [**LongTraceRL: Learning Long-Context Reasoning from Search Agent Trajectories with Rubric Rewards.**](https://arxiv.org/abs/2605.31584) _Nianyi Lin, Jiajie Zhang, Lei Hou, Juanzi Li._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/THU-KEG/LongTraceRL)](https://github.com/THU-KEG/LongTraceRL)

2. [**Let's (not) just put things in Context: Test-Time Training for Long-Context LLMs.**](https://arxiv.org/abs/2512.13898) _Rachit Bansal, Aston Zhang, Rishabh Tiwari, Lovish Madaan, Sai Surya Duvvuri, Devvrit Khatri, David Brandfonbrener, David Alvarez-Melis, Prajjwal Bhargava, Mihir Sanjay Kale, Samy Jelassi._ Arxiv 2025.

3. [**In-Place Test-Time Training (In-Place TTT).**](https://arxiv.org/abs/2604.06169) _Guhao Feng, Shengjie Luo, Kai Hua, Ge Zhang, Di He, Wenhao Huang, Tianle Cai._ ICLR 2026 Oral. [![GitHub Repo stars](https://img.shields.io/github/stars/ByteDance-Seed/In-Place-TTT)](https://github.com/ByteDance-Seed/In-Place-TTT)

4. [**With Greater Text Comes Greater Necessity: Inference-Time Training Helps Long Text Generation.**](https://arxiv.org/abs/2401.11504) _Y. Wang, D. Ma, D. Cai._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TemporaryLoRA/Temp-LoRA)](https://github.com/TemporaryLoRA/Temp-LoRA)

5. [**LOGO -- Long cOntext aliGnment via efficient preference Optimization.**](https://arxiv.org/abs/2410.18533) _Zecheng Tang, Zechen Sun, Juntao Li, Qiaoming Zhu, Min Zhang._ [ICML 2025]. [![GitHub Repo stars](https://img.shields.io/github/stars/ZetangForward/LCM_Stack)](https://github.com/ZetangForward/LCM_Stack)

6. [**LongReward: Improving Long-context Large Language Models with AI Feedback.**](https://arxiv.org/abs/2410.21252) _Jiajie Zhang, Zhongni Hou, Xin Lv, Shulin Cao, Zhenyu Hou, Yilin Niu, Lei Hou, Yuxiao Dong, Ling Feng, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongReward)](https://github.com/THUDM/LongReward)

7. [**LongPO: Long Context Self-Evolution of Large Language Models through Short-to-Long Preference Optimization.**](https://arxiv.org/abs/2502.13922) _Guanzheng Chen, Xin Li, Michael Qizhe Shieh, Lidong Bing._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DAMO-NLP-SG/LongPO)](https://github.com/DAMO-NLP-SG/LongPO)

8. [**End-to-End Test-Time Training for Long Context.**](https://arxiv.org/abs/2512.23675) _Arnuv Tandon, Karan Dalal, Xinhao Li, Daniel Koceja, Marcel Rød, Sam Buchanan, Xiaolong Wang, Jure Leskovec, Sanmi Koyejo, Tatsunori Hashimoto, Carlos Guestrin, Jed McCaleb, Yejin Choi, Yu Sun._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/test-time-training/e2e)](https://github.com/test-time-training/e2e)

9. [**UIO-LLMs: Unbiased Incremental Optimization for Long-Context LLMs.**](https://arxiv.org/abs/2406.18173) _Wenhao Li, Mingbao Lin, Yunshan Zhong, Shuicheng Yan, Rongrong Ji._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/wenhaoli-xmu/UIO-LLMs)](https://github.com/wenhaoli-xmu/UIO-LLMs)

10. [**LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GPU Budget.**](https://arxiv.org/abs/2607.14952) _Changhai Zhou, Kieran Liu, Yuhua Zhou, Qian Qiao, Jun Gao, Harry Zhang, Irvine Lu, Nolan Ho, Lucian Li, Andrew Lei, Cleon Cheng, Steven Chiang, Yihang Zeng, Di Zhang, Rio Yang, Kaijie Chen, Andrew Chen, Pony Ma, Weizhong Zhang, Cheng Jin._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/MindLab-Research/longstraw)](https://github.com/MindLab-Research/longstraw)

11. [**Beyond Reward Engineering: A Data Recipe for Long-Context Reinforcement Learning.**](https://arxiv.org/abs/2606.18831) _Xiaoyue Xu, Sikui Zhang, Xiaorong Wang, Xu Han, Chaojun Xiao._ Arxiv 2026.

12. [**TimeRLM: Recursive Language Models Enable Precise Anomaly Localization in Long-Context Time-Series.**](https://arxiv.org/abs/2608.03391) _Nicolas Zumarraga, Lorenzo Steno, Ning Wang, Max Rosenblattl, Thomas Kaar, Maxwell A. Xu, Kevin O'Sullivan, Markus Kreft, Elgar Fleisch, Paul Schmiedmayer, Patrick Langer, Robert Jakob._ Arxiv 2026.

13. [**Learning What to Remember: Test-Time Training via Context Distillation.**](https://arxiv.org/abs/2608.01672) _Zixuan Wang, Xingyu Dang, Rui-Jie Zhu, Zixin Wen, Hengyu Fu, Wenhao Chai, Jason D. Lee._ Arxiv 2026.

14. [**EASE-TTT: Evidence-Aligned Selective Test-Time Training for Long-Context Question Answering.**](https://arxiv.org/abs/2606.06906) _Xiaopeng Yuan, Zebin Wang, Suwen Wang, Zongxin Yang, Haohan Wang, Yushun Dong._ Arxiv 2026.

15. [**LongZero: Enhancing Long-Context Reasoning in LLMs from Zero Data.**](https://arxiv.org/abs/2610.30132) _Zhennan Wan, Jianfei Chen._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/zhennan1/LongZero)](https://github.com/zhennan1/LongZero)

16. [**Chunks as Arms: Multi-Armed Bandit-Guided Sampling for Long-Context LLM Preference Optimization.**](https://arxiv.org/abs/2508.13993) _Shaohua Duan, Pengcheng Huang, Xinze Li, Zhenghao Liu, Xiaoyuan Yi, Yukun Yan, Shuo Wang, Yu Gu, Ge Yu, Maosong Sun._ ACL 2026 Oral. [![GitHub Repo stars](https://img.shields.io/github/stars/NEUIR/LongMab-PO)](https://github.com/NEUIR/LongMab-PO)

#### 7.3 Mid-Training: Data, Recipes & Scaling

1. [**Mid-Training of Large Language Models: A Survey.**](https://arxiv.org/abs/2510.06826) _Kaixiang Mo, Yuxin Shi, Weiwei Weng, Zhiqiang Zhou, Shuman Liu, Haibo Zhang, Anxiang Zeng._ Arxiv 2025.

2. [**A Survey on LLM Mid-Training.**](https://arxiv.org/abs/2510.23081) _Chengying Tu, Xuemiao Zhang, Rongxiang Weng, Rumei Li, Chen Zhang, Yang Bai, Hongfei Yan, Jingang Wang, Xunliang Cai._ Arxiv 2025.

3. [**Midtraining Bridges Pretraining and Posttraining Distributions.**](https://arxiv.org/abs/2510.14865) _Emmy Liu, Graham Neubig, Chenyan Xiong._ Arxiv 2025.

4. [**On the Interplay of Pre-Training, Mid-Training, and RL on Reasoning Language Models.**](https://arxiv.org/abs/2512.07783) _Charlie Zhang, Graham Neubig, Xiang Yue._ Arxiv 2025.

5. [**Function-Aware Fill-in-the-Middle as Mid-Training for Coding Agent Foundation Models.**](https://arxiv.org/abs/2607.12463) _Yubo Wang, Jiarong Liang, Yuxuan Zhang, Xuye Liu, Cong Wei, Yuyu Zhang, Ping Nie, Wenhu Chen._ Arxiv 2026.

6. [**Trajectory Soup: Pushing the Compute-Scaling Frontier of LLM Mid-training via Diverse Trajectories.**](https://arxiv.org/abs/2609.37169) _Zhehao Huang, Changxin Tian, Qingyuan Yang, Kunlong Chen, Ziqi Liu, Zhiqiang Zhang, Xiaolin Huang, Jun Zhou._ Arxiv 2026.

7. [**What Pretraining and Midtraining Make Learnable from Rewards?**](https://arxiv.org/abs/2609.38446) _Chiwun Yang, Xiaoyu Li._ Arxiv 2026.

8. [**TrajLong: Co-Designing Agentic and Long-Context Supervision for Mid-Training.**](https://arxiv.org/abs/2610.04973) _Miao Peng, Qintong Zhang, Nuo Chen, Yuhan Li, Guochen Yan, Xinran Gu, Hongqiu Wu, Hai Wang, Lydell Huang, Wentao Zhang, Jia Li._ Arxiv 2026.

9. [**Priming Base Models for Agentic Post-Training: An Open Midtraining Recipe.**](https://arxiv.org/abs/2610.22019) _Soumye Singhal, Joseph Jennings, Ka Shun Shum, Alexander Bukharin, Khushi Bhardwaj, Zirui Liu, Venkat Srinivasan, Jonathan Li, Yash Jain, Kezhi Kong, Markus Kliegl, Olivier Delalleau, Sanjeev Satheesh, Mostofa Patwary._ Arxiv 2026.

10. [**Data Schedules and Learning Rate Schedules Should Be Designed Together.**](https://arxiv.org/abs/2610.29348) _Haodong Wen, Kairong Luo, Tingkai Yan, Wenguang Chen, Kaifeng Lyu._ Arxiv 2026.
