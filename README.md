# Knowledge Graph and other NLP source
*Colleted by Kuyi King*
<br>
<br>

---
## **Useful Toolboxes**

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
<br>
<br>
<br>

---
## **Literatures Searching Tools**

### ACL Anthology
  * link: https://aclanthology.info/
  * note: infomation for ACL

### Awesome Chinese NLP
  * link: https://github.com/crownpku/awesome-chinese-nlp
  * note: a curated list of resources for NLP (Natural Language Processing) for Chinese.

### awesome-knowledge-graph
  * link: https://github.com/husthuke/awesome-knowledge-graph
  * author: hooke
  * note: a well-organized knowledge-graph learning source list including organizations, researchers, education vedios, conferences, competitions, etc.
<br>
<br>
<br>

---
## **Open Source Graphs**

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
<br>
<br>
<br>

---
## **Graph from Scratch**

### Paper
  * [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-11964-9_19): Wang, H., Wu, T., Qi, G., & Tong, R. (2014). On Publishing Chinese Linked Open Schema. International Semantic Web Conference.
  * [paper](https://www.researchgate.net/publication/312561715_An_automatic_approach_for_constructing_a_knowledge_base_of_symptoms_in_Chinese): Ruan, T. , Wang, M. , Sun, J. , Wang, T. , & Gao, J. . (2016). An automatic approach for constructing a knowledge base of symptoms in Chinese. 2016 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)
  * [paper](https://arxiv.org/abs/1703.05028): Wu, S. , Hsiao, L. , Cheng, X. , Hancock, B. , Rekatsinas, T. , & Levis, P. , et al. (2017). Fonduer: knowledge base construction from richly formatted data. arXiv.
  * [paper](https://arxiv.org/pdf/1205.2320.pdf): Dalamagas, T. , Bikakis, N. , Papastefanatos, G. , Stavrakas, Y. , & Hatzigeorgiou, A. G. . (2012). Publishing life science data as linked open data: the case study of miRBase. arXiv.
  * [paper](https://pure.mpg.de/rest/items/item_2157584_1/component/file_2157583/content): Ernst, P. , Siu, A. , & Weikum, G. . (2015). Knowlife: a versatile approach for constructing a large knowledge graph for biomedical sciences. BMC Bioinformatics, 16(1), 157.

### ShenMa from Ali
  * [remark](https://blog.csdn.net/yunqiinsight/article/details/79563396): 知识图谱数据构建的“硬骨头”，阿里工程师如何拿下？<br>
  * [remark](https://mp.weixin.qq.com/s/qw9i24goTsVgdk1qW6ie9A): 知识图谱数据构建的“硬骨头”，阿里工程师如何拿下？(阿里技术公众号)<br>
<br>
<br>
<br>

---
## **Rule-based Techniques**

### Paper
  * [paper](https://arxiv.org/pdf/1801.09856.pdf): Wang, H. . (2018). Renn: rule-embedded neural networks.
  * [paper](https://arxiv.org/pdf/1805.05588.pdf): Luo, B. , Feng, Y. , Wang, Z. , Huang, S. , Yan, R. , & Zhao, D. . (2018). Marrying up regular expressions with neural networks: a case study for spoken language understanding.

### Duckling
  * link: https://github.com/facebook/duckling
  * author: facebook
  * note: a Haskell library that parses text into structured data.

### Snorkel
  * link: https://github.com/HazyResearch/snorkel
  * author: HazyResearch (Stanford)
  * note: a tool using weak-supervised (which means it needs a small golden set for training process) method to extact assigned triple from context.
  * extra: the same team also supplies a various frameworks for information/relation extraction ([DeepDive](https://github.com/HazyResearch/deepdive)) and knowledge base construction([Fonduer](https://github.com/HazyResearch/fonduer)).
  * extra: [Quick Start for DeepDive](http://deepdive.stanford.edu/quickstart), [支持中文的DeepDive数据（from OpenKG）](http://www.openkg.cn/dataset/cn-deepdive), [DeepDive中文关系提取](https://blog.csdn.net/whatwho_518/article/details/79467138)

### SLING
  * link: https://github.com/google/sling
  * author: google

### KnowItAll Project
* link: https://github.com/knowitall ([OpenIE Theme](http://openie.allenai.org/))
* note: a project for information extraction such openie, relation extracion, etc.
* remark: http://projectsweb.cs.washington.edu/research/knowitall/

### Implementing a Regular Expression Engine
  * link: https://github.com/deniskyashif/regexjs/
  * author: Denis Kyashif
  * remark: https://deniskyashif.com/implementing-a-regular-expression-engine/
  
### RASA
  * link: https://github.com/rasaHQ/
  * remark: https://www.rasa.com/docs/
  * note: open source machine learning tools for developers to build, improve, and deploy text-and voice-based chatbots and assistants.
<br>
<br>
<br>

---
## **Hypernym Discovery**

### Paper
  * [paper](https://arxiv.org/pdf/1703.04178.pdf): Camachocollados, J. . (2017). Why we have switched from building full-fledged taxonomies to simply detecting hypernymy relations. arXiv.
  * [paper](http://aclweb.org/anthology/E17-1007)/[code](https://github.com/vered1986/UnsupervisedHypernymy): Shwartz, V. , Santus, E. , & Schlechtweg, D. . (2016). Hypernyms under siege: linguistically-motivated artillery for hypernymy detection. ACL 2016.
  * [paper](http://aclweb.org/anthology/D17-1123): A Short Survey on Taxonomy Learning from Text Corpora-Issues, Resources and Recent Advances, EMNLP 2017.
  * [paper](http://aclweb.org/anthology/P16-1226)/[code](https://github.com/vered1986/HypeNET): Shwartz, V. , Goldberg, Y. , & Dagan, I. . (2016). Improving hypernymy detection with an integrated path-based and distributional method. ACL 2016.
  * [paper](http://wwwusers.di.uniroma1.it/~navigli/pubs/Semeval_2015_Bordeaetal.pdf): SemEval-2015 Task 17: Taxonomy Extraction Evaluation (TExEval).
  * [paper](http://ai.stanford.edu/~rion/papers/hypernym_nips05.pdf): A Snow, R. , Jurafsky, D. , & Ng, A. Y. . (2004). Learning Syntactic Patterns for Automatic Hypernym Discovery. Advances in Neural Information Processing Systems.
<br>
<br>
<br>

---
## **Network Representation Learning / Network Embedding**

### Paper
  * [paper](https://aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12216/12004)/[code](https://github.com/xrb92/DKRL): Ruobing Xie, Zhiyuan Liu, Jia Jia1, Huanbo Luan, Maosong Sun (2016). Representation Learning of Knowledge Graphs with Entity Descriptions, Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence (AAAI-16).
  * [paper](https://arxiv.org/pdf/1805.02408.pdf)/[code](https://github.com/iieir-km/ComplEx-NNE_AER): Ding, B. , Wang, Q. , Wang, B. , & Guo, L. . (2018). Improving knowledge graph embedding using simple constraints.

### NRLPapers
  * link: https://github.com/thunlp/NRLPapers
  * author: thunlp
  * note: a lists of must-read papers for network representation learning/ network embedding

### OpenKE
  * link: https://github.com/thunlp/OpenKE
  * author: thunlp
  * note: An open-source framework for knowledge embedding with both [tensorflow](https://github.com/thunlp/TensorFlow-TransX) and [pytorch](https://github.com/thunlp/OpenKE/tree/OpenKE-PyTorch) versions, including several classic methods such as TransE, TransD, TransH, TransR, etc, and related to another light C++ project named [Fast-TransX](https://github.com/thunlp/Fast-TransX).
  * extra: various network embedding-related works could be found under the lists of thunlp groups, such as [KB2E](https://github.com/thunlp/KB2E), [OpenNE](https://github.com/thunlp/OpenNE), [Fast-TransX](https://github.com/thunlp/Fast-TransX).

### CANE
  * link: https://github.com/thunlp/CANE
  * author: thunlp
  * note: Network embedding using mutual attention to acquire contextual information of attributes (eg. the description about the node) of nodes

### SINE
  * link: https://github.com/benedekrozemberczki/SINE
  * author: Benedek Rozemberczki
  * note: Attributed network embedding from incomplete graphs by learning the attribute infomation, pytorch approach.

### DGI
  * link: https://github.com/PetarV-/DGI
  * author: Petar Veličković
  * note: a pytorch unsupervised approach for learning node representations within graph-structured data.

### StarSpace
  * link: https://github.com/facebookresearch/StarSpace
  * author: Facebook Research
  * note: a framework to learn entity embedding for various downstream works

### HARP
  * link: https://github.com/GTmac/HARP
  * author: Haochen Chen
  * note: a meta-strategy based on hierarchical representation learning to improve other network embedding methods, such as DeepWalk, LINE and Node2vec.

### NetMF
  * link: https://github.com/xptree/NetMF
  * author: Jiezhong Qiu
  * note: a model to unify DeepWalk, LINE, PTE, and node2vec through matrix factorization, python version.

### deepwalk
  * link: https://github.com/phanein/deepwalk
  * author: Bryan Perozzi
  * note: a classic method using short random walks to learn representations for nodes in graphs.

### Graph Embedding中文总结博客
  * link: http://www.jintiankansha.me/t/3gSTXhbNvB
<br>
<br>
<br>

---
## **Relation Extraction**

### OpenNRE
  * link: https://github.com/thunlp/OpenNRE
  * author: thunlp
  * note: a tensorflow-based framework for neural relation extraction tasks (mainly for English corpus)
  * extra: various NRE-related works could be found under the lists of thunlp groups, such as [NRE](https://github.com/thunlp/NRE)(C++ approach), [JointNRE](https://github.com/thunlp/JointNRE)(Mutual Attention between graph and text), [PathNRE](https://github.com/thunlp/PathNRE)(C++ approach), [AMNRE](https://github.com/thunlp/AMNRE)(Adversarial Multi-lingual NRE), [MNRE](https://github.com/thunlp/MNRE)(Multi-Language NRE).

### Information-Extraction-Chinese
  * link: https://github.com/crownpku/Information-Extraction-Chinese
  * author: Guan Wang
  * note: approaches for Chinese corpus including RE_BGRU_2ATT, NER_IDCNN_CRF, and ID-CNN-CWS

### Attention-Based-BiLSTM-relation-extraction
  * link: https://github.com/SeoSangwoo/Attention-Based-BiLSTM-relation-extraction
  * author: SeoSangwoo
  * note: compare with RE_BGRU_2ATT, mainly for task8, SemEval2010

### Awesome Relation Extraction
  * link: https://github.com/roomylee/awesome-relation-extraction
  * Joohong Lee

### NREPapers
  * link: https://github.com/thunlp/NREPapers
  * author: thunlp
  * note: a lists of must-read papers for neural relation extraction

### BaiDu2019 Relation Extraction Competition
  * link: http://lic2019.ccf.org.cn/kg
  * code: [kg-2019-baseline](https://github.com/bojone/kg-2019-baseline)(author: 苏剑林(Jianlin Su))
  
### Papers about Open Relation Extraction(ORE)
  * [paper](https://www.researchgate.net/publication/301405129_ZORE_A_Syntax-based_System_for_Chinese_Open_Relation_Extraction): Qiu, L. , & Zhang, Y. . (2014). ZORE: A Syntax-based System for Chinese Open Relation Extraction. Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP).
  * [paper](https://aclweb.org/anthology/E14-4003): Yuen-Hsien Tseng, Lung-Hao Lee, Shu-Yen Lin, Bo-Shun Liao, Mei-Jun Liu, Hsin-Hsi Chen, Oren Etzioni, Anthony Fader (2014). Chinese open relation extraction for knowledge acquisition. Proceedings of the 14th Conference of the European Chapter of the Association for Computational Linguistics, Volume 2: Short Papers. 12-16. 
<br>
<br>
<br>


---
## **Automatic Terminology Extraction**

### Introduction from ACADEMIA, Wikipedia, etc
  * [ACADEMIA](https://www.academia.edu/Documents/in/Automatic_Term_Extraction): a collection of papers about term extraction
  * [Wiki](https://en.wikipedia.org/wiki/Terminology_extraction): definition on terminology extraction
  * [remark](https://linguagreca.com/blog/2013/09/automatic-terminology-extraction/): 10 things you should know about automatic terminology extraction

### Term Extraction Tools
  * link: http://termcoord.eu/discover__trashed/free-term-extractors/term-extraction-tools/
  * author: Terminology Coordination Unit
  * note: a community including resources, articles, tools for term extraction

###
  
<br>
<br>
<br>


---
## **Open Information Extraction**

### Paper
  * [paper](https://arxiv.org/abs/1806.05599v1): Niklaus, C. , Cetto, M. , Freitas, André, & Handschuh, S. . (2018). A survey on open information extraction.
  * [paper](http://turing.cs.washington.edu/papers/etzioni-ijcai2011.pdf): Etzioni, O. , Fader, A. , Christensen, J. , Soderland, S. , & Mausam. (2012). Open Information Extraction: The Second Generation. International Joint Conference on Ijcai. DBLP.
  * [paper](https://aclweb.org/anthology/P17-2050): Saha Swarnadeep, Pal Harinder,  Mausam. (2017). Bootstrapping for Numerical Open IE. 10.18653/v1/P17-2050. 
  * [paper](http://www.docin.com/p-1065213229.html): 王莉峰. (0). 领域自适应的中文实体关系抽取研究. (Doctoral dissertation, 哈尔滨工业大学).
  * [slide](https://user.eng.umd.edu/~smiran/OpenIE.pdf):  Sina Miran. Brief Introduction and Review of Open Information Extraction (Open-IE) Systems. CS 290D Project Presentation.
  * [paper](http://jcip.cipsc.org.cn/CN/abstract/abstract1548.shtml): 赵 军, 刘 康, 周光有, 蔡 黎. 开放式文本信息抽取[J]. 中文信息学报, 2011, 25(6): 98-111.
  * [paper](http://crad.ict.ac.cn/CN/abstract/abstract2910.shtml): 秦兵, 刘安安, & 刘挺. (2015). 无指导的中文开放式实体关系抽取. 计算机研究与发展, 52(5), 1029-1035.

### Open Information Extraction (OIE) Resources
  * link: https://github.com/gkiril/oie-resources
  * author: Kiril Gashteovski
  * note: a collection of papers for oie tasks.

### ReVerb
  * link: http://reverb.cs.washington.edu/

### CoreNLP(OpenIE)
  * link: https://stanfordnlp.github.io/CoreNLP/openie.html
  * author: Stanford
<br>
<br>
<br>


---
## **Zero-Shot Learning (NLP)**

### Paper about entity/relation discovery/classificaiton
  * [paper](http://www.cis.upenn.edu/~danielkh/files/2018_zoe/2018_zero_zhot_typing.pdf)/[code](https://github.com/CogComp/zoe): Ben Zhou, Daniel Khashabi, Chen-Tse Tsai, Dan Roth (2018). Zero-Shot Open Entity Typing as Type-Compatible Grounding.
  * [paper](https://www.researchgate.net/publication/318058815_Zero-Shot_Embedding_for_Unseen_Entities_in_Knowledge_Graph)/[code](https://github.com/yzur/JointE): Zhao, Y. , Gao, S. , Gallinari, P. , & Guo, J. . (2017). Zero-shot embedding for unseen entities in knowledge graph. IEICE Transactions on Information and Systems, 100.

### Paper about QA
  * [paper](https://arxiv.org/pdf/1608.03542.pdf): Hewlett, D. , Lacoste, A. , Jones, L. , Polosukhin, I. , Fandrianto, A. , & Han, J. , et al. (2016). Wikireading: a novel large-scale language understanding task over wikipedia.
  * [paper](https://arxiv.org/pdf/1706.04115.pdf)/[link](http://nlp.cs.washington.edu/zeroshot/): Levy, O. , Seo, M. , Choi, E. , & Zettlemoyer, L. . (2017). Zero-shot relation extraction via reading comprehension.
  * [paper](https://arxiv.org/pdf/1802.06842.pdf)/[code](https://github.com/hadyelsahar/Zeroshot-QuestionGeneration): Elsahar, H. , Gravier, C. , & Laforest, F. . (2018). Zero-shot question generation from knowledge graphs for unseen predicates and entity types.
<br>
<br>
<br>


---
### Coming soon ...



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
<br>
<br>
<br>

---
## **Literatures Searching Tools**

### ACL Anthology
  * link: https://aclanthology.info/
  * note: infomation for ACL

### Awesome Chinese NLP
  * link: https://github.com/crownpku/awesome-chinese-nlp
  * note: a curated list of resources for NLP (Natural Language Processing) for Chinese.

### awesome-knowledge-graph
  * link: https://github.com/husthuke/awesome-knowledge-graph
  * author: hooke
  * note: a well-organized knowledge-graph learning source list including organizations, researchers, education vedios, conferences, competitions, etc.
<br>
<br>
<br>

---
## **Open Source Graphs**

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
<br>
<br>
<br>

---
## **Graph from Scratch**

### Paper
  * [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-11964-9_19): Wang, H., Wu, T., Qi, G., & Tong, R. (2014). On Publishing Chinese Linked Open Schema. International Semantic Web Conference.
  * [paper](https://www.researchgate.net/publication/312561715_An_automatic_approach_for_constructing_a_knowledge_base_of_symptoms_in_Chinese): Ruan, T. , Wang, M. , Sun, J. , Wang, T. , & Gao, J. . (2016). An automatic approach for constructing a knowledge base of symptoms in Chinese. 2016 IEEE International Conference on Bioinformatics and Biomedicine (BIBM)
  * [paper](https://arxiv.org/abs/1703.05028): Wu, S. , Hsiao, L. , Cheng, X. , Hancock, B. , Rekatsinas, T. , & Levis, P. , et al. (2017). Fonduer: knowledge base construction from richly formatted data. arXiv.
  * [paper](https://arxiv.org/pdf/1205.2320.pdf): Dalamagas, T. , Bikakis, N. , Papastefanatos, G. , Stavrakas, Y. , & Hatzigeorgiou, A. G. . (2012). Publishing life science data as linked open data: the case study of miRBase. arXiv.
  * [paper](https://pure.mpg.de/rest/items/item_2157584_1/component/file_2157583/content): Ernst, P. , Siu, A. , & Weikum, G. . (2015). Knowlife: a versatile approach for constructing a large knowledge graph for biomedical sciences. BMC Bioinformatics, 16(1), 157.

### ShenMa from Ali
  * [remark](https://blog.csdn.net/yunqiinsight/article/details/79563396): 知识图谱数据构建的“硬骨头”，阿里工程师如何拿下？<br>
  * [remark](https://mp.weixin.qq.com/s/qw9i24goTsVgdk1qW6ie9A): 知识图谱数据构建的“硬骨头”，阿里工程师如何拿下？(阿里技术公众号)<br>
<br>
<br>
<br>

---
## **Rule-based Techniques**

### Paper
  * [paper](https://arxiv.org/pdf/1801.09856.pdf): Wang, H. . (2018). Renn: rule-embedded neural networks.
  * [paper](https://arxiv.org/pdf/1805.05588.pdf): Luo, B. , Feng, Y. , Wang, Z. , Huang, S. , Yan, R. , & Zhao, D. . (2018). Marrying up regular expressions with neural networks: a case study for spoken language understanding.

### Duckling
  * link: https://github.com/facebook/duckling
  * author: facebook
  * note: a Haskell library that parses text into structured data.

### Snorkel
  * link: https://github.com/HazyResearch/snorkel
  * author: HazyResearch (Stanford)
  * note: a tool using weak-supervised (which means it needs a small golden set for training process) method to extact assigned triple from context.
  * extra: the same team also supplies a various frameworks for information/relation extraction ([DeepDive](https://github.com/HazyResearch/deepdive)) and knowledge base construction([Fonduer](https://github.com/HazyResearch/fonduer)).
  * extra: [Quick Start for DeepDive](http://deepdive.stanford.edu/quickstart), [支持中文的DeepDive数据（from OpenKG）](http://www.openkg.cn/dataset/cn-deepdive), [DeepDive中文关系提取](https://blog.csdn.net/whatwho_518/article/details/79467138)

### SLING
  * link: https://github.com/google/sling
  * author: google

### KnowItAll Project
* link: https://github.com/knowitall ([OpenIE Theme](http://openie.allenai.org/))
* note: a project for information extraction such openie, relation extracion, etc.
* remark: http://projectsweb.cs.washington.edu/research/knowitall/

### Implementing a Regular Expression Engine
  * link: https://github.com/deniskyashif/regexjs/
  * author: Denis Kyashif
  * remark: https://deniskyashif.com/implementing-a-regular-expression-engine/
  
### RASA
  * link: https://github.com/rasaHQ/
  * remark: https://www.rasa.com/docs/
  * note: open source machine learning tools for developers to build, improve, and deploy text-and voice-based chatbots and assistants.
<br>
<br>
<br>

---
## **Hypernym Discovery**

### Paper
  * [paper](https://arxiv.org/pdf/1703.04178.pdf): Camachocollados, J. . (2017). Why we have switched from building full-fledged taxonomies to simply detecting hypernymy relations. arXiv.
  * [paper](http://aclweb.org/anthology/E17-1007)/[code](https://github.com/vered1986/UnsupervisedHypernymy): Shwartz, V. , Santus, E. , & Schlechtweg, D. . (2016). Hypernyms under siege: linguistically-motivated artillery for hypernymy detection. ACL 2016.
  * [paper](http://aclweb.org/anthology/D17-1123): A Short Survey on Taxonomy Learning from Text Corpora-Issues, Resources and Recent Advances, EMNLP 2017.
  * [paper](http://aclweb.org/anthology/P16-1226)/[code](https://github.com/vered1986/HypeNET): Shwartz, V. , Goldberg, Y. , & Dagan, I. . (2016). Improving hypernymy detection with an integrated path-based and distributional method. ACL 2016.
  * [paper](http://wwwusers.di.uniroma1.it/~navigli/pubs/Semeval_2015_Bordeaetal.pdf): SemEval-2015 Task 17: Taxonomy Extraction Evaluation (TExEval).
  * [paper](http://ai.stanford.edu/~rion/papers/hypernym_nips05.pdf): A Snow, R. , Jurafsky, D. , & Ng, A. Y. . (2004). Learning Syntactic Patterns for Automatic Hypernym Discovery. Advances in Neural Information Processing Systems.
<br>
<br>
<br>

---
## **Network Representation Learning / Network Embedding**

### Paper
  * [paper](https://aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12216/12004)/[code](https://github.com/xrb92/DKRL): Ruobing Xie, Zhiyuan Liu, Jia Jia1, Huanbo Luan, Maosong Sun (2016). Representation Learning of Knowledge Graphs with Entity Descriptions, Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence (AAAI-16).
  * [paper](https://arxiv.org/pdf/1805.02408.pdf)/[code](https://github.com/iieir-km/ComplEx-NNE_AER): Ding, B. , Wang, Q. , Wang, B. , & Guo, L. . (2018). Improving knowledge graph embedding using simple constraints.

### NRLPapers
  * link: https://github.com/thunlp/NRLPapers
  * author: thunlp
  * note: a lists of must-read papers for network representation learning/ network embedding

### OpenKE
  * link: https://github.com/thunlp/OpenKE
  * author: thunlp
  * note: An open-source framework for knowledge embedding with both [tensorflow](https://github.com/thunlp/TensorFlow-TransX) and [pytorch](https://github.com/thunlp/OpenKE/tree/OpenKE-PyTorch) versions, including several classic methods such as TransE, TransD, TransH, TransR, etc, and related to another light C++ project named [Fast-TransX](https://github.com/thunlp/Fast-TransX).
  * extra: various network embedding-related works could be found under the lists of thunlp groups, such as [KB2E](https://github.com/thunlp/KB2E), [OpenNE](https://github.com/thunlp/OpenNE), [Fast-TransX](https://github.com/thunlp/Fast-TransX).

### CANE
  * link: https://github.com/thunlp/CANE
  * author: thunlp
  * note: Network embedding using mutual attention to acquire contextual information of attributes (eg. the description about the node) of nodes

### SINE
  * link: https://github.com/benedekrozemberczki/SINE
  * author: Benedek Rozemberczki
  * note: Attributed network embedding from incomplete graphs by learning the attribute infomation, pytorch approach.

### DGI
  * link: https://github.com/PetarV-/DGI
  * author: Petar Veličković
  * note: a pytorch unsupervised approach for learning node representations within graph-structured data.

### StarSpace
  * link: https://github.com/facebookresearch/StarSpace
  * author: Facebook Research
  * note: a framework to learn entity embedding for various downstream works

### HARP
  * link: https://github.com/GTmac/HARP
  * author: Haochen Chen
  * note: a meta-strategy based on hierarchical representation learning to improve other network embedding methods, such as DeepWalk, LINE and Node2vec.

### NetMF
  * link: https://github.com/xptree/NetMF
  * author: Jiezhong Qiu
  * note: a model to unify DeepWalk, LINE, PTE, and node2vec through matrix factorization, python version.

### deepwalk
  * link: https://github.com/phanein/deepwalk
  * author: Bryan Perozzi
  * note: a classic method using short random walks to learn representations for nodes in graphs.

### Graph Embedding中文总结博客
  * link: http://www.jintiankansha.me/t/3gSTXhbNvB
<br>
<br>
<br>

---
## **Relation Extraction**

### Papers about Open Relation Extraction(ORE)
  * [paper](https://www.researchgate.net/publication/301405129_ZORE_A_Syntax-based_System_for_Chinese_Open_Relation_Extraction): Qiu, L. , & Zhang, Y. . (2014). ZORE: A Syntax-based System for Chinese Open Relation Extraction. Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP).
  * [paper](https://aclweb.org/anthology/E14-4003): Yuen-Hsien Tseng, Lung-Hao Lee, Shu-Yen Lin, Bo-Shun Liao, Mei-Jun Liu, Hsin-Hsi Chen, Oren Etzioni, Anthony Fader (2014). Chinese open relation extraction for knowledge acquisition. Proceedings of the 14th Conference of the European Chapter of the Association for Computational Linguistics, Volume 2: Short Papers. 12-16. 

### OpenNRE
  * link: https://github.com/thunlp/OpenNRE
  * author: thunlp
  * note: a tensorflow-based framework for neural relation extraction tasks (mainly for English corpus)
  * extra: various NRE-related works could be found under the lists of thunlp groups, such as [NRE](https://github.com/thunlp/NRE)(C++ approach), [JointNRE](https://github.com/thunlp/JointNRE)(Mutual Attention between graph and text), [PathNRE](https://github.com/thunlp/PathNRE)(C++ approach), [AMNRE](https://github.com/thunlp/AMNRE)(Adversarial Multi-lingual NRE), [MNRE](https://github.com/thunlp/MNRE)(Multi-Language NRE).

### Information-Extraction-Chinese
  * link: https://github.com/crownpku/Information-Extraction-Chinese
  * author: Guan Wang
  * note: approaches for Chinese corpus including RE_BGRU_2ATT, NER_IDCNN_CRF, and ID-CNN-CWS

### Awesome Relation Extraction
  * link: https://github.com/roomylee/awesome-relation-extraction
  * Joohong Lee

### NREPapers
  * link: https://github.com/thunlp/NREPapers
  * author: thunlp
  * note: a lists of must-read papers for neural relation extraction

### BaiDu2019 Relation Extraction Competition
  * link: http://lic2019.ccf.org.cn/kg
  * code: [kg-2019-baseline](https://github.com/bojone/kg-2019-baseline)(author: 苏剑林(Jianlin Su))
  
### Tacred-Relation
  * link: https://github.com/yuhaozhang/tacred-relation
  * author: Yuhao Zhang
  * [paper](https://nlp.stanford.edu/pubs/zhang2017tacred.pdf): Bilan, Ivan & Roth, Benjamin. (2018). Position-aware Self-attention with Relative Positional Encodings for Slot Filling. arXiv.
<br>
<br>
<br>


---
## **Automatic Terminology Extraction**

### Papers
  * [paper](https://www.researchgate.net/publication/220387502_Automatic_Recognition_of_Multi-word_Terms_The_C-value_NC-value_Method): Frantzi, K. , Ananiadou, S. , & Mima, H. . (2000). Automatic recognition of multi-word terms:. the c-value/nc-value method. International Journal on Digital Libraries, 3(2), 115-130.

### Introduction from ACADEMIA, Wikipedia, etc
  * [ACADEMIA](https://www.academia.edu/Documents/in/Automatic_Term_Extraction): a collection of papers about term extraction
  * [Wiki](https://en.wikipedia.org/wiki/Terminology_extraction): definition on terminology extraction
  * [remark](https://linguagreca.com/blog/2013/09/automatic-terminology-extraction/): 10 things you should know about automatic terminology extraction

### Term Extraction Tools
  * link: http://termcoord.eu/discover__trashed/free-term-extractors/term-extraction-tools/
  * author: Terminology Coordination Unit
  * note: a community including resources, articles, tools for term extraction

### HAST
  * link: https://github.com/lixin4ever/HAST
  * author: LI XIN
  * [paper](https://arxiv.org/abs/1805.00760):Li, X. , Bing, L. , Li, P. , Lam, W. , & Yang, Z. . (2018). Aspect term extraction with history attention and selective transformation.

### C-Value-Term-Extraction
  * link: https://github.com/huanyannizu/C-Value-Term-Extraction
  * author: Xinyue Li
  * note: implementations of the c-value-based term extraction algorithm without filters.
  
### SemRe-Rank
  * link: https://github.com/ziqizhang/semrerank
  * author:
  * [paper](https://arxiv.org/abs/1711.03373): Zhang, Z. , Gao, J. , & Ciravegna, F. . (2017). Semre-rank: improving automatic term extraction by incorporating semantic relatedness with personalised pagerank. Acm Transactions on Knowledge Discovery from Data, 12(5).
<br>
<br>
<br>


---
## **Open Information Extraction**

### Paper
  * [paper](https://arxiv.org/abs/1806.05599v1): Niklaus, C. , Cetto, M. , Freitas, André, & Handschuh, S. . (2018). A survey on open information extraction.
  * [paper](http://turing.cs.washington.edu/papers/etzioni-ijcai2011.pdf): Etzioni, O. , Fader, A. , Christensen, J. , Soderland, S. , & Mausam. (2012). Open Information Extraction: The Second Generation. International Joint Conference on Ijcai. DBLP.
  * [paper](https://aclweb.org/anthology/P17-2050): Saha Swarnadeep, Pal Harinder,  Mausam. (2017). Bootstrapping for Numerical Open IE. 10.18653/v1/P17-2050. 
  * [paper](http://www.docin.com/p-1065213229.html): 王莉峰. (0). 领域自适应的中文实体关系抽取研究. (Doctoral dissertation, 哈尔滨工业大学).
  * [slide](https://user.eng.umd.edu/~smiran/OpenIE.pdf):  Sina Miran. Brief Introduction and Review of Open Information Extraction (Open-IE) Systems. CS 290D Project Presentation.
  * [paper](http://jcip.cipsc.org.cn/CN/abstract/abstract1548.shtml): 赵 军, 刘 康, 周光有, 蔡 黎. 开放式文本信息抽取[J]. 中文信息学报, 2011, 25(6): 98-111.
  * [paper](http://crad.ict.ac.cn/CN/abstract/abstract2910.shtml): 秦兵, 刘安安, & 刘挺. (2015). 无指导的中文开放式实体关系抽取. 计算机研究与发展, 52(5), 1029-1035.

### Open Information Extraction (OIE) Resources
  * link: https://github.com/gkiril/oie-resources
  * author: Kiril Gashteovski
  * note: a collection of papers for oie tasks.

### ReVerb
  * link: http://reverb.cs.washington.edu/

### CoreNLP(OpenIE)
  * link: https://stanfordnlp.github.io/CoreNLP/openie.html
  * author: Stanford
<br>
<br>
<br>


---
## **Zero-Shot Learning (NLP)**

### Paper about entity/relation discovery/classificaiton
  * [paper](http://www.cis.upenn.edu/~danielkh/files/2018_zoe/2018_zero_zhot_typing.pdf)/[code](https://github.com/CogComp/zoe): Ben Zhou, Daniel Khashabi, Chen-Tse Tsai, Dan Roth (2018). Zero-Shot Open Entity Typing as Type-Compatible Grounding.
  * [paper](https://www.researchgate.net/publication/318058815_Zero-Shot_Embedding_for_Unseen_Entities_in_Knowledge_Graph)/[code](https://github.com/yzur/JointE): Zhao, Y. , Gao, S. , Gallinari, P. , & Guo, J. . (2017). Zero-shot embedding for unseen entities in knowledge graph. IEICE Transactions on Information and Systems, 100.

### Paper about QA
  * [paper](https://arxiv.org/pdf/1608.03542.pdf): Hewlett, D. , Lacoste, A. , Jones, L. , Polosukhin, I. , Fandrianto, A. , & Han, J. , et al. (2016). Wikireading: a novel large-scale language understanding task over wikipedia.
  * [paper](https://arxiv.org/pdf/1706.04115.pdf)/[link](http://nlp.cs.washington.edu/zeroshot/): Levy, O. , Seo, M. , Choi, E. , & Zettlemoyer, L. . (2017). Zero-shot relation extraction via reading comprehension.
  * [paper](https://arxiv.org/pdf/1802.06842.pdf)/[code](https://github.com/hadyelsahar/Zeroshot-QuestionGeneration): Elsahar, H. , Gravier, C. , & Laforest, F. . (2018). Zero-shot question generation from knowledge graphs for unseen predicates and entity types.
<br>
<br>
<br>


---
### Coming soon ...


