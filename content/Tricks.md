## **Tricks to Sharpen your Models**


### Adversarial Training
  * Survey
    - blog: [一文搞懂NLP中的对抗训练FGSM/FGM/PGD/FreeAT/YOPO/FreeLB/SMART](https://zhuanlan.zhihu.com/p/103593948)
  * FGM(Fast Gradient Method)
  * PGD(Projected Gradient Descent)
  * FreeLB (Free Large-Batch)

### Attention
  * DIN & DIEN
    - blog: [DIN+DIEN，机器学习唯一指定涨点技Attention](https://mp.weixin.qq.com/s/oRoy82I_8S7uvMToMouIeQ)

### Batch Size
  * Size
    - blog: [一番实验后，有关Batch Size的玄学被打破了](https://mp.weixin.qq.com/s/eMxxpPwRYSeYy9suUSX_gQ)

### BlockShuffle

### Cross-Validation
  * kFCV(k-Fold Cross-Validation)
  * LOO(Leave-One-Out Cross-Validation)

### Data Augmentation
  * Survey
    - blog: [一篇就够！数据增强方法综述](https://mp.weixin.qq.com/s/HPItY9xXJcOZWisBGOrkSw)
  * SDE
  * EDA
  * FlipDA: [为大模型定制的数据增强方法FlipDA，屠榜六大NLU 数据集！](https://mp.weixin.qq.com/s/EcC8naSuNrTNQf0Es32YHQ)

### Distillation
  * Survey
    - blog: 
      - [BERT蒸馏完全指南｜原理/技巧/代码](https://mp.weixin.qq.com/s/tKfHq49heakvjM0EVQPgHw)
      - [深度神经网络模型蒸馏Distillation](https://zhuanlan.zhihu.com/p/71986772)
    - [awesome-knowledge-distillation](https://github.com/dkozlov/awesome-knowledge-distillation)

### Distribution
  * Survey
    - blog:
      - [新生手册：PyTorch分布式训练](https://mp.weixin.qq.com/s/dovriJnogKp1rIg6YZG2dw)
      - [PyTorch 深度剖析：并行训练的 DP 和 DDP 分别在什么情况下使用及实例](https://blog.csdn.net/God_WeiYang/article/details/125289149)

### EMA
  * [ema-pytorch](https://github.com/lucidrains/ema-pytorch): a simple way to keep track of an Exponential Moving Average (EMA) version of your pytorch model.

### Explaination
  * Survey
    - blog: [机器学习模型可解释性的详尽介绍](https://www.jiqizhixin.com/articles/2019-10-30-9)
  * SHAP(SHapley Additive exPlanations)
    - [code](https://github.com/slundberg/shap)
    - blog: [不再黑盒，机器学习解释利器：SHAP原理及实战](https://zhuanlan.zhihu.com/p/106320452)
  * LIME(Local Interpretable Model-agnostic Explanations)
    - [code](https://github.com/marcotcr/lime)
    - [paper](https://arxiv.org/abs/1602.04938)
    - blog: [能相信模型的预测吗？LIME：一种解释模型预测的方法](https://www.jiqizhixin.com/articles/2016-08-22-6)

### Feature Selection
  * Survey
    - blog: 
      - [特征选择：11 种特征选择策略总结！](https://mp.weixin.qq.com/s/BhCfPkJexi-DCLpwYwY6YA)
      - [Amazing-Feature-Engineering](https://github.com/ashishpatel26/Amazing-Feature-Engineering)（译文：[特征工程架构性好文](https://mp.weixin.qq.com/s/j1ofgcZ_Wcnn4ehbPnKM8w)）

### Finetune
  * [How to Fine-Tune BERT for Text Classification?](https://arxiv.org/abs/1905.05583?context=cs.CL)

### Label-Focused
  * Mix-up
  * Label Smoothing
  * CAN

### Lookahead

### Loss
  * Cross-Entropy Loss
    - [Things that confused me about cross-entropy](https://chris-said.io/2020/12/26/two-things-that-confused-me-about-cross-entropy/) by [Chris Said](https://chris-said.io/)

### Mask
  * Mask Ratio
    - blog: [丹琦女神又发新作，Mask 15%？我不](https://mp.weixin.qq.com/s/6bCwBy5_72Hl7-xr3hSZMA) （reserving my views :( ）

### Model-Fusion
  * Stacking
  * Ensemble

### Normalization
  * [归一化原来这么重要！深入浅出详解Transformer中的Normalization](https://mp.weixin.qq.com/s/n_twT43ZmQrkBKkAxOKa-Q)
  * [超细节的BatchNorm/BN/LayerNorm/LN知识点](https://mp.weixin.qq.com/s/rvs82W91jDPGyhcC_9PlLw)
  * [为什么Pre Norm的效果不如Post Norm？](https://mp.weixin.qq.com/s/kJnZpfYUIJRnLAUEuRQGsA)

### Parallelism
  * Survey
    - blog: [大规模模型训练tricks集锦](https://mp.weixin.qq.com/s/p99u10YOODDmZQPN0lc03w)

### Pre-Finetune
  * Survey
    - blog: [语言模型微调领域有哪些最新进展？一文详解最新趋势](https://mp.weixin.qq.com/s/XVZSAxaWM30t9rOeXYM03A) cited from [here](https://ruder.io/recent-advances-lm-fine-tuning/)

### Prior-Experience
  * Concatenate & Embedding
    - REINA([paper](https://arxiv.org/abs/2203.08773)/[code](https://github.com/microsoft/REINA)): [微软发现了一个超简单的NLP上分技巧，还发了ACL2022 ？？](https://mp.weixin.qq.com/s/koUKcfIozcl2zYeVzGj9wA)
  * Prompt
    - [哄一哄能让GPT-3准确率暴涨61%！谷歌&东京大学研究震惊四座](https://mp.weixin.qq.com/s/jDqaL6d2UCeY_8usXszkJg)

### Re-Parameter

### Soft Label

### Softmax
  * Gumbel Softmax

### Warm-up
  * Linear Warm-up

### Other Trick-and-Tips
  * link: https://github.com/oukohou/trick-and-tips
