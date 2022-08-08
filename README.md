# Awesome Pretrained Language Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Pretrained Language Models (PLMs) have been achieved great success over  many NLP tasks. And with the rapid development of PLMs, there is a need to make a list to show these succesful and remarkable language models.

# Lists of Language Models

Group by companies and organizations.

* [Al21 Labs](#al21-labs)
* [Alibaba](#alibaba)
* [Amazon](#amazon)
* [Baidu](#baidu)
* [BigSicence](#bigsicence)
* [DeepMind](#deepmind)
* [EleutherAI](#eleutherai)
* [Meta (Facebook)](#meta-facebook)
* [Fudan University](#fudan-university)
* [Google](#google)
* [HIT & iFLYTEK](#hit--iflytek)
* [Huawei](#huawei)
* [Inspur](#inspur)
* [JD (JINGDONG)](#jd-jingdong)
* [Langboat](#langboat)
* [Microsoft](#microsoft)
* [Nvidia](#nvidia)
* [OpenAI](#openai)
* [OPPO](#oppo)
* [Tencent](#tencent)
* [THU (Tsinghua) & BAAI (Beijing)](#thu-tsinghua--baai-beijing)
* [More PLMs are coming ...](#more-plms-are--coming-)

## Al21 Labs

* Jurassic-1
  * [JURASSIC-1: TECHNICAL DETAILS AND EVALUATION](https://uploads-ssl.webflow.com/60fd4503684b466578c0d307/61138924626a6981ee09caf6_jurassic_tech_paper.pdf) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/ai21labs/lm-evaluation) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

## Alibaba

* PLUG (**P**re-training for **L**anguage **U**nderstanding and **G**eneration))
  * [超大规模中文生成](https://nlp.aliyun.com/portal#/plug) ![demo](https://img.shields.io/badge/-demo-blue?style=flat)

## Amazon

* Alexa Teacher Model 
  * [Alexa Teacher Model: Pretraining and Distilling Multi-Billion-Parameter Encoders for Natural Language Understanding Systems](https://arxiv.org/abs/2206.07808) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * AlexaTM 20B
    * [AlexaTM 20B: Few-Shot Learning Using a Large-Scale Multilingual Seq2Seq Model](https://arxiv.org/abs/2208.01448)  ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/amazon-research/alexa-teacher-models) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    (model hasn't been publicly released yet, stay tuned!)

## Baidu

* ERNIE family: [github repo](https://github.com/PaddlePaddle/ERNIE) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * ERNIE 1.0
    * [ERNIE: Enhanced Representation through Knowledge Integration](https://arxiv.org/abs/1904.09223) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE 2.0
    * [ERNIE 2.0: A Continual Pre-training Framework for Language Understanding](https://arxiv.org/abs/1907.12412) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE 3.0
    * [ERNIE 3.0: Large-scale Knowledge Enhanced Pre-training for Language Understanding and Generation](https://arxiv.org/abs/2107.02137) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE 3.0 TiTan
    * [ERNIE 3.0 Titan: Exploring Larger-scale Knowledge Enhanced Pre-training for Language Understanding and Generation](https://arxiv.org/abs/2112.12731) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE 3.0 Zeus 
    * [ERNIE 3.0 Zeus Prompt: 全球首个融合任务相关知识的千亿中文大模型](https://wenxin.baidu.com/younger/apiDetail?id=20006) ![demo](https://img.shields.io/badge/-demo-blue?style=flat)
  * ERNIE-GEN
    * [ERNIE-GEN: An Enhanced Multi-Flow Pre-training and Fine-tuning Framework for Natural Language Generation](https://arxiv.org/abs/2001.11314) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat) 
  * ERNIE-ViL
    * [ERNIE-ViL: Knowledge Enhanced Vision-Language Representations Through Scene Graph](https://arxiv.org/abs/2006.16934) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-ViLG
    * [ERNIE-ViLG: Unified Generative Pre-training for Bidirectional Vision-Language Generation
      ](https://arxiv.org/abs/2112.15283) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-Gram 
    * [ERNIE-Gram: Pre-Training with Explicitly N-Gram Masked Language Modeling for Natural Language Understanding](https://arxiv.org/abs/2010.12148) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-M
    * [ERNIE-M: Enhanced Multilingual Representation by Aligning Cross-lingual Semantics with Monolingual Corpora](https://arxiv.org/abs/2012.15674) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-Doc
    * [ERNIE-Doc: A Retrospective Long-Document Modeling Transformer](https://arxiv.org/abs/2012.15688) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-Tiny
    * [ERNIE-Tiny : A Progressive Distillation Framework for Pretrained Transformer Compression](https://arxiv.org/abs/2106.02241) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-GeoL
    * [ERNIE-GeoL: A Geography-and-Language Pre-trained Model and its Applications in Baidu Maps](https://arxiv.org/abs/2203.09127) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-SPARSE
    * [ERNIE-SPARSE: Learning Hierarchical Efficient Transformer Through Regularized Self-Attention](https://arxiv.org/abs/2203.12276) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * ERNIE-Search
    * [ERNIE-Search: Bridging Cross-Encoder with Dual-Encoder via Self On-the-fly Distillation for Dense Passage Retrieval](https://arxiv.org/abs/2205.09153) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)

<br/>

* PLATO family:  [github repo](https://github.com/PaddlePaddle/Knover) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * PLATO-1 
    * [PLATO: Pre-trained Dialogue Generation Model with Discrete Latent Variable](https://arxiv.org/abs/1910.07931) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * PLATO-2
    * [PLATO-2: Towards Building an Open-Domain Chatbot via Curriculum Learning](https://arxiv.org/abs/2006.16779) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * PLATO-XL
    * [PLATO-XL: Exploring the Large-scale Pre-training of Dialogue Generation](https://arxiv.org/abs/2109.09519) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * PLATO-KAG
    * [PLATO-KAG: Unsupervised Knowledge-Grounded Conversation via Joint Modeling](https://aclanthology.org/2021.nlp4convai-1.14/) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)

## BigSicence

* T0 series
  * [Multitask Prompted Training Enables Zero-Shot Task Generalization
    ](https://arxiv.org/abs/2110.08207) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [Hugging Face 🤗](https://huggingface.co/bigscience/T0) 
  * [github repo](https://github.com/bigscience-workshop/t-zero) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
* BLOOM 
  * [Hugging Face 🤗](https://huggingface.co/bigscience/bloom)

## DeepMind

* Gopher 
  * [Scaling Language Models: Methods, Analysis & Insights from Training Gopher](https://arxiv.org/abs/2112.11446) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
* Chinchilla
  * [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
* Retro
  * [Improving language models by retrieving from trillions of tokens](https://arxiv.org/abs/2112.04426) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/lucidrains/RETRO-pytorch) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white) (Non-offical implementation)

## EleutherAI

[Hugging Face 🤗](https://huggingface.co/EleutherAI)

* GPT-Neo
  * [github repo](https://github.com/EleutherAI/gpt-neo/) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white) 
* GPT-J
  * [github repo](https://github.com/kingoflolz/mesh-transformer-jax/) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white) 
* GPT-NeoX 
  * [github repo](https://github.com/EleutherAI/gpt-neox) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

## Meta (Facebook)

* XGLM
  * [Few-shot Learning with Multilingual Language Models](https://arxiv.org/abs/2112.10668) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [Hugging Face 🤗](https://huggingface.co/facebook/xglm-7.5B)
* XLM-R 
  * [Unsupervised Cross-lingual Representation Learning at Scale](https://arxiv.org/abs/1911.02116) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/facebookresearch/XLM) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * [Hugging Face 🤗](https://huggingface.co/xlm-roberta-base)
* M2M-100
  * [Beyond English-Centric Multilingual Machine Translation](https://arxiv.org/abs/2010.11125) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github page](https://github.com/facebookresearch/fairseq/blob/main/examples/m2m_100/README.md) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * [Hugging Face 🤗](https://huggingface.co/facebook/m2m100_418M)
* Blender
  * [Recipes for building an open-domain chatbot](https://arxiv.org/abs/2004.13637) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [Internet-Augmented Dialogue Generation](https://arxiv.org/abs/2107.07566) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [Beyond Goldfish Memory: Long-Term Open-Domain Conversation](https://arxiv.org/abs/2107.07567) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/facebookresearch/ParlAI) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * [Hugging Face 🤗](https://huggingface.co/facebook/blenderbot-3B)
* OPT
  * [OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/abs/2205.01068) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/facebookresearch/metaseq) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * [Hugging Face 🤗](https://huggingface.co/facebook/opt-350m)
  * [Request access to OPT-175B](https://docs.google.com/forms/d/e/1FAIpQLSe4IP4N6JkCEMpCP-yY71dIUPHngVReuOmQKDEI1oHFUaVg7w/viewform)
* NLLB 
  * [No Language Left Behind: Scaling Human-Centered Machine Translation](https://scontent-lax3-1.xx.fbcdn.net/v/t39.8562-6/292295068_402295381932691_8903854229220968087_n.pdf?_nc_cat=102&ccb=1-7&_nc_sid=ad8a9d&_nc_ohc=hNcSHrgRXoYAX-c47WB&_nc_ht=scontent-lax3-1.xx&oh=00_AT9viWtexbgbbP0pFK0fotG86Hoj-9rvkkCVV8aC38ifZw&oe=62F21993) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/facebookresearch/fairseq/tree/nllb/) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * [Hugging Face 🤗](https://huggingface.co/facebook/nllb-200-distilled-600M)

## Fudan University

* CPT
  * [CPT: A Pre-Trained Unbalanced Transformer for Both Chinese Language Understanding and Generation](https://arxiv.org/abs/2109.05729) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/fastnlp/CPT) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white) 

## Google

* T5 family
  * T5 series 
    * [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * [GLU Variants Improve Transformer](https://arxiv.org/abs/2002.05202) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * [github repo](https://github.com/google-research/text-to-text-transfer-transformer) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * [Hugging Face 🤗](https://huggingface.co/t5-base)
  * ByT5 
    * [ByT5: Towards a token-free future with pre-trained byte-to-byte models](https://arxiv.org/abs/2105.13626) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * [github repo](https://github.com/google-research/byt5) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * [Hugging Face 🤗](https://huggingface.co/google/byt5-base)
  * ExT5
    * [ExT5: Towards Extreme Multi-Task Scaling for Transfer Learning](https://arxiv.org/abs/2111.10952) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * LongT5
    * [LongT5: Efficient Text-To-Text Transformer for Long Sequences](https://arxiv.org/abs/2112.07916) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * [github repo](https://github.com/google-research/longt5) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * [Hugging Face 🤗](https://huggingface.co/google/long-t5-local-base)
* LaMDA
  * [LaMDA: Language Models for Dialog Applications](https://arxiv.org/abs/2201.08239) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/conceptofmind/LaMDA-pytorch) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white) (Non-offical)
* FLAN 
  * [Finetuned Language Models Are Zero-Shot Learners](https://arxiv.org/abs/2109.01652) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/google-research/FLAN) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
* GShard 
  * [GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding](https://arxiv.org/abs/2006.16668) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
* Meena
  * [Towards a Human-like Open-Domain Chatbot](https://arxiv.org/abs/2001.09977) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/frankplus/meena-chatbot) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white) (Non-offical)
* PaLM 
  * [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/abs/2204.02311) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/lucidrains/PaLM-pytorch) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white) (Non-offical)
* UL2 
  * [Unifying Language Learning Paradigms](https://arxiv.org/abs/2205.05131) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/google-research/google-research/tree/master/ul2) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * [Hugging Face 🤗](https://huggingface.co/google/ul2)
* Minerva 
  * [Solving Quantitative Reasoning Problems with Language Models](https://arxiv.org/abs/2206.14858) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [Minerva SAMPLE EXPLORER](https://minerva-demo.github.io/#category=Algebra&index=1) ![demo](https://img.shields.io/badge/-demo-blue?style=flat)



## HIT & iFLYTEK


* PERT:
  * [PERT: Pre-training BERT with Permuted Language Model](https://arxiv.org/abs/2203.06906) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/ymcui/PERT) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)


>  [哈工大讯飞联合实验室: Joint Laboratory of HIT and iFLYTEK Research (HFL)](https://hfl-rc.com/).




## Huawei

* PanGu (盘古) family 
  * PanGu-Alpha 
    * [PanGu-α: Large-scale Autoregressive Pretrained Chinese Language Models with Auto-parallel Computation](https://arxiv.org/abs/2104.12369) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * [启智 AI协作平台](https://git.openi.org.cn/PCL-Platform.Intelligence/PanGu-Alpha) ![website](https://img.shields.io/badge/-website-9cf?style=flat)
  * PanGu-Bot
    * [PanGu-Bot: Efficient Generative Dialogue Pre-training from Pre-trained Language Model](https://arxiv.org/abs/2203.17090) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * PanGu-Coder
    * [PanGu-Coder: Program Synthesis with Function-Level Language Modeling](https://arxiv.org/abs/2207.11280) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
* NEZHA (哪吒) 
  * [NEZHA: Neural Contextualized Representation for Chinese Language Understanding](https://arxiv.org/abs/1909.00204) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)


> [Huawei-Noah offical github repo for Pretrained-Language Model](https://github.com/huawei-noah/Pretrained-Language-Model). ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

## Inspur

* Yuan 1.0 
  * [Yuan 1.0: Large-Scale Pre-trained Language Model in Zero-Shot and Few-Shot Learning](https://arxiv.org/abs/2110.04725) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/Shawn-Inspur/Yuan-1.0) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)




## IDEA

* [封神榜——中文语言预训练模型开源计划](https://fengshenbang-doc.readthedocs.io/zh/latest/index.html) ![website](https://img.shields.io/badge/-website-9cf?style=flat)
  * Erlangshen (二郎神)
  * Wenzhong (闻仲)
  * Rangdeng (燃灯)
  * Yuyuan (余元)
  * Bigan (比干)
  * Zhouwenwang (周文王)
  * Taiyi (太乙)

> IDEA refers to [粤港澳大湾区数字经济研究院](https://idea.edu.cn/).

## JD (JINGDONG)

* 织女 Vega v1

## Langboat

* Mengzi
  * [Mengzi: Towards Lightweight yet Ingenious Pre-trained Models for Chinese](https://arxiv.org/abs/2110.06696) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/Langboat/Mengzi) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

## Microsoft

* Megatron-Turning NLG family 
* DeBERTa series 
  * [DeBERTa: Decoding-enhanced BERT with Disentangled Attention](https://arxiv.org/abs/2006.03654) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [DeBERTaV3: Improving DeBERTa using ELECTRA-Style Pre-Training with Gradient-Disentangled Embedding Sharing](https://arxiv.org/abs/2111.09543)
  * [github repo](https://github.com/microsoft/DeBERTa) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * [Hugging Face 🤗](https://huggingface.co/microsoft/deberta-base)
* DeepNMT
  * [Very Deep Transformers for Neural Machine Translation](https://arxiv.org/abs/2008.07772)
  * [github repo](https://github.com/microsoft/deepnmt) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
* DeepNet 
  * [DeepNet: Scaling Transformers to 1,000 Layers](https://arxiv.org/abs/2203.00555) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
* GODEL
  * [GODEL: Large-Scale Pre-Training for Goal-Directed Dialog](https://www.microsoft.com/en-us/research/uploads/prod/2022/05/2206.11309.pdf) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/microsoft/GODEL) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
* METRO
  * [METRO: Efficient Denoising Pretraining of Large Scale Autoencoding Language Models with Model Generated Signals](https://arxiv.org/abs/2204.06644)


## Nvidia

* Megatron-LM 
  * [Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/abs/1909.08053) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/NVIDIA/Megatron-LM) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

## OpenAI

* GPT-family
  * GPT, GPT-2, GPT-3  
    * GPT: [Improving Language Understanding by Generative Pre-Training](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * GPT-2: [Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language-models.pdf) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * GPT-3: [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
    * [GPT-2 github repo](https://github.com/openai/gpt-2) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * [GPT-2 Hugging Face 🤗](https://huggingface.co/gpt2)
  * WebGPT
    * [WebGPT: Browser-assisted question-answering with human feedback](https://arxiv.org/abs/2112.09332) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * InstructGPT
    * [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
* Codex 
  * [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)


## OPPO

* OBERT 

## Tencent

* Motian (摩天)
* ShenZhou (神舟)
* ShenNonG (神农)
* HunYuan  (混元)

## THU (Tsinghua) & BAAI (Beijing)

* THUDM
  * Wenhui (文汇)
    * [github repo](https://github.com/THUDM/Chinese-Transformer-XL) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
  * GLM-130B
    * [github repo](https://github.com/THUDM/GLM-130B) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * [demo for GLM-130B](https://huggingface.co/spaces/THUDM/GLM-130B) ![demo](https://img.shields.io/badge/-demo-blue?style=flat)



> THUDM refers to "Data Mining Research Group at Tsinghua University".

* Tsinghua AI
  * ERNIE
    * [ERNIE: Enhanced Language Representation with Informative Entities](https://arxiv.org/abs/1905.07129) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * CPM family
    * CPM-1
      * [CPM: A Large-scale Generative Chinese Pre-trained Language Model](https://arxiv.org/abs/2012.00413) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github repo](https://github.com/TsinghuaAI/CPM-1-Generate) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * CPM-2
      * [CPM-2: Large-scale cost-effective pre-trained language models](https://www.sciencedirect.com/science/article/pii/S2666651021000310) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github repo](https://github.com/TsinghuaAI/CPM-2-Pretrain) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
      * [启智 AI协作平台](https://git.openi.org.cn/BAAI/WuDao-Model/src/branch/master/CPM) ![website](https://img.shields.io/badge/-website-9cf?style=flat)


* THU-CoAI
  * EVA family
    * EVA 1.0 
      * [EVA: An Open-Domain Chinese Dialogue System with Large-Scale Generative Pre-Training](https://arxiv.org/abs/2108.01547) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github project](https://github.com/thu-coai/EVA) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * EVA 2.0  
      * [EVA2.0: Investigating Open-Domain Chinese Dialogue Systems with Large-Scale Pre-Training](https://arxiv.org/abs/2203.09313) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github project](https://github.com/thu-coai/EVA)  ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

> THU-CoAI refers to "Conversational AI groups from Tsinghua University".

* BAAI
  * Chinese-Transformer-XL 
    * [github repo](https://github.com/THUDM/Chinese-Transformer-XL) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
    * [启智 AI协作平台](https://git.openi.org.cn/BAAI/WuDao-Model/src/branch/master/Transformer-XL) ![website](https://img.shields.io/badge/-website-9cf?style=flat)
  * GLM 
    * [GLM: General Language Model Pretraining with Autoregressive Blank Infilling](https://arxiv.org/abs/2103.10360)
    * [启智 AI协作平台](https://git.openi.org.cn/BAAI/WuDao-Model/src/branch/master/GLM) ![website](https://img.shields.io/badge/-website-9cf?style=flat)


## More PLMs are  coming ...

🔥Coming soon!🔥

--- 

# Claims

Thanks for all these companies and orgnizations paying a lot of money and efforts to build and train these large models for the benefit of all human beings. 

> This repo is inspired by [awesome pretrained Chinese NLP models](https://github.com/lonePatient/awesome-pretrained-chinese-nlp-models).
