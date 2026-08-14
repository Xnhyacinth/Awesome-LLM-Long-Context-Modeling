# 18. Benchmarks & Evaluation

[← Back to README](../README.md#-papers)

<!-- chapter-toc -->
- [18.1 Long-Context LLM Benchmarks](#181-long-context-llm-benchmarks)
- [18.2 Long-Context Multimodal & Video Benchmarks](#182-long-context-multimodal--video-benchmarks)
- [18.3 Agentic Long-Horizon Benchmarks](#183-agentic-long-horizon-benchmarks)
- [18.4 Long Reasoning / Long Generation Benchmarks](#184-long-reasoning--long-generation-benchmarks)
<!-- /chapter-toc -->

#### 18.1 Long-Context LLM Benchmarks

1. [**Long Range Arena : A Benchmark for Efficient Transformers.**](https://arxiv.org/abs/2011.04006) _Yi Tay, Mostafa Dehghani, Samira Abnar, Yikang Shen, Dara Bahri, Philip Pham, Jinfeng Rao, Liu Yang, Sebastian Ruder, Donald Metzler._ ICLR 2021. [![GitHub Repo stars](https://img.shields.io/github/stars/google-research/long-range-arena)](https://github.com/google-research/long-range-arena)

2. [**LOT: A Story-Centric Benchmark for Evaluating Chinese Long Text Understanding and Generation.**](https://aclanthology.org/2022.tacl-1.25.pdf) _Jian Guan, Zhuoer Feng, Yamei Chen, Ruilin He, Xiaoxi Mao, Changjie Fan, Minlie Huang._ TACL 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/thu-coai/LOT-LongLM)](https://github.com/thu-coai/LOT-LongLM)

3. [**SCROLLS: Standardized CompaRison Over Long Language Sequences.**](https://arxiv.org/abs/2201.03533) _Uri Shaham, Elad Segal, Maor Ivgi, Avia Efrat, Ori Yoran, Adi Haviv, Ankit Gupta, Wenhan Xiong, Mor Geva, Jonathan Berant, Omer Levy._ EMNLP 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/tau-nlp/scrolls)](https://github.com/tau-nlp/scrolls)

4. [**MuLD: The Multitask Long Document Benchmark.**](https://aclanthology.org/2022.lrec-1.392/) _George Hudson, Noura Al Moubayed._ LREC 2022. [![GitHub Repo stars](https://img.shields.io/github/stars/ghomasHudson/muld)](https://github.com/ghomasHudson/muld)

5. [**Lost in the Middle: How Language Models Use Long Contexts.**](https://arxiv.org/abs/2307.03172) _Nelson F. Liu, Kevin Lin, John Hewitt, Ashwin Paranjape, Michele Bevilacqua, Fabio Petroni, Percy Liang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/nelson-liu/lost-in-the-middle)](https://github.com/nelson-liu/lost-in-the-middle)

6. [**L-Eval: Instituting Standardized Evaluation for Long Context Language Models.**](https://arxiv.org/abs/2307.11088) _Chenxin An, Shansan Gong, Ming Zhong, Mukai Li, Jun Zhang, Lingpeng Kong, Xipeng Qiu._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenLMLab/LEval)](https://github.com/OpenLMLab/LEval)

7. [**LongBench: A Bilingual, Multitask Benchmark for Long Context Understanding.**](https://arxiv.org/abs/2308.14508) _Yushi Bai, Xin Lv, Jiajie Zhang, Hongchang Lyu, Jiankai Tang, Zhidian Huang, Zhengxiao Du, Xiao Liu, Aohan Zeng, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongBench)](https://github.com/THUDM/LongBench)

8. [**Content Reduction, Surprisal and Information Density Estimation for Long Documents.**](https://arxiv.org/abs/2309.06009) _Shaoxiong Ji, Wei Sun, Pekka Marttinen._ Arxiv 2023.

9. [**BAMBOO: A Comprehensive Benchmark for Evaluating Long Text Modeling Capacities of Large Language Models.**](https://arxiv.org/abs/2309.13345) _Zican Dong, Tianyi Tang, Junyi Li, Wayne Xin Zhao, Ji-Rong Wen._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/BAMBOO)](https://github.com/RUCAIBox/BAMBOO)

10. [**Retrieval meets Long Context Large Language Models.**](https://arxiv.org/abs/2310.03025) _Peng Xu, Wei Ping, Xianchao Wu, Lawrence McAfee, Chen Zhu, Zihan Liu, Sandeep Subramanian, Evelina Bakhturina, Mohammad Shoeybi, Bryan Catanzaro._ Arxiv 2023.

11. [**LooGLE: Long Context Evaluation for Long-Context Language Models.**](https://arxiv.org/pdf/2311.04939v1.pdf) _Jiaqi Li, Mengmeng Wang, Zilong Zheng, Muhan Zhang._ Arxiv 2023. [![GitHub Repo stars](https://img.shields.io/github/stars/bigai-nlco/loogle)](https://github.com/bigai-nlco/loogle)

12. [**The Impact of Reasoning Step Length on Large Language Models.**](https://arxiv.org/abs/2401.04925v1) _Mingyu Jin, Qinkai Yu, Dong shu, Haiyan Zhao, Wenyue Hua, Yanda Meng, Yongfeng Zhang, Mengnan Du._ Arxiv 2024.

13. [**DocFinQA: A Long-Context Financial Reasoning Dataset.**](https://arxiv.org/abs/2401.06915) _Varshini Reddy, Rik Koncel-Kedziorski, Viet Dac Lai, Chris Tanner._ Arxiv 2024.

14. [**LongFin: A Multimodal Document Understanding Model for Long Financial Domain Documents.**](https://arxiv.org/abs/2401.15050) _Ahmed Masry, Amir Hajian._ Arxiv 2024.

15. [**PROXYQA: An Alternative Framework for Evaluating Long-Form Text Generation with Large Language Models.**](https://arxiv.org/abs/2401.15042) _Haochen Tan, Zhijiang Guo, Zhan Shi, Lu Xu, Zhili Liu, Xiaoguang Li, Yasheng Wang, Lifeng Shang, Qun Liu, Linqi Song._ Arxiv 2024.

16. [**LongHealth: A Question Answering Benchmark with Long Clinical Documents.**](https://arxiv.org/abs/2401.14490) _Lisa Adams, Felix Busch, Tianyu Han, Jean-Baptiste Excoffier, Matthieu Ortala, Alexander Löser, Hugo JWL. Aerts, Jakob Nikolas Kather, Daniel Truhn, Keno Bressem._ Arxiv 2024.

17. [**Long-form evaluation of model editing.**](https://arxiv.org/abs/2402.09394) _Domenic Rosati, Robie Gonzales, Jinkun Chen, Xuemin Yu, Melis Erkan, Yahya Kayani, Satya Deepika Chavatapalli, Frank Rudzicz, Hassan Sajjad._ Arxiv 2024.

18. [**In Search of Needles in a 10M Haystack: Recurrent Memory Finds What LLMs Miss.**](https://arxiv.org/abs/2402.10790v1) _Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

19. [**∞Bench: Extending Long Context Evaluation Beyond 100K Tokens.**](https://arxiv.org/abs/2402.13718) _Xinrong Zhang, Yingfa Chen, Shengding Hu, Zihang Xu, Junhao Chen, Moo Khai Hao, Xu Han, Zhen Leng Thai, Shuo Wang, Zhiyuan Liu, Maosong Sun._ Arxiv 2024.

20. [**Same Task, More Tokens: the Impact of Input Length on the Reasoning Performance of Large Language Models.**](https://arxiv.org/abs/2402.14848) _Mosh Levy, Alon Jacoby, Yoav Goldberg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/alonj/Same-Task-More-Tokens)](https://github.com/alonj/Same-Task-More-Tokens)

21. [**Language Models as Science Tutors.**](https://arxiv.org/abs/2402.11111) _Alexis Chevalier, Jiayi Geng, Alexander Wettig, Howard Chen, Sebastian Mizera, Toni Annala, Max Jameson Aragon, Arturo Rodríguez Fanlo, Simon Frieder, Simon Machado, Akshara Prabhakar, Ellie Thieu, Jiachen T. Wang, Zirui Wang, Xindi Wu, Mengzhou Xia, Wenhan Jia, Jiatong Yu, Jun-Jie Zhu, Zhiyong Jason Ren, Sanjeev Arora, Danqi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/LM-Science-Tutor)](https://github.com/princeton-nlp/LM-Science-Tutor)

22. [**Needle in a haystack - pressure testing llms.**](https://github.com/gkamradt/LLMTest_NeedleInAHaystack) _Kamradt, G._ Github 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/gkamradt/LLMTest_NeedleInAHaystack)](https://github.com/gkamradt/LLMTest_NeedleInAHaystack)

23. [**LV-Eval: A Balanced Long-Context Benchmark with 5 Length Levels Up to 256K.**](https://arxiv.org/abs/2402.05136) _Tao Yuan, Xuefei Ning, Dong Zhou, Zhijie Yang, Shiyao Li, Minghui Zhuang, Zheyue Tan, Zhuyu Yao, Dahua Lin, Boxun Li, Guohao Dai, Shengen Yan, Yu Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/infinigence/LVEval)](https://github.com/infinigence/LVEval)

24. [**Counting-Stars: A Simple, Efficient, and Reasonable Strategy for Evaluating Long-Context Large Language Models.**](https://arxiv.org/abs/2403.11802) _Mingyang Song, Mao Zheng, Xuan Luo._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/Counting-Stars)](https://github.com/nick7nlp/Counting-Stars)

25. [**NovelQA: A Benchmark for Long-Range Novel Question Answering.**](https://arxiv.org/abs/2403.12766) _Cunxiang Wang, Ruoxi Ning, Boqi Pan, Tonghui Wu, Qipeng Guo, Cheng Deng, Guangsheng Bao, Qian Wang, Yue Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/NovelQA/novelqa.github.io)](https://github.com/NovelQA/novelqa.github.io)

26. [**Long-form factuality in large language models.**](https://arxiv.org/abs/2403.18802) _Jerry Wei, Chengrun Yang, Xinying Song, Yifeng Lu, Nathan Hu, Dustin Tran, Daiyi Peng, Ruibo Liu, Da Huang, Cosmo Du, Quoc V. Le._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/long-form-factuality)](https://github.com/google-deepmind/long-form-factuality)

27. [**LUQ: Long-text Uncertainty Quantification for LLMs.**](https://arxiv.org/abs/2403.20279) _JCaiqi Zhang, Fangyu Liu, Marco Basaldella, Nigel Collier._ Arxiv 2024.

28. [**CLongEval: A Chinese Benchmark for Evaluating Long-Context Large Language Models.**](https://arxiv.org/abs/2403.03514) _Zexuan Qiu, Jingjing Li, Shijue Huang, Wanjun Zhong, Irwin King._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zexuanqiu/CLongEval)](https://github.com/zexuanqiu/CLongEval)

29. [**Long-context LLMs Struggle with Long In-context Learning.**](https://arxiv.org/abs/2404.02060) _Tianle Li, Ge Zhang, Quy Duc Do, Xiang Yue, Wenhu Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/LongICLBench)](https://github.com/TIGER-AI-Lab/LongICLBench)

30. [**CLAPNQ: Cohesive Long-form Answers from Passages in Natural Questions for RAG systems.**](https://arxiv.org/abs/2404.02103) _Sara Rosenthal, Avirup Sil, Radu Florian, Salim Roukos._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/primeqa/clapnq)](https://github.com/primeqa/clapnq)

31. [**XL2Bench: A Benchmark for Extremely Long Context Understanding with Long-range Dependencies.**](https://arxiv.org/abs/2404.05446) _Xuanfan Ni, Hengyi Cai, Xiaochi Wei, Shuaiqiang Wang, Dawei Yin, Piji Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nuaa-nlp/XL2Bench)](https://github.com/nuaa-nlp/XL2Bench)

32. [**Never Train from Scratch: Fair Comparison of Long-Sequence Models Requires Data-Driven Priors.**](https://openreview.net/forum?id=PdaPky8MUn) _Ido Amos, Jonathan Berant, Ankit Gupta._ ICLR 2024 Oral.

33. [**Ada-LEval: Evaluating long-context LLMs with length-adaptable benchmarks.**](https://arxiv.org/abs/2404.06480) _Chonghua Wang, Haodong Duan, Songyang Zhang, Dahua Lin, Kai Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/Ada-LEval)](https://github.com/open-compass/Ada-LEval)

34. [**RULER: What's the Real Context Size of Your Long-Context Language Models?.**](https://arxiv.org/abs/2404.06654) _Cheng-Ping Hsieh, Simeng Sun, Samuel Kriman, Shantanu Acharya, Dima Rekesh, Fei Jia, Boris Ginsburg._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/hsiehjackson/RULER)](https://github.com/hsiehjackson/RULER)

35. [**LongEmbed: Extending Embedding Models for Long Context Retrieval.**](https://arxiv.org/abs/2404.12096) _Dawei Zhu, Liang Wang, Nan Yang, Yifan Song, Wenhao Wu, Furu Wei, Sujian Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dwzhu-pku/LongEmbed)](https://github.com/dwzhu-pku/LongEmbed)

36. [**S3Eval: A Synthetic, Scalable, Systematic Evaluation Suite for Large Language Models.**](https://arxiv.org/abs/2310.15147) _Fangyu Lei, Qian Liu, Yiming Huang, Shizhu He, Jun Zhao, Kang Liu._ NAACL 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/lfy79001/S3Eval)](https://github.com/lfy79001/S3Eval)

37. [**In-Context Learning with Long-Context Models: An In-Depth Exploration.**](https://arxiv.org/abs/2405.00200) _Amanda Bertsch, Maor Ivgi, Uri Alon, Jonathan Berant, Matthew R. Gormley, Graham Neubig._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/abertsch72/long-context-icl)](https://github.com/abertsch72/long-context-icl)

38. [**Many-shot Jailbreaking.**](https://www-cdn.anthropic.com/af5633c94ed2beb282f6a53c595eb437e8e7b630/Many_Shot_Jailbreaking__2024_04_02_0936.pdf) Anthropic 2024.

39. [**DOLOMITES: Domain-Specific Long-Form Methodical Tasks.**](https://arxiv.org/abs/2405.05938) _Chaitanya Malaviya, Priyanka Agrawal, Kuzman Ganchev, Pranesh Srinivasan, Fantine Huot, Jonathan Berant, Mark Yatskar, Dipanjan Das, Mirella Lapata, Chris Alberti._ Arxiv 2024.

40. [**Challenges in Deploying Long-Context Transformers: A Theoretical Peak Performance Analysis.**](https://arxiv.org/abs/2405.08944) _Yao Fu._ Arxiv 2024.

41. [**FinTextQA: A Dataset for Long-form Financial Question Answering.**](https://arxiv.org/abs/2405.09980) _Jian Chen, Peilin Zhou, Yining Hua, Yingxin Loh, Kehui Chen, Ziyuan Li, Bing Zhu, Junwei Liang._ Arxiv 2024.

42. [**A Multi-Perspective Analysis of Memorization in Large Language Models.**](https://arxiv.org/abs/2405.11577) _Bowen Chen, Namgi Han, Yusuke Miyao._ Arxiv 2024.

43. [**OLAPH: Improving Factuality in Biomedical Long-form Question Answering.**](https://arxiv.org/abs/2405.12701) _Minbyul Jeong, Hyeon Hwang, Chanwoong Yoon, Taewhoo Lee, Jaewoo Kang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dmis-lab/OLAPH)](https://github.com/dmis-lab/OLAPH)

44. [**Can LLMs Solve longer Math Word Problems Better?.**](https://arxiv.org/abs/2405.14804) _Xin Xu, Tong Xiao, Zitong Chao, Zhenya Huang, Can Yang, Yang Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/XinXU-USTC/CoLeG-Math)](https://github.com/XinXU-USTC/CoLeG-Math)

45. [**Many-shot In-Context Learning.**](https://arxiv.org/abs/2404.11018) _Rishabh Agarwal, Avi Singh, Lei M. Zhang, Bernd Bohnet, Luis Rosias, Stephanie Chan, Biao Zhang, Ankesh Anand, Zaheer Abbas, Azade Nova, John D. Co-Reyes, Eric Chu, Feryal Behbahani, Aleksandra Faust, Hugo Larochelle._ Arxiv 2024.

46. [**Long Context is Not Long at All: A Prospector of Long-Dependency Data for Large Language Models.**](https://arxiv.org/abs/2405.17915) _Longze Chen, Ziqiang Liu, Wanwei He, Yunshui Li, Run Luo, Min Yang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/October2001/ProLong)](https://github.com/October2001/ProLong)

47. [**Language Models Need Inductive Biases to Count Inductively.**](https://arxiv.org/abs/2405.20131) _Yingshan Chang, Yonatan Bisk._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/zdxdsw/inductive_counting_with_LMs)](https://github.com/zdxdsw/inductive_counting_with_LMs)

48. [**Analyzing Temporal Complex Events with Large Language Models? A Benchmark towards Temporal, Long Context Understanding.**](https://arxiv.org/abs/2406.02472) _Zhihan Zhang, Yixin Cao, Chenchen Ye, Yunshan Ma, Lizi Liao, Tat-Seng Chua._ Arxiv 2024.

49. [**CRAG -- Comprehensive RAG Benchmark.**](https://arxiv.org/abs/2406.04744) _Xiao Yang, Kai Sun, Hao Xin, Yushi Sun, Nikita Bhalla, Xiangsen Chen, Sajal Choudhary, Rongze Daniel Gui, Ziran Will Jiang, Ziyu Jiang, Lingkun Kong, Brian Moran, Jiaqi Wang, Yifan Ethan Xu, An Yan, Chenyu Yang, Eting Yuan, Hanwen Zha, Nan Tang, Lei Chen, Nicolas Scheffer, Yue Liu, Nirav Shah, Rakesh Wanga, Anuj Kumar, Wen-tau Yih, Xin Luna Dong._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.aicrowd.com/challenges/meta-comprehensive-rag-benchmark-kdd-cup-2024)

50. [**BABILong: Testing the Limits of LLMs with Long Context Reasoning-in-a-Haystack.**](https://arxiv.org/abs/2406.10149) _Yuri Kuratov, Aydar Bulatov, Petr Anokhin, Ivan Rodkin, Dmitry Sorokin, Artyom Sorokin, Mikhail Burtsev._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/booydar/babilong)](https://github.com/booydar/babilong)

51. [**Can Many-Shot In-Context Learning Help Long-Context LLM Judges? See More, Judge Better!.**](https://arxiv.org/abs/2406.11629) _Mingyang Song, Mao Zheng, Xuan Luo._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/nick7nlp/SeeMoreJudgeBetter)](https://github.com/nick7nlp/SeeMoreJudgeBetter)

52. [**What Kinds of Tokens Benefit from Distant Text? An Analysis on Long Context Language Modeling.**](https://arxiv.org/abs/2406.11238) _Yutong Hu, Quzhe Huang, Kangcheng Luo, Yansong Feng._ Arxiv 2024.

53. [**Understanding the RoPE Extensions of Long-Context LLMs: An Attention Perspective.**](https://arxiv.org/abs/2406.13282) _Meizhi Zhong, Chen Zhang, Yikun Lei, Xikai Liu, Yan Gao, Yao Hu, Kehai Chen, Min Zhang._ Arxiv 2024.

54. [**Can Long-Context Language Models Subsume Retrieval, RAG, SQL, and More?.**](https://arxiv.org/abs/2406.13121) _Jinhyuk Lee, Anthony Chen, Zhuyun Dai, Dheeru Dua, Devendra Singh Sachan, Michael Boratko, Yi Luan, Sébastien M. R. Arnold, Vincent Perot, Siddharth Dalmia, Hexiang Hu, Xudong Lin, Panupong Pasupat, Aida Amini, Jeremy R. Cole, Sebastian Riedel, Iftekhar Naim, Ming-Wei Chang, Kelvin Guu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/loft)](https://github.com/google-deepmind/loft)

55. [**Insights into LLM Long-Context Failures: When Transformers Know but Don't Tell.**](https://arxiv.org/abs/2406.14673) _Taiming Lu, Muhan Gao, Kuai Yu, Adam Byerly, Daniel Khashabi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/TaiMingLu/know-dont-tell)](https://github.com/TaiMingLu/know-dont-tell)

56. [**MedOdyssey: A Medical Domain Benchmark for Long Context Evaluation Up to 200K Tokens.**](https://arxiv.org/abs/2406.15019) _Yongqi Fan, Hongli Sun, Kui Xue, Xiaofan Zhang, Shaoting Zhang, Tong Ruan._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/JOHNNY-fans/MedOdyssey)](https://github.com/JOHNNY-fans/MedOdyssey)

57. [**USDC: A Dataset of $\underline{U}$ser $\underline{S}$tance and $\underline{D}$ogmatism in Long $\underline{C}$onversations.**](https://arxiv.org/abs/2406.16833) _Mounika Marreddy, Subba Reddy Oota, Venkata Charan Chinni, Manish Gupta, Lucie Flek._ Arxiv 2024.

58. [**Found in the Middle: Calibrating Positional Attention Bias Improves Long Context Utilization.**](https://arxiv.org/abs/2406.16008) _Cheng-Yu Hsieh, Yung-Sung Chuang, Chun-Liang Li, Zifeng Wang, Long T. Le, Abhishek Kumar, James Glass, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister._ Arxiv 2024.

59. [**One Thousand and One Pairs: A "novel" challenge for long-context language models.**](https://arxiv.org/abs/2406.16264) _Marzena Karpinska, Katherine Thai, Kyle Lo, Tanya Goyal, Mohit Iyyer._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/marzenakrp/nocha)](https://github.com/marzenakrp/nocha/)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://novelchallenge.github.io/)

60. [**LongIns: A Challenging Long-context Instruction-based Exam for LLMs.**](https://arxiv.org/abs/2406.17588) _Shawn Gavin, Tuney Zheng, Jiaheng Liu, Quehry Que, Noah Wang, Jian Yang, Chenchen Zhang, Wenhao Huang, Wenhu Chen, Ge Zhang._ Arxiv 2024.

61. [**Leave No Document Behind: Benchmarking Long-Context LLMs with Extended Multi-Doc QA.**](https://arxiv.org/abs/2406.17419) _Minzheng Wang, Longze Chen, Cheng Fu, Shengyi Liao, Xinghua Zhang, Bingli Wu, Haiyang Yu, Nan Xu, Lei Zhang, Run Luo, Yunshui Li, Min Yang, Fei Huang, Yongbin Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/MozerWang/Loong)](https://github.com/MozerWang/Loong)

62. [**VERISCORE: Evaluating the factuality of verifiable claims in long-form text generation.**](https://arxiv.org/abs/2406.19276) _Yixiao Song, Yekyung Kim, Mohit Iyyer._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Yixiao-Song/VeriScore)](https://github.com/Yixiao-Song/VeriScore)

63. [**Is It Really Long Context if All You Need Is Retrieval? Towards Genuinely Difficult Long Context NLP.**](https://arxiv.org/abs/2407.00402) _Omer Goldman, Alon Jacovi, Aviv Slobodkin, Aviya Maimon, Ido Dagan, Reut Tsarfaty._ Arxiv 2024.

64. [**Summary of a Haystack: A Challenge to Long-Context LLMs and RAG Systems.**](https://arxiv.org/abs/2407.01370) _Philippe Laban, Alexander R. Fabbri, Caiming Xiong, Chien-Sheng Wu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/salesforce/summary-of-a-haystack)](https://github.com/salesforce/summary-of-a-haystack)

65. [**Entity-Level Sentiment: More than the Sum of Its Parts.**](https://arxiv.org/abs/2407.03916) _Egil Rønningstad, Roman Klinger, Erik Velldal, Lilja Øvrelid._ Arxiv 2024.

66. [**Evaluating Language Model Context Windows: A "Working Memory" Test and Inference-time Correction.**](https://arxiv.org/abs/2407.03651) _Amanda Dsouza, Christopher Glaze, Changho Shin, Frederic Sala._ Arxiv 2024.

67. [**RAG vs. Long Context: Examining Frontier Large Language Models for Environmental Review Document Comprehension.**](https://arxiv.org/abs/2407.07321) _Hung Phan, Anurag Acharya, Sarthak Chaturvedi, Shivam Sharma, Mike Parker, Dan Nally, Ali Jannesari, Karl Pazdernik, Mahantesh Halappanavar, Sai Munikoti, Sameera Horawalavithana._ Arxiv 2024.

68. [**Attribute or Abstain: Large Language Models as Long Document Assistants.**](https://arxiv.org/abs/2407.07799) _Jan Buchmann, Xiao Liu, Iryna Gurevych._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/UKPLab/arxiv2024-attribute-or-abstain)](https://github.com/UKPLab/arxiv2024-attribute-or-abstain)

69. [**How Well Can a Long Sequence Model Model Long Sequences? Comparing Architechtural Inductive Biases on Long-Context Abilities.**](https://arxiv.org/abs/2407.08112) _Jerry Huang._ Arxiv 2024.

70. [**DOCBENCH: A Benchmark for Evaluating LLM-based Document Reading Systems.**](https://arxiv.org/abs/2407.10701) _Anni Zou, Wenhao Yu, Hongming Zhang, Kaixin Ma, Deng Cai, Zhuosheng Zhang, Hai Zhao, Dong Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Anni-Zou/DocBench)](https://github.com/Anni-Zou/DocBench)

71. [**NeedleBench: Can LLMs Do Retrieval and Reasoning in 1 Million Context Window?.**](https://arxiv.org/abs/2407.11963) _Mo Li, Songyang Zhang, Yunxin Liu, Kai Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/opencompass)](https://github.com/open-compass/opencompass)

72. [**LongLaMP: A Benchmark for Personalized Long-form Text Generation.**](https://arxiv.org/abs/2407.11016) _Ishita Kumar, Snigdha Viswanathan, Sushrita Yerra, Alireza Salemi, Ryan A. Rossi, Franck Dernoncourt, Hanieh Deilamsalehy, Xiang Chen, Ruiyi Zhang, Shubham Agarwal, Nedim Lipka, Hamed Zamani._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://longlamp-benchmark.github.io/)

73. [**RAG-QA Arena: Evaluating Domain Robustness for Long-form Retrieval Augmented Question Answering.**](https://arxiv.org/abs/2407.13998) _Rujun Han, Yuhao Zhang, Peng Qi, Yumo Xu, Jenyuan Wang, Lan Liu, William Yang Wang, Bonan Min, Vittorio Castelli._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/awslabs/rag-qa-arena)](https://github.com/awslabs/rag-qa-arena)

74. [**Stress-Testing Long-Context Language Models with Lifelong ICL and Task Haystack.**](https://arxiv.org/abs/2407.16695) _Xiaoyue Xu, Qinyuan Ye, Xiang Ren._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/INK-USC/Lifelong-ICL)](https://github.com/INK-USC/Lifelong-ICL)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://inklab.usc.edu/lifelong-icl/)

75. [**WildHallucinations: Evaluating Long-form Factuality in LLMs with Real-World Entity Queries.**](https://arxiv.org/abs/2407.17468) _Wenting Zhao, Tanya Goyal, Yu Ying Chiu, Liwei Jiang, Benjamin Newman, Abhilasha Ravichander, Khyathi Chandu, Ronan Le Bras, Claire Cardie, Yuntian Deng, Yejin Choi._ Arxiv 2024.

76. [**Retrieval Augmented Generation or Long-Context LLMs? A Comprehensive Study and Hybrid Approach.**](https://arxiv.org/abs/2407.16833) _Zhuowan Li, Cheng Li, Mingyang Zhang, Qiaozhu Mei, Michael Bendersky._ Arxiv 2024.

77. [**Evaluating Long Range Dependency Handling in Code Generation Models using Multi-Step Key Retrieval.**](https://arxiv.org/abs/2407.21049) _Yannick Assogba, Donghao Ren._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/apple/ml-key-retrieval-code-tasks)](https://github.com/apple/ml-key-retrieval-code-tasks)

78. [**Long Input Benchmark for Russian Analysis.**](https://arxiv.org/abs/2408.02439) _Igor Churin, Murat Apishev, Maria Tikhonova, Denis Shevelev, Aydar Bulatov, Yuri Kuratov, Sergej Averkiev, Alena Fenogenova._ Arxiv 2024.

79. [**CoverBench: A Challenging Benchmark for Complex Claim Verification.**](https://arxiv.org/abs/2408.03325) _Alon Jacovi, Moran Ambar, Eyal Ben-David, Uri Shaham, Amir Feder, Mor Geva, Dror Marcus, Avi Caciularu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/datasets/google/coverbench)

80. [**Multilingual Needle in a Haystack: Investigating Long-Context Behavior of Multilingual Large Language Models.**](https://arxiv.org/abs/2408.10151) _Amey Hengle, Prasoon Bajpai, Soham Dan, Tanmoy Chakraborty._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/AmeyHengle/multilingual-needle-in-a-haystack)](https://github.com/AmeyHengle/multilingual-needle-in-a-haystack)

81. [**What are the Essential Factors in Crafting Effective Long Context Multi-Hop Instruction Datasets? Insights and Best Practices.**](https://arxiv.org/abs/2409.01893) _Zhi Chen, Qiguang Chen, Libo Qin, Qipeng Guo, Haijun Lv, Yicheng Zou, Wanxiang Che, Hang Yan, Kai Chen, Dahua Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/WowCZ/LongMIT)](https://github.com/WowCZ/LongMIT)

82. [**Retrieval Or Holistic Understanding? Dolce: Differentiate Our Long Context Evaluation Tasks.**](https://arxiv.org/abs/2409.06338) _Zi Yang._ Arxiv 2024.

83. [**A Controlled Study on Long Context Extension and Generalization in LLMs.**](https://arxiv.org/abs/2409.12181) _Yi Lu, Jing Nathan Yan, Songlin Yang, Justin T. Chiu, Siyu Ren, Fei Yuan, Wenting Zhao, Zhiyong Wu, Alexander M. Rush._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Leooyii/LCEG)](https://github.com/Leooyii/LCEG)

84. [**RAD-Bench: Evaluating Large Language Models Capabilities in Retrieval Augmented Dialogues.**](https://arxiv.org/abs/2409.12558) _Tzu-Lin Kuo, Feng-Ting Liao, Mu-Wei Hsieh, Fu-Chieh Chang, Po-Chun Hsu, Da-Shan Shiu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mtkresearch/RAD-Bench)](https://github.com/mtkresearch/RAD-Bench)

85. [**Fact, Fetch, and Reason: A Unified Evaluation of Retrieval-Augmented Generation.**](https://arxiv.org/abs/2409.12941) _Satyapriya Krishna, Kalpesh Krishna, Anhad Mohananey, Steven Schwarcz, Adam Stambler, Shyam Upadhyay, Manaal Faruqui._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/datasets/google/frames-benchmark)

86. [**Michelangelo: Long Context Evaluations Beyond Haystacks via Latent Structure Queries.**](https://arxiv.org/abs/2409.12640) _Kiran Vodrahalli, Santiago Ontanon, Nilesh Tripuraneni, Kelvin Xu, Sanil Jain, Rakesh Shivanna, Jeffrey Hui, Nishanth Dikkala, Mehran Kazemi, Bahare Fatemi, Rohan Anil, Ethan Dyer, Siamak Shakeri, Roopali Vij, Harsh Mehta, Vinay Ramasesh, Quoc Le, Ed Chi, Yifeng Lu, Orhan Firat, Angeliki Lazaridou, Jean-Baptiste Lespiau, Nithya Attaluri, Kate Olszewska._ Arxiv 2024.

87. [**DetectiveQA: Evaluating Long-Context Reasoning on Detective Novels.**](https://arxiv.org/abs/2409.02465) _Zhe Xu, Jiasheng Ye, Xiangyang Liu, Tianxiang Sun, Xiaoran Liu, Qipeng Guo, Linlin Li, Qun Liu, Xuanjing Huang, Xipeng Qiu._ Arxiv 2024.

88. [**LongCite: Enabling LLMs to Generate Fine-grained Citations in Long-context QA.**](https://arxiv.org/abs/2409.02897) _Jiajie Zhang, Yushi Bai, Xin Lv, Wanjun Gu, Danqing Liu, Minhao Zou, Shulin Cao, Lei Hou, Yuxiao Dong, Ling Feng, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongCite)](https://github.com/THUDM/LongCite)

89. [**HelloBench: Evaluating Long Text Generation Capabilities of Large Language Models.**](https://arxiv.org/abs/2409.16191) _Haoran Que, Feiyu Duan, Liqun He, Yutao Mou, Wangchunshu Zhou, Jiaheng Liu, Wenge Rong, Zekun Moore Wang, Jian Yang, Ge Zhang, Junran Peng, Zhaoxiang Zhang, Songyang Zhang, Kai Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Tintri/hello-bench)](https://github.com/Tintri/hello-bench)

90. [**Multilingual Evaluation of Long Context Retrieval and Reasoning.**](https://arxiv.org/abs/2409.18006) _Ameeta Agrawal, Andy Dang, Sina Bagheri Nezhad, Rhitabrat Pokharel, Russell Scheinberg._ Arxiv 2024.

91. [**L-CiteEval: Do Long-Context Models Truly Leverage Context for Responding?**](https://arxiv.org/abs/2410.02115) _Zecheng Tang, Keyan Zhou, Juntao Li, Baibei Ji, Jianye Hou, Min Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ZetangForward/L-CITEEVAL)](https://github.com/ZetangForward/L-CITEEVAL)

92. [**HELMET: How to Evaluate Long-Context Language Models Effectively and Thoroughly.**](https://arxiv.org/abs/2410.02694) _Howard Yen, Tianyu Gao, Minmin Hou, Ke Ding, Daniel Fleischer, Peter Izasak, Moshe Wasserblat, Danqi Chen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/HELMET)](https://github.com/princeton-nlp/HELMET)

93. [**MathHay: An Automated Benchmark for Long-Context Mathematical Reasoning in LLMs.**](https://arxiv.org/abs/2410.04698) _Lei Wang, Shan Dong, Yuhui Xu, Hanze Dong, Yalu Wang, Amrita Saha, Ee-Peng Lim, Caiming Xiong, Doyen Sahoo._ Arxiv 2024.

94. [**Hyper-multi-step: The Truth Behind Difficult Long-context Tasks.**](https://arxiv.org/abs/2410.04422) _Yijiong Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/yuyijiong/hard_retrieval_for_llm)](https://github.com/yuyijiong/hard_retrieval_for_llm)

95. [**Holistic Reasoning with Long-Context LMs: A Benchmark for Database Operations on Massive Textual Data.**](https://arxiv.org/abs/2410.11996) _Seiji Maekawa, Hayate Iso, Nikita Bhutani._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/megagonlabs/holobench)](https://github.com/megagonlabs/holobench)

96. [**How much do contextualized representations encode long-range context?.**](https://arxiv.org/abs/2410.12292) _Simeng Sun, Cheng-Ping Hsieh._ Arxiv 2024.

97. [**LongMemEval: Benchmarking Chat Assistants on Long-Term Interactive Memory.**](https://arxiv.org/abs/2410.10813) _Di Wu, Hongwei Wang, Wenhao Yu, Yuwei Zhang, Kai-Wei Chang, Dong Yu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/xiaowu0162/LongMemEval)](https://github.com/xiaowu0162/LongMemEval)

98. [**When Attention Sink Emerges in Language Models: An Empirical View.**](https://arxiv.org/abs/2410.10781) _Xiangming Gu, Tianyu Pang, Chao Du, Qian Liu, Fengzhuo Zhang, Cunxiao Du, Ye Wang, Min Lin._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/Attention-Sink)](https://github.com/sail-sg/Attention-Sink)

99. [**Distance between Relevant Information Pieces Causes Bias in Long-Context LLMs.**](https://arxiv.org/abs/2410.14641) _Runchu Tian, Yanghao Li, Yuepeng Fu, Siyang Deng, Qinyu Luo, Cheng Qian, Shuo Wang, Xin Cong, Zhong Zhang, Yesai Wu, Yankai Lin, Huadong Wang, Xiaojiang Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Rachum-thu/LongPiBench)](https://github.com/Rachum-thu/LongPiBench)

100. [**ETHIC: Evaluating Large Language Models on Long-Context Tasks with High Information Coverage.**](https://arxiv.org/abs/2410.16848) _Taewhoo Lee, Chanwoong Yoon, Kyochul Jang, Donghyeon Lee, Minju Song, Hyunjae Kim, Jaewoo Kang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dmis-lab/ETHIC)](https://github.com/dmis-lab/ETHIC)

101. [**Long2RAG: Evaluating Long-Context & Long-Form Retrieval-Augmented Generation with Key Point Recall.**](https://arxiv.org/abs/2410.23000) _Zehan Qi, Rongwu Xu, Zhijiang Guo, Cunxiang Wang, Hao Zhang, Wei Xu._ EMNLP 2024.

102. [**Needle Threading: Can LLMs Follow Threads through Near-Million-Scale Haystacks?.**](https://arxiv.org/abs/2411.05000) _Jonathan Roberts, Kai Han, Samuel Albanie._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/jonathan-roberts1/needle-threading)](https://github.com/jonathan-roberts1/needle-threading)

103. [**Retrieval or Global Context Understanding? On Many-Shot In-Context Learning for Long-Context Evaluation.**](https://arxiv.org/abs/2411.07130) _Kaijian Zou, Muhammad Khalifa, Lu Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/launchnlp/ManyICLBench)](https://github.com/launchnlp/ManyICLBench)

104. [**LIFBench: Evaluating the Instruction Following Performance and Stability of Large Language Models in Long-Context Scenarios.**](https://arxiv.org/abs/2411.07037) _Xiaodong Wu, Minhao Wang, Yichen Liu, Xiaoming Shi, He Yan, Xiangju Lu, Junmin Zhu, Wei Zhang._ Arxiv 2024.

105. [**A Benchmark for Long-Form Medical Question Answering.**](https://arxiv.org/abs/2411.09834) _Pedram Hosseini, Jessica M. Sin, Bing Ren, Bryceton G. Thomas, Elnaz Nouri, Ali Farahanchi, Saeed Hassanpour._ NeurIPS 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/lavita-ai/medical-eval-sphere)](https://github.com/lavita-ai/medical-eval-sphere)

106. [**DENIAHL: In-Context Features Influence LLM Needle-In-A-Haystack Abilities.**](https://arxiv.org/abs/2411.19360) _Hui Dai, Dan Pechi, Xinyi Yang, Garvit Banga, Raghav Mantri._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ameliadai/DENIAHL)](https://github.com/ameliadai/DENIAHL)

107. [**LCFO: Long Context and Long Form Output Dataset and Benchmarking.**](https://arxiv.org/abs/2412.08268) _Marta R. Costa-jussà, Pierre Andrews, Mariano Coria Meglioli, Joy Chen, Joe Chuang, David Dale, Christophe Ropers, Alexandre Mourachko, Eduardo Sánchez, Holger Schwenk, Tuan Tran, Arina Turkatenko, Carleigh Wood._ Arxiv 2024.

108. [**SCBench: A KV Cache-Centric Analysis of Long-Context Methods.**](https://arxiv.org/abs/2412.10319) _Yucheng Li, Huiqiang Jiang, Qianhui Wu, Xufang Luo, Surin Ahn, Chengruidong Zhang, Amir H. Abdi, Dongsheng Li, Jianfeng Gao, Yuqing Yang, Lili Qiu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://hqjiang.com/scbench.html)

109. [**LongBench v2: Towards Deeper Understanding and Reasoning on Realistic Long-context Multitasks.**](https://arxiv.org/abs/2412.15204) _Yushi Bai, Shangqing Tu, Jiajie Zhang, Hao Peng, Xiaozhi Wang, Xin Lv, Shulin Cao, Jiazheng Xu, Lei Hou, Yuxiao Dong, Jie Tang, Juanzi Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LongBench)](https://github.com/THUDM/LongBench)

110. [**XRAG: eXamining the Core -- Benchmarking Foundational Components in Advanced Retrieval-Augmented Generation.**](https://arxiv.org/abs/2412.15529) _Qianren Mao, Yangyifei Luo, Jinlong Zhang, Hanwen Hao, Zhilong Cao, Xiaolong Wang, Xiao Guan, Zhenting Huang, Weifeng Jiang, Shuyu Guo, Zhentao Han, Qili Zhang, Siyuan Tao, Yujie Liu, Junnan Liu, Zhixing Tan, Jie Sun, Bo Li, Xudong Liu, Richong Zhang, Jianxin Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/DocAILab/XRAG)](https://github.com/DocAILab/XRAG)

111. [**RepoTransBench: A Real-World Benchmark for Repository-Level Code Translation.**](https://arxiv.org/abs/2412.17744) _Yanli Wang, Yanlin Wang, Suiquan Wang, Daya Guo, Jiachi Chen, John Grundy, Xilin Liu, Yuchi Ma, Mingzhi Mao, Hongyu Zhang, Zibin Zheng._ Arxiv 2024.

112. [**Long Context vs. RAG for LLMs: An Evaluation and Revisits.**](https://arxiv.org/abs/2501.01880) _Xinze Li, Yixin Cao, Yubo Ma, Aixin Sun._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/lixinze777/LC_VS_RAG)](https://github.com/lixinze777/LC_VS_RAG)

113. [**MTRAG: A Multi-Turn Conversational Benchmark for Evaluating Retrieval-Augmented Generation Systems.**](https://arxiv.org/abs/2501.03468) _Yannis Katsis, Sara Rosenthal, Kshitij Fadnis, Chulaka Gunasekara, Young-Suk Lee, Lucian Popa, Vraj Shah, Huaiyu Zhu, Danish Contractor, Marina Danilevsky._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ibm/mt-rag-benchmark)](https://github.com/ibm/mt-rag-benchmark)

114. [**RedStar: Does Scaling Long-CoT Data Unlock Better Slow-Reasoning Systems?.**](https://arxiv.org/abs/2501.11284) _Haotian Xu, Xing Wu, Weinong Wang, Zhongzhi Li, Da Zheng, Boyuan Chen, Yi Hu, Shijia Kang, Jiaming Ji, Yingying Zhang, Zhijiang Guo, Yaodong Yang, Muhan Zhang, Debing Zhang._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/RedStar-Reasoning)

115. [**LongReason: A Synthetic Long-Context Reasoning Benchmark via Context Expansion.**](https://arxiv.org/abs/2501.15089) _Zhan Ling, Kang Liu, Kai Yan, Yifan Yang, Weijian Lin, Ting-Han Fan, Lingfeng Shen, Zhengyin Du, Jiecao Chen._ Arxiv 2025.

116. [**Explaining Context Length Scaling and Bounds for Language Models.**](https://arxiv.org/abs/2502.01481) _Jingzhe Shi, Qinwei Ma, Hongyi Liu, Hang Zhao, Jeng-Neng Hwang, Serge Belongie, Lei Li._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/JingzheShi/NLPCtlScalingAndBounds)](https://github.com/JingzheShi/NLPCtlScalingAndBounds)

117. [**Attention Sinks and Outlier Features: A 'Catch, Tag, and Release' Mechanism for Embeddings.**](https://arxiv.org/abs/2502.00919) _Stephen Zhang, Mustafa Khan, Vardan Papyan._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://catch-tag-release.github.io/)

118. [**NoLiMa: Long-Context Evaluation Beyond Literal Matching.**](https://arxiv.org/abs/2502.05167) _Ali Modarressi, Hanieh Deilamsalehy, Franck Dernoncourt, Trung Bui, Ryan A. Rossi, Seunghyun Yoon, Hinrich Schütze._ Arxiv 2025.

119. [**Technical Debt in In-Context Learning: Diminishing Efficiency in Long Context.**](https://arxiv.org/abs/2502.04580) _Taejong Joo, Diego Klabjan._ Arxiv 2025.

120. [**DebateBench: A Challenging Long Context Reasoning Benchmark For Large Language Models.**](https://arxiv.org/abs/2502.06279) _Utkarsh Tiwari, Aryan Seth, Adi Mukherjee, Kaavya Mer, Kavish, Dhruv Kumar._ Arxiv 2025.

121. [**CLOVER: A Test Case Generation Benchmark with Coverage, Long-Context, and Verification.**](https://arxiv.org/abs/2502.08806) _Jiacheng Xu, Bo Pang, Jin Qu, Hiroaki Hayashi, Caiming Xiong, Yingbo Zhou._ Arxiv 2025.

122. [**MIR-Bench: Benchmarking LLM's Long-Context Intelligence via Many-Shot In-Context Inductive Reasoning.**](https://arxiv.org/abs/2502.09933) _Kai Yan, Zhan Ling, Kang Liu, Yifan Yang, Ting-Han Fan, Lingfeng Shen, Zhengyin Du, Jiecao Chen._ Arxiv 2025.

123. [**LaRA: Benchmarking Retrieval-Augmented Generation and Long-Context LLMs - No Silver Bullet for LC or RAG Routing.**](https://arxiv.org/abs/2502.09977) _Kuan Li, Liwen Zhang, Yong Jiang, Pengjun Xie, Fei Huang, Shuai Wang, Minhao Cheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/likuanppd/LaRA)](https://github.com/likuanppd/LaRA)

124. [**Does RAG Really Perform Bad For Long-Context Processing?.**](https://arxiv.org/abs/2502.11444) _Kun Luo, Zheng Liu, Peitian Zhang, Hongjin Qian, Jun Zhao, Kang Liu._ Arxiv 2025.

125. [**SQLong: Enhanced NL2SQL for Longer Contexts with LLMs.**](https://arxiv.org/abs/2502.16747) _Dai Quoc Nguyen, Cong Duy Vu Hoang, Duy Vu, Gioacchino Tangari, Thanh Tien Vu, Don Dharmasiri, Yuan-Fang Li, Long Duong._ Arxiv 2025.

126. [**LongSafety: Evaluating Long-Context Safety of Large Language Models.**](https://arxiv.org/abs/2502.16971) _Yida Lu, Jiale Cheng, Zhexin Zhang, Shiyao Cui, Cunxiang Wang, Xiaotao Gu, Yuxiao Dong, Jie Tang, Hongning Wang, Minlie Huang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/thu-coai/LongSafety)](https://github.com/thu-coai/LongSafety)

127. [**LR2Bench: Evaluating Long-chain Reflective Reasoning Capabilities of Large Language Models via Constraint Satisfaction Problems.**](https://arxiv.org/abs/2502.17848) _Jianghao Chen, Zhenlin Wei, Zhenjiang Ren, Ziyong Li, Jiajun Zhang._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/spaces/UltraRonin/LR2Bench)

128. [**DocPuzzle: A Process-Aware Benchmark for Evaluating Realistic Long-Context Reasoning Capabilities.**](https://arxiv.org/abs/2502.17807) _Tianyi Zhuang, Chuqiao Kuang, Xiaoguang Li, Yihua Teng, Jihao Wu, Yasheng Wang, Lifeng Shang._ Arxiv 2025.

129. [**U-NIAH: Unified RAG and LLM Evaluation for Long Context Needle-In-A-Haystack.**](https://arxiv.org/abs/2503.00353) _Yunfan Gao, Yun Xiong, Wenlong Wu, Zijing Huang, Bohan Li, Haofen Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Tongji-KGLLM/U-NIAH)](https://github.com/Tongji-KGLLM/U-NIAH)

130. [**CURIE: Evaluating LLMs On Multitask Scientific Long Context Understanding and Reasoning.**](https://arxiv.org/abs/2503.13517) _Hao Cui, Zahra Shamsi, Gowoon Cheon, Xuejian Ma, Shutong Li, Maria Tikhanovskaya, Peter Norgaard, Nayantara Mudur, Martyna Plomecka, Paul Raccuglia, Yasaman Bahri, Victor V. Albert, Pranesh Srinivasan, Haining Pan, Philippe Faist, Brian Rohr, Michael J. Statt, Dan Morris, Drew Purves, Elise Kleeman, Ruth Alcantara, Matthew Abraham, Muqthar Mohammad, Ean Phing VanLee, Chenfei Jiang, Elizabeth Dorfman, Eun-Ah Kim, Michael P Brenner, Viren Jain, Sameera Ponda, Subhashini Venugopalan._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/google/curie)](https://github.com/google/curie)

131. [**Can LLMs reason over extended multilingual contexts? Towards long-context evaluation beyond retrieval and haystacks.**](https://arxiv.org/abs/2504.12845) _Amey Hengle, Prasoon Bajpai, Soham Dan, Tanmoy Chakraborty._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/AmeyHengle/multilingual-long-context-reasoning)](https://github.com/AmeyHengle/multilingual-long-context-reasoning)

132. [**Too Long, Didn't Model: Decomposing LLM Long-Context Understanding With Novels.**](https://arxiv.org/abs/2505.14925) _Sil Hamilton, Rebecca M. M. Hicke, Matthew Wilkens, David MimnoSil Hamilton, Rebecca M. M. Hicke, Matthew Wilkens, David Mimno._ Arxiv 2025.

133. [**Longer Context, Deeper Thinking: Uncovering the Role of Long-Context Ability in Reasoning.**](https://arxiv.org/abs/2505.17315) _Wang Yang, Zirui Liu, Hongye Jin, Qingyu Yin, Vipin Chaudhary, Xiaotian Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/uservan/LCTMerge)](https://github.com/uservan/LCTMerge)

134. [**THINK-Bench: Evaluating Thinking Efficiency and Chain-of-Thought Quality of Large Reasoning Models.**](https://arxiv.org/abs/2505.22113) _Zhiyuan Li, Yi Chang, Yuan Wu._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ZhiyuanLi218/Think-Bench)](https://github.com/ZhiyuanLi218/Think-Bench)

135. [**MiniLongBench: The Low-cost Long Context Understanding Benchmark for Large Language Models.**](https://arxiv.org/abs/2505.19959) _Zhongzhan Huang, Guoming Ling, Shanshan Zhong, Hefeng Wu, Liang Lin._ ACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/MilkThink-Lab/MiniLongBench)](https://github.com/MilkThink-Lab/MiniLongBench)

136. [**100-LongBench: Are de facto Long-Context Benchmarks Literally Evaluating Long-Context Ability?.**](https://arxiv.org/abs/2505.19293) _Wang Yang, Hongye Jin, Shaochen Zhong, Song Jiang, Qifan Wang, Vipin Chaudhary, Xiaotian Han._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/uservan/100-LongBench)](https://github.com/uservan/100-LongBench)

137. [**ExpertLongBench: Benchmarking Language Models on Expert-Level Long-Form Generation Tasks with Structured Checklists.**](https://arxiv.org/abs/2506.01241) _Jie Ruan, Inderjeet Nair, Shuyang Cao, Amy Liu, Sheza Munir, Micah Pollens-Dempsey, Tiffany Chiang, Lucy Kates, Nicholas David, Sihan Chen, Ruxin Yang, Yuqian Yang, Jasmine Gump, Tessa Bialek, Vivek Sankaran, Margo Schlanger, Lu Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/launchnlp/ExpertLongBench)](https://github.com/launchnlp/ExpertLongBench)

138. [**LOOM-Scope: a comprehensive and efficient LOng-cOntext Model evaluation framework.**](https://arxiv.org/abs/2507.04723) _Zecheng Tang, Haitian Wang, Quantong Qiu, Baibei Ji, Ruoxi Sun, Keyan Zhou, Juntao Li, Min Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LCM-Lab/LOOM-Scope)](https://github.com/LCM-Lab/LOOM-Scope) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://loomscope.github.io/)

139. [**LLMThinkBench: Towards Basic Math Reasoning and Overthinking in Large Language Models.**](https://arxiv.org/abs/2507.04023) _Gaurav Srivastava, Aafiya Hussain, Sriram Srinivasan, Xuan Wang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/ctrl-gaurav/LLMThinkBench)](https://github.com/ctrl-gaurav/LLMThinkBench/)

140. [**NeedleChain: Measuring Intact Long-Context Reasoning Capability of Large Language Models.**](https://arxiv.org/abs/2507.22411) _Hyeonseok Moon, Heuiseok Lim._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/hyeonseokk/NeedleChain)](https://github.com/hyeonseokk/NeedleChain)

141. [**PRELUDE: A Benchmark Designed to Require Global Comprehension and Reasoning over Long Contexts.**](https://arxiv.org/abs/2508.09848) _Mo Yu, Tsz Ting Chung, Chulun Zhou, Tong Li, Rui Lu, Jiangnan Li, Liyan Xu, Haoshu Lu, Ning Zhang, Jing Li, Jie Zhou._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://gorov.github.io/prelude/)

142. [**OptimalThinkingBench: Evaluating Over and Underthinking in LLMs.**](https://arxiv.org/abs/2508.13141) _Pranjal Aggarwal, Seungone Kim, Jack Lanchantin, Sean Welleck, Jason Weston, Ilia Kulikov, Swarnadeep Saha._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/RAM)](https://github.com/facebookresearch/RAM/tree/main/projects/otb)

143. [**LongReasonArena: A Long Reasoning Benchmark for Large Language Models.**](https://arxiv.org/abs/2508.19363) _Jiayu Ding, Shuming Ma, Lei Cui, Nanning Zheng, Furu Wei._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LongReasonArena/LongReasonAren)](https://github.com/LongReasonArena/LongReasonArena)

144. [**A Controllable Examination for Long-Context Language Models**](https://arxiv.org/abs/2506.02921) _Yijun Yang, Zeyu Huang, Wenhao Zhu, Zihan Qiu, Fei Yuan, Jeff Z.Pan, Ivan Titov._ NeurIPS 2025 Spotlight. [![GitHub Repo stars](https://img.shields.io/github/stars/Thomasyyj/LongBio-Benchmark)](https://github.com/Thomasyyj/LongBio-Benchmark)

145. [**Large Language Models Still Exhibit Bias in Long Text.**](https://arxiv.org/abs/2410.17519) _Wonje Jeung, Dongjae Jeon, Ashkan Yousefpour, Jonghyun Choi._ Arxiv 2024.

146. [**Evaluating Zero-Shot Long-Context LLM Compression.**](https://arxiv.org/abs/2406.06773) _Chenyu Wang, Yihan Wang._ Arxiv 2024.

147. [**When Reasoning Meets Compression: Benchmarking Compressed Large Reasoning Models on Complex Reasoning Tasks.**](https://arxiv.org/abs/2504.02010) _Nan Zhang, Yusen Zhang, Prasenjit Mitra, Rui Zhang._ Arxiv 2025.

148. [**Does quantization affect models' performance on long-context tasks?.**](https://arxiv.org/abs/2505.20276) _Anmol Mekala, Anirudh Atmakuru, Yixiao Song, Marzena Karpinska, Mohit Iyyer._ Arxiv 2025.

149. [**Rethinking Key-Value Cache Compression Techniques for Large Language Model Serving.**](https://arxiv.org/abs/2503.24000) _Wei Gao, Xinyu Zhou, Peng Sun, Tianwei Zhang, Yonggang Wen._ MLSys 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/LLMkvsys/rethink-kv-compression)](https://github.com/LLMkvsys/rethink-kv-compression)

150. [**KV Cache Compression, But What Must We Give in Return? A Comprehensive Benchmark of Long Context Capable Approaches.**](https://arxiv.org/abs/2407.01527) _Jiayi Yuan, Hongyi Liu, Shaochen (Henry)Zhong, Yu-Neng Chuang, Songchen Li, Guanchu Wang, Duy Le, Hongye Jin, Vipin Chaudhary, Zhaozhuo Xu, Zirui Liu, Xia Hu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/henryzhongsc/longctx_bench)](https://github.com/henryzhongsc/longctx_bench)

151. [**RepoQA: Evaluating Long Context Code Understanding.**](https://arxiv.org/abs/2406.06025) _Jiawei Liu, Jia Le Tian, Vijay Daita, Yuxiang Wei, Yifeng Ding, Yuhan Katherine Wang, Jun Yang, Lingming Zhang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/evalplus/repoqa)](https://github.com/evalplus/repoqa)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://evalplus.github.io/repoqa.html)

152. [**mGTE: Generalized Long-Context Text Representation and Reranking Models for Multilingual Text Retrieval.**](https://arxiv.org/abs/2407.19669) _Xin Zhang, Yanzhao Zhang, Dingkun Long, Wen Xie, Ziqi Dai, Jialong Tang, Huan Lin, Baosong Yang, Pengjun Xie, Fei Huang, Meishan Zhang, Wenjie Li, Min Zhang._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/Alibaba-NLP/gte-multilingual-base)

153. [**One ruler to measure them all: Benchmarking multilingual long-context language models.**](https://arxiv.org/abs/2503.01996) _Yekyung Kim, Jenna Russell, Marzena Karpinska, Mohit Iyyer._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/mungg/OneRuler)](https://github.com/mungg/OneRuler)

154. [**The First Drop of Ink: Nonlinear Impact of Misleading Information in Long-Context Reasoning.**](https://arxiv.org/abs/2605.10828) _Muhan Gao, Zih-Ching Chen, Kuan-Hao Huang._ ICML 2026.

155. [**How Agent Skills Fail under Long Contexts: A White-Box Study in Code Auditing.**](https://arxiv.org/abs/2607.17937) _Yue Xue._ Arxiv 2026.

#### 18.2 Long-Context Multimodal & Video Benchmarks

1. [**MileBench: Benchmarking MLLMs in Long Context.**](https://arxiv.org/abs/2404.18532) _Dingjie Song, Shunian Chen, Guiming Hardy Chen, Fei Yu, Xiang Wan, Benyou Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/MileBench/MileBench)](https://github.com/MileBench/MileBench)

2. [**Many-Shot In-Context Learning in Multimodal Foundation Models.**](https://arxiv.org/abs/2405.09798) _Yixing Jiang, Jeremy Irvin, Ji Hun Wang, Muhammad Ahmed Chaudhry, Jonathan H. Chen, Andrew Y. Ng._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/stanfordmlgroup/ManyICL)](https://github.com/stanfordmlgroup/ManyICL)

3. [**MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding.**](https://arxiv.org/abs/2406.04264) _Junjie Zhou, Yan Shu, Bo Zhao, Boya Wu, Shitao Xiao, Xi Yang, Yongping Xiong, Bo Zhang, Tiejun Huang, Zheng Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/FlagOpen/FlagEmbedding)](https://github.com/FlagOpen/FlagEmbedding/tree/master/MLVU)

4. [**Short Film Dataset (SFD): A Benchmark for Story-Level Video Understanding.**](https://arxiv.org/abs/2406.10221) _Ridouane Ghermi, Xi Wang, Vicky Kalogeiton, Ivan Laptev._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/shortfilmdataset/ShortFilmDataset)](https://github.com/shortfilmdataset/ShortFilmDataset)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://shortfilmdataset.github.io/)

5. [**Multimodal Needle in a Haystack: Benchmarking Long-Context Capability of Multimodal Large Language Models.**](https://arxiv.org/abs/2406.11230) _Hengyi Wang, Haizhou Shi, Shiwei Tan, Weiyi Qin, Wenyuan Wang, Tunyu Zhang, Akshay Nambi, Tanuja Ganu, Hao Wang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/Wang-ML-Lab/multimodal-needle-in-a-haystack)](https://github.com/Wang-ML-Lab/multimodal-needle-in-a-haystack)

6. [**Losing Visual Needles in Image Haystacks: Vision Language Models are Easily Distracted in Short and Long Contexts.**](https://arxiv.org/abs/2406.16851) _Aditya Sharma, Michael Saxon, William Yang Wang._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://locovqa.github.io/)

7. [**MMLongBench-Doc: Benchmarking Long-context Document Understanding with Visualizations.**](https://arxiv.org/abs/2407.01523) _Yubo Ma, Yuhang Zang, Liangyu Chen, Meiqi Chen, Yizhu Jiao, Xinze Li, Xinyuan Lu, Ziyu Liu, Yan Ma, Xiaoyi Dong, Pan Zhang, Liangming Pan, Yu-Gang Jiang, Jiaqi Wang, Yixin Cao, Aixin Sun._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mayubo2333/MMLongBench-Doc)](https://github.com/mayubo2333/MMLongBench-Doc)
   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://mayubo2333.github.io/MMLongBench-Doc/)

8. [**Stark: Social Long-Term Multi-Modal Conversation with Persona Commonsense Knowledge.**](https://arxiv.org/abs/2407.03958) _Young-Jun Lee, Dokyong Lee, Junyoung Youn, Kyeongjin Oh, Byungsoo Ko, Jonghwan Hyeon, Ho-Jin Choi._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/passing2961/Stark)](https://github.com/passing2961/Stark)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://stark-dataset.github.io/)

9. [**SPIQA: A Dataset for Multimodal Question Answering on Scientific Papers.**](https://arxiv.org/abs/2407.09413) _Shraman Pramanick, Rama Chellappa, Subhashini Venugopalan._ Arxiv 2024.

10. [**LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding.**](https://arxiv.org/abs/2407.15754) _Haoning Wu, Dongxu Li, Bei Chen, Junnan Li._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/longvideobench/LongVideoBench)](https://github.com/longvideobench/LongVideoBench)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://longvideobench.github.io/)

11. [**MovieSum: An Abstractive Summarization Dataset for Movie Screenplays.**](https://arxiv.org/abs/2408.06281) _Rohit Saxena, Frank Keller._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/saxenarohit/MovieSum)](https://github.com/saxenarohit/MovieSum)

12. [**M-Longdoc: A Benchmark For Multimodal Super-Long Document Understanding And A Retrieval-Aware Tuning Framework.**](https://arxiv.org/abs/2411.06176) _Yew Ken Chia, Liying Cheng, Hou Pong Chan, Chaoqun Liu, Maojia Song, Sharifah Mahani Aljunied, Soujanya Poria, Lidong Bing._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://multimodal-documents.github.io/)

13. [**LongVALE: Vision-Audio-Language-Event Benchmark Towards Time-Aware Omni-Modal Perception of Long Videos.**](https://arxiv.org/abs/2411.19772) _Tiantian Geng, Jinrui Zhang, Qingni Wang, Teng Wang, Jinming Duan, Feng Zheng._ Arxiv 2024.

14. [**LMAct: A Benchmark for In-Context Imitation Learning with Long Multimodal Demonstrations.**](https://arxiv.org/abs/2412.01441) _Anian Ruoss, Fabio Pardo, Harris Chan, Bonnie Li, Volodymyr Mnih, Tim Genewein._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/lm_act)](https://github.com/google-deepmind/lm_act)

15. [**Neptune: The Long Orbit to Benchmarking Long Video Understanding.**](https://arxiv.org/abs/2412.09582) _Arsha Nagrani, Mingda Zhang, Ramin Mehran, Rachel Hornung, Nitesh Bharadwaj Gundavarapu, Nilpa Jha, Austin Myers, Xingyi Zhou, Boqing Gong, Cordelia Schmid, Mikhail Sirotenko, Yukun Zhu, Tobias Weyand._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/google-deepmind/neptune)](https://github.com/google-deepmind/neptune)

16. [**VisDoM: Multi-Document QA with Visually Rich Elements Using Multimodal Retrieval-Augmented Generation.**](https://arxiv.org/abs/2412.10704) _Manan Suri, Puneet Mathur, Franck Dernoncourt, Kanika Goswami, Ryan A. Rossi, Dinesh Manocha._ Arxiv 2024.

17. [**Is Your World Simulator a Good Story Presenter? A Consecutive Events-Based Benchmark for Future Long Video Generation.**](https://arxiv.org/abs/2412.16211) _Yiping Wang, Xuehai He, Kuan Wang, Luyao Ma, Jianwei Yang, Shuohang Wang, Simon Shaolei Du, Yelong Shen._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ypwang61/StoryEval)](https://github.com/ypwang61/StoryEval)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://ypwang61.github.io/project/StoryEval/)

18. [**LongDocURL: a Comprehensive Multimodal Long Document Benchmark Integrating Understanding, Reasoning, and Locating.**](https://arxiv.org/abs/2412.18424) _Chao Deng, Jiale Yuan, Pi Bu, Peijie Wang, Zhong-Zhi Li, Jian Xu, Xiao-Hui Li, Yuan Gao, Jun Song, Bo Zheng, Cheng-Lin Liu._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/dengc2023/LongDocURL)](https://github.com/dengc2023/LongDocURL)

19. [**HLV-1K: A Large-scale Hour-Long Video Benchmark for Time-Specific Long Video Understanding.**](https://arxiv.org/abs/2501.01645) _Heqing Zou, Tianze Luo, Guiyang Xie, Victor (Xiao Jie)Zhang, Fengmao Lv, Guangcong Wang, Junyang Chen, Zhuochen Wang, Hansheng Zhang, Huaijian Zhang._ Arxiv 2025.

20. [**MMDocIR: Benchmarking Multi-Modal Retrieval for Long Documents.**](https://arxiv.org/abs/2501.08828) _Kuicai Dong, Yujing Chang, Xin Deik Goh, Dexun Li, Ruiming Tang, Yong Liu._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://huggingface.co/MMDocIR)

21. [**EnigmaEval: A Benchmark of Long Multimodal Reasoning Challenges.**](https://arxiv.org/abs/2502.08859) _Clinton J. Wang, Dean Lee, Cristina Menghini, Johannes Mols, Jack Doughty, Adam Khoja, Jayson Lynch, Sean Hendryx, Summer Yue, Dan Hendrycks._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://scale.com/leaderboard/enigma_eval)

22. [**MomentSeeker: A Comprehensive Benchmark and A Strong Baseline For Moment Retrieval Within Long Videos.**](https://arxiv.org/abs/2502.12558) _Huaying Yuan, Jian Ni, Yueze Wang, Junjie Zhou, Zhengyang Liang, Zheng Liu, Zhao Cao, Zhicheng Dou, Ji-Rong Wen._ Arxiv 2025.

23. [**LVLM-Compress-Bench: Benchmarking the Broader Impact of Large Vision-Language Model Compression.**](https://arxiv.org/abs/2503.04982) _Souvik Kundu, Anahita Bhiwandiwalla, Sungduk Yu, Phillip Howard, Tiep Le, Sharath Nittur Sridhar, David Cobbley, Hao Kang, Vasudev Lal._ NAACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/opengear-project/LVLM-compress-bench)](https://github.com/opengear-project/LVLM-compress-bench)

24. [**NeedleInATable: Exploring Long-Context Capability of Large Language Models towards Long-Structured Tables.**](https://arxiv.org/abs/2504.06560) _Lanrui Wang, Mingyu Zheng, Hongyin Tang, Zheng Lin, Yanan Cao, Jingang Wang, Xunliang Cai, Weiping Wang._ Arxiv 2025.

25. [**LiveLongBench: Tackling Long-Context Understanding for Spoken Texts from Live Streams.**](https://arxiv.org/abs/2504.17366) _Yongxuan Wu, Runyu Chen, Peiyu Liu, Hongjin Qian._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Yarayx/livelongbench)](https://github.com/Yarayx/livelongbench)

26. [**MMLongBench: Benchmarking Long-Context Vision-Language Models Effectively and Thoroughly.**](https://arxiv.org/abs/2505.10610) _Zhaowei Wang, Wenhao Yu, Xiyu Ren, Jipeng Zhang, Yu Zhao, Rohit Saxena, Liang Cheng, Ginny Wong, Simon See, Pasquale Minervini, Yangqiu Song, Mark Steedman._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/EdinburghNLP/MMLongBench)](https://github.com/EdinburghNLP/MMLongBench)

27. [**ScaleLong: A Multi-Timescale Benchmark for Long Video Understanding.**](https://arxiv.org/abs/2505.23922) _David Ma, Huaqing Yuan, Xingjian Wang, Qianbo Zang, Tianci Liu, Xinyang He, Yanbin Wei, Jiawei Guo, Ni Jiahui, Zhenzhu Yang, Meng Cao, Shanghaoran Quan, Yizhi Li, Wangchunshu Zhou, Jiaheng Liu, Wenhao Huang, Ge Zhang, Shiwen Ni, Xiaojie Jin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/multimodal-art-projection/ScaleLong)](https://github.com/multimodal-art-projection/ScaleLong)

28. [**LVBench: An Extreme Long Video Understanding Benchmark.**](https://arxiv.org/abs/2406.08035) _Weihan Wang, Zehai He, Wenyi Hong, Yean Cheng, Xiaohan Zhang, Ji Qi, Xiaotao Gu, Shiyu Huang, Bin Xu, Yuxiao Dong, Ming Ding, Jie Tang._ ICCV 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/zai-org/LVBench)](https://github.com/zai-org/LVBench)

29. [**MMLongCite: A Benchmark for Evaluating Fidelity of Long-Context Vision-Language Models.**](https://arxiv.org/abs/2510.13276) _Keyan Zhou, Zecheng Tang, Lingfeng Ming, Guanghao Zhou, Qiguang Chen, Dan Qiao, Zheming Yang, Libo Qin, Minghui Qiu, Juntao Li, Min Zhang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/jiqimaoke/MMLongCite)](https://github.com/jiqimaoke/MMLongCite)

30. [**VideoZeroBench: Probing the Limits of Video MLLMs with Spatio-Temporal Evidence Verification.**](https://arxiv.org/abs/2604.01569) _Jiahao Meng, Tan Yue, Qi Xu, Haochen Wang, Zhongwei Ren, Weisong Liu, Yuhao Wang, Renrui Zhang, Yunhai Tong, Haodong Duan._ Arxiv 2026.

31. [**LongInsightBench: A Comprehensive Benchmark for Evaluating Omni-Modal Models on Human-Centric Long-Video Understanding.**](https://arxiv.org/abs/2510.17305) _ZhaoYang Han, Qihan Lin, Hao Liang, Bowen Chen, Zhou Liu, Wentao Zhang._ Arxiv 2025.

32. [**Beyond Accuracy: Evaluating Grounded Visual Evidence in Thinking with Images (ViEBench).**](https://arxiv.org/abs/2601.11633) _Xuchen Li, Xuzhao Li, Renjie Pi, Shiyu Hu, Jian Zhao, Jiahui Gao._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/Xuchen-Li/ViEBench)](https://github.com/Xuchen-Li/ViEBench)

33. [**StreamingEval: A Unified Evaluation Framework for Streaming Video Understanding.**](https://arxiv.org/abs/2603.21493) _Guowei Tang, Tianwen Qian, Huanran Zheng, Yifei Wang, Xiaoling Wang._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/wwgTang-111/StreamingEval1)](https://github.com/wwgTang-111/StreamingEval1)

34. [**InfiniBench: A Benchmark for Large Multi-Modal Models in Long-Form Movies and TV Shows.**](https://arxiv.org/abs/2406.19875) _Kirolos Ataallah, Eslam Abdelrahman, Mahmoud Ahmed, Chenhui Gou, Khushbu Pahwa, Jian Ding, Mohamed Elhoseiny._ Arxiv 2024.

35. [**MemLens: Benchmarking Multimodal Long-Term Memory in Large Vision-Language Models.**](https://arxiv.org/abs/2605.14906) _Xiyu Ren, Zhaowei Wang, Yiming Du, Zhongwei Xie, Chi Liu, Xinlin Yang, Haoyue Feng, Wenjun Pan, Tianshi Zheng, Baixuan Xu, Zhengnan Li, Yangqiu Song, Ginny Wong, Simon See._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/xrenaf/MEMLENS)](https://github.com/xrenaf/MEMLENS)

36. [**EGOSTREAM: A Diagnostic Benchmark for Streaming Episodic Memory in Egocentric Vision.**](https://arxiv.org/abs/2605.31557) _Rosario Forte, Giuseppe Lando, Antonino Furnari._ Arxiv 2026.

37. [**PaSBench-Video: A Streaming Video Benchmark for Proactive Safety Warning.**](https://arxiv.org/abs/2606.02443) _Yusong Zhao, Yuejin Xie, Youliang Yuan, Junjie Hu, Jitian Guo, Yujiu Yang, Pinjia He._ Arxiv 2026.

38. [**Plan, Watch, Recover: A Benchmark and Architectures for Proactive Procedural Assistance.**](https://arxiv.org/abs/2606.04970) _Kaustav Kundu, Ritvik Shrivastava, Maxim Arap, Nanshu Wang, Xianhui Zhu, Quintin Fettes, Gautam Tiwari, Parth Suresh, Théo Moutakanni, Alejandro Castillejo Munoz, Allen Bolourchi, Pascale Fung, Pinar Donmez, Babak Damavandi, Anuj Kumar, Seungwhan Moon._ Arxiv 2026.

39. [**SynthDocBench: Controlled Benchmark for Long-Context Visual Document Understanding.**](https://arxiv.org/abs/2607.10400) _Abhigya Verma, Khyati Mahajan, Amit Kumar Saha, Shruthan Radhakrishna, Sagar Davasam, Vikas Yadav, Sai Rajeswar Mudumba._ Arxiv 2026.

40. [**SLVMBench: Skill Learning from Video Memory.**](https://arxiv.org/abs/2607.11312) _Yudong Yang, Guangzhi Sun, Yixuan Li, Chao Zhang._ Arxiv 2026.

#### 18.3 Agentic Long-Horizon Benchmarks

1. [**Watching, Reasoning, and Searching: A Video Deep Research Benchmark on Open Web for Agentic Video Reasoning.**](https://arxiv.org/abs/2601.06943) _Chengwen Liu, Xiaomin Yu, Zhuoyue Chang, Zhe Huang, Shuo Zhang, Heng Lian, Kunyi Wang, Rui Xu, Sen Hu, Jianheng Hou, Hao Peng, Chengwei Qin, Xiaobin Hu, Hong Peng, Ronghao Chen, Huacan Wang._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/QuantaAlpha/VideoDR-Benchmark)](https://github.com/QuantaAlpha/VideoDR-Benchmark)
2. [**ToolBeHonest: A Multi-level Hallucination Diagnostic Benchmark for Tool-Augmented Large Language Models.**](https://arxiv.org/abs/2406.20015) _Yuxiang Zhang, Jing Chen, Junjie Wang, Yaxin Liu, Cheng Yang, Chufan Shi, Xinyu Zhu, Zihao Lin, Hanwen Wan, Yujiu Yang, Tetsuya Sakai, Tian Feng, Hayato Yamana._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/ToolBeHonest/ToolBeHonest)](https://github.com/ToolBeHonest/ToolBeHonest)

3. [**ComplexFuncBench: Exploring Multi-Step and Constrained Function Calling under Long-Context Scenario.**](https://arxiv.org/abs/2501.10132) _Lucen Zhong, Zhengxiao Du, Xiaohan Zhang, Haiyi Hu, Jie Tang._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/ComplexFuncBench)](https://github.com/THUDM/ComplexFuncBench)

4. [**SwingArena: Competitive Programming Arena for Long-context GitHub Issue Solving.**](https://arxiv.org/abs/2505.23932) Wendong Xu, Jing Xiong, Chenyang Zhao, Qiujiang Chen, Haoran Wang, Hui Shen, Zhongwei Wan, Jianbo Dai, Taiqiang Wu, He Xiao, Chaofan Tao, Z. Morley Mao, Ying Sheng, Zhijiang Guo, Hongxia Yang, Bei Yu, Lingpeng Kong, Quanquan Gu, Ngai Wong._ Arxiv 2025.

5. [**UltraHorizon: Benchmarking Agent Capabilities in Ultra Long-Horizon Scenarios.**](https://arxiv.org/abs/2509.21766) _Haotian Luo, Kaijiang Pan, Bosheng Qin, Yijun Wang, Yubai Yuan, Chufeng Tang, Zhongyi Li, Lei Chen, Wenqi Shao, Yao Teng, Yongqi Zhang, Yuhui Yuan, Maosong Sun, Li Shen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/StarDewXXX/UltraHorizon)](https://github.com/StarDewXXX/UltraHorizon)

6. [**Spider 2.0: Evaluating Language Models on Real-World Enterprise Text-to-SQL Workflows.**](https://arxiv.org/abs/2411.07763) _Fangyu Lei, Jixuan Chen, Yuxiao Ye, Ruisheng Cao, Dongchan Shin, Hongjin Su, Zhaoqing Suo, Hongcheng Gao, Wenjing Hu, Pengcheng Yin, Victor Zhong, Caiming Xiong, Ruoxi Sun, Qian Liu, Sida Wang, Tao Yu._ Arxiv 2024. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://spider2-sql.github.io/)
     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![GitHub Repo stars](https://img.shields.io/github/stars/xlang-ai/Spider2)](https://github.com/xlang-ai/Spider2)

7. [**Evaluating Very Long-Term Conversational Memory of LLM Agents.**](https://arxiv.org/abs/2402.17753) _Adyasha Maharana, Dong-Ho Lee, Sergey Tulyakov, Mohit Bansal, Francesco Barbieri, Yuwei Fang._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/snap-research/LoCoMo)](https://github.com/snap-research/LoCoMo)

8. [**GroupMemBench: Benchmarking LLM Agent Memory in Multi-Party Conversations.**](https://arxiv.org/abs/2605.14498) _Jingbo Yang, Kwei-Herng Lai, Xiaowen Wang, Shiyu Chang, Yaar Harari, Evgeniy Gabrilovich._ Arxiv 2026.

9. [**MemEye: A Visual-Centric Evaluation Framework for Multimodal Agent Memory.**](https://arxiv.org/abs/2605.15128) _Minghao Guo, Qingyue Jiao, Zeru Shi, Yihao Quan, Boxuan Zhang, Danrui Li, Liwei Che, Wujiang Xu, Shilong Liu, Zirui Liu, Mubbasir Kapadia, Vladimir Pavlovic, Jiang Liu, Mengdi Wang, Yiyu Shi, Dimitris N. Metaxas, Ruixiang Tang._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/MinghoKwok/MemEye)](https://github.com/MinghoKwok/MemEye) [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://minghokwok.github.io/MemEye/)

10. [**Beyond Static Dialogues: Benchmarking Realistic, Heterogeneous, and Evolving Long-Term Memory.**](https://arxiv.org/abs/2605.31086) _Han Zhang, Zihao Tang, Xin Yu, Xiao Liu, Yeyun Gong, Haizhen Huang, Yan Lu, Weiwei Deng, Feng Sun, Qi Zhang, Hanfang Yang._ Arxiv 2026.

11. [**H2HMem: A Multimodal Memory Benchmark for Agents in Human-Human Interactions.**](https://arxiv.org/abs/2606.09461) _Shiping Zhu, Yibo Yang, Zhengyang Wang, Tiancheng Shen, Dandan Guo, Ming-Hsuan Yang._ Arxiv 2026.

12. [**SWE-Marathon: Can Agents Autonomously Complete Ultra-Long-Horizon Software Work?**](https://arxiv.org/abs/2606.07682) _Rishi Desai, Jesse Hu, Joan Cabezas, Neel Harsola, Pratyush Shukla, Roey Ben Chaim, Adnan El Assadi, Omkaar Mukund Kamath, Fenil Faldu, Prannay Hebbar, Jiankai Sun, Yiyuan Li, Pramod Srinivasan, Ishan Gupta, Christopher Settles, Daniel Wang, Derek Chen, Pranav Raja, Albert Liu, Marek Šuppa, Nevasini Sasikumar, Luyang Kong, Erik Quintanilla, Xiangyi Li, Ivan Bercovich, Steven Dillmann._ Arxiv 2026. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://swe-marathon.org/)

13. [**EvoArena: Tracking Memory Evolution for Robust LLM Agents in Dynamic Environments.**](https://arxiv.org/abs/2606.13681) _Jundong Xu, Qingchuan Li, Jiaying Wu, Yihuai Lan, Shuyue Stella Li, Huichi Zhou, Bowen Jiang, Lei Wang, Jun Wang, Anh Tuan Luu, Caiming Xiong, Hae Won Park, Bryan Hooi, Zhiyuan Hu._ Arxiv 2026.

14. [**DynamicMem: A Long-Horizon Memory Benchmark in Real-World Settings.**](https://arxiv.org/abs/2606.22877) _Wenya Xie, Shengming Zhou, Zelin Li, Pouya Parsa, Shuang Zhou, Xinheng Ding, Chinmay Arvind, Guanchu Wang, Vladimir Braverman, Ali Payani, Yantao Zheng, Zirui Liu._ Arxiv 2026. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://wenyaxie023.github.io/DynamicMem/)

15. [**GateMem: Benchmarking Memory Governance in Multi-Principal Shared-Memory Agents.**](https://arxiv.org/abs/2606.18829) _Zhe Ren, Yibo Yang, Yimeng Chen, Zijun Zhao, Benshuo Fu, Zhihao Shu, Bingjie Zhang, Yangyang Xu, Dandan Guo, Shuicheng Yan._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/rzhub/GateMem)](https://github.com/rzhub/GateMem)

16. [**StreamMemBench: Streaming Evaluation of Agent Memory for Future-Oriented Assistance.**](https://arxiv.org/abs/2606.14571) _Guanming Liu, Yuqi Ren, Hansu Gu, Peng Zhang, Weihang Wang, Jiahao Liu, Ning Gu, Tun Lu._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/landian60/StreamMemBench)](https://github.com/landian60/StreamMemBench)

17. [**ClawBench: Can AI Agents Complete Everyday Online Tasks?**](https://arxiv.org/abs/2604.08523) _Yuxuan Zhang, Yubo Wang, Yipeng Zhu, Penghui Du, Junwen Miao, Xuan Lu, Zhuofeng Li, Xingwei Qu, Zhengkang Guo, Yuanzhe Shen, Dingjie Song, Han Zhou, Tuney Zheng, Xian Wu, Hao Yu, Songcheng Cai, Yi Lu, Yunzhuo Hao, Minyi Lei, Liang Chen, Kai Zou, Huifeng Yin, Wendong Xu, Dongfu Jiang, Ping Nie, Jiaheng Liu, Wenhu Chen, Kelsey R. Allen._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/reacher-z/ClawBench)](https://github.com/reacher-z/ClawBench) [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://claw-bench.com/)

18. [**MemOps: Benchmarking Lifecycle Memory Operations in Long-Horizon Conversations.**](https://arxiv.org/abs/2607.12893) _Xixuan Hao, Zeyu Zhang, Zehao Lin, Yihang Sun, Ziliang Guo, Xichong Zhang, Yuxuan Liang, Feiyu Xiong, Zhiyu Li._ Arxiv 2026.

19. [**AgenticSTS: A Bounded-Memory Testbed for Long-Horizon LLM Agents.**](https://arxiv.org/abs/2607.02255) _Xiangchen Cheng, Yunwei Jiang, Jianwen Sun, Zizhen Li, Chuanhao Li, Xiangcheng Cao, Yihao Liu, Fanrui Zhang, Li Jin, Kaipeng Zhang._ Arxiv 2026.

20. [**MemSyco-Bench: Benchmarking Sycophancy in Agent Memory.**](https://arxiv.org/abs/2607.01071) _Zhishang Xiang, Zerui Chen, Yunbo Tang, Zhimin Wei, Ruqin Ning, Yujie Lin, Qinggang Zhang, Jinsong Su._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/XMUDeepLIT/MemSyco-Bench)](https://github.com/XMUDeepLIT/MemSyco-Bench)

21. [**Long-Horizon-Terminal-Bench: Testing the Limits of Agents on Long-Horizon Terminal Tasks with Dense Reward-Based Grading.**](https://arxiv.org/abs/2607.08964) _Zongxia Li, Zhongzhi Li, Yucheng Shi, Ruhan Wang, Junyao Yang, Zhichao Liu, Xiyang Wu, Anhao Li, Yue Yu, Ninghao Liu, Lichao Sun, Haotao Mi, Leowei Liang._ Arxiv 2026.

22. [**OSWorld2.0: Benchmarking Computer Use Agents on Long-Horizon Real-World Tasks.**](https://arxiv.org/abs/2606.29537) _Mengqi Yuan, Zilong Zhou, Xinzhuang Xiong, Weiming Wu, Jiayang Sun, Jiamin Song, Kaiqian Cui, Bowen Wang, Haoyuan Wu, Yitong Li, Dunjie Lu, Haikong Lu, Qi Zhen, Xinyuan Wang, Jiaqi Deng, Yuhao Yang, et al.._ Arxiv 2026.

23. [**SWE-INTERACT: Reimagining SWE Benchmarks as User-Driven Long-Horizon Coding Sessions.**](https://arxiv.org/abs/2606.30573) _Mohit Raghavendra, Anisha Gunjal, Aakash Sabharwal, Yunzhong He._ Arxiv 2026.

24. [**ArbiGraph: Arbitrarily Scalable Verifiable Task Graphs for Evaluating Context Management.**](https://arxiv.org/abs/2607.20764) _Pavel Golikov, Evgenii Opryshko, Gennady Pekhimenko, Mark C. Jeffrey._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/pavelgolikov/ArbiGraph)](https://github.com/pavelgolikov/ArbiGraph)

25. [**DMV-Bench: Diagnosing Long-Horizon Multimodal Agents' Visual Memory with Incidental Cue Injection.**](https://arxiv.org/abs/2606.27499) _Yujin Tang, Chenming Shang, Ruize Xu, Nikhil Singh._ Arxiv 2026. [![GitHub Repo stars](https://img.shields.io/github/stars/yyyujintang/DMV-Bench)](https://github.com/yyyujintang/DMV-Bench)

#### 18.4 Long Reasoning / Long Generation Benchmarks

1. [**Lost-in-the-Middle in Long-Text Generation: Synthetic Dataset, Evaluation Framework, and Mitigation.**](https://arxiv.org/abs/2503.06868) _Junhao Zhang, Richong Zhang, Fanshuang Kong, Ziyang Miao, Yanhan Ye, Yaowei Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OnlyAR/RAL-Writer)](https://github.com/OnlyAR/RAL-Writer)

2. [**ExPerT: Effective and Explainable Evaluation of Personalized Long-Form Text Generation.**](https://arxiv.org/abs/2501.14956) _Alireza Salemi, Julian Killingback, Hamed Zamani._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/alirezasalemi7/ExPerT)](https://github.com/alirezasalemi7/ExPerT)

3. [**LongProc: Benchmarking Long-Context Language Models on Long Procedural Generation.**](https://arxiv.org/abs/2501.05414) _Xi Ye, Fangcong Yin, Yinghui He, Joie Zhang, Howard Yen, Tianyu Gao, Greg Durrett, Danqi Chen._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/princeton-pli/LongProc)](https://github.com/princeton-pli/LongProc)
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://princeton-pli.github.io/LongProc/)

4. [**The FACTS Grounding Leaderboard: Benchmarking LLMs' Ability to Ground Responses to Long-Form Input.**](https://arxiv.org/abs/2501.03200) _Alon Jacovi, Andrew Wang, Chris Alberti, Connie Tao, Jon Lipovetz, Kate Olszewska, Lukas Haas, Michelle Liu, Nate Keating, Adam Bloniarz, Carl Saroufim, Corey Fry, Dror Marcus, Doron Kukliansky, Gaurav Singh Tomar, James Swirhun, Jinwei Xing, Lily Wang, Madhu Gurumurthy, Michael Aaron, Moran Ambar, Rachana Fellinger, Rui Wang, Zizhao Zhang, Sasha Goldshtein, Dipanjan Das._ Arxiv 2025. [![Static Badge](https://img.shields.io/badge/Homepage-blue)](https://www.kaggle.com/facts-leaderboard)

5. [**Beyond Factual Accuracy: Evaluating Coverage of Diverse Factual Information in Long-form Text Generation.**](https://arxiv.org/abs/2501.03545) _Chris Samarinas, Alexander Krubner, Alireza Salemi, Youngwoo Kim, Hamed Zamani._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/algoprog/ICAT)](https://github.com/algoprog/ICAT)

6. [**Ref-Long: Benchmarking the Long-context Referencing Capability of Long-context Language Models.**](https://arxiv.org/abs/2507.09506) _Junjie Wu, Gefei Gu, Yanan Zheng, Dit-Yan Yeung, Arman Cohan._ ACL 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/wujunjie1998/Ref-Long)](https://github.com/wujunjie1998/Ref-Long)

7. [**Can Large Language Models Detect Errors in Long Chain-of-Thought Reasoning?.**](https://arxiv.org/abs/2502.19361) _Yancheng He, Shilong Li, Jiaheng Liu, Weixun Wang, Xingyuan Bu, Ge Zhang, Zhongyuan Peng, Zhaoxiang Zhang, Zhicheng Zheng, Wenbo Su, Bo Zheng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/OpenStellarTeam/DeltaBench)](https://github.com/OpenStellarTeam/DeltaBench)

8. [**THOUGHTTERMINATOR: Benchmarking, Calibrating, and Mitigating Overthinking in Reasoning Models.**](https://arxiv.org/abs/2504.13367) _Xiao Pu, Michael Saxon, Wenyue Hua, William Yang Wang._ Arxiv 2025.

9. [**LongGenBench: Benchmarking Long-Form Generation in Long Context LLMs.**](https://arxiv.org/abs/2409.02076) _Yuhao Wu, Ming Shan Hee, Zhiqing Hu, Roy Ka-Wei Lee._ Arxiv 2024. [![GitHub Repo stars](https://img.shields.io/github/stars/mozhu621/LongGenBench)](https://github.com/mozhu621/LongGenBench/)

10. [**LongEval: A Comprehensive Analysis of Long-Text Generation Through a Plan-based Paradigm.**](https://arxiv.org/abs/2502.19103) _Siwei Wu, Yizhi Li, Xingwei Qu, Rishi Ravikumar, Yucheng Li, Tyler Loakman Shanghaoran Quan Xiaoyong Wei, Riza Batista-Navarro, Chenghua Lin._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/Wusiwei0410/LongEval)](https://github.com/Wusiwei0410/LongEval)

11. [**DeFine: A Decomposed and Fine-Grained Annotated Dataset for Long-form Article Generation.**](https://arxiv.org/abs/2503.07170) _Ming Wang, Fang Wang, Minghao Hu, Li He, Haiyang Wang, Jun Zhang, Tianwei Yan, Li Li, Zhunchen Luo, Wei Luo, Xiaoying Bai, Guotong Geng._ Arxiv 2025. [![GitHub Repo stars](https://img.shields.io/github/stars/DeFine-LFAG/DeFine_Dataset)](https://github.com/DeFine-LFAG/DeFine_Dataset)

12. [**LiteLong: Resource-Efficient Long-Context Data Synthesis for LLMs.**](https://arxiv.org/abs/2509.15568) _Junlong Jia, Xing Wu, Chaochen Gao, Ziyang Chen, Zijia Lin, Zhongzhi Li, Weinong Wang, Haotian Xu, Donghui Jin, Debing Zhang, Binghui Guo._ Arxiv 2025.
