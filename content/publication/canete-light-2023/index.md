---
title: "Light and Fast Language Models for Spanish Through Compression Techniques"
date: 2023-01-01
publishDate: 2023-04-18T22:08:23.748893Z
authors:
    - admin
publication_types: ["1"]
abstract: "
Large language models (LLMs) have become a prevalent and successful approach to address natural language processing (NLP) tasks, including but not limited to document classifica- tion, named-entity recognition, and question answering. Despite their remarkable perfor- mance, utilizing these LLMs on constrained resources, such as web or mobile applications, is challenging, particularly in real-time scenarios that demand fast responses. Techniques to compress these LLM into smaller and fastest models have emerged for English or Multilingual settings, but it is still a challenge for other languages. In fact, Spanish is the second language with most native speakers but lacks of these kind of resources.
In this work, we present ALBETO and Speedy Gonzales, two new resources for the Spanish NLP community that aim to bridge the gap in terms of lighter and faster models for Spanish. ALBETO is a set of 5 lightweight models, with sizes ranging from 5M to 223M parameters, that are pre-trained exclusively on Spanish corpora following the ALBERT architecture. We evaluate our ALBETO models along with other publicly available models for Spanish on a set of 6 tasks and then, by leveraging on Knowledge Distillation (KD), we present Speedy Gonzales, a collection of more inference-efficient task-specific language models based on ALBETO.
The outcomes of our study reveal that our ALBETO models perform at a similar level to other models with comparable inference speed, despite being lighter in weight and having substantially fewer parameters. Moreover, our ALBETO xxlarge model outperforms all other pre-trained Spanish models that are currently available.
Regarding our Speedy Gonzales models, the results indicate an enhancement in inference speed at the expense of a slight decline in task performance. Notably, this decay is minimal in the case of our 8 and 10 layer models, while it is more pronounced in the faster models with 2-4 layers. Moreover, our 10-layer model, referred to as ALBETO base-10, delivers performance that is generally comparable to base-sized models, while also demonstrating improved inference speed.
All of our models (pre-trained, fine-tuned and distilled) are publicly available on: https://huggingface.co/dccuchile."
featured: false
publication: "Universidad de Chile"
url_pdf: https://repositorio.uchile.cl/handle/2250/196742
# url_code: https://github.com/OpenCENIA/Spanish-Sentence-Evaluation
# url_slides: 
# url_video:

# links:
# - name: arXiv
#   url: https://arxiv.org/abs/2204.07571
---

