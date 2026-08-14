# 17. Inference Acceleration & Serving

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [17.1 Speculative & Parallel Decoding](#171-speculative--parallel-decoding)
- [17.2 Quantization-Aware Long-Context Inference](#172-quantization-aware-long-context-inference)
- [17.3 Prefill & Sparse Attention Acceleration](#173-prefill--sparse-attention-acceleration)
- [17.4 System & Serving Optimization](#174-system--serving-optimization)
<!-- /chapter-toc -->

#### 17.1 Speculative & Parallel Decoding

1. [**LongSpec: Long-Context Speculative Decoding with Efficient Drafting and Verification.**](https://arxiv.org/abs/2502.17421) _Penghui Yang, Cunxiao Du, Fengzhuo Zhang, Haonan Wang, Tianyu Pang, Chao Du, Bo An._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/LongSpec)](https://github.com/sail-sg/LongSpec)

2. [**Long-Context Inference with Retrieval-Augmented Speculative Decoding.**](https://arxiv.org/abs/2502.20330) _Guanzheng Chen, Qilong Feng, Jinjie Ni, Xin Li, Michael Qizhe Shieh._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/John-AI-Lab/RAPID)](https://github.com/John-AI-Lab/RAPID)

3. [**Efficient Reasoning for LLMs through Speculative Chain-of-Thought.**](https://arxiv.org/abs/2504.19095) _Jikai Wang, Juntao Li, Lijun Wu, Min Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Jikai0Wang/Speculative_CoT)](https://github.com/Jikai0Wang/Speculative_CoT)

4. [**SpecExtend: A Drop-in Enhancement for Speculative Decoding of Long Sequences.**](https://arxiv.org/abs/2505.20776) _Jungyoub Cha, Hyunjong Kim, Sungzoon Cho._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/jycha98/SpecExtend)](https://github.com/jycha98/SpecExtend)

5. [**Mamba Drafters for Speculative Decoding.**](https://arxiv.org/abs/2506.01206) _Daewon Choi, Seunghyuk Oh, Saket Dingliwal, Jihoon Tack, Kyuyoung Kim, Woomin Song, Seojin Kim, Insu Han, Jinwoo Shin, Aram Galstyan, Shubham Katiyar, Sravan Babu Bodapati._ Arxiv 2025.

6. [**SwiftSpec: Ultra-Low Latency LLM Decoding by Scaling Asynchronous Speculative Decoding.**](https://arxiv.org/abs/2506.11309) _Ziyi Zhang, Ziheng Jiang, Chengquan Jiang, Menghan Yu, Size Zheng, Haibin Lin, Henry Hoffmann, Xin Liu._ Arxiv 2025.

7. [**Scaling Up, Speeding Up: A Benchmark of Speculative Decoding for Efficient LLM Test-Time Scaling.**](https://arxiv.org/abs/2509.04474) _Shengyin Sun, Yiming Li, Xing Li, Yingzhao Lian, Weizhe Lin, Hui-Ling Zhen, Zhiyuan Yang, Chen Chen, Xianzhi Yu, Mingxuan Yuan, Chen Ma._ Arxiv 2025.

8. [**ParallelVLM: Lossless Video-LLM Acceleration with Visual Alignment Aware Parallel Speculative Decoding.**](https://arxiv.org/abs/2603.19610) _Quan Kong, Yuhao Shen, Yicheng Ji, Huan Li, Cong Wang._ Arxiv 2026.

9. [**HIPPO: Accelerating Video Large Language Models Inference via Holistic-aware Parallel Speculative Decoding.**](https://arxiv.org/abs/2601.08273) _Qitan Lv, Tianyu Liu, Wen Wu, Xuenan Xu, Bowen Zhou, Feng Wu, Chao Zhang._ Arxiv 2026.

10. [**L-MTP: Leap Multi-Token Prediction Beyond Adjacent Context for Large Language Models.**](https://arxiv.org/abs/2505.17505) _Xiaohao Liu, Xiaobo Xia, Weixiang Zhao, Manyi Zhang, Xianzhi Yu, Xiu Su, Shuo Yang, See-Kiong Ng, Tat-Seng Chua._ Arxiv 2025.

11. [**Self-Distillation for Multi-Token Prediction.**](https://arxiv.org/abs/2603.23911) _Guoliang Zhao, Ruobing Xie, An Wang, Shuaipeng Li, Huaibing Xie, Xingwu Sun._ Arxiv 2026.

12. [**From Hours to Minutes: Lossless Acceleration of Ultra Long Sequence Generation up to 100K Tokens.**](https://arxiv.org/abs/2502.18890) _Tong Wu, Junzhe Shen, Zixia Jia, Yuxuan Wang, Zilong Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/TokenSwift)](https://github.com/bigai-nlco/TokenSwift)

13. [**MagicDec: Breaking the Latency-Throughput Tradeoff for Long Context Generation with Speculative Decoding.**](https://arxiv.org/abs/2408.11049) _Jian Chen, Vashisth Tiwari, Ranajoy Sadhukhan, Zhuoming Chen, Jinyuan Shi, Ian En-Hsu Yen, Beidi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Infini-AI-Lab/MagicDec)](https://github.com/Infini-AI-Lab/MagicDec/)

14. [**Speculative Prefill: Turbocharging TTFT with Lightweight and Training-Free Token Importance Estimation.**](https://arxiv.org/abs/2502.02789) _Jingyu Liu, Beidi Chen, Ce Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Jingyu6/speculative_prefill)](https://github.com/Jingyu6/speculative_prefill)

15. [**QuantSpec: Self-Speculative Decoding with Hierarchical Quantized KV Cache.**](https://arxiv.org/abs/2502.10424) _Rishabh Tiwari, Haocheng Xi, Aditya Tomar, Coleman Hooper, Sehoon Kim, Maxwell Horton, Mahyar Najibi, Michael W. Mahoney, Kurt Keutzer, Amir Gholami._ Arxiv 2025.

16. [**Radar: Fast Long-Context Decoding for Any Transformer.**](https://arxiv.org/abs/2503.10571) _Yongchang Hao, Mengyao Zhai, Hossein Hajimirsadeghi, Sepidehsadat Hosseini, Frederick Tung._ ICLR 2025.

17. [**SpeCache: Speculative Key-Value Caching for Efficient Generation of LLMs.**](https://arxiv.org/abs/2503.16163) _Shibo Jie, Yehui Tang, Kai Han, Zhi-Hong Deng, Jing Han._ Arxiv 2025.

18. [**FocusLLM: Scaling LLM's Context by Parallel Decoding.**](https://arxiv.org/abs/2408.11745) _Zhenyu Li, Yike Zhang, Tengyu Pan, Yutao Sun, Zhichao Duan, Junjie Fang, Rong Han, Zixuan Wang, Jianyong Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/leezythu/FocusLLM)](https://github.com/leezythu/FocusLLM)

19. [**Position-Aware Depth Decay Decoding (D3): Boosting Large Language Model Inference Efficiency.**](https://arxiv.org/abs/2503.08524) _Siqi Fan, Xuezhi Fang, Xingrun Xing, Peng Han, Shuo Shang, Yequan Wang._ Arxiv 2025.

20. [**AdaSkip: Adaptive Sublayer Skipping for Accelerating Long-Context LLM Inference.**](https://arxiv.org/abs/2501.02336) _Zhuomin He, Yizhen Yao, Pengfei Zuo, Bin Gao, Qinya Li, Zhenzhe Zheng, Fan Wu._ AAAI 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ASISys/AdaSkip)](https://github.com/ASISys/AdaSkip)

#### 17.2 Quantization-Aware Long-Context Inference

1. [**Rotate, Clip, and Partition: Towards W2A4KV4 Quantization by Integrating Rotation and Learnable Non-uniform Quantizer.**](https://arxiv.org/abs/2502.15779) _Euntae Choi, Sumin Song, Woosang Lim, Sungjoo Yoo._ Arxiv 2025.

2. [**KVSink: Understanding and Enhancing the Preservation of Attention Sinks in KV Cache Quantization for LLMs.**](https://arxiv.org/abs/2508.04257) _Zunhai Su, Kehong Yuan._ COLM 2025.

3. [**CaliDrop: KV Cache Compression with Calibration.**](https://arxiv.org/abs/2507.19906) _Yi Su, Quantong Qiu, Yuechi Zhou, Juntao Li, Qingrong Xia, Ping Li, Xinyu Duan, Zhefeng Wang, Min Zhang._ Arxiv 2025.

4. [**CommVQ: Commutative Vector Quantization for KV Cache Compression.**](https://arxiv.org/abs/2506.18879) _Junyan Li, Yang Zhang, Muhammad Yusuf Hassan, Talha Chafekar, Tianle Cai, Zhile Ren, Pengsheng Guo, Foroozan Karimzadeh, Colorado Reed, Chong Wang, Chuang Gan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/UMass-Embodied-AGI/CommVQ)](https://github.com/UMass-Embodied-AGI/CommVQ)

5. [**KVmix: Gradient-Based Layer Importance-Aware Mixed-Precision Quantization for KV Cache.**](https://arxiv.org/abs/2506.08018) _Fei Li, Song Liu, Weiguo Wu, Shiqiang Nie, Jinyu Wang._ Arxiv 2025.

6. [**PM-KVQ: Progressive Mixed-precision KV Cache Quantization for Long-CoT LLMs.**](https://arxiv.org/abs/2505.18610) _Tengxuan Liu, Shiyao Li, Jiayi Yang, Tianchen Zhao, Feng Zhou, Xiaohui Song, Guohao Dai, Shengen Yan, Huazhong Yang, Yu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/thu-nics/PM-KVQ)](https://github.com/thu-nics/PM-KVQ)

7. [**SQuat: Subspace-orthogonal KV Cache Quantization.**](https://arxiv.org/abs/2503.24358) _Hao Wang, Ligong Han, Kai Xu, Akash Srivastava._ Arxiv 2025.

8. [**Cocktail: Chunk-Adaptive Mixed-Precision Quantization for Long-Context LLM Inference.**](https://arxiv.org/abs/2503.23294) _Wei Tao, Bin Zhang, Xiaoyang Qu, Jiguang Wan, Jianzong Wang._ DATE 2025.

9. [**LogQuant: Log-Distributed 2-Bit Quantization of KV Cache with Superior Accuracy Preservation.**](https://arxiv.org/abs/2503.19950) _Han Chen, Zicong Jiang, Zining Zhang, Bingsheng He, Pingyi Luo, Mian Lu, Yuqiang Chen._ ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Concyclics/LogQuantKV)](https://github.com/Concyclics/LogQuantKV)

10. [**A2ATS: Retrieval-Based KV Cache Reduction via Windowed Rotary Position Embedding and Query-Aware Vector Quantization.**](https://arxiv.org/abs/2502.12665) _Junhui He, Junna Xing, Nan Wang, Rui Xu, Shangyu Wu, Peng Zhou, Qiang Liu, Chun Jason Xue, Qingan Li._ Arxiv 2025.

11. [**KVTuner: Sensitivity-Aware Layer-wise Mixed Precision KV Cache Quantization for Efficient and Nearly Lossless LLM Inference.**](https://arxiv.org/abs/2502.04420) _Xing Li, Zeyu Xing, Yiming Li, Linping Qu, Hui-Ling Zhen, Wulong Liu, Yiwu Yao, Sinno Jialin Pan, Mingxuan Yuan._ Arxiv 2025.

12. [**AKVQ-VL: Attention-Aware KV Cache Adaptive 2-Bit Quantization for Vision-Language Models.**](https://arxiv.org/abs/2501.15021) _Zunhai Su, Wang Shen, Linge Li, Zhe Chen, Hanyu Wei, Huangqi Yu, Kehong Yuan._ Arxiv 2025.

13. [**PQCache: Product Quantization-based KVCache for Long Context LLM Inference.**](https://arxiv.org/abs/2407.12820) _Hailin Zhang, Xiaodong Ji, Yilin Chen, Fangcheng Fu, Xupeng Miao, Xiaonan Nie, Weipeng Chen, Bin Cui._ Arxiv 2024.

14. [**KVarN: Variance-Normalized KV-Cache Quantization Mitigates Error Accumulation in Reasoning Tasks.**](https://arxiv.org/abs/2606.03458) _Lorenz K. Muller, Philippe Bich, Chiara Boretti, Hyun-Min Chang, Jiawei Zhuang, Lukas Cavigelli._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/huawei-csl/KVarN)](https://github.com/huawei-csl/KVarN)

15. [**Unlocking Data-free Low-bit Quantization with Matrix Decomposition for KV Cache Compression.**](https://arxiv.org/abs/2405.12591) _Peiyu Liu, Ze-Feng Gao, Wayne Xin Zhao, Yipeng Ma, Tao Wang, Ji-Rong Wen._ Arxiv 2024.

16. [**ChunkKV: Semantic-Preserving KV Cache Compression for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2502.00299) _Xiang Liu, Zhenheng Tang, Peijie Dong, Zeyu Li, Bo Li, Xuming Hu, Xiaowen Chu._ Arxiv 2025.

17. [**BitDecoding: Unlocking Tensor Cores for Long-Context LLMs Decoding with Low-Bit KV Cache.**](https://arxiv.org/abs/2503.18773) _Dayou Du, Shijie Cao, Jianyi Cheng, Ting Cao, Mao Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DD-DuDa/BitDecoding)](https://github.com/DD-DuDa/BitDecoding)

18. [**Oaken: Fast and Efficient LLM Serving with Online-Offline Hybrid KV Cache Quantization.**](https://arxiv.org/abs/2503.18599) _Minsu Kim, Seongmin Hong, RyeoWook Ko, Soongyu Choi, Hunjong Lee, Junsoo Kim, Joo-Young Kim, Jongse Park._ Arxiv 2025.

19. [**Lookahead Q-Cache: Achieving More Consistent KV Cache Eviction via Pseudo Query.**](https://arxiv.org/abs/2505.20334) _Yixuan Wang, Shiyu Ji, Yijun Liu, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che._ Arxiv 2025.

20. [**TaDA: Training-free recipe for Decoding with Adaptive KV Cache Compression and Mean-centering.**](https://arxiv.org/abs/2506.04642) _Vinay Joshi, Pratik Prabhanjan Brahma, Zicheng Liu, Emad Barsoum._ Arxiv 2025.

21. [**LeanK: Learnable K Cache Channel Pruning for Efficient Decoding.**](https://arxiv.org/abs/2508.02215) _Yike Zhang, Zhiyuan He, Huiqiang Jiang, Chengruidong Zhang, Yuqing Yang, Jianyong Wang, Lili Qiu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference/tree/main/LeanK)

22. [**MadaKV: Adaptive Modality-Perception KV Cache Eviction for Efficient Multimodal Long-Context Inference.**](https://arxiv.org/abs/2506.15724) _Kunxi Li, Zhonghua Jiang, Zhouzhou Shen, Zhaode Wang, Chengfei Lv, Shengyu Zhang, Fan Wu, Fei Wu._ Arxiv 2025.

#### 17.3 Prefill & Sparse Attention Acceleration

1. [**CritiPrefill: A Segment-wise Criticality-based Approach for Prefilling Acceleration in LLMs.**](https://arxiv.org/abs/2409.12490) _Junlin Lv, Yuan Feng, Xike Xie, Xin Jia, Qirong Peng, Guiming Xie._ Arxiv 2024.

2. [**Star Attention: Efficient LLM Inference over Long Sequences.**](https://arxiv.org/pdf/2411.17116) _Shantanu Acharya, Fei Jia, Boris Ginsburg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NVIDIA/Star-Attention)](https://github.com/NVIDIA/Star-Attention)

3. [**FlexPrefill: A Context-Aware Sparse Attention Mechanism for Efficient Long-Sequence Inference.**](https://arxiv.org/abs/2502.20766) _Xunhao Lai, Jianqiao Lu, Yao Luo, Yiyuan Ma, Xun Zhou._ ICLR 2025 Oral.

4. [**Progressive Sparse Attention: Algorithm and System Co-design for Efficient Attention in LLM Serving.**](https://arxiv.org/abs/2503.00392) _Qihui Zhou, Peiqi Yin, Pengfei Zuo, James Cheng._ Arxiv 2025.

5. [**Hardware-Efficient Attention for Fast Decoding.**](https://arxiv.org/abs/2505.21487) _Ted Zadouri, Hubert Strauss, Tri Dao._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Dao-AILab/grouped-latent-attention)](https://github.com/Dao-AILab/grouped-latent-attention)

6. [**UniPrefill: Universal Long-Context Prefill Acceleration via Block-wise Dynamic Sparsification.**](https://arxiv.org/abs/2605.06221) _Qihang Fan, Huaibo Huang, Zhiying Wu, Bingning Wang, Ran He._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/qhfan/UniPrefill)](https://github.com/qhfan/UniPrefill)

7. [**MInference 1.0: Accelerating Pre-filling for Long-Context LLMs via Dynamic Sparse Attention.**](https://arxiv.org/abs/2407.02490) _Huiqiang Jiang, Yucheng Li, Chengruidong Zhang, Qianhui Wu, Xufang Luo, Surin Ahn, Zhenhua Han, Amir H. Abdi, Dongsheng Li, Chin-Yew Lin, Yuqing Yang, Lili Qiu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/MInference)](https://github.com/microsoft/MInference)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://hqjiang.com/minference.html)

8. [**SentenceVAE: Faster, Longer and More Accurate Inference with Next-sentence Prediction for Large Language Models.**](https://arxiv.org/abs/2408.00655) _Hongjun An, Yifan Chen, Xiaozhen Qiao, Zhe Sun, Xuelong Li._ Arxiv 2024.

9. [**DTRNet: Dynamic Token Routing Network to Reduce Quadratic Costs in Transformers.**](https://arxiv.org/abs/2509.00925) _Aman Sharma, Saeed Najafi, Parsa Farinneya, Benyamin Jamialahmadi, Marzieh S. Tahaei, Yuhe Fan, Mehdi Rezagholizadeh, Boxing Chen, Aref Jafari._ Arxiv 2025.

10. [**Inference Time Context Sparsity: Illusion or Opportunity?**](https://arxiv.org/abs/2605.24168) _Sahil Joshi, Prithvi Dixit, Agniva Chowdhury, Anshumali Shrivastava, Joseph E. Gonzalez, Ion Stoica, Kumar Krishna Agrawal, Aditya Desai._ Arxiv 2026.

11. [**SparDA: Sparse Decoupled Attention for Efficient Long-Context LLM Inference.**](https://arxiv.org/abs/2606.04511) _Yaosheng Fu, Guangxuan Xiao, Xin Dong, Song Han, Oreste Villa._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/NVlabs/SparDA)](https://github.com/NVlabs/SparDA)

12. [**How Much Dense Attention is Necessary? Oracle-Guided Sparse Prefill for Full/GQA Layers in Hybrid Long-Context Models.**](https://arxiv.org/abs/2606.07703) _Hongxing Wang, Harenome Razanajato, Zhen Zhang, Yujie Yuan, Hongsheng Liu._ Arxiv 2026.

13. [**Predict, Reuse, and Repair: Accelerating Dynamic Sparse Attention for Long-Context LLM Decoding.**](https://arxiv.org/abs/2606.30389) _Tianyu Wang, Gourav Rattihalli, Aditya Dhakal, Junbo Li, Zhiwei Ren, Dejan Milojicic, Longfei Shangguan._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/Tianyu9748/Incremental_FlashAttention)](https://github.com/Tianyu9748/Incremental_FlashAttention)

14. [**CompactAttention: Accelerating Chunked Prefill with Block-Union KV Selection.**](https://arxiv.org/abs/2605.16839) _Jiwon Song, Dongwon Jo, Beomseok Kang, Jae-Joon Kim._ Arxiv 2026.

#### 17.4 System & Serving Optimization

1. [**EPIC: Efficient Position-Independent Context Caching for Serving Large Language Models.**](https://arxiv.org/abs/2410.15332) _Junhao Hu, Wenrui Huang, Haoyi Wang, Weidong Wang, Tiancheng Hu, Qin Zhang, Hao Feng, Xusheng Chen, Yizhou Shan, Tao Xie._ Arxiv 2024.

2. [**BatchLLM: Optimizing Large Batched LLM Inference with Global Prefix Sharing and Throughput-oriented Token Batching.**](https://arxiv.org/abs/2412.03594) _Zhen Zheng, Xin Ji, Taosong Fang, Fanghao Zhou, Chuanjie Liu, Gang Peng._ Arxiv 2024.

3. [**LServe: Efficient Long-sequence LLM Serving with Unified Sparse Attention.**](https://arxiv.org/abs/2502.14866) _Shang Yang, Junxian Guo, Haotian Tang, Qinghao Hu, Guangxuan Xiao, Jiaming Tang, Yujun Lin, Zhijian Liu, Yao Lu, Song Han._ MLSys 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/omniserve)](https://github.com/mit-han-lab/omniserve)

4. [**LoopServe: An Adaptive Dual-phase LLM Inference Acceleration System for Multi-Turn Dialogues.**](https://arxiv.org/abs/2507.13681) _Haoyang Li, Zhanchao Xu, Yiming Li, Xuejia Chen, Darian Li, Anxin Tian, Qingfa Xiao, Cheng Deng, Jun Wang, Qing Li, Lei Chen, Mingxuan Yuan._ Arxiv 2025.

5. [**Online Scheduling for LLM Inference with KV Cache Constraints.**](https://arxiv.org/abs/2502.07115) _Patrick Jaillet, Jiashuo Jiang, Chara Podimata, Zijie Zhou._ Arxiv 2025.

6. [**FlowKV: A Disaggregated Inference Framework with Low-Latency KV Cache Transfer and Load-Aware Scheduling.**](https://arxiv.org/abs/2504.03775) _Weiqing Li, Guochao Jiang, Xiangyong Ding, Zhangcheng Tao, Chuzhan Hao, Chenfeng Xu, Yuewei Zhang, Hao Wang._ Arxiv 2025.

7. [**Apt-Serve: Adaptive Request Scheduling on Hybrid Cache for Scalable LLM Inference Serving.**](https://arxiv.org/abs/2504.07494) _Shihong Gao, Xin Zhang, Yanyan Shen, Lei Chen._ Arxiv 2025.

8. [**CALVO: Cache-Aware LLM Serving for Network-Intensive Inference.**](https://arxiv.org/abs/2603.21257) _Weiye Wang, Chen Chen, Junxue Zhang, Zhusheng Wang, Hui Yuan, Zixuan Guan, Xiaolong Zheng, Qizhen Weng, Yin Chen, Minyi Guo._ Arxiv 2026.

9. [**TokenDance: Scaling Multi-Agent LLM Serving via Collective KV Cache Sharing.**](https://arxiv.org/abs/2604.03143) _Zhuohang Bian, Feiyang Wu, Chengrui Zhang, Hangcheng Dong, Yun Liang, Youwei Zhuo._ Arxiv 2026.

10. [**KVServe: Service-Aware KV Cache Compression for Communication-Efficient Disaggregated LLM Serving.**](https://arxiv.org/abs/2605.13734) _Zedong Liu, Xinyang Ma, Dejun Luo, Hairui Zhao, Bing Lu, Wenjing Huang, Yida Gu, Xingchen Liu, Zheng Wei, Jinyang Liu, Dingwen Tao, Guangming Tan._ SIGCOMM 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/hpdps-group/KVServe)](https://github.com/hpdps-group/KVServe)

11. [**Tutti: Making SSD-Backed KV Cache Practical for Long-Context LLM Serving.**](https://arxiv.org/abs/2605.03375) _Shi Qiu, Yifan Hu, Xintao Wang, Wenhao Zhu, Jianqin Yan, Hao Chen, Kaiqiang Xu, Kai Chen, Yiming Zhang._ Arxiv 2026.

12. [**Parallel Context Compaction for Long-Horizon LLM Agent Serving.**](https://arxiv.org/abs/2605.23296) _Musa Cim, Burak Topcu, Chita Das, Mahmut Taylan Kandemir._ Arxiv 2026.

13. [**RedKnot: Efficient Long-Context LLM Serving with Head-Aware KV Reuse and SegPagedAttention.**](https://arxiv.org/abs/2606.06256) _Yang Liu, ZhaoKai Luo, HuaYi Jin, ZhiYong Wang, RuoZhou He, BoYu Wang, Guanjie Chen, Junhao Hu._ Arxiv 2026.
