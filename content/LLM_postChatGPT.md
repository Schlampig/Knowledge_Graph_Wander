## **Large Language Methods from the Post-ChatGPT-Age**

</br>

### A
  * Alpaca(斯坦福):
    - code: https://github.com/tatsu-lab/stanford_alpaca
    - data: 
      - [AlpacaDataCleaned](https://github.com/gururise/AlpacaDataCleaned)
      - [alpaca_chinese_dataset](https://github.com/hikariming/alpaca_chinese_dataset)
    - demo: https://github.com/tatsu-lab/stanford_alpaca
    - blog:
      - [斯坦福70亿参数开源模型媲美GPT-3.5，100美元即可复现](https://mp.weixin.qq.com/s/U6ioEygg5mlVpAIb2L3cZw) | 机器之心 2023-03-15
      - [训练个中文版ChatGPT没那么难：不用A100，开源Alpaca-LoRA+RTX 4090就能搞定](https://mp.weixin.qq.com/s/cTodp4lVeW6YP9NxoKhCcA) | 机器之心 2023-03-26
      - [深入理解LLaMA, Alpaca, ColossalChat 系列模型](https://mp.weixin.qq.com/s/7kPhMNyfvhmQb97kt-BByA) | 深度学习自然语言处理 2023-04-04
    - extra:
      - [Alpaca-Lora](https://github.com/tloen/alpaca-lora): [可以微调类ChatGPT模型啦！开源Alpaca-LoRA+RTX 4090就能搞定](https://mp.weixin.qq.com/s/vzIm-fOxxPEU69ArAowoIg) | 夕小瑶的卖萌屋 2023-03-27
      - [Chinese-LLaMA-Alpaca](https://github.com/ymcui/Chinese-LLaMA-Alpaca): 中文LLaMA&Alpaca大语言模型+本地部署 (Chinese LLaMA & Alpaca LLMs).
      - [medAlpaca](https://github.com/kbressem/medAlpaca): LLM finetuned for medical question answering.
      - [Chinese-Vicuna](https://github.com/Facico/Chinese-Vicuna): A Chinese Instruction-following LLaMA-based Model，一个中文低资源的LLaMA+LoRa方案，结构参考Alpaca.
  
  * Apprentice Bard(谷歌): 
    - [Apprentice Bard: Google's potential ChatGPT rival](https://gpt3demo.com/apps/google-apprentice-bard)
    - [An important next step on our AI journey](https://blog.google/technology/ai/bard-google-ai-search-updates/) | Google Blog 2023-02-06
    - blog:
      - [谷歌版ChatGPT首秀，第一个Demo就大翻车，市值暴跌7000亿](https://mp.weixin.qq.com/s/1mkAlJbtYCmQcz_mV9cdoA) | 机器之心 2023-02-09 
      - [谷歌版ChatGPT Bard开放测试！我们已经体验上了](https://mp.weixin.qq.com/s/mbxMDuPaQLt5uXGh9kDtiQ) | 机器之心 2023-03-22
      - [Bard是拿ChatGPT数据训练的？谷歌顶级科学家抗议无果，出走OpenAI](https://mp.weixin.qq.com/s/WeUSi5rMl9_Wu-ty30gNiw) | 机器之心 2023-03-31
      - [ChatGPT实测全线碾压Bard！谷歌溃败，十年心血打水漂](https://mp.weixin.qq.com/s/f4FWGU4OjAHpFbav8SSnRA) | 新智元 2023-04-12
  
  * Aurora genAI(英特尔):
    - blog:
      - [参数是ChaGPT的近6倍！英特尔公布AI大模型Aurora genAI，具备1万亿参数](https://mp.weixin.qq.com/s/6GzWuQV-uYQqEE24nroI4g) | 人工智能学家 2023-05-25 
  
  * AutoGPT
    - code: https://github.com/torantulino/auto-gpt
    - blog:
      - [AutoGPT太火了，无需人类插手自主完成任务，GitHub2.7万星](https://mp.weixin.qq.com/s/bV1tPc7hNn2z06YOpzyanw) | 机器之心 2023-04-12
      - [理解AutoGPT原理](https://mp.weixin.qq.com/s/dONLPpeMxd5tVkTnqv1LCg) | AINLP 2023-04-22
      - [OpenAI官方的AutoGPT要来了！实测效果很优秀](https://mp.weixin.qq.com/s/rS5i3prVKqFDA62qpj3UPg) | 夕小瑶科技说 2023-04-24
      - [ChatGPT大模型如何做科学研究? CMU提出《大模型智能体系统》，高推理展现出大型语言模型的新兴自主科学研究能力](https://mp.weixin.qq.com/s/hvN3vkgMKDbyEuJ29DleZg) | 专知 2023-04-12
    - extra:
      - [GPT-4等大模型迎来进化转折点：不只是使用，还会自己制作工具了](https://mp.weixin.qq.com/s/HD8XYv9-U0q6YAU6-jFEmg) | 机器之心 2023-05-30

</br>

### B
  * 白泽BaiZe(加州大学圣迭戈分校&中山大学&微软亚研院):
    - code: https://github.com/project-baize/baize/blob/main/README.md
    - [paper](https://arxiv.org/abs/2304.01196): Baize: An Open-Source Chat Model with Parameter-Efficient Tuning on Self-Chat Data.
    - demo: https://huggingface.co/spaces/project-baize/baize-lora-7B
    - blog:
      - [用ChatGPT训练羊驼：「白泽」开源，轻松构建专属模型，可在线试玩](https://mp.weixin.qq.com/s/zxElGfclNbBwTuDG4Qrxnw) | 机器之心 2023-04-04
  
  * BBT(超对称&知识工厂):
    - code: https://github.com/ssymmetry
    - homepage: https://bbt.ssymmetry.com/model.html
    - blog:
      - [超对称联合知识工场实验室发布并开源120亿参数语言模型BBT-2](https://mp.weixin.qq.com/s/nKyvSjWykYziHXNulEz2kg) | 知识工场 2023-04-21 
  
  * BELLE(LianjiaTech):
    - code: https://github.com/LianjiaTech/BELLE)
    - note: 基于Alpaca的开源中文对话大模型（70亿参数）
    - blog:
      - [每一个人的大模型：开源BELLE项目集训练、数据、模型、评估、APP一体](https://mp.weixin.qq.com/s/HI2VvokqYNdRZgcZwfSDqw) | 机器学习算法与自然语言处理 2023-04-23
  
  * BioMedGPT(清华):
    - code: https://github.com/BioFM/OpenBioMed 
    - blog:
      - [清华AIR开源轻量版BioMedGPT！聂再清：最终目标是生物医药领域基础大模型](https://mp.weixin.qq.com/s/nD430QsT5mOQOEbpM9IO2Q) | 量子位 2023-04-20 
  
  * BloombergGPT(彭博):
    - [paper](https://arxiv.org/abs/2303.17564)
    - blog:
      - [金融圈注意了！彭博研究人员刚推出BloombergGPT](https://wallstreetcn.com/articles/3685406) | 华尔街见闻 2023-03-31 
      - [ChatGPT如何垂直化？彭博发布《BloombergGPT-500亿参数金融大型语言模型》论文，65页pdf详述模型优异性能](https://mp.weixin.qq.com/s/YmGZPjw494S90sbhw7qqqw) | 专知 2023-03-31
      - [极低资源条件下如何微调大模型：LoRA模型思想与BLOOM-LORA代码实现分析](https://mp.weixin.qq.com/s/iog2jGpb2yYQnuhSW6yH4Q) | AINLP 2023-03-31
      - [金融GPT来了：500亿参数，但用来投资还是跑不赢大盘](https://mp.weixin.qq.com/s/4ZOjbFD47M-GzklWYQH-YQ) | 机器之心 2023-04-01
      - [再谈垂直领域大模型及今日前沿速递：金融领域FinBERT、BloombergGPT以及法律领域微调模型LawGPT_zh](https://mp.weixin.qq.com/s/g5BYXnOHUTMpmKIUK4IlHg) | 老刘说NLP 2023-05-04

</br>

### C
  * ChatALL(开课吧(?)孙志岗):
    - code: https://github.com/sunner/ChatALL
    - download: https://github.com/sunner/ChatALL/releases
    - hub: https://chathub.gg/
    - blog:
      - [前哈工大教授开发的ChatALL火了！可同时提问17个聊天模型，ChatGPT/Bing/Bard/文心/讯飞都OK](https://mp.weixin.qq.com/s/1ERc9nBKMz9H_7hO02ky6w) | 量子位 2023-05-19 

  * ChatGLM(智谱AI):
    - code: https://github.com/THUDM/ChatGLM-6B/tree/main/ptuning 
    - blog:
      - [ChatGLM：千亿基座的对话模型启动内测，单卡版模型已全面开源](https://mp.weixin.qq.com/s/N79Sdx3K1em1EJxQZ9lcpA) | 学术头条 2023-03-14
      - [清华系ChatGPT发布！唐杰团队打造，专对中文优化，还能把握最新新闻动态](https://mp.weixin.qq.com/s/ZUiybuj73cgBIYDM90aE3Q) | 量子位 2023-03-18
      - [【官方教程】ChatGLM-6B微调，最低只需7GB显存](https://mp.weixin.qq.com/s/miML4PXioK5iM8UI0cTSCQ) | 学术头条 2023-03-31
      - [文心一言 VS ChatGLM-6B对比](https://mp.weixin.qq.com/s/iK_0HCYyPAXJIUw5yuTB2w) | ArronAI 2023-03-20
      - [大模型掀起诸神之战，我们更需要人人可用的“普惠模型”](https://mp.weixin.qq.com/s/RMzZIRoSfM4rxCPQb8kXGQ) | 罗超频道 2023-04-17
      - [ChatGLM基座：GLM（General Language Model）](https://mp.weixin.qq.com/s/B1U0GhnikrhFKozs_keM5w) | ChallengeHub 2023-05-15
    - technic:
      - [从0到1基于ChatGLM-6B使用LoRA进行参数高效微调](https://mp.weixin.qq.com/s/ZqlOFOrDmLIzpTJm5y0Y3Q) | AINLP 2023-05-16
      - [ChatGLM-6B V1.1：平衡微调数据，提升英文能力，加强中英互译](https://mp.weixin.qq.com/s/kkjnYQ8Mr-b_U-H0lgFi1Q) | AINLP 2023-05-17
      - [使用DeepSpeed/P-Tuning v2对ChatGLM-6B进行微调](https://mp.weixin.qq.com/s/5Zx3I39cPzfWt-HN_e-jFw) | AINLP 2023-05-18
      - [大模型阅读笔记：ChatGLM-6B模型结构组件源码阅读](https://mp.weixin.qq.com/s/bEBrWooUU2MuMt8DwzsDKQ) | 老刘说NLP 2023-05-19
    - extra:
      - [Med-ChatGLM](https://github.com/SCIR-HI/Med-ChatGLM): 基于中文医学知识的ChatGLM指令微调。
      - [Chinese-LangChain](https://github.com/yanqiangmiffy/Chinese-LangChain): [基于ChatGLM-6b+langchain实现本地化知识库检索与智能答案生成](https://mp.weixin.qq.com/s/xAsZZ_LOkr9Nj-JafSbXnA) | ChallengeHub 2023-04-19
      - [ChatGLM-Efficient-Tuning](https://github.com/hiyouga/ChatGLM-Efficient-Tuning): 基于PEFT的高效ChatGLM微调。
  
  * ChatLLM-Web(Ryan-yang125):
    - code: https://github.com/Ryan-yang125/ChatLLM-Web
    - demo: https://chat-llm-web.vercel.app/
    - note: 允许用户通过WebGPU在浏览器中使用像Vicuna这样的LLM(大型语言模型)进行聊天，保证了安全性、隐私性，且无需服务器支持。所有操作都在浏览器中完成，且由WebGPU加速。特性包括模型运行在web worker中以保证用户界面不会被阻塞、一键部署到Vercel、模型缓存支持、支持多对话聊天以及Markdown和流式响应。此应用需要支持WebGPU的浏览器，例如Chrome 113或Chrome Canary。用户的GPU需要大约6.4GB的内存。首次使用需要下载模型，目前使用的Vicuna-7b模型大小约为4GB。下载后，模型将从浏览器缓存中加载以加快使用速度。
  
  * ChatLMG(元乘象):
    - blog:
      - [会看图的「ChatGPT」来了！给张图就能聊天、讲故事、写广告](https://mp.weixin.qq.com/s/uZiYpKQOxyXaVX_3wNq1DQ) | 机器之心 2023-03-11
  
  * Chat-REC(复旦):
    - [paper](https://arxiv.org/pdf/2303.14524.pdf): Chat-REC: Towards Interactive and Explainable LLMs-Augmented Recommender System
    - blog:
      - [Chat-REC: 用大语言模型增强传统推荐的全新范式](https://mp.weixin.qq.com/s/8yuAt1KVuLF3hP-9ZtgGTg) | PaperWeekly 2023-04-02
  
  * ChatRWKV(PENG Bo):
    - code: https://github.com/BlinkDL/ChatRWKV
    - tutorial(中文): https://zhuanlan.zhihu.com/p/618011122
    - blog:
      - [使用RNN就能达到超越GPT的对话效果！甚至超越LLaMA？](https://mp.weixin.qq.com/s/gYW3L7YTNOCiJpu-66_l_g) | 深度学习自然语言处理 2023-05-12
      - [RWKV论文燃爆！将RNN崛起进行到底！可扩百亿级参数，与Transformer表现相当！](https://mp.weixin.qq.com/s/JokJttEBlXm2b8Zew4m1mw) | 深度学习自然语言处理 2023-05-24
      - [RWKV – transformer 与 RNN 的强强联合](https://mp.weixin.qq.com/s/0It3q5vgpuR_Sgk34Vce9g) | Hugging Face 2023-05-30
  
  * ChatYuan(元语智能): 
    - code: https://github.com/clue-ai/ChatYuan
    - huggingface: https://huggingface.co/ClueAI/ChatYuan-large-v2
    - modelscope: https://modelscope.cn/models/ClueAI/ChatYuan-large-v2/summary
    - 内侧申请: https://wj.qq.com/s2/11984341/e00b/
    - blog:
      - [ChatYuan: 元语功能型对话大模型](https://github.com/clue-ai/ChatYuan)
      - [部署国产ChatGPT仅需6G显存！ChatYuan模型开放下载：业内首个功能型对话开源中文大模型](https://mp.weixin.qq.com/s/1UnFUaUK7vNh9uId7XxJ2A) | 新智元 2023-02-03
      - [ChatGPT国产化：ChatYuan元语对话大模型升级](https://mp.weixin.qq.com/s/FtXAnrhavA5u7hRyfm8j6Q) | 机器之心 2023-02-21
      - [ChatYuan又开源了！效果大幅升级，在手机上也可以跑](https://mp.weixin.qq.com/s/T2cGW-r_PYvumWb0JmjSuA) | AINLP 2023-03-30
  
  * Claude([Anthropic](https://www.anthropic.com/)): 
    - homepage: https://www.anthropic.com/claude-in-slack
    - blog:
      - [ChatGPT被超越了？OpenAI核心成员出走，打造Claude模型](https://mp.weixin.qq.com/s/GT6BNVH8lt7CtLfCpKLSNg) | 夕小瑶的卖萌屋 2023-01-30
      - [「ChatGPT最强竞品」爆火：不限量不要钱免注册！一手实测体验在此](https://mp.weixin.qq.com/s/QB85YPjh6DMBTPla4NDfXg) | 量子位 2023-04-14
      - [一次10万token！GPT4最强对手史诗升级，百页资料一分钟总结完毕](https://mp.weixin.qq.com/s/h_JyYVs38lOrTmorQuoGCg) | 量子位 2023-05-12
  
  * ColossalAI(潞晨科技):
    - code: https://github.com/hpcaitech/ColossalAI
    - blog:
      - [0门槛克隆ChatGPT方案再升级，开源模型完整复现，在线体验无需注册](https://mp.weixin.qq.com/s/V5pCvYvkPXwiMw-FNIErXw) | 机器之心 2023-03-29

  * CPM-Bee(OpenBMB):
    - code: https://github.com/OpenBMB/CPM-Bee
    - huggingface: https://huggingface.co/openbmb/cpm-bee-10b
    - blog:
      - [终于 ！中文基座模型CPM-Bee开源了](https://mp.weixin.qq.com/s/BO4cDB9KRSODZw3TvZpUAA) | OpenBMB开源社区 2023-05-27
    - extra:
      - [面壁智能联合知乎开源 CPM-Bee 并发布智能对话助手“露卡”（Luca），联网论文查找摘要功能太炸裂了！](https://mp.weixin.qq.com/s/fowTQs7xHLS_0rEtIuLaaA) | 量子位 2023-05-29 

</br>

### D
  * Davinci(OpenAI): 
    - blog:
      - [GPT-3新模型Davinci，将AI写作提升到新水平！网友惊呼：GPT-4要来了？](https://mp.weixin.qq.com/s/FEeNn-_LhJLf-xqMaSlLNg) | 夕小瑶的卖萌屋 2022-12-23
  
  * DB-GPT(magic.chen):
    - code: https://github.com/csunny/DB-GPT
    - note: 一个开源的以数据库为基础的GPT实验项目，使用本地化的GPT大模型与您的数据和环境进行交互，无数据泄露风险，100% 私密，100% 安全。
  
  * DeepSpeed Chat(微软):
    - code: https://github.com/microsoft/DeepSpeed
    - homepage: https://www.deepspeed.ai/
    - blog:
      - [人手一个ChatGPT！微软DeepSpeed Chat震撼发布，一键RLHF训练千亿级大模型](https://mp.weixin.qq.com/s/G8W9nSQd600wesSJFE2dhw) | 新智元 2023-04-12
  
  * DoctorGLM(xionghonglin):
    - code: https://github.com/xionghonglin/DoctorGLM
    - project page: https://xionghonglin.github.io/DoctorGLM/
  
  * Dolly
    - blog:
      - [0门槛克隆ChatGPT！30分钟训完，60亿参数性能堪比GPT-3.5](https://mp.weixin.qq.com/s/RMrXIHGOy3cPu8ybQNWonA) | 新智元 2023-03-27
      - [Hello Dolly: Democratizing the magic of ChatGPT with open models](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html)
    - extra:
      - Dolly 2.0: 
        - [世界首款真开源类ChatGPT大模型Dolly 2.0，可随意修改商用](https://mp.weixin.qq.com/s/_9JevS70pRqEmPRbVVM9Vw) | 机器之心 2023-04-13
        - code: https://huggingface.co/databricks/dolly-v2-12b
        - dataset: https://github.com/databrickslabs/dolly/tree/master/data  
  
  * DreamGPT(DivergentAI):
    - code: https://github.com/DivergentAI/dreamGPT
    - note: 首个利用大型语言模型(LLMs)产生的幻觉进行发散性思考，以创造新颖创新想法的基于GPT的解决方案。目标是尽可能探索更多的可能性，而不是解决特定的问题。
  
  * Dromedary(IBM):
    - code: https://huggingface.co/zhiqings/dromedary-65b-lora-delta-v0
    - [paper](https://arxiv.org/pdf/2305.03047.pdf): Principle-Driven Self-Alignment of Language Models from Scratch with Minimal Human Supervision.
    - blog:
      - [IBM加入战局！任意大模型低成本变ChatGPT方法开源，个别任务超GPT-4](https://mp.weixin.qq.com/s/t5X2UDAIweKEAEE3qnuDOQ) | 量子位 2023-05-07
  * Dragonfly(OpenAI-text-davinci-003)

</br>

### E
  * 文心一言ERNIE(百度):
    - [demo](https://yiyan.baidu.com/welcome) 
    - blog:
      - [百度生成式AI产品文心一言邀请测试，五大场景、五大能力革新生产力工具](https://mp.weixin.qq.com/s/M0PE64egXweQaRWQNfNjMw) | 百度NLP 2023-03-16 
      - [文心一言 vs GPT-4实测！百度背水一战交卷](https://mp.weixin.qq.com/s/uO8N3RpcrYU8rV1RkwBxzQ) | 量子位 2023-03-16
      - [文心一言算力从哪来？自家最大智算中心：算力规模4EFLOPS，base李彦宏老家](https://mp.weixin.qq.com/s/0f51e4aUmqlXBiztfaDfeg) | 量子位 2023-03-16
      - [文心一言「起舞」，触发云战场「变天」](https://mp.weixin.qq.com/s/k_UZpLJiNCJckmILDKHbnQ) | 雷峰网 2023-03-17
      - [百度文心一言在国产模型中倒数？我看懵了](https://mp.weixin.qq.com/s/mKXw1A06Wyjznekhfuz4Hg) | 夕小瑶科技说 2023-05-12
    - extra:
      - [从通用到更专更精：百度祭出了一个「调教」大模型的平台](https://mp.weixin.qq.com/s/i24TnrYeBncmhJ5ioZPBLg) | 机器之心 2023-05-11

</br>

### F
  * FATE-LLM([Federated AI](https://fedai.org/)):
    - code: https://github.com/FederatedAI/FATE
    - blog:
      - [首个开源联邦大模型FATE-LLM，突破数据与算力壁垒](https://mp.weixin.qq.com/s/rE51A0L0sowg-8Rk9XYyaw) | AI前线 2023-04-17
  
  * 流萤Firefly(Jianxin Yang):
    - code: https://github.com/yangjianxin1/Firefly
    - blog:
      - [Firefly(流萤): 中文对话式大语言模型](https://mp.weixin.qq.com/s/O1QV32QRJtYjtvu6ZCDc7Q) | AINLP 2023-04-06 

</br>

### G
  * Ghost in the Minecraft(GITM, 商汤&清华&上海人工智能实验室):
    - code: https://github.com/OpenGVLab/GITM
    - [paper](https://github.com/OpenGVLab/GITM/blob/main/GITM.pdf): Ghost in the Minecraft: Generally Capable Agents for Open-World Enviroments via Large Language Models with Text-based Knowledge and Memory.
    - blog:
      - [商汤、清华发布通才智能体完全解锁《我的世界》，像人类一样生存，探索和创造](https://mp.weixin.qq.com/s/iECSXLdAasrwNwQTruLP7g) | 机器之心 2023-05-27 

  * Glow(北京稀宇科技有限公司(MiniMax)):
    - [api](https://api.minimax.chat/)
    - [demo](https://www.inspo.vip/)
    - blog: 
      - [首款产品Glow已达数百万用户，前商汤科技副总裁创立AI大模型企业](https://zhuanlan.zhihu.com/p/607262463) | 知乎-科技商说 2023-02-17
      - [破案了！百万用户与AI交友，背后果然有大模型](https://mp.weixin.qq.com/s/k-v6hbSonrlkPrJA6wPOlQ) | 量子位 2023-02-18
    - extra:
      - [安卓版「AI乌托邦」APP上线，下载即玩！](https://mp.weixin.qq.com/s/NYbHrGLZXv8ss0QjQPPILw) | 聆心智能官方 2023-05-09
  
  * Gorilla(UC伯克利):
   - code: https://github.com/ShishirPatil/gorilla/
   - [paper](arxiv.org/abs/2305.15334): Gorilla: Large Language Model Connected with Massive APIs.
   - homepage: gorilla.cs.berkeley.edu
   - discord community: https://discord.gg/pWeBheVY7n
   - blog:
     - [首个大规模使用工具的大模型来了：伯克利发布Gorilla](https://mp.weixin.qq.com/s/p9tx3q3Lpr4fNqdyxWhzyA) | 机器之心 2023-05-26
     - [也读大猩猩Gorilla—面向API调用场景的微调语言模型：从训练数据、训练方法到模型效果评估](https://mp.weixin.qq.com/s/HOW8xURiThngfyuQq9RXaw) | 老刘说NLP 2023-05-28
  
  * GPT4All
    - code: https://github.com/nomic-ai/gpt4all
    - source: https://gpt4all.io/index.html
    - blog:
      - [笔记本就能运行的ChatGPT平替来了，附完整版技术报告](https://mp.weixin.qq.com/s/crpG4dtfQFe3Q7hR3oeyxQ) | 机器之心 2023-03-30 

  * Guanaco(华盛顿大学):
    - code: https://github.com/artidoro/qlora
    - [paper](https://arxiv.org/abs/2305.14314): QLoRA: Efficient Finetuning of Quantized LLMs.
    - demo: https://huggingface.co/spaces/uwnlp/guanaco-playground-tgi
    - blog:
      - [跑分达ChatGPT的99%，人类难以分辨！开源「原驼」爆火，iPhone都能微调大模型了](https://mp.weixin.qq.com/s/1ZrPtBmgkklFk2_TvOhK_w) | 量子位 2023-05-25
    - extra:
      - [Making LLMs even more accessible with bitsandbytes, 4-bit quantization and QLoRA](https://huggingface.co/blog/4bit-transformers-bitsandbytes) | Huggingface 2023-05-24
</br>

### H
  * HugGPT(华师大&NUS):
    - code: https://github.com/HugAILab/HugNLP
    - [paper](https://arxiv.org/abs/2302.14286): HugNLP: A Unified and Comprehensive Library for Natural Language Processing
    - blog:
      - [可直训ChatGPT类模型！华师大、NUS开源HugNLP框架：一键刷榜，全面统一NLP训练](https://mp.weixin.qq.com/s/IpgOQJ8vrIvnjdrmGCT2FA) | 新智元 2023-05-24

  * 华驼HuaTuo
    - code: https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese
    - note: LLaMA-7B tuned with Chinese medical knowledge.
    - blog:
      - [中文医学大模型“本草”（原名华驼）：医学知识增强在中文大型语言模型指令微调上的初步探索](https://mp.weixin.qq.com/s/iuQANmwCS7AXQRik7HwQPg) | 赛尔实验室 2023-05-22
  
  * HuggingGPT(微软亚研院&浙大):
    - code(JARVIS): https://github.com/microsoft/JARVIS
    - [paper](https://arxiv.org/pdf/2303.17580.pdf): HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in HuggingFace.
    - blog:
      - [ChatGPT自己会选模型了！微软亚研院+浙大爆火新论文，HuggingGPT项目已开源](https://mp.weixin.qq.com/s/iVlc_MKSB7LFtGT-9K2hcA) | 新智元 2023-04-02 
      - [用ChatGPT「指挥」数百个模型，HuggingGPT让专业模型干专业事](https://mp.weixin.qq.com/s/tjPEFApzdLjn2Y7iz8O77A) | 机器之心 2023-04-03
    - extra:
      - [HuggingChat叫板ChatGPT！300亿参数大模型免费用](https://mp.weixin.qq.com/s/oBWc42h6GeyIbyOI2jisqQ) | 新智元 2023-04-26
      - [一键控制10万多个AI模型，HuggingFace给类ChatGPT模型们做了个「APP Store」](https://mp.weixin.qq.com/s/FaPTaMXOqCapE1mZKXnQKQ) | 机器之心 2023-05-12

</br>

### I
  * InstructBLIP(Salesforce&港科大&南洋理工):
    - code: https://github.com/salesforce/LAVIS/tree/main/projects/instructblip
    - [paper](https://arxiv.org/pdf/2305.06500.pdf): InstructBLIP: Towards General-purpose Vision-Language Models with Instruction Tuning.
    - blog:
      - [超越GPT-4！华人团队爆火InstructBLIP抢跑看图聊天，开源项目横扫多项SOTA](https://mp.weixin.qq.com/s/jI1cf7FDYJscHDZKiNvoug) | 新智元 2023-05-14 

  * InstructGLM(yanqiangmiffy):
    - code: https://mp.weixin.qq.com/s/5xFwqtJINh6HwdKPdgMARw
    - blog:
      - [InstructGLM:基于ChatGLM-6B在指令数据集上进行微调](https://mp.weixin.qq.com/s/5xFwqtJINh6HwdKPdgMARw) | ChallengeHub 2023-04-10 

</br>

### J

</br>

### K
  * 鼷鹿Kanchil:
    - code: https://github.com/vxfla/kanchil
    - note: 基于MT5的小模型。
  
  * Kosmos(微软):
    - [paper](https://arxiv.org/abs/2302.14045): Language Is Not All You Need: Aligning Perception with Language Models
    - [微软亚研院：Language Is Not All You Need](https://mp.weixin.qq.com/s/n7ziKJeVzEzVB1w1kpsn4g) | 量子位 2023-03-01
    - [从LLM到MLLM，多模态大规模语言模型KOSMOS-1赋予了语言模型看见世界的能力](https://mp.weixin.qq.com/s/c_ElIiluOsSR2rmGuF0bug) | 微软亚洲研究院 2023-03-02

</br>

### L
  * LAMINI(LaminiAI):
    - homepage: https://lamini.ai/
    - blog:
      - [神奇LLM引擎上线：帮你把GPT-3直接调成ChatGPT](https://mp.weixin.qq.com/s/eBFjLfyLycdMIF6-ucgy1w) | 机器之心 2023-04-29
  
  * LaWGPT(南大Pengxiao Song):
    - code: https://github.com/pengxiao-song/LawGPT
    - note: 一系列基于中文法律知识的开源大语言模型。该系列模型在通用中文基座模型（如 Chinese-LLaMA、ChatGLM 等）的基础上扩充法律领域专有词表、大规模中文法律语料预训练，增强了大模型在法律领域的基础语义理解能力。在此基础上，构造法律领域对话问答数据集、中国司法考试数据集进行指令精调，提升了模型对法律内容的理解和执行能力。
    - extra:
      - [也读Lawyer LLaMA法律领域微调大模型：从训练数据、模型训练到实验效果研读](https://mp.weixin.qq.com/s/Oqa6qOSI7rrhQ5kx4FzvZw) | 老刘说NLP 2023-05-26
  
  * LIMA(Meta):
    - [paper](https://arxiv.org/abs/2305.11206): LIMA: Less Is More for Alignment.
    - blog:
      - [没有RLHF，一样媲美GPT-4、Bard，Meta发布650亿参数语言模型LIMA](https://mp.weixin.qq.com/s/Oze93Brun-AQUBI5Tt1b6w) | 机器之心 2023-05-23 
  
  * 伶荔Linly([大数据系统计算机技术国家工程实验室](http://pweb.mashuwaibao.com/public/index.html#/h5/home) & 深圳大学):
    - code: https://github.com/CVI-SZU/Linly
    - blog:
      - [国产开源大模型： 百亿参数“伶荔”，填补中文基础模型空白！](https://mp.weixin.qq.com/s/XD63CRzTKrM2I2uPQrLTTQ) | Datawhale 2023-04-28 
  
  * LLaMA(Meta): 
    - [paper](https://research.facebook.com/publications/llama-open-and-efficient-foundation-language-models/): LLaMA: Open and Efficient Foundation Language Models.
    - code: https://github.com/facebookresearch/llama
    - blog:
      - [这是Meta版ChatGPT雏形？开源、一块GPU就能跑，1/10参数量打败GPT-3](https://mp.weixin.qq.com/s/Qj8smMCKzNS_oC6Mm0u_5A) | 机器之心 2023-02-25
      - [Meta最新语言模型LLaMA论文研读：小参数+大数据的开放、高效基础语言模型阅读笔记](https://mp.weixin.qq.com/s/VsFSsTPohKGDIJdATvDuvA) | 老刘说NLP 2023-02-26
      - [轻量版ChatGPT训练方法开源！仅用3天围绕LLaMA打造，号称训练速度比OpenAI快15倍](https://mp.weixin.qq.com/s/Qyf7Ng2mhuJggpyDp_84zQ) | 量子位 2023-03-01
      - [Meta开源的ChatGPT平替到底好不好用？测试结果、加料改装方法已出炉，2天5.2k星](https://mp.weixin.qq.com/s/kImwfWWtXMmEDVOhJZ4dJg) | 机器之心 2023-03-05
      - [Meta开源的LLaMa到底好不好用？最全测评结果来了](https://mp.weixin.qq.com/s/k4mYf7ZwHWhi7dWb7gEjcQ) | 夕小瑶的卖萌屋 2023-03-06
      - [代码角度看LLaMA语言模型：Meta最新模型LLaMA细节与代码详解](https://mp.weixin.qq.com/s/kz2DpGDW-MUFLROTUk-olw) | 老刘说NLP 2023-03-06
      - [A brief history of LLaMA models](https://agi-sphere.com/llama-models/) | AGI Sphere 2023-04-30
      - [【LLM系列之LLaMA】LLaMA:Open and Efficient Foundation Language Models](https://mp.weixin.qq.com/s/fGNuTcYE8QI9_JKS9LcQ7w) | ChallengeHub 2023-05-16
      - [How to run Llama 13B with a 6GB graphics card](https://gist.github.com/rain-1/8cc12b4b334052a21af8029aa9c4fafc)
    - extra: 
      - [chinese_llama_alpaca_lora](https://github.com/zhangnn520/chinese_llama_alpaca_lora): LLaMA信息抽取实战。
      - [LlamaAcademy](https://github.com/danielgross/LlamaAcademy): Teach GPTs to read API documentation using LLaMA, LoRA, and Langchain.
  
  * Llama-X:
    - [paper/code](https://github.com/AetherCortex/Llama-X): Llama-X: Open Academic Research on Improving LLaMA to SOTA LLM
    - discord: https://discord.gg/2etwhe6GvU
    - email: llama-x@mail.com
    - blog:
      - [Llama-X开源！呼吁每一位NLPer参与推动LLaMA成为最先进的LLM](https://mp.weixin.qq.com/s/HrCg6vfqq7BxBo5ATEcLrA) | PaperWeekly 2023-03-31 
  
  * LLM-Adapters(新加坡科技设计大学&新加坡管理学院&西南交大):
    - code: LLM-Adapters
    - [paper](https://arxiv.org/abs/2304.01933): LLM-Adapters: An Adapter Family for Parameter-Efficient Fine-Tuning of Large Language.
    - blog:
      - [从此告别繁琐的模型微调，LLM-Adapters助力NLP任务快速高效微调！](https://mp.weixin.qq.com/s/96FrL20w9doVfnQFO4ZaTw) | PaperWeekly 2023-04-06
  
  * LLM-IFT:
    - code: https://github.com/PhoebusSi/Alpaca-CoT
    - [doc](https://github.com/PhoebusSi/Alpaca-CoT/blob/main/CN_README.md): Alpaca-CoT: An Instruction Fine-Tuning Platform with Instruction Data Collection and Unified Large Language Models Interface.
    - blog:
      - [特制自己的ChatGPT：多接口统一的轻量级LLM-IFT平台](https://mp.weixin.qq.com/s/Q5Q3RpQ80XmpbfhSxq2R1Q) | PaperWeekly 2023-04-01
  
  * LMFlow(港科大):
    - code: https://github.com/OptimalScale/LMFlow
    - demo: http://lmflow.com/
    - blog:
      - [3090单卡5小时，每个人都能训练专属ChatGPT，港科大开源LMFlow](https://mp.weixin.qq.com/s/LCGQyNA6sHcdfIIARSNlww) | 机器之心 2023-04-02
    - extra:
      - RAFT: [玩不起RLHF？港科大开源高效对齐算法RAFT「木筏」，GPT扩散模型都能用](https://mp.weixin.qq.com/s/rhO0bE8CCQsQzsH3kdTbCA) | 量子位 2023-04-17 
  
  * Luotuo:
    - code: https://sota.jiqizhixin.com/project/luotuo
    - extra:
      - [骆驼](https://github.com/LC1332/Chinese-alpaca-lora): [中文Alpaca模型Luotuo，权重语料均开源，适用各类垂域开发；GPT-4版Copilot发布，可实时对话、语音交流代码](https://mp.weixin.qq.com/s/3QL4wK8ZAr_lztivTdoQDA) | 机器之心SOTA模型 2023-03-27
      - [Luotuo Embedding](https://github.com/LC1332/Luotuo-Text-Embedding): 用OpenAI的嵌入数据蒸馏得到的文本嵌入(text embedding)模型。
      - [Luotuo-QA](https://github.com/LC1332/Luotuo-QA): [骆驼QA：基于陈丹琦CoQA数据集的中文阅读理解模型，可给定知识文本进行问答](https://mp.weixin.qq.com/s/C4tZ7jtZ1KidGK27FSqhuQ) | 深度学习自然语言处理 2023-04-27

</br>

### M
  * MChat(澜舟科技):
    - blog:
      - [AI大牛周明发布MChat：生成可控，参数规模可负担，顺便官宣了新融资](https://mp.weixin.qq.com/s/xlmSJ7WSKgVTlr2QrK6_ow) | 量子位 2023-03-20
  
  * MedGPT(医联):
    - blog:
      - [国内首个医疗大语言模型问世！多模态打通诊疗全流程，别再叫我做题家](https://mp.weixin.qq.com/s/wDVT4Z29eggGjiyKvhHoVQ) | 新智元 2023-05-26 
  
  * MetaLLM([秘塔科技](https://metasota.ai/#/)): 
    - [秘塔写作猫](xiezuocat.com/chat)
    - [立即体验！直接可用的中文版ChatGPT来了](https://mp.weixin.qq.com/s/uV4rjy3aBaHLnT5RsLqbZA) | 机器之心 2023-02-28
  
  * MiniGPT(KAUST):
    - code: https://github.com/Vision-CAIR/MiniGPT-4
    - blog:
      - [MiniGPT-4实现原理及其核心BLIP2模型实践：从代表性图文对数据集、BLIP2模型结构到调用实践](https://mp.weixin.qq.com/s/aU6fhmlO-6SY5VyjTMpIMg) | 老刘说NLP 2023-04-24
  
  * MOSS(复旦大学): 
    - code: https://github.com/OpenLMLab/MOSS
    - blog
      - [复旦发布中国版ChatGPT：MOSS开启测试冲上热搜，服务器挤爆](https://mp.weixin.qq.com/s/LjwSozikB6CK5zh2Nd2JHw) | 机器之心 2023-02-21
      - [研究成果将会开源！复旦MOSS团队深度访谈来了](https://mp.weixin.qq.com/s/NCWFaTsWOPEsTu2Qs6SYwA) | 深度学习自然语言处理 2023-03-02
      - [复旦团队大模型 MOSS 开源了，有哪些技术亮点值得关注？](https://mp.weixin.qq.com/s/LjToZVWjQ-ot5KJFCFtA3g) | 深度学习自然语言处理 2023-04-22
      - [符尧：我想为 MOSS 正名](https://mp.weixin.qq.com/s/NicaChbg_Js3RFliHjkb2w) | 深度学习自然语言处理 2023-04-23
      - [复旦NLP团队大模型 MOSS 开源了，有哪些技术亮点值得关注？](https://mp.weixin.qq.com/s/C68RjC3eqADaoEEKIcsMVQ) | AINLP 2023-04-23
      - [MOSS国产大模型问答原理与插件式SFT数据概述：一个类HuggingGPT思想的精彩工作简单总结](https://mp.weixin.qq.com/s/9cD2-4gIMIz9j6d3xapQhg) | 老刘说NLP 2023-04-26
      - [文心一言和MOSS相比，竟然在这些方面完败！](https://mp.weixin.qq.com/s/tbb-__9UiHYm3HJjjuvGjQ) | 深度学习自然语言处理 2023-04-29
  
  * MPT(MosaicML):
    - homepage: https://www.mosaicml.com/blog/mpt-7b
    - blog: 
      - [两大可商用开源大模型同时发布！性能不输LLaMA，羊驼家族名字都不够用了](https://mp.weixin.qq.com/s/cOKCElMEWgjkACA_pG78RQ) | 量子位 2023-05-07

</br>

### N

</br>

### O
  * OpenChatKit(Together):
    - website: https://www.together.xyz/blog/openchatkit 
    - blog:
      - [ChatGPT开源替代来了！参数量200亿，在4300万条指令上微调而成](https://mp.weixin.qq.com/s/9Av3nhJLrcYAsBW9vVGjTw) | 机器之心 2023-03-13
      - [ChatGPT开源平替来了，开箱即用！前OpenAI团队打造，GitHub刚发布就揽获800+星](https://mp.weixin.qq.com/s/-MEOhOVut2dCvbF5N6UfyQ) | 量子位 2023-03-13
      - [Together发布首个全面开源社区版ChatGPT](https://mp.weixin.qq.com/s/awb6AyEl8QHSiv-eHpmwdw) | 机器之心SOTA模型 2023-03-13
  
  * OpenFlamingo(AI2&华大&哥大):
    - code: https://github.com/mlfoundations/open_flamingo
    - [paper](https://arxiv.org/abs/2304.06939): Multimodal C4: An Open, Billion-scale Corpus of Images Interleaved With Text 
    - blog:
      - [ANNOUNCING OPENFLAMINGO: AN OPEN-SOURCE FRAMEWORK FOR TRAINING VISION-LANGUAGE MODELS WITH IN-CONTEXT LEARNING](https://laion.ai/blog/open-flamingo/) | official blog 2023-03-28
  
  * 水獭Otter(南洋理工):
    - code: https://github.com/Luodian/otter
    - [paper](https://arxiv.org/abs/2305.03726): Otter: A Multi-Modal Model with In-Context Instruction Tuning
    - note: 一种基于OpenFlamingo构建的指令调优模型，已针对上下文进行了定制。

</br>

### P
  * PaLM2(谷歌):
    - blog:
      - [新大模型能超GPT-4，Bard全面升级，谷歌反击ChatGPT](https://mp.weixin.qq.com/s/HsyJ272c3joHo_4EeDOrWg) | 机器之心 2023-05-11
      - [谷歌不服输：大模型PaLM2剑指GPT-4，Bard会写20种代码，推出办公助手「Duet A​I」](https://mp.weixin.qq.com/s/2p1XVEMM-sqQJpk8a6RUVw) | 36氪 2023-05-11
      - [PaLM 2重磅来袭，深挖谷歌92页技术报告亮点总结](https://mp.weixin.qq.com/s/XQE6RWz_8soyAsEfXl0NbQ) | 将门创投 2023-05-22
    - extra:
      - [大模型如何构建“医生级”问答？谷歌DeepMInd最新《基于大型语言模型的专家级医疗问答研究》论文，提出Med-PaLM 2](https://mp.weixin.qq.com/s/rChVy5lhFoX5dV9oPkVzfw) | 专知 2023-05-21

  * PandaLM(北京大学&西湖大学):
    - code: https://github.com/WeOpenML/PandaLM
    - former study: https://github.com/PKU-Alignment/omnisafe
    - dataset: https://huggingface.co/datasets/PKU-Alignment/PKU-SafeRLHF-10K
    - blog: 
      - [可复现、自动化、低成本、高评估水平，首个自动化评估大模型的大模型PandaLM来了](https://mp.weixin.qq.com/s/CNODZmTW7QJAJ42ZSCWqrA) | 机器之心 2023-05-08
  
  * PKU-Beaver(北大):
    - code: https://github.com/PKU-Alignment/safe-rlhf
    - blog:
      - [国内首个可复现的RLHF基准，北大团队开源 PKU-Beaver](https://mp.weixin.qq.com/s/O1RDHrmEg99zCil8ycqOGQ) | 机器之心 2023-05-18 

</br>

### Q

</br>

### R
  * RecurrentGPT(ETH):
    - code: https://github.com/aiwaves-cn/RecurrentGPT
    - [paper](https://arxiv.org/abs/2305.13304): RecurrentGPT: Interactive Generation of (Arbitrarily) Long Text.
    - demo: https://www.aiwaves.org/recurrentgpt (长篇小说写作)
    - demo2: https://www.aiwaves.org/interactivefiction (交互式小说)
    - blog:
      - [ChatGPT能写长篇小说了，ETH提出RecurrentGPT实现交互式超长文本生成](https://mp.weixin.qq.com/s/9zDyyqaHA8Ghnh96f2IOLg) | 机器之心 2023-05-28 

</br>

### S
  * Sage(OpenAI-GPT-3.5-Turbo):
    - blog:
      - [Everything You Need to Know About Sage-Chatbot Testing Feature](https://www.qyrus.com/post/feature-friday-everything-you-need-to-know-about-sage-chatbot-testing-feature) 
      - [Sage Gpt-4 Claude+ ChatGPT Dragonfly五个AI的各自特点](https://zhuanlan.zhihu.com/p/614720305) | 春眠不觉晓 2023-03-17
  
  * 商量SenseChat(商汤科技):
    - blog:
      - [商汤“日日新SenseNova”大模型超市，来了！](https://mp.weixin.qq.com/s/Y97ejN4ZeLqECvGhfUs8Gw) | 商汤科技SenseTime 2023-04-10
      - [商汤版ChatGPT「商量」来了！开放API，基于千亿参数大模型，体验实录在此](https://mp.weixin.qq.com/s/QoQwfuzttBMxLgjVZLYI4w) | 量子位 2023-04-10
  
  * SpeechGPT(复旦):
    - code: https://github.com/0nutation/SpeechGPT
    - [paper](https://arxiv.org/pdf/2305.11000.pdf): SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities.
    - demo: https://0nutation.github.io/SpeechGPT.github.io/
    - blog: 
      - [为多模态LLM指明方向，邱锡鹏团队提出具有内生跨模态能力的SpeechGPT](https://mp.weixin.qq.com/s/KpdOUdeYSVzrBtfuqFbjaQ) | 机器之心 2023-05-20  
  
  * StarChat:
    - code: https://huggingface.co/blog/starchat-alpha
    - blog:
      - [秒杀自动编码Copilot！「动嘴编程」神器StarChat开源，码农狂喜](https://mp.weixin.qq.com/s/gYn33ZDqqabjagpacCsh-w) | 新智元 2023-05-14 
  
  * StarCoder(HuggingFace&ServiceNow ):
    - code: https://github.com/bigcode-project/starcoder
    - [paper](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view): StarCoder: may the source be with you!
    - blog:
      - [StarCoder: 最先进的代码大模型](https://mp.weixin.qq.com/s/f-WwzLcEO-ZJczI-_bZh3Q) | Hugging Face 2023-05-08
      - [使用 StarCoder 创建一个编程助手](https://mp.weixin.qq.com/s/-j_d0D0paFHrm4ciDFcI6Q) | Hugging Face 2023-05-24

</br>

### T
  * 通义千问(阿里):
    - homepage: tongyi.aliyun.com
    - blog:
      - [官宣：阿里云大模型开始邀请测试](https://mp.weixin.qq.com/s/Zp23VMxQiWHZzsBZNUtPwQ) | 阿里云 2023-04-07
      - [阿里版ChatGPT突然上线邀测！大模型热战正剧开始，这是第一手体验实录](https://mp.weixin.qq.com/s/olGY9Cm6hO1h8C9DSy7_qA) | 量子位 2023-04-07
      - [阿里版ChatGPT「通义千问」邀请测试，我们第一时间试了试](https://mp.weixin.qq.com/s/95qLhDVwNUnyJuF21jzHPw) | 机器之心 2023-04-07 
      - [阿里「通义千问」大战百度「文心一言」15个回合后，GPT4沉默了](https://mp.weixin.qq.com/s/fF8uXP00B9MtehaHE2ld9Q) | 夕小瑶的卖萌屋 2023-04-09

</br>

### U

</br>

### V
  * Vicuna(UC伯克利&CMU&斯坦福):
    - demo: https://chat.lmsys.org/
    - blog:
      - [300美元平替ChatGPT！斯坦福130亿参数「小羊驼」诞生，暴杀「草泥马」](https://mp.weixin.qq.com/s/mErCYhbAXlhSFVUuyMc9hw) | 新智元 2023-03-31
      - [警惕不负责任的误导宣传-LLaMA微调7W数据的Vicuna达90%+ChatGPT：评测方式概述和开源微调数据介绍](https://mp.weixin.qq.com/s/whLY8wc6WMaHkx4VJ7aewg) | 老刘说NLP 2023-04-07 
      - [大模型也内卷，Vicuna训练及推理指南，效果碾压斯坦福羊驼](https://mp.weixin.qq.com/s/tjXYrHCYhQQeRPEGBiSQWw) | AINLP 2023-05-12
  
  * Visual ChatGPT(微软):
    - blog:
      - [王炸！微软发布Visual ChatGPT：视觉模型加持ChatGPT实现丝滑聊天](https://mp.weixin.qq.com/s/cd7g7l01V5poP41hRt1IPQ) | 夕小瑶的卖萌屋 2023-03-10
  
  * VisualGLM(智谱AI&清华KEG):
    - code: https://github.com/THUDM/VisualGLM-6B
    - huggignface: https://huggingface.co/THUDM/visualglm-6b
    - blog:
      - [VisualGLM-6B：开源的多模态对话模型，最低只需8.7G显存](https://mp.weixin.qq.com/s/qXFDCz4AvgWo8oBiH-udgg) | 学术头条 2023-05-18
      - [巧用prompt可提升解题：多模态对话语言模型VisualGLM-6B及借助多步渐进式提示PHP增强解题能力工作介绍](https://mp.weixin.qq.com/s/gGHjvqxt0E88cgAzfvejww) | 老刘说NLP 2023-05-18
  
  * Voyager(英伟达):
    - homepage: https://voyager.minedojo.org/
    - [paper](https://arxiv.org/abs/2305.16291): Voyager: An Open-Ended Embodied Agent with Large Language Models. 
    - blog:
      - [英伟达AI智能体接入GPT-4，完胜AutoGPT！自主写代码独霸我的世界，无需人类插手](https://mp.weixin.qq.com/s/jaUeCl5pSs-sier89MXq1Q) | 新智元 2023-05-27 
  
  * VPGTrans(新加坡国立&清华):
    - code: https://github.com/VPGTrans/VPGTrans
    - [paper](https://arxiv.org/pdf/2305.01278.pdf): VPGTrans:Transfer Visual Prompt Generator across LLMs.
    - demo: https://vpgtrans.github.io/
    - blog:
      - [VPGTrans: 10%的成本定制你自己的类GPT-4多模态大模型](https://mp.weixin.qq.com/s/COByThDpn6pVICGD6dMG0Q) | 夕小瑶科技说 2023-05-10 

</br>

### W
  * WebCPM(清华):
    - code: https://github.com/thunlp/WebCPM
    - [paper](https://arxiv.org/abs/2305.06849): WebCPM: Interactive Web Search for Chinese Long-form Question Answering.
    - blog:
      - [清华ACL 2023最新长文 | WebCPM：首个联网支持中文问答开源模型](https://mp.weixin.qq.com/s/WSzJpQBxQQKdMRRrDObICQ) | PaperWeekly 2023-05-13 

  * 袋熊Wombat(阿里达摩院):
    - code: https://github.com/GanjinZero/RRHF
    - [paper](https://arxiv.org/abs/2304.05302): RRHF: Rank Responses to Align Language Models with Human Feedback without tears.
    - blog:
      - [无需强化学习的与人类偏好对齐的语言模型：Wombat袋熊](https://mp.weixin.qq.com/s/xoPKmOzjlNZ2qGdcKeGARw) | PaperWeekly 2023-04-13 

</br>

### X
  * 星火(科大讯飞):
    - blog:
      - [“三项能力超过ChatGPT”，科大讯飞星火大模型现场接受观众挑战，写稿制表PPT通通拿下](https://mp.weixin.qq.com/s/o-Yy2uz51_gMyEjamtkAkw) | 量子位 2023-05-06
      - [GPT诸神之战，小巨头如何做大模型？](https://mp.weixin.qq.com/s/ZS-yiIleIVEJAsnmvS6AGg) | 雷峰网 2023-05-08

  * 轩辕(度小满):
    - blog:
      - [首个开源中文金融大模型来了！解释授信额度、计算收益率、决策参考样样通，来自度小满](https://mp.weixin.qq.com/s/cQ72KvOhYf6Cojzn2l35dQ) | 量子位 2023-05-26
</br>

### Y
  * youChat(You.com): 
    - blog:
      - [ChatGPT还在2G冲浪？新模型「youChat」：我已能够解说2022世界杯](https://mp.weixin.qq.com/s/HQDfdgtDhRvSWSdiPQEPcg) | 机器之心 2022-12-24

</br>

### Z
  
