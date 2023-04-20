## **Pre-Trained Language Model (Unsupervised Representation Learning)**


### References
  * [PLMpapers](https://github.com/thunlp/PLMpapers): a list of the representative work on Pre-trained Languge Model.
  * [Book: Representation Learning for Natural Language Processing](https://github.com/thunlp/Book_RL4NLP).
  * [OpenCLaP](https://github.com/thunlp/OpenCLaP): Open Chinese Language Pre-trained Model Zoo.
  * [OpenVINO](https://github.com/openvinotoolkit/openvino): a toolkit allowing developers to deploy pre-trained deep learning models through a high-level C++ Inference Engine API integrated with application logic.
  * [Kashgari](https://github.com/BrikerMan/Kashgari): a Production-ready NLP Transfer learning framework for text-labeling and text-classification, includes Word2Vec, BERT, and GPT2 Language Embedding.
  * [Awesome Pretrained Chinese NLP Models](https://github.com/lonePatient/awesome-pretrained-chinese-nlp-models): 高质量中文预训练模型集合.
  * [Chinese-Minority-PLM](https://github.com/ymcui/Chinese-Minority-PLM): 少数民族语言预训练模型.
  * [ColossalAI](https://github.com/hpcaitech/ColossalAI): a unified deep learning system for big model era.
  * [OpenBMB](https://github.com/OpenBMB/BMList): a list of big models.

### Benchmark
  * [ChineseGLUE](https://github.com/chineseGLUE/chineseGLUE): Language Understanding Evaluation benchmark for Chinese: datasets, baselines, pre-trained models,corpus and leaderboard.
  * [CLUE](https://github.com/CLUEbenchmark/CLUE): Advanced version of ChineseGLUE ([homepage](https://www.cluebenchmarks.com/)/[paper](https://arxiv.org/abs/2004.05986)).
  * [FewCLUE](https://github.com/CLUEbenchmark/FewCLUE): [paper](https://arxiv.org/abs/2107.07498)
  * [ChineseBLUE](https://github.com/alibaba-research/ChineseBLUE): Chinese Biomedical Language Understanding Evaluation benchmark.
  * CUGE(Chinese LanguageUnderstanding and Generation Evaluation): [report](arxiv.org/pdf/2112.13610.pdf)/[homepage](cuge.baai.ac.cn)
  * NATURAL-INSTRUCTIONSv2: [paper](https://arxiv.org/pdf/2204.07705.pdf), [news](https://mp.weixin.qq.com/s/VulP2-xSeJQsn4SwwFaC7w)

### Tokenizer
  * Pinyin Tokenizer
    - link: https://github.com/shibing624/pinyin-tokenizer
    - author: xuming
    - note: 使用python3开发的中文拼音分词器，将连续的拼音切分为单字拼音列表，开箱即用。
  * tiktoken
    - link: https://github.com/openai/tiktoken
    - author: OpenAI
    - note: a fast BPE tokeniser for use with OpenAI's models.
  * easytokenizer
    - link: https://github.com/zejunwang1/easytokenizer
    - author: WangZeJun
    - note: 一个简单易用的高性能文本 Tokenizer 库，支持类似 HuggingFace transformers 中 BertTokenizer 的词语切分和标记化功能。
    - blog: [easytokenizer-v0.2.0: 高性能文本 Tokenizer 库](https://mp.weixin.qq.com/s/hxbAlRS4hDMqPxOQtPmxCQ)

### ELMo
  * [paper](http://export.arxiv.org/pdf/1812.10860): Samuel R. , Ellie P. , Edouard G. , Benjamin Van D. , Alex W. , Jan H. , Patrick X. , Raghavendra P. , R. T. M. , Roma P. , Najoung K. , Ian T. , Yinghui H. , Katherin Y. , Shuning J. , Berlin C. . (2018). *Looking for ELMo's Friends: Sentence-Level Pretraining Beyond Language Modeling*. 
  * code: [Origin by ML²AT CILVR Report](https://github.com/nyu-mll/jiant), [Tutorial by Prashant Ranjan](https://github.com/PrashantRanjan09/Elmo-Tutorial), [keras by iliaschalkidis](https://github.com/iliaschalkidis/ELMo-keras), [Multi-Language-oriented ELMo by HIT-SCIR](https://github.com/HIT-SCIR/ELMoForManyLangs), [another keras version by strongio](https://github.com/strongio/keras-elmo).

### Transformer
  * [paper](https://arxiv.org/pdf/1706.03762.pdf): Vaswani, A. , Shazeer, N. , Parmar, N. , Uszkoreit, J. , Jones, L. , & Gomez, A. N. , et al. (2017). *Attention is all you need*.
  * code: 
    - [pytorch by Yu-Hsiang Huang](https://github.com/jadore801120/attention-is-all-you-need-pytorch)
    - [tensorflow by Kyubyong](https://github.com/Kyubyong/transformer)
    - [another pytorch version by leviswind](https://github.com/leviswind/pytorch-transformer)
    - [Simple Transformers by Thilina Rajapakse](https://github.com/ThilinaRajapakse/simpletransformers)
    - [Transformers-Recipe](https://github.com/dair-ai/Transformers-Recipe)
  * attention:
    - [External-Attention-pytorch](https://github.com/xmu-xiaoma666/External-Attention-pytorch): pytorch implementation of various attention mechanisms, mlp, re-parameter, convolution, which is helpful to further understand papers.
  * survey: 
    - [2023年：Transformer models: an introduction and catalog](https://arxiv.org/abs/2302.07730): [ChatGPT背后的大模型最新有哪些？最新最全《Transformer预训练模型分类》论文，36页pdf详述大模型技术目录](https://mp.weixin.qq.com/s/ISOcGNaGKTw7pefvWi74lg)
    - [2022年：Shortcut Learning of Large Language Models in Natural Language Understanding: A Survey](https://www.arxiv-vanity.com/papers/2208.11857/)
    - [2022年：从SwinTransformer到GFlowNets，我们从2021年2万份SOTA工作中选了256个最值得关注的（附完整名录）](https://mp.weixin.qq.com/s/41kaiZm7PR5bRb8GpAJcTw)
    - [2021年：自然语言处理：基于预训练模型的方法](https://github.com/HIT-SCIR/plm-nlp-code)(哈工大SCIR 车万翔、郭江、崔一鸣著)
    - [2021年：国内数十位NLP大佬合作，综述预训练模型的过去、现在与未来](https://mp.weixin.qq.com/s/3hlSFny6RjwwxZODlEgSlA)
    - [2021年：复旦大学邱锡鹏教授团队：Transformer最新综述](https://mp.weixin.qq.com/s/0DYOljpR9ePbutMvn8fMzQ)
    - [2021年：视觉Transformer最新综述](https://mp.weixin.qq.com/s/-4jLuBOTh9oM46r45T3efA)
    - [Long Range Arena: A Benchmark for Efficient Transformers (2020-11)](https://arxiv.org/pdf/2011.04006.pdf)
    - [Efficient Transformers: A Survey (2020-09)](https://arxiv.org/pdf/2009.06732.pdf)
  * introduction/tutorial:
    - [2022年：transformer-walkthrough](https://github.com/markriedl/transformer-walkthrough): a walkthrough of transformer architecture code.
    - [2022年：简单实现 BERT](https://mp.weixin.qq.com/s/tV7DwiFx7SAccgh2byqb2g)
    - [2022年：技术解读：BERT语言模型的预训练源码浅析与总结](https://mp.weixin.qq.com/s/9NXDZDDTFV5xmm3ONjyiKw)
    - [2022年：Bert系列之模型参数计算](https://mp.weixin.qq.com/s/D7T0Pdqr01viicJfAWdIMQ)
    - [2022年：矩阵视角下的Transformer详解（附代码）](https://mp.weixin.qq.com/s/ZllvtpGfkLrcUBKZDtdoTA)
    - [2021年：HuggingFace BERT源码详解：基本模型组件实现](https://mp.weixin.qq.com/s/I4KSerhkFJdnIIpaZuf08A)
    - [2021年：Huggingface BERT源码详解：应用模型与训练优化](https://mp.weixin.qq.com/s/gR2i8HvyRBUxofovQarLNw)
    - [2021年：详解Transformer](https://zhuanlan.zhihu.com/p/48508221)
    - [2021年：3W字长文带你轻松入门视觉transformer](https://zhuanlan.zhihu.com/p/308301901)
    - [2020年：How Transformers work in deep learning and NLP: an intuitive introduction](https://theaisummer.com/transformer/) by [AI SUMMER](https://theaisummer.com/)
    - [2018年：The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html)
    - [2018年：真正的完全图解Seq2Seq Attention模型](https://mp.weixin.qq.com/s/0k71fKKv2SRLv9M6BjDo4w)

### Variations of Transformer
  * Fast Transformers
    - [paper](https://arxiv.org/abs/2006.16236): Katharopoulos, A. , Vyas, A. , Pappas, N. , Fleuret, F. . (2020). *Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention*.
    - code: [fast-transformers by Idiap Research Institute](https://github.com/idiap/fast-transformers)
    - website: https://linear-transformers.com/
  * Flowformer
    - code: https://github.com/thuml/Flowformer
    - author: THUML
    - [paper](https://arxiv.org/pdf/2202.06258.pdf): Wu, H. , Wu, J. , Xu, J. , Wang, J. , & Long, M. . (2022). *Flowformer: linearizing transformers with conservation flows*.
    - blog: [任务通用！清华提出主干网络Flowformer，实现线性复杂度｜ICML2022](https://mp.weixin.qq.com/s/kiMnIaRh5uf8jcFzWWEtKQ)
  * Infinite Memory Transformer
    - [paper](https://arxiv.org/abs/2109.00301): Martins, P. H., Marinho, Z., & Martins, A. F. (2021). *$\infty $-former: Infinite Memory Transformer*. arXiv preprint arXiv:2109.00301.
    - [blog](https://mp.weixin.qq.com/s/xlIy5Zsy9UWIO8SqBVT5CA): Transformer又出新变体∞-former：无限长期记忆，任意长度上下文.
  * Longformer
    - [paper](https://arxiv.org/abs/2004.05150): Beltagy, I. , Peters, M.E. , Cohan, A. . (2020). *Longformer: The Long-Document Transformer*.
    - code: [longformer by allenai](https://github.com/allenai/longformer)
  * ReFormer
    - [paper](https://arxiv.org/pdf/2001.04451.pdf): Kitaev, N. , Kaiser, U. , & Levskaya, A. . (2020). *Reformer: the efficient Transformer*.
    - code: [reformer-pytorch by Phil Wang](https://github.com/lucidrains/reformer-pytorch)
  * RoFormer
    - [RoFormer](https://github.com/ZhuiyiTechnology/roformer): [Transformer升级之路：2、博采众长的旋转式位置编码](https://kexue.fm/archives/8265)
    - [RoFormer(v2)](https://github.com/ZhuiyiTechnology/roformer-v2): [RoFormerV2：自然语言理解的极限探索](https://kexue.fm/archives/8998)
  * Transformer-XL
    - [paper](https://arxiv.org/pdf/1901.02860.pdf): Dai, Z. , Yang, Z. , Yang, Y. , Carbonell, J. , Le, Q. V. , & Salakhutdinov, R. . (2019). *Transformer-xl: attentive language models beyond a fixed-length context*.
    - code: [tensorflow & pytorch by Zhilin Yang](https://github.com/kimiyoung/transformer-xl)
  * xFormers
    - code: https://github.com/facebookresearch/xformers
    - author: Facebook Research
    - note: hackable and optimized Transformers building blocks, supporting a composable construction.

### FLASH
  * [paper](https://arxiv.org/abs/2202.10447): Hua, W., Dai, Z., Liu, H., & Le, Q. V. (2022). *Transformer Quality in Linear Time*. arXiv preprint arXiv:2202.10447. 
  * blog
    - [FLASH：可能是近来最有意思的高效Transformer设计](https://www.spaces.ac.cn/archives/8934)
    - [谷歌Quoc Le团队新transformer：线性可扩展，训练成本仅有原版1/12](https://mp.weixin.qq.com/s/t30AKLJaOKTZVhlZgdCFnQ)

### PaLM
  * [paper](https://storage.googleapis.com/pathways-language-model/PaLM-paper.pdf): *PaLM: Scaling Language Modeling with Pathways*.
  * [paper](https://arxiv.org/abs/2203.12533): *Pathways: Asynchronous Distributed Dataflow for ML*.
  * code: [PaLM - Pytorch](https://github.com/lucidrains/PaLM-pytorch) by [Phil Wang](https://github.com/lucidrains)
  * blog
    - [Pathways Language Model (PaLM): Scaling to 540 Billion Parameters for Breakthrough Performance](https://ai.googleblog.com/2022/04/pathways-language-model-palm-scaling-to.html)
    - [6144块TPU，5400亿参数，会改bug、解读笑话，谷歌刚刚用Pathways训练了一个大模型](https://mp.weixin.qq.com/s/-Annt2JkAhgv9YxYpc7pXQ)
    - [解读谷歌Pathways架构（一）：Single-controller与Multi-controller](https://zhuanlan.zhihu.com/p/495592456)/[解读 Pathways （二）：向前一步是 OneFlow
](https://mp.weixin.qq.com/s/N99dRgFYC9zOOcGlg0Ulsw)
    - [如何评价 Google 在 2022 年 3 月公开的 Pathways 架构设计？](http://www-quic.zhihu.com/question/524596983)

### BERT
  * [paper](https://arxiv.org/pdf/1810.04805.pdf): Devlin, J. , Chang, M. W. , Lee, K. , & Toutanova, K. . (2018). *Bert: pre-training of deep bidirectional transformers for language understanding*.
  * code: 
    - [tensorflow by google-research](https://github.com/google-research/bert)
    - [pytorch by Hugging Face Report abuse](https://github.com/huggingface/pytorch-pretrained-BERT)
    - [keras by Zhao HG](https://github.com/CyberZHG/keras-bert)
    - [keras bert examples by bojone](https://github.com/bojone/bert_in_keras) and his [blog](https://spaces.ac.cn/archives/6736)
    - [bert-as-service by Han Xiao](https://github.com/hanxiao/bert-as-service)
    - [bert4keras by bojone](https://github.com/bojone/bert4keras)
    - [bert_cn_finetune by ewrfcas](https://github.com/ewrfcas/bert_cn_finetune)
    - [pretrained-models by ZhuiyiTechnology](https://github.com/ZhuiyiTechnology/pretrained-models)
  * list: [awesome-bert by Jiakui Wang](https://github.com/Jiakui/awesome-bert)
  * pre-trained models: [OpenCLaP](https://github.com/thunlp/OpenCLaP)
  * extra: 
    - [GuwenBERT](https://github.com/Ethan-yt/guwenbert)
    - [PERT](https://github.com/ymcui/PERT): [PERT：一种基于乱序语言模型的预训练模型](https://mp.weixin.qq.com/s/gx6N5QBZozxdZqSOjMKOKA)
  * blog:
    - [2023年：语言模型预训练基础知识总结：标准数据流pipleline、tokenizer的认识以及常见编码模型范式](https://mp.weixin.qq.com/s/qdJtUZlQhSYLdd4hTcZ5tw)

### BERT-WWM (Pre-Training with Whole Word Masking for BERT)
  * link: [Chinese-BERT-wwm](https://github.com/ymcui/Chinese-BERT-wwm) by Yiming Cui.

### RoBERTa
  * [paper](https://arxiv.org/pdf/1907.11692.pdf): Liu, Y. , Ott, M. , Goyal, N. , Du, J. , Joshi, M. , Chen, D. , Levy, O. , Lewis, M. , Zettlemoyer L. , Stoyanov V. . (2019). *A Robustly Optimized BERT Pretraining Approach*
  * code: 
    - [pytorch by facebook](https://github.com/pytorch/fairseq)
    - [roberta_zh by brightmart](https://github.com/brightmart/roberta_zh)

### ALBERT
  * [paper](https://openreview.net/pdf?id=H1eA7AEtvS): *ALBERT: A LITE BERT FOR SELF-SUPERVISED LEARNING OF LANGUAGE REPRESENTATIONS*
  * code: 
    - [albert by google-research](https://github.com/google-research/google-research/tree/master/albert)
    - [albert_zh by brightmart](https://github.com/brightmart/albert_zh)
    - [albert_pytorch by lonePatient](https://github.com/lonePatient/albert_pytorch)

### DeBERTa
  * paper
    - [*DeBERTa: Decoding-enhanced BERT with Disentangled Attention*](https://arxiv.org/abs/2006.03654)
    - [*DeBERTaV3: Improving DeBERTa using ELECTRA-Style Pre-Training with Gradient-Disentangled Embedding Sharing*](https://arxiv.org/abs/2111.09543)
  * code:
    - [DeBERTa](https://github.com/microsoft/DeBERTa)

### GPT
  * [paper](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf): Alec R. , Karthik N. , Tim S. , & Ilya S. . (2018). *Improving Language Understanding by Generative Pre-Training*.
  * code: [tensorflow by OpenAI](https://github.com/openai/finetune-transformer-lm)
  * blog:
    - [2023年：通俗理解文本生成的常用解码策略](https://mp.weixin.qq.com/s/sVZuEkYXQ9ZZYXJCQz7F4A)
    - [2023年：60行代码就能构建GPT！网友：比之前的教程都要清晰｜附代码](https://mp.weixin.qq.com/s/LBA4vWfU4FbhWTit-gLXkA)
      - [2023年：本科生60行代码教你手搓GPT大模型，技术介绍堪比教程](https://mp.weixin.qq.com/s/pJ3qRjS07jdhW3Vf-HRD5w) 
    - [2023年：李飞飞高徒教你从0到1构建GPT](https://mp.weixin.qq.com/s/pszo5KZgusmQpjkYCT2ihg)
    - [2023年：小破本也能炼GPT！300行代码搞定，GitHub获6k星，来自特斯拉前AI总监](https://mp.weixin.qq.com/s/2FZ-_-lL84i5cSxirO0ciA)
  
### GPT-2
  * [paper](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf): Alec R. , Jeffrey W. , Rewon C. , David L. , Dario A. , Ilya S. . (2019). *Language Models are Unsupervised Multitask Learners*.
  * code: 
    - [tensorflow by OpenAI](https://github.com/openai/gpt-2)
    - [GPT2-Chinese by Zeyao Du](https://github.com/Morizeyao/GPT2-Chinese)
    - [GPT-2-pytorch by Tae-Hwan Jung](https://github.com/graykode/gpt-2-Pytorch)
    - [gpt2-ml by Caspar ZHANG](https://github.com/imcaspar/gpt2-ml).
  * extra: [another unofficial tensorflow version by ConnorJL](https://github.com/ConnorJL/GPT2) and the author's [blog](https://medium.com/@NPCollapse/gpt2-counting-consciousness-and-the-curious-hacker-323c6639a3a8).
  * tutorial: 
    - [GPT2.0 解读 Language Models are Unsupervised Multitask Learners](https://terrifyzhao.github.io/2019/02/18/GPT2.0%E8%AE%BA%E6%96%87%E8%A7%A3%E8%AF%BB.html)
    - [The Illustrated GPT-2 (Visualizing Transformer Language Models)](https://jalammar.github.io/illustrated-gpt2/)

### GPT-3
  * [paper](https://arxiv.org/abs/2005.14165): OpenAI . (2020). *Language Models are Few-Shot Learners*.
  * code: [descriptions by OpenAI](https://github.com/openai/gpt-3).
  * blog:
    - [2023年：Why did all of the public reproduction of GPT-3 fail? In which tasks should we use GPT-3.5/ChatGPT?](https://jingfengyang.github.io/gpt)
    - [2022年：千亿参数大模型首次被撬开！Meta复刻GPT-3“背刺”OpenAI，完整模型权重及训练代码全公布](https://mp.weixin.qq.com/s/zCgXWGUlkIQaGDE14wAATw)(OPT): [code](https://github.com/facebookresearch/metaseq/tree/main/projects/OPT), [paper](https://arxiv.org/abs/2205.01068)
    - [2022年：GPT-3回答问题不靠谱？OpenAI找来人类“调教师”，终于给教明白了](https://mp.weixin.qq.com/s/vIYDGAeDx6fi6t4xaD4GIA)

### GPT-J
  * code: https://github.com/kingoflolz/mesh-transformer-jax

### minGPT
  * code: https://github.com/karpathy/minGPT

### GPT-JT
  * blog:
    - [Releasing v1 of GPT-JT powered by open-source AI](https://www.together.xyz/blog/releasing-v1-of-gpt-jt-powered-by-open-source-ai)

### CPM-Generate
  * code: https://github.com/TsinghuaAI/CPM-Generate
  * author: Tsinghua AI & BAAI
  * homepage: https://cpm.baai.ac.cn/
  * [paper](https://arxiv.org/pdf/1911.06136.pdf): Wang, X. , Gao, T. , Zhu, Z. , Liu, Z. , Li, J. , & Tang, J. . (2019). *Kepler: a unified model for knowledge embedding and pre-trained language representation*.

### ELECTRA
  * [paper](https://openreview.net/pdf?id=r1xMH1BtvB): Kevin, C. , Minh-Thang L. , Quoc V.lE. , Christopher D. Manning. . (2020). *ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators*
  * code: [tensorflow by Google](https://github.com/google-research/electra), [Chinese-ELECTRA by Yiming Cui](https://github.com/ymcui/Chinese-ELECTRA)

### ERNIE
  * [paper](https://arxiv.org/pdf/1905.07129.pdf): Zhang, Z. , Han, X. , Liu, Z. , Jiang, X. , Sun, M. , & Liu, Q. . (2019). *Ernie: enhanced language representation with informative entities*.
  * code: [pytorch by thunlp](https://github.com/thunlp/ERNIE), [paddlepaddle by Bai Du](https://github.com/PaddlePaddle/LARK/tree/develop/ERNIE)

### ERNIE 3.0
  * [paper](https://arxiv.org/pdf/2107.02137.pdf): ERNIE 3.0: LARGE-SCALE KNOWLEDGE ENHANCED PRE-TRAINING FOR LANGUAGE UNDERSTANDING AND GENERATION
  * [demo](https://wenxin.baidu.com/wenxin/ernie): ERNIE 3.0 知识增强大模型

### XLNET
  * [paper](https://arxiv.org/pdf/1906.08237.pdf): Yang, Z. , Dai, Z. , Yang Y. , Carbonell, J. , Salakhutdinov R. , V. Le, Q. . (2019). *XLNet: Generalized Autoregressive Pretraining for Language Understanding* .
  * code: https://github.com/zihangdai/xlnet
  * extra: [Chinese-XLNet by Yiming Cui](https://github.com/ymcui/Chinese-XLNet)

### Megatron-LM
  * [paper](https://arxiv.org/pdf/1909.08053v2.pdf): Shoeybi, M. , Patwary, M. , Puri, R. , Legresley, P. , Casper, J. , & Catanzaro, B. . (2019). *Megatron-lm: training multi-billion parameter language models using model parallelism*.
  * code: https://github.com/NVIDIA/Megatron-LM

### LiBai
  * link: https://github.com/Oneflow-Inc/libai
  * author: [OneFlow](https://github.com/Oneflow-Inc)
  * blog: [大模型训练之难，难于上青天？预训练易用、效率超群的「李白」模型库来了！](https://mp.weixin.qq.com/s/u1up19FQ-FoNLpZvM9dgkw)

### MASS
  * [paper](https://arxiv.org/pdf/1905.02450.pdf): Kaitao S. , Xu T. , Tao Q. , Jianfeng L. , Tie-Y. L. . (2019). *MASS: Masked Sequence to Sequence Pre-training for Language Generation*.
  
### UniLM
  * [paper](https://arxiv.org/abs/1905.03197): Dong, L. , Yang, N. , Wang, W. , Wei, F. , Liu, X. , & Wang, Y. , et al. (2019). *Unified language model pre-training for natural language understanding and generation*. NeurIPS 2019.
  * code: https://github.com/microsoft/unilm
  * note: including UniLM v1/v2, MiniLM, LayoutLM, and s2s-ft.
  * extra: [Unilm(Chinese) by YuwenTechnology](https://github.com/YunwenTechnology/Unilm), [Pretrained-Unilm-Chinese by zhongerqiandan](https://github.com/zhongerqiandan/pretrained-unilm-Chinese)

### BART
  * [paper](https://arxiv.org/pdf/1910.13461.pdf): Lewis, M. , Liu, Y. , Goyal, N. , Ghazvininejad M. , Mohamed A. , Levy O. , Stoyanov, V. , & Zettlemoyer, L. . (2019). *BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension*.
  * extra: [BARTScore](https://github.com/neulab/BARTScore)

### T5
  * [code](https://github.com/google-research/t5x/blob/main/docs/models.md)
  * [paper](https://arxiv.org/pdf/1910.10683.pdf): Raffel, C., Shazeer, N., Roberts, A., Lee, K., Narang, S., Matena, M., ... & Liu, P. J. (2020). *Exploring the limits of transfer learning with a unified text-to-text transformer*. J. Mach. Learn. Res., 21(140), 1-67.
  * [tutorial](https://huggingface.co/docs/transformers/model_doc/t5)
  * extra:
    - mT5: 
      - [paper](https://arxiv.org/pdf/2010.11934.pdf): mT5: A Massively Multilingual Pre-trained Text-to-Text Transformer.
      - [code](https://github.com/google-research/multilingual-t5)
    - ByT5:
      - [paper](https://aclanthology.org/2022.tacl-1.17/): ByT5: Towards a Token-Free Future with Pre-trained Byte-to-Byte Models.
    - TabT5: 
      - [paper](https://arxiv.org/abs/2210.09162): Table-To-Text generation and pre-training with TabT5.
    - Flan-T5: 
      - [paper](https://arxiv.org/abs/2210.11416): Scaling Instruction-Finetuned Language Models.
      - blog:
        - [2022年：谷歌Flan-T5诞生！1800种语言任务超大规模微调](https://mp.weixin.qq.com/s/AI-8YfNgs2gz2Xj-n-8RMg)
        - [2022年：30亿跑赢GPT-3的1750亿，谷歌新模型引热议，然而却把Hinton年龄搞错了](https://mp.weixin.qq.com/s/oW9tU7vJvMRxPcpkbofsMQ)

### ZEN
  * [paper](https://arxiv.org/abs/1911.00720): Diao, S. , Bai, J. , Song, Y. , Zhang, T. , & Wang, Y. . (2019). Zen: pre-training chinese text encoder enhanced by n-gram representations.
  * code: https://github.com/sinovation/ZEN

### Mengzi
  * [paper](https://arxiv.org/abs/2110.06696): Zhang, Z., Zhang, H., Chen, K., Guo, Y., Hua, J., Wang, Y., & Zhou, M. (2021). *Mengzi: Towards Lightweight yet Ingenious Pre-trained Models for Chinese*. arXiv preprint arXiv:2110.06696.
  * code: https://github.com/Langboat/Mengzi
  * author: Langboat

### NeZha_Chinese_PyTorch
  * code: https://github.com/lonePatient/NeZha_Chinese_PyTorch
  * author: lonePatient

### HUAWEI-Pretrained Language Model
  * code: https://github.com/huawei-noah/Pretrained-Language-Model
  
### UER-py
  * code: https://github.com/dbiir/UER-py
  * author: DBIIR @ RUC
  * note: open source pre-training model framework in pytorch & pre-trained model zoo.
  
### FARM
  * code: https://github.com/deepset-ai/FARM
  * author: deepset-ai
  * note: tool makes Transfer Learning with BERT & Co simple, fast and enterprise-ready.

### fastNLP
  * code: https://github.com/fastnlp/fastNLP
  * document: https://fastnlp.readthedocs.io/zh/latest/
  * author: fastnlp group ([FengZiYjun](https://fengziyjun.github.io/), fudan)
  * note: a modularized and extensible nlp framework, currently still in incubation.
  * extra: [fastHan: 基于BERT的中文NLP集成工具](https://zhuanlan.zhihu.com/p/147665538)([fastHan](https://github.com/fastnlp/fastHan))
  * news: [邱锡鹏：用fastNLP快速搭建自然语言处理模型（时间10.17）](http://kyc.henu.edu.cn/info/1077/10612.htm)

### AliceMind
  * code: https://github.com/alibaba/AliceMind/
  * author: alibaba-luofuli
  * note: ALIbaba's Collection of Encoder-decoders from MinD (Machine IntelligeNce of Damo) Lab
  * news: [官宣！达摩院开源秘藏深度语言模型体系AliceMind，NLP正在走向大工业时代](https://mp.weixin.qq.com/s/hjnDl3sxDvN2VjtC85DZQw)

### WuDao
  * github page: https://github.com/BAAI-WuDao
  * author: BAAI
  * note: 智源·悟道大规模预训练语言模型 

### Fengshenbang-LM
  * github page: https://github.com/IDEA-CCNL/Fengshenbang-LM
  * author: IDEA CCNL
  * note: 封神榜大模型是IDEA研究院认知计算与自然语言研究中心主导的大模型开源计划，包括二郎神（中文BERT）、周文王（与追一共同研发，中文LM&MLM）、余元（中文医疗LM）、闻仲（中文GPT）、燃灯（中文All2Gen）

### :dizzy_face: Why so many huge language models?
  * 2023年03月07日（5620亿参数） **PaLM-E** by 谷歌: [news](https://mp.weixin.qq.com/s/yZt3sEQPzVjnIvqXsNOnPA)
  * 2022年07月28日（1760亿参数） **BLOOM** by BigScienceLLM: [news](https://mp.weixin.qq.com/s/hNcJeX7WN8V62szIDUfOaQ), [intro](https://mp.weixin.qq.com/s/JUUJQpVFQsc2j2fiwkUX2A), [optimization](https://mp.weixin.qq.com/s/yzVqh4d6ynNROJxHycDUXg), [tutorial](https://mp.weixin.qq.com/s/4osRaxrbAGLHqO1mDz2kPQ)
  * 2022年06月13日（10亿参数） **乾元(BigBang Transformer)** by 超对称技术: [news](https://mp.weixin.qq.com/s/Ck2fDCUYlUxLrt8BM-l-SQ), [benchmark](https://github.com/ssymmetry/BBT-FinCUGE-Application)
  * 2022年05月04日（1750亿参数） **OPT-175B** by Meta AI: [paper](https://arxiv.org/pdf/2205.01068.pdf), [code](https://github.com/facebookresearch/metaseq), [model file](https://docs.google.com/forms/d/e/1FAIpQLSe4IP4N6JkCEMpCP-yY71dIUPHngVReuOmQKDEI1oHFUaVg7w/viewform), [news](https://mp.weixin.qq.com/s/qaik2nZtmptLv-51M-dmag)
  * 2022年04月05日（5400亿参数） **PaLM** by 谷歌: [news](https://mp.weixin.qq.com/s/-Annt2JkAhgv9YxYpc7pXQ), [intro](https://mp.weixin.qq.com/s/l7WOSaKnyU_Sa8DpBqUF7w)
  * 2022年02月04日（200亿参数） **GPT-NeoX** by EleutherAI: [news](https://mp.weixin.qq.com/s/yVF7nzh9HBsjUoncsvpooA)
  * 2022年01月23日（1370亿参数） **LaMDA** by 谷歌: [news](https://mp.weixin.qq.com/s/hw7CWvbm4zUY93ev7SLIgw), [news](https://mp.weixin.qq.com/s/f9JMqZ8U0f8EYTxMzyf-4Q)
  * 2021年12月09日（2800亿参数） **地鼠（Gopher）** by DeepMind: [news](https://mp.weixin.qq.com/s/z6fhsX8idpTjWNUwdeJT7A)
  * 2021年12月08日（2600亿参数） **文心（ERNIE3.0 Titan）** by 百度: [news](http://ai.baidu.com/support/news?action=detail&id=2683), [news](https://mp.weixin.qq.com/s/3hJtO_iWNcMd9PDV0pJb_A)
  * 2021年10月12日（5300亿参数） **Megatron-Turing** by 微软&英伟达: [news](https://mp.weixin.qq.com/s/F3f1Q15fyEd4L5jV41INDw)
  * 2021年09月30日（?亿参数） **神舟1.0** by QQ浏览器: [news](https://mp.weixin.qq.com/s/PODShmOo0tg9cmchNhzvtw)
  * 2021年09月28日（2457亿参数） **源1.0** by 浪潮人工智能研究院: [news](https://mp.weixin.qq.com/s/d6wVEM6dUalkITKo8Sly6A).
  * 2021年07月08日（?亿参数） **ERNIE3.0** by 百度: [paper](https://arxiv.org/pdf/2107.02137.pdf), [demo](https://wenxin.baidu.com/wenxin/ernie), [news](https://mp.weixin.qq.com/s/78rU2mC9MUXEkEI5p9bCug).
  * 2021年06月01日（17500亿参数） **悟道2.0** by 北京智源人工智能研究院: [news](https://baijiahao.baidu.com/s?id=1701360796163699362&wfr=spider&for=pc)
  * 2021年04月26日（2000亿参数） **盘古（PanGu）** by 华为: [code](https://git.openi.org.cn/PCL-Platform.Intelligence/PanGu-Alpha), [news](https://zhuanlan.zhihu.com/p/368261642).
  * 2021年04月19日（270亿参数） **PLUG** by 阿里巴巴达摩院: [demo](https://nlp.aliyun.com/portal#/BigText_chinese), [news](https://www.thepaper.cn/newsDetail_forward_12274410).
  * 2021年03月20日（?亿参数） **悟道1.0** by 北京智源人工智能研究院: [homepage](https://wudaoai.cn/home), [corpora](https://resource.wudaoai.cn/home), [news](https://zhuanlan.zhihu.com/p/358876576).
  * 2021年03月11日（26/217亿参数） **CPM-LM/CPM-KM** by 北京智源人工智能研究院: [code](https://github.com/lsq357/cpm-generate), [homepage](https://cpm.baai.ac.cn/), [paper](https://arxiv.org/abs/2012.00413).
