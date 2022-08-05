# Awesome Pretrained Language Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


Pretrained Language Models (PLMs) have been achieved great success over  many NLP tasks. And with the rapid development of PLMs, there is a need to make a list to show these succesful and remarkable language models.


#  Lists of Language Models

Group by companies and organizations.

  * [Alibaba](#alibaba)
  * [Amazon](#amazon)
  * [Baidu](#baidu)
  * [BigSicence](#bigsicence)
  * [DeepMind](#deepmind)
  * [EleutherAI](#eleutherai)
  * [Facebook (Meta)](#facebook-meta)
  * [Fudan University](#fudan-university)
  * [Google](#google)
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


## Alibaba 

* PLUG
  *  [超大规模中文生成](https://nlp.aliyun.com/portal#/plug) ![demo](https://img.shields.io/badge/-demo-blue?style=flat)

## Amazon 

* Alexa Teacher Model 
  * [Alexa Teacher Model: Pretraining and Distilling Multi-Billion-Parameter Encoders for Natural Language Understanding Systems](https://arxiv.org/abs/2206.07808) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * AlexaTM 20B
    * [AlexaTM 20B: Few-Shot Learning Using a Large-Scale Multilingual Seq2Seq Model](https://arxiv.org/abs/2208.01448)  ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/amazon-research/alexa-teacher-models)![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)
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
* BLOOM 


 

 
## DeepMind 

* Gopher 
* Chinchilla
* AlphaCode 
* Retro


 
## EleutherAI

* GPT-Neo
* GPT-J
* GPT-NeoX 


 
## Facebook (Meta)

* XGLM
* MOE LM 
* XLM-R 
* M2M-100
* Blender
* OPT
* NLLB 

## Fudan University

* CPT
  *   [CPT: A Pre-Trained Unbalanced Transformer for Both Chinese Language Understanding and Generation](https://arxiv.org/abs/2109.05729) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  *  [github repo](https://github.com/fastnlp/CPT) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

 
## Google 

* T5 family
  * T5 series 
  * ByT5 
  * ExT5 
* LaMDA 
* FLAN 
* GShard 
* Meena
* PaLM 
* UL2 
* Minerva 


 
## Huawei 

* PanGu (盘古) family 
  * PanGu-Alpha 
  * PanGu-Coder
* NEZHA (哪吒) 


 
## Inspur 

* Yuan 1.0 

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
* Turning NLG 
* DeepNet 
* GODEL 
* Metro-LM 
* Z-code M3 


 
## Nvidia

* Megatron-LM 
  * [Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/abs/1909.08053) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * [github repo](https://github.com/NVIDIA/Megatron-LM) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)



 
## OpenAI

* GPT-family
  * GPT, GPT-2, GPT-3  
  * WebGPT
  * InstructGPT
* Codex 

 
## OPPO


* OBERT 






 
## Tencent 


* Motian 
* ShenZhou 
* ShenNonG
* TI-NLP
* HunYuan_nlp  


 
## THU (Tsinghua) & BAAI (Beijing)

* THUDM
  * Wenhui (文汇)
    * [github repo](https://github.com/THUDM/Chinese-Transformer-XL) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)


> THUDM refers to "Data Mining Research Group at Tsinghua University".
 
* Tsinghua AI
  * ERNIE
    * [ERNIE: Enhanced Language Representation with Informative Entities](https://arxiv.org/abs/1905.07129) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
  * CPM family
    * CPM-1
      * [CPM: A Large-scale Generative Chinese Pre-trained Language Model](https://arxiv.org/abs/2012.00413) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github repo](https://github.com/TsinghuaAI/CPM-1-Generate) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

    * CPM-2
      *  [CPM-2: Large-scale cost-effective pre-trained language models](https://www.sciencedirect.com/science/article/pii/S2666651021000310) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github repo](https://github.com/TsinghuaAI/CPM-2-Pretrain) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)


* THU-CoAI
  * EVA family
    * EVA 1.0 
      *  [EVA: An Open-Domain Chinese Dialogue System with Large-Scale Generative Pre-Training](https://arxiv.org/abs/2108.01547) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github project](https://github.com/thu-coai/EVA) ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

    * EVA 2.0 
      *  [EVA2.0: Investigating Open-Domain Chinese Dialogue Systems with Large-Scale Pre-Training](https://arxiv.org/abs/2203.09313) ![paper](https://img.shields.io/badge/-paper-lightgrey?style=flat)
      * [github project](https://github.com/thu-coai/EVA)  ![github](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)

    
> THU-CoAI refers to "Conversational AI groups from Tsinghua University".



* BAAI
  * Chinese-Transformer-XL 
  * CPM family
    * CPM-1 
    * CPM-2 
  * GLM 

## More PLMs are  coming ...

🔥Coming soon!🔥


--- 

# Claims 

Thanks for all these companies and orgnizations paying a lot of money and efforts to build and train these large models for the benefit of all human beings. 


> This repo is inspired by [awesome pretrained Chinese NLP models](https://github.com/lonePatient/awesome-pretrained-chinese-nlp-models).


