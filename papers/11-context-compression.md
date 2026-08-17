# 11. Context Compression

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [11.1 Token / Prompt Compression](#111-token--prompt-compression)
  - [11.1.1 Hard Prompt & Token Pruning](#1111-hard-prompt--token-pruning)
  - [11.1.2 Soft Prompt / Gist / Latent Compression](#1112-soft-prompt--gist--latent-compression)
  - [11.1.3 Visual & Multimodal Token Compression](#1113-visual--multimodal-token-compression)
  - [11.1.4 RAG / KV-Aware Compression](#1114-rag--kv-aware-compression)
<!-- /chapter-toc -->

#### 11.1 Token / Prompt Compression

##### 11.1.1 Hard Prompt & Token Pruning

1. [**Compressing Context to Enhance Inference Efficiency of Large Language Models.**](https://arxiv.org/abs/2310.06201) _Yucheng Li, Bo Dong, Chenghua Lin, Frank Guerin._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/liyucheng09/Selective_Context)](https://github.com/liyucheng09/Selective_Context)

2. [**LLMLingua: Compressing Prompts for Accelerated Inference of Large Language Models.**](https://arxiv.org/abs/2310.05736) _Huiqiang Jiang, Qianhui Wu, Chin-Yew Lin, Yuqing Yang, Lili Qiu._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

3. [**LongLLMLingua: Accelerating and Enhancing LLMs in Long Context Scenarios via Prompt Compression.**](https://arxiv.org/abs/2310.06839) _Huiqiang Jiang, Qianhui Wu, Xufang Luo, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

4. [**Learning to Compress Prompt in Natural Language Formats.**](https://arxiv.org/abs/2402.18700) _Yu-Neng Chuang, Tianwei Xing, Chia-Yuan Chang, Zirui Liu, Xun Chen, Xia Hu._ Arxiv 2024.

5. [**LLMLingua-2: Data Distillation for Efficient and Faithful Task-Agnostic Prompt Compression.**](https://arxiv.org/abs/2403.12968) _Zhuoshi Pan, Qianhui Wu, Huiqiang Jiang, Menglin Xia, Xufang Luo, Jue Zhang, Qingwei Lin, Victor Rühle, Yuqing Yang, Chin-Yew Lin, H. Vicky Zhao, Lili Qiu, Dongmei Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

6. [**PCToolkit: A Unified Plug-and-Play Prompt Compression Toolkit of Large Language Models.**](https://arxiv.org/abs/2403.17411) _Jinyi Li, Yihuai Lan, Lei Wang, Hao Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/3DAgentWorld/Toolkit-for-Prompt-Compression)](https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression)

7. [**PROMPT-SAW: Leveraging Relation-Aware Graphs for Textual Prompt Compression.**](https://arxiv.org/abs/2404.00489) _Muhammad Asif Ali, Zhengping Li, Shu Yang, Keyuan Cheng, Yang Cao, Tianhao Huang, Lijie Hu, Lu Yu, Di Wang._ Arxiv 2024.

8. [**InstructCMP: Length Control in Sentence Compression through Instruction-based Large Language Models.**](https://arxiv.org/abs/2406.11097) _Juseon-Do, Jingun Kwon, Hidetaka Kamigaito, Manabu Okumura._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JuseonDo/InstructCMP)](https://github.com/JuseonDo/InstructCMP)

9. [**Characterizing Prompt Compression Methods for Long Context Inference.**](https://arxiv.org/abs/2407.08892) _Siddharth Jha, Lutfi Eren Erdogan, Sehoon Kim, Kurt Keutzer, Amir Gholami._ Arxiv 2024.

10. [**Fundamental Limits of Prompt Compression: A Rate-Distortion Framework for Black-Box Language Models.**](https://arxiv.org/abs/2407.15504) _Adway Girish, Alliot Nagle, Marco Bondaschi, Michael Gastpar, Ashok Vardhan Makkuva, Hyeji Kim._ Arxiv 2024.

11. [**QUITO: Accelerating Long-Context Reasoning through Query-Guided Context Compression.**](https://arxiv.org/abs/2408.00274) _Wenshan Wang, Yihang Wang, Yixing Fan, Huaming Liao, Jiafeng Guo._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Wenshansilvia/attention_compressor)](https://github.com/Wenshansilvia/attention_compressor)

12. [**QUITO-X: An Information Bottleneck-based Compression Algorithm with Cross-Attention.**](https://arxiv.org/abs/2408.10497) _Yihang Wang, Xu Huang, Bowen Tian, Yixing Fan, Jiafeng Guo._ Arxiv 2024.

13. [**Prompt Compression with Context-Aware Sentence Encoding for Fast and Improved LLM Inference.**](https://arxiv.org/abs/2409.01227) _Barys Liskavets, Maxim Ushakov, Shuvendu Roy, Mark Klibanov, Ali Etemad, Shane Luke._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Workday/cpc)](https://github.com/Workday/cpc)

14. [**TACO-RL: Task Aware Prompt Compression Optimization with Reinforcement Learning.**](https://arxiv.org/abs/2409.13035) _Shivam Shandilya, Menglin Xia, Supriyo Ghosh, Huiqiang Jiang, Jue Zhang, Qianhui Wu, Victor Rühle._ Arxiv 2024.

15. [**Parse Trees Guided LLM Prompt Compression.**](https://arxiv.org/abs/2409.15395) _Wenhao Mao, Chengbin Hou, Tianyu Zhang, Xinyu Lin, Ke Tang, Hairong Lv._ Arxiv 2024.

16. [**Perception Compressor:A training-free prompt compression method in long context scenarios.**](https://arxiv.org/abs/2409.19272) _Jiwei Tang, Jin Xu, Tingwei Lu, Hai Lin, Yiming Zhao, Hai-Tao Zheng._ Arxiv 2024.

17. [**From Reading to Compressing: Exploring the Multi-document Reader for Prompt Compression.**](https://arxiv.org/abs/2410.04139) _Eunseong Choi, Sunkyung Lee, Minjin Choi, June Park, Jongwuk Lee._ EMNLP 2024.

18. [**Selection-p: Self-Supervised Task-Agnostic Prompt Compression for Faithfulness and Transferability.**](https://arxiv.org/abs/2410.11786) _Tsz Ting Chung, Leyang Cui, Lemao Liu, Xinting Huang, Shuming Shi, Dit-Yan Yeung._ EMNLP 2024.

19. [**Style-Compress: An LLM-Based Prompt Compression Framework Considering Task-Specific Styles.**](https://arxiv.org/abs/2410.14042) _Xiao Pu, Tianxing He, Xiaojun Wan._ EMNLP 2024.

20. [**FTP: A Fine-grained Token-wise Pruner for Large Language Models via Token Routing.**](https://arxiv.org/abs/2412.11494) _Zekai Li, Jintu Zheng, Ji Liu, Han Liu, Haowei Zhu, Zeping Li, Fuwei Yang, Haiduo Huang, Jinzhang Peng, Dong Li, Lu Tian, Emad Barsoum._ Arxiv 2024.

21. [**Efficient Prompt Compression with Evaluator Heads for Long-Context Transformer Inference.**](https://arxiv.org/abs/2501.12959) _Weizhi Fei, Xueyan Niu, Guoqing Xie, Yingqing Liu, Bo Bai, Wei Han._ Arxiv 2025.

22. [**Knowing When to Stop: Dynamic Context Cutoff for Large Language Models.**](https://arxiv.org/abs/2502.01025) _Roy Xie, Junlin Wang, Paul Rosu, Chunyuan Deng, Bolun Sun, Zihao Lin, Bhuwan Dhingra._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ruoyuxie/when-to-stop)](https://github.com/ruoyuxie/when-to-stop)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://royxie.com/when-to-stop-project/)

23. [**EFPC: Towards Efficient and Flexible Prompt Compression.**](https://arxiv.org/abs/2503.07956) _Yun-Hao Cao, Yangsong Wang, Shuzheng Hao, Zhenxing Li, Chengjun Zhan, Sichao Liu, Yi-Qi Hu._ Arxiv 2025.

24. [**Understanding and Improving Information Preservation in Prompt Compression for LLMs.**](https://arxiv.org/abs/2503.19114) _Weronika Łajewska, Momchil Hardalov, Laura Aina, Neha Anna John, Hang Su, Lluís Màrquezu._ Arxiv 2025.

25. [**Saliency-driven Dynamic Token Pruning for Large Language Models.**](https://arxiv.org/abs/2504.04514) _Yao Tao, Yehui Tang, Yun Wang, Mingjian Zhu, Hailin Hu, Yunhe Wang._ Arxiv 2025.

26. [**Dynamic Compressing Prompts for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2504.11004) _Jinwu Hu, Wei Zhang, Yufeng Wang, Yu Hu, Bin Xiao, Mingkui Tan, Qing Du._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Fhujinwu/DCP)](https://github.com/Fhujinwu/DCP)

27. [**MOOSComp: Improving Lightweight Long-Context Compressor via Mitigating Over-Smoothing and Incorporating Outlier Scores.**](https://arxiv.org/abs/2504.16786) _Fengwei Zhou, Jiafei Song, Wenjin Jason Li, Gengjian Xue, Zhikang Zhao, Yichao Lu, Bailin Na._ Arxiv 2025.

28. [**An Empirical Study on Prompt Compression for Large Language Models.**](https://arxiv.org/abs/2505.00019) _Zheng Zhang, Jinyi Li, Yihuai Lan, Xiang Wang, Hao Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/3DAgentWorld/Toolkit-for-Prompt-Compression)](https://github.com/3DAgentWorld/Toolkit-for-Prompt-Compression)

29. [**Beyond Hard and Soft: Hybrid Context Compression for Balancing Local and Global Information Retention.**](https://arxiv.org/abs/2505.15774) _Huanxuan Liao, Wen Hu, Yao Xu, Shizhu He, Jun Zhao, Kang Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/HyCo2)](https://github.com/Xnhyacinth/HyCo2)

30. [**QwenLong-CPRS: Towards ∞-LLMs with Dynamic Context Optimization.**](https://arxiv.org/abs/2505.18092) _Weizhou Shen, Chenliang Li, Fanqi Wan, Shengyi Liao, Shaopeng Lai, Bo Zhang, Yingcheng Shi, Yuning Wu, Gang Fu, Zhansheng Li, Bin Yang, Ji Zhang, Fei Huang, Jingren Zhou, Ming Yan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongyi-Zhiwen/QwenLong-CPRS)](https://github.com/Tongyi-Zhiwen/QwenLong-CPRS)

31. [**Sentinel: Attention Probing of Proxy Models for LLM Context Compression with an Understanding Perspective.**](https://arxiv.org/abs/2505.23277) _Yong Zhang, Yanwen Huang, Ning Cheng, Yang Guo, Yun Zhu, Yanmeng Wang, Shaojun Wang, Jing Xiao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/yzhangchuck/Sentinel)](https://github.com/yzhangchuck/Sentinel)

32. [**SecurityLingua: Efficient Defense of LLM Jailbreak Attacks via Security-Aware Prompt Compression.**](https://arxiv.org/abs/2506.12707) _Yucheng Li, Surin Ahn, Huiqiang Jiang, Amir H. Abdi, Yuqing Yang, Lili Qiu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LLMLingua)](https://github.com/microsoft/LLMLingua)

33. [**DAC: A Dynamic Attention-aware Approach for Task-Agnostic Prompt Compression.**](https://arxiv.org/abs/2507.11942) _Yi Zhao, Zuchao Li, Hai Zhao, Baoyuan Qi, Guoming Liu._ ACL 2025.

34. [**ProCut: LLM Prompt Compression via Attribution Estimation.**](https://arxiv.org/abs/2508.02053) _Zhentao Xu, Fengyi Li, Albert Chen, Xiaofeng Wang._ Arxiv 2025.

35. [**DSPC: Dual-Stage Progressive Compression Framework for Efficient Long-Context Reasoning.**](https://arxiv.org/abs/2509.13723) _Yaxin Gao, Yao Lu, Zongfei Zhang, Jiaqi Nie, Shanqing Yu, Qi Xuan._ Arxiv 2025.

36. [**LongCodeZip: Compress Long Context for Code Language Models.**](https://arxiv.org/abs/2510.00446) _Yuling Shi, Yichun Qian, Hongyu Zhang, Beijun Shen, Xiaodong Gu._ ASE 2025.
[![GitHub Repo stars](https://img.shields.io/github/stars/YerbaPage/LongCodeZip)](https://github.com/YerbaPage/LongCodeZip)

37. [**Context Cascade Compression: Exploring the Upper Limits of Text Compression.**](https://arxiv.org/abs/2511.15244) _Fanfan Liu, Haibo Qiu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/liufanfanlff/C3-Context-Cascade-Compression)](https://github.com/liufanfanlff/C3-Context-Cascade-Compression)

38. [**FineZip: Pushing the Limits of Large Language Models for Practical Lossless Text Compression.**](https://arxiv.org/abs/2409.17141) _Fazal Mittu, Yihuan Bu, Akshat Gupta, Ashok Devireddy, Alp Eren Ozdarendeli, Anant Singh, Gopala Anumanchipalli._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/fazalmittu/FineZip)](https://github.com/fazalmittu/FineZip)

39. [**Training-Free Long-Context Scaling of Large Language Models.**](https://arxiv.org/abs/2402.17463) _Chenxin An, Fei Huang, Jun Zhang, Shansan Gong, Xipeng Qiu, Chang Zhou, Lingpeng Kong._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HKUNLP/ChunkLlama)](https://github.com/HKUNLP/ChunkLlama)

40. [**ILRe: Intermediate Layer Retrieval for Context Compression in Causal Language Models.**](https://arxiv.org/abs/2508.17892) _Manlai Liang, Mandi Liu, Jiangzhou Ji, Huaijun Li, Haobo Yang, Yaohan He, Jinlong Li._ Arxiv 2025.

41. [**Prompts As Programs: A Structure-Aware Approach to Efficient Compile-Time Prompt Optimization.**](https://arxiv.org/abs/2404.02319) _Tobias Schnabel, Jennifer Neville._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/sammo)](https://github.com/microsoft/sammo)

42. [**ZipRL: Adaptive Multi-Turn Context Compression with Hindsight Response Replay.**](https://arxiv.org/abs/2605.28069) _Zhexin Hu, Li Wang, Xiaohan Wang, Jiajun Chai, Xiaojun Guo, Wei Lin, Guojun Yin._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/huzhexin/ZipRL)](https://github.com/huzhexin/ZipRL)

43. [**LongAttnComp: Cross-Family Context Compression for Long-Context Reasoning.**](https://arxiv.org/abs/2606.01336) _et al.._ Arxiv 2026.

44. [**Relevant but Incomplete: Referential Dangling as a Paradigm-Level Failure Mode in Hard Prompt Compression.**](https://arxiv.org/abs/2608.04569) _Zhengpei Hu, Kai Li, Dapeng Fu, Xuechao Zou, Yuanhao Tang, Yue Li, Tengfei Cao, Jianqiang Huang._ Arxiv 2026.

45. [**Every Time I Hire a Linguist, Inference Costs Go Down: On Linguistic Rules as Effective Prompt Compressors.**](https://arxiv.org/abs/2607.25335) _Jianfei Ma, Zhaoxin Feng, Emmanuele Chersoni, Si Chen._ Arxiv 2026.

46. [**SALT: Salience-Aware Lexical Trie for Long-Context Compression.**](https://arxiv.org/abs/2607.17486) _Oteo Mamo, Hyunjin Yi, Joydhriti Choudhury, Shangqian Gao, Weikuan Yu._ Arxiv 2026.

47. [**PReM: Learning What to Preserve and When to Refresh for Context Compression.**](https://arxiv.org/abs/2607.14327) _Bohan Yu, Lei Shen, Chenxi Zhou, Chen Han, Junlin Liu, Wenbo Su, Yu Cheng, Bo Zheng._ Arxiv 2026.

48. [**Context Compression Is Not One Thing: Readable Symbolic Re-expression vs. Coherent Summary at Matched Budget.**](https://arxiv.org/abs/2606.14875) _Sisong Bei, Mikhail L. Arbuzov, Ziwei Dong, Dmitri Kalaev, Alexey Shvets._ Arxiv 2026.

##### 11.1.2 Soft Prompt / Gist / Latent Compression

1. [**Adapting Language Models to Compress Contexts.**](https://arxiv.org/abs/2305.14788) _Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/AutoCompressors)](https://github.com/princeton-nlp/AutoCompressors)

2. [**Say More with Less: Understanding Prompt Learning Behaviors through Gist Compression.**](https://arxiv.org/abs/2402.16058) _Xinze Li, Zhenghao Liu, Chenyan Xiong, Shi Yu, Yukun Yan, Shuo Wang, Ge Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenMatch/Gist-COCO)](https://github.com/OpenMatch/Gist-COCO)

3. [**Compressed Context Memory for Online Language Model Interaction.**](https://arxiv.org/abs/2312.03414) _Jang-Hyun Kim, Junyoung Yeom, Sangdoo Yun, Hyun Oh Song._ ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/snu-mllab/context-memory)](https://github.com/snu-mllab/context-memory)

4. [**Training LLMs over Neurally Compressed Text.**](https://arxiv.org/abs/2404.03626) _Brian Lester, Jaehoon Lee, Alex Alemi, Jeffrey Pennington, Adam Roberts, Jascha Sohl-Dickstein, Noah Constant._ Arxiv 2024.

5. [**Adapting LLMs for Efficient Context Processing through Soft Prompt Compression.**](https://arxiv.org/abs/2404.04997) _Cangqing Wang, Yutian Yang, Ruisi Li, Dan Sun, Ruicong Cai, Yuzhu Zhang, Chengqian Fu, Lillian Floyd._ Arxiv 2024.

6. [**LLoCO: Learning Long Contexts Offline.**](https://arxiv.org/abs/2404.07979) _Sijun Tan, Xiuyu Li, Shishir Patil, Ziyang Wu, Tianjun Zhang, Kurt Keutzer, Joseph E. Gonzalez, Raluca Ada Popa._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/jeffreysijuntan/lloco)](https://github.com/jeffreysijuntan/lloco)

7. [**SelfCP: Compressing Long Prompt to 1/12 Using the Frozen Large Language Model Itself.**](https://arxiv.org/abs/2405.17052) _Jun Gao._ Arxiv 2024.

8. [**Compressing Lengthy Context With UltraGist.**](https://arxiv.org/abs/2405.16635) _Peitian Zhang, Zheng Liu, Shitao Xiao, Ninglu Shao, Qiwei Ye, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/namespace-Pt/UltraGist)](https://github.com/namespace-Pt/UltraGist)

9. [**In-context Autoencoder for Context Compression in a Large Language Model.**](https://openreview.net/forum?id=uREj4ZuGJE) _Tao Ge, Hu Jing, Lei Wang, Xun Wang, Si-Qing Chen, Furu Wei._ ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/getao/icae)](https://github.com/getao/icae)

10. [**Retaining Key Information under High Compression Ratios: Query-Guided Compressor for LLMs.**](https://arxiv.org/abs/2406.02376) _Zhiwei Cao, Qian Cao, Yu Lu, Ningxin Peng, Luyang Huang, Shanbo Cheng, Jinsong Su._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DeepLearnXMU/QGC)](https://github.com/DeepLearnXMU/QGC)

11. [**Recurrent Context Compression: Efficiently Expanding the Context Window of LLM.**](https://arxiv.org/abs/2406.06110) _Chensen Huang, Guibo Zhu, Xuepeng Wang, Yifei Luo, Guojing Ge, Haoran Chen, Dong Yi, Jinqiao Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WUHU-G/RCC_Transformer)](https://github.com/WUHU-G/RCC_Transformer)

12. [**LoCoCo: Dropping In Convolutions for Long Context Compression.**](https://arxiv.org/abs/2406.05317) _Ruisi Cai, Yuandong Tian, Zhangyang Wang, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/LoCoCo)](https://github.com/VITA-Group/LoCoCo)

13. [**In-Context Former: Lightning-fast Compressing Context for Large Language Model.**](https://arxiv.org/abs/2406.13618) _Xiangfeng Wang, Zaiyi Chen, Zheyong Xie, Tong Xu, Yongyi He, Enhong Chen._ Arxiv 2024.

14. [**PromptIntern: Saving Inference Costs by Internalizing Recurrent Prompt during Large Language Model Fine-tuning.**](https://arxiv.org/abs/2407.02211) _Jiaru Zou, Mengyu Zhou, Tao Li, Shi Han, Dongmei Zhang._ Arxiv 2024.

15. [**Concise and Precise Context Compression for Tool-Using Language Models.**](https://arxiv.org/abs/2407.02043) _Yang Xu, Yunlong Feng, Honglin Mu, Yutai Hou, Yitong Li, Xinghao Wang, Wanjun Zhong, Zhongyang Li, Dandan Tu, Qingfu Zhu, Min Zhang, Wanxiang Che._ Arxiv 2024.

16. [**A Silver Bullet or a Compromise for Full Attention? A Comprehensive Study of Gist Token-based Context Compression.**](https://arxiv.org/abs/2412.17483) _Chenlong Deng, Zhisong Zhang, Kelong Mao, Shuaiyi Li, Xinting Huang, Dong Yu, Zhicheng Dou._ Arxiv 2024.

17. [**LCIRC: A Recurrent Compression Approach for Efficient Long-form Context and Query Dependent Modeling in LLMs.**](https://arxiv.org/abs/2502.06139) _Sumin An, Junyoung Sung, Wonpyo Park, Chanjun Park, Paul Hongsuck Seo._ NAACL 2025.

18. [**DAST: Context-Aware Compression in LLMs via Dynamic Allocation of Soft Tokens.**](https://arxiv.org/abs/2502.11493) _Shaoshen Chen, Yangning Li, Zishan Xu, Yinghui Li, Xin Su, Zifei Shan, Hai-tao Zheng._ Arxiv 2025.

19. [**Cramming 1568 Tokens into a Single Vector and Back Again: Exploring the Limits of Embedding Space Capacity.**](https://arxiv.org/abs/2502.13063) _Yuri Kuratov, Mikhail Arkhipov, Aydar Bulatov, Mikhail Burtsev._ Arxiv 2025.

20. [**Lossless Token Sequence Compression via Meta-Tokens.**](https://arxiv.org/abs/2506.00307) _John Harvill, Ziwei Fan, Hao Wang, Yizhou Sun, Hao Ding, Luke Huan, Anoop Deoras._ Arxiv 2025.

21. [**Simple Context Compression: Mean-Pooling and Multi-Ratio Training.**](https://arxiv.org/abs/2510.20797) _Yair Feldman, Yoav Artzi._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lil-lab/simple-context-compression)](https://github.com/lil-lab/simple-context-compression)

22. [**Large Language Model as Token Compressor and Decompressor.**](https://arxiv.org/abs/2603.25340) _Wenbing Li, Zikai Song, Jielei Zhang, Tianhao Zhao, Junkai Lin, Yiran Wang, Wei Yang._ Arxiv 2026.

23. [**Density-aware Soft Context Compression with Semi-Dynamic Compression Ratio.**](https://arxiv.org/abs/2603.25926) _Yijiong Yu, Shuai Yuan, Jie Zheng, Huazheng Wang, Ji Pei._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/yuyijiong/semi-dynamic-context-compress)](https://github.com/yuyijiong/semi-dynamic-context-compress)

24. [**Latent Context Compilation: Distilling Long Context into Compact Portable Memory.**](https://arxiv.org/abs/2602.21221) _Zeju Li, Yizhou Zhou, Qiang Xu._ Arxiv 2026.

25. [**Adaptive Multi-Resolution Procedural Knowledge Compression for Large Language Models.**](https://arxiv.org/abs/2606.12203) _Changyue Wang, Weihang Su, Qingyao Ai, Yichen Tang, Runzhong Qiao, Xuancheng Li, Min Zhang, Yiqun Liu._ Arxiv 2026.

26. [**End-to-End Context Compression at Scale.**](https://arxiv.org/abs/2606.09659) _Ang Li, Sean McLeish, Haozhe Chen, Nimit Kalra, Zaiqian Chen, Artem Gazizov, Venkata Anoop Suhas Kumar Morisetty, Bhavya Kailkhura, Harshitha Menon, Zhuang Liu, Brian R. Bartoldson, Tom Goldstein, Sanae Lotfi, Micah Goldblum, Pavel Izmailov._ Arxiv 2026.

27. [**The Sleeping Agent: What Gist-Based Context Compression Loses and Why.**](https://arxiv.org/abs/2608.11775) _Nicholas E. Kyrkewood._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/kyrkewood/sleeping-agent)](https://github.com/kyrkewood/sleeping-agent)

##### 11.1.3 Visual & Multimodal Token Compression

1. [**AgentOCR: Reimagining Agent History via Optical Self-Compression.**](https://arxiv.org/abs/2601.04786) _Lang Feng, Fuchao Yang, Feng Chen, Xin Cheng, Haiyang Xu, Zhenglin Wan, Ming Yan, Bo An._ Arxiv 2026.

2. [**SpeechPrune: Context-aware Token Pruning for Speech Information Retrieval.**](https://arxiv.org/abs/2412.12009) _Yueqian Lin, Yuzhe Fu, Jingyang Zhang, Yudong Liu, Jianyi Zhang, Jingwei Sun, Hai "Helen" Li, Yiran Chen._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://speechprune.github.io/)

3. [**Layer- and Timestep-Adaptive Differentiable Token Compression Ratios for Efficient Diffusion Transformers.**](https://arxiv.org/abs/2412.16822) _Haoran You, Connelly Barnes, Yuqian Zhou, Yan Kang, Zhenbang Du, Wei Zhou, Lingzhi Zhang, Yotam Nitzan, Xiaoyang Liu, Zhe Lin, Eli Shechtman, Sohrab Amirghodsi, Yingyan Celine Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/GATECH-EIC/DiffRatio-MoD)](https://github.com/GATECH-EIC/DiffRatio-MoD)

4. [**ETC: Extreme Token Compression via Task-aware Visual Information Distillation in VLMs.**](https://arxiv.org/abs/2606.00543) _Yiling Gao, Hongchen Wei, Zhenzhong Chen._ Arxiv 2026.

5. [**RESTORE: Improving Visual Token Reduction via Rectifying Distortions for Efficient Multimodal LLM Inference.**](https://arxiv.org/abs/2606.01711) _Hyeonwoo Cho, DongHyeon Baek, Yewon Kim, Bumsub Ham._ ICML 2026.

6. [**Token Pruning in Multimodal Large Language Models: Are We Solving the Right Problem?.**](https://arxiv.org/abs/2502.11501) _Zichen Wen, Yifeng Gao, Weijia Li, Conghui He, Linfeng Zhang._ Arxiv 2025.

7. [**FCoT-VL: Advancing Text-oriented Large Vision-Language Models with Efficient Visual Token Compression.**](https://arxiv.org/abs/2502.18512) _Jianjian Li, Junquan Fan, Feng Tang, Gang Huang, Shitao Zhu, Songlin Liu, Nian Xie, Wulong Liu, Yong Liao._ Arxiv 2025.

8. [**DivPrune: Diversity-based Visual Token Pruning for Large Multimodal Models.**](https://arxiv.org/abs/2503.02175) _Saeed Ranjbar Alvar, Gursimran Singh, Mohammad Akbari, Yong Zhang._ Arxiv 2025.

9. [**Hybrid-Level Instruction Injection for Video Token Compression in Multi-modal Large Language Models.**](https://arxiv.org/abs/2503.16036) _Zhihang Liu, Chen-Wei Xie, Pandeng Li, Liming Zhao, Longxiang Tang, Yun Zheng, Chuanbin Liu, Hongtao Xie._ CVPR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lntzm/HICom)](https://github.com/lntzm/HICom)

10. [**Token Dynamics: Towards Efficient and Dynamic Video Token Representation for Video Large Language Models.**](https://arxiv.org/abs/2503.16980) _Haichao Zhang, Zhuowei Li, Dimitris Metaxas, Yun Fu._ Arxiv 2025.

11. [**Fwd2Bot: LVLM Visual Token Compression with Double Forward Bottleneck.**](https://arxiv.org/abs/2503.21757) _Adrian Bulat, Yassine Ouali, Georgios Tzimiropoulos._ Arxiv 2025.

12. [**Token Sequence Compression for Efficient Multimodal Computing.**](https://arxiv.org/abs/2504.17892) _Yasmine Omri, Parth Shroff, Thierry Tambe._ Arxiv 2025.

13. [**Video Compression Commander: Plug-and-Play Inference Acceleration for Video Large Language Models.**](https://arxiv.org/abs/2505.14454) _Xuyang Liu, Yiyu Wang, Junpeng Ma, Linfeng Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/xuyang-liu16/VidCom2)](https://github.com/xuyang-liu16/VidCom2)

14. [**METok: Multi-Stage Event-based Token Compression for Efficient Long Video Understanding.**](https://arxiv.org/abs/2506.02850) _Mengyue Wang, Shuo Chen, Kristian Kersting, Volker Tresp, Yunpu Ma._ Arxiv 2025.

15. [**DeepSeek-OCR: Contexts Optical Compression.**](https://arxiv.org/abs/2510.18234) _Haoran Wei, Yaofeng Sun, Yukun Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-OCR)](https://github.com/deepseek-ai/DeepSeek-OCR)

16. [**See the Text: From Tokenization to Visual Reading.**](https://arxiv.org/abs/2510.18840) _Ling Xing, Alex Jinpeng Wang, Rui Yan, Hongyu Qu, Zechao Li, Jinhui Tang._ Arxiv 2025.

17. [**Visual Text Compression as Measure Transport.**](https://arxiv.org/abs/2605.06708) _Lv Tang, Tianyi Zheng, Yang Liu, Bo Li, Xingyu Li._ Arxiv 2026.

18. [**Look Less, Reason More: Block-wise Attention Skipping for Efficient Multimodal LLMs.**](https://arxiv.org/abs/2606.08511) _Jie Ma, Zhike Qiu, Jiayi Ji, Xiaoshuai Sun, Rongrong Ji._ Arxiv 2026.

19. [**VisCo: Leveraging Large Language Models as Intrinsic Encoders for Visual Token Compression.**](https://arxiv.org/abs/2607.12756) _Yupeng Zheng, Kai Zou, Bin Liu, Nenghai Yu._ Arxiv 2026.

20. [**AnchorPrune: Relevance-Anchored Contextual Expansion for Visual Token Pruning.**](https://arxiv.org/abs/2607.07033) _Kyuan Oh, Bumsoo Kim._ Arxiv 2026.

21. [**LASER: A Corrective Lens for LVLMs via Visual Attention Preservation and Sink Suppression.**](https://arxiv.org/abs/2607.01707) _Bowen Yuan, Zijian Wang, Yadan Luo, Shijie Wang, Zi Huang._ Arxiv 2026.

22. [**Do All Visual Tokens Matter Equally? Object-Evidence Preserving Token Merging for Vision-Language Retrieval.**](https://arxiv.org/abs/2607.04605) _Suhyeong Park, Junha Jung, Jungwoo Park, Jaewoo Kang._ Arxiv 2026.

23. [**CoverPrune: Coverage-Driven Token Pruning for 3D VLMs via Optimal Transport.**](https://arxiv.org/abs/2608.13226) _Peng Ling, Yingda Yin, Lingting Zhu, Weikai Chen, Shengju Qian, Zeyu Hu, Xin Wang, Wenming Yang._ ECCV 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/Brucess/CoverPrune)](https://github.com/Brucess/CoverPrune)

24. [**When Vision Becomes Text: Visual Token Pruning via Cross-Modal Residual Guidance in VLMs.**](https://arxiv.org/abs/2608.10489) _Congyang Ou, Ruike Song, Yang Zhou, Libo Sun, Haokui Zhang, Zhenbo Luo._ Arxiv 2026.

25. [**Not All Visual Tokens Are Equally Safe to Remove:Consequence-Sensitive Visual Token Compression.**](https://arxiv.org/abs/2608.09176) _Jingbo Wen, Liang He, Mingyu Cao, Haoyu Wang, Minxuan Hu, Kangning Cui, Xilu Wang._ Arxiv 2026.

26. [**RoRA: Role-Oriented Regional Allocation for Visual Token Pruning in MLLMs.**](https://arxiv.org/abs/2608.07088) _Qiyanhui Lu, Han Wu, Rongjian Xu, Tingzhang Luo, Cheng Fan, Xinghao Chen, Minjing Dong, Jufeng Yang, Jianyuan Guo._ Arxiv 2026.

27. [**An AI4AI Framework for Visual Token Pruning.**](https://arxiv.org/abs/2608.07193) _Zhen Liu, Wenli Huang, Wei Song, Yuhan Liu, Zhiqin Yang, Jingwen Fu._ Arxiv 2026.

28. [**Not All Redundant Tokens Are Alike: Analyzing Visual Token Pruning through Token Roles.**](https://arxiv.org/abs/2608.04483) _Hyeonyu Kim, Sehwan Lim, Youngwon Choi, Taeyoun Kwon, Jaejin Kim._ ECCV 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/jaykim9870/Not_All_Redundant_Tokens_Are_Alike)](https://github.com/jaykim9870/Not_All_Redundant_Tokens_Are_Alike)

29. [**RUTA: Principled Visual Token Allocation via Rate-Utility Optimization.**](https://arxiv.org/abs/2608.04132) _Jian Zou, Xiaoyu Xu, Zhihua Wang, Yilin Wang, Balu Adsumilli, Kede Ma._ Arxiv 2026.

30. [**When Do Fewer Visual Tokens Accelerate Multimodal Inference? A Break-Even Study Across Decision Locations and Hardware.**](https://arxiv.org/abs/2608.03649) _Hao Dou, Ruiwen Tian._ Arxiv 2026.

31. [**Learning to Predict Middle-Layer Attention in MLLMs for Visual Token Prunin.**](https://arxiv.org/abs/2608.06411) _Yuyao Sun, Tao Deng, Shuang Li, Deqing Wang, Hao Geng, Minjun Yu._ Arxiv 2026.

32. [**Decoupling semantics from vision: A framework for faithful visual-text compression evaluation.**](https://arxiv.org/abs/2608.01848) _Yonghan Gao, Zehong Chen, Lijian Xu, Jingzhi Chen, Jingwei Guan, Xingyu Zeng._ Arxiv 2026.

33. [**DiffPrune: differentiable information throttling for token pruning in vision-language models.**](https://arxiv.org/abs/2608.01985) _Landi He, Mingde Yao, Shawn Young, Lijian Xu._ Arxiv 2026.

34. [**ET-Prune: Evidence-Aware Dynamic Budgeting for Visual Token Pruning in Text-Rich MLLMs.**](https://arxiv.org/abs/2608.01979) _Zizhong Ding, Junxian Li, Kai Liu, Shaoqiu Zhang, Xiao Xiao, Linghe Kong, Yulun Zhang._ Arxiv 2026.

35. [**LAST: The Last Query Token Guides Visual Token Pruning for Edge-Cloud Collaborative MLLM Inference.**](https://arxiv.org/abs/2607.27952) _Feng Yang, Xinrui Ju, Keyang Zhang, Xiandong Meng, Rongqun Lin, Howard Leung, Shiqi Wang, Haoliang Li, Chris Xing Tian._ Arxiv 2026.

36. [**Calibrate Before Reason: Robust Visual Token Reduction against Semantic Drift in VLMs.**](https://arxiv.org/abs/2607.27700) _Jiasheng Li, Zhong Ji, Yan Zhang, Huihui Li._ Arxiv 2026.

37. [**Omni-Prune: Query-Aware Unified Token Pruning for Efficient Omnimodal Large Language Models.**](https://arxiv.org/abs/2607.23445) _Yiming Zhong, Chang Nie, Caifeng Shan._ Arxiv 2026.

38. [**Structured Redundancy Modeling for Efficient Visual Token Pruning in High-Resolution MLLMs.**](https://arxiv.org/abs/2607.23046) _Jouwon Song, Woohyeong Kim, Kyeongbo Kong._ ECCV 2026.

39. [**CRISP: Pre-LLM Yet Text-Driven Visual Token Pruning for Efficient LVLM Inference.**](https://arxiv.org/abs/2607.16326) _Xu Li, Yi Zheng, Mengyang Zhao, Yuxuan Liang, Zhe Liu, Rui Zhu, Xiaolei Chen, Wei Zhou, Baoquan Zhao, Juncen Guo._ Arxiv 2026.

##### 11.1.4 RAG / KV-Aware Compression

1. [**Compressing Long Context for Enhancing RAG with AMR-based Concept Distillation.**](https://arxiv.org/abs/2405.03085) _Kaize Shi, Xueyao Sun, Qing Li, Guandong Xu._ Arxiv 2024.

2. [**Improving Long Text Understanding with Knowledge Distilled from Summarization Model.**](https://arxiv.org/abs/2405.04955) _Yan Liu, Yazheng Yang, Xiaokang Chen._ Arxiv 2024.

3. [**xRAG: Extreme Context Compression for Retrieval-augmented Generation with One Token.**](https://arxiv.org/abs/2405.13792) _Xin Cheng, Xun Wang, Xingxing Zhang, Tao Ge, Si-Qing Chen, Furu Wei, Huishuai Zhang, Dongyan Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Hannibal046/xRAG)](https://github.com/Hannibal046/xRAG)

4. [**Context Embeddings for Efficient Answer Generation in RAG.**](https://arxiv.org/abs/2407.09252) _David Rau, Shuai Wang, Hervé Déjean, Stéphane Clinchant._ Arxiv 2024.

5. [**AdaComp: Extractive Context Compression with Adaptive Predictor for Retrieval-Augmented Large Language Models.**](https://arxiv.org/abs/2409.01579) _Qianchi Zhang, Hainan Zhang, Liang Pang, Hongwei Zheng, Zhiming Zheng._ Arxiv 2024.

6. [**Familiarity-aware Evidence Compression for Retrieval Augmented Generation.**](https://arxiv.org/abs/2409.12468) _Dongwon Jung, Qin Liu, Tenghao Huang, Ben Zhou, Muhao Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/luka-group/FaviComp)](https://github.com/luka-group/FaviComp)

7. [**EXIT: Context-Aware Extractive Compression for Enhancing Retrieval-Augmented Generation.**](https://arxiv.org/abs/2412.12559) _Taeho Hwang, Sukmin Cho, Soyeong Jeong, Hoyun Song, SeungYoon Han, Jong C. Park._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ThisIsHwang/EXIT)](https://github.com/ThisIsHwang/EXIT)

8. [**PISCO: Pretty Simple Compression for Retrieval-Augmented Generation.**](https://arxiv.org/abs/2501.16075) _Maxime Louis, Hervé Déjean, Stéphane Clinchant._ Arxiv 2025.

9. [**Provence: efficient and robust context pruning for retrieval-augmented generation.**](https://arxiv.org/abs/2501.16214) _Nadezhda Chirkova, Thibault Formal, Vassilina Nikoulina, Stéphane Clinchant._ ICLR 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/naver/provence-reranker-debertav3-v1)

10. [**AttentionRAG: Attention-Guided Context Pruning in Retrieval-Augmented Generation.**](https://arxiv.org/abs/2503.10720) _Yixiong Fang, Tianran Sun, Yuling Shi, Xiaodong Gu._ Arxiv 2025.

11. [**Efficient Dynamic Clustering-Based Document Compression for Retrieval-Augmented-Generation.**](https://arxiv.org/abs/2504.03165) _Weitao Li, Kaiming Liu, Xiangyu Zhang, Xuanyu Lei, Weizhi Ma, Yang Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tsinghua-dhy/EDC-2-RAG)](https://github.com/Tsinghua-dhy/EDC-2-RAG)

12. [**ACoRN: Noise-Robust Abstractive Compression in Retrieval-Augmented Language Models.**](https://arxiv.org/abs/2504.12673) _Singon Kim, Gunho Jung, Seong-Whan Lee._ Arxiv 2025.

13. [**SARA: Selective and Adaptive Retrieval-augmented Generation with Context Compression.**](https://arxiv.org/abs/2507.05633) _Yiqiao Jin, Kartik Sharma, Vineeth Rakesh, Yingtong Dou, Menghai Pan, Mahashweta Das, Srijan Kumar._ Arxiv 2025.

14. [**AttnComp: Attention-Guided Adaptive Context Compression for Retrieval-Augmented Generation.**](https://arxiv.org/abs/2509.17486) _Lvzhou Luo, Yixuan Cao, Ping Luo._ EMNLP 2025.

15. [**Prompt Compression for Large Language Models: A Survey.**](https://arxiv.org/abs/2410.12388) _Zongqian Li, Yinhong Liu, Yixuan Su, Nigel Collier._ Arxiv 2024.

16. [**What to Keep, What to Forget: A Rate--Distortion View of Memory Compaction in LLMs and Agents.**](https://arxiv.org/abs/2607.08032) _Ashwin Gerard Colaco, Nada Lahjouji._ Arxiv 2026.

17. [**MemoSight: Unifying Context Compression and Multi Token Prediction for Reasoning Acceleration.**](https://arxiv.org/abs/2604.14889) _Xinyu Liu, Xin Liu, Bo Jin, Runsong Zhao, Pengcheng Huang, Junhao Ruan, Bei Li, Chunyang Xiao, Chenglong Wang, Tong Xiao, Jingbo Zhu._ Arxiv 2026.

18. [**VLZip: Unified Visual and Textual Compression for Interleaved Long-Context Modeling.**](https://arxiv.org/abs/2608.08630) _Yuqi Zhang, Cheng Chen, Yuyu Guo, Wenjie Yang, Lingchen Meng, Peng Di, Hang Yu, Zuxuan Wu, Yu-Gang Jiang._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/ShareLab-SII/VLZip)](https://github.com/ShareLab-SII/VLZip)

19. [**Cache-Aware Prompt Compression:A Two-Tier Cost Model for LLM API Caching.**](https://arxiv.org/abs/2607.15516) _Yan Song._ Arxiv 2026.
