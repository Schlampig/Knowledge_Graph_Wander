## **Make Your Models More Clever**

---
## Knowledge into language model

### Papers
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

---
## Prompt-Tuning

### PromptPapers
  * link: https://github.com/thunlp/PromptPapers
  * author: THUNLP
  * note: must-read papers on prompt-based tuning for pre-trained language models.
  * blog:
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
    - [P-tuning：自动构建模版，释放语言模型潜能](https://spaces.ac.cn/archives/8295) | 苏剑林 科学空间 2021年4月3日

### OpenPrompt
  * link: https://github.com/thunlp/OpenPrompt
  * author: THUNLP
  * note: an open-source toolkit for prompt-learning.

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

### Instruction Tuning
  * [paper](https://arxiv.org/pdf/2109.01652v1.pdf): FINETUNED LANGUAGE MODELS ARE ZERO-SHOT LEARNERS （FLAN）.
  * blog:
    - [Instruction Tuning｜谷歌Quoc V.Le团队提出精调新范式！香过Prompt！](https://mp.weixin.qq.com/s/DcdYRzdGkF5MaL5M3yGLTw) | rumor 李rumor 9月9日
    - [别再Prompt了！谷歌提出tuning新方法，强力释放GPT-3潜力！](https://mp.weixin.qq.com/s/TLdKRvG1Hdsjak8AeNG-3w) | Yimin_饭煲 夕小瑶的卖萌屋 9月7日

</br>
