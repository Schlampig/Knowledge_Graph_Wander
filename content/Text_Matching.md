## **Text Similarity Learning**

### Libraries
  * simhash
    - [pypi](https://pypi.org/project/simhash/)
    - [homepage](https://leons.im/posts/a-python-implementation-of-simhash-algorithm/)
    - [code](https://github.com/1e0ng/simhash)

### Datasets
  * [CSTS](https://github.com/zejunwang1/CSTS): 中文自然语言推理与语义相似度数据集
  * [CLUE](https://www.cluebenchmarks.com/introduce.html)文本相似度任务
  * [千言](http://www.luge.ai/)文本相似度任务

### Matching Models in Searching
  * Blogs
    - [搜索中的深度匹配模型·上](https://zhuanlan.zhihu.com/p/113244063)，[搜索中的深度匹配模型·下](https://zhuanlan.zhihu.com/p/118183738)
    - [文本相似度/文本匹配模型归纳总结](https://blog.csdn.net/u012526436/article/details/90179466)
    - [知乎搜索排序模型的演进](https://mp.weixin.qq.com/s/QaoeztUZK2yE29tWtfjq1A)
  * Model Collections
    - [deep-text-matching](https://github.com/wangle1218/deep_text_matching): implementation several deep text match (text similarly) models for keras . cdssm, arc-ii,match_pyramid, mvlstm ,esim, drcn ,bimpm, bert, albert, raberta.
    - [text_matching](https://github.com/pengming617/text_matching): Models such as DSSM, ESIM, ABCNN, BiMPM.
    - [tensorflow-DSMM](https://github.com/ChenglongChen/tensorflow-DSMM): Tensorflow implementations of various Deep Semantic Matching Models (DSMM).
    - [semantic-matching](https://github.com/jastfkjg/semantic-matching): semantic matching/text matching models including MatchPyramid, MV-LSTM, ABCNN.
    - [Text-Similarity](https://github.com/pengshuang/Text-Similarity): Text-Similarity Method in Pytorch for ESIM, SiaGRU, ABCNN, BiMPM.
    - [TextSimilar](https://github.com/phychaos/TextSimilar): MatchPyramid, Siamese RNN.
  * DSSM
    - [paper](https://posenhuang.github.io/papers/cikm2013_DSSM_fullversion.pdf): Learning Deep Structured Semantic Models for Web Search using Clickthrough Data 
    - [code](https://github.com/baharefatemi/DSSM): unofficial
  * ARC-I & ARC-II
    - [paper](https://arxiv.org/pdf/1503.03244.pdf): Convolutional Neural Network Architectures for Matching Natural Language Sentences
    - [code](https://github.com/wyu-du/ARCII-for-Matching-Natural-Language-Sentences): A simple Keras implementation of ARC-II, unofficial
  * MatchPyramid
    - [paper](https://arxiv.org/abs/1602.06359): Text Matching as Image Recognition
    - code: [tensorflow ver.](https://github.com/pl8787/MatchPyramid-TensorFlow), [keras ver.](https://github.com/wyu-du/MatchPyramid-for-semantic-matching), [pytorch ver.](https://github.com/pl8787/DeepRank_PyTorch), unofficial
  * MV-LSTM
    - [paper](http://www.bigdatalab.ac.cn/~lanyanyan/papers/2016/AAAI2016_wan.pdf): A Deep Architecture for Semantic Matching with Multiple Positional Sentence Representations
    - code: [tensorflow ver.](https://github.com/coderbyr/MV-LSTM), unofficial
  * aNMM
    - [paper](https://arxiv.org/abs/1801.01641): aNMM: Ranking Short Answer Texts with Attention-Based Neural Matching Model
    - [code](https://github.com/yangliuy/aNMM-CIKM16): official
  * ABCNN
    - [paper](https://arxiv.org/abs/1512.05193): ABCNN: Attention-Based Convolutional Neural Network for Modeling Sentence Pairs
    - [code](https://github.com/yinwenpeng/Answer_Selection): official
  * HCRN
    - [paper](https://www.ijcai.org/proceedings/2018/0615.pdf): Hermitian Co-Attention Networks for Text Matching in Asymmetrical Domains
  * BiMPM
    - [paper](https://arxiv.org/pdf/1702.03814.pdf): Bilateral Multi-Perspective Matching for Natural Language Sentences
  * ESIM
    - [paper](https://arxiv.org/abs/1609.06038): Enhanced LSTM for Natural Language Inference
    - code: [tensorflow ver.](https://github.com/enningxie/ESIM), [keras ver.](https://github.com/EternalFeather/ESIM), [keras ver.2](https://github.com/Deep1994/ESIM-keras), [pytorch ver.](https://github.com/MrXJC/ESIM), [Theano ver.](https://github.com/lukecq1231/nli)
  * DIIN
    - [paper](https://arxiv.org/abs/1709.04348): NATURAL LANGUAGE INFERENCE OVER INTERACTION SPACE
    - [code](https://github.com/YichenGong/Densely-Interactive-Inference-Network): official

### Contrastive Methods
  * SimCSE
    - [paper](https://arxiv.org/abs/2104.08821): SimCSE: Simple Contrastive Learning of Sentence Embeddings
    - [code](https://github.com/princeton-nlp/SimCSE)
    - [demo](https://gradio.app/g/AK391/SimCSE)
    - [introduction blog](https://zhuanlan.zhihu.com/p/368353121)
    - further reading
      - [一文掌握《对比学习（Contrastive Learning）》要旨，详述MoCo和SimCLR算法](https://mp.weixin.qq.com/s/2a6xKL61u0M6mD1UMJjV3Q)
      - [SimCSE论文精读](https://mp.weixin.qq.com/s/DAu9jJ36s4-cs6olH9iwIQ)
    - [R-Drop](https://github.com/dropreg/R-Drop): [又是Dropout两次！这次它做到了有监督任务的SOTA](https://spaces.ac.cn/archives/8496)
  * Chinese SimCSE
    - [code](https://github.com/bojone/SimCSE)
    - further reading
      - [中文任务还是SOTA吗？我们给SimCSE补充了一些实验](https://kexue.fm/archives/8348)
  * ConSERT
    - [paper](https://arxiv.org/abs/2105.11741): ConSERT: A Contrastive Framework for Self-Supervised Sentence Representation Transfer
    - [code](https://github.com/yym6472/ConSERT)
    - further reading
      - [ACL 2021｜美团提出基于对比学习的文本表示模型，效果提升8%](https://mp.weixin.qq.com/s/C4KaIXO9Lp8tlqhS3b0VCw)
  * PyGCL
      - [code](https://github.com/GraphCL/PyGCL)
      - note: an open-source Graph Contrastive Learning (GCL) library for PyTorch

### Matching Models through Pre-trained Models
  * SimBERT
    - blog: [鱼与熊掌兼得：融合检索和生成的SimBERT模型](https://spaces.ac.cn/archives/7427)
    - [code](https://github.com/ZhuiyiTechnology/simbert)
  * ERNIE-Gram
    - [news](https://baijiahao.baidu.com/s?id=1700728264640462603&wfr=spider&for=pc): 「四大模型」革新NLP技术应用，百度文心ERNIE最新开源预训练模型
    - [paper](https://arxiv.org/abs/2010.12148): ERNIE-Gram: Pre-Training with Explicitly N-Gram Masked Language Modeling for Natural Language Understanding
  * CoSENT
    - blog: [CoSENT：比Sentence-BERT更有效的句向量方案](https://kexue.fm/archives/8847)
    - [code](https://github.com/bojone/CoSENT)

### Other Methods
  * BERT-whitening
    - [idea(blog)](https://kexue.fm/archives/8069): 你可能不需要BERT-flow：一个线性变换媲美BERT-flow
    - [experiments(blog)](https://kexue.fm/archives/8321): 无监督语义相似度哪家强？我们做了个比较全面的评测
    - [paper](https://arxiv.org/abs/2103.15316)
  * Perfect Match
    - [code](https://github.com/d909b/perfect_match)
    - [paper](https://arxiv.org/abs/1810.00656)
