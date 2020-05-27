## **Relation Extraction**


### Papers (Survey)
  * [paper](https://arxiv.org/pdf/1712.05191.pdf): Pawar, S. , Palshikar, G. K. , & Bhattacharyya, P. . (2017). *Relation extraction : a survey*.
  * [paper](https://arxiv.org/pdf/1705.03645.pdf): Kumar, S. . (2017). *A survey of deep learning methods for relation extraction*.
  
### Papers (Various)
  * [paper](https://arxiv.org/abs/1903.01306v1): Zhang, N. , Deng, S. , Sun, Z. , Wang, G. , Chen, X. , Zhang, W. , Chen, H. . (2019). *Long-tail Relation Extraction via Knowledge Graph Embeddings and Graph Convolution Networks*. NAACL 2019.
  * [paper](https://www.aclweb.org/anthology/D18-1247/): Han, X. , Yu, P. , Liu, Z. , Sun, M. , Li P. . (2018). *Hierarchical Relation Extraction with Coarse-to-Fine Grained Attention*. EMNLP 2018.

### Papers about Open Relation Extraction(ORE)
  * [paper](https://arxiv.org/abs/1906.03158?context=cs.CL)/[code 1](https://github.com/zhpmatrix/BERTem)/[code 2](https://github.com/plkmo/BERT-Relation-Extraction): Soares, L. B. , FitzGerald, N. , Ling, J. , Kwiatkowski T. . (2019). *Matching the Blanks: Distributional Similarity for Relation Learning*. ACL 2019.
  * [paper](https://www.researchgate.net/publication/301405129_ZORE_A_Syntax-based_System_for_Chinese_Open_Relation_Extraction): Qiu, L. , & Zhang, Y. . (2014). *ZORE: A Syntax-based System for Chinese Open Relation Extraction*. Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP).
  * [paper](https://aclweb.org/anthology/E14-4003): Yuen-Hsien Tseng, Lung-Hao Lee, Shu-Yen Lin, Bo-Shun Liao, Mei-Jun Liu, Hsin-Hsi Chen, Oren Etzioni, Anthony Fader (2014). *Chinese open relation extraction for knowledge acquisition*. Proceedings of the 14th Conference of the European Chapter of the Association for Computational Linguistics, Volume 2: Short Papers. 12-16.

### Datasets
  * [CORE](https://github.com/TJUNLP/COER): Chinese Open Entity-Relation Knowledge Base.

### OpenNRE
  * link: https://github.com/thunlp/OpenNRE
  * author: thunlp
  * [paper](https://arxiv.org/abs/1909.13078 ): Han, X. , Gao, T. , Yao, Y. , Ye, D. , Liu, Z. , & Sun, M. . (2019). *Opennre: an open and extensible toolkit for neural relation extraction*.
  * note: a tensorflow-based framework for neural relation extraction tasks (mainly for English corpus)
  * extra: various NRE-related works could be found under the lists of thunlp groups, such as [NRE](https://github.com/thunlp/NRE)(C++ approach), [JointNRE](https://github.com/thunlp/JointNRE)(Mutual Attention between graph and text), [PathNRE](https://github.com/thunlp/PathNRE)(C++ approach), [AMNRE](https://github.com/thunlp/AMNRE)(Adversarial Multi-lingual NRE), [MNRE](https://github.com/thunlp/MNRE)(Multi-Language NRE).

### Chinese_NRE
  * link: https://github.com/thunlp/Chinese_NRE
  * author: thunlp
  * note: Chinese Relation Extraction with Multi-Grained Information and External Linguistic Knowledge
  * [paper](http://nlp.csai.tsinghua.edu.cn/~lzy/publications/acl2019_nre4chinese.pdf): Ziran, L. , Ning, D. , Zhiyuan, L. ,  Hai-Tao, Z. , & Ying, S. . (2019). *Chinese Relation Extraction with Multi-Grained Information and External Linguistic Knowledge*. The 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019).

### Information-Extraction-Chinese
  * link: https://github.com/crownpku/Information-Extraction-Chinese
  * author: Guan Wang
  * note: approaches for Chinese corpus including RE_BGRU_2ATT, NER_IDCNN_CRF, and ID-CNN-CWS

### Attention-Based-BiLSTM-relation-extraction
  * link: https://github.com/SeoSangwoo/Attention-Based-BiLSTM-relation-extraction
  * author: SeoSangwoo
  * note: compare with RE_BGRU_2ATT, mainly for task8, SemEval2010
  
### Tacred-Relation
  * link: https://github.com/yuhaozhang/tacred-relation
  * author: Yuhao Zhang
  * [paper](https://nlp.stanford.edu/pubs/zhang2017tacred.pdf): Bilan, Ivan & Roth, Benjamin. (2018). *Position-aware Self-attention with Relative Positional Encodings for Slot Filling*.

### Awesome Relation Extraction
  * link: https://github.com/roomylee/awesome-relation-extraction
  * Joohong Lee

### NREPapers
  * link: https://github.com/thunlp/NREPapers
  * author: thunlp
  * note: a lists of must-read papers for neural relation extraction

### BaiDu2019 Relation Extraction Competition
  * link: http://lic2019.ccf.org.cn/kg
  * code: [kg-2019-baseline](https://github.com/bojone/kg-2019-baseline) and [kg-2019-final](https://github.com/bojone/kg-2019)(author: 苏剑林(Jianlin Su))
  * code: [IE-Bert-CNN](https://github.com/Wangpeiyi9979/IE-Bert-CNN)(author: Peiyi Wang)
  
### JointRE
  * link: https://github.com/datquocnguyen/jointRE
  * author: Dat Quoc Nguyen
  * note: a neural network model for joint extraction of named entities and relations between them, tested in CoNLL04 task.
 
### Multiple-Relations-Extraction-Only-Look-Once
  * link: https://github.com/yuanxiaosc/Multiple-Relations-Extraction-Only-Look-Once
  * author: yuanxiaosc
  * note: a method to look at the sentence only once and extract the multiple pairs of entities and their corresponding relations.
  
### [Dataset/Competition] FewRel
  * homepage: https://thunlp.github.io/fewrel.html
  * link: https://github.com/thunlp/FewRel
  * organizaer: thunlp
  * note: a Few-shot Relation classification dataset, which features 70, 000 natural language sentences expressing 100 relations annotated by crowdworkers.
  
### [Dataset/Competition] DocRED
  * homepage: https://competitions.codalab.org/competitions/23392
  * link: https://github.com/thunlp/DocRED
  * organizaer: thunlp
  * note: a document-level dataset for relation extraction tasks.

### ChineseNRE
  * link: https://github.com/buppt/ChineseNRE
  * author: buppt
  * note: bilstm + attention to do the Chinese NRE by pytorch
  
### DeepKE
  * link：https://github.com/zjunlp/deepke
  * author: zjunlp
  * note: neural relation extraction using bert
  * wiki: https://github.com/zjunlp/deepke/wiki
 
### DISTRE
  * link：https://github.com/DFKI-NLP/DISTRE
  * author: DFKI-NLP
  * [paper](https://www.aclweb.org/anthology/P19-1134): Alt, C. , Hübner M. , & Hennig, L. . (2019). *Fine-tuning Pre-Trained Transformer Language Models to Distantly Supervised Relation Extraction*. Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics.

### GraphRel
  * link: https://github.com/tsujuifu/pytorch_graph-rel
  * author: Tsu-Jui Fu
  * [paper](https://tsujuifu.github.io/pubs/acl19_graph-rel.pdf): Fu, T. , Li, P. , & Ma, W. . (2019). *GraphRel: Modeling Text as Relational Graphs for Joint Entity and Relation Extraction*.
  * note: a PyTorch implementation of GraphRel
  
### Falcon 2.0
  * link: https://github.com/SDM-TIB/Falcon2.0
  * author: SDM-TIB
  * [paper](https://arxiv.org/pdf/1912.11270v1.pdf)
  * note: a joint entity and relation linking tool over Wikidata

### Lifelong Relation Detection
  * link: https://github.com/hongwang600/Lifelong_Relation_Detection
  * author: Hong Wang
  * [paper](https://arxiv.org/abs/1903.02588)
  * note: a lifelong learning strategy to handle the FewRel challenge
  
