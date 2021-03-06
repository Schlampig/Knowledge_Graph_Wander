## **Unsupervised Representation Learning**


### References
  * [PLMpapers](https://github.com/thunlp/PLMpapers): a list of the representative work on Pre-trained Languge Model.
  * [OpenCLaP](https://github.com/thunlp/OpenCLaP): Open Chinese Language Pre-trained Model Zoo.
  * [Kashgari](https://github.com/BrikerMan/Kashgari): a Production-ready NLP Transfer learning framework for text-labeling and text-classification, includes Word2Vec, BERT, and GPT2 Language Embedding.
  * [ChineseGLUE](https://github.com/chineseGLUE/chineseGLUE): Language Understanding Evaluation benchmark for Chinese: datasets, baselines, pre-trained models,corpus and leaderboard.
  * [CLUE](https://github.com/CLUEbenchmark/CLUE): Advanced version of ChineseGLUE ([homepage](https://www.cluebenchmarks.com/)).
  * [ChineseBLUE](https://github.com/alibaba-research/ChineseBLUE): Chinese Biomedical Language Understanding Evaluation benchmark.

### Word Dictionary / Word Vector Resource
  * [OSCAR](https://oscar-corpus.com/): **O**pen **S**uper-large **C**rawled **A**ggregated co**R**pus is a huge multilingual corpus obtained by language classification and filtering of the Common Crawl corpus using the goclassy architecture.
  * [Chinese-Word-Vectors](https://github.com/Embedding/Chinese-Word-Vectors) by Embedding.
  * [Listed-company-news-crawl-and-text-analysis](https://github.com/DemonDamon/Listed-company-news-crawl-and-text-analysis) by Damon Li.
  * [funNLP 敏感词词库](https://github.com/fighting41love/funNLP) by Yang fighting41love.
  * [dict_complete 各类生活字典](https://github.com/hee0624/dict_complete) by He Chen.
  * [chinese-xinhua 中华新华字典数据库](https://github.com/pwxcoo/chinese-xinhua) by Xiance Wu.
  * [nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus) by brightmart.

### ELMo
  * [paper](http://export.arxiv.org/pdf/1812.10860): Samuel R. , Ellie P. , Edouard G. , Benjamin Van D. , Alex W. , Jan H. , Patrick X. , Raghavendra P. , R. T. M. , Roma P. , Najoung K. , Ian T. , Yinghui H. , Katherin Y. , Shuning J. , Berlin C. . (2018). *Looking for ELMo's Friends: Sentence-Level Pretraining Beyond Language Modeling*. 
  * code: [Origin by ML²AT CILVR Report](https://github.com/nyu-mll/jiant), [Tutorial by Prashant Ranjan](https://github.com/PrashantRanjan09/Elmo-Tutorial), [keras by iliaschalkidis](https://github.com/iliaschalkidis/ELMo-keras), [Multi-Language-oriented ELMo by HIT-SCIR](https://github.com/HIT-SCIR/ELMoForManyLangs), [another keras version by strongio](https://github.com/strongio/keras-elmo).

### Transformer
  * [paper](https://arxiv.org/pdf/1706.03762.pdf): Vaswani, A. , Shazeer, N. , Parmar, N. , Uszkoreit, J. , Jones, L. , & Gomez, A. N. , et al. (2017). *Attention is all you need*.
  * code: [pytorch by Yu-Hsiang Huang](https://github.com/jadore801120/attention-is-all-you-need-pytorch), [tensorflow by Kyubyong](https://github.com/Kyubyong/transformer), [another pytorch version by leviswind](https://github.com/leviswind/pytorch-transformer)
  * survey: 
    - [Long Range Arena: A Benchmark for Efficient Transformers (2020-11)](https://arxiv.org/pdf/2011.04006.pdf)
    - [Efficient Transformers: A Survey (2020-09)](https://arxiv.org/pdf/2009.06732.pdf)
    - [2021年：复旦大学邱锡鹏教授团队：Transformer最新综述](https://mp.weixin.qq.com/s/0DYOljpR9ePbutMvn8fMzQ)
    - [2021年：视觉Transformer最新综述](https://mp.weixin.qq.com/s/-4jLuBOTh9oM46r45T3efA)
  * introduction/tutorial:
    - [2021年：HuggingFace BERT源码详解：基本模型组件实现](https://mp.weixin.qq.com/s/I4KSerhkFJdnIIpaZuf08A)
    - [2021年：Huggingface BERT源码详解：应用模型与训练优化](https://mp.weixin.qq.com/s/gR2i8HvyRBUxofovQarLNw)
    - [2021年：详解Transformer](https://zhuanlan.zhihu.com/p/48508221)
    - [2021年：3W字长文带你轻松入门视觉transformer](https://zhuanlan.zhihu.com/p/308301901)
    - [How Transformers work in deep learning and NLP: an intuitive introduction](https://theaisummer.com/transformer/) by [AI SUMMER](https://theaisummer.com/)

### Transformer-XL
  * [paper](https://arxiv.org/pdf/1901.02860.pdf): Dai, Z. , Yang, Z. , Yang, Y. , Carbonell, J. , Le, Q. V. , & Salakhutdinov, R. . (2019). *Transformer-xl: attentive language models beyond a fixed-length context*.
  * code: [tensorflow & pytorch by Zhilin Yang](https://github.com/kimiyoung/transformer-xl)
  
### Longformer
  * [paper](https://arxiv.org/abs/2004.05150): Beltagy, I. , Peters, M.E. , Cohan, A. . (2020). *Longformer: The Long-Document Transformer*.
  * code: [longformer by allenai](https://github.com/allenai/longformer)
  
### Fast Transformers
  * [paper](https://arxiv.org/abs/2006.16236): Katharopoulos, A. , Vyas, A. , Pappas, N. , Fleuret, F. . (2020). *Transformers are RNNs: Fast Autoregressive Transformers with Linear Attention*.
  * code: [fast-transformers by Idiap Research Institute](https://github.com/idiap/fast-transformers)
  * website: https://linear-transformers.com/

### REFORMER
  * [paper](https://arxiv.org/pdf/2001.04451.pdf): Kitaev, N. , Kaiser, U. , & Levskaya, A. . (2020). *Reformer: the efficient Transformer*.
  * code: [reformer-pytorch by Phil Wang](https://github.com/lucidrains/reformer-pytorch)

### BERT
  * [paper](https://arxiv.org/pdf/1810.04805.pdf): Devlin, J. , Chang, M. W. , Lee, K. , & Toutanova, K. . (2018). *Bert: pre-training of deep bidirectional transformers for language understanding*.
  * code: [tensorflow by google-research](https://github.com/google-research/bert), [pytorch by Hugging Face
Report abuse](https://github.com/huggingface/pytorch-pretrained-BERT), [keras by Zhao HG](https://github.com/CyberZHG/keras-bert), [keras bert examples by bojone](https://github.com/bojone/bert_in_keras) and his [blog](https://spaces.ac.cn/archives/6736), [bert-as-service by Han Xiao](https://github.com/hanxiao/bert-as-service), [bert4keras by bojone](https://github.com/bojone/bert4keras), [bert_cn_finetune by ewrfcas](https://github.com/ewrfcas/bert_cn_finetune)
  * list: [awesome-bert by Jiakui Wang](https://github.com/Jiakui/awesome-bert)
  * pre-trained models: [OpenCLaP](https://github.com/thunlp/OpenCLaP)
  * extra: [GuwenBERT](https://github.com/Ethan-yt/guwenbert)

### BERT-WWM (Pre-Training with Whole Word Masking for BERT)
  * link: [Chinese-BERT-wwm](https://github.com/ymcui/Chinese-BERT-wwm) by Yiming Cui.

### RoBERTa
  * [paper](https://arxiv.org/pdf/1907.11692.pdf): Liu, Y. , Ott, M. , Goyal, N. , Du, J. , Joshi, M. , Chen, D. , Levy, O. , Lewis, M. , Zettlemoyer L. , Stoyanov V. . (2019). *A Robustly Optimized BERT Pretraining Approach*
  * code: [pytorch by facebook](https://github.com/pytorch/fairseq), [roberta_zh by brightmart](https://github.com/brightmart/roberta_zh)

### ALBERT
  * [paper](https://openreview.net/pdf?id=H1eA7AEtvS): *ALBERT: A LITE BERT FOR SELF-SUPERVISED LEARNING OF LANGUAGE REPRESENTATIONS*
  * code: [albert by google-research](https://github.com/google-research/google-research/tree/master/albert), [albert_zh by brightmart](https://github.com/brightmart/albert_zh), [albert_pytorch by lonePatient](https://github.com/lonePatient/albert_pytorch)

### GPT
  * [paper](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf): Alec R. , Karthik N. , Tim S. , & Ilya S. . (2018). *Improving Language Understanding by Generative Pre-Training*.
  * code: [tensorflow by OpenAI](https://github.com/openai/finetune-transformer-lm)
  
### GPT-2
  * [paper](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf): Alec R. , Jeffrey W. , Rewon C. , David L. , Dario A. , Ilya S. . (2019). *Language Models are Unsupervised Multitask Learners*.
  * code: [tensorflow by OpenAI](https://github.com/openai/gpt-2), [GPT2-Chinese by Zeyao Du](https://github.com/Morizeyao/GPT2-Chinese), [GPT-2-pytorch by Tae-Hwan Jung](https://github.com/graykode/gpt-2-Pytorch), [gpt2-ml by Caspar ZHANG](https://github.com/imcaspar/gpt2-ml).
  * extra: [another unofficial tensorflow version by ConnorJL](https://github.com/ConnorJL/GPT2) and the author's [blog](https://medium.com/@NPCollapse/gpt2-counting-consciousness-and-the-curious-hacker-323c6639a3a8).

### GPT-3
  * [paper](https://arxiv.org/abs/2005.14165): OpenAI . (2020). *Language Models are Few-Shot Learners*.
  * code: [descriptions by OpenAI](https://github.com/openai/gpt-3).

### minGPT
  * code: https://github.com/karpathy/minGPT

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

### MASS
  * [paper](https://arxiv.org/pdf/1905.02450.pdf): Kaitao S. , Xu T. , Tao Q. , Jianfeng L. , Tie-Y. L. . (2019). *MASS: Masked Sequence to Sequence Pre-training for Language Generation*.
  
### UniLM
  * [paper](https://arxiv.org/abs/1905.03197): Dong, L. , Yang, N. , Wang, W. , Wei, F. , Liu, X. , & Wang, Y. , et al. (2019). *Unified language model pre-training for natural language understanding and generation*. NeurIPS 2019.
  * code: https://github.com/microsoft/unilm
  * note: including UniLM v1/v2, MiniLM, LayoutLM, and s2s-ft.
  
### BART
  * [paper](https://arxiv.org/pdf/1910.13461.pdf): Lewis, M. , Liu, Y. , Goyal, N. , Ghazvininejad M. , Mohamed A. , Levy O. , Stoyanov, V. , & Zettlemoyer, L. . (2019). *BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension*.

### ZEN
  * [paper](https://arxiv.org/abs/1911.00720): Diao, S. , Bai, J. , Song, Y. , Zhang, T. , & Wang, Y. . (2019). Zen: pre-training chinese text encoder enhanced by n-gram representations.
  * code: https://github.com/sinovation/ZEN
  
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

### AliceMind
  * code: https://github.com/alibaba/AliceMind/
  * author: alibaba-luofuli
  * note: ALIbaba's Collection of Encoder-decoders from MinD (Machine IntelligeNce of Damo) Lab
  * news: [官宣！达摩院开源秘藏深度语言模型体系AliceMind，NLP正在走向大工业时代](https://mp.weixin.qq.com/s/hjnDl3sxDvN2VjtC85DZQw)
  
### :dizzy_face: Why so many useless fxxking huge language models?
  * CPM-Generate by 北京智源人工智能研究院: [code](https://github.com/lsq357/cpm-generate), [homepage](https://cpm.baai.ac.cn/), [paper](https://arxiv.org/abs/2012.00413).
  * 悟道 by 北京智源人工智能研究院: [homepage](https://wudaoai.cn/home), [corpora](https://resource.wudaoai.cn/home).
  * 盘古（PanGu） by 华为: [code](https://git.openi.org.cn/PCL-Platform.Intelligence/PanGu-Alpha), [news](https://zhuanlan.zhihu.com/p/368261642).
  * PLUG by 阿里巴巴达摩院: [demo](https://nlp.aliyun.com/portal#/BigText_chinese), [news](https://www.thepaper.cn/newsDetail_forward_12274410).
  * ERNIE 3.0 by 百度: [paper](https://arxiv.org/pdf/2107.02137.pdf), [demo](https://wenxin.baidu.com/wenxin/ernie), [news](https://mp.weixin.qq.com/s/78rU2mC9MUXEkEI5p9bCug).
