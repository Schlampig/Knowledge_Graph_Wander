## **Text Similarity Learning**

### Libraries
  * simhash
    - [pypi](https://pypi.org/project/simhash/)
    - [homepage](https://leons.im/posts/a-python-implementation-of-simhash-algorithm/)
    - [code](https://github.com/1e0ng/simhash)
  * difflib
  * pdf-diff
    - [code](https://github.com/serhack/pdf-diff)

### Datasets
  * [CSTS](https://github.com/zejunwang1/CSTS): 中文自然语言推理与语义相似度数据集
  * [CLUE](https://www.cluebenchmarks.com/introduce.html)文本相似度任务: [SimCLUE](https://github.com/CLUEbenchmark/SimCLUE)
  * [千言](http://www.luge.ai/)文本相似度任务
  * [CNSD:中文自然语言推理数据集](https://github.com/pluto-junzeng/CNSD)


### Blogs
  * [搜索中的深度匹配模型·上](https://zhuanlan.zhihu.com/p/113244063)，[搜索中的深度匹配模型·下](https://zhuanlan.zhihu.com/p/118183738)
  * [文本相似度/文本匹配模型归纳总结](https://blog.csdn.net/u012526436/article/details/90179466)
  * [竞赛中的文本相似性！](https://mp.weixin.qq.com/s/bn78MQ2SYNCJz5QjrQXMCg)
  * [知乎搜索排序模型的演进](https://mp.weixin.qq.com/s/QaoeztUZK2yE29tWtfjq1A)
  * [阿里飞猪搜索技术的应用与创新](https://mp.weixin.qq.com/s/UTFXn1vD548IUoh53Gm2VA)
  * [阿里粗排技术体系与最新进展](https://mp.weixin.qq.com/s/qAJWXaplQeRD5gGEsPjijQ)
  * [图谱实战 | 阿里周晓欢：如何将实体抽取从生成问题变成匹配问题？](https://mp.weixin.qq.com/s/xSl2uRE2MWm6Z0YPNEZh2g)
  * [丁香园：聊聊电商搜索的语义理解问题](https://mp.weixin.qq.com/s/I82U9NAD3KD2js04c3a0CQ)/[从文本匹配到语义相关——新闻相似度计算的一般思路](https://mp.weixin.qq.com/s/G8nQ78zUwZ01enDyDv1fnw)
  * [都是推荐系统，广告算法和推荐算法有啥区别？](https://mp.weixin.qq.com/s/AeAD97nDwZ8s3I2quI-Riw)
  * [初来乍到：帮助新用户冷启的算法技巧](https://mp.weixin.qq.com/s/LvRx8hYYMwd71atojOEEiA)
  * [KG与搜广推入门：C端广告业务的生态、展示类型、结算方式与评估指标总结](https://mp.weixin.qq.com/s/5fD4UT-waj0dGmIcYlSFIg)
  * [21个经典深度学习句间关系模型｜代码&技巧](https://mp.weixin.qq.com/s/SH2FaDZH6lw8hy3Ym8esTw), [交互模型你快跑，双塔要卷过来了](https://mp.weixin.qq.com/s/jFQWOVnDZHdvSAOKafbDqw)
  * [两万字聊对话系统](https://mp.weixin.qq.com/s/M7NkxMYVPcgTYLqp07ocuA)
  * [一文详解文本语义相似度的研究脉络和最新进展](https://mp.weixin.qq.com/s/qxYz_n_UM2lWhaz1YBhXYw)
  * [搜狐文本匹配算法大赛方案总结](https://mp.weixin.qq.com/s/emYOMZKE8jX0UaorwalPug)
  * [京东推荐算法精排技术实践](https://mp.weixin.qq.com/s/fBsDPiU1y78XLbvxrPs6xQ)
  * [综述 | 《面向推荐的大型语言模型》](https://mp.weixin.qq.com/s/TOe_b5r9zYTlqrJFWO-3OA)
  * [When RS Meets LLM：推荐系统如何从大语言模型中取长补短？面向应用视角的全面综述](https://mp.weixin.qq.com/s/SssrkpZ7OSggTHCcTkiyzQ)
  * [大模型实现生成式推荐系统](https://mp.weixin.qq.com/s/5q9I4kP086dbGFNleVY3MQ)
  * [写了个向量检索的baseline](https://mp.weixin.qq.com/s/ev73NPB_9OxR7vcN0lM1ug)
  * [无监督字面相似度CQR/CTR源码](https://mp.weixin.qq.com/s/TC8wJjlVamZEBNlqAXGSNw)

### Searching / Recommending Matching Methods
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
  * RE2
    - [paper](https://arxiv.org/abs/1908.00300): Simple and Effective Text Matching with Richer Alignment Features
    - [code](https://github.com/alibaba-edu/simple-effective-text-matching-pytorch): official
  * DSI
    - [paper](https://arxiv.org/abs/2202.06991): Transformer Memory as a Differentiable Search Index (DSI, 可微搜索索引)
    - further reading
      - [别再双塔了！谷歌提出DSI索引，检索效果吊打双塔，零样本超BM25！](https://mp.weixin.qq.com/s/l1kVnr_GMxoWgZOaCgCbXQ)
  * SDEs vs ADEs
    - [paper](https://arxiv.org/pdf/2204.07120.pdf): Exploring Dual Encoder Architectures for Question Answering
    - further reading
      - [双塔模型的最强出装，谷歌又开始玩起“老古董”了？](https://mp.weixin.qq.com/s/MF3NVyLBh0xIVCEMltzBgw)
  * Trans-Encoder
    - [paper](https://arxiv.org/abs/2109.13059): Trans-Encoder: Unsupervised sentence-pair modelling through self- and mutual-distillations
    - [code](https://github.com/amzn/trans-encoder): official 

### Searching Liburaries
  * [ann-benchmarks](http://ann-benchmarks.com/index.html): a benchmarking environment for approximate nearest neighbor algorithms search.
  * [faiss](https://faiss.ai/)
    - [autofaiss](https://github.com/criteo/autofaiss)
    - [RETRO-pytorch](https://github.com/lucidrains/RETRO-pytorch)
  * [SPTAG](https://github.com/microsoft/SPTAG)
  * [milvus](https://milvus.io/)
  * [vearch](https://github.com/vearch)
  * [jina](https://jina.ai/)
  * blog:
    - [2021年11月 笔记︱几款多模态向量检索引擎：Faiss 、milvus、Proxima、vearch、Jina等](https://zhuanlan.zhihu.com/p/364923722)
    - [2021年11月 Faiss入门及应用经验记录](https://zhuanlan.zhihu.com/p/357414033)
    - [2020年02月 Faiss入门及应用经验记录](https://zhuanlan.zhihu.com/p/107241260)
    - [Facebook AI Similarity Search (Faiss): The Missing Manual](https://www.pinecone.io/learn/faiss-tutorial/)

### Re-Ranking Methods
  * [LibRerank](https://github.com/LibRerank-Community/LibRerank): a toolkit for re-ranking algorithms, such as PRM, DLCM, GSF, miDNN, SetRank, EGRerank, Seq2Slate.

### Contrastive Methods
  * Blogs:
    - [利用Contrastive Loss（对比损失）思想设计自己的loss function](https://mp.weixin.qq.com/s/F_7HtfYL0aJd_mfpc40Ycw)
    - [在 Transformers 中使用对比搜索生成可媲美人类水平的文本](https://mp.weixin.qq.com/s/mydQLDlGUzFJuNBCIYc3CA)
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
      - [句子表示学习前沿技术分享](https://mp.weixin.qq.com/s/BnFbf6R6hGe-OSf0JIIOcw)
      - [ACL 2021｜美团提出基于对比学习的文本表示模型，效果提升8%](https://mp.weixin.qq.com/s/C4KaIXO9Lp8tlqhS3b0VCw)
  * SimCTG
    - [code](https://github.com/yxuansu/SimCTG)
    - [paper](https://arxiv.org/pdf/2202.06417.pdf)
    - further reading
      - [论文领读｜文本生成模型退化怎么办？SimCTG 告诉你答案](https://mp.weixin.qq.com/s/3Kv-GVLnNdPoJ-3f3d33-A)
      - [智能创作助手Effidit](https://effidit.qq.com/)
  * PyGCL
      - [code](https://github.com/GraphCL/PyGCL)
      - note: an open-source Graph Contrastive Learning (GCL) library for PyTorch
  * PairSCL
      - [paper](https://arxiv.org/pdf/2201.10927.pdf): Pair-Level Supervised Contrastive Learning for Natural Language Inference
      - [code](https://github.com/THU-BPM/PairSCL)
      - further reading
        - [PairSCL：句子对级别的有监督对比学习方法](https://mp.weixin.qq.com/s/6rMxHrxlTlNBX8H6Z6wUAA)
  * SNCSE
      - [paper](https://arxiv.org/pdf/2201.05979.pdf): SNCSE: Contrastive Learning for Unsupervised Sentence Embedding with Soft Negative Samples
      - [code](https://github.com/Sense-GVT/SNCSE)
      - further reading
        - [SNCSE：一种基于软负例的无监督句向量对比学习方法](https://mp.weixin.qq.com/s/73Qoth8U9MSN6RI3_CEyaQ)
  * DualCL
      - [paper](https://arxiv.org/pdf/2201.08702.pdf): Dual Contrastive Learning: Text Classification via Label-Aware Data Augmentation
      - further reading
        - [文本分类还停留在BERT？对偶比学习框架也太强了](https://mp.weixin.qq.com/s/rcQw3sNU2-wDDANkCK4C6w)
  * PICO
      - [paper](https://arxiv.org/pdf/2201.08984v2.pdf): PiCO: Contrastive Label Disambiguation for Partial Label Learning
      - [code](https://github.com/hbzju/pico)
      - further reading
        - [ICLR 2022最佳论文：基于对比消歧的偏标签学习](https://mp.weixin.qq.com/s/gJRVPitOK9ONkTRMo6-G-w)
        - [ICLR Oral｜PiCO：基于对比消歧的偏标签学习](https://zhuanlan.zhihu.com/p/463255610)(作者知乎)
        - [对比学习引领弱标签学习新SOTA，浙大新研究入选ICLR Oral](https://mp.weixin.qq.com/s/ls3Kaj7tozcMx6RkaFkrfg)
  * Open-world Contrastive Learning
      - [paper](https://arxiv.org/abs/2208.02764)

### Pre-Trained-Model-based Matching Methods
  * SimBERT
    - blog: [鱼与熊掌兼得：融合检索和生成的SimBERT模型](https://spaces.ac.cn/archives/7427)
    - [code](https://github.com/ZhuiyiTechnology/simbert)
  * ERNIE-Gram
    - [news](https://baijiahao.baidu.com/s?id=1700728264640462603&wfr=spider&for=pc): 「四大模型」革新NLP技术应用，百度文心ERNIE最新开源预训练模型
    - [paper](https://arxiv.org/abs/2010.12148): ERNIE-Gram: Pre-Training with Explicitly N-Gram Masked Language Modeling for Natural Language Understanding
  * CoSENT
    - blog: [CoSENT：比Sentence-BERT更有效的句向量方案](https://kexue.fm/archives/8847)
    - [code](https://github.com/bojone/CoSENT)([CoSENT_Pytorch](https://github.com/shawroad/CoSENT_Pytorch))

### Other Methods
  * BERT-whitening
    - [idea(blog)](https://kexue.fm/archives/8069): 你可能不需要BERT-flow：一个线性变换媲美BERT-flow
    - [experiments(blog)](https://kexue.fm/archives/8321): 无监督语义相似度哪家强？我们做了个比较全面的评测
    - [paper](https://arxiv.org/abs/2103.15316)
    - blog
      [当BERT-whitening引入超参数：总有一款适合你](https://mp.weixin.qq.com/s/Xx9unl0QL6aNO1pY_szENA)
  * Perfect Match
    - [code](https://github.com/d909b/perfect_match)
    - [paper](https://arxiv.org/abs/1810.00656)
  * PT-HCL
    - [code](https://github.com/HITSZ-HLT/PT-HCL)
    - [paper](http://www.hitsz-hlt.com/paper/Zero-Shot-Stance-Detection-via-Contrastive-Learning-WWW2022.pdf): Zero-Shot Stance Detection via Contrastive Learning.
    - further reading
      - [无关于目标or特定于目标：简单且有效的零样本立场检测对比学习方法](https://mp.weixin.qq.com/s/cT0K7txwNWiON4XsYGOrSA)
