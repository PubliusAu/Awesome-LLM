# Awesome-LLM

🔥 Large Language Models(LLM) have taken the ~~NLP community~~ **the Whole World** by storm. Here is a comprehensive list of papers about large language models, especially relating to ChatGPT. It also contains codes, courses and related websites as shown below:

  * [Milestone Papers](#milestone-papers)
  * [ChatGPT Evaluation](#chatgpt-evaluation)
  * [Tools for Training LLM](#tools-for-training-llm)
  * [Tutorials about LLM](#tutorials-about-llm)
  * [Course about LLM](#course-about-llm)
  * [Useful Resources](#useful-resources)
  * [Contributing](#contributing)

## Milestone Papers

| Year | keywords     | Institute | Paper                                                        | Publication |
| :--: | :----------- | :-------: | :----------------------------------------------------------- | :---------: |
| 2017 | Transformers |  Google   | [Attention Is All You Need](https://arxiv.org/pdf/1706.03762.pdf) |   NeurIPS   |
| 2018 | GPT 1.0      |  OpenAI   | [Improving Language Understanding by Generative Pre-Training](https://www.cs.ubc.ca/~amuham01/LING530/papers/radford2018improving.pdf) |             |
| 2019 | BERT         |  Google   | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://aclanthology.org/N19-1423.pdf) |    NAACL    |
| 2019 | T5           |  Google   | [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://jmlr.org/papers/v21/20-074.html) |    JMLR     |
| 2019 | GPT 2.0      |  OpenAI   | [Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) |             |
| 2020 | GPT 3.0      |  OpenAI   | [Language models are few-shot learners](https://papers.nips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf) |   NeurIPS   |
| 2020 | Scaling Law  |  OpenAI   | [Scaling Laws for Neural Language Models](https://arxiv.org/pdf/2001.08361.pdf) |             |
| 2020 | Megatron-LM  | NVIDIA | [Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/pdf/1909.08053.pdf) ||
| 2022 | Flan-T5 | Google | [Scaling Instruction-Finetuned Language Models](https://arxiv.org/pdf/2210.11416.pdf) |  |
| 2021 | LM-BFF | Princeton | [Making Pre-trained Language Models Better Few-shot Learners](https://arxiv.org/pdf/2012.15723.pdf) | ACL|
| 2021 | WebGPT | OpenAI | [WebGPT: Improving the Factual Accuracy of Language Models through Web Browsing](https://openai.com/blog/webgpt/) |  |
| 2021 | Codex | OpenAI | [Evaluating Large Language Models Trained on Code](https://arxiv.org/pdf/2107.03374.pdf) |  |
| 2022 | Foundation Models | Stanford |[On the Opportunities and Risks of Foundation Models](https://arxiv.org/pdf/2108.07258.pdf) |  |
| 2022 | HELM | Stanford | [Holistic Evaluation of Language Models](https://arxiv.org/pdf/2211.09110.pdf) |  |
| 2022 | InstructGPT | OpenAI | [Training language models to follow instructions with human feedback](https://arxiv.org/pdf/2203.02155.pdf) |  |
| 2022 | Emergent Abilities | Google | [Emergent Abilities of Large Language Models](https://openreview.net/pdf?id=yzkSU5zdwD) | TMLR |
| 2022 | COT | Google | [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/pdf/2201.11903.pdf) | NeurIPS |
| 2022 | PaLM | Google | [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/pdf/2204.02311.pdf) |  |
| 2022 | FLAN | Google | [Finetuned Language Models are Zero-Shot Learners](https://openreview.net/forum?id=gEZrGCozdqR) | ICLR |
| 2022 | Chinchilla| DeepMind | [An empirical analysis of compute-optimal large language model training](https://www.deepmind.com/publications/an-empirical-analysis-of-compute-optimal-large-language-model-training) | NeurIPS |
| 2022 | BIG-bench | Google | [Beyond the Imitation Game: Quantifying and extrapolating the capabilities of language models](https://github.com/google/BIG-bench) |  |
| 2022 | BLOOM | BigScience | [BLOOM: A 176B-Parameter Open-Access Multilingual Language Model](https://arxiv.org/pdf/2211.05100.pdf) |  |
| 2022 | OPT | Meta | [OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/pdf/2205.01068.pdf) |  |
| 2022 | LaMDA| Google | [LaMDA: Language Models for Dialog Applications](https://arxiv.org/pdf/2201.08239.pdf) |  |
| 2022 | Sparrow | DeepMind | [Improving alignment of dialogue agents via targeted human judgements](https://arxiv.org/pdf/2209.14375.pdf) |  |
| 2022 | Retro | DeepMind | [Improving language models by retrieving from trillions of tokens](https://www.deepmind.com/publications/improving-language-models-by-retrieving-from-trillions-of-tokens) | ICML |
| 2022 | METALM | Microsoft | [Language Models are General-Purpose Interfaces](https://arxiv.org/pdf/2206.06336.pdf) |  |
| 2022 | Galactica | Meta | [Galactica: A Large Language Model for Science](https://arxiv.org/pdf/2211.09085.pdf) |  |
| 2023 | Flan 2022 Collection | Google | [The Flan Collection: Designing Data and Methods for Effective Instruction Tuning](https://arxiv.org/pdf/2301.13688.pdf) |  |

## ChatGPT Evaluation

- Is ChatGPT a General-Purpose Natural Language Processing Task Solver? [Link](https://arxiv.org/pdf/2302.06476.pdf)

- Is ChatGPT A Good Translator? A Preliminary Study [Link](https://arxiv.org/pdf/2301.08745.pdf)

## Tools for Training LLM

- DeepSpeed [Link](https://www.deepspeed.ai)

- Megatron-LM [Link](https://github.com/NVIDIA/Megatron-LM)

- Colossal-AI [Link](https://colossalai.org)

- Mesh TensorFlow [Link](https://github.com/tensorflow/mesh)

## Tutorials about LLM

- [ICML 2022] Welcome to the &#34;Big Model&#34; Era: Techniques and Systems to Train and Serve Bigger Models [Link](https://icml.cc/virtual/2022/tutorial/18440)

- [NeurIPS 2022] Foundational Robustness of Foundation Models [Link](https://nips.cc/virtual/2022/tutorial/55796)

- [Andrej Karpathy] Let's build GPT: from scratch, in code, spelled out. [Video](https://www.youtube.com/watch?v=kCc8FmEb1nY)|[Code](https://github.com/karpathy/ng-video-lecture)

## Course about LLM

- [Stanford] CS224N-Lecture 11: Prompting, Instruction Finetuning, and RLHF [Slides](https://web.stanford.edu/class/cs224n/slides/cs224n-2023-lecture11-prompting-rlhf.pdf)

- [Stanford] CS324-Large Language Models [Homepage](https://stanford-cs324.github.io/winter2022/)

- [Stanford] CS25-Transformers United V2 [Homepage](https://web.stanford.edu/class/cs25/)

- [李沐] InstructGPT论文精读 [Bilibili](https://www.bilibili.com/video/BV1hd4y187CR/?spm_id_from=333.337.search-card.all.click&vd_source=1e55c5426b48b37e901ff0f78992e33f) [Youtube](https://www.youtube.com/watch?v=zfIGAwD1jOQ)

- [李沐] HELM全面语言模型评测 [Bilibili](https://www.bilibili.com/video/BV1z24y1B7uX/?spm_id_from=333.337.search-card.all.click&vd_source=1e55c5426b48b37e901ff0f78992e33f)

- [李沐] GPT，GPT-2，GPT-3 论文精读 [Bilibili](https://www.bilibili.com/video/BV1AF411b7xQ/?spm_id_from=333.788&vd_source=1e55c5426b48b37e901ff0f78992e33f) [Youtube](https://www.youtube.com/watch?v=t70Bl3w7bxY&list=PLFXJ6jwg0qW-7UM8iUTj3qKqdhbQULP5I&index=18)

- [Aston Zhang] Chain of Thought论文 [Bilibili](https://www.bilibili.com/video/BV1t8411e7Ug/?spm_id_from=333.788&vd_source=1e55c5426b48b37e901ff0f78992e33f) [Youtube](https://www.youtube.com/watch?v=H4J59iG3t5o&list=PLFXJ6jwg0qW-7UM8iUTj3qKqdhbQULP5I&index=29)

## Useful Resources
- \[2023-02-16][知乎][旷视科技]**对话旷视研究院张祥雨｜ChatGPT的科研价值可能更大** [Link](https://zhuanlan.zhihu.com/p/606918875)
- \[2023-02-15][知乎][张家俊]**关于ChatGPT八个技术问题的猜想** [Link](https://zhuanlan.zhihu.com/p/606478660)
- \[2023-02-14][Stephen Wolfram]**What Is ChatGPT Doing … and Why Does It Work? [Link](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)**
- \[2023-02-13]\[知乎][熊德意] **对ChatGPT的二十点看法 [Link](https://zhuanlan.zhihu.com/p/605882945?utm_medium=social&utm_oi=939485757606461440&utm_psn=1609870392121860096&utm_source=wechat_session)**
- \[2023-02-11]\[知乎][刘聪NLP] **ChatGPT-所见、所闻、所感 [Link](https://zhuanlan.zhihu.com/p/605331104)**
- \[2023-02-07][Forbes] **The Next Generation Of Large Language Models [Link](https://www.notion.so/Awesome-LLM-40c8aa3f2b444ecc82b79ae8bbd2696b)**
- \[2023-01-26][NVIDIA] **What Are Large Language Models Used For? [Link](https://www.notion.so/Awesome-LLM-40c8aa3f2b444ecc82b79ae8bbd2696b)**
- \[2023-01-18]\[知乎][张俊林] **通向AGI之路：大型语言模型(LLM)技术精要 [Link](https://zhuanlan.zhihu.com/p/597586623)**
- \[2023-01-06\][Shayne Longpre] **Major LLMs + Data Availability [Link](https://docs.google.com/spreadsheets/d/1bmpDdLZxvTCleLGVPgzoMTQ0iDP2-7v7QziPrzPdHyM/edit#gid=0)**
- \[2021-10-26\]\[Huggingface\] **Large Language Models: A New Moore's Law [Link](https://huggingface.co/blog/large-language-models)**

## Contributing

This is an active repository and your contributions are always welcome! 

I will keep some pull requests open if I'm not sure if they are awesome for LLM, you could vote for them by adding 👍 to them.

------

If you have any question about this opinionated list, do not hesitate to contact me chengxin1998@stu.pku.edu.cn.
