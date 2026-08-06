# 3. KV-Cache Optimization

[← Back to README](../README.md#-papers)

#### 3.1 Eviction / Selection

##### 3.1.1 Attention-Score & Heavy-Hitter Eviction

1. [**SnapKV: LLM Knows What You are Looking for Before Generation.**](https://arxiv.org/abs/2404.14469) _Yuhong Li, Yingbing Huang, Bowen Yang, Bharat Venkitesh, Acyr Locatelli, Hanchen Ye, Tianle Cai, Patrick Lewis, Deming Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FasterDecoding/SnapKV)](https://github.com/FasterDecoding/SnapKV)

2. [**Model Tells You What to Discard: Adaptive KV Cache Compression for LLMs.**](https://openreview.net/forum?id=uNrFpDPMyo) _Suyu Ge, Yunan Zhang, Liyuan Liu, Minjia Zhang, Jiawei Han, Jianfeng Gao._ ICLR 2024 Oral.

3. [**Keyformer: KV Cache Reduction through Key Tokens Selection for Efficient Generative Inference.**](https://arxiv.org/abs/2403.09054) _Muhammad Adnan, Akhil Arunkumar, Gaurav Jain, Prashant J. Nair, Ilya Soloveychik, Purushotham Kamath._ Arxiv 2024.

4. [**A Simple and Effective L2 Norm-Based Strategy for KV Cache Compression.**](https://arxiv.org/abs/2406.11430) _Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini._ Arxiv 2024.

5. [**Attention Score is not All You Need for Token Importance Indicator in KV Cache Reduction: Value Also Matters.**](https://arxiv.org/abs/2406.12335) _Zhiyu Guo, Hidetaka Kamigaito, Taro Watanabe._ Arxiv 2024.

6. [**LazyLLM: Dynamic Token Pruning for Efficient Long Context LLM Inference.**](https://arxiv.org/abs/2407.14057) _Qichen Fu, Minsik Cho, Thomas Merth, Sachin Mehta, Mohammad Rastegari, Mahyar Najibi._ Arxiv 2024.

7. [**A2SF: Accumulative Attention Scoring with Forgetting Factor for Token Pruning in Transformer Decoder.**](https://arxiv.org/abs/2407.20485) _Hyun-rae Jo, Dongkun Shin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Dirac-Notation/A2SF)](https://github.com/Dirac-Notation/A2SF)

8. [**NACL: A General and Effective KV Cache Eviction Framework for LLMs at Inference Time.**](https://arxiv.org/abs/2408.03675) _Yilong Chen, Guoxia Wang, Junyuan Shang, Shiyao Cui, Zhenyu Zhang, Tingwen Liu, Shuohuan Wang, Yu Sun, Dianhai Yu, Hua Wu._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/PaddlePaddle/Research)](https://github.com/PaddlePaddle/Research/tree/master/NLP/ACL2024-NACL)

9. [**BUZZ: Beehive-structured Sparse KV Cache with Segmented Heavy Hitters for Efficient LLM Inference.**](https://arxiv.org/abs/2410.23079) _Junqi Zhao, Zhijin Fang, Shu Li, Shaohui Yang, Shichao He._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JunqiZhao888/buzz-llm)](https://github.com/JunqiZhao888/buzz-llm)

10. [**TokenSelect: Efficient Long-Context Inference and Length Extrapolation for LLMs via Dynamic Token-Level KV Cache Selection.**](https://arxiv.org/abs/2411.02886) _Wei Wu, Zhuoshi Pan, Chao Wang, Liyi Chen, Yunchu Bai, Kun Fu, Zheng Wang, Hui Xiong._ Arxiv 2024.

11. [**Recycled Attention: Efficient inference for long-context language models.**](https://arxiv.org/abs/2411.05787) _Fangyuan Xu, Tanya Goyal, Eunsol Choi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/carriex/recycled-attention)](https://github.com/carriex/recycled-attention)

12. [**Squeezed Attention: Accelerating Long Context Length LLM Inference.**](https://arxiv.org/abs/2411.09688) _Coleman Hooper, Sehoon Kim, Hiva Mohammadzadeh, Monishwaran Maheswaran, June Paik, Michael W. Mahoney, Kurt Keutzer, Amir Gholami._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SqueezeAILab/SqueezedAttention)](https://github.com/SqueezeAILab/SqueezedAttention)

13. [**SparseAccelerate: Efficient Long-Context Inference for Mid-Range GPUs.**](https://arxiv.org/abs/2412.06198) _James Vo._ Arxiv 2024.

14. [**SCOPE: Optimizing Key-Value Cache Compression in Long-context Generation.**](https://arxiv.org/abs/2412.13649) _Jialong Wu, Zhenglin Wang, Linhai Zhang, Yilong Lai, Yulan He, Deyu Zhou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Linking-ai/SCOPE)](https://github.com/Linking-ai/SCOPE)

15. [**FastKV: KV Cache Compression for Fast Long-Context Processing with Token-Selective Propagation.**](https://arxiv.org/abs/2502.01068) _Dongwon Jo, Jiwon Song, Yulhwa Kim, Jae-Joon Kim._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/dongwonjo/FastKV)](https://github.com/dongwonjo/FastKV)

16. [**Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective.**](https://arxiv.org/abs/2502.03805) _Yuan Feng, Junlin Lv, Yukun Cao, Xike Xie, S Kevin Zhou._ Arxiv 2025.

17. [**Exploiting Sparsity for Long Context Inference: Million Token Contexts on Commodity GPUs.**](https://arxiv.org/abs/2502.06766) _Ryan Synk, Monte Hoover, John Kirchenbauer, Neel Jain, Alex Stein, Manli Shu, Josue Melendez Sanchez, Ramani Duraiswami, Tom Goldstein._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ryansynk/topk-decoding)](https://github.com/ryansynk/topk-decoding)

18. [**Q-Filters: Leveraging QK Geometry for Efficient KV Cache Compression.**](https://arxiv.org/abs/2503.02812) _Nathan Godey, Alessio Devoto, Yu Zhao, Simone Scardapane, Pasquale Minervini, Éric de la Clergerie, Benoît Sagot._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NathanGodey/qfilters)](https://github.com/NathanGodey/qfilters)

19. [**LLMs Know What to Drop: Self-Attention Guided KV Cache Eviction for Efficient Long-Context Inference.**](https://arxiv.org/abs/2503.08879) _Guangtao Wang, Shubhangi Upasani, Chen Wu, Darshan Gandhi, Jonathan Li, Changran Hu, Bo Li, Urmish Thakker._ ICLR 2025.

20. [**LagKV: Lag-Relative Information of the KV Cache Tells Which Tokens Are Important.**](https://arxiv.org/abs/2504.04704) _Manlai Liang, JiaMing Zhang, Xiong Li, Jinlong Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AI-Lab-China-Merchants-Bank/LagKV)](https://github.com/AI-Lab-China-Merchants-Bank/LagKV)

21. [**KeepKV: Eliminating Output Perturbation in KV Cache Compression for Efficient LLMs Inference.**](https://arxiv.org/abs/2504.09936) _Yuxuan Tian, Zihan Wang, Yebo Peng, Aomufei Yuan, Zhiming Wang, Bairen Yi, Xin Liu, Yong Cui, Tong Yang._ Arxiv 2025.

22. [**CAOTE: KV Caching through Attention Output Error based Token Eviction.**](https://arxiv.org/abs/2504.14051) _Raghavv Goel, Junyoung Park, Mukul Gagrani, Dalton Jones, Matthew Morse, Harper Langston, Mingu Lee, Chris Lott._ Arxiv 2025.

23. [**Mustafar: Promoting Unstructured Sparsity for KV Cache Pruning in LLM Inference.**](https://arxiv.org/abs/2505.22913) _Donghyeon Joo, Helya Hosseini, Ramyad Hadidi, Bahar Asgari._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/dhjoo98/mustafar)](https://github.com/dhjoo98/mustafar)

24. [**AhaKV: Adaptive Holistic Attention-Driven KV Cache Eviction for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2506.03762) _Yifeng Gu, Zicong Jiang, Jianxiu Jin, Kailing Guo, Ziyang Zhang, Xiangmin Xu._ Arxiv 2025.

25. [**Multipole Attention for Efficient Long Context Reasoning.**](https://arxiv.org/abs/2506.13059) _Coleman Hooper, Sebastian Zhao, Luca Manolache, Sehoon Kim, Michael W. Mahoney, Yakun Sophia Shao, Kurt Keutzer, Amir Gholami._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SqueezeAILab/MultipoleAttention)](https://github.com/SqueezeAILab/MultipoleAttention)

26. [**LazyEviction: Lagged KV Eviction with Attention Pattern Observation for Efficient Long Reasoning.**](https://arxiv.org/abs/2506.15969) _Haoyue Zhang, Hualei Zhang, Xiaosong Ma, Jie Zhang, Song Guo._ Arxiv 2025.

27. [**Think Clearly: Improving Reasoning via Redundant Token Pruning.**](https://arxiv.org/abs/2507.08806) _Daewon Choi, Jimin Lee, Jihoon Tack, Woomin Song, Saket Dingliwal, Sai Muralidhar Jayanthi, Bhavana Ganesh, Jinwoo Shin, Aram Galstyan, Sravan Babu Bodapati._ Arxiv 2025.

28. [**SlimInfer: Accelerating Long-Context LLM Inference via Dynamic Token Pruning.**](https://arxiv.org/abs/2508.06447) _Lingkun Long, Rubing Yang, Yushi Huang, Desheng Hui, Ao Zhou, Jianlei Yang._ Arxiv 2025.

29. [**Retrospective Sparse Attention for Efficient Long-Context Generation.**](https://arxiv.org/abs/2508.09001) _Seonghwan Choi, Beomseok Kang, Dongwon Jo, Jae-Joon Kim._ Arxiv 2025.

30. [**Value-Aware Stochastic KV Cache Eviction for Reasoning Models.**](https://arxiv.org/abs/2606.03928) _Ting-Yun Chang, Harvey Yiyun Fu, Deqing Fu, Chenghao Yang, Jesse Thomason, Robin Jia._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/terarachang/VaSE)](https://github.com/terarachang/VaSE)

31. [**IntentKV: Cross-Turn Intent-Aware KV Cache Pruning for Agent Inference.**](https://arxiv.org/abs/2606.09916) _Junjie Li, Jiong Lou, Jie Li._ Arxiv 2026.

32. [**FlashMemory-DeepSeek-V4: Lightning Index Ultra-Long Context via Lookahead Sparse Attention.**](https://arxiv.org/abs/2606.09079) _Yan Wang, Qifan Zhang, Jiachen Yu, Tian Liang, Dongyang Ma, Xiang Hu, Zibo Lin, Chunyang Li, Zhichao Wang, Miao Peng, Nuo Chen, Jia Li, Yujiu Yang, Haitao Mi, Dong Yu._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/libertywing/FlashMemory-Deepseek-V4)](https://github.com/libertywing/FlashMemory-Deepseek-V4)

33. [**MemDecay: Region-Aware KV Cache Eviction for Efficient LLM Agent Inference.**](https://arxiv.org/abs/2607.10582) _Venkatesha Matam, Keon Kim._ Arxiv 2026.

34. [**KVpop -- Key-Value Cache Compression with Predictive Online Pruning.**](https://arxiv.org/abs/2607.05061) _Lukas Hauzenberger, Niklas Schmidinger, Anamaria-Roberta Hartl, David Stap, Thomas Schmied, Sebastian Böck, Günter Klambauer, Sepp Hochreiter._ Arxiv 2026.

35. [**CONF-KV: Confidence-Aware KV Cache Eviction with Mixed-Precision Storage for Long-Horizon LLM.**](https://arxiv.org/abs/2605.24786) _Yubo Li, Yidi Miao._ Arxiv 2026.

##### 3.1.2 Streaming & Sliding-Window Retention

1. [**Training-Free Exponential Extension of Sliding Window Context with Cascading KV Cache.**](https://arxiv.org/abs/2406.17808) _Jeffrey Willette, Heejun Lee, Youngwan Lee, Myeongjae Jeon, Sung Ju Hwang._ Arxiv 2024.

2. [**Farewell to Length Extrapolation, a Training-Free Infinite Context with Finite Attention Scope.**](https://arxiv.org/abs/2407.15176) _Xiaoran Liu, Qipeng Guo, Yuerong Song, Zhigeng Liu, Kai Lv, Hang Yan, Linlin Li, Qun Liu, Xipeng Qiu._ Arxiv 2024.

3. [**Ltri-LLM: Streaming Long Context Inference for LLMs with Training-Free Dynamic Triangular Attention Pattern.**](https://arxiv.org/abs/2412.04757) _Hongyin Tang, Di Xiu, Lanrui Wang, Xiurui Geng, Jingang Wang, Xunliang Cai._ Arxiv 2024.

4. [**SepLLM: Accelerate Large Language Models by Compressing One Segment into One Separator.**](https://arxiv.org/abs/2412.12094) _Guoxuan Chen, Han Shi, Jiawei Li, Yihang Gao, Xiaozhe Ren, Yimeng Chen, Xin Jiang, Zhenguo Li, Weiyang Liu, Chao Huang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HKUDS/SepLLM)](https://github.com/HKUDS/SepLLM)

5. [**Round Attention: A Novel Round-Level Attention Mechanism to Accelerate LLM Inference.**](https://arxiv.org/abs/2502.15294) _Yaohua Tang, Zhicheng Hu, Kun Cheng, Fan Mo, Qiheng Lv, Hua Wang, Zhi Chen._ Arxiv 2025.

6. [**Dialogue Without Limits: Constant-Sized KV Caches for Extended Responses in LLMs.**](https://arxiv.org/abs/2503.00979) _Ravi Ghadia, Avinash Kumar, Gaurav Jain, Prashant Nair, Poulami Das._ Arxiv 2025.

7. [**WindowKV: Task-Adaptive Group-Wise KV Cache Window Selection for Efficient LLM Inference.**](https://arxiv.org/abs/2503.17922) _Youhui Zuo, Sibo Wei, Chen Zhang, Zhuorui Liu, Wenpeng Lu, Dawei Song._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/optim996/WindowKV)](https://github.com/optim996/WindowKV)

##### 3.1.3 Query-Aware & Learnable Retention

1. [**Quest: Query-Aware Sparsity for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2406.10774) _Jiaming Tang, Yilong Zhao, Kan Zhu, Guangxuan Xiao, Baris Kasikci, Song Han._ ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/Quest)](https://github.com/mit-han-lab/Quest)

2. [**CItruS: Chunked Instruction-aware State Eviction for Long Sequence Modeling.**](https://arxiv.org/abs/2406.12018) _Yu Bai, Xiyuan Zou, Heyan Huang, Sanxing Chen, Marc-Antoine Rondeau, Yang Gao, Jackie Chi Kit Cheung._ Arxiv 2024.

3. [**QuickLLaMA: Query-aware Inference Acceleration for Large Language Models.**](https://arxiv.org/abs/2406.07528) _Jingyao Li, Han Shi, Xin Jiang, Zhenguo Li, Hong Xu, Jiaya Jia._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/Q-LLM)](https://github.com/dvlab-research/Q-LLM)

4. [**RazorAttention: Efficient KV Cache Compression Through Retrieval Heads.**](https://arxiv.org/abs/2407.15891) _Hanlin Tang, Yang Lin, Jing Lin, Qingsen Han, Shikuan Hong, Yiwu Yao, Gongyi Wang._ Arxiv 2024.

5. [**ThinK: Thinner Key Cache by Query-Driven Pruning.**](https://arxiv.org/abs/2407.21018) _Yuhui Xu, Zhanming Jie, Hanze Dong, Lei Wang, Xudong Lu, Aojun Zhou, Amrita Saha, Caiming Xiong, Doyen Sahoo._ ICLR 2025.

6. [**CSKV: Training-Efficient Channel Shrinking for KV Cache in Long-Context Scenarios.**](https://arxiv.org/abs/2409.10593) _Luning Wang, Shiyao Li, Xuefei Ning, Zhihang Yuan, Shengen Yan, Guohao Dai, Yu Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/wln20/cskv)](https://github.com/wln20/cskv/)

7. [**Locret: Enhancing Eviction in Long-Context LLM Inference with Trained Retaining Heads.**](https://arxiv.org/abs/2410.01805) _Yuxiang Huang, Binhang Yuan, Xu Han, Chaojun Xiao, Zhiyuan Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/huangyuxiang03/Locret)](https://github.com/huangyuxiang03/Locret)

8. [**DuoAttention: Efficient Long-Context LLM Inference with Retrieval and Streaming Heads.**](https://arxiv.org/abs/2410.10819) _Guangxuan Xiao, Jiaming Tang, Jingwei Zuo, Junxian Guo, Shang Yang, Haotian Tang, Yao Fu, Song Han._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/duo-attention)](https://github.com/mit-han-lab/duo-attention)

9. [**In-context KV-Cache Eviction for LLMs via Attention-Gate.**](https://arxiv.org/abs/2410.12876) _Zihao Zeng, Bokai Lin, Tianqi Hou, Hao Zhang, Zhijie Deng._ Arxiv 2024.

10. [**Boosting Long-Context Information Seeking via Query-Guided Activation Refilling.**](https://arxiv.org/abs/2412.12486) _Hongjin Qian, Zheng Liu, Peitian Zhang, Zhicheng Dou, Defu Lian._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/qhjqhj00/activation_refilling)](https://github.com/qhjqhj00/activation_refilling)

11. [**AttentionPredictor: Temporal Pattern Matters for Efficient LLM Inference.**](https://arxiv.org/abs/2502.04077) _Qingyue Yang, Jie Wang, Xing Li, Zhihai Wang, Chen Chen, Lei Chen, Xianzhi Yu, Wulong Liu, Jianye Hao, Mingxuan Yuan, Bin Li._ Arxiv 2025.

12. [**Activation-aware Probe-Query: Effective Key-Value Retrieval for Long-Context LLMs Inference.**](https://arxiv.org/abs/2502.13542) _Qingfa Xiao, Jiachuan Wang, Haoyang Li, Cheng Deng, Jiaqi Tang, Shuangyin Li, Yongqi Zhang, Jun Wang, Lei Chen._ Arxiv 2025.

13. [**Unshackling Context Length: An Efficient Selective Attention Approach through Query-Key Compression.**](https://arxiv.org/abs/2502.14477) _Haoyu Wang, Tong Teng, Tianyu Guo, An Xiao, Duyu Tang, Hanting Chen, Yunhe Wang._ Arxiv 2025.

14. [**TokenButler: Token Importance is Predictable.**](https://arxiv.org/abs/2503.07518) _Yash Akhauri, Ahmed F AbouElhamayed, Yifei Gao, Chi-Chih Chang, Nilesh Jain, Mohamed S. Abdelfattah._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/abdelfattah-lab/TokenButler)](https://github.com/abdelfattah-lab/TokenButler)

15. [**KV-Distill: Nearly Lossless Learnable Context Compression for LLMs.**](https://arxiv.org/abs/2503.10337) _Vivek Chari, Guanghui Qin, Benjamin Van Durme._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/vnchari/kv-distill)](https://github.com/vnchari/kv-distill)

16. [**PromptDistill: Query-based Selective Token Retention in Intermediate Layers for Efficient Large Language Model Inference.**](https://arxiv.org/abs/2503.23274) _Weisheng Jin, Maojia Song, Tej Deep Pala, Yew Ken Chia, Amir Zadeh, Chuan Li, Soujanya Poria._ Arxiv 2025.

17. [**Cache Me If You Can: How Many KVs Do You Need for Effective Long-Context LMs?.**](https://arxiv.org/abs/2506.17121) _Adithya Bhaskar, Alexander Wettig, Tianyu Gao, Yihe Dong, Danqi Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-pli/PruLong)](https://github.com/princeton-pli/PruLong)

18. [**SparK: Query-Aware Unstructured Sparsity with Recoverable KV Cache Channel Pruning.**](https://arxiv.org/abs/2508.15212) _Huanxuan Liao, Yixing Xu, Shizhu He, Guanchen Li, Xuanwu Yin, Dong Li, Emad Barsoum, Jun Zhao, Kang Liu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/SparK)](https://github.com/Xnhyacinth/SparK)

19. [**LKV: End-to-End Learning of Head-wise Budgets and Token Selection for LLM KV Cache Eviction.**](https://arxiv.org/abs/2605.06676) _Enshuai Zhou, Yifan Hao, Chao Wang, Rui Zhang, Di Huang, Jiaming Guo, Xing Hu, Zidong Du, Qi Guo, Yunji Chen._ Arxiv 2026.

20. [**Neurocache: Efficient Vector Retrieval for Long-range Language Modeling.**](https://arxiv.org/abs/2407.02486) _Ali Safaya, Deniz Yuret._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alisafaya/neurocache)](https://github.com/alisafaya/neurocache)

21. [**IndexMem: Learned KV-Cache Eviction with Latent Memory for Long-Context LLM Inference.**](https://arxiv.org/abs/2605.25475) _Xintong Yang, Hao Gu, Binxing Xu, Lujun Li, Bei Liu, Jiacheng Liu, Qiyuan Zhu, Sirui Han, Yike Guo._ Arxiv 2026.

##### 3.1.4 Layer-Budget / Merge / Hybrid Eviction

1. [**GRKV: Global Regression for Training-Free KV Cache Compression in Long-Context LLMs.**](https://arxiv.org/abs/2605.31105) _Junjie Peng, You Wu, Haoyi Wu, Jialong Han, Xiaohua Xie, Kewei Tu, Jianhuang Lai._ Arxiv 2026.

2. [**WaveFilter: Enhancing the Long-Context Capability of Diffusion LLMs via Wavelet-Guided KV Cache Filtering.**](https://arxiv.org/abs/2606.00724) _Jinnan Yang, Yan Wang, Zhen Bi, Kehao Wu, Xiaojie Li, Jungang Lou, Zechao Li, Jing Liu._ Arxiv 2026.

3. [**ChunkAttention: Efficient Self-Attention with Prefix-Aware KV Cache and Two-Phase Partition.**](https://arxiv.org/abs/2402.15220) _Lu Ye, Ze Tao, Yong Huang, Yang Li._ Arxiv 2024.

4. [**Efficient LLM Inference with Kcache.**](https://arxiv.org/abs/2404.18057) _Qiaozhi He, Zhihua Wu._ Arxiv 2024.

5. [**PyramidInfer: Pyramid KV Cache Compression for High-throughput LLM Inference.**](https://arxiv.org/abs/2405.12532) _William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mutonix/pyramidinfer)](https://github.com/mutonix/pyramidinfer)

6. [**PyramidKV: Dynamic KV Cache Compression based on Pyramidal Information Funneling.**](https://arxiv.org/abs/2406.02069) _Zefan Cai., Yichi Zhang, Bofei Gao, Tianyu Liu, Keming Lu, Wayne Xiong, Yue Dong, Baobao Chang, Junjie Hu, Wen Xiao._ Arxiv 2024.

7. [**Effectively Compress KV Heads for LLM.**](https://arxiv.org/abs/2406.07056) _Hao Yu, Zelan Yang, Shen Li, Yong Li, Jianxin Wu._ Arxiv 2024.

8. [**D2O: Dynamic Discriminative Operations for Efficient Generative Inference of Large Language Models.**](https://arxiv.org/abs/2406.13035) _Zhongwei Wan, Xinjian Wu, Yu Zhang, Yi Xin, Chaofan Tao, Zhihong Zhu, Xin Wang, Siqi Luo, Jing Xiong, Mi Zhang._ Arxiv 2024.

9. [**Model Tells You Where to Merge: Adaptive KV Cache Merging for LLMs on Long-Context Tasks.**](https://arxiv.org/abs/2407.08454) _Zheng Wang, Boxiao Jin, Zhongzhi Yu, Minjia Zhang._ Arxiv 2024.

10. [**Optimizing KV Cache Eviction in LLMs: Adaptive Allocation for Enhanced Budget Utilization.**](https://arxiv.org/abs/2407.11550) _Yuan Feng, Junlin Lv, Yukun Cao, Xike Xie, S. Kevin Zhou._ Arxiv 2024.

11. [**RetrievalAttention: Accelerating Long-Context LLM Inference via Vector Retrieval.**](https://arxiv.org/abs/2409.10516) _Di Liu, Meng Chen, Baotong Lu, Huiqiang Jiang, Zhenhua Han, Qianxi Zhang, Qi Chen, Chengruidong Zhang, Bailu Ding, Kai Zhang, Chen Chen, Fan Yang, Yuqing Yang, Lili Qiu._ Arxiv 2024.

12. [**Discovering the Gems in Early Layers: Accelerating Long-Context LLMs with 1000x Input Token Reduction.**](https://arxiv.org/abs/2409.17422) _Zhenmei Shi, Yifei Ming, Xuan-Phi Nguyen, Yingyu Liang, Shafiq Joty._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SalesforceAIResearch/GemFilter)](https://github.com/SalesforceAIResearch/GemFilter)

13. [**Inference-Friendly Models With MixAttention.**](https://arxiv.org/abs/2409.15012) _Shashank Rajput, Ying Sheng, Sean Owen, Vitaliy Chiley._ Arxiv 2024.

14. [**KV-Compress: Paged KV-Cache Compression with Variable Compression Rates per Attention Head.**](https://arxiv.org/abs/2410.00161) _Isaac Rehg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/IsaacRe/vllm-kvcompress)](https://github.com/IsaacRe/vllm-kvcompress)

15. [**SimLayerKV: A Simple Framework for Layer-Level KV Cache Reduction.**](https://arxiv.org/abs/2410.13846) _Xuan Zhang, Cunxiao Du, Chao Du, Tianyu Pang, Wei Gao, Min Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/SimLayerKV)](https://github.com/sail-sg/SimLayerKV)

16. [**MagicPIG: LSH Sampling for Efficient LLM Generation.**](https://arxiv.org/abs/2410.16179) _Zhuoming Chen, Ranajoy Sadhukhan, Zihao Ye, Yang Zhou, Jianyu Zhang, Niklas Nolte, Yuandong Tian, Matthijs Douze, Leon Bottou, Zhihao Jia, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicPIG)](https://github.com/Infini-AI-Lab/MagicPIG)

17. [**Not All Heads Matter: A Head-Level KV Cache Compression Method with Integrated Retrieval and Reasoning.**](https://arxiv.org/abs/2410.19258) _Yu Fu, Zefan Cai, Abedelkadir Asi, Wayne Xiong, Yue Dong, Wen Xiao._ Arxiv 2024.

18. [**Long Sequence Modeling with Attention Tensorization: From Sequence to Tensor Learning.**](https://arxiv.org/abs/2410.20926) _Aosong Feng, Rex Ying, Leandros Tassiulas._ Arxiv 2024.

19. [**Compressing KV Cache for Long-Context LLM Inference with Inter-Layer Attention Similarity.**](https://arxiv.org/abs/2412.02252) _Da Ma, Lu Chen, Situo Zhang, Yuxun Miao, Su Zhu, Zhi Chen, Hongshen Xu, Hanqi Li, Shuai Fan, Lei Pan, Kai Yu._ Arxiv 2024.

20. [**ClusterKV: Manipulating LLM KV Cache in Semantic Space for Recallable Compression.**](https://arxiv.org/abs/2412.03213) _Guangda Liu, Chengwei Li, Jieru Zhao, Chenqi Zhang, Minyi Guo._ Arxiv 2024.

21. [**XKV: Personalized KV Cache Memory Reduction for Long-Context LLM Inference.**](https://arxiv.org/abs/2412.05896) _Weizhuo Li, Zhigang Wang, Yu Gu, Ge Yu._ Arxiv 2024.

22. [**EMS: Adaptive Evict-then-Merge Strategy for Head-wise KV Cache Compression Based on Global-Local Importance.**](https://arxiv.org/abs/2412.08521) _Yingxin Li, Ye Li, Yuan Meng, Xinzhu Ma, Zihan Geng, Shutao Xia, Zhi Wang._ Arxiv 2024.

23. [**ZigZagkv: Dynamic KV Cache Compression for Long-context Modeling based on Layer Uncertainty.**](https://arxiv.org/abs/2412.09036) _Meizhi Zhong, Xikai Liu, Chen Zhang, Yikun Lei, Yan Gao, Yao Hu, Kehai Chen, Min Zhang._ Arxiv 2024.

24. [**More Tokens, Lower Precision: Towards the Optimal Token-Precision Trade-off in KV Cache Compression.**](https://arxiv.org/abs/2412.12706) _Jiebin Zhang, Dawei Zhu, Yifan Song, Wenhao Wu, Chuqiao Kuang, Xiaoguang Li, Lifeng Shang, Qun Liu, Sujian Li._ Arxiv 2024.

25. [**DynamicKV: Task-Aware Adaptive KV Cache Compression for Long Context LLMs.**](https://arxiv.org/abs/2412.14838) _Xiabin Zhou, Wenbin Wang, Minyan Zeng, Jiaxian Guo, Xuebo Liu, Li Shen, Min Zhang, Liang Ding._ Arxiv 2024.

26. [**HashEvict: A Pre-Attention KV Cache Eviction Strategy using Locality-Sensitive Hashing.**](https://arxiv.org/abs/2412.16187) _Minghui Liu, Tahseen Rabbani, Tony O'Halloran, Ananth Sankaralingam, Mary-Anne Hartley, Brian Gravelle, Furong Huang, Cornelia Fermüller, Yiannis Aloimonos._ Arxiv 2024.

27. [**TreeKV: Smooth Key-Value Cache Compression with Tree Structures.**](https://arxiv.org/abs/2501.04987) _Ziwei He, Jian Yuan, Haoli Bai, Jingwen Leng, Bo Jiang._ Arxiv 2025.

28. [**Sigma: Differential Rescaling of Query, Key and Value for Efficient Language Models.**](https://arxiv.org/abs/2501.13629) _Zhenghao Lin, Zihao Tang, Xiao Liu, Yeyun Gong, Yi Cheng, Qi Chen, Hang Li, Ying Xin, Ziyue Yang, Kailai Yang, Yu Yan, Xiao Liang, Shuai Lu, Yiming Huang, Zheheng Luo, Lei Qu, Xuan Feng, Yaoxiang Wang, Yuqing Xia, Feiyang Chen, Yuting Jiang, Yasen Hu, Hao Ni, Binyang Li, Guoshuai Zhao, Jui-Hao Chiang, Zhongxin Guo, Chen Lin, Kun Kuang, Wenjie Li, Yelong Shen, Jian Jiao, Peng Cheng, Mao Yang._ Arxiv 2025.

29. [**CAKE: Cascading and Adaptive KV Cache Eviction with Layer Preferences.**](https://openreview.net/forum?id=EQgEMAD4kv) _Ziran Qin, Yuchen Cao, Mingbao Lin, Wen Hu, Shixuan Fan, Ke Cheng, Weiyao Lin, Jianguo Li._ ICLR 2025.

30. [**Can LLMs Maintain Fundamental Abilities under KV Cache Compression?.**](https://arxiv.org/abs/2502.01941) _Xiang Liu, Zhenheng Tang, Hong Chen, Peijie Dong, Zeyu Li, Xiuze Zhou, Bo Li, Xuming Hu, Xiaowen Chu._ Arxiv 2025.

31. [**Tactic: Adaptive Sparse Attention with Clustering and Distribution Fitting for Long-Context LLMs.**](https://arxiv.org/abs/2502.12216) _Kan Zhu, Tian Tang, Qinyu Xu, Yile Gu, Zhichen Zeng, Rohan Kadekodi, Liangyu Zhao, Ang Li, Arvind Krishnamurthy, Baris Kasikci._ Arxiv 2025.

32. [**BaKlaVa -- Budgeted Allocation of KV cache for Long-context Inference.**](https://arxiv.org/abs/2502.13176) _Ahmed Burak Gulhan, Krishna Teja Chitty-Venkata, Murali Emani, Mahmut Kandemir, Venkatram Vishwanath._ Arxiv 2025.

33. [**RocketKV: Accelerating Long-Context LLM Inference via Two-Stage KV Cache Compression.**](https://arxiv.org/abs/2502.14051) _Payman Behnam, Yaosheng Fu, Ritchie Zhao, Po-An Tsai, Zhiding Yu, Alexey Tumanov._ Arxiv 2025.

34. [**DBudgetKV: Dynamic Budget in KV Cache Compression for Ensuring Optimal Performance.**](https://arxiv.org/abs/2502.16886) _Xuanfan Ni, Liyan Xu, Chenyang Lyu, Longyue Wang, Mo Yu, Lemao Liu, Fandong Meng, Jie Zhou, Piji Li._ Arxiv 2025.

35. [**FairKV: Balancing Per-Head KV Cache for Fast Multi-GPU Inference.**](https://arxiv.org/abs/2502.15804) _Bingzhe Zhao, Ke Cheng, Aomufei Yuan, Yuxuan Tian, Ruiguang Zhong, Chengchen Hu, Tong Yang, Lian Yu._ Arxiv 2025.

36. [**CoKV: Optimizing KV Cache Allocation via Cooperative Game.**](https://arxiv.org/abs/2502.17501) _Qiheng Sun, Hongwei Zhang, Haocheng Xia, Jiayao Zhang, Jinfei Liu, Kui Ren._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/nawei1010/CoKV)](https://github.com/nawei1010/CoKV)

37. [**MEDA: Dynamic KV Cache Allocation for Efficient Multimodal Long-Context Inference.**](https://arxiv.org/abs/2502.17599) _Zhongwei Wan, Hui Shen, Xin Wang, Che Liu, Zheda Mai, Mi Zhang._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AIoT-MLSys-Lab/MEDA)](https://github.com/AIoT-MLSys-Lab/MEDA)

38. [**WeightedKV: Attention Scores Weighted Key-Value Cache Merging for Large Language Models.**](https://arxiv.org/abs/2503.01330) _Jian Yuan, Ziwei He, Haoli Bai, Jingwen Leng, Bo Jiang._ ICASSP 2025.

39. [**KVCrush: Key value cache size-reduction using similarity in head-behaviour.**](https://arxiv.org/abs/2503.00022) _Gopi Krishna Jha, Sameh Gobriel, Liubov Talamanova, Alexander Kozlov, Nilesh Jain._ Arxiv 2025.

40. [**ZeroMerge: Parameter-Free KV Cache Compression for Memory-Efficient Long-Context LLMs.**](https://arxiv.org/abs/2503.10714) _Xin Liu, Pei Liu, Guoming Tang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SusCom-Lab/ZeroMerge)](https://github.com/SusCom-Lab/ZeroMerge)

41. [**SentenceKV: Efficient LLM Inference via Sentence-Level Semantic KV Caching.**](https://arxiv.org/abs/2504.00970) _Yuxuan Zhu, Ali Falahati, David H. Yang, Mohammad Mohammadi Amiri._ Arxiv 2025.

42. [**dKV-Cache: The Cache for Diffusion Language Models.**](https://arxiv.org/abs/2505.15781) _Xinyin Ma, Runpeng Yu, Gongfan Fang, Xinchao Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/horseee/dKV-Cache)](https://github.com/horseee/dKV-Cache)

43. [**TailorKV: A Hybrid Framework for Long-Context Inference via Tailored KV Cache Optimization.**](https://arxiv.org/abs/2505.19586) _Dingyu Yao, Bowen Shen, Zheng Lin, Wei Liu, Jian Luan, Bin Wang, Weiping Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ydyhello/TailorKV)](https://github.com/ydyhello/TailorKV)

44. [**R-KV: Redundancy-aware KV Cache Compression for Training-Free Reasoning Models Acceleration.**](https://arxiv.org/abs/2505.24133) _Zefan Cai, Wen Xiao, Hanshi Sun, Cheng Luo, Yikai Zhang, Ke Wan, Yucheng Li, Yeyang Zhou, Li-Wen Chang, Jiuxiang Gu, Zhen Dong, Anima Anandkumar, Abedelkadir Asi, Junjie Hu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Zefan-Cai/R-KV)](https://github.com/Zefan-Cai/R-KV)

45. [**KVzip: Query-Agnostic KV Cache Compression with Context Reconstruction.**](https://arxiv.org/abs/2505.23416) _Jang-Hyun Kim, Jinuk Kim, Sangwoo Kwon, Jae W. Lee, Sangdoo Yun, Hyun Oh Song._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/snu-mllab/KVzip)](https://github.com/snu-mllab/KVzip)

46. [**Accelerating Diffusion Language Model Inference via Efficient KV Caching and Guided Diffusion.**](https://arxiv.org/abs/2505.21467) _Zhanqiu Hu, Jian Meng, Yash Akhauri, Mohamed S. Abdelfattah, Jae-sun Seo, Zhiru Zhang, Udit Gupta._ Arxiv 2025.

47. [**Inference-Time Hyper-Scaling with KV Cache Compression.**](https://arxiv.org/abs/2506.05345) _Adrian Łańcucki, Konrad Staniszewski, Piotr Nawrot, Edoardo M. Ponti._ Arxiv 2025.

48. [**Paged Attention Meets FlexAttention: Unlocking Long-Context Efficiency in Deployed Inference.**](https://arxiv.org/abs/2506.07311) _Thomas Joshi, Herman Saini, Neil Dhillon, Antoni Viros i Martin, Kaoutar El Maghraoui._ Arxiv 2025.

49. [**Efficient Long-Context LLM Inference via KV Cache Clustering.**](https://arxiv.org/abs/2506.11418) _Jie Hu, Shengnan Wang, Yutong He, Ping Gong, Jiawei Yi, Juncheng Zhang, Youhui Bai, Renhai Chen, Gong Zhang, Cheng Li, Kun Yuan._ Arxiv 2025.

50. [**AlayaDB: The Data Foundation for Efficient and Effective Long-context LLM Inference**](https://dl.acm.org/doi/10.1145/3722212.3724428) _Yangshen Deng, Zhengxin You, Long Xiang, Qilong Li, Peiqi Yuan, Zhaoyang Hong, Yitao Zheng, Wanting Li, Runzhong Li, Haotian Liu, Kyriakos Mouratidis, Man Lung Yiu, Huan Li, Qiaomu Shen, Rui Mao, Bo Tang._ SIGMOD 2025.

51. [**Spotlight Attention: Towards Efficient LLM Generation via Non-linear Hashing-based KV Cache Retrieval.**](https://arxiv.org/abs/2508.19740) _Wenhao Li, Yuxin Zhang, Gen Luo, Haiyuan Wan, Ziyang Gong, Fei Chao, Rongrong Ji._ Arxiv 2025.

52. [**GraphKV: Breaking the Static Selection Paradigm with Graph-Based KV Cache Eviction.**](https://arxiv.org/abs/2509.00388) _Xuelin Li, Xiangqi Jin, Linfeng Zhang._ Arxiv 2025.

53. [**KVCompose: Efficient Structured KV Cache Compression with Composite Tokens.**](https://arxiv.org/abs/2509.05165) _Dmitry Akulov, Mohamed Sana, Antonio De Domenico, Tareq Si Salem, Nicola Piovesan, Fadhel Ayed._ Arxiv 2025.

54. [**EvolKV: Evolutionary KV Cache Compression for LLM Inference.**](https://arxiv.org/abs/2509.08315) _Bohan Yu, Yekun Chai._ Arxiv 2025.

55. [**LAVa: Layer-wise KV Cache Eviction with Dynamic Budget Allocation.**](https://arxiv.org/abs/2509.09754) _Yiqun Shen, Song Yuan, Zhengze Zhang, Xiaoliang Wang, Daxin Jiang, Nguyen Cam-Tu._ Arxiv 2025.

56. [**UniGist: Towards General and Hardware-aligned Sequence-level Long Context Compression.**](https://arxiv.org/abs/2509.15763) _Chenlong Deng, Zhisong Zhang, Kelong Mao, Shuaiyi Li, Tianqing Fang, Hongming Zhang, Haitao Mi, Dong Yu, Zhicheng Dou._ Arxiv 2025.

57. [**EpiCache: Episodic KV Cache Management for Long Conversational Question Answering.**](https://arxiv.org/abs/2509.17396) _Minsoo Kim, Arnav Kundu, Hana_Byul Kim, Richa Dixit, Minsik Cho._ Arxiv 2025.

58. [**ProxyAttn: Guided Sparse Attention via Representative Heads.**](https://arxiv.org/abs/2509.24745) _Yixuan Wang, Huang He, Siqi Bao, Hua Wu, Haifeng Wang, Qingfu Zhu, Wanxiang Che._ Arxiv 2025.

59. [**VLA-Pruner: Temporal-Aware Dual-Level Visual Token Pruning for Efficient Vision-Language-Action Inference.**](https://arxiv.org/abs/2511.16449) _Ziyan Liu, Yeqiu Chen, Hongyi Cai, Tao Lin, Shuo Yang, Zheng Liu, Bo Zhao._ Arxiv 2025.

60. [**Revisiting Multimodal KV Cache Compression: A Frequency-Domain-Guided Outlier-KV-Aware Approach.**](https://arxiv.org/abs/2511.16786) _Yaoxin Yang, Peng Ye, Xudong Tan, Chongjun Tu, Maosen Zhao, Jia Hao, Tao Chen._ Arxiv 2025.

61. [**EchoKV: Efficient KV Cache Compression via Similarity-Based Reconstruction.**](https://arxiv.org/abs/2603.22910) _Yixuan Wang, Shiyu Ji, Yijun Liu, Qingfu Zhu, Wanxiang Che._ Arxiv 2026.

62. [**TriAttention: Efficient Long Reasoning with Trigonometric KV Compression.**](https://arxiv.org/abs/2604.04921) _Weian Mao, Xi Lin, Wei Huang, Yuxin Xie, Tianfu Fu, Bohan Zhuang, Song Han, Yukang Chen._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/WeianMao/triattention)](https://github.com/WeianMao/triattention)

63. [**Comparative Characterization of KV Cache Management Strategies for LLM Inference.**](https://arxiv.org/abs/2604.05012) _Oteo Mamo._ Arxiv 2026.

64. [**IceCache: Memory-efficient KV-cache Management for Long-Sequence LLMs.**](https://arxiv.org/abs/2604.10539) _Yuzhen Mao, Qitong Wang, Martin Ester, Ke Li._ Arxiv 2026. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://yuzhenmao.github.io/IceCache/)

65. [**Reformulating KV Cache Eviction Problem for Long-Context LLM Inference.**](https://arxiv.org/abs/2605.07234) _Tho Mai, Joo-Young Kim._ Arxiv 2026.

66. [**Make Each Token Count: Towards Improving Long-Context Performance with KV Cache Eviction.**](https://arxiv.org/abs/2605.09649) _Ngoc Bui, Hieu Trung Nguyen, Arman Cohan, Rex Ying._ Arxiv 2026.

67. [**Minimal-Intervention KV Retention: A Design-Space Study and a Diversity-Penalty Survivor.**](https://arxiv.org/abs/2605.14292) _Libo Sun, Po-wei Harn, Peixiong He, Xiao Qin._ Arxiv 2026.

#### 3.2 Quantization / Compression

1. [**MiniCache: KV Cache Compression in Depth Dimension for Large Language Models.**](https://arxiv.org/abs/2405.14366) _Akide Liu, Jing Liu, Zizheng Pan, Yefei He, Gholamreza Haffari, Bohan Zhuang._ NeurIPS 2024.

2. [**UNComp: Uncertainty-Aware Long-Context Compressor for Efficient Large Language Model Inference.**](https://arxiv.org/abs/2410.03090) _Jing Xiong, Jianghan Shen, Fanghua Ye, Chaofan Tao, Zhongwei Wan, Jianqiao Lu, Xun Wu, Chuanyang Zheng, Zhijiang Guo, Lingpeng Kong, Ngai Wong._ Arxiv 2024.

3. [**LoRC: Low-Rank Compression for LLMs KV Cache with a Progressive Compression Strategy.**](https://arxiv.org/abs/2410.03111) _Rongzhi Zhang, Kuang Wang, Liyuan Liu, Shuohang Wang, Hao Cheng, Chao Zhang, Yelong Shen._ Arxiv 2024.

4. [**Lossless KV Cache Compression to 2%.**](https://arxiv.org/abs/2410.15252) _Zhen Yang, J.N.Han, Kan Wu, Ruobing Xie, An Wang, Xingwu Sun, Zhanhui Kang._ Arxiv 2024.

5. [**MatryoshkaKV: Adaptive KV Compression via Trainable Orthogonal Projection.**](https://arxiv.org/abs/2410.14731) _Bokai Lin, Zihao Zeng, Zipeng Xiao, Siqi Kou, Tianqi Hou, Xiaofeng Gao, Hao Zhang, Zhijie Deng._ Arxiv 2024.

6. [**When Precision Meets Position: BFloat16 Breaks Down RoPE in Long-Context Training.**](https://arxiv.org/abs/2411.13476) _Haonan Wang, Qian Liu, Chao Du, Tongyao Zhu, Cunxiao Du, Kenji Kawaguchi, Tianyu Pang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/haonan3/AnchorContext)](https://github.com/haonan3/AnchorContext)

7. [**Pushing the Limits of LLM Inference via 2-Bit Layer-Discriminative KV Cache.**](https://arxiv.org/abs/2411.18077) _Akshat Sharma, Hangliang Ding, Jianping Li, Neel Dani, Minjia Zhang._ Arxiv 2024.

8. [**BalanceKV: KV Cache Compression through Discrepancy Theory.**](https://arxiv.org/abs/2502.07861) _Insu Han, Michael Kapralov, Ekaterina Kochetkova, Kshiteej Sheth, Amir Zandieh._ Arxiv 2025.

9. [**RoSTE: An Efficient Quantization-Aware Supervised Fine-Tuning Approach for Large Language Models.**](https://arxiv.org/abs/2502.09003) _Quan Wei, Chung-Yiu Yau, Hoi-To Wai, Yang (Katie)Zhao, Dongyeop Kang, Youngsuk Park, Mingyi Hong._ Arxiv 2025.

10. [**SVDq: 1.25-bit and 410x Key Cache Compression for LLM Attention.**](https://arxiv.org/abs/2502.15304) _Hong Yankun, Li Xing, Zhen Hui-Ling, Yu Xianzhi, Liu Wulong, Yuan Mingxuan._ Arxiv 2025.

11. [**EliteKV: Scalable KV Cache Compression via RoPE Frequency Selection and Joint Low-Rank Projection.**](https://arxiv.org/abs/2503.01586) _Yuhao Zhou, Sirui Song, Boyang Liu, Zhiheng Xi, Senjie Jin, Xiaoran Fan, Zhihao Zhang, Wei Li, Xuanjing Huang._ Arxiv 2025.

12. [**FreqKV: Frequency Domain Key-Value Compression for Efficient Context Window Extension.**](https://arxiv.org/abs/2505.00570) _Jushi Kai, Boyi Zeng, Yixuan Wang, Haoli Bai, Bo Jiang, Zhouhan Lin._ Arxiv 2025.

13. [**ReCalKV: Low-Rank KV Cache Compression via Head Reordering and Offline Calibration.**](https://arxiv.org/abs/2505.24357) _Xianglong Yan, Zhiteng Li, Tianao Zhang, Linghe Kong, Yulun Zhang, Xiaokang Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/XIANGLONGYAN/ReCalKV)](https://github.com/XIANGLONGYAN/ReCalKV)

14. [**Beyond Homogeneous Attention: Memory-Efficient LLMs via Fourier-Approximated KV Cache.**](https://arxiv.org/abs/2506.11886) _Xiaoran Liu, Siyang He, Qiqi Wang, Ruixiao Li, Yuerong Song, Zhigeng Liu, Linlin Li, Qun Liu, Zengfeng Huang, Qipeng Guo, Ziwei He, Xipeng Qiu._ Arxiv 2025.

15. [**SpindleKV: A Novel KV Cache Reduction Method Balancing Both Shallow and Deep Layers.**](https://arxiv.org/abs/2507.06517) _Zicong Tang, Shi Luohe, Zuchao Li, Baoyuan Qi, Guoming Liu, Lefei Zhang, Ping Wang._ ACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/tyxqc/SpindleKV)](https://github.com/tyxqc/SpindleKV)

16. [**Compactor: Calibrated Query-Agnostic KV Cache Compression with Approximate Leverage Scores.**](https://arxiv.org/abs/2507.08143) _Vivek Chari, Benjamin Van Durme._ Arxiv 2025.

17. [**HCAttention: Extreme KV Cache Compression via Heterogeneous Attention Computing for LLMs.**](https://arxiv.org/abs/2507.19823) _Dongquan Yang, Yifan Yang, Xiaotian Yu, Xianbiao Qi, Rong Xiao._ Arxiv 2025.

18. [**FAEDKV: Infinite-Window Fourier Transform for Unbiased KV Cache Compression.**](https://arxiv.org/abs/2507.20030) _Runchao Li, Yao Fu, Mu Sheng, Xianxuan Long, Haotian Yu, Pan Li._ Arxiv 2025.

19. [**CompressKV: Semantic Retrieval Heads Know What Tokens are Not Important Before Generation.**](https://arxiv.org/abs/2508.02401) _Xiaolin Lin, Jingcun Wang, Olga Kondrateva, Yiyu Shi, Bing Li, Grace Li Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/TUDa-HWAI/CompressKV)](https://github.com/TUDa-HWAI/CompressKV)

20. [**OjaKV: Context-Aware Online Low-Rank KV Cache Compression with Oja's Rule.**](https://arxiv.org/abs/2509.21623) _Yuxuan Zhu, David H. Yang, Mohammad Mohammadi Amiri, Keerthiram Murugesan, Tejaswini Pedapati, Pin-Yu Chen._ Arxiv 2025.
21. [**Limits of KV Cache Compression for Tensor Attention based Autoregressive Transformers.**](https://arxiv.org/abs/2503.11108) _Yifang Chen, Xiaoyu Li, Yingyu Liang, Zhenmei Shi, Zhao Song, Yu Tian._ Arxiv 2025.

22. [**CSR:Achieving 1 Bit Key-Value Cache via Sparse Representation.**](https://arxiv.org/abs/2412.11741) _Hongxuan Zhang, Yao Zhao, Jiaqi Zheng, Chenyi Zhuang, Jinjie Gu, Guihai Chen._ AAAI 2025.

23. [**Dynamic Memory Compression: Retrofitting LLMs for Accelerated Inference.**](https://arxiv.org/abs/2403.09636) _Piotr Nawrot, Adrian Łańcucki, Marcin Chochowski, David Tarjan, Edoardo M. Ponti._ Arxiv 2024.

24. [**OrthoRank: Token Selection via Sink Token Orthogonality for Efficient LLM inference.**](https://arxiv.org/abs/2507.03865) _Seungjun Shin, Jaehoon Oh, Dokwan Oh._ ICML 2025.

25. [**ARKV: Adaptive and Resource-Efficient KV Cache Management under Limited Memory Budget for Long-Context Inference in LLMs.**](https://arxiv.org/abs/2603.08727) _Jianlong Lei, Shashikant Ilager._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/Large-scale-Sustainable-Computing-LSC/ARKV)](https://github.com/Large-scale-Sustainable-Computing-LSC/ARKV)

26. [**DASH-KV: Accelerating Long-Context LLM Inference via Asymmetric KV Cache Hashing.**](https://arxiv.org/abs/2604.19351) _Jinyu Guo, Zhihan Zhang, Jiehui Xie, Md. Tamim Iqbal, Dongshen Han, Lik-Hang Lee, Sung-Ho Bae, Jie Zou, Yang Yang, Chaoning Zhang._ Arxiv 2026.

27. [**Beyond RAG: Task-Aware KV Cache Compression for Comprehensive Knowledge Reasoning.**](https://arxiv.org/abs/2503.04973) _Giulio Corallo, Orion Weller, Fabio Petroni, Paolo Papotti._ Arxiv 2025.

28. [**Hurwitz Quaternion Multiplicative Quantization for KV Cache Compression.**](https://arxiv.org/abs/2605.27646) _Kabir Swain, Sijie Han, Daniel Karl I. Weidele, Mauro Martino, David Cox, Antonio Torralba._ Arxiv 2026.

29. [**RaBitQCache: Rotated Binary Quantization for KVCache in Long Context LLM Inference.**](https://arxiv.org/abs/2606.31519) _Wenhao Li, Jinhao Dong, Hailin Zhang, Wenhang Shi, Wei Lu, Xiaoyong Du._ ICML 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/Sakuraaa0/RaBitQCache)](https://github.com/Sakuraaa0/RaBitQCache)

30. [**MosaicKV: Serving Long-Context LLM with Dynamic Two-D KV Cache Compression.**](https://arxiv.org/abs/2607.00760) _Sheng Qiang, Ruiwei Chen, Yinpeng Wu, Jinyu Gu, Zhichao Hua, Yubin Xia, Binyu Zang, Haibo Chen._ Arxiv 2026.

31. [**Information-Aware KV Cache Compression for Long Reasoning.**](https://arxiv.org/abs/2606.26875) _Jushi Kai, Zhuiri Xiao, Alexandra Birch, Zhouhan Lin._ Arxiv 2026.

32. [**RoPE-Aware Bit Allocation for KV-Cache Quantization.**](https://arxiv.org/abs/2606.24033) _Fengfeng Liang, Yuechen Zhang, Jiaya Jia._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/JIA-Lab-research/blockgtq)](https://github.com/JIA-Lab-research/blockgtq)

33. [**Tangram: Unlocking Non-Uniform KV Cache Compression for Efficient Multi-turn LLM Serving.**](https://arxiv.org/abs/2606.06302) _Hyungmin Kim, Minsoo Kim, Hongseok Kim, Jungwook Choi._ Arxiv 2026.

34. [**NestedKV: Nested Memory Routing for Long-Context KV Cache Compression.**](https://arxiv.org/abs/2605.26678) _Hong Chen, Xiang Liu, Yubo Gao, Yuxuan Fan, Bo Wang, Yuanlin Chu, Yuanguo Lin, Xuming Hu._ Arxiv 2026.

35. [**Meta-Soft: Leveraging Composable Meta-Tokens for Context-Preserving KV Cache Compression.**](https://arxiv.org/abs/2605.22337) _Wei Luo, Yi Huang, Songchen Ma, Huanyu Qu, Jiang Cai, Mingkun Xu._ Arxiv 2026.

36. [**MuKV: Multi-Grained KV Cache Compression for Long Streaming Video Question-Answering.**](https://arxiv.org/abs/2605.22269) _Junbin Xiao, Jiajun Chen, Tianxiang Sun, Xun Yang, Angela Yao._ Arxiv 2026.

37. [**OSCAR: Offline Spectral Covariance-Aware Rotation for 2-bit KV Cache Quantization.**](https://arxiv.org/abs/2605.17757) _Zhongzhu Zhou, Donglin Zhuang, Jisen Li, Ziyan Chen, Shuaiwen Leon Song, Ben Athiwaratkun, Xiaoxia Wu._ Arxiv 2026.

38. [**Moment-KV: Momentum-Based Decode-Time KV Cache Compression for Long Generation.**](https://arxiv.org/abs/2605.29873) _Soumyadeep Jana, Sagar Nishad, Sanasam Ranbir Singh._ Arxiv 2026.

39. [**SPHERICAL KV: Angle-Domain Attention and Rate-Distortion Retention for Efficient Long-Context Inference.**](https://arxiv.org/abs/2605.18856) _Anay Chauhan, Gurucharan Marthi Krishna Kumar, Arion Das, Amit Dhanda, Vinija Jain, Aman Chadha, Amitava Das._ Arxiv 2026.

40. [**DepthWeave-KV: Token-Adaptive Cross-Layer Residual Factorization for Long-Context KV Cache Compression.**](https://arxiv.org/abs/2607.06523) _Anna Cordoba, Adam Puente Tercero, Nerea Angulo Hijo, Mar Linares Tercero, Julia Barrientos, Ainhoa Miranda, Jesus Olivera._ Arxiv 2026.

41. [**FreqDepthKV: Frequency-Guided Depth Sharing for Robust KV Cache Compression in Long-Context LLM Inference.**](https://arxiv.org/abs/2607.06519) _Anna Córdoba, Adam Puente Tercero, Nerea Angulo Hijo, Mar Linares Tercero, Julia Barrientos, Ainhoa Miranda, Jesús Olivera._ Arxiv 2026.

42. [**HiKV: Hierarchical Importance-Aware KV Cache with Hardware Acceleration for LLM Decoding.**](https://arxiv.org/abs/2607.22389) _Chao Fang, Jun Yin, Man Shi, Marian Verhelst._ Arxiv 2026.

43. [**C$^2$KV: Compressed and Composable KV Cache Reuse for Efficient LLM Inference.**](https://arxiv.org/abs/2607.17715) _Chuheng Du, Junyi Chen, Hanlin Tang, Kan Liu, Tao Lan, Lin Qu, Chaoyue Niu, Shengzhong Liu, Guihai Chen, Fan Wu._ Arxiv 2026.

#### 3.3 Offloading / Hierarchical Cache

1. [**InstInfer: In-Storage Attention Offloading for Cost-Effective Long-Context LLM Inference.**](https://arxiv.org/abs/2409.04992) _Xiurui Pan, Endian Li, Qiao Li, Shengwen Liang, Yizhou Shan, Ke Zhou, Yingwei Luo, Xiaolin Wang, Jie Zhang._ Arxiv 2024.

2. [**InfiniPot: Infinite Context Processing on Memory-Constrained LLMs.**](https://arxiv.org/abs/2410.01518) _Minsoo Kim, Kyuhong Shim, Jungwook Choi, Simyung Chang._ Arxiv 2024.

3. [**ShadowKV: KV Cache in Shadows for High-Throughput Long-Context LLM Inference.**](https://arxiv.org/abs/2410.21465) _Hanshi Sun, Li-Wen Chang, Wenlei Bao, Size Zheng, Ningxin Zheng, Xin Liu, Harry Dong, Yuejie Chi, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/ShadowKV)](https://github.com/bytedance/ShadowKV)

4. [**Twilight: Adaptive Attention Sparsity with Hierarchical Top-p Pruning.**](https://arxiv.org/abs/2502.02770) _Chaofan Lin, Jiaming Tang, Shuo Yang, Hanshuo Wang, Tian Tang, Boyu Tian, Ion Stoica, Song Han, Mingyu Gao._ Arxiv 2025.

5. [**InfiniteHiP: Extending Language Model Context Up to 3 Million Tokens on a Single GPU.**](https://arxiv.org/abs/2502.08910) _Heejun Lee, Geon Park, Jaduk Suh, Sung Ju Hwang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DeepAuto-AI/hip-attention)](https://github.com/DeepAuto-AI/hip-attention)

6. [**HeadInfer: Memory-Efficient LLM Inference by Head-wise Offloading.**](https://arxiv.org/abs/2502.12574) _Cheng Luo, Zefan Cai, Hanshi Sun, Jinqi Xiao, Bo Yuan, Wen Xiao, Junjie Hu, Jiawei Zhao, Beidi Chen, Anima Anandkumar._ Arxiv 2025.

7. [**MOM: Memory-Efficient Offloaded Mini-Sequence Inference for Long Context Language Models.**](https://arxiv.org/abs/2504.12526) _Junyang Zhang, Tianyi Zhu, Cheng Luo, Anima Anandkumar._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/TianyiZhu877/MOM)](https://github.com/TianyiZhu877/MOM)

8. [**SlimPipe: Memory-Thrifty and Efficient Pipeline Parallelism for Long-Context LLM Training.**](https://arxiv.org/abs/2504.14519) _Zhouyang Li, Yuliang Liu, Wei Zhang, Tailing Yuan, Bin Chen, Chengru Song, Di Zhang._ Arxiv 2025.

9. [**Homogeneous Keys, Heterogeneous Values: Exploiting Local KV Cache Asymmetry for Long-Context LLMs.**](https://arxiv.org/abs/2506.05410) _Wanyun Cui, Mingwei Xu._ Arxiv 2025.

10. [**LaCache: Ladder-Shaped KV Caching for Efficient Long-Context Modeling of Large Language Models.**](https://arxiv.org/abs/2507.14204) _Dachuan Shi, Yonggan Fu, Xiangchi Yuan, Zhongzhi Yu, Haoran You, Sixu Li, Xin Dong, Jan Kautz, Pavlo Molchanov, Yingyan (Celine)Lin._ ICML 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/tGATECH-EIC/LaCache)](https://github.com/GATECH-EIC/LaCache)

11. [**XQuant: Breaking the Memory Wall for LLM Inference with KV Cache Rematerialization.**](https://arxiv.org/abs/2508.10395) _Aditya Tomar, Coleman Hooper, Minjae Lee, Haocheng Xi, Rishabh Tiwari, Wonjun Kang, Luca Manolache, Michael W. Mahoney, Kurt Keutzer, Amir Gholami._ Arxiv 2025.

12. [**APB: Accelerating Distributed Long-Context Inference by Passing Compressed Context Blocks across GPUs.**](https://arxiv.org/abs/2502.12085) _Yuxiang Huang, Mingye Li, Xu Han, Chaojun Xiao, Weilin Zhao, Sun Ao, Hao Zhou, Jie Zhou, Zhiyuan Liu, Maosong Sun._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/APB)](https://github.com/thunlp/APB)

13. [**TTKV: Temporal-Tiered KV Cache for Long-Context LLM Inference.**](https://arxiv.org/abs/2604.19769) _Gradwell Dzikanyanga, Weihao Yang, Hao Huang, Donglei Wu, Shihao Wang, Wen Xia, Sanjeeb K C._ Arxiv 2026.

14. [**KV Cache Offloading for Context-Intensive Tasks.**](https://arxiv.org/abs/2604.08426) _Andrey Bocharnikov, Ivan Ermakov, Denis Kuznedelev, Vyacheslav Zhdanovskiy, Yegor Yershov._ Arxiv 2026.

15. [**Infinite-LLM: Efficient LLM Service for Long Context with DistAttention and Distributed KVCache.**](https://arxiv.org/abs/2401.02669) _Bin Lin, Tao Peng, Chen Zhang, Minmin Sun, Lanbo Li, Hanyu Zhao, Wencong Xiao, Qi Xu, Xiafei Qiu, Shen Li, Zhigang Ji, Yong Li, Wei Lin._ Arxiv 2024.

16. [**SeKV: Resolution-Adaptive KV Cache with Hierarchical Semantic Memory for Long-Context LLM Inference.**](https://arxiv.org/abs/2606.31145) _Amirhossein Abaskohi, Giuseppe Carenini, Peter West, Yuhang He._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/AmirAbaskohi/SeKV)](https://github.com/AmirAbaskohi/SeKV)

#### 3.4 Architectural KV Reduction & Cache Sharing

1. [**Reducing Transformer Key-Value Cache Size with Cross-Layer Attention.**](https://arxiv.org/abs/2405.12981) _William Brandon, Mayank Mishra, Aniruddha Nrusimha, Rameswar Panda, Jonathan Ragan Kelly._ Arxiv 2024.

2. [**Beyond KV Caching: Shared Attention for Efficient LLMs.**](https://arxiv.org/abs/2407.12866) _Bingli Liao, Danilo Vasconcellos Vargas._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/metacarbon/shareAtt)](https://github.com/metacarbon/shareAtt)

3. [**Cross-layer Attention Sharing for Large Language Models.**](https://arxiv.org/abs/2408.01890) _Yongyu Mu, Yuzhang Wu, Yuchun Fan, Chenglong Wang, Hengyu Li, Qiaozhi He, Murun Yang, Tong Xiao, Jingbo Zhu._ Arxiv 2024.

4. [**A Systematic Study of Cross-Layer KV Sharing for Efficient LLM Inference.**](https://arxiv.org/abs/2410.14442) _You Wu, Haoyi Wu, Kewei Tu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

5. [**KVSharer: Efficient Inference via Layer-Wise Dissimilar KV Cache Sharing.**](https://arxiv.org/abs/2410.18517) _Yifei Yang, Zouying Cao, Qiguang Chen, Libo Qin, Dongjie Yang, Hai Zhao, Zhi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yangyifei729/KVSharer)](https://github.com/yangyifei729/KVSharer)

6. [**Cross-Self KV Cache Pruning for Efficient Vision-Language Inference.**](https://arxiv.org/abs/2412.04652) _Xiaohuan Pei, Tao Huang, Chang Xu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TerryPei/CSP)](https://github.com/TerryPei/CSP)

7. [**KVLink: Accelerating Large Language Models via Efficient KV Cache Reuse.**](https://arxiv.org/abs/2502.16002) _Jingbo Yang, Bairu Hou, Wei Wei, Yujia Bao, Shiyu Changi._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UCSB-NLP-Chang/KVLink)](https://github.com/UCSB-NLP-Chang/KVLink)

8. [**KVShare: Semantic-Aware Key-Value Cache Sharing for Efficient Large Language Model Inference.**](https://arxiv.org/abs/2503.16525) _Huan Yang, Renji Zhang, Deyu Zhang._ Arxiv 2025.

9. [**xKV: Cross-Layer SVD for KV-Cache Compression.**](https://arxiv.org/abs/2503.18893) _Chi-Chih Chang, Chien-Yu Lin, Yash Akhauri, Wei-Cheng Lin, Kai-Chiang Wu, Luis Ceze, Mohamed S. Abdelfattah._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/abdelfattah-lab/xKV)](https://github.com/abdelfattah-lab/xKV)

10. [**Mixture of Weight-shared Heterogeneous Group Attention Experts for Dynamic Token-wise KV Optimization.**](https://arxiv.org/abs/2506.13541v1) _Guanghui Song, Dongping Liao, Yiren Zhao, Kejiang Ye, Cheng-zhong Xu, Xitong Gao._ Arxiv 2025.

11. [**Krul: Efficient State Restoration for Multi-turn Conversations with Dynamic Cross-layer KV Sharing.**](https://arxiv.org/abs/2507.08045) _Junyi Wen, Junyuan Liang, Zicong Hong, Wuhui Chen, Zibin Zheng._ Arxiv 2025.

12. [**Sparse Attention across Multiple-context KV Cache.**](https://arxiv.org/abs/2508.11661) _Ziyi Cao, Qingyi Si, Jingbin Zhang, Bingquan Liu._ Arxiv 2025.
13. [**X-EcoMLA: Upcycling Pre-Trained Attention into MLA for Efficient and Extreme KV Compression.**](https://arxiv.org/abs/2503.11132) _Guihong Li, Mehdi Rezagholizadeh, Mingyu Yang, Vikram Appia, Emad Barsoum._ Arxiv 2025.

14. [**GTA: Grouped-head latenT Attention.**](https://arxiv.org/abs/2506.17286) _Luoyang Sun, Jiwen Jiang, Cheng Deng, Xinjian Wu, Haifeng Zhang, Lei Chen, Lionel Ni, Jun Wang._ Arxiv 2025.

15. [**You Only Cache Once: Decoder-Decoder Architectures for Language Models.**](https://arxiv.org/abs/2405.05254) _Yutao Sun, Li Dong, Yi Zhu, Shaohan Huang, Wenhui Wang, Shuming Ma, Quanlu Zhang, Jianyong Wang, Furu Wei._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/unilm)](https://github.com/microsoft/unilm/tree/master/YOCO)

16. [**GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints.**](https://arxiv.org/abs/2305.13245) _Joshua Ainslie, James Lee-Thorp, Michiel de Jong, Yury Zemlyanskiy, Federico Lebrón, Sumit Sanghai._ Arxiv 2023.

17. [**DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model.**](https://arxiv.org/abs/2405.04434) _DeepSeek-AI._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V2)](https://github.com/deepseek-ai/DeepSeek-V2)

18. [**DeepSeek-V3 Technical Report.**](https://arxiv.org/abs/2412.19437) _DeepSeek-AI, Aixin Liu, Bei Feng, Bing Xue, Bingxuan Wang, Bochao Wu, Chengda Lu, Chenggang Zhao, Chengqi Deng, Chenyu Zhang, Chong Ruan, Damai Dai, Daya Guo, Dejian Yang, Deli Chen, Dongjie Ji, Erhang Li, Fangyun Lin, Fucong Dai, Fuli Luo, Guangbo Hao, Guanting Chen, Guowei Li, H. Zhang, Han Bao, Hanwei Xu, Haocheng Wang, Haowei Zhang, Honghui Ding, Huajian Xin, Huazuo Gao, Hui Li, Hui Qu, J.L. Cai, Jian Liang, Jianzhong Guo, Jiaqi Ni, Jiashi Li, Jiawei Wang, Jin Chen, Jingchang Chen, Jingyang Yuan, Junjie Qiu, Junlong Li, Junxiao Song, Kai Dong, Kai Hu, Kaige Gao, Kang Guan, Kexin Huang, Kuai Yu, Lean Wang, Lecong Zhang, Lei Xu, Leyi Xia, Liang Zhao, Litong Wang, Liyue Zhang, Meng Li, Miaojun Wang, Mingchuan Zhang, Minghua Zhang, Minghui Tang, Mingming Li, Ning Tian, Panpan Huang, Peiyi Wang, Peng Zhang, Qiancheng Wang, Qihao Zhu, Qinyu Chen, Qiushi Du, R.J. Chen, R.L. Jin, Ruiqi Ge, Ruisong Zhang, Ruizhe Pan, Runji Wang, Runxin Xu, Ruoyu Zhang, Ruyi Chen, S.S. Li, Shanghao Lu, Shangyan Zhou, Shanhuang Chen, Shaoqing Wu, Shengfeng Ye, Shengfeng Ye, Shirong Ma, Shiyu Wang, Shuang Zhou, Shuiping Yu, Shunfeng Zhou, Shuting Pan, T. Wang, Tao Yun, Tian Pei, Tianyu Sun, W.L. Xiao, Wangding Zeng et al. (100 additional authors not shown)._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V3)](https://github.com/deepseek-ai/DeepSeek-V3)

19. [**Layer-Condensed KV Cache for Efficient Inference of Large Language Models.**](https://arxiv.org/abs/2405.10637) _Haoyi Wu, Kewei Tu._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/whyNLP/LCKV)](https://github.com/whyNLP/LCKV)

20. [**Slim attention: cut your context memory in half without loss of accuracy -- K-cache is all you need for MHA.**](https://arxiv.org/abs/2503.05840) _Nils Graef, Andrew Wasielewski._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenMachine-ai/transformer-tricks)](https://github.com/OpenMachine-ai/transformer-tricks)

21. [**Smarter and Cheaper at Once: Byte-Exact KV-Cache Grafting Turns a Frozen Small Model into a Verified-Knowledge Flywheel.**](https://arxiv.org/abs/2607.14431) _Sietse Schelpe._ Arxiv 2026.
