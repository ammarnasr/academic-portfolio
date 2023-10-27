---
title: Scaling Down Multi-Lingual Code Language Models

summary: This project fine-tuned compact monolingual code language models to new programming languages using efficient techniques, with the goal of expanding capabilities and accessibility of code intelligence tools. The work shares insights from optimizing training efficiency and makes models/datasets publicly available to further AI democratization.

tags:
  - Deep Learning
  - Natural Language Processing
  - Code Generation
  - PyTorch
  - HuggingFace
  - LLM
  - Large Language Models
  - Democratisation of AI

date: '2023-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Screen Shot of the Code Generation with Language-Specific LoRa Models HuggingFace Space
  focal_point: Smart

links:
  - icon: huggingface
    icon_pack: fab
    name: Demo
    url: https://huggingface.co/spaces/ammarnasr/Code-Generation-with-Language-Specific-LoRa-Models
url_code: 'https://github.com/ammarnasr/LLM-for-code-intelligence'
url_pdf: 'https://github.com/ammarnasr/LLM-for-code-intelligence/blob/main/ammar_dissertation.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

The democratisation of AI and access to code language models have become pivotal goals in the field of artificial intelligence. Large Language Models (LLMs) have shown exceptional capabilities in code intelligence tasks, but their accessibility remains a challenge due to computational costs and training complexities. This paper addresses these challenges by presenting a comprehensive approach to scaling down Code Intelligence LLMs. To enhance usability, we focus on training smaller code language models, which lowers the computation cost of inference and training. We extend these models to diverse programming languages, enabling code completion tasks across various domains 

Additionally, we explore the impact of different choices in fine-tuning LLMs, providing empirical evidence on training efficiency in terms of time, cost, and performance. In pursuit of these goals, we fine-tune a Python-based mono-lingual code LLM for Java, Rust, Ruby, and Swift. Utilising the LoRa Parameter Efficient Fine-Tuning technique, we share these models, their training datasets, and evaluation results openly. Extensive hyperparameter tuning, trade-off analysis, and error analysis shed light on the effects of training process choices. This work contributes to the democratisation of AI by making Code LLMs more accessible and usable for practitioners. By addressing computational barriers and providing insights into training dynamics, we bridge the gap between AI development and practical application, fostering an environment where code intelligence tools can be readily adopted.

