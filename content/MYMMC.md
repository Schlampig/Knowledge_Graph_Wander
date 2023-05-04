## **Make Your Models More Clever**

---
## Knowledge into language model

### Papers
  * Zhou, C., Li, Q., Li, C., Yu, J., Liu, Y., Wang, G., ... & Sun, L. (2023). [A Comprehensive Survey on Pretrained Foundation Models: A History from BERT to ChatGPT](https://arxiv.org/pdf/2302.09419.pdf). arXiv preprint arXiv:2302.09419. Also see: [从BERT到ChatGPT，北航等9大顶尖研究机构全面综述：那些年一起追过的「预训练基础模型」](https://mp.weixin.qq.com/s/RDpOCcJKQ6h8Ns5xZyTBYw) | 新智元 2023-02-27
  * Liu, P., Yuan, W., Fu, J., Jiang, Z., Hayashi, H., & Neubig, G. (2023). [Pre-train, prompt, and predict: A systematic survey of prompting methods in natural language processing](https://arxiv.org/abs/2107.13586). ACM Computing Surveys, 55(9), 1-35. Also see [homepage](http://pretrain.nlpedia.ai/).
  * Sanh, V., Webson, A., Raffel, C., Bach, S. H., Sutawika, L., Alyafeai, Z., ... & Rush, A. M. (2021). [Multitask Prompted Training Enables Zero-Shot Task Generalization](https://arxiv.org/abs/2110.08207). arXiv preprint arXiv:2110.08207.
  * Wei, J., Bosma, M., Zhao, V. Y., Guu, K., Yu, A. W., Lester, B., ... & Le, Q. V. (2021). [Finetuned language models are zero-shot learners](https://arxiv.org/abs/2109.01652). arXiv preprint arXiv:2109.01652.
  * Schick, T. , & H Schütze. (2020). [Exploiting cloze questions for few shot text classification and natural language inference](https://arxiv.org/abs/2001.07676v3). EACL 2021.
  * Dai, D., Dong, L., Hao, Y., Sui, Z., & Wei, F. (2021). [Knowledge neurons in pretrained transformers](https://arxiv.org/abs/2104.08696). arXiv preprint arXiv:2104.08696.
  * Li, L., Xu, C., Wu, W., Zhao, Y., Zhao, X., & Tao, C. (2020). [Zero-resource knowledge-grounded dialogue generation](https://arxiv.org/abs/2008.12918). arXiv preprint arXiv:2008.12918.
  * Zhou, W., Lee, D. H., Selvam, R. K., Lee, S., Lin, B. Y., & Ren, X. (2020). [Pre-training text-to-text transformers for concept-centric common sense](https://arxiv.org/abs/2011.07956). arXiv preprint arXiv:2011.07956. 
  * Heinzerling, B., & Inui, K. (2020). [Language models as knowledge bases: On entity representations, storage capacity, and paraphrased queries](https://arxiv.org/abs/2008.09036). arXiv preprint arXiv:2008.09036. 
  * Wang, C., Liu, X., & Song, D. (2020). [Language models are open knowledge graphs](https://arxiv.org/abs/2010.11967). arXiv preprint arXiv:2010.11967.
  * He, B., Jiang, X., Xiao, J., & Liu, Q. (2020). [KgPLM: Knowledge-guided Language Model Pre-training via Generative and Discriminative Learning](https://arxiv.org/abs/2012.03551). arXiv preprint arXiv:2012.03551.
  * Cui, L., Cheng, S., Wu, Y., & Zhang, Y. (2020). [Does BERT Solve Commonsense Task via Commonsense Knowledge?](https://arxiv.org/abs/2008.03945). arXiv preprint arXiv:2008.03945.
  * Petroni, F., Rocktäschel, T., Lewis, P., Bakhtin, A., Wu, Y., Miller, A. H., & Riedel, S. (2019). [Language models as knowledge bases?](https://arxiv.org/abs/1909.01066). arXiv preprint arXiv:1909.01066.
  * Wang, X., Gao, T., Zhu, Z., Zhang, Z., Liu, Z., Li, J., & Tang, J. (2021). [KEPLER: A unified model for knowledge embedding and pre-trained language representation](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00360/98089/KEPLER-A-Unified-Model-for-Knowledge-Embedding-and). Transactions of the Association for Computational Linguistics, 9, 176-194.
  * Talmor, A., Herzig, J., Lourie, N., & Berant, J. (2018). [Commonsenseqa: A question answering challenge targeting commonsense knowledge](https://arxiv.org/abs/1811.00937). arXiv preprint arXiv:1811.00937.
  * Bosselut, A., Rashkin, H., Sap, M., Malaviya, C., Celikyilmaz, A., & Choi, Y. (2019). [Comet: Commonsense transformers for automatic knowledge graph construction](https://arxiv.org/abs/1906.05317). arXiv preprint arXiv:1906.05317.
  * Wang, C., & Jiang, H. (2018). [Explicit utilization of general knowledge in machine reading comprehension](https://arxiv.org/abs/1809.03449). arXiv preprint arXiv:1809.03449.
  * Sap, M., Le Bras, R., Allaway, E., Bhagavatula, C., Lourie, N., Rashkin, H., ... & Choi, Y. (2019, July). [Atomic: An atlas of machine commonsense for if-then reasoning](https://ojs.aaai.org/index.php/AAAI/article/view/4160). In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 33, No. 01, pp. 3027-3035).
</br>

### Blogs
  * [技术总结：KG融合预训练语言模型中的常见知识类型及代表工作浅析](https://mp.weixin.qq.com/s/XQqjqDK1fH15c3OzH3YOdg) | AINLP 2021年12月22日 转载
  * [OpenAI-Cookbook](https://github.com/openai/openai-cookbook): Examples and guides for using the OpenAI API.

---
## Prompt-Tuning

### Prompt Engineering
  * [Learning Prompt](https://learningprompt.wiki/)
    - [code](https://github.com/thinkingjimmy/Learning-Prompt)

### PromptPapers
  * link: https://github.com/thunlp/PromptPapers
  * author: THUNLP
  * note: must-read papers on prompt-based tuning for pre-trained language models.
  * blog:
    - [In-Context Learning中的示例选择及效果](https://mp.weixin.qq.com/s/SsGmta7Ethx_rSchcKUioA) |  李rumor 2023年04月24日 
    - [关于Prompt Engineering你该了解啥？OpenAI应用研究负责人帮你梳理了](https://mp.weixin.qq.com/s/010srTP8w-GV-SUXcVz94g) | 机器之心 2023年04月22日 
    - [五万字综述！Prompt Tuning：深度解读一种新的微调范式](https://mp.weixin.qq.com/s/dyKcRUKIS_HKuNQ_WZ3WCg) | AINLP 2023年04月03日
    - [一文详解Prompt学习和微调（Prompt Learning & Prompt Tuning）](https://mp.weixin.qq.com/s/upVlzJ7_mweLhspg3M0TLQ) |  PaperWeekly 2023年03月30日
    - [ChatGPT中的提示工程（Prompt Engineering）怎么做？50页最新PPT下载](https://mp.weixin.qq.com/s/Y5U4PUgIxfTI8TemMS4VBg) | 深度学习自然语言处理 2023年03月24日 
    - [ChatGPT中的提示工程(Prompt)怎么做？DAIR.AI最新《提示工程指南》，全面讲述提示技术，附书册课件视频](https://mp.weixin.qq.com/s/vfaLYPtRJH4roX1wAKno9Q) | 专知 2023年03月20日 
    - [In-Context Learning玩法大全](https://mp.weixin.qq.com/s/5sdIMCXplt61a3-IfNlPXQ) | AINLP 2023年02月22日 转载
    - [AI取代人类，可以自动生成prompt了](https://mp.weixin.qq.com/s/gpgBPeXcWL01CSoefPv9yg) | 智商掉了一地 夕小瑶的卖萌屋 2022年11月01日
    - [Prompt+对比学习，更好地学习句子表征](https://mp.weixin.qq.com/s/q4Jww1sXrOdmqQ5fyo9Cxw) | AINLP 2022年10月22日 转载
    - [NLP Prompt系列——Prompt Engineering方法详细梳理](https://mp.weixin.qq.com/s/aubMldgEBCLa6iLfifoVgw) | AINLP AINLP 2022年10月09日
    - [ACL‘22杰出论文：Prompt范式有bug！](https://mp.weixin.qq.com/s/mgXEZgXyPfW5vg_6kigwmA) | python 夕小瑶的卖萌屋 2022年07月10日 （[paper](https://aclanthology.org/2022.acl-long.556.pdf)）
    - [总结|Prompt在NER场景的应用](https://mp.weixin.qq.com/s/ExkKWV3GwbmNSU-AVseyeg) | 刘聪NLP NLP工作站 2022年05月22日
    - [Prompt learning系列之训练策略篇](https://mp.weixin.qq.com/s/qxEqO0OUbQs-sM0zbAi3Lg) | AINLP 2022年05月01日 转载
    - [NLP新范式：从Fine-tuning到Prompt，再到AdaPrompt工作赏析](https://mp.weixin.qq.com/s/JHT-dhzQu96QBFT4JlzT8g) | CReep 老刘说NLP 2022年02月28日
    - [后Prompt时代｜NLP统一范式：预训练+大规模多任务学习](https://mp.weixin.qq.com/s/EOJGIXSo7bj7oi0nqbbMlw) | AINLP 2022年02月09日 转载
    - [一文速览！多模态预训练中的 Prompt 范式](https://mp.weixin.qq.com/s/FSu5YzR3pRYEgmZdonH15Q) | 深度学习自然语言处理 2022年01月27日 转载
    - [ZeroPrompt：首个中文多任务Prompt统一模型，zeroshot性能可比微调！](https://mp.weixin.qq.com/s/Kn8KbhaWUyajjee7-klBwg) | AINLP 2022年01月24日 转载
    - [WWW2022 | OntoPrompt & KnowPrompt：知识提示的预训练微调](https://mp.weixin.qq.com/s/3ds2qiy_OmKSj40zYMUbgA) | 张宁豫叶宏彬陈想 浙大KG 2022年01月24日
    - [nlp中的prompt learning 有哪些可能的天生的缺陷？目前有什么样的方法来解决这样的缺陷？](https://www.zhihu.com/question/508658141) | 知乎问题
    - [统一对比学习框架？没错它来了。](https://mp.weixin.qq.com/s/vhWfd9Y-K9-ToZ77AtAx2Q) | rumor 李rumor 2021年12月27日
    - [Hugging Face牵头，42位作者发文，1939个prompt，大幅提升Zero-Shot性能！](https://mp.weixin.qq.com/s/CZTyZVooG1jtsnicA8SYHw) | AINLP 2021年10月20日 转载
    - [Prompt超过finetune了？Emm...](https://mp.weixin.qq.com/s/GEHRKr05LsjROTyhj9Tv_w) | rumor 李rumor 2021年10月19日
    - [清华CPT：基于预训练视觉-语言模型的跨模态Prompt-Tuning](https://mp.weixin.qq.com/s/-DHL73OfNnhB75dXSONytQ) | 李rumor 2021年10月15日 转载
    - [格局打开，带你解锁 prompt 的花式用法](https://mp.weixin.qq.com/s/lSFrdC64nDNh0Qah0zLKnA) | Severus 夕小瑶的卖萌屋 2021年9月20日
    - [一个「PPT」框架，让超大模型调参变简单：清华刘知远、黄民烈团队力作](https://mp.weixin.qq.com/s/nJpBULGGnB0Ifit8bb6SAw) | 机器之心编辑部 机器之心 2021年9月11日
    - [清华提出：用于细粒度实体分类的Prompt-Learning，并提出可训练Prompt模板](https://mp.weixin.qq.com/s/Dnqxi2sPifNCGmV8lqqkVQ) | zenRRan 深度学习自然语言处理 2021年9月9日
    - [清华大学刘知远组：文本分类任务中，将知识融入Prompt-tuning过程](https://mp.weixin.qq.com/s/AcdShY8-m5tRXgypQjmPhQ) | 苏剑林 PaperWeekly 2021年8月13日
    - [Fine-tune之后的NLP新范式：Prompt越来越火，CMU华人博士后出了篇综述文章](https://mp.weixin.qq.com/s/2eA4PBd-wr9tVyyuzJ66Bw) | 机器之心编辑部 机器之心 2021年8月3日
    - [Prompt范式的缘起｜Pattern-Exploiting Training](https://mp.weixin.qq.com/s/3XzXMZmanINcMgzySCmAXw) | rumor 李rumor 2021年8月5日
    - [近代自然语言处理技术发展的“第四范式”](https://zhuanlan.zhihu.com/p/395115779) | 刘鹏飞 知乎专栏 2021年8月1日
    - [Prompt-based Language Models：模版增强语言模型小结](https://mp.weixin.qq.com/s/w0BH7Uty3In09QIHdVEG8w) | 李泺秋 PaperWeekly 2021年6月14日

### PromptClue
  * link: https://github.com/clue-ai/PromptCLUE
  * homepage: https://www.cluebenchmarks.com/clueai.html
  * author: [ClueAI](https://github.com/clue-ai)
  * note: 全中文任务支持零样本学习模型.

### Prompt-Patterns
  * link: https://github.com/phodal/prompt-patterns
  * homepage: https://prompt.phodal.com/
  * author: Fengda Huang
  * note: Prompt编写模式：如何将思维框架赋予机器，以设计模式的形式来思考提示.

### P-Tuning（PET）
  * link: https://github.com/THUDM/P-tuning
  * author: THUDM
  * [paper](https://arxiv.org/abs/2103.10385): GPT Understands, Too
  * extra: [P-tuning](https://github.com/bojone/P-tuning) by bojone
  * blog: 
    - [P-tuning：自动构建模版，释放语言模型潜能](https://spaces.ac.cn/archives/8295) | 苏剑林 科学空间 2021年04月03日

### Instruction Tuning
  * [paper](https://arxiv.org/pdf/2109.01652v1.pdf): FINETUNED LANGUAGE MODELS ARE ZERO-SHOT LEARNERS （FLAN）.
  * extra:
    - [Awesome-instruction-tuning](https://github.com/zhilizju/Awesome-instruction-tuning): a curated list of awesome instruction tuning datasets, models, papers and repositories.
    - [awesome-instruction-learning](https://github.com/RenzeLou/awesome-instruction-learning): awesome papers on Textual Instruction learning.
    - [awesome-instruction-dataset](https://github.com/yaodongC/awesome-instruction-dataset): a collection of open-source dataset to train instruction-following LLMs (ChatGPT, LLaMA, Alpaca).
    - [paper](https://arxiv.org/abs/2304.03277): Instruction Tuning with GPT-4.
  * blog:
    - [打开模型Zero-Shot新范式：Instruction Tuning](https://mp.weixin.qq.com/s/1qsaT0AVlNjhQJR8z8PAGA) | 避暑山庄梁朝伟 PaperWeekly 2022年08月25日
    - [Instruction Tuning｜谷歌Quoc V.Le团队提出精调新范式！香过Prompt！](https://mp.weixin.qq.com/s/DcdYRzdGkF5MaL5M3yGLTw) | rumor 李rumor 2021年9月9日
    - [别再Prompt了！谷歌提出tuning新方法，强力释放GPT-3潜力！](https://mp.weixin.qq.com/s/TLdKRvG1Hdsjak8AeNG-3w) | Yimin_饭煲 夕小瑶的卖萌屋 2021年9月7日
    - [Instruction Tuning：无/少样本学习新范式](https://mp.weixin.qq.com/s/M9Z91OI330tYGozihE2wPQ) | AINLP 2023-02-19
    - [微软用GPT-4做大模型指令微调，新任务零样本性能再提升](https://mp.weixin.qq.com/s/JWn2wZeg7MJ33zTq2TOCGg) | 机器之心 2023-04-09
    - [从语言模型到ChatGPT，大模型调教全攻略](https://mp.weixin.qq.com/s/hPUVled5_uYsebKUbomdxQ) | 夕小瑶科技说 2023-04-19

### Ladder Side-Tuning（LST）
  * link: https://github.com/bojone/LST-CLUE
  * author: bojone
  * [paper](https://arxiv.org/abs/2206.06522): LST: Ladder Side-Tuning for Parameter and Memory Efficient Transfer Learning.
  * blog:
    - [Ladder Side-Tuning：预训练模型的“过墙梯”](https://spaces.ac.cn/archives/9138) | 苏剑林 科学空间 2021年06月20日

### OpenPrompt
  * link: https://github.com/thunlp/OpenPrompt
  * homepage: https://thunlp.github.io/OpenPrompt/
  * author: THUNLP
  * note: an open-source toolkit for prompt-learning.

### OpenDelta
  * link: https://github.com/thunlp/OpenDelta
  * author: THUNLP
  * note: a plug-and-play library for parameter-efficient-tuning (Delta-tuning).

### Prompt Source
  * link: https://github.com/bigscience-workshop/promptsource
  * author: BigScience Workshop
  * note: toolkit for collecting and applying prompts.

### NSP-BERT
  * [paper](https://arxiv.org/pdf/2109.03564.pdf): NSP-BERT: A Prompt-based Zero-Shot Learner Through an Original Pre-training Task —— Next Sentence Prediction
  * blog:
    - [曾被嫌弃的预训练任务NSP，做出了优秀的Zero Shot效果](https://spaces.ac.cn/archives/8671)

### CPT
  * blog:
    - [CPT：刷爆少样本REC任务！清华刘知远团队提出跨模态预训练Prompt Tuning](https://mp.weixin.qq.com/s/Q1z-1-UWHUtvfSRUfjzDsg) | 小马 我爱计算机视觉 2022年01月18日
    - [CPT模型：一种中文兼顾NLU和NLG的非平衡预训练语言模型](https://mp.weixin.qq.com/s/e7kDPRw_wfdWrKI4b8FbtA) | 刘聪工作站 NLP工作站 2022年01月12日

### KPT
  * [paper](https://arxiv.org/abs/2108.02035): Knowledgeable Prompt-tuning: Incorporating Knowledge into Prompt Verbalizer for Text Classification
  * [code](https://github.com/thunlp/KnowledgeablePromptTuning)
  * blog:
    - [ACL 2022 | KPT: 文本分类中融入知识的Prompt Verbalizer](https://mp.weixin.qq.com/s/4PEfBbRr98FjxHc2oiDPKA)

### UL2
  * [paper](https://arxiv.org/pdf/2205.05131.pdf): Unifying Language Learning Paradigms.
  * [code](https://github.com/google-research/google-research/tree/master/ul2)
  * blog:
    - [击败GPT3，刷新50个SOTA！谷歌全面统一NLP范式](https://mp.weixin.qq.com/s/oMUASBSKe3xgGVLuQz7MGg) | ZenMoore 夕小瑶的卖萌屋 2022年05月13日
    - [“统一语言学习范式”：详解50个任务达到sota的谷歌新模型](https://mp.weixin.qq.com/s/1LlezA0uhFyq0pf86iJI_Q) | LZM 数据实战派 2022年05月17日
 
 ### Selt-Instruct
   * [paper](https://arxiv.org/pdf/2212.10560v1.pdf): SELF-INSTRUCT: Aligning Language Model with Self Generated Instructions.
   * [code](https://github.com/yizhongw/self-instruct)
   * blog:
     - [面向大模型微调的instruction指令自动化生成技术：SELF-INSTRUCT指令自动化生成框架工作介绍](https://mp.weixin.qq.com/s/QW-dGXUsrHXFdIfGI68HXw) | 老刘说NLP 2023年03月23日
 
 ### Delta Tuning
   * [paper](https://www.nature.com/articles/s42256-023-00626-4): Parameter-efficient fine-tuning of large-scale pre-trained language models.
   * [code](https://github.com/thunlp/OpenDelta)
   * blog:
     - [拨动大模型的琴弦！Delta Tuning成果登上Nature子刊封面](https://mp.weixin.qq.com/s/3LUKkovbEQssC0DgHSHILg) | PaperWeekly 2023年03月24日
 
 ### Regeneration Learning
   * [paper](https://arxiv.org/abs/2301.08846): Regeneration Learning: A Learning Paradigm for Data Generation.
   * [homepage](https://ai-creation.github.io/)
   * blog:
     - [微软研究员联合Yoshua Bengio推出AIGC数据生成学习范式Regeneration Learning](https://mp.weixin.qq.com/s/CdshbjsSlVQmRXFqUnFFSA) | 微软亚洲研究院 2023-04-10
 
</br>

---
## Where will AI go?

### JEPA-pytorch
  * link: https://github.com/lucidrains/JEPA-pytorch
  * author: lucidrains(Phil Wang)
  * [paper](https://openreview.net/forum?id=BZ5a1r-kVsf): A Path Towards Autonomous Machine Intelligence
  * note: implementation of JEPA, Yann LeCun's vision of how AGI would be built, in pytorch.

### News
  - [2022年02月04日：盘古α, Gopher, 派大星, GLIDE...18个中美大厂去年搞的大模型工作我们试着总结回顾了一下](https://mp.weixin.qq.com/s/KuFfFAhXz5O5EsF2A_aBGQ)
  - [2022年02月15日：关于大模型的发展趋势，我突然有个细思极恐的脑洞](https://mp.weixin.qq.com/s/dlFJYyCsip5fGlY88Bd7DA):sweat_smile:
  - [2022年04月14日：百位学者署名的大模型综述研究被质疑「抄袭」，智源研究院官方发布致歉信](https://mp.weixin.qq.com/s/MbmJPaZYKYNqH1z0zzvsqQ)
    - [2022年07月18日：智源“抄袭门”最新通报：2处抄袭4处引用不规范，相关责任人均已主动离职](https://mp.weixin.qq.com/s/9gnQ0RYCWLwM_h_fre91uA)
  - [2022年05月01日：大型语言模型能真正理解人类语言吗？](https://mp.weixin.qq.com/s/EHmPvcS5M5NwIxN6IQ08YQ)
  - [2022年05月01日：斯坦福教授曼宁AAAS特刊发文：大模型已成突破，展望通用人工智能](https://mp.weixin.qq.com/s/PLKDezmaTn8dEkhcES1g2Q)
  - [2022年06月09日：Geoffrey Hinton 最新访谈：不出五年，我们就会破解大脑的运作机制，但不是通过反向传播](https://mp.weixin.qq.com/s/KAfDxOzEfb55_ABK4nGJgw)
    - [2022年06月09日：Gary Marcus公开喊话Hinton、马斯克：深度学习就是撞墙了，我赌十万美金](https://mp.weixin.qq.com/s/bqPV_BgHtPYa5ST_TVC3ug)
    - [2022年06月17日：终于，Yann LeCun发文驳斥Gary Marcus：别把一时的困难当撞墙](https://mp.weixin.qq.com/s/Ty8y6llpantMYz8I3T-S_A)
    - [2022年06月28日：思考总结10年，图灵奖得主Yann LeCun指明下一代AI方向：自主机器智能](https://mp.weixin.qq.com/s/JUlhu95uFsY0c5WjJOJl3g)
    - [2022年07月08日：LeCun论文被指「洗稿」？ LSTM之父发文怒怼：抄我的还标原创](https://mp.weixin.qq.com/s/naCveSEguaUdjkZ5u0rbSg)
    - [2022年08月01日：Yann LeCun开怼谷歌研究：目标传播早就有了，你们创新在哪里？](https://mp.weixin.qq.com/s/8Orad1pPsnryj2U9wjgDCA)
    - [2022年08月13日：人工智能有大事发生，LeCun也转型了](https://mp.weixin.qq.com/s/yL7vaQfTFOEsXF-DZOIUzA)
    - [2022年09月24日：Gary Marcus：文本生成图像系统理解不了世界，离 AGI 还差得远](https://mp.weixin.qq.com/s/DfcjZJCw4xyg4SLBPBSOsA)
    - [2022年09月26日：LeCun再炮轰Marcus： 他是心理学家，不是搞AI的](https://mp.weixin.qq.com/s/QTjZSZxrn3Z_pbiLiGXcPQ)
    - [2022年10月14日：Yann LeCun：大模型方向错了，智力无法接近人类](https://mp.weixin.qq.com/s/HolU4FQSra_DpZtINic98Q)
    - [2022年10月17日：Gary Marcus又来「整顿」AI圈：LeCun不可信，Nature审稿人没用脑子](https://mp.weixin.qq.com/s/N72mogWNkqogDnk21H9IkA)
  - [2022年06月12日：谷歌研究员走火入魔事件曝光：认为AI已具备人格，被罚带薪休假，聊天记录让网友San值狂掉](https://mp.weixin.qq.com/s/FpXW9AyharQMrLVf6v69IA)
    - [2022年06月14日：谷歌AI具有意识？LaMDA像个聪明孩子？专家：胡扯](https://mp.weixin.qq.com/s/kHhI3bL29yygDdBP8ELeuw)
    - [2022年06月01日：研究者意外发现DALL-E 2在用自创语言生成图像：全文黑话，人类都看不懂](https://mp.weixin.qq.com/s/IJBMPfKHy1d1KnfV4vt-oQ)
    - [2022年07月01日：人工智能学会数学推理了，考试成绩比CS博士还高](https://mp.weixin.qq.com/s/7wqEkqgFGpVlQiJ_hnPCyw)
    - [2022年07月15日：语言AI原来知道自己的回答是否正确！伯克利等高校新研究火了，网友：危险危险危险](https://mp.weixin.qq.com/s/25UXC2OHt43qla8mZwEESg)
  - [2022年06月13日：又一篇超百名作者的 AI 论文问世！442位作者耗时两年发布大模型新基准 BIG-bench……](https://mp.weixin.qq.com/s/N_XYh04y92psPk9h1ISxzQ)
  - [2022年06月29日：李飞飞划重点的「具身智能」，走到哪一步了？](https://mp.weixin.qq.com/s/fQgIHv78Q1AG5bF6fQYbGg)
    - [2022年07月14日：下一站，Embodied AI](https://mp.weixin.qq.com/s/iePasFauFjAziXU8u0PcTg)
  - [2022年07月08日：人工智能是不是走错了方向？](https://mp.weixin.qq.com/s/6kVjsiAGtfVHr6L2b3tmZA) :smile:
  - [2022年07月12日：DeepMind最新研究：让 AI 像婴儿一样思考](https://mp.weixin.qq.com/s/dBUrGlIWb3Xtf8z1F9nf9w)
  - [2022年07月18日：马毅沈向洋曹颖最新 AI 综述火了！耗时 3 月打造，网友：必读论文](https://mp.weixin.qq.com/s/xQZ8Lp_lklzcJjqPIuEmQg)
  - [2022年08月02日：DeepMind 首席科学家 Oriol Vinyals 最新访谈：通用 AI 的未来是强交互式元学习](https://mp.weixin.qq.com/s/srWdDW461vQYD735Gi8Tbg)
    - [2022年08月15日：DeepMind创始人Demis Hassabis：AI 的强大，超乎我们的想象](https://mp.weixin.qq.com/s/D5DzLqlizHaURNHOqs5GnQ)
  - [2022年09月27日：【前沿报告】Richard Sutton 直言卷积反向传播已经落后，AI 突破要有新思路：持续反向传播](https://mp.weixin.qq.com/s/P3gArNbpBwVlAAoh0qIOMw)
  - [2022年10月22日：Bengio、LeCun 等人联名上书，呼吁美国投资神经AI，攻破「具身图灵测试」](https://mp.weixin.qq.com/s/FrhFb5RxGGDi2DC6UJMvpw)
  - [2022年12月02日：近万人围观Hinton最新演讲：前向-前向神经网络训练算法，论文已公开](https://mp.weixin.qq.com/s/oxS57R8lZGAQga2AbvYnRw)
  - [2023年01月19日：超详超硬Jeff Dean万字总结火热出炉！图解谷歌2022年AIGC、LLM、CV三大领域成就](https://mp.weixin.qq.com/s/mYhSFtZZMRv5dDMnYcruJg)
  - [2023年01月27日：Transformer模仿大脑，在预测大脑成像上超越42个模型，还能够模拟感官与大脑之间的传输](https://mp.weixin.qq.com/s/O-gCHzTL4lAJ8bQDZtzPDQ)
  - [2023年02月26日：ChatGPT掀智力革命！OpenAI发布AGI路线图，最终通向超级智能世界](https://mp.weixin.qq.com/s/6Lyr2nVG5mxy1UBnOC5DAw)
    - [2023年02月27日：ChatGPT之后何去何从？LeCun新作：全面综述下一代「增强语言模型」](https://mp.weixin.qq.com/s/1Qz8D3ZKkS4jdbNiJ7MWFg)
    - [2023年03月03日：LeCun：ChatGPT无法实现通用人工智能，但ALM技术路线可以！](https://mp.weixin.qq.com/s/MEdl3zmiYJU1iFsTXmibng)
    - [2023年03月16日：深度剖析：ChatGPT 及其继任者会成为通用人工智能吗？](https://mp.weixin.qq.com/s/iOVHUIX8gLjAzNGWVu2W3g)
  - [2023年03月07日：仿造一个大脑，就可创造智能？](https://mp.weixin.qq.com/s/pCUOL95XmaDGONaoAdAXCA)
    - [2023年03月16日：AI认知架构四十年：发展与挑战](https://mp.weixin.qq.com/s/gPcj9bA6iumE-faKhSd2ww) 
    - [2023年03月16日：脑机类比特刊：寻找复杂智能系统的普遍规律](https://mp.weixin.qq.com/s/_aQlAKf5Oj2ckbdlTZ_3Gg)
  - [2023年03月25日：摩尔定律提出者去世，他奠定了英特尔CPU黄金时代，享年94岁](https://mp.weixin.qq.com/s/z6kuEH3YBclHvdrvzp6fVg)
  - [2023年03月27日：他自己的生命游戏结束了，留给后人的数学游戏长存](https://mp.weixin.qq.com/s/4xRGPWnibcC_IyDPwTqJAA)
  - [2023年03月29日：当自然语言处理遇上量子计算与范畴论：人工智能开启更大想象空间](https://mp.weixin.qq.com/s/Cr8la2ShCbbAxX9pRUkEUg)
  - [2023年04月09日：欧洲“脑奖”得主：人脑为什么比机器学得好？](https://mp.weixin.qq.com/s/NB3RHKHwGtxXGRyu8-j4zA)
  - [2023年04月11日：爆火论文打造《西部世界》雏形：25个AI智能体，在虚拟小镇自由成长](https://mp.weixin.qq.com/s/n0I8Yisi8qNXg9qp4ic5iw)
    - [2023年04月11日：这个低调的国人团队，做出了完全由AI驱动的“开放世界”](https://mp.weixin.qq.com/s/h9NEJuUr-EXovfx4Hz3jiA)
  - [2023年04月12日：突破神经网络限制，量子蒙特卡洛研究新进展登Nature子刊](https://mp.weixin.qq.com/s/H-GHRfZpeh_l0LuZ8XFxGA)
  - [2023年04月12日：人类语言能力的自然演化：乔姆斯基对阵达尔文](https://mp.weixin.qq.com/s/6fsUaGBMrk9pDTHQk5fn6A)
  - [2023年04月30日：放弃反向传播后，Geoffrey Hinton参与的前向梯度学习重磅研究来了](https://mp.weixin.qq.com/s/xoW2DKfWYAoyPQp-b5cpTQ)
    - [2023年05月02日：谷歌突失Hinton！深度学习之父警告AI风险，对毕生工作表示遗憾](https://mp.weixin.qq.com/s/7XLa5d-UZ16O6Ead3MCanw)
    - [2023年05月04日：AI教父Hinton最新采访万字实录：ChatGPT和AI的过去现在与未来](https://mp.weixin.qq.com/s/e3EPx0voqz-d1Z2eZpet3Q)

### Pre-trained Language Model Paradigm Updating
  - [ChatGPT出来后，我们是否真的面临范式转变?](https://mp.weixin.qq.com/s/60_h5biTOlBAa3Rt2tMn6A) | 李rumor(符尧) 2022-12-29
  - [万字拆解！追溯ChatGPT各项能力的起源](https://mp.weixin.qq.com/s/VYv8BRgGnp9ZTuXxaSuFwg) | 李rumor(符尧) 2022-12-20
  - [自然语言处理范式正在变迁](https://mp.weixin.qq.com/s/FoY888g9nv5mw2kz4IWY5A) | 李rumor(车万翔) 2022-12-08
  - [通向AGI之路：大型语言模型（LLM）技术精要](https://zhuanlan.zhihu.com/p/597586623) | 张俊林 2023-01-18
  - [乘风破浪的PTM：两年来预训练模型的技术进展](https://zhuanlan.zhihu.com/p/254821426) | 张俊林 2020-09-20
