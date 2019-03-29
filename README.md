# Knowledge Graph and other NLP Collections

link, data, code, paper, remark, note


---
## Useful Toolboxes
### Opensource Guide
  * link: https://opensource.guide/
  * note: how to make your project in github attractive.

### StateOfTheArt
  * link: https://www.stateoftheart.ai/
  * note: collections of the SOTA codes and papers of 7 main machine learning domains.

### Model Zoo
  * link: https://modelzoo.co/
  * note: collections of useful machine learning models and frameworks.

### Paper with codes
  * link: https://paperswithcode.com/
  * note: ranked lists of researches with codes in various machine learning domains, according to github stars.

### Some funny and helpful python lib.
  * link: https://www.cnblogs.com/palace/p/9889235.html


---
## About Literatures
### ACL Anthology
  * link: https://aclanthology.info/
  * note: infomation for ACL

### Awesome Chinese NLP
  * link: https://github.com/crownpku/awesome-chinese-nlp
  * note: a curated list of resources for NLP (Natural Language Processing) for Chinese.


---
## Open Source Graphs
### CN BDPedia 知识工厂
  * link: http://kw.fudan.edu.cn/
  * [paper](https://www.researchgate.net/publication/318144300_CN-DBpedia_A_Never-Ending_Chinese_Knowledge_Extraction_System): CN-DBpedia: A Never-Ending Chinese Knowledge Extraction System
  * data: http://openkg.cn/dataset/cndbpedia
  * [remark](https://mp.weixin.qq.com/s?__biz=MzI0MTI1Nzk1MA==&mid=2651675251&idx=1&sn=9031665d4b66100bf327a8797b7cd457&chksm=f2f7a6c2c5802fd4318b242aa395cf52e59a72a09026f9b91f0ddab6efbe9a1f0732e2d4c6ee#rd): CN-DBpedia介绍
  * [remark](https://www.sohu.com/a/127397409_500659): 第1期Talk实录, CN-DBpedia构建技术和思路

### Zhishi.me
  * link: http://zhishi.me/lookup
  * [paper](https://www.researchgate.net/publication/221467123_Zhishime_-_Weaving_Chinese_Linking_Open_Data): Zhishi.me - Weaving Chinese Linking Open Data
  * data: http://openkg.cn/dataset/zhishi-me

### YAGO
  * link: https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/
  * code: https://github.com/yago-naga/yago3

### WikiData
  * link: https://www.wikidata.org/wiki/Wikidata:Main_Page

### WordNet
  * link: https://wordnet.princeton.edu/download

### DBPedia
  * link: https://wiki.dbpedia.org/dbpedia-wiki
  * data: https://wiki.dbpedia.org/datasets/dbpedia-version-2016-10

### FreeBase
  * link: http://webarchive.loc.gov/all/20100713021232/http://wiki.freebase.com/wiki/Main_Page

### EventKG
  * link: http://eventkg.l3s.uni-hannover.de/index.html


---
## Graph from Scratch
### Wang, H., Wu, T., Qi, G., & Tong, R. (2014). On Publishing Chinese Linked Open Schema. International Semantic Web Conference.
  * link: https://link.springer.com/chapter/10.1007%2F978-3-319-11964-9_19

### Ruan, T. , Wang, M. , Sun, J. , Wang, T. , & Gao, J. . (2016). An automatic approach for constructing a knowledge base of symptoms in Chinese. 2016 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)
  * link: https://www.researchgate.net/publication/312561715_An_automatic_approach_for_constructing_a_knowledge_base_of_symptoms_in_Chinese

### Wu, S. , Hsiao, L. , Cheng, X. , Hancock, B. , Rekatsinas, T. , & Levis, P. , et al. (2017). Fonduer: knowledge base construction from richly formatted data. arXiv.
  * link: https://arxiv.org/abs/1703.05028

### Dalamagas, T. , Bikakis, N. , Papastefanatos, G. , Stavrakas, Y. , & Hatzigeorgiou, A. G. . (2012). Publishing life science data as linked open data: the case study of miRBase. arXiv.
  * link: https://arxiv.org/pdf/1205.2320.pdf

### Ernst, P. , Siu, A. , & Weikum, G. . (2015). Knowlife: a versatile approach for constructing a large knowledge graph for biomedical sciences. BMC Bioinformatics, 16(1), 157.
  * link: https://pure.mpg.de/rest/items/item_2157584_1/component/file_2157583/content

### ShenMa from Ali
  * [remark](https://blog.csdn.net/yunqiinsight/article/details/79563396): 知识图谱数据构建的“硬骨头”，阿里工程师如何拿下？<br>
  * [remark](https://mp.weixin.qq.com/s/qw9i24goTsVgdk1qW6ie9A): 知识图谱数据构建的“硬骨头”，阿里工程师如何拿下？(阿里技术公众号)<br>







---

---

### Zero-Shot Relation Extraction via Reading Comprehension
* paper: https://arxiv.org/abs/1706.04115
* website: http://nlp.cs.washington.edu/zeroshot/

### ReNN: Rule-embedded Neural Networks
* paper: https://arxiv.org/pdf/1801.09856.pdf
* 2018
* 规则&模型

### Marrying Up Regular Expressions with Neural Networks: A Case Study for Spoken Language Understanding
* paper: https://arxiv.org/pdf/1805.05588.pdf
* 2018
* 规则&模型

### Consensus-Driven Propagation in Massive Unlabeled Data for Face Recognition
* paper: https://arxiv.org/pdf/1809.01407.pdf
* 2018
* 利用少量标注的图片和大量无标注图片训练模型，自动为大量无标注图片打标注
* https://github.com/XiaohangZhan/cdp/

### Contextual String Embeddings for Sequence Labeling
* paper: http://blog.tvect.cc/archives/620
* 2018
* 新的BiLSTM结构做Embedding
* https://github.com/zalandoresearch/flair

### An Introductory Survey on Attention Mechanisms in NLP Problems
* paper: https://arxiv.org/pdf/1811.05544.pdf
* 2018
* NLP里使用Attention的综述

### SOSELETO: A Unified Approach to Transfer Learning and Training with Noisy Labels
* paper: https://arxiv.org/abs/1805.09622
* 2018
* 保持神经网络隐层不变，输出层以source和target而改变，且source或target的损失不同，用belevel optimizition方式共同优化两个loss，实现transfer learning。

### BERT极小数据下完成训练的开源模型
* https://github.com/Socialbird-AILab/BERT-Classification-Tutorial
* 博客：https://www.itcodemonkey.com/article/11929.html

### Noisy-Labels-Problem-Collection
* https://github.com/GuokaiLiu/Noisy-Labels-Problem-Collection
* 这一页收集了各种处理noisy label问题的开源与论文，更新到2017年
*

### A Light CNN for Deep Face Representation with Noisy Labels
* paper: https://arxiv.org/pdf/1511.02683.pdf
* 轻量级CNN处理noisy labels问题
* pytorch实现，https://github.com/AlfredXiangWu/LightCNN
* mxnet实现，https://github.com/ly-atdawn/LightCNN-mxnet

### Training deep neural-networks using a noise adaptation layer
* paper: https://openreview.net/forum?id=H12GRgcxg
* 2017 ICLR
* https://github.com/udibr/noisy_labels

### Co-teaching: Robust Training of Deep Neural Networks with Extremely Noisy Labels
* paper: https://arxiv.org/pdf/1805.07836.pdf
* 2018 NeurIPS
* pytorch实现，for 图像
* https://github.com/bhanML/Co-teaching

### EmotionNet_GammaLabVersion
* https://gitlab.com/GammaLab_AI/EmotioNet

### Residual Attention Network
* paper: https://arxiv.org/pdf/1704.06904.pdf
* pytorch代码：https://github.com/tengshaofeng/ResidualAttentionNetwork-pytorch
* pytorch代码：https://github.com/fwang91/residual-attention-network

### InsightFace
* paper: https://arxiv.org/pdf/1801.07698v1.pdf
* mxnet: https://github.com/deepinsight/insightface
* pytorch: https://github.com/TreB1eN/InsightFace_Pytorch
* mtcnn结合arcloss

### Bilinear-CNN
* paper: https://blog.csdn.net/wayne2019/article/details/78441001
* tensorflow：https://github.com/abhaydoke09/Bilinear-CNN-TensorFlow
* pytorch: https://github.com/HaoMood/bilinear-cnn
* pytorch(fast): https://github.com/HaoMood/blinear-cnn-faster-
* keras: https://github.com/tkhs3/BCNN_keras

### Spatial Transformer Networks
* paper: https://arxiv.org/pdf/1506.02025.pdf
* 把扭曲、旋转的图像尽可能复原的网络预处理层
* tensorflow: https://github.com/kevinzakka/spatial-transformer-network
* pytorch: https://github.com/fxia22/stn.pytorch
* keras: https://github.com/oarriaga/STN.keras

### Where to Focus Deep Attention based Spatially Recurrent Bilinear Networks for Fine Grained Visual Recognition
* paper: https://arxiv.org/abs/1709.05769
* 使用两股CNN（M-Net与D-Net）提取图像局部特征，经过bilinear pooling层拼接并加attention，最后过空间LSTM学习全局特征。

### 各种Attention的代码实现
* allennlp与pytorch版本
* https://github.com/pytorch/translate/tree/master/pytorch_translate/attention
* https://github.com/allenai/allennlp/tree/master/allennlp/modules/attention
* https://github.com/allenai/allennlp/tree/master/allennlp/modules/seq2seq_encoders
* https://github.com/allenai/allennlp/tree/master/allennlp/modules/matrix_attention

### attention的应用
* use two rnns, one for classification task (rnn1) and the other for predicting the glimpse location (rnn2).
* In this model, the task of predicting glimpse location is done by using soft attention over context image. 
* pytorch: https://github.com/rohithreddy024/Visual-Attention-Pytorch

### github上fine-grained问题的一些开源实现
* https://github.com/MacwinWin/Deep-Model-Transfer
* https://github.com/abhimanyudubey/confusion
* https://github.com/mengrang/DFL-CNN-tensorflow
* https://github.com/abhaydoke09/Bilinear-CNN-TensorFlow

### imbalanced-learn库
* https://imbalanced-learn.readthedocs.io/en/stable/install.html
* 这个库的SMOTE采样有一点问题，慎用
* imbalance问题的三种处理方法：1. 采样（去掉负类样本，或人造/重复采集正类样本）；2.代价敏感（对样本加权）；3.集成
* imbalance延伸的内容：1. one-shot或zero-shot，极少量样本学习（可能通过数据增强制造样本）；2.样本除杂； 3. 分层次分类

### Fine-Tune Torchvision
* https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html

### Keras预训练模型下载地址
* https://github.com/fchollet/deep-learning-models/releases

### The Impact of Imbalanced Training Data for Convolutional Neural Networks
* http://www.diva-portal.org/smash/get/diva2:811111/FULLTEXT01.pdf
* 不平衡卷积网络处理心得

### Focal Loss
* pytorch: https://github.com/clcarwin/focal_loss_pytorch
* keras: https://github.com/mkocabas/focal-loss-keras
* https://blog.csdn.net/c9Yv2cf9I06K2A9E/article/details/78920998

### 李沐：CNN图像分类Trick合集
* https://www.tinymind.cn/articles/3899

### Hourglass Network
* 沙漏型网络，可处理细粒度的分类问题
* tensorflow: https://github.com/wbenbihi/hourglasstensorlfow
* keras: https://github.com/yuanyuanli85/Stacked_Hourglass_Network_Keras

### 快速上手笔记，PyTorch模型训练实用教程
* https://mp.weixin.qq.com/s/c7QEnZ0_NTY1aUaoZ4nT7g
* https://github.com/tensor-yu/PyTorch_Tutorial

### Jointly Learning to Label Sentences and Tokens
* https://mp.weixin.qq.com/s/whWaseYWcurOLp-V8gCBvQ
* paper: https://arxiv.org/pdf/1811.05949.pdf
* 基于不同颗粒度语言联合训练的表示学习

### OpenNRE（基于tensorflow的开源关系抽取框架）
* https://github.com/thunlp/OpenNRE

### RASA自然语言推理及对话机器人开源项目
* 官网（含文档）：https://www.rasa.com/docs/
* github地址：https://github.com/rasaHQ/

### 命名体识别以及实体关系抽取介绍
* https://zhuanlan.zhihu.com/p/36175370

### 通用信息抽取（Open Information Extraction）
* 工具库ReVerb: http://reverb.cs.washington.edu/
* paper: https://arxiv.org/abs/1806.05599v1
* paper: http://turing.cs.washington.edu/papers/etzioni-ijcai2011.pdf
* slide: https://ece.umd.edu/~smiran/OpenIE.pdf
* 斯坦福工具CoreNLP：https://stanfordnlp.github.io/CoreNLP/openie.html
* 中文论文：https://wenku.baidu.com/view/428fdc722a160b4e767f5acfa1c7aa00b42a9d41.html

### 开放事件抽取(Open domain event extraction)
* paper (about datasets): http://www.lrec-conf.org/proceedings/lrec2016/pdf/837_Paper.pdf
* paper (experiments on twitter): http://ceur-ws.org/Vol-1363/paper_5.pdf
* paper (overview OpenEE from text): http://ceur-ws.org/Vol-779/derive2011_submission_1.pdf
* company (NETOWL): https://www.netowl.com/event-extraction

### KnowItAll Project
* 里面包含多种信息提取工具
* website: http://projectsweb.cs.washington.edu/research/knowitall/
* github: https://github.com/knowitall
* open ie website: http://openie.allenai.org/

### Open IE Survey
* github: https://github.com/gkiril/oie-resources#2007

### 哈工大秦兵教授主页（信息抽取/情感识别等领域）
* http://ir.hit.edu.cn/~qinb/

### 事理图谱
* 中文复合（条件事件、因果事件、顺承事件、反转事件）事理图谱构建项目：https://www.jiqizhixin.com/articles/2018-09-10-7
* 哈工大报道：https://www.jiqizhixin.com/articles/2018-09-10-7

### 刑法图谱（280万instance）
* https://github.com/liuhuanyong/CrimeKgAssitant

### DBpedia,复旦大学知识图谱
* 介绍：https://mp.weixin.qq.com/s?__biz=MzI0MTI1Nzk1MA==&mid=2651675251&idx=1&sn=9031665d4b66100bf327a8797b7cd457&chksm=f2f7a6c2c5802fd4318b242aa395cf52e59a72a09026f9b91f0ddab6efbe9a1f0732e2d4c6ee#rd
* website: http://kw.fudan.edu.cn/

### QASystemOnMedicalKG(医药领域事件/事理图谱)
* 从无到有搭建一个以疾病为中心的一定规模医药领域知识图谱，并以该知识图谱完成自动问答与分析服务。
* github: https://github.com/liuhuanyong/QASystemOnMedicalKG

### 刘烷勇自然语言项目处理主页
* https://liuhuanyong.github.io/

### 思知知识图谱机器人
* website: https://www.ownthink.com/
* github: https://github.com/ownthink/KnowledgeGraph

### 自动问题生成
* homepage: http://www.cs.cmu.edu/~ark/mheilman/questions/

### 综述 | 事件抽取及推理
* https://mp.weixin.qq.com/s/-zDMPfR1wWSV9A7HDzJlZA

### 2019年全国知识图谱与语义计算大会
* https://mp.weixin.qq.com/s/ofF3lvwtxt77rW_HUYwHHA

### SeqGAN
* paper: https://arxiv.org/pdf/1609.05473.pdf
 
### 不列颠百科全书
* download page: http://vdisk.weibo.com/s/al6dG90H0Icrm#

### 自动摘要生成
* paper: Autoencoder as Assistant Supervisor: Improving Text Representation for Chinese Social Media Text Summarization
* paper: https://arxiv.org/pdf/1805.04869.pdf
* github: https://github.com/lancopku/superAE
* potential data: 第1财经-https://www.yicai.com/news/，东方财富网-http://www.eastmoney.com/，新闻一般首段即为summary

### DeepDive
* 官网：http://deepdive.stanford.edu/quickstart
* 入门介绍：https://blog.csdn.net/cx943024256/article/details/79056726
* 中文相关：https://blog.csdn.net/whatwho_518/article/details/79467138

### 知识图谱补全
* CCKS2018南大最佳英文论文：https://blog.csdn.net/TgqDT3gGaMdkHasLZv/article/details/82026903
* CCKS2018南大最佳英文论文pdf：https://arxiv.org/pdf/1810.12582.pdf
* github代码：https://github.com/nju-websoft/DSKG

### 正则语法优化
* Implementing a Regular Expression Engine：https://deniskyashif.com/2019/02/17/implementing-a-regular-expression-engine/?from=timeline&isappinstalled=0

### Graph Embedding
* website: http://www.jintiankansha.me/t/3gSTXhbNvB


