# 6. Position Encoding & Length Extrapolation

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [6.1 Positional Encoding Variants](#61-positional-encoding-variants)
- [6.2 YaRN / NTK / Position Interpolation](#62-yarn--ntk--position-interpolation)
- [6.3 Length Extrapolation & Inference-Time Context Extension](#63-length-extrapolation--inference-time-context-extension)
<!-- /chapter-toc -->

#### 6.1 Positional Encoding Variants

1. [**RoFormer: Enhanced Transformer with Rotary Position Embedding.**](https://arxiv.org/abs/2104.09864) _Jianlin Su, Yu Lu, Shengfeng Pan, Ahmed Murtadha, Bo Wen, Yunfeng Liu._ Arxiv 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/ZhuiyiTechnology/roformer)](https://github.com/ZhuiyiTechnology/roformer)

2. [**KERPLE: Kernelized Relative Positional Embedding for Length Extrapolation.**](https://arxiv.org/abs/2205.09921) _Ta-Chung Chi, Ting-Han Fan, Peter J. Ramadge, Alexander I. Rudnicky._ Arxiv 2022.

3. [**Randomized Positional Encodings Boost Length Generalization of Transformers.**](https://aclanthology.org/2023.acl-short.161/) _Anian Ruoss, Grégoire Delétang, Tim Genewein, Jordi Grau-Moya, Róbert Csordás, Mehdi Bennani, Shane Legg, Joel Veness._ ACL 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/randomized_positional_encodings)](https://github.com/google-deepmind/randomized_positional_encodings)

4. [**The Impact of Positional Encoding on Length Generalization in Transformers.**](https://arxiv.org/abs/2305.19466) _Amirhossein Kazemnejad, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Payel Das, Siva Reddy._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/McGill-NLP/length-generalization)](https://github.com/McGill-NLP/length-generalization)

5. [**Two Stones Hit One Bird: Bilevel Positional Encoding for Better Length Extrapolation.**](https://arxiv.org/abs/2401.16421) _Zhenyu He, Guhao Feng, Shengjie Luo, Kai Yang, Di He, Jingjing Xu, Zhi Zhang, Hongxia Yang, Liwei Wang._ ICML 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zhenyuhe00/BiPE)](https://github.com/zhenyuhe00/BiPE)

6. [**Found in the Middle: How Language Models Use Long Contexts Better via Plug-and-Play Positional Encoding.**](https://arxiv.org/abs/2403.04797) _Zhenyu Zhang, Runjin Chen, Shiwei Liu, Zhewei Yao, Olatunji Ruwase, Beidi Chen, Xiaoxia Wu, Zhangyang Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/VITA-Group/Ms-PoE)](https://github.com/VITA-Group/Ms-PoE)

7. [**DAPE: Data-Adaptive Positional Encoding for Length Extrapolation.**](https://arxiv.org/abs/2405.14722) _Chuanyang Zheng, Yihang Gao, Han Shi, Minbin Huang, Jingyao Li, Jing Xiong, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE)](https://github.com/chuanyang-Zheng/DAPE)

8. [**Contextual Position Encoding: Learning to Count What's Important.**](https://arxiv.org/abs/2405.18719) _Olga Golovneva, Tianlu Wang, Jason Weston, Sainbayar Sukhbaatar._ Arxiv 2024.

9. [**Position Coupling: Improving Length Generalization of Arithmetic Transformers Using Task Structure.**](https://openreview.net/forum?id=5cIRdGM1uG) _Hanseul Cho, Jaeyoung Cha, Pranjal Awasthi, Srinadh Bhojanapalli, Anupam Gupta, Chulhee Yun._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HanseulJo/position-coupling)](https://github.com/HanseulJo/position-coupling)

10. [**An Efficient Recipe for Long Context Extension via Middle-Focused Positional Encoding.**](https://arxiv.org/abs/2406.07138) _Tong Wu, Yanpeng Zhao, Zilong Zheng._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/cream)](https://github.com/bigai-nlco/cream)

11. [**3D-RPE: Enhancing Long-Context Modeling Through 3D Rotary Position Encoding.**](https://arxiv.org/abs/2406.09897) _Xindian Ma, Wenyuan Liu, Peng Zhang, Nan Xu._ Arxiv 2024.

12. [**DAPE V2: Process Attention Score as Feature Map for Length Extrapolation.**](https://arxiv.org/abs/2410.04798) _Chuanyang Zheng, Yihang Gao, Han Shi, Jing Xiong, Jiankai Sun, Jingyao Li, Minbin Huang, Xiaozhe Ren, Michael Ng, Xin Jiang, Zhenguo Li, Yu Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chuanyang-Zheng/DAPE)](https://github.com/chuanyang-Zheng/DAPE)

13. [**HoPE (NoDecay): A Novel Positional Encoding Without Long-Term Decay for Enhanced Context Awareness and Extrapolation.**](https://arxiv.org/abs/2410.21216) _Yuhan Chen, Ang Lv, Jian Luan, Bin Wang, Wei Liu._ Arxiv 2024.

14. [**Circuit Complexity Bounds for RoPE-based Transformer Architecture.**](https://arxiv.org/abs/2411.07602) _Bo Chen, Xiaoyu Li, Yingyu Liang, Jiangxuan Long, Zhenmei Shi, Zhao Song._ Arxiv 2024.

15. [**DINT Transformer.**](https://arxiv.org/abs/2501.17486) _Yueyang Cang, Yuhang Liu, Xiaoteng Zhang, Erlu Zhao, Li Shi._ Arxiv 2025.

16. [**The Rotary Position Embedding May Cause Dimension Inefficiency in Attention Heads for Long-Distance Retrieval.**](https://arxiv.org/abs/2502.11276) _Ting-Rui Chiang, Dani Yogatama._ Arxiv 2025.

17. [**Forgetting Transformer: Softmax Attention with a Forget Gate.**](https://arxiv.org/abs/2503.02130) _Zhixuan Lin, Evgenii Nikishin, Xu Owen He, Aaron Courville._ ICLR 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zhixuan-lin/forgetting-transformer)](https://github.com/zhixuan-lin/forgetting-transformer)

18. [**Layer-Specific Scaling of Positional Encodings for Superior Long-Context Modeling.**](https://arxiv.org/abs/2503.04355) _Zhenghua Wang, Yiran Ding, Changze Lv, Zhibo Xu, Tianlong Li, Tianyuan Shi, Xiaoqing Zheng, Xuanjing Huang._ Arxiv 2025.

19. [**SWAN-GPT: An Efficient and Scalable Approach for Long-Context Language Modeling.**](https://arxiv.org/abs/2504.08719) _Krishna C. Puvvada, Faisal Ladhak, Santiago Akle Serrano, Cheng-Ping Hsieh, Shantanu Acharya, Somshubra Majumdar, Fei Jia, Samuel Kriman, Simeng Sun, Dima Rekesh, Boris Ginsburg._ Arxiv 2025.

20. [**Effective Length Extrapolation via Dimension-Wise Positional Embeddings Manipulation.**](https://arxiv.org/abs/2504.18857) _Yi Lu, Wanxu Zhao, Xin Zhou, Chenxin An, Chenglong Wang, Shuo Li, Yuming Yang, Jun Zhao, Tao Ji, Tao Gui, Qi Zhang, Xuanjing Huang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LuLuLuyi/DPE)](https://github.com/LuLuLuyi/DPE)

21. [**Mitigating Posterior Salience Attenuation in Long-Context LLMs with Positional Contrastive Decoding.**](https://arxiv.org/abs/2506.08371) _Zikai Xiao, Ziyang Wang, Wen Ma, Yan Zhang, Wei Shen, Yan Wang, Luqi Gong, Zuozhu Liu._ Arxiv 2025.

22. [**Bayesian Attention Mechanism: A Probabilistic Framework for Positional Encoding and Context Length Extrapolation.**](https://arxiv.org/abs/2505.22842) _Arthur S. Bianchessi, Rodrigo C. Barros, Lucas S. Kupssinskü_ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ArthurSBianchessi/BAM)](https://github.com/ArthurSBianchessi/BAM)

23. [**HoPE (Hyperbolic): Hyperbolic Rotary Positional Encoding for Stable Long-Range Dependency Modeling in Large Language Models.**](https://arxiv.org/abs/2509.05218) _Chang Dai, Hongyu Shan, Mingyang Song, Di Liang._ Arxiv 2025.

24. [**Positional Encoding via Token-Aware Phase Attention.**](https://arxiv.org/abs/2509.12635) _Yu, Wang, Sheng Shen, Rémi Munos, Hongyuan Zhan, Yuandong Tian._ Arxiv 2025.

25. [**RePo: Language Models with Context Re-Positioning.**](https://arxiv.org/abs/2512.14391) _Huayang Li, Tianyu Zhao, Richard Sproat._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SakanaAI/repo)](https://github.com/SakanaAI/repo)

26. [**Length Generalization of Causal Transformers without Position Encoding.**](https://arxiv.org/abs/2404.12224) _Jie Wang, Tao Ji, Yuanbin Wu, Hang Yan, Tao Gui, Qi Zhang, Xuanjing Huang, Xiaoling Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AntNLP/nope_head_scale)](https://github.com/AntNLP/nope_head_scale)

27. [**Rope to Nope and Back Again: A New Hybrid Attention Strategy.**](https://arxiv.org/abs/2501.18795) _Bowen Yang, Bharat Venkitesh, Dwarak Talupuru, Hangyu Lin, David Cairuz, Phil Blunsom, Acyr Locatelli._ Arxiv 2025.

28. [**Extending the Context of Pretrained LLMs by Dropping Their Positional Embeddings (DroPE).**](https://arxiv.org/abs/2512.12167) _Yoav Gelberg, Koshi Eguchi, Takuya Akiba, Edoardo Cetin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/SakanaAI/DroPE)](https://github.com/SakanaAI/DroPE)

29. [**Extensible Embedding: A Flexible Multipler For LLM's Context Length.**](https://arxiv.org/abs/2402.11577) _Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

30. [**Base of RoPE Bounds Context Length.**](https://arxiv.org/abs/2405.14591) _Xin Men, Mingyu Xu, Bingning Wang, Qingyu Zhang, Hongyu Lin, Xianpei Han, Weipeng Chen._ Arxiv 2024.

31. [**Periodic RoPE for Infinite Context LLMs.**](https://arxiv.org/abs/2605.27980) _Simin Huo._ Arxiv 2026.

32. [**Disentangling the Expressivity of RoPE.**](https://arxiv.org/abs/2608.11909) _Selim Jerad, Anej Svete, Jiaoda Li, Ryan Cotterell._ Arxiv 2026.

33. [**Anti-Periodic Positional Encoding: Möbius Boundary Conditions Make In-Context Retrieval Reliable.**](https://arxiv.org/abs/2607.21405) _Ji Ho Bae._ Arxiv 2026.

#### 6.2 YaRN / NTK / Position Interpolation

1. [**Extending Context Window of Large Language Models via Positional Interpolation.**](https://arxiv.org/abs/2306.15595) _Shouyuan Chen, Sherman Wong, Liangjian Chen, Yuandong Tian._ Arxiv 2023.

2. [**YaRN: Efficient Context Window Extension of Large Language Models.**](https://arxiv.org/abs/2309.00071) _Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/jquesnelle/yarn)](https://github.com/jquesnelle/yarn)

3. [**Scaling Laws of RoPE-based Extrapolation.**](https://arxiv.org/abs/2310.05209) _Xiaoran Liu, Hang Yan, Shuo Zhang, Chenxin An, Xipeng Qiu, Dahua Lin._ Arxiv 2023.

4. [**LongRoPE: Extending LLM ContextWindow Beyond 2 Million Tokens.**](https://arxiv.org/abs/2402.13753) _Yiran Ding, Li Lyna Zhang, Chengruidong Zhang, Yuanyuan Xu, Ning Shang, Jiahang Xu, Fan Yang, Mao Yang._ Arxiv 2024.

5. [**CLEX: Continuous Length Extrapolation for Large Language Models.**](https://arxiv.org/abs/2310.16450) _Guanzheng Chen, Xin Li, Zaiqiao Meng, Shangsong Liang, Lidong Bing._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/DAMO-NLP-SG/CLEX)](https://github.com/DAMO-NLP-SG/CLEX)

6. [**Resonance RoPE: Improving Context Length Generalization of Large Language Models.**](https://arxiv.org/abs/2403.00071) _Suyuchen Wang, Ivan Kobyzev, Peng Lu, Mehdi Rezagholizadeh, Bang Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sheryc/resonance_rope)](https://github.com/sheryc/resonance_rope)

7. [**A Training-Free Length Extrapolation Approach for LLMs: Greedy Attention Logit Interpolation (GALI).**](https://arxiv.org/abs/2502.02659) _Yan Li, Tianyi Zhang, Zechuan Li, Soyeon Caren Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AcademyCityL/GALI)](https://github.com/AcademyCityL/GALI)

8. [**LongRoPE2: Near-Lossless LLM Context Window Scaling.**](https://arxiv.org/abs/2502.20082) _Ning Shang, Li Lyna Zhang, Siyuan Wang, Gaokai Zhang, Gilsinia Lopez, Fan Yang, Weizhu Chen, Mao Yang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/LongRoPE)](https://github.com/microsoft/LongRoPE)

#### 6.3 Length Extrapolation & Inference-Time Context Extension

1. [**Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation.**](https://arxiv.org/abs/2108.12409) _Ofir Press, Noah A. Smith, Mike Lewis._ ICLR 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/ofirpress/attention_with_linear_biases)](https://github.com/ofirpress/attention_with_linear_biases)

2. [**Dissecting Transformer Length Extrapolation via the Lens of Receptive Field Analysis.**](https://aclanthology.org/2023.acl-long.756/) _Ta-Chung Chi, Ting-Han Fan, Alexander I. Rudnicky, Peter J. Ramadge._ ACL 2023.

3. [**A Length-Extrapolatable Transformer.**](https://aclanthology.org/2023.acl-long.816/) _Yutao Sun, Li Dong, Barun Patra, Shuming Ma, Shaohan Huang, Alon Benhaim, Vishrav Chaudhary, Xia Song, Furu Wei._ ACL 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/sunyt32/torchscale)](https://github.com/sunyt32/torchscale)

4. [**Exploring Transformer Extrapolation.**](https://arxiv.org/abs/2307.10156) _Zhen Qin, Yiran Zhong, Hui Deng._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenNLPLab/Rpe)](https://github.com/OpenNLPLab/Rpe)

5. [**LM-Infinite: Simple On-the-Fly Length Generalization for Large Language Models.**](https://arxiv.org/pdf/2308.16137.pdf) _Chi Han, Qifan Wang, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/LM-Infinite)](https://github.com/kyegomez/LM-Infinite)

6. [**Attention Alignment and Flexible Positional Embeddings Improve Transformer Length Extrapolation.**](https://arxiv.org/pdf/2311.00684v1.pdf) _Ta-Chung Chi,Ting-Han Fan,Alexander I. Rudnicky._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/chijames/Attention-Alignment-Transformer-Length-Extrapolation)](https://github.com/chijames/Attention-Alignment-Transformer-Length-Extrapolation)

7. [**CoCA: Fusing position embedding with Collinear Constrained Attention for fine-tuning free context window extending.**](https://arxiv.org/abs/2309.08646) _Shiyi Zhu, Jing Ye, Wei Jiang, Qi Zhang, Yifan Wu, Jianguo Li._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/codefuse-ai/Collinear-Constrained-Attention)](https://github.com/codefuse-ai/Collinear-Constrained-Attention)

8. [**LLM Maybe LongLM: Self-Extend LLM Context Window Without Tuning.**](https://arxiv.org/abs/2401.01325v1) _Hongye Jin, Xiaotian Han, Jingfeng Yang, Zhimeng Jiang, Zirui Liu, Chia-Yuan Chang, Huiyuan Chen, Xia Hu._ Arxiv 2024.

9. [**Transformers Can Achieve Length Generalization But Not Robustly.**](https://arxiv.org/abs/2402.09371v1) _Yongchao Zhou, Uri Alon, Xinyun Chen, Xuezhi Wang, Rishabh Agarwal, Denny Zhou._ Arxiv 2024.

10. [**Can't Remember Details in Long Documents? You Need Some R&R.**](https://arxiv.org/abs/2403.05004) _Devanshu Agrawal, Shang Gao, Martin Gajek._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/casetext/r-and-r)](https://github.com/casetext/r-and-r)

11. [**InfLLM: Unveiling the Intrinsic Capacity of LLMs for Understanding Extremely Long Sequences with Training-Free Memory.**](https://arxiv.org/abs/2402.04617) _Chaojun Xiao, Pengle Zhang, Xu Han, Guangxuan Xiao, Yankai Lin, Zhengyan Zhang, Zhiyuan Liu, Song Han, Maosong Sun._ Arxiv 2024.

12. [**Naive Bayes-based Context Extension for Large Language Models.**](https://arxiv.org/abs/2403.17552) _Jianlin Su, Murtadha Ahmed, Wenbo, Luo Ao, Mingren Zhu, Yunfeng Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/amurtadha/NBCE-master)](https://github.com/amurtadha/NBCE-master)

13. [**Explicitly Encoding Structural Symmetry is Key to Length Generalization in Arithmetic Tasks.**](https://arxiv.org/abs/2406.01895) _Mahdi Sabbaghi, George Pappas, Hamed Hassani, Surbhi Goel._ Arxiv 2024.

14. [**Mixture of In-Context Experts Enhance LLMs' Long Context Awareness.**](https://arxiv.org/abs/2406.19598) _Hongzhan Lin, Ang Lv, Yuhan Chen, Chen Zhu, Yang Song, Hengshu Zhu, Rui Yan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/p1nksnow/MoICE)](https://github.com/p1nksnow/MoICE)

15. [**Efficient Solutions For An Intriguing Failure of LLMs: Long Context Window Does Not Mean LLMs Can Analyze Long Sequences Flawlessly.**](https://arxiv.org/abs/2408.01866) _Peyman Hosseini, Ignacio Castro, Iacopo Ghinassi, Matthew Purver._ Arxiv 2024.

16. [**Extending Context Window of Large Language Models from a Distributional Perspective.**](https://arxiv.org/abs/2410.01490) _Yingsheng Wu, Yuxuan Gu, Xiaocheng Feng, Weihong Zhong, Dongliang Xu, Qing Yang, Hongtao Liu, Bing Qin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/1180301012/DPRoPE)](https://github.com/1180301012/DPRoPE)

17. [**Why Does the Effective Context Length of LLMs Fall Short?.**](https://arxiv.org/abs/2410.18745) _Chenxin An, Jun Zhang, Ming Zhong, Lei Li, Shansan Gong, Yao Luo, Jingjing Xu, Lingpeng Kong._ Arxiv 2024.

18. [**Two are better than one: Context window extension with multi-grained self-injection.**](https://arxiv.org/abs/2410.19318) _Wei Han, Pan Zhou, Soujanya Poria, Shuicheng Yan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Clement25/SharedLLM)](https://github.com/Clement25/SharedLLM)

19. [**What is Wrong with Perplexity for Long-context Language Modeling?.**](https://arxiv.org/abs/2410.23771) _Lizhe Fang, Yifei Wang, Zhaoyang Liu, Chenheng Zhang, Stefanie Jegelka, Jinyang Gao, Bolin Ding, Yisen Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/PKU-ML/LongPPL)](https://github.com/PKU-ML/LongPPL)

20. [**Transformers Can Do Arithmetic with the Right Embeddings.**](https://openreview.net/forum?id=cBFsFt1nDW) _Sean Michael McLeish, Arpit Bansal, Alex Stein, Neel Jain, John Kirchenbauer, Brian R. Bartoldson, Bhavya Kailkhura, Abhinav Bhatele, Jonas Geiping, Avi Schwarzschild, Tom Goldstein._ NeurIPS 2024.

21. [**Arithmetic Transformers Can Length-Generalize in Both Operand Length and Count.**](https://arxiv.org/abs/2410.15787) _Hanseul Cho, Jaeyoung Cha, Srinadh Bhojanapalli, Chulhee Yun._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/HanseulJo/position-coupling)](https://github.com/HanseulJo/position-coupling)

22. [**Attention Entropy is a Key Factor: An Analysis of Parallel Context Encoding with Full-attention-based Pre-trained Language Models.**](https://arxiv.org/abs/2412.16545) _Zhisong Zhang, Yan Wang, Xinting Huang, Tianqing Fang, Hongming Zhang, Chenlong Deng, Shuaiyi Li, Dong Yu._ Arxiv 2024.

23. [**DCIS: Efficient Length Extrapolation of LLMs via Divide-and-Conquer Scaling Factor Search.**](https://arxiv.org/abs/2412.18811) _Lei Yang, Shaoyang Xu, Deyi Xiong._ Arxiv 2024.

24. [**Information Entropy Invariance: Enhancing Length Extrapolation in Attention Mechanisms.**](https://arxiv.org/abs/2501.08570) _Kewei Li, Yanwen Kong, Yiping Xu, Lan Huang, Ruochi Zhang, Fengfeng Zhou._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/HT-NEKO/InfoScale)](https://github.com/HT-NEKO/InfoScale)

25. [**SEAL: Scaling to Emphasize Attention for Long-Context Retrieval.**](https://arxiv.org/abs/2501.15225) _Changhun Lee, Jun-gyu Jin, Younghyun Cho, Eunhyeok Park._ Arxiv 2025.

26. [**Unveiling Simplicities of Attention: Adaptive Long-Context Head Identification.**](https://arxiv.org/abs/2502.09647) _Konstantin Donhauser, Charles Arnal, Mohammad Pezeshki, Vivien Cabannes, David Lopez-Paz, Kartik Ahuja._ Arxiv 2025.

27. [**ParallelComp: Parallel Long-Context Compressor for Length Extrapolation.**](https://arxiv.org/abs/2502.14317) _Jing Xiong, Jianghan Shen, Chuanyang Zheng, Zhongwei Wan, Chenyang Zhao, Chiwun Yang, Fanghua Ye, Hongxia Yang, Lingpeng Kong, Ngai Wong._ ICML 2025.

28. [**SELF: Self-Extend the Context Length With Logistic Growth Function.**](https://arxiv.org/abs/2505.17296) _Phat Thanh Dang, Saahil Thoppay, Wang Yang, Qifan Wang, Vipin Chaudhary, Xiaotian Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/alexeipc/SELF-LLM)](https://github.com/alexeipc/SELF-LLM)

29. [**Hierarchical Context Merging: Better Long Context Understanding for Pre-trained LLMs.**](https://arxiv.org/abs/2404.10308) _Woomin Song, Seunghyuk Oh, Sangwoo Mo, Jaehyung Kim, Sukmin Yun, Jung-Woo Ha, Jinwoo Shin._ ICLR 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alinlab/HOMER)](https://github.com/alinlab/HOMER)

30. [**Compress, Gather, and Recompute: REFORMing Long-Context Processing in Transformers.**](https://arxiv.org/abs/2506.01215) _Woomin Song, Sai Muralidhar Jayanthi, Srikanth Ronanki, Kanthashree Mysore Sathyendra, Jinwoo Shin, Aram Galstyan, Shubham Katiyar, Sravan Babu Bodapati._ Arxiv 2025.

31. [**Causal Attention with Lookahead Keys.**](https://arxiv.org/abs/2509.07301) _Zhuoqing Song, Peng Sun, Huizhuo Yuan, Quanquan Gu._ Arxiv 2025.

32. [**XL3M: A Training-free Framework for LLM Length Extension Based on Segment-wise Inference.**](https://arxiv.org/abs/2405.17755) _Shengnan Wang, Youhui Bai, Lin Zhang, Pingyi Zhou, Shixiong Zhao, Gong Zhang, Sen Wang, Renhai Chen, Hua Xu, Hongwei Sun._ Arxiv 2024.

33. [**Soaring from 4K to 400K: Extending LLM's Context with Activation Beacon.**](https://arxiv.org/abs/2401.03462) _Peitian Zhang, Zheng Liu, Shitao Xiao, Ninglu Shao, Qiwei Ye, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

34. [**Flexibly Scaling Large Language Models Contexts Through Extensible Tokenization.**](https://arxiv.org/abs/2401.07793) _Ninglu Shao, Shitao Xiao, Zheng Liu, Peitian Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

35. [**Self-Guided Test-Time Training for Long-Context LLMs.**](https://arxiv.org/abs/2607.09415) _Xinyu Zhu, Zhe Xu, Xiaohan Wei, Yunchen Pu, Fei Tian, Chonglin Sun, Kaushik Rangadurai, Hua Zhi, Frank Shyu, Sandeep Pandey, Luke Simon, Yu Meng, Xi Liu._ Arxiv 2026.

36. [**Jet-Long: Efficient Long-Context Extension with Dynamic Bifocal RoPE.**](https://arxiv.org/abs/2607.07740) _Haozhan Tang, Zerui Wang, Yuxian Gu, Song Han, Han Cai._ Arxiv 2026.

37. [**EndPrompt: Efficient Long-Context Extension via Terminal Anchoring.**](https://arxiv.org/abs/2605.14589) _Han Tian, Luxuan Chen, Xinran Chen, Rui Kong, Fang Wang, Jiamin Chen, Jinman Zhao, Yuchen Li, Jiashu Zhao, Shuaiqiang Wang, Haoyi Xiong, Dawei Yin._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/clx1415926/EndPrompt)](https://github.com/clx1415926/EndPrompt)

38. [**From Rigid to Dynamic: Entropy-Guided Adaptive Inference for Long-Context LLMs.**](https://arxiv.org/abs/2606.09508) _Zhanchao Xu, Haoyang Li, Qingfa Xiao, Fei Teng, Chen Jason Zhang, Lei Chen, Qing Li._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/SHA-4096/EntropyInfer)](https://github.com/SHA-4096/EntropyInfer)
