# 13. Long Reasoning (Long CoT)

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [13.1 Efficient Long CoT: Compression, Budgeting & Early Exit](#131-efficient-long-cot-compression-budgeting--early-exit)
- [13.2 Policy / Reward Optimization for Long Reasoning](#132-policy--reward-optimization-for-long-reasoning)
- [13.3 Test-time Scaling](#133-test-time-scaling)
- [13.4 Latent & Multimodal Reasoning](#134-latent--multimodal-reasoning)
- [13.5 Long-CoT Training, Distillation & Analysis](#135-long-cot-training-distillation--analysis)
<!-- /chapter-toc -->

#### 13.1 Efficient Long CoT: Compression, Budgeting & Early Exit

1. [**Reasoning Path Compression: Compressing Generation Trajectories for Efficient LLM Reasoning.**](https://arxiv.org/abs/2505.13866) _Jiwon Song, Dongwon Jo, Yulhwa Kim, Jae-Joon Kim._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/jiwonsong-dev/ReasoningPathCompression)](https://github.com/jiwonsong-dev/ReasoningPathCompression)

2. [**Can Pruning Improve Reasoning? Revisiting Long-CoT Compression with Capability in Mind for Better Reasoning.**](https://arxiv.org/abs/2505.14582) _Shangziqi Zhao, Jiahao Yuan, Guisong Yang, Usman Naseem._ Arxiv 2025.

3. [**FlashThink: An Early Exit Method For Efficient Reasoning.**](https://arxiv.org/abs/2505.13949) _Guochao Jiang, Guofeng Quan, Zepeng Ding, Ziqin Luo, Dixuan Wang, Zheng Hu._ Arxiv 2025.

4. [**Not All Tokens Are What You Need In Thinking.**](https://arxiv.org/abs/2505.17827) _Hang Yuan, Bin Yu, Haotian Li, Shijun Yang, Christina Dan Wang, Zhou Yu, Xueyin Xu, Weizhen Qi, Kai Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Faustrazor/Not-All-Thinking-Tokens)](https://github.com/Faustrazor/Not-All-Thinking-Tokens)

5. [**TrimR: Verifier-based Training-Free Thinking Compression for Efficient Test-Time Scaling.**](https://arxiv.org/abs/2505.17155) _Weizhe Lin, Xing Li, Zhiyuan Yang, Xiaojin Fu, Hui-Ling Zhen, Yaoyuan Wang, Xianzhi Yu, Wulong Liu, Xiaosong Li, Mingxuan Yuan._ Arxiv 2025.

6. [**Efficient Long CoT Reasoning in Small Language Models.**](https://arxiv.org/abs/2505.18440) _Zhaoyang Wang, Jinqi Jiang, Tian Qiu, Hui Liu, Xianfeng Tang, Huaxiu Yao._ Arxiv 2025.

7. [**Efficient Reasoning via Chain of Unconscious Thought.**](https://arxiv.org/abs/2505.19756) _Ruihan Gong, Yue Liu, Wenjie Qu, Mingzhe Du, Yufei He, Yingwei Ma, Yulin Chen, Xiang Liu, Yi Wen, Xinfeng Li, Ruidong Wang, Xinzhong Zhu, Bryan Hooi, Jiaheng Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Rohan-GRH/CoUT)](https://github.com/Rohan-GRH/CoUT)

8. [**System-1.5 Reasoning: Traversal in Language and Latent Spaces with Dynamic Shortcuts.**](https://arxiv.org/abs/2505.18962) _Xiaoqiang Wang, Suyuchen Wang, Yun Zhu, Bang Liu._ Arxiv 2025.

9. [**Optimizing Length Compression in Large Reasoning Models.**](https://arxiv.org/abs/2506.14755) _Zhengxiang Cheng, Dongping Chen, Mingyang Fu, Tianyi Zhou._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zxiangx/LC-R1)](https://github.com/zxiangx/LC-R1)

10. [**From Long to Short: LLMs Excel at Trimming Own Reasoning Chains.**](https://arxiv.org/abs/2509.06174) _Wei Han, Geng Zhan, Sicheng Yu, Chenyu Wang, Bryan Hooi._ Arxiv 2025.

11. [**Reasoning Efficiently Through Adaptive Chain-of-Thought Compression: A Self-Optimizing Framework.**](https://arxiv.org/abs/2509.14093) _Kerui Huang, Shuhan Liu, Xing Hu, Tongtong Xu, Lingfeng Bao, Xin Xia._ Arxiv 2025.

12. [**From Long to Lean: Performance-aware and Adaptive Chain-of-Thought Compression via Multi-round Refinement.**](https://arxiv.org/abs/2509.22144) _Jianzhi Yan, Le Liu, Youcheng Pan, Shiwei Chen, Zike Yuan, Yang Xiang, Buzhou Tang._ Arxiv 2025.

13. [**Chain-of-Thought Compression Should Not Be Blind: V-Skip for Efficient Multimodal Reasoning via Dual-Path Anchoring.**](https://arxiv.org/abs/2601.13879) _Dongxu Zhang, Yiding Sun, Cheng Tan, Wenbiao Yan, Ning Yang, Jihua Zhu, Hiajun Zhang._ Arxiv 2026.

14. [**Efficient Long-Decoding Inference with Reasoning-Aware Attention Sparsity.**](https://arxiv.org/abs/2502.11147) _Junhao Hu, Wenrui Huang, Weidong Wang, Zhenwen Li, Tiancheng Hu, Zhixia Liu, Xusheng Chen, Tao Xie, Yizhou Shan._ Arxiv 2025.

15. [**TokenSkip: Controllable Chain-of-Thought Compression in LLMs.**](https://arxiv.org/abs/2502.12067) _Heming Xia, Yongqi Li, Chak Tou Leong, Wenjie Wang, Wenjie Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hemingkx/TokenSkip)](https://github.com/hemingkx/TokenSkip)

16. [**LightThinker: Thinking Step-by-Step Compression.**](https://arxiv.org/abs/2502.15589) _Jintian Zhang, Yuqi Zhu, Mengshu Sun, Yujie Luo, Shuofei Qiao, Lun Du, Da Zheng, Huajun Chen, Ningyu Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zjunlp/LightThinker)](https://github.com/zjunlp/LightThinker)

17. [**PENCIL: Long Thoughts with Short Memory.**](https://arxiv.org/abs/2503.14337) _Chenxiao Yang, Nathan Srebro, David McAllester, Zhiyuan Li._ Arxiv 2025.

18. [**Thought Manipulation: External Thought Can Be Efficient for Large Reasoning Models.**](https://arxiv.org/abs/2504.13626) _Yule Liu, Jingyi Zheng, Zhen Sun, Zifan Peng, Wenhan Dong, Zeyang Sha, Shiwen Cui, Weiqiang Wang, Xinlei He._ Arxiv 2025.

19. [**Prolonged Reasoning Is Not All You Need: Certainty-Based Adaptive Routing for Efficient LLM/MLLM Reasoning.**](https://arxiv.org/abs/2505.15154) _Jinghui Lu, Haiyang Yu, Siliang Xu, Shiwei Ran, Guozhi Tang, Siqi Wang, Bin Shan, Teng Fu, Hao Feng, Jingqun Tang, Han Wang, Can Huang._ Arxiv 2025.

20. [**ThinkLess: A Training-Free Inference-Efficient Method for Reducing Reasoning Redundancy.**](https://arxiv.org/abs/2505.15684) _Gengyang Li, Yifeng Gao, Yuming Li, Yunfang Wu._ Arxiv 2025.

21. [**When to Continue Thinking: Adaptive Thinking Mode Switching for Efficient Reasoning.**](https://arxiv.org/abs/2505.15400) _Xiaoyun Zhang, Jingqing Ruan, Xing Ma, Yawen Zhu, Haodong Zhao, Hao Li, Jiansong Chen, Ke Zeng, Xunliang Cai._ Arxiv 2025.

22. [**Don't Overthink it. Preferring Shorter Thinking Chains for Improved LLM Reasoning.**](https://arxiv.org/abs/2505.17813) _Michael Hassid, Gabriel Synnaeve, Yossi Adi, Roy Schwartz._ Arxiv 2025.

23. [**A\*-Thought: Efficient Reasoning via Bidirectional Compression for Low-Resource Settings.**](https://arxiv.org/abs/2505.24550) _Xiaoang Xu, Shuo Wang, Xu Han, Zhenghao Liu, Huijia Wu, Peipei Li, Zhiyuan Liu, Maosong Sun, Zhaofeng He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AI9Stars/AStar-Thought)](https://github.com/AI9Stars/AStar-Thought)

24. [**AutoL2S: Auto Long-Short Reasoning for Efficient Large Language Models.**](https://arxiv.org/abs/2505.22662) _Feng Luo, Yu-Neng Chuang, Guanchu Wang, Hoang Anh Duy Le, Shaochen Zhong, Hongyi Liu, Jiayi Yuan, Yang Sui, Vladimir Braverman, Vipin Chaudhary, Xia Hu._ Arxiv 2025.

25. [**Self-Route: Automatic Mode Switching via Capability Estimation for Efficient Reasoning.**](https://arxiv.org/abs/2505.20664) _Yang He, Xiao Ding, Bibo Cai, Yufei Zhang, Kai Xiong, Zhouhao Sun, Bing Qin, Ting Liu._ Arxiv 2025.

26. [**TL;DR: Too Long, Do Re-weighting for Efficient LLM Reasoning Compression.**](https://arxiv.org/abs/2506.02678) _Zhong-Zhi Li, Xiao Liang, Zihao Tang, Lei Ji, Peijie Wang, Haotian Xu, Xing W, Haizhen Huang, Weiwei Deng, Ying Nian Wu, Yeyun Gong, Zhijiang Guo, Xiao Liu, Fei Yin, Cheng-Lin Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zzli2022/TLDR)](https://github.com/zzli2022/TLDR)

27. [**Long or short CoT? Investigating Instance-level Switch of Large Reasoning Models.**](https://arxiv.org/abs/2506.04182) _Ruiqi Zhang, Changyi Xiao, Yixin Cao._ Arxiv 2025.

28. [**AALC: Large Language Model Efficient Reasoning via Adaptive Accuracy-Length Control.**](https://arxiv.org/abs/2506.20160) _Ruosen Li, Ziming Luo, Quan Zhang, Ruochen Li, Ben Zhou, Ali Payani, Xinya Du._ Arxiv 2025.

29. [**Do Thinking Tokens Help or Trap? Towards More Efficient Large Reasoning Model.**](https://arxiv.org/abs/2506.23840) _Bowen Ding, Yuhan Chen, Futing Wang, Lingfeng Ming, Tao Lin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Danield21/Dual-Policy-Preference-Optimization)](https://github.com/Danield21/Dual-Policy-Preference-Optimization)

30. [**Pruning the Unsurprising: Efficient Code Reasoning via First-Token Surprisal.**](https://arxiv.org/abs/2508.05988) _Wenhao Zeng, Yaoning Wang, Chao Hu, Yuling Shi, Chengcheng Wan, Hongyu Zhang, Xiaodong Gu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Zengwh02/ASAP)](https://github.com/Zengwh02/ASAP)

31. [**SABER: Switchable and Balanced Training for Efficient LLM Reasoning.**](https://arxiv.org/abs/2508.10026) _Kai Zhao, Yanjun Zhao, Jiaming Song, Shien He, Lusheng Zhang, Qiang Zhang, Tianjiao Li._ Arxiv 2025.

32. [**Stop Spinning Wheels: Mitigating LLM Overthinking via Mining Patterns for Early Reasoning Exit.**](https://arxiv.org/abs/2508.17627) _Zihao Wei, Liang Pang, Jiahao Liu, Jingcheng Deng, Shicheng Xu, Zenghao Duan, Jingang Wang, Fei Sun, Xunliang Cai, Huawei Shen, Xueqi Cheng._ Arxiv 2025.

33. [**DRQA: Dynamic Reasoning Quota Allocation for Controlling Overthinking in Reasoning Large Language Models.**](https://arxiv.org/abs/2508.17803) _Kaiwen Yan, Xuanqing Shi, Hongcheng Guo, Wenxuan Wang, Zhuosheng Zhang, Chengwei Qin._ Arxiv 2025.

34. [**ADaPT: Token-Level Decoupling for Efficient Large Reasoning Models.**](https://arxiv.org/abs/2606.19919) _Tingyun Li, Zishang Jiang, Jinyi Han, Xinyi Wang, Sihang Jiang, Han Xia, Zhaoqian Dai, Shuguang Ma, Fei Yu, Jiaqing Liang, Yanghua Xiao._ Arxiv 2026.

35. [**BudgetThinker: Empowering Budget-aware LLM Reasoning with Control Tokens.**](https://arxiv.org/abs/2508.17196) _Hao Wen, Xinrui Wu, Yi Sun, Feifei Zhang, Liye Chen, Jie Wang, Yunxin Liu, Ya-Qin Zhang, Yuanchun Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MobileLLM/BudgetThinker)](https://github.com/MobileLLM/BudgetThinker)

36. [**SmartSwitch: Advancing LLM Reasoning by Overcoming Underthinking via Promoting Deeper Thought Exploration.**](https://arxiv.org/abs/2510.19767) _Xichen Zhang, Sitong Wu, Haoru Tan, Shaozuo Yu, Yinghao Zhu, Ziyi He, Jiaya Jia._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/SmartSwitch)](https://github.com/dvlab-research/SmartSwitch)
37. [**Dynamic Early Exit in Reasoning Models.**](https://arxiv.org/abs/2504.15895) _Chenxu Yang, Qingyi Si, Yongjie Duan, Zheliang Zhu, Chenyu Zhu, Zheng Lin, Li Cao, Weiping Wang._ Arxiv 2025.

38. [**ThinkSwitcher: When to Think Hard, When to Think Fast.**](https://arxiv.org/abs/2505.14183) _Guosheng Liang, Longguang Zhong, Ziyi Yang, Xiaojun Quan._ Arxiv 2025.

39. [**ARM: Adaptive Reasoning Model.**](https://arxiv.org/abs/2505.20258) _Siye Wu, Jian Xie, Yikai Zhang, Aili Chen, Kai Zhang, Yu Su, Yanghua Xiao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/TEAM-ARM/ARM)](https://github.com/TEAM-ARM/ARM)

40. [**Think or Not? Exploring Thinking Efficiency in Large Reasoning Models via an Information-Theoretic Lens.**](https://arxiv.org/abs/2505.18237) _Xixian Yong, Xiao Zhou, Yingying Zhang, Jinlin Li, Yefeng Zheng, Xian Wu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/chicosirius/think-or-not)](https://github.com/chicosirius/think-or-not)

41. [**AlphaOne: Reasoning Models Thinking Slow and Fast at Test Time.**](https://arxiv.org/abs/2505.24863) _Junyu Zhang, Runpei Dong, Han Wang, Xuying Ning, Haoran Geng, Peihao Li, Xialin He, Yutong Bai, Jitendra Malik, Saurabh Gupta, Huan Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ASTRAL-Group/AlphaOne)](https://github.com/ASTRAL-Group/AlphaOne)

42. [**Adaptive Deep Reasoning: Triggering Deep Thinking When Needed.**](https://arxiv.org/abs/2505.20101) _Yunhao Wang, Yuhao Zhang, Tinghao Yu, Can Xu, Feng Zhang, Fengzong Lian._ Arxiv 2025.

43. [**Route to Reason: Adaptive Routing for LLM and Reasoning Strategy Selection.**](https://arxiv.org/abs/2505.19435) _Zhihong Pan, Kai Zhang, Yuze Zhao, Yupeng Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/goodmanpzh/Route-To-Reason)](https://github.com/goodmanpzh/Route-To-Reason)

44. [**Adaptive Termination for Multi-round Parallel Reasoning: An Universal Semantic Entropy-Guided Framework.**](https://arxiv.org/abs/2507.06829) _Zenan Xu, Zexuan Qiu, Guanhua Huang, Kun Li, Siheng Li, Chenchen Zhang, Kejiao Li, Qi Yi, Yuhao Jiang, Bo Zhou, Fengzong Lian, Zhanhui Kang._ Arxiv 2025.

45. [**Aware First, Think Less: Dynamic Boundary Self-Awareness Drives Extreme Reasoning Efficiency in Large Language Models.**](https://arxiv.org/abs/2508.11582) _Qiguang Chen, Dengyun Peng, Jinhao Liu, HuiKang Su, Jiannan Guan, Libo Qin, Wanxiang Che._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/sfasfaffa/DR_SAF)](https://github.com/sfasfaffa/DR_SAF)

46. [**ThinkDial: An Open Recipe for Controlling Reasoning Effort in Large Language Models.**](https://arxiv.org/abs/2508.18773) _Qianyu He, Siyu Yuan, Xuefeng Li, Mingxuan Wang, Jiangjie Chen._ Arxiv 2025.

47. [**Early Stopping Chain-of-thoughts in Large Language Models.**](https://arxiv.org/abs/2509.14004) _Minjia Mao, Bowen Yin, Yu Zhu, Xiao Fang._ Arxiv 2025.

48. [**Fast Thinking for Large Language Models.**](https://arxiv.org/abs/2509.23633) _Haoyu Zheng, Zhuonan Wang, Yuqian Yuan, Tianwei Lin, Wenqiao Zhang, Zheqi Lv, Juncheng Li, Siliang Tang, Yueting Zhuang, Hongyang He._ Arxiv 2025.

49. [**Think When You Need: Self-Adaptive Chain-of-Thought Learning.**](https://arxiv.org/abs/2504.03234) _Junjie Yang, Ke Lin, Xing Yu._ Arxiv 2025.

50. [**SmartThinker: Progressive Chain-of-Thought Length Calibration for Efficient Large Language Model Reasoning.**](https://arxiv.org/abs/2603.08000) _Chenzhi Hu, Qinzhe Hu, Yuhang Xu, Junyi Chen, Ruijie Wang, Shengzhong Liu, Jianxin Li, Fan Wu, Guihai Chen._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/SJTU-RTEAS/SmartThinker)](https://github.com/SJTU-RTEAS/SmartThinker)

51. [**Draft-Thinking: Learning Efficient Reasoning in Long Chain-of-Thought LLMs.**](https://arxiv.org/abs/2603.00578) _Jie Cao, Tianwei Lin, Zhenxuan Fan, Bo Yuan, Ziyuan Zhao, Rolan Yan, Wenqiao Zhang, Siliang Tang._ Arxiv 2026.

52. [**Efficient Reasoning with Balanced Thinking.**](https://arxiv.org/abs/2603.12372) _Yulin Li, Tengyao Tu, Li Ding, Junjie Wang, Huiling Zhen, Yixin Chen, Yong Li, Zhuotao Tian._ Arxiv 2026.

53. [**CreDes: Causal Reasoning Enhancement and Dual-End Searching for Solving Long-Range Reasoning Problems using LLMs.**](https://arxiv.org/abs/2410.01696) _Kangsheng Wang, Xiao Zhang, Hao Liu, Songde Han, Huimin Ma, Tianyu Hu._ Arxiv 2024.

54. [**System 2 Attention (is something you might need too).**](https://arxiv.org/abs/2311.11829) _Jason Weston, Sainbayar Sukhbaatar._ Arxiv 2023.

55. [**SLPO: Scaling Latent Reasoning via a Surrogate Policy.**](https://arxiv.org/abs/2607.19691) _Runyang You, Zhiyuan Liu, Yongqi Li, Wenjie Li._ Arxiv 2026.

56. [**HybridThinker: Efficient Chain-of-Thought Reasoning via Compressed Memory and Transient Thought Steps.**](https://arxiv.org/abs/2606.03768) _Xin Liu, Runsong Zhao, Xinyu Liu, Junhao Ruan, Pengcheng Huang, Shichao Dong, Chunyang Xiao, Chenglong Wang, Changliang Li, Jingbo Zhu, Tong Xiao._ Arxiv 2026.

57. [**Nice Fold or Hero Call: Learning Budget-Efficient Thinking for Adaptive Reasoning.**](https://arxiv.org/abs/2605.11625) _Zhaomeng Zhou, Lan Zhang, Junyang Wang, Mu Yuan, Junda Lin._ Arxiv 2026.

58. [**Not Worth Another Token: Marginal Value Estimation for Efficient Deep Research Agents.**](https://arxiv.org/abs/2608.08389) _Harshitha Kolukuluru, Reshma Ashok, Kirat Arora, Evan William Ciccarelli, Nischal Ashok Kumar, Lunyiu Nie, Franck Dernoncourt, Samyadeep Basu, Ryan A. Rossi, Nedim Lipka._ Arxiv 2026.

59. [**Refining Over Resampling: Test-Time Self-Correction for LLM Reasoning.**](https://arxiv.org/abs/2608.05643) _Ahsan Bilal, Muhammad Ahmed Mohsin, Muhammad Umer, Lena Trigg, Ali Subhan, Muhammad Ali, Dean F. Hougen._ EMNLP 2026.

60. [**Fewer Tokens, Smaller Cache: Reward-Coordinated Efficient Reasoning.**](https://arxiv.org/abs/2608.04771) _Qiyuan Zhu, Dezhi Li, Pengyu Cheng, Tianle Chen, Jiacheng Wang, Ruijie Shen, Hao Gu, Sida Lin, Zirui Liu, Jiacheng Liu, Sirui Han._ Arxiv 2026.

61. [**Thinking with Anchors: Grounded and Efficient Document Reasoning.**](https://arxiv.org/abs/2608.04424) _Sichen Zhu, Yuchen Zhu, Wenzhuo Xu, Jason Kuen, Wanrong Zhu, Jing Shi, Xuan Shen, Quanyi Wang, Yiwei Wang, Yujun Cai, Bing Shuai, Qin Zhang, Yongxin Chen, Shilong Liu, Molei Tao, Jiuxiang Gu._ Arxiv 2026.

62. [**EvoThink: Evolving Thinking in Large Reasoning Models via Self-Pruning and Aha-Moment Preference Optimization.**](https://arxiv.org/abs/2607.19962) _Xinbang Dai, Zheyu Xin, Huikang Hu, Lin Ren, Rihui Jin, Guohui Xiao, Guilin Qi, Kuicai Dong, Zhaocheng Du, Yuyang Zhang._ Arxiv 2026.

63. [**CAT: Confidence-Adaptive Thinking for Efficient Reasoning of Large Reasoning Models.**](https://arxiv.org/abs/2607.00862) _Qizhi Jiang, Shuo Wang, Pei Ke, Yuhang Song, Ke Qin._ ACL 2026.

64. [**Know When to Stop: Segment-Level Credit Assignment for Reducing Overthinking.**](https://arxiv.org/abs/2607.00482) _Chia-Hsuan Lee, Sihui Dai, Mingyang Zhou, Isha Slavin, Hsuan Su, Shi-Xiong Zhang, Sambit Sahu, William Campbell._ Arxiv 2026.

65. [**DART: Draft-Agreement Routing for Training-Free Adaptive Thinking Budgets in Hybrid Reasoning Models.**](https://arxiv.org/abs/2606.23181) _Jungseob Lee, Seongtae Hong, Seungjun Lee, Jaehyung Seo, Junyoung Son, Sugyeong Eo, Chanjun Park, Hyeongju Park, Hyeonseok Moon, Heuiseok Lim._ Arxiv 2026.

#### 13.2 Policy / Reward Optimization for Long Reasoning

1. [**OpenRFT: Adapting Reasoning Foundation Model for Domain-specific Tasks with Reinforcement Fine-Tuning.**](https://arxiv.org/abs/2412.16849) _Yuxiang Zhang, Yuqi Yang, Jiangming Shu, Yuhang Wang, Jinlin Xiao, Jitao Sang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ADaM-BJTU/OpenRFT)](https://github.com/ADaM-BJTU/OpenRFT)

2. [**What's Behind PPO's Collapse in Long-CoT? Value Optimization Holds the Secret.**](https://arxiv.org/abs/2503.01491) _Yufeng Yuan, Yu Yue, Ruofei Zhu, Tiantian Fan, Lin Yan._ Arxiv 2025.

3. [**L1: Controlling How Long A Reasoning Model Thinks With Reinforcement Learning.**](https://arxiv.org/abs/2503.04697) _Pranjal Aggarwal, Sean Welleck._ Arxiv 2025.

4. [**Light-R1: Curriculum SFT, DPO and RL for Long COT from Scratch and Beyond.**](https://arxiv.org/abs/2503.10460) _Liang Wen, Yunke Cai, Fenrui Xiao, Xin He, Qi An, Zhenyu Duan, Yimin Du, Junchen Liu, Lifu Tang, Xiaowei Lv, Haosheng Zou, Yongchao Deng, Shousheng Jia, Xiangzheng Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Qihoo360/Light-R1)](https://github.com/Qihoo360/Light-R1)

5. [**SimpleRL-Zoo: Investigating and Taming Zero Reinforcement Learning for Open Base Models in the Wild.**](https://arxiv.org/abs/2503.18892) _Weihao Zeng, Yuzhen Huang, Qian Liu, Wei Liu, Keqing He, Zejun Ma, Junxian He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hkust-nlp/simpleRL-reason)](https://github.com/hkust-nlp/simpleRL-reason)

6. [**ReTool: Reinforcement Learning for Strategic Tool Use in LLMs.**](https://arxiv.org/abs/2504.11536) _Jiazhan Feng, Shijue Huang, Xingwei Qu, Ge Zhang, Yujia Qin, Baoquan Zhong, Chengquan Jiang, Jinxin Chi, Wanjun Zhong._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ReTool-RL/ReTool)](https://github.com/ReTool-RL/ReTool)

7. [**AdaR1: From Long-CoT to Hybrid-CoT via Bi-Level Adaptive Reasoning Optimization.**](https://arxiv.org/abs/2504.21659) _Haotian Luo, Haiying He, Yibo Wang, Jinluan Yang, Rui Liu, Naiqiang Tan, Xiaochun Cao, Dacheng Tao, Li Shen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/StarDewXXX/AdaR1)](https://github.com/StarDewXXX/AdaR1)

8. [**RM-R1: Reward Modeling as Reasoning.**](https://arxiv.org/abs/2505.02387) _Xiusi Chen, Gaotang Li, Ziqi Wang, Bowen Jin, Cheng Qian, Yu Wang, Hongru Wang, Yu Zhang, Denghui Zhang, Tong Zhang, Hanghang Tong, Heng Ji._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/RM-R1-UIUC/RM-R1)](https://github.com/RM-R1-UIUC/RM-R1)

9. [**Think on your Feet: Adaptive Thinking via Reinforcement Learning for Social Agents.**](https://arxiv.org/abs/2505.02156) _Minzheng Wang, Yongbin Li, Haobo Wang, Xinghua Zhang, Nan Xu, Bingli Wu, Fei Huang, Haiyang Yu, Wenji Mao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MozerWang/AMPO)](https://github.com/MozerWang/AMPO)

10. [**Reinforcement Learning vs. Distillation: Understanding Accuracy and Capability in LLM Reasoning.**](https://arxiv.org/abs/2505.14216) _Minwu Kim, Anubhav Shrestha, Safal Shrestha, Aadim Nepal, Keith Ross._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/minwukim/RLvsDistillation)](https://github.com/minwukim/RLvsDistillation)

11. [**QwenLong-L1: Towards Long-Context Large Reasoning Models with Reinforcement Learning.**](https://arxiv.org/abs/2505.17667) _Fanqi Wan, Weizhou Shen, Shengyi Liao, Yingcheng Shi, Chenliang Li, Ziyi Yang, Ji Zhang, Fei Huang, Jingren Zhou, Ming Yan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongyi-Zhiwen/QwenLong-L1)](https://github.com/Tongyi-Zhiwen/QwenLong-L1)

12. [**Walk Before You Run! Concise LLM Reasoning via Reinforcement Learning.**](https://arxiv.org/abs/2505.21178) _Mingyang Song, Mao Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/ConciseR)](https://github.com/nick7nlp/ConciseR)

13. [**Thinking Fast and Right: Balancing Accuracy and Reasoning Length with Adaptive Rewards.**](https://arxiv.org/abs/2505.18298) _Jinyan Su, Claire Cardie._ Arxiv 2025.

14. [**Just Enough Thinking: Efficient Reasoning with Adaptive Length Penalties Reinforcement Learning.**](https://arxiv.org/abs/2506.05256) _Violet Xiang, Chase Blagden, Rafael Rafailov, Nathan Lile, Sang Truong, Chelsea Finn, Nick Haber._ Arxiv 2025.

15. [**AdapThink: Adaptive Thinking Preferences for Reasoning Language Model.**](https://arxiv.org/abs/2506.18237) _Xu Wan, Wei Wang, Wenyue Xu, Wotao Yin, Jie Song, Mingyang Sun._ Arxiv 2025.

16. [**OctoThinker: Mid-training Incentivizes Reinforcement Learning Scaling.**](https://arxiv.org/abs/2506.20512) _Zengzhi Wang, Fan Zhou, Xuefeng Li, Pengfei Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/OctoThinker)](https://github.com/GAIR-NLP/OctoThinker)

17. [**LAPO: Internalizing Reasoning Efficiency via Length-Adaptive Policy Optimization.**](https://arxiv.org/abs/2507.15758) _Xingyu Wu, Yuchen Yan, Shangke Lyu, Linjuan Wu, Yiwen Qiu, Yongliang Shen, Weiming Lu, Jian Shao, Jun Xiao, Yueting Zhuang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zju-real/lapo)](https://github.com/zju-real/lapo)

18. [**Sample More to Think Less: Group Filtered Policy Optimization for Concise Reasoning.**](https://arxiv.org/abs/2508.09726) _Vaishnavi Shrivastava, Ahmed Awadallah, Vidhisha Balachandran, Shivam Garg, Harkirat Behl, Dimitris Papailiopoulos._ Arxiv 2025.

19. [**SSPO: Self-traced Step-wise Preference Optimization for Process Supervision and Reasoning Compression.**](https://arxiv.org/abs/2508.12604) _Yuyang Xu, Yi Cheng, Haochao Ying, Zhuoyun Du, Renjun Hu, Xing Shi, Wei Lin, Jian Wu._ Arxiv 2025.
20. [**Hybrid Latent Reasoning via Reinforcement Learning.**](https://arxiv.org/abs/2505.18454) _Zhenrui Yue, Bowen Jin, Huimin Zeng, Honglei Zhuang, Zhen Qin, Jinsung Yoon, Lanyu Shang, Jiawei Han, Dong Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Yueeeeeeee/HRPO)](https://github.com/Yueeeeeeee/HRPO)

21. [**Learn to Reason Efficiently with Adaptive Length-based Reward Shaping.**](https://arxiv.org/abs/2505.15612) _Wei Liu, Ruochen Zhou, Yiyun Deng, Yuzhen Huang, Junteng Liu, Yuntian Deng, Yizhe Zhang, Junxian He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hkust-nlp/Laser)](https://github.com/hkust-nlp/Laser)

22. [**Hierarchical Budget Policy Optimization for Adaptive Reasoning.**](https://arxiv.org/abs/2507.15844) _Shangke Lyu, Linjuan Wu, Yuchen Yan, Xingyu Wu, Hao Li, Yongliang Shen, Peisheng Jiang, Weiming Lu, Jun Xiao, Yueting Zhuang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zju-real/hbpo)](https://github.com/zju-real/hbpo)

23. [**Train Long, Think Short: Curriculum Learning for Efficient Reasoning.**](https://arxiv.org/abs/2508.08940) _Hasan Abed Al Kader Hammoud, Kumail Alhamoud, Abed Hammoud, Elie Bou-Zeid, Marzyeh Ghassemi, Bernard Ghanem._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hammoudhasan/curriculum_grpo)](https://github.com/hammoudhasan/curriculum_grpo)

24. [**ThinkPrune: Pruning Long Chain-of-Thought of LLMs via Reinforcement Learning.**](https://arxiv.org/abs/2504.01296) _Bairu Hou, Yang Zhang, Jiabao Ji, Yujian Liu, Kaizhi Qian, Jacob Andreas, Shiyu Chang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UCSB-NLP-Chang/ThinkPrune)](https://github.com/UCSB-NLP-Chang/ThinkPrune)

25. [**Batched Contextual Reinforcement: A Task-Scaling Law for Efficient Reasoning.**](https://arxiv.org/abs/2604.02322) _Bangji Yang, Hongbo Ma, Jiajun Fan, Ge Liu._ Arxiv 2026.

26. [**AdaptR1: Reinforcement Learning Based Adaptive Interleaved Thinking in Multi-hop Question Answering.**](https://arxiv.org/abs/2605.31062) _Yuxin Wang, Jiahao Lu, Qifeng Wu, Shicheng Fang, Chuanyuan Tan, Yining Zheng, Xuanjing Huang, Xipeng Qiu._ Arxiv 2026.

27. [**Sparrow: Sparse Rollout for Stable and Efficient Long-context RL of Large Language Models.**](https://arxiv.org/abs/2606.08446) _Yang Zhou, Ranajoy Sadhukhan, Zhaofeng Sun, Zhuoming Chen, Souvik Kundu, Saket Dingliwal, Sai Muralidhar Jayanthi, Aram Galstyan, Haizhong Zheng, Beidi Chen._ Arxiv 2026.

28. [**LLMZero: Discovering Adaptive Training Strategies for RL Post-Training via LLM Agents.**](https://arxiv.org/abs/2606.18388) _Haoyang Fang, Wei Zhu, Boran Han, Alex Zhang, Zhenyu Pan, Shuo Yang, Shuai Zhang, Jiading Gai, Peng Tang, Cuixiong Hu, Xuan Zhu, Huzefa Rangwala, George Karypis, Bernie Wang._ Arxiv 2026.

#### 13.3 Test-time Scaling

1. [**Leveraging Constrained Monte Carlo Tree Search to Generate Reliable Long Chain-of-Thought for Mathematical Reasoning.**](https://arxiv.org/abs/2502.11169) _Qingwen Lin, Boyan Xu, Zijian Li, Zhifeng Hao, Keli Zhang, Ruichu Cai._ Arxiv 2025.

2. [**Revisiting the Test-Time Scaling of o1-like Models: Do they Truly Possess Test-Time Scaling Capabilities?.**](https://arxiv.org/abs/2502.12215) _Zhiyuan Zeng, Qinyuan Cheng, Zhangyue Yin, Yunhua Zhou, Xipeng Qiu._ Arxiv 2025.

3. [**Process Reward Models That Think.**](https://arxiv.org/abs/2504.16828) _Muhammad Khalifa, Rishabh Agarwal, Lajanugen Logeswaran, Jaekyeom Kim, Hao Peng, Moontae Lee, Honglak Lee, Lu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mukhal/thinkprm)](https://github.com/mukhal/thinkprm)

4. [**Does Thinking More always Help? Understanding Test-Time Scaling in Reasoning Models.**](https://arxiv.org/abs/2506.04210) _Soumya Suvra Ghosal, Souradip Chakraborty, Avinash Reddy, Yifu Lu, Mengdi Wang, Dinesh Manocha, Furong Huang, Mohammad Ghavamzadeh, Amrit Singh Bedi._ Arxiv 2025.

5. [**Kinetics: Rethinking Test-Time Scaling Laws.**](https://arxiv.org/abs/2506.05333) _Ranajoy Sadhukhan, Zhuoming Chen, Haizhong Zheng, Yang Zhou, Emma Strubell, Beidi Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/Kinetics)](https://github.com/Infini-AI-Lab/Kinetics)

6. [**ParaThinker: Native Parallel Thinking as a New Paradigm to Scale LLM Test-time Compute.**](https://arxiv.org/abs/2509.04475) _Hao Wen, Yifan Su, Feifei Zhang, Yunxin Liu, Yunhao Liu, Ya-Qin Zhang, Yuanchun Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MobileLLM/ParaThinker)](https://github.com/MobileLLM/ParaThinker)

7. [**Scaling Reasoning Tokens via RL and Parallel Thinking: Evidence From Competitive Programming.**](https://arxiv.org/abs/2604.01302) _Qianfan Zhang, Tianyu Guo, Xuandi Ren, Jiale Chen, Ming Ding, Ran Xin, Xia Xiao._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/slime)](https://github.com/THUDM/slime)

8. [**Claim-Level Reliability Assessment for Efficient Test-Time Reasoning.**](https://arxiv.org/abs/2608.11994) _Sen Xu, Wei Wang, Shixi Liu, Jixin Min, Yingwei Dai, Zhibin Yin, Yirong Chen, Junlin Zhang._ Arxiv 2026.

9. [**CoBa: Cost-Effective Test-Time Scaling via Compute-Balanced Routing.**](https://arxiv.org/abs/2608.07424) _Yan Zhou, Yue Ouyang, Kaiyang Zheng, Suncheng Xiang._ Arxiv 2026.

10. [**Test-Time Scaling in Reasoning LLMs: Inference Regimes, Evaluation, and Reproducibility.**](https://arxiv.org/abs/2608.04001) _Mohsen Hariri, Weicong Chen, Nahal Shahini, Vikash Singh, Kai Ye, Amirhossein Samandar, Debargha Ganguly, Sreehari Sankar, Yanyan Zhang, Shouren Wang, Jerry Peng, Biyao Zhang, Michael Hinczewski, Vipin Chaudhary._ Arxiv 2026.

11. [**Interpretable Adaptive Sampling for LLM Test-Time Scaling.**](https://arxiv.org/abs/2608.03961) _Mobina Kashaniyan, Ali Jannesari._ Arxiv 2026.

#### 13.4 Latent & Multimodal Reasoning

1. [**Language Models are Hidden Reasoners: Unlocking Latent Reasoning Capabilities via Self-Rewarding.**](https://arxiv.org/abs/2411.04282) _Haolin Chen, Yihao Feng, Zuxin Liu, Weiran Yao, Akshara Prabhakar, Shelby Heinecke, Ricky Ho, Phil Mui, Silvio Savarese, Caiming Xiong, Huan Wang._ Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/SalesforceAIResearch/LaTRO)](https://github.com/SalesforceAIResearch/LaTRO)

2. [**Training Large Language Models to Reason in a Continuous Latent Space.**](https://arxiv.org/abs/2412.06769) _Shibo Hao, Sainbayar Sukhbaatar, DiJia Su, Xian Li, Zhiting Hu, Jason Weston, Yuandong Tian._ Arxiv 2024. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/coconut)](https://github.com/facebookresearch/coconut)

3. [**Deliberation in Latent Space via Differentiable Cache Augmentation.**](https://arxiv.org/abs/2412.17747) _Luyang Liu, Jonas Pfeiffer, Jiaxing Wu, Jun Xie, Arthur Szlam._ Arxiv 2024.

4. [**Compressed Chain of Thought: Efficient Reasoning Through Dense Representations.**](https://arxiv.org/abs/2412.13171) _Jeffrey Cheng, Benjamin Van Durme._ Arxiv 2024.

5. [**Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach.**](https://arxiv.org/abs/2502.05171) _Jonas Geiping, Sean McLeish, Neel Jain, John Kirchenbauer, Siddharth Singh, Brian R. Bartoldson, Bhavya Kailkhura, Abhinav Bhatele, Tom Goldstein._ Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/seal-rg/recurrent-pretraining)](https://github.com/seal-rg/recurrent-pretraining)

6. [**Reasoning with Latent Thoughts: On the Power of Looped Transformers.**](https://arxiv.org/abs/2502.17416) _Nikunj Saunshi, Nishanth Dikkala, Zhiyuan Li, Sanjiv Kumar, Sashank J. Reddi._ Arxiv 2025.

7. [**Human Preferences in Large Language Model Latent Space: A Technical Analysis on the Reliability of Synthetic Data in Voting Outcome Prediction.**](https://arxiv.org/abs/2502.16280) _Sarah Ball, Simeon Allmendinger, Frauke Kreuter, Niklas Kühl._ Arxiv 2025.

8. [**CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation.**](https://arxiv.org/abs/2502.21074) _Zhenyi Shen, Hanqi Yan, Linhai Zhang, Zhanghao Hu, Yali Du, Yulan He._ Arxiv 2025.

9. [**LLM Pretraining with Continuous Concepts.**](https://arxiv.org/abs/2502.08524) _Jihoon Tack, Jack Lanchantin, Jane Yu, Andrew Cohen, Ilia Kulikov, Janice Lan, Shibo Hao, Yuandong Tian, Jason Weston, Xian Li._ Arxiv 2025. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/RAM)](https://github.com/facebookresearch/RAM/tree/main/projects/cocomix)

10. [**Soft Thinking: Unlocking the Reasoning Potential of LLMs in Continuous Concept Space.**](https://arxiv.org/abs/2505.15778) _Zhen Zhang, Xuehai He, Weixiang Yan, Ao Shen, Chenyang Zhao, Shuohang Wang, Yelong Shen, Xin Eric Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/eric-ai-lab/Soft-Thinking)](https://github.com/eric-ai-lab/Soft-Thinking)

11. [**Mitigating Visual Forgetting via Take-along Visual Conditioning for Multi-modal Long CoT Reasoning.**](https://arxiv.org/abs/2503.13360) _Hai-Long Sun, Zhun Sun, Houwen Peng, Han-Jia Ye._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/sun-hailong/TVC)](https://github.com/sun-hailong/TVC)

12. [**LongPerceptualThoughts: Distilling System-2 Reasoning for System-1 Perception.**](https://arxiv.org/abs/2504.15362) _Yuan-Hong Liao, Sven Elflein, Liu He, Laura Leal-Taixé, Yejin Choi, Sanja Fidler, David Acuna._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/andrewliao11/LongPerceptualThoughts)](https://github.com/andrewliao11/LongPerceptualThoughts)

13. [**Self-Prophetic Decoding to Unlock Visual Search in LVLMs.**](https://arxiv.org/abs/2605.28741) _Zhendong He, Qiyuan Dai, Guanbin Li, Liang Lin, Sibei Yang._ ICML 2026.

14. [**Attention-guided Fine-tuning of Multimodal Large Language Models Improves Chain-of-Thought Reasoning.**](https://arxiv.org/abs/2606.01558) _Sanchit Sinha, Guangzhi Xiong, Bohan Liu, Zhenghao He, Aidong Zhang._ Arxiv 2026.

15. [**Demystifying Hidden-State Recurrence: Switchable Latent Reasoning with On-Policy Reinforcement Learning.**](https://arxiv.org/abs/2606.13106) _Jiayu Yang, Chao Chen, Shengen Wu, Yinhong Liu, Yuxuan Fan, Lujundong Li, Songning Lai, Chengwei Qin, Zhijiang Guo._ Arxiv 2026.

16. [**CARE: Competence-Aware Reward Shaping for Adaptive Reasoning Length in Video-MLLMs.**](https://arxiv.org/abs/2606.19927) _Chengwen Liu, Hao Peng, Jisheng Dang, Hong Peng, Bin Hu, Tat-Seng Chua._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/1Pansy/Video-CARE)](https://github.com/1Pansy/Video-CARE)

17. [**CoLT: Teaching Multi-Modal Models to Think with Chain of Latent Thoughts.**](https://arxiv.org/abs/2606.31986) _Lianyu Hu, Shengqian Qin, Zeqin Liao, Qing Guo, Liang Wan, Wei Feng, Yang Liu._ ECCV 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/hulianyuyy/CoLT)](https://github.com/hulianyuyy/CoLT)

18. [**TARPO: Token-Wise Latent-Explicit Reasoning via Action-Routing Policy Optimization.**](https://arxiv.org/abs/2606.05859) _Liting Zhang, Shiwan Zhao, Xuyang Zhao, Zichen Xu, Jianye Wang, Qicheng Li._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/NKU-LITI/TARPO-master)](https://github.com/NKU-LITI/TARPO-master)

19. [**Chained Recursive Language Models for Multi-Iteration Reasoning.**](https://arxiv.org/abs/2608.05124) _Purbesh Mitra, Sennur Ulukus._ Arxiv 2026.

20. [**AdaThinkV: Adaptive Thinking for Token-Efficient Video Reasoning.**](https://arxiv.org/abs/2608.01980) _Jingqi Tian, Haoji Zhang, Lin Chen, Hongbo Jin, Haonan Xu, Tianrui Zhu, Xingming Shui, Shilin Ma, Wenjing Yang, Yansong Tang._ Arxiv 2026. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://trilarflagz.github.io/AdaThinkV/)

#### 13.5 Long-CoT Training, Distillation & Analysis

1. [**When More is Less: Understanding Chain-of-Thought Length in LLMs.**](https://arxiv.org/abs/2502.07266) _Yuyang Wu, Yifei Wang, Tianqi Du, Stefanie Jegelka, Yisen Wang._ Arxiv 2025.

2. [**LLMs Can Easily Learn to Reason from Demonstrations Structure, not content, is what matters!.**](https://arxiv.org/abs/2502.07374) _Dacheng Li, Shiyi Cao, Tyler Griggs, Shu Liu, Xiangxi Mo, Shishir G. Patil, Matei Zaharia, Joseph E. Gonzalez, Ion Stoica._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NovaSky-AI/SkyThought)](https://github.com/NovaSky-AI/SkyThought)

3. [**Monte Carlo Tree Diffusion for System 2 Planning.**](https://arxiv.org/abs/2502.07202) _Jaesik Yoon, Hyeonseo Cho, Doojin Baek, Yoshua Bengio, Sungjin Ahn._ Arxiv 2025.

4. [**Enhancing Auto-regressive Chain-of-Thought through Loop-Aligned Reasoning.**](https://arxiv.org/abs/2502.08482) _Qifan Yu, Zhenyu He, Sijie Li, Xun Zhou, Jun Zhang, Jingjing Xu, Di He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/qifanyu/RELAY)](https://github.com/qifanyu/RELAY)

5. [**DRT: Deep Reasoning Translation via Long Chain-of-Thought.**](https://arxiv.org/abs/2412.17498) _Jiaan Wang, Fandong Meng, Yunlong Liang, Jie Zhou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/krystalan/DRT-o1)](https://github.com/krystalan/DRT-o1)

6. [**O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple Distillation, Big Progress or Bitter Lesson?.**](https://arxiv.org/abs/2411.16489) _Zhen Huang, Haoyang Zou, Xuefeng Li, Yixiu Liu, Yuxiang Zheng, Ethan Chern, Shijie Xia, Yiwei Qin, Weizhe Yuan, Pengfei Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/O1-Journey)](https://github.com/GAIR-NLP/O1-Journey)

7. [**Dynamic Chain-of-Thought: Towards Adaptive Deep Reasoning.**](https://arxiv.org/abs/2502.10428) _Libo Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/brucewang123456789/GeniusTrail)](https://github.com/brucewang123456789/GeniusTrail/tree/main/Dynamic%20CoT)

8. [**SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities.**](https://arxiv.org/abs/2502.12025) _Fengqing Jiang, Zhangchen Xu, Yuetai Li, Luyao Niu, Zhen Xiang, Bo Li, Bill Yuchen Lin, Radha Poovendran._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://safe-chain.github.io/)

9. [**Towards Thinking-Optimal Scaling of Test-Time Compute for LLM Reasoning.**](https://arxiv.org/abs/2502.18080) _Wenkai Yang, Shuming Ma, Yankai Lin, Furu Wei._ Arxiv 2025.

10. [**Towards Widening The Distillation Bottleneck for Reasoning Models.**](https://arxiv.org/abs/2503.01461) _Huifeng Yin, Yu Zhao, Minghao Wu, Xuanfan Ni, Bo Zeng, Hao Wang, Tianqi Shi, Liangying Shao, Chenyang Lyu, Longyue Wang, Weihua Luo, Kaifu Zhang._ Arxiv 2025.

11. [**MA-LoT: Multi-Agent Lean-based Long Chain-of-Thought Reasoning enhances Formal Theorem Proving.**](https://arxiv.org/abs/2503.03205) _Ruida Wang, Rui Pan, Yuxin Li, Jipeng Zhang, Yizhen Jia, Shizhe Diao, Renjie Pi, Junjie Hu, Tong Zhang._ Arxiv 2025.

12. [**START: Self-taught Reasoner with Tools.**](https://arxiv.org/abs/2503.04625) _Chengpeng Li, Mingfeng Xue, Zhenru Zhang, Jiaxi Yang, Beichen Zhang, Xiang Wang, Bowen Yu, Binyuan Hui, Junyang Lin, Dayiheng Liu._ Arxiv 2025.

13. [**InftyThink: Breaking the Length Limits of Long-Context Reasoning in Large Language Models.**](https://arxiv.org/abs/2503.06692) _Yuchen Yan, Yongliang Shen, Yang Liu, Jin Jiang, Mengdi Zhang, Jian Shao, Yueting Zhuang._ Arxiv 2025.

14. [**Attention Reveals More Than Tokens: Training-Free Long-Context Reasoning with Attention-guided Retrieval.**](https://arxiv.org/abs/2503.09819) _Yuwei Zhang, Jayanth Srinivasa, Gaowen Liu, Jingbo Shang._ Arxiv 2025.

15. [**"Well, Keep Thinking": Enhancing LLM Reasoning with Adaptive Injection Decoding.**](https://arxiv.org/abs/2503.10167) _Hyunbin Jin, Je Won Yeom, Seunghyun Bae, Taesup Kim._ Arxiv 2025.

16. [**Unlocking General Long Chain-of-Thought Reasoning Capabilities of Large Language Models via Representation Engineering.**](https://arxiv.org/abs/2503.11314) _Xinyu Tang, Xiaolei Wang, Zhihao Lv, Yingqian Min, Wayne Xin Zhao, Binbin Hu, Ziqi Liu, Zhiqiang Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/txy77/GLoRE)](https://github.com/txy77/GLoRE)

17. [**Large Reasoning Models in Agent Scenarios: Exploring the Necessity of Reasoning Capabilities.**](https://arxiv.org/abs/2503.11074) _Xueyang Zhou, Guiyao Tie, Guowen Zhang, Weidong Wang, Zhigang Zuo, Di Wu, Duanfeng Chu, Pan Zhou, Lichao Sun, Neil Zhenqiang Gong._ Arxiv 2025.

18. [**Long Is More Important Than Difficult for Training Reasoning Models.**](https://arxiv.org/abs/2503.18069) _Si Shen, Fei Huang, Zhixiao Zhao, Chang Liu, Tiansheng Zheng, Danhao Zhu._ Arxiv 2025.

19. [**TwT: Thinking without Tokens by Habitual Reasoning Distillation with Multi-Teachers' Guidance.**](https://arxiv.org/abs/2503.24198) _Jingxian Xu, Mengyu Zhou, Weichang Liu, Hanbing Liu, Shi Han, Dongmei Zhang._ Arxiv 2025.

20. [**SKIntern: Internalizing Symbolic Knowledge for Distilling Better CoT Capabilities into Small Language Models.**](https://aclanthology.org/2025.coling-main.215/) _Huanxuan Liao, Shizhu He, Yupu Hao, Xiang Li, Yuanzhe Zhang, Jun Zhao, Kang Liu._ COLING 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/SKIntern)](https://github.com/Xnhyacinth/SKIntern)

21. [**Amplify Adjacent Token Differences: Enhancing Long Chain-of-Thought Reasoning with Shift-FFN.**](https://arxiv.org/abs/2505.17153) _Yao Xu, Mingyu Xu, Fangyu Lei, Wangtao Sun, Xiangrong Zeng, Bingning Wang, Guang Liu, Shizhu He, Jun Zhao, Kang Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongyi-Zhiwen/Shift-FFN](https://anonymous.4open.science/r/Shift-FFN)

22. [**Demystifying Reasoning Dynamics with Mutual Information: Thinking Tokens are Information Peaks in LLM Reasoning.**](https://arxiv.org/abs/2506.02867) _Chen Qian, Dongrui Liu, Haochen Wen, Zhen Bai, Yong Liu, Jing Shao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ChnQ/MI-Peaks)](https://github.com/ChnQ/MI-Peaks)

23. [**Through the Valley: Path to Effective Long CoT Training for Small Language Models.**](https://arxiv.org/abs/2506.07712) _Renjie Luo, Jiaxi Li, Chen Huang, Wei Lu._ Arxiv 2025.

24. [**Wait, We Don't Need to "Wait"! Removing Thinking Tokens Improves Reasoning Efficiency.**](https://arxiv.org/abs/2506.08343) _Chenlong Wang, Yuanning Feng, Dongping Chen, Zhaoyang Chu, Ranjay Krishna, Tianyi Zhou._ Arxiv 2025.

25. [**CoT-Valve: Length-Compressible Chain-of-Thought Tuning.**](https://arxiv.org/abs/2502.09601) _Xinyin Ma, Guangnian Wan, Runpeng Yu, Gongfan Fang, Xinchao Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/CoT-Valve)](https://github.com/horseee/CoT-Valve)

26. [**DRP: Distilled Reasoning Pruning with Skill-aware Step Decomposition for Efficient Large Reasoning Models.**](https://arxiv.org/abs/2505.13975) _Yuxuan Jiang, Dawei Li, Frank Ferraro._ Arxiv 2025.

27. [**Between Underthinking and Overthinking: An Empirical Study of Reasoning Length and correctness in LLMs.**](https://arxiv.org/abs/2505.00127) _Jinyan Su, Jennifer Healey, Preslav Nakov, Claire Cardie._ Arxiv 2025.

28. [**Do NOT Think That Much for 2+3=? On the Overthinking of o1-Like LLMs.**](https://arxiv.org/abs/2412.21187) _Xingyu Chen, Jiahao Xu, Tian Liang, Zhiwei He, Jianhui Pang, Dian Yu, Linfeng Song, Qiuzhi Liu, Mengfei Zhou, Zhuosheng Zhang, Rui Wang, Zhaopeng Tu, Haitao Mi, Dong Yu._ Arxiv 2024.

29. [**Thinking Slow, Fast: Scaling Inference Compute with Distilled Reasoners.**](https://arxiv.org/abs/2502.20339) _Daniele Paliotta, Junxiong Wang, Matteo Pagliardini, Kevin Y. Li, Aviv Bick, J. Zico Kolter, Albert Gu, François Fleuret, Tri Dao._ Arxiv 2025.

30. [**IS-CoT: Breaking the Long-form Generation Collapse via Interleaved Structural Thinking.**](https://arxiv.org/abs/2606.09709) _Zechen Sun, Yuyang Sun, Zecheng Tang, Juntao Li, Wenpeng Hu, Wenliang Chen, Zhunchen Luo, Guotong Geng, Min Zhang._ ACL 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/zechensun/IS-CoT)](https://github.com/zechensun/IS-CoT)

31. [**BOLT: Bootstrap Long Chain-of-Thought in Language Models without Distillation.**](https://arxiv.org/abs/2502.03860) _Bo Pang, Hanze Dong, Jiacheng Xu, Silvio Savarese, Yingbo Zhou, Caiming Xiong._ Arxiv 2025.

32. [**Demystifying Long Chain-of-Thought Reasoning in LLMs.**](https://arxiv.org/abs/2502.03373) _Edward Yeo, Yuxuan Tong, Morry Niu, Graham Neubig, Xiang Yue._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/eddycmu/demystify-long-cot)](https://github.com/eddycmu/demystify-long-cot)

33. [**Dissecting Long Reasoning Models: An Empirical Study.**](https://arxiv.org/abs/2506.04913) _Yongyu Mu, Jiali Zeng, Bei Li, Xinyan Guan, Fandong Meng, Jie Zhou, Tong Xiao, Jingbo Zhu._ Arxiv 2025.

34. [**Chain-of-Thought Matters: Improving Long-Context Language Models with Reasoning Path Supervision.**](https://arxiv.org/abs/2502.20790) _Dawei Zhu, Xiyu Wei, Guangxiang Zhao, Wenhao Wu, Haosheng Zou, Junfeng Ran, Xun Wang, Lin Sun, Xiangzheng Zhang, Sujian Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lemon-prog123/LongRePS)](https://github.com/lemon-prog123/LongRePS)

35. [**CGMIS: Concept-Graph Based Multi-Hop Instructions Synthesis for Enhancing Long-Context Reasoning.**](https://ojs.aaai.org/index.php/AAAI/article/view/40599) _Zechen Sun, Zecheng Tang, Juntao Li, Wenpeng Hu, Wenliang Chen, Zhunchen Luo, Qiaoming Zhu._ AAAI 2026.

36. [**SimpleOPD: Simple Tokenizer-Agnostic On-Policy Distillation for Long-Context Reasoning.**](https://arxiv.org/abs/2608.14277) _Haonan He, Haodi Lei, Yun Luo, Haoran Zhang, Shunkai Zhang, Yizhuo Li, Shengji Tang, Zhilin Wang, Runzhe Zhan, Lei Bai, Ganqu Cui, Fangchen Yu, Yafu Li, Peng Ye, Ning Ding, Yu Cheng._ Arxiv 2026.

37. [**Towards Understanding On-Policy Distillation through the Lens of Test-Time Scaling.**](https://arxiv.org/abs/2608.11829) _Xinmu Ge, Zizhuo Zhang, Yu Huang, Jianing Zhu, Lin Yuan, Wanli Gu, Weichang Wu, Weiran Huang, Xiaolu Zhang, Bo Han, Jun Zhou, Jiangchao Yao._ Arxiv 2026.
