## Machine Reading Comprehension

### Literature
  - [English Machine Reading Comprehension Datasets: A Survey](https://aclanthology.org/2021.emnlp-main.693.pdf)
  - [RCPapers](https://github.com/thunlp/RCPapers): Must-read papers on Machine Reading Comprehension, by THUNLP.
  - [Reading-Comprehension-Question-Answering-Papers](https://github.com/xanhho/Reading-Comprehension-Question-Answering-Papers): Survey on Machine Reading Comprehension, by Xanh Ho.
  - [MRC_book](https://github.com/zcgzcgzcg1/MRC_book): 《机器阅读理解：算法与实践》代码, by Chenguang Zhu.
  - [Multi-hopRC](https://github.com/krystalan/Multi-hopRC): 多跳阅读理解相关论文, by Jiaan Wang.
  - [Sewon Min (민세원) personal homepage](https://shmsw25.github.io/)

### Classic Model
  - R-NET 2017: [paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/r-net.pdf)|[code](https://github.com/localminimum/R-net)
  - DrQA 2017: [paper](https://arxiv.org/pdf/1704.00051.pdf)|[code](https://github.com/facebookresearch/DrQA)
  - BiDAF 2018: [paper](https://arxiv.org/pdf/1611.01603.pdf)|[code](https://github.com/allenai/bi-att-flow)|[homepage](https://allenai.github.io/bi-att-flow/)
  - QANet 2018: [paper](https://arxiv.org/pdf/1804.09541.pdf)|[code](https://github.com/localminimum/QANet)
  - BERT-MRC(base) 2018: [paper](https://arxiv.org/pdf/1810.04805.pdf)|[code](https://github.com/huggingface/transformers/tree/master/examples/pytorch/multiple-choice)(multi-choices)|[code](https://github.com/huggingface/transformers/tree/master/examples/pytorch/question-answering)(question-answering)
  - NumNet 2019: [paper](https://aclanthology.org/D19-1251/)|[code](https://github.com/ranqiu92/NumNet)

### Dialogue MRC
  - [面向对话的机器阅读理解任务（Dialogue MRC）相关论文整理](https://mp.weixin.qq.com/s/R2e1-Bn1FF5pt25qhsh0jA)

### Explainability in MRC
  - [ExpMRC: explainability evaluation for machine reading comprehension (2022)](https://www.cell.com/action/showPdf?pii=S2405-8440%2822%2900578-3)
  - [A Survey on Explainability in Machine Reading Comprehension (2020)](https://arxiv.org/abs/2010.00389)

### Logical Reasoning
  - [赛尔笔记 | 逻辑推理阅读理解任务及方法](https://mp.weixin.qq.com/s/OiiE6fLXs3JVTbbCKHmXzg)
  - [ReClor：一个需要逻辑推理的数据集](https://zhuanlan.zhihu.com/p/143067841)
  - [从Bengio演讲发散开来：探讨逻辑推理与机器学习](https://zhuanlan.zhihu.com/p/265157196?utm_source=qq)

### Multi-Hop MRC
  - PathNet 2018: [paper](https://arxiv.org/pdf/1811.01127.pdf)|[code](https://github.com/allenai/PathNet)
  - CogQA 2019: [homepage](https://sites.google.com/view/cognitivegraph/)|[paper](https://arxiv.org/pdf/1905.05460.pdf)|[code](https://github.com/THUDM/CogQA)
  - DecompRC 2019: [paper](https://arxiv.org/pdf/1906.02916.pdf)|[code](https://github.com/shmsw25/DecompRC)|[demo](http://allgood.cs.washington.edu:2019/)
  - SAE 2020: [paper](https://arxiv.org/pdf/1911.00484.pdf)|[code](https://github.com/JD-AI-Research-Silicon-Valley/SAE)

### Datasets & Competitions
  - [CAIL](https://github.com/china-ai-law-challenge): **C**hina **AI** **L**aw Challenge(中国法研杯司法人工智能挑战赛(含阅读理解赛道)).
  - [C³](https://dataset.org/c3/): Multiple-**C**hoice **C**hinese Machine Reading **C**omprehension Dataset.
  - [ChID](https://aclanthology.org/P19-1075.pdf): A Large-scale **Ch**inese **ID**iom Dataset for Cloze Test.
  - [CLICR](https://github.com/clips/clicr): Machine reading comprehension on **CLI**nical **C**ase **R**eports.
  - [CLUE阅读理解排行榜](https://www.cluebenchmarks.com/rc.html)
  - [CMRC](https://hfl-rc.com/cmrc/)
    - [CMRC 2017](https://hfl-rc.com/cmrc2017/): The 1st Evaluation Workshop on **C**hinese **M**achine **R**eading **C**omprehension.
    - [CMRC 2018](https://ymcui.com/cmrc2018/): A Span-Extraction Dataset for **C**hinese **M**achine **R**eading **C**omprehension.
    - [CMRC 2019](https://ymcui.com/cmrc2019/): A Sentence Cloze Dataset for **C**hinese **M**achine **R**eading **C**omprehension.
    - [CMRC 2020](https://hfl-rc.com/cmrc2020/): Challenge of AI in Law ([CAIL](http://cail.cipsc.org.cn/)) for **C**hinese **M**achine **R**eading **C**omprehension.
    - [CMRC 2022](https://hfl-rc.com/cmrc2022/): A Weak-Supervised Explainability-focused Dataset (from [ExpMRC](https://ymcui.com/expmrc/)) for **C**hinese **M**achine **R**eading **C**omprehension.
  - [CoQA](https://stanfordnlp.github.io/coqa/): A Conversational Question Answering Challenge.
  - [DREAM](https://github.com/nlpdata/dream): A Challenge Dataset and Models for Dialogue-Based Reading Comprehension.
  - [DRCD](https://github.com/DRCKnowledgeTeam/DRCD): **D**elta **R**eading **C**omprehension **D**ataset.
  - [DROP](https://allennlp.org/drop): A Reading Comprehension Benchmark Requiring **D**iscrete **R**easoning **O**ver **P**aragraphs.
  - [DuReader](https://aistudio.baidu.com/aistudio/competition/detail/49/?isFromLUGE=TRUE) from [千言（LUGE）](https://www.luge.ai/): a Chinese Machine Reading Comprehension Dataset from Real-world Applications.
  - [ExpMRC](https://ymcui.com/expmrc/): **Exp**lainability Evaluation for **M**achine **R**eading **C**omprehension. [哈工大讯飞联合实验室发布可解释性阅读理解评测集ExpMRC](https://mp.weixin.qq.com/s/spR-KQWWTxZD44jGnuOF7Q)
  - [FinQA](https://github.com/czyssrs/FinQA)([paper](https://arxiv.org/abs/2109.00122)): A Dataset of Numerical Reasoning over Financial Data.
  - [FriendsQA](https://github.com/emorynlp/FriendsQA): Open-Domain Question Answering on TV Show Transcripts.
  - [Hotpot](https://hotpotqa.github.io/): A Dataset for Diverse, Explainable Multi-hop Question Answering.
  - [LogiQA](https://arxiv.org/abs/2007.08124): A Challenge Dataset for Machine Reading Comprehension with Logical Reasoning.
  - [MCScript](https://arxiv.org/pdf/1803.05223.pdf): A Novel Dataset for Assessing Machine Comprehension Using Script Knowledge.
  - [MCTest](https://www.microsoft.com/en-us/research/publication/mctest-challenge-dataset-open-domain-machine-comprehension-text/): A Challenge Dataset for the Open-Domain Machine Comprehension of Text.
  - [MS MARCO](https://microsoft.github.io/msmarco/): A Human Generated **MA**chine **R**eading **CO**mprehension Dataset.
  - [NarrativeQA](https://aclanthology.org/Q18-1023.pdf): The NarrativeQA Reading Comprehension Challenge.
  - [NewsQA](https://www.microsoft.com/en-us/research/project/newsqa-dataset/): A Machine Comprehension Dataset.
  - [NumNet+](https://leaderboard.allenai.org/drop/submission/bm60vq8f7g2p7t2ld0j0) & [NumNet+ v2](https://leaderboard.allenai.org/drop/submission/bmfuq9e0v32fq8pskug0): Machine Reading Comprehension with Numerical Reasoning.
  - [QAConv](https://github.com/salesforce/QAConv): **Q**uestion **A**nswering on Informative **Conv**ersations.
  - [ReClor](https://arxiv.org/abs/2002.04326): A **Re**ading **C**omprehension Dataset Requiring **Lo**gical **R**easoning.
  - [SearchQA](https://arxiv.org/pdf/1704.05179.pdf): A New Q&A Dataset Augmented with Context from a Search Engine.
  - [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/): The **S**tanford **Qu**estion **A**nswering **D**ataset (v1.1 & v2.0).
  - [TriviaQA](https://nlp.cs.washington.edu/triviaqa/): A Large Scale Distantly Supervised Challenge Dataset for Reading Comprehension.

### All about Question, Answer, Evidence...
  * Question-Generation-Paper-List
    - link: https://github.com/teacherpeterpan/Question-Generation-Paper-List
    - author: Liangming Pan
    - note: a summary of must-read papers for Neural Question Generation (NQG).
  * Questgen.ai
    - link: https://github.com/ramsrigouthamg/Questgen.ai
    - author: Ramsri Goutham Golla
    - note: question generation using state-of-the-art nlp algorithms.
  * Question-Generation
    - link: https://github.com/KristiyanVachev/Question-Generation
    - author: Kristiyan Vachev
    - note: generating multiple choice questions from text using Machine Learning..
  * question_generator
    - link: https://github.com/AMontgomerie/question_generator
    - author: Adam Montgomerie
    - note: an nlp system for generating reading comprehension questions.
