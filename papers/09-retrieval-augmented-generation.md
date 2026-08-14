# 9. Retrieval-Augmented Generation

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [9.1 Long-Document QA & Iterative Reasoning RAG](#91-long-document-qa--iterative-reasoning-rag)
- [9.2 Long-Context vs RAG: Comparison & Hybrid](#92-long-context-vs-rag-comparison--hybrid)
- [9.3 Memory-Augmented RAG](#93-memory-augmented-rag)
- [9.4 RAG Pipelines: Chunk Caches & KV Reuse](#94-rag-pipelines-chunk-caches--kv-reuse)
- [9.5 Retriever, Indexing & RAG Optimization](#95-retriever-indexing--rag-optimization)
- [9.6 RAG Surveys & Evaluation](#96-rag-surveys--evaluation)
<!-- /chapter-toc -->

#### 9.1 Long-Document QA & Iterative Reasoning RAG

1. [**Retrieval Meets Reasoning: Dynamic In-Context Editing for Long-Text Understanding.**](https://arxiv.org/abs/2406.12331) _Weizhi Fei, Xueyan Niu, Guoqing Xie, Yanhua Zhang, Bo Bai, Lei Deng, Wei Han._ Arxiv 2024.

2. [**FoRAG: Factuality-optimized Retrieval Augmented Generation for Web-enhanced Long-form Question Answering.**](https://arxiv.org/abs/2406.13779) _Tianchi Cai, Zhiwen Tan, Xierui Song, Tao Sun, Jiyan Jiang, Yunqi Xu, Yinger Zhang, Jinjie Gu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/forag)

3. [**Retrieve, Summarize, Plan: Advancing Multi-hop Question Answering with an Iterative Approach.**](https://arxiv.org/abs/2407.13101) _Zhouyu Jiang, Mengshu Sun, Lei Liang, Zhiqiang Zhang._ Arxiv 2024.

4. [**Making Long-Context Language Models Better Multi-Hop Reasoners.**](https://arxiv.org/abs/2408.03246) _Yanyang Li, Shuo Liang, Michael R. Lyu, Liwei Wang._ ACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/LaVi-Lab/LongContextReasoner)](https://github.com/LaVi-Lab/LongContextReasoner)

5. [**Writing in the Margins: Better Inference Pattern for Long Context Retrieval.**](https://arxiv.org/abs/2408.14906) _Melisa Russak, Umar Jamil, Christopher Bryant, Kiran Kamble, Axel Magnuson, Mateusz Russak, Waseem AlShikh._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/writer/writing-in-the-margins)](https://github.com/writer/writing-in-the-margins)

6. [**Bridging Context Gaps: Leveraging Coreference Resolution for Long Contextual Understanding.**](https://arxiv.org/abs/2410.01671) _Yanming Liu, Xinyue Peng, Jiannan Cao, Shi Bo, Yanxin Shen, Xuhong Zhang, Sheng Cheng, Xun Wang, Jianwei Yin, Tianyu Du._ Arxiv 2024.

7. [**ALR2: A Retrieve-then-Reason Framework for Long-context Question Answering.**](https://arxiv.org/abs/2410.03227) _Huayang Li, Pat Verga, Priyanka Sen, Bowen Yang, Vijay Viswanathan, Patrick Lewis, Taro Watanabe, Yixuan Su._ Arxiv 2024.

8. [**GARLIC: LLM-Guided Dynamic Progress Control with Hierarchical Weighted Graph for Long Document QA.**](https://arxiv.org/abs/2410.04790) _Xinyu Wang, Yanzheng Xiang, Lin Gui, Yulan He._ Arxiv 2024.

9. [**Enhancing Long Context Performance in LLMs Through Inner Loop Query Mechanism.**](https://arxiv.org/abs/2410.12859) _Yimin Tang, Yurong Xu, Ning Yan, Masood Mortazavi._ NeurIPS 2024.

10. [**LongRAG: A Dual-Perspective Retrieval-Augmented Generation Paradigm for Long-Context Question Answering.**](https://arxiv.org/abs/2410.18050) _Qingfei Zhao, Ruobing Wang, Yukuo Cen, Daren Zha, Shicheng Tan, Yuxiao Dong, Jie Tang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/QingFei1/LongRAG)](https://github.com/QingFei1/LongRAG)

11. [**Eliciting In-context Retrieval and Reasoning for Long-context Large Language Models.**](https://arxiv.org/abs/2501.08248) _Yifu Qiu, Varun Embar, Yizhe Zhang, Navdeep Jaitly, Shay B. Cohen, Benjamin Han._ Arxiv 2024.

12. [**MuDAF: Long-Context Multi-Document Attention Focusing through Contrastive Learning on Attention Heads.**](https://arxiv.org/abs/2502.13963) _Weihao Liu, Ning Wu, Shiping Yang, Wenbiao Ding, Shining Liang, Ming Gong, Dongmei Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/NeosKnight233/MuDAF)](https://github.com/NeosKnight233/MuDAF)

13. [**ReaRAG: Knowledge-guided Reasoning Enhances Factuality of Large Reasoning Models with Iterative Retrieval Augmented Generation.**](https://arxiv.org/abs/2503.21729) _Zhicheng Lee, Shulin Cao, Jinxin Liu, Jiajie Zhang, Weichuan Liu, Xiaoyin Che, Lei Hou, Juanzi Li._ Arxiv 2025.

14. [**FReM: A Flexible Reasoning Mechanism for Balancing Quick and Slow Thinking in Long-Context Question Answering.**](https://arxiv.org/abs/2503.22985) _Zhengyi Zhao, Shubo Zhang, Zezhong Wang, Bin Liang, Binyang Li, Kam-Fai Wong._ Arxiv 2025.

15. [**Dynamic Chunking and Selection for Reading Comprehension of Ultra-Long Context in Large Language Models.**](https://arxiv.org/abs/2506.00773) _Boheng Sheng, Jiacheng Yao, Meicong Zhang, Guoxiu He._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ECNU-Text-Computing/DCS)](https://github.com/ECNU-Text-Computing/DCS)

16. [**Imagination Augmented Generation: Learning to Imagine Richer Context for Question Answering over Large Language Models.**](https://arxiv.org/abs/2403.15268) _Huanxuan Liao, Shizhu He, Yao Xu, Yuanzhe Zhang, Kang Liu, Shengping Liu, Jun Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Xnhyacinth/IAG)](https://github.com/Xnhyacinth/IAG)

17. [**SEGMENT+: Long Text Processing with Short-Context Language Models.**](https://arxiv.org/abs/2410.06519) _Wei Shi, Shuang Li, Kerun Yu, Jinglei Chen, Zujie Liang, Xinhui Wu, Yuxi Qian, Feng Wei, Bo Zheng, Jiaqing Liang, Jiangjie Chen, Yanghua Xiao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WeiShi-9/segmentplus)](https://github.com/WeiShi-9/segmentplus)

18. [**LLM×MapReduce: Simplified Long-Sequence Processing using Large Language Models.**](https://arxiv.org/abs/2410.09342) _Zihan Zhou, Chong Li, Xinyi Chen, Shuo Wang, Yu Chao, Zhili Li, Haoyu Wang, Rongqiao An, Qi Shi, Zhixing Tan, Xu Han, Xiaodong Shi, Zhiyuan Liu, Maosong Sun._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/thunlp/LLMxMapReduce)](https://github.com/thunlp/LLMxMapReduce)

#### 9.2 Long-Context vs RAG: Comparison & Hybrid

1. [**Walking Down the Memory Maze: Beyond Context Limit through Interactive Reading.**](https://arxiv.org/abs/2310.05029) _Howard Chen, Ramakanth Pasunuru, Jason Weston, Asli Celikyilmaz._ Arxiv 2023.

2. [**Retrieval Head Mechanistically Explains Long-Context Factuality.**](https://arxiv.org/abs/2404.15574) _Wenhao Wu, Yizhong Wang, Guangxuan Xiao, Hao Peng, Yao Fu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nightdessert/Retrieval_Head)](https://github.com/nightdessert/Retrieval_Head)

3. [**Are Long-LLMs A Necessity For Long-Context Tasks?.**](https://arxiv.org/abs/2405.15318) _Hongjin Qian, Zheng Liu, Peitian Zhang, Kelong Mao, Yujia Zhou, Xu Chen, Zhicheng Dou._ Arxiv 2024.

4. [**LongRAG: Enhancing Retrieval-Augmented Generation with Long-context LLMs.**](https://arxiv.org/abs/2406.15319) _Ziyan Jiang, Xueguang Ma, Wenhu Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/LongRAG)](https://github.com/TIGER-AI-Lab/LongRAG)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://tiger-ai-lab.github.io/LongRAG/)

5. [**In Defense of RAG in the Era of Long-Context Language Models.**](https://arxiv.org/abs/2409.01666) _Tan Yu, Anbang Xu, Rama Akkiraju._ Arxiv 2024.

6. [**Inference Scaling for Long-Context Retrieval Augmented Generation.**](https://arxiv.org/abs/2410.04343) _Zhenrui Yue, Honglei Zhuang, Aijun Bai, Kai Hui, Rolf Jagerman, Hansi Zeng, Zhen Qin, Dong Wang, Xuanhui Wang, Michael Bendersky._ Arxiv 2024.

7. [**Long-Context LLMs Meet RAG: Overcoming Challenges for Long Inputs in RAG.**](https://arxiv.org/abs/2410.05983) _Bowen Jin, Jinsung Yoon, Jiawei Han, Sercan O. Arik._ Arxiv 2024.

#### 9.3 Memory-Augmented RAG

1. [**KG-RAG: Bridging the Gap Between Knowledge and Creativity.**](https://arxiv.org/abs/2405.12035) _Diego Sanmartin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dsanmart/KG-RAG)](https://github.com/dsanmart/KG-RAG)

2. [**HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models.**](https://arxiv.org/abs/2405.14831) _Bernal Jiménez Gutiérrez, Yiheng Shu, Yu Gu, Michihiro Yasunaga, Yu Su._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/OSU-NLP-Group/HippoRAG)](https://github.com/OSU-NLP-Group/HippoRAG)

3. [**FragRel: Exploiting Fragment-level Relations in the External Memory of Large Language Models.**](https://arxiv.org/abs/2406.03092) _Xihang Yue, Linchao Zhu, Yi Yang._ Arxiv 2024.

4. [**Memory3: Language Modeling with Explicit Memory.**](https://arxiv.org/abs/2407.01178) _Hongkang Yang, Zehao Lin, Wenjin Wang, Hao Wu, Zhiyu Li, Bo Tang, Wenqiang Wei, Jinbo Wang, Zeyun Tang, Shichao Song, Chenyang Xi, Yu Yu, Kai Chen, Feiyu Xiong, Linpeng Tang, Weinan E._ Arxiv 2024.

5. [**MemLong: Memory-Augmented Retrieval for Long Text Modeling.**](https://arxiv.org/abs/2408.16967) _Weijie Liu, Zecheng Tang, Juntao Li, Kehai Chen, Min Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Bui1dMySea/MemLong)](https://github.com/Bui1dMySea/MemLong)

6. [**MemoRAG: Moving towards Next-Gen RAG Via Memory-Inspired Knowledge Discovery.**](https://arxiv.org/abs/2409.05591) _Hongjin Qian, Peitian Zhang, Zheng Liu, Kelong Mao, Zhicheng Dou._ Arxiv 2024.

7. [**Graph of Records: Boosting Retrieval Augmented Generation for Long-context Summarization with Graphs.**](https://arxiv.org/abs/2410.11001) _Haozhen Zhang, Tao Feng, Jiaxuan You._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ulab-uiuc/GoR)](https://github.com/ulab-uiuc/GoR)

8. [**Long Context Modeling with Ranked Memory-Augmented Retrieval.**](https://arxiv.org/abs/2503.14800) _Ghadir Alselwi, Hao Xue, Shoaib Jameel, Basem Suleiman, Flora D. Salim, Imran Razzak._ Arxiv 2025.

9. [**Tuning LLMs by RAG Principles: Towards LLM-native Memory.**](https://arxiv.org/abs/2503.16071) _Jiale Wei, Shuchi Wu, Ruochen Liu, Xiang Ying, Jingbo Shang, Fangbo Tao._ Arxiv 2025.

10. [**Enhancing Long-Term Memory using Hierarchical Aggregate Tree for Retrieval Augmented Generation.**](https://arxiv.org/abs/2406.06124) _Aadharsh Aadhithya A, Sachin Kumar S, Soman K.P._ Arxiv 2024.

11. [**Thinking Ahead: Prospection-Guided Retrieval of Memory with Language Models.**](https://arxiv.org/abs/2605.14177) _Harshita Chopra, Krishna Kant Chintalapudi, Suman Nath, Ryen W. White, Chirag Shah._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/harshita-chopra/PGR-mem)](https://github.com/harshita-chopra/PGR-mem)

12. [**Why Neighborhoods Matter: Traversal Context and Provenance in Agentic GraphRAG.**](https://arxiv.org/abs/2605.15109) _Riccardo Terrenzi, Maximilian von Zastrow, Serkan Ayvaz._ Arxiv 2026.

#### 9.4 RAG Pipelines: Chunk Caches & KV Reuse

1. [**Attendre: Wait To Attend By Retrieval With Evicted Queries in Memory-Based Transformers for Long Context Processing.**](https://arxiv.org/abs/2401.04881) _Zi Yang, Nan Hua._ Arxiv 2024.

2. [**TurboRAG: Accelerating Retrieval-Augmented Generation with Precomputed KV Caches for Chunked Text.**](https://arxiv.org/abs/2410.07590) _Songshuo Lu, Hua Wang, Yutian Rong, Zhi Chen, Yaohua Tang._ Arxiv 2024.

3. [**CacheFocus: Dynamic Cache Re-Positioning for Efficient Retrieval-Augmented Generation.**](https://arxiv.org/abs/2502.11101) _Kun-Hui Lee, Eunhwan Park, Donghoon Han, Seung-Hoon Na._ Arxiv 2025.

4. [**Cache-Craft: Managing Chunk-Caches for Efficient Retrieval-Augmented Generation.**](https://arxiv.org/abs/2502.15734) _Shubham Agarwal, Sai Sundaresan, Subrata Mitra, Debabrata Mahapatra, Archit Gupta, Rounak Sharma, Nirmal Joshua Kapu, Tong Yu, Shiv Saini._ SIGMOD 2025.

5. [**Cartridges at Scale: Training Modular KV Caches over Large Document Collections.**](https://arxiv.org/abs/2606.04557) _Momchil Hardalov, Gonzalo Iglesias, Adrià de Gispert._ Arxiv 2026.

6. [**LazyAttention: Efficient Retrieval-Augmented Generation with Deferred Positional Encoding.**](https://arxiv.org/abs/2606.04302) _Haocheng Xia, Mihir Pamnani, Hanxi Fang, Supawit Chockchowwat, Yongjoo Park._ ICML 2026.

7. [**Can I Buy Your KV Cache?**](https://arxiv.org/abs/2606.13361) _Luoyuan Zhang._ Arxiv 2026.

#### 9.5 Retriever, Indexing & RAG Optimization

1. [**BGE Landmark Embedding: A Chunking-Free Embedding Method For Retrieval Augmented Long-Context Large Language Models.**](https://arxiv.org/abs/2402.11573) _Kun Luo, Zheng Liu, Shitao Xiao, Kang Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding)

2. [**Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity.**](https://arxiv.org/abs/2403.14403) _Soyeong Jeong, Jinheon Baek, Sukmin Cho, Sung Ju Hwang, Jong C. Park._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/starsuzi/Adaptive-RAG)](https://github.com/starsuzi/Adaptive-RAG)

3. [**RQ-RAG: Learning to Refine Queries for Retrieval Augmented Generation.**](https://arxiv.org/abs/2404.00610) _Chi-Min Chan, Chunpu Xu, Ruibin Yuan, Hongyin Luo, Wei Xue, Yike Guo, Jie Fu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/chanchimin/RQ-RAG)](https://github.com/chanchimin/RQ-RAG)

4. [**Improving Retrieval Augmented Open-Domain Question-Answering with Vectorized Contexts.**](https://arxiv.org/abs/2404.02022) _Zhuo Chen, Xinyu Wang, Yong Jiang, Pengjun Xie, Fei Huang, Kewei Tu._ Arxiv 2024.

5. [**Superposition Prompting: Improving and Accelerating Retrieval-Augmented Generation.**](https://arxiv.org/abs/2404.06910) _Thomas Merth, Qichen Fu, Mohammad Rastegari, Mahyar Najibi._ Arxiv 2024.

6. [**Multi-view Content-aware Indexing for Long Document Retrieval.**](https://arxiv.org/abs/2404.15103) _Kuicai Dong, Derrick Goh Xin Deik, Yi Quan Lee, Hao Zhang, Xiangyang Li, Cong Zhang, Yong Liu._ Arxiv 2024.

7. [**FlashBack:Efficient Retrieval-Augmented Language Modeling for Long Context Inference.**](https://arxiv.org/abs/2405.04065) _Runheng Liu, Xingchen Xiao, Heyan Huang, Zewen Chi, Zhijing Wu._ Arxiv 2024.

8. [**Accelerating Inference of Retrieval-Augmented Generation via Sparse Context Selection.**](https://arxiv.org/abs/2405.16178) _Yun Zhu, Jia-Chen Gu, Caitlin Sikora, Ho Ko, Yinxiao Liu, Chu-Cheng Lin, Lei Shu, Liangchen Luo, Lei Meng, Bang Liu, Jindong Chen._ Arxiv 2024.

9. [**Multi-Head RAG: Solving Multi-Aspect Problems with LLMs.**](https://arxiv.org/abs/2406.05085) _Maciej Besta, Ales Kubicek, Roman Niggli, Robert Gerstenberger, Lucas Weitzendorf, Mingyuan Chi, Patrick Iff, Joanna Gajda, Piotr Nyczyk, Jürgen Müller, Hubert Niewiadomski, Marcin Chrapek, Michał Podstawski, Torsten Hoefler._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/spcl/MRAG)](https://github.com/spcl/MRAG)

10. [**From Artificial Needles to Real Haystacks: Improving Retrieval Capabilities in LLMs by Finetuning on Synthetic Data.**](https://arxiv.org/abs/2406.19292) _Zheyang Xiong, Vasilis Papageorgiou, Kangwook Lee, Dimitris Papailiopoulos._ Arxiv 2024.

11. [**Speculative RAG: Enhancing Retrieval Augmented Generation through Drafting.**](https://arxiv.org/abs/2407.08223) _Zilong Wang, Zifeng Wang, Long Le, Huaixiu Steven Zheng, Swaroop Mishra, Vincent Perot, Yuwei Zhang, Anush Mattapalli, Ankur Taly, Jingbo Shang, Chen-Yu Lee, Tomas Pfister._ Arxiv 2024.

12. [**R^2AG: Incorporating Retrieval Information into Retrieval Augmented Generation.**](https://arxiv.org/abs/2406.13249) _Fuda Ye, Shuangyin Li, Yongqi Zhang, Lei Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yefd/RRAG)](https://github.com/yefd/RRAG)

13. [**You Only Use Reactive Attention Slice For Long Context Retrieval.**](https://arxiv.org/abs/2409.13695) _Yun Joon Soh, Hanxian Huang, Yuandong Tian, Jishen Zhao._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yjsoh/youra)](https://github.com/yjsoh/youra)

14. [**SMART-RAG: Selection using Determinantal Matrices for Augmented Retrieval.**](https://arxiv.org/abs/2409.13992) _Jiatao Li, Xinyu Hu, Xiaojun Wan._ Arxiv 2024.

15. [**Lighter And Better: Towards Flexible Context Adaptation For Retrieval Augmented Generation.**](https://arxiv.org/abs/2409.15699) _Zheng Liu, Chenyuan Wu, Ninglu Shao, Shitao Xiao, Chaozhuo Li, Defu Lian._ CIKM 2024.

16. [**Astute RAG: Overcoming Imperfect Retrieval Augmentation and Knowledge Conflicts for Large Language Models.**](https://arxiv.org/abs/2410.07176) _Fei Wang, Xingchen Wan, Ruoxi Sun, Jiefeng Chen, Sercan Ö. Arık._ Arxiv 2024.

17. [**ChuLo: Chunk-Level Key Information Representation for Long Document Processing.**](https://arxiv.org/abs/2410.11119) _Yan Li, Caren Han, Yue Dai, Feiqi Cao._ Arxiv 2024.

18. [**Reducing Distraction in Long-Context Language Models by Focused Learning.**](https://arxiv.org/abs/2411.05928) _Zijun Wu, Bingyuan Liu, Ran Yan, Lei Chen, Thomas Delteil._ Arxiv 2024.

19. [**Sliding Windows Are Not the End: Exploring Full Ranking with Long-Context Large Language Models.**](https://arxiv.org/abs/2412.14574) _Wenhan Liu, Xinyu Ma, Yutao Zhu, Ziliang Zhao, Shuaiqiang Wang, Dawei Yin, Zhicheng Dou._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/8421BCD/fullrank)](https://github.com/8421BCD/fullrank)

20. [**OkraLong: A Flexible Retrieval-Augmented Framework for Long-Text Query Processing.**](https://arxiv.org/abs/2503.02603) _Yulong Hui, Yihao Liu, Yao Lu, Huanchen Zhang._ Arxiv 2025.

21. [**Focus Directions Make Your Language Models Pay More Attention to Relevant Contexts.**](https://arxiv.org/abs/2503.23306) _Youxiang Zhu, Ruochen Li, Danqing Wang, Daniel Haehn, Xiaohui Liang._ Arxiv 2025.

22. [**Conflict-Aware Soft Prompting for Retrieval-Augmented Generation.**](https://arxiv.org/abs/2508.15253) _Eunseong Choi, June Park, Hyeri Lee, Jongwuk Lee._ EMNLP 2025.
23. [**Infini-gram: Scaling Unbounded n-gram Language Models to a Trillion Tokens.**](https://arxiv.org/abs/2401.17377) _Jiacheng Liu, Sewon Min, Luke Zettlemoyer, Yejin Choi, Hannaneh Hajishirzi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/liujch1998/infini-gram)](https://github.com/liujch1998/infini-gram)

24. [**PEAR: Position-Embedding-Agnostic Attention Re-weighting Enhances Retrieval-Augmented Generation with Zero Inference Overhead.**](https://arxiv.org/abs/2409.19745) _Tao Tan, Yining Qian, Ang Lv, Hongzhan Lin, Songhao Wu, Yongbo Wang, Feng Wang, Jingtong Wu, Xin Lu, Rui Yan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TTArch/PEAR-RAG)](https://github.com/TTArch/PEAR-RAG)

25. [**Efficient Long-range Language Modeling with Self-supervised Causal Retrieval.**](https://arxiv.org/abs/2410.01651) _Xiang Hu, Zhihao Teng, Wei Wu, Kewei Tu._ Arxiv 2024.

26. [**Hierarchical Document Refinement for Long-context Retrieval-augmented Generation.**](https://arxiv.org/abs/2505.10413) _Jiajie Jin, Xiaoxi Li, Guanting Dong, Yuyao Zhang, Yutao Zhu, Yongkang Wu, Zhonghua Li, Qi Ye, Zhicheng Dou._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ignorejjj/LongRefiner)](https://github.com/ignorejjj/LongRefiner)

27. [**Is Grep All You Need? How Agent Harnesses Reshape Agentic Search.**](https://arxiv.org/abs/2605.15184) _Sahil Sen, Akhil Kasturi, Elias Lumer, Anmol Gulati, Vamse Kumar Subbiah._ Arxiv 2026.

28. [**Stop Overthinking: Unlocking Efficient Listwise Reranking with Minimal Reasoning.**](https://arxiv.org/abs/2605.14450) _Danyang Liu, Kan Li._ Arxiv 2026.

#### 9.6 RAG Surveys & Evaluation

1. [**A Survey on RAG Meets LLMs: Towards Retrieval-Augmented Large Language Models.**](https://arxiv.org/abs/2405.06211) _Yujuan Ding, Wenqi Fan, Liangbo Ning, Shijie Wang, Hengyun Li, Dawei Yin, Tat-Seng Chua, Qing Li._ Arxiv 2024.

2. [**Evaluation of Retrieval-Augmented Generation: A Survey.**](https://arxiv.org/abs/2405.07437) _Hao Yu, Aoran Gan, Kai Zhang, Shiwei Tong, Qi Liu, Zhaofeng Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/YHPeter/Awesome-RAG-Evaluation)](https://github.com/YHPeter/Awesome-RAG-Evaluation)

3. [**Contextual Compression in Retrieval-Augmented Generation for Large Language Models: A Survey.**](https://arxiv.org/abs/2409.13385) _Sourav Verma._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/SrGrace/Contextual-Compression)](https://github.com/SrGrace/Contextual-Compression)

4. [**Retrieval Augmented Generation (RAG) and Beyond: A Comprehensive Survey on How to Make your LLMs use External Data More Wisely.**](https://arxiv.org/abs/2409.14924) _Siyun Zhao, Yuqing Yang, Zilong Wang, Zhiyuan He, Luna K. Qiu, Lili Qiu._ Arxiv 2024.

5. [**A Survey on Knowledge-Oriented Retrieval-Augmented Generation.**](https://arxiv.org/abs/2503.10677) _Mingyue Cheng, Yucong Luo, Jie Ouyang, Qi Liu, Huijie Liu, Li Li, Shuo Yu, Bohou Zhang, Jiawei Cao, Jie Ma, Daoyu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/USTCAGI/Awesome-Papers-Retrieval-Augmented-Generation)](https://github.com/USTCAGI/Awesome-Papers-Retrieval-Augmented-Generation)

6. [**RAGChecker: A Fine-grained Framework for Diagnosing Retrieval-Augmented Generation.**](https://arxiv.org/abs/2408.08067) _Dongyu Ru, Lin Qiu, Xiangkun Hu, Tianhang Zhang, Peng Shi, Shuaichen Chang, Cheng Jiayang, Cunxiang Wang, Shichao Sun, Huanyu Li, Zizhao Zhang, Binjie Wang, Jiarong Jiang, Tong He, Zhiguo Wang, Pengfei Liu, Yue Zhang, Zheng Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/amazon-science/RAGChecker)](https://github.com/amazon-science/RAGChecker)

7. [**Why Retrieval-Augmented Generation Fails: A Graph Perspective.**](https://arxiv.org/abs/2605.14192) _Kai Guo, Xinnan Dai, Zhibo Zhang, Nuohan Lin, Shenglai Zeng, Jie Ren, Haoyu Han, Jiliang Tang._ Arxiv 2026.
