# Long Text Modeling Papers

![](https://img.shields.io/github/last-commit/Xnhyacinth/Long_Text_Modeling_Papers?color=blue) ![](https://img.shields.io/badge/PRs-Welcome-red) 

Mainly Contributed and Maintained by [Xnhyacinth](https://github.com/Xnhyacinth).

Thanks for all great contributors on GitHub!🔥⚡🔥

### Contents

* [1. Survey Papers](#1-Survey-Papers)
* [2. Efficient Transformers](#2-Efficient-Transformers)
  * [2.1 Sparse Transformers](#21-Sparse-Transformers)
  * [2.2 Linear Transformers](#22-Linear-Transformers)
  * [2.3 Hierarchical Transformers](#23-Hierarchical-Transformers)
* [3. Recurrent Transformers](#3-Recurrent-Transformers)
* [4. Length Extrapolation](#4-Length-Extrapolation)    🔥RoPE🔥
* [5. Long Term Memory](#5-Long-Term-Memory)
* [6. Benchmark and Evaluation](#5-Benchmark-and-Evaluation)
* [Acknowledgements](#acknowledgements)

## 1. Survey Papers

1. **Efficient Transformers: A Survey.** *Yi Tay, Mostafa Dehghani, Dara Bahri, Donald Metzler.* Arxiv 2022. [paper](https://arxiv.org/abs/2009.06732)

2. **A Survey on Long Text Modeling with Transformers.** *Zican Dong, Tianyi Tang, Lunyi Li, Wayne Xin Zhao.* Arxiv 2023. [paper](https://arxiv.org/abs/2302.14502)

3. **Neural Natural Language Processing for Long Texts: A Survey of the State-of-the-Art.** *Dimitrios Tsirmpas, Ioannis Gkionis, Ioannis Mademlis, Georgios Papadopoulos.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.16259)

## 2. Efficient Transformers

### 2.1 Sparse Transformers

1. **Generating Long Sequences with Sparse Transformers.** *Rewon Child, Scott Gray, Alec Radford, Ilya Sutskever.* Arxiv 2019. [paper](https://arxiv.org/abs/1904.10509)

2. **Blockwise selfattention for long document understanding.** *Jiezhong Qiu, Hao Ma, Omer Levy, Wen-tau Yih, Sinong Wang, Jie Tang.* EMNLP 2020. [paper](https://aclanthology.org/2020.findings-emnlp.232/) [code](https://github.com/xptree/BlockBERT)

3. **Longformer: The Long-Document Transformer.** *Iz Beltagy, Matthew E. Peters, Arman Cohan.* Arxiv 2020. [paper](https://arxiv.org/abs/2004.05150) [code](https://github.com/allenai/longformer)

4. **ETC: Encoding Long and Structured Inputs in Transformers.** *Joshua Ainslie, Santiago Ontanon, Chris Alberti, Vaclav Cvicek, Zachary Fisher, Philip Pham, Anirudh Ravula, Sumit Sanghai, Qifan Wang, Li Yang.* EMNLP 2020. [paper](https://aclanthology.org/2020.emnlp-main.19/)

5. **Big Bird: Transformers for Longer Sequences.** *Manzil Zaheer, Guru Guruganesh, Kumar Avinava Dubey, Joshua Ainslie, Chris Alberti, Santiago Ontanon, Philip Pham, Anirudh Ravula, Qifan Wang, Li Yang, Amr Ahmed.* NeurIPS 2020. [paper](https://papers.nips.cc/paper/2020/hash/c8512d142a2d849725f31a9a7a361ab9-Abstract.html) [code](https://github.com/google-research/bigbird)

6. **Reformer: The efficient transformer.** *Nikita Kitaev, Łukasz Kaiser, Anselm Levskaya.* ICLR 2020. [paper](https://arxiv.org/abs/2001.04451) [code](https://github.com/lucidrains/reformer-pytorch)

7. **Sparse Sinkhorn Attention.** *Yi Tay, Dara Bahri, Liu Yang, Donald Metzler, Da-Cheng Juan.* ICML 2020. [paper](https://arxiv.org/abs/2002.11296) [code](https://github.com/lucidrains/sinkhorn-transformer)

8. **Sparse and continuous attention mechanisms.** *André F. T. Martins, António Farinhas, Marcos Treviso, Vlad Niculae, Pedro M. Q. Aguiar, Mário A. T. Figueiredo.* NIPS 2020. [paper](https://arxiv.org/abs/2006.07214)

9. **Efficient Content-Based Sparse Attention with Routing Transformers** *Aurko Roy, Mohammad Saffar, Ashish Vaswani, David Grangier.* TACL 2021. [paper](https://aclanthology.org/2021.tacl-1.4/) [code](https://github.com/lucidrains/routing-transformer)

10. **LongT5: Efficient text-to-text transformer for long sequences.** *Mandy Guo, Joshua Ainslie, David Uthus, Santiago Ontanon, Jianmo Ni, Yun-Hsuan Sung, Yinfei Yang.* NAACL 2022. [paper](https://aclanthology.org/2022.findings-naacl.55/) [code](https://github.com/google-research/longt5)

11. **Efficient Long-Text Understanding with Short-Text Models.** *Maor Ivgi, Uri Shaham, Jonathan Berant.* TACL 2023. [paper](https://aclanthology.org/2023.tacl-1.17/) [code](https://github.com/Mivg/SLED)

12. **Parallel Context Windows for Large Language Models.** *Nir Ratner, Yoav Levine, Yonatan Belinkov, Ori Ram, Inbal Magar, Omri Abend, Ehud Karpas, Amnon Shashua, Kevin Leyton-Brown, Yoav Shoham.* ACL 2023. [paper](https://aclanthology.org/2023.acl-long.352/) [code](https://github.com/AI21Labs/Parallel-Context-Windows)

13. **Unlimiformer: Long-Range Transformers with Unlimited Length Input.** *Amanda Bertsch, Uri Alon, Graham Neubig, Matthew R. Gormley.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.01625) [code](https://github.com/abertsch72/unlimiformer)

14. **Landmark Attention: Random-Access Infinite Context Length for Transformers.** *Amirkeivan Mohtashami, Martin Jaggi* Arxiv 2023. [paper](https://arxiv.org/abs/2305.16300) [code](https://github.com/epfml/landmark-attention)

15. **LONGNET: Scaling Transformers to 1,000,000,000 Tokens.** *Jiayu Ding, Shuming Ma, Li Dong, Xingxing Zhang, Shaohan Huang, Wenhui Wang, Nanning Zheng, Furu Wei.* Arxiv 2023. [paper](https://arxiv.org/abs/2307.02486) [code](https://github.com/kyegomez/LongNet)

16. **Adapting Language Models to Compress Contexts.** *Alexis Chevalier, Alexander Wettig, Anirudh Ajith, Danqi Chen.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.14788) [code](https://github.com/princeton-nlp/AutoCompressors)

17. **Blockwise Parallel Transformer for Long Context Large Models.** *Hao Liu, Pieter Abbeel.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.19370) [code](https://github.com/kyegomez/Blockwise-Parallel-Transformer)

18. **MEGABYTE: Predicting Million-byte Sequences with Multiscale Transformers.** *Lili Yu, Dániel Simig, Colin Flaherty, Armen Aghajanyan, Luke Zettlemoyer, Mike Lewis.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.07185) [code](https://github.com/lucidrains/MEGABYTE-pytorch)

19. **Dynamic Context Pruning for Efficient and Interpretable Autoregressive Transformers.** *Sotiris Anagnostidis, Dario Pavllo, Luca Biggio, Lorenzo Noci, Aurelien Lucchi, Thomas Hofmann.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.15805)

20. **Long-range Language Modeling with Self-retrieval.** *Ohad Rubin, Jonathan Berant.* Arxiv 2023. [paper](https://arxiv.org/abs/2306.13421)

21. **Max-Margin Token Selection in Attention Mechanism.** *Davoud Ataee Tarzanagh, Yingcong Li, Xuechen Zhang, Samet Oymak.* Arxiv 2023. [paper](https://arxiv.org/abs/2306.13596)

22. **Chunk, Align, Select: A Simple Long-sequence Processing Method for Transformers.** *Jiawen Xie, Pengyu Cheng, Xiao Liang, Yong Dai, Nan Du.* Arxiv 2023. [paper](https://arxiv.org/abs/2308.13191)

23. **Sparse Token Transformer with Attention Back Tracking.** *Heejun Lee, Minki Kang, Youngwan Lee, Sung Ju Hwang.* ICLR 2023. [paper](https://openreview.net/forum?id=VV0hSE8AxCw)

24. **Empower Your Model with Longer and Better Context Comprehension.** *YiFei Gao, Lei Wang, Jun Fang, Longhua Hu, Jun Cheng.* Arxiv 2023. [paper](https://arxiv.org/pdf/2307.13365v2.pdf) [code](https://github.com/yileijin/attention-transition)

### 2.2 Linear Transformers

1. **Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention.** *Angelos Katharopoulos, Apoorv Vyas, Nikolaos Pappas, François Fleuret.* ICML 2020. [paper](https://arxiv.org/abs/2006.16236) [code](https://github.com/idiap/fast-transformers)

2. **Learning Fast Algorithms for Linear Transforms Using Butterfly Factorizations.** *Tri Dao, Albert Gu, Matthew Eichhorn, Atri Rudra, Christopher Ré.* Arxiv 2019. [paper](https://arxiv.org/abs/1903.05895) [code](https://github.com/HazyResearch/butterfly)

3. **Masked language modeling for proteins via linearly scalable long-context transformers.** *Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, David Belanger, Lucy Colwell, Adrian Weller.* Arxiv 2020. [paper](https://arxiv.org/abs/2006.03555)

4. **Rethinking attention with performers.** *Krzysztof Choromanski, Valerii Likhosherstov, David Dohan, Xingyou Song, Andreea Gane, Tamas Sarlos, Peter Hawkins, Jared Davis, Afroz Mohiuddin, Lukasz Kaiser, David Belanger, Lucy Colwell, Adrian Weller.* Arxiv 2020. [paper](https://arxiv.org/abs/2009.14794) [code](https://github.com/lucidrains/performer-pytorch)

5. **Linformer: Self-attention with linear complexity.** *Sinong Wang, Belinda Z. Li, Madian Khabsa, Han Fang, Hao Ma.* Arxiv 2020. [paper](https://arxiv.org/abs/2006.04768) [code](https://github.com/lucidrains/linear-attention-transformer)

6. **Random Feature Attention.** *Hao Peng, Nikolaos Pappas, Dani Yogatama, Roy Schwartz, Noah A. Smith, Lingpeng Kong.* Arxiv 2021. [paper](https://arxiv.org/abs/2103.02143) [code](https://github.com/Noahs-ARK/RFA)

7. **Luna: Linear unified nested attention.** *Xuezhe Ma, Xiang Kong, Sinong Wang, Chunting Zhou, Jonathan May, Hao Ma, Luke Zettlemoyer.* Arxiv 2021. [paper](https://arxiv.org/abs/2106.01540) [code](https://github.com/sooftware/luna-transformer)

8. **Fnet: Mixing tokens with fourier transforms.** *James Lee-Thorp, Joshua Ainslie, Ilya Eckstein, Santiago Ontanon.* Arxiv 2021. [paper](https://arxiv.org/abs/2105.03824) [code](https://github.com/jaketae/fnet)

### 2.3 Hierarchical Transformers

1. **Neural Legal Judgment Prediction in English.** *Ilias Chalkidis, Ion Androutsopoulos, Nikolaos Aletras.* ACL 2019. [paper](https://aclanthology.org/P19-1424.pdf) [code](https://github.com/PolarisRisingWar/pytorch_ljp)

2. **Hierarchical Neural Network Approaches for Long Document Classification.** *Snehal Khandve, Vedangi Wagh, Apurva Wani, Isha Joshi, Raviraj Joshi.* ICML 2022. [paper](https://arxiv.org/abs/2201.06774)

3. **Hi-transformer: Hierarchical interactive transformer for efficient and effective long document modeling.** *Chuhan Wu, Fangzhao Wu, Tao Qi, Yongfeng Huang.* ACL-IJCNLP 2021 [paper](https://arxiv.org/abs/2106.01040)

4. **Erniesparse: Learning hierarchical efficient transformer through regularized self-attention.** *Yang Liu, Jiaxiang Liu, Li Chen, Yuxiang Lu, Shikun Feng, Zhida Feng, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang.* Arxiv 2022. [paper](https://arxiv.org/abs/2203.12276)

## 3. Recurrent Transformers

1. **Transformer-XL: Attentive language models beyond a fixed-length context.** *Zihang Dai, Zhilin Yang, Yiming Yang, Jaime Carbonell, Quoc V. Le, Ruslan Salakhutdinov.* ACL 2019. [paper](https://arxiv.org/abs/1901.02860) [code](https://github.com/kimiyoung/transformer-xl)

2. **Compressive Transformers for Long-Range Sequence Modelling.** *Jack W. Rae, Anna Potapenko, Siddhant M. Jayakumar, Timothy P. Lillicrap.* Arxiv 2019. [paper](https://arxiv.org/abs/1911.05507) [code](https://github.com/lucidrains/compressive-transformer-pytorch)

3. **Memformer: The memory-augmented transformer.** *Qingyang Wu, Zhenzhong Lan, Kun Qian, Jing Gu, Alborz Geramifard, Zhou Yu.* Arxiv 2020. [paper](https://arxiv.org/abs/2010.06891) [code](https://github.com/lucidrains/memformer)

4. **ERNIE-Doc: A Retrospective Long-Document Modeling Transformer.** *SiYu Ding, Junyuan Shang, Shuohuan Wang, Yu Sun, Hao Tian, Hua Wu, Haifeng Wang.* ACL-IJCNLP 2021. [paper](https://aclanthology.org/2021.acl-long.227/)

5. **Memorizing Transformers.** *Yuhuai Wu, Markus N. Rabe, DeLesley Hutchins, Christian Szegedy.* Arxiv 2022. [paper](https://arxiv.org/abs/2203.08913) [code](https://github.com/lucidrains/memorizing-transformers-pytorch)

6. **Recurrent Attention Networks for Long-text Modeling.** *Xianming Li, Zongxi Li, Xiaotian Luo, Haoran Xie, Xing Lee, Yingbin Zhao, Fu Lee Wang, Qing Li.* ACL 2023. [paper](https://aclanthology.org/2023.findings-acl.188/) [code](https://github.com/4ai/ran)

7. **RWKV: Reinventing RNNs for the Transformer Era.** *Bo Peng, Eric Alcaide, Quentin Anthony, Alon Albalak, Samuel Arcadinho, Huanqi Cao, Xin Cheng, Michael Chung, Matteo Grella, Kranthi Kiran GV, Xuzheng He, Haowen Hou, Przemyslaw Kazienko, Jan Kocon, Jiaming Kong, Bartlomiej Koptyra, Hayden Lau, Krishna Sri Ipsit Mantri, Ferdinand Mom, Atsushi Saito, Xiangru Tang, Bolun Wang, Johan S. Wind, Stansilaw Wozniak, Ruichong Zhang, Zhenyuan Zhang, Qihang Zhao, Peng Zhou, Jian Zhu, Rui-Jie Zhu.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.13048) [code](https://github.com/BlinkDL/RWKV-LM)

8. **Segmented Recurrent Transformer: An Efficient Sequence-to-Sequence Model.** *Yinghan Long, Sayeed Shafayet Chowdhury, Kaushik Roy.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.16340)

9. **Scaling Transformer to 1M tokens and beyond with RMT.** *Aydar Bulatov, Yuri Kuratov, Mikhail S. Burtsev.* Arxiv 2023. [paper](https://arxiv.org/abs/2304.11062)

10. **Block-Recurrent Transformers.** *DeLesley Hutchins, Imanol Schlag, Yuhuai Wu, Ethan Dyer, Behnam Neyshabur.* Arxiv 2023. [paper](https://arxiv.org/abs/2203.07852) [code](https://github.com/lucidrains/block-recurrent-transformer-pytorch)

## 4. Length Extrapolation

1. **RoFormer: Enhanced Transformer with Rotary Position Embedding.** *Jianlin Su, Yu Lu, Shengfeng Pan, Ahmed Murtadha, Bo Wen, Yunfeng Liu.* Arxiv 2021. [paper](https://arxiv.org/abs/2104.09864) [code](https://github.com/ZhuiyiTechnology/roformer)

2. **Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation.** *Ofir Press, Noah A. Smith, Mike Lewis.* ICLR 2022. [paper](https://arxiv.org/abs/2108.12409) [code](https://github.com/ofirpress/attention_with_linear_biases)

3. **KERPLE: Kernelized Relative Positional Embedding for Length Extrapolation.** *Ta-Chung Chi, Ting-Han Fan, Peter J. Ramadge, Alexander I. Rudnicky.* Arxiv 2022. [paper](https://arxiv.org/abs/2205.09921)

4. **Dissecting Transformer Length Extrapolation via the Lens of Receptive Field Analysis.** *Ta-Chung Chi, Ting-Han Fan, Alexander I. Rudnicky, Peter J. Ramadge.* ACL 2023. [paper](https://aclanthology.org/2023.acl-long.756/)

5. **A Length-Extrapolatable Transformer.** *Yutao Sun, Li Dong, Barun Patra, Shuming Ma, Shaohan Huang, Alon Benhaim, Vishrav Chaudhary, Xia Song, Furu Wei.* ACL 2023. [paper](https://aclanthology.org/2023.acl-long.816/) [code](https://github.com/sunyt32/torchscale)

6. **Randomized Positional Encodings Boost Length Generalization of Transformers.** *Anian Ruoss, Grégoire Delétang, Tim Genewein, Jordi Grau-Moya, Róbert Csordás, Mehdi Bennani, Shane Legg, Joel Veness.* ACL 2023. [paper](https://aclanthology.org/2023.acl-short.161/) [code](https://github.com/google-deepmind/randomized_positional_encodings)

7. **The Impact of Positional Encoding on Length Generalization in Transformers.** *Amirhossein Kazemnejad, Inkit Padhi, Karthikeyan Natesan Ramamurthy, Payel Das, Siva Reddy.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.19466) [code](https://github.com/McGill-NLP/length-generalization)

8. **Focused Transformer: Contrastive Training for Context Scaling.** *Szymon Tworkowski, Konrad Staniszewski, Mikołaj Pacek, Yuhuai Wu, Henryk Michalewski, Piotr Miłoś.* Arxiv 2023. [paper](https://arxiv.org/abs/2307.03170) [code](https://github.com/CStanKonrad/long_llama)

9. **Extending Context Window of Large Language Models via Positional Interpolation.** *Shouyuan Chen, Sherman Wong, Liangjian Chen, Yuandong Tian.* Arxiv 2023. [paper](https://arxiv.org/abs/2306.15595)

10. **Exploring Transformer Extrapolation.** *Zhen Qin, Yiran Zhong, Hui Deng.* Arxiv 2023. [paper](https://arxiv.org/abs/2307.10156) [code](https://github.com/OpenNLPLab/Rpe)

11. **LM-Infinite: Simple On-the-Fly Length Generalization for Large Language Models.** *Chi Han, Qifan Wang, Wenhan Xiong, Yu Chen, Heng Ji, Sinong Wang.* Arxiv 2023. [paper](https://arxiv.org/pdf/2308.16137.pdf) [code](https://github.com/kyegomez/LM-Infinite)

12. **YaRN: Efficient Context Window Extension of Large Language Models.** *Bowen Peng, Jeffrey Quesnelle, Honglu Fan, Enrico Shippole.* Arxiv 2023. [paper](https://arxiv.org/abs/2309.00071) [code](https://github.com/jquesnelle/yarn)

## 5. Long Term Memory

1. **Unleashing Infinite-Length Input Capacity for Large-scale Language Models with Self-Controlled Memory System.** *Xinnian Liang, Bing Wang, Hui Huang, Shuangzhi Wu, Peihao Wu, Lu Lu, Zejun Ma, Zhoujun Li.* Arxiv 2023. [paper](https://arxiv.org/abs/2304.13343) [code](https://github.com/wbbeyourself/SCM4LLMs)

2. **MemoryBank: Enhancing Large Language Models with Long-Term Memory.** *Wanjun Zhong, Lianghong Guo, Qiqi Gao, He Ye, Yanlin Wang.* Arxiv 2023. [paper](https://arxiv.org/abs/2305.10250) [code](https://github.com/zhongwanjun/MemoryBank-SiliconFriend)

3. **Improve Long-term Memory Learning Through Rescaling the Error Temporally.** *Shida Wang, Zhanglu Yan.* Arxiv 2023. [paper](https://arxiv.org/abs/2307.11462)

4. **Recursively Summarizing Enables Long-Term Dialogue Memory in Large Language Models.** *Qingyue Wang, Liang Ding, Yanan Cao, Zhiliang Tian, Shi Wang, Dacheng Tao, Li Guo.* Arxiv 2023. [paper](https://arxiv.org/abs/2308.15022)

## 6. Benchmark and Evaluation

1. **Long Range Arena : A Benchmark for Efficient Transformers.** *Yi Tay, Mostafa Dehghani, Samira Abnar, Yikang Shen, Dara Bahri, Philip Pham, Jinfeng Rao, Liu Yang, Sebastian Ruder, Donald Metzler.* ICLR 2021. [paper](https://arxiv.org/abs/2011.04006) [code](https://github.com/google-research/long-range-arena)

2. **LOT: A Story-Centric Benchmark for Evaluating Chinese Long Text Understanding and Generation.** *Jian Guan, Zhuoer Feng, Yamei Chen, Ruilin He, Xiaoxi Mao, Changjie Fan, Minlie Huang.* TACL 2022. [paper](https://aclanthology.org/2022.tacl-1.25.pdf) [code](https://github.com/thu-coai/LOT-LongLM)

3. **SCROLLS: Standardized CompaRison Over Long Language Sequences.** *Uri Shaham, Elad Segal, Maor Ivgi, Avia Efrat, Ori Yoran, Adi Haviv, Ankit Gupta, Wenhan Xiong, Mor Geva, Jonathan Berant, Omer Levy.* EMNLP 2022. [paper](https://arxiv.org/abs/2201.03533) [code](https://github.com/tau-nlp/scrolls)

4. **MuLD: The Multitask Long Document Benchmark.** *George Hudson, Noura Al Moubayed.* LREC 2022. [paper](https://aclanthology.org/2022.lrec-1.392/) [code](https://github.com/ghomasHudson/muld)

5. **Lost in the Middle: How Language Models Use Long Contexts.** *Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang.* Arxiv 2023. [paper](https://arxiv.org/abs/2307.03172) [code](https://github.com/nelson-liu/lost-in-the-middle)

6. **L-Eval: Instituting Standardized Evaluation for Long Context Language Models.** *Chenxin An, Shansan Gong, Ming Zhong, Mukai Li, Jun Zhang, Lingpeng Kong, Xipeng Qiu.* Arxiv 2023. [paper](https://arxiv.org/abs/2307.11088) [code](https://github.com/OpenLMLab/LEval)

7. **LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding.** *Yushi Bai, Xin Lv, Jiajie Zhang, Hongchang Lyu, Jiankai Tang, Zhidian Huang, Zhengxiao Du, Xiao Liu, Aohan Zeng, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li.* Arxiv 2023. [paper](https://arxiv.org/abs/2308.14508) [code](https://github.com/THUDM/LongBench)

8. **Content Reduction, Surprisal and Information Density Estimation for Long Documents.** *Shaoxiong Ji, Wei Sun, Pekka Marttinen.* Arxiv 2023. [paper](https://arxiv.org/abs/2309.06009)

## Acknowledgements
Please contact me if I miss your names in the list, I will add you back ASAP!
