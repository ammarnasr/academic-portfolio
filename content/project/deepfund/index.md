---
title: Knowledge-Based QA System
summary: Our proposal was awarded $20,000 to update Enigma knowledge-based question answering service by applying adapters which makes the service scalable and more affordable to small businesses. I was responsible for the research and development of the adapters.
tags:
  - Deep Learning
  - NLP
  - Multilingual
  - Knowledge-Based QA
  - Deployment

date: '2023-04-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Screen Shot of the Code Generation with Language-Specific LoRa Models HuggingFace Space
  focal_point: Smart

links:
  # - icon: huggingface
  #   icon_pack: fab
  #   name: Demo
  #   url: ''
url_code: 'https://github.com/mukhtar-algezoli/DeepFunding_project'
url_pdf: 'https://deepfunding.ai/proposal/knowledge-based-question-answering-system/'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This service is an extension to an already running service on Enigma AI platform (https://platform.enigma-ai.com/), It is intended to work as a knowledge-based question-answering system, i.e., the customer would ask a question and the service (chatbot) will try matching the question with the most similar question from a database (containing question-answer pairs) then the answer (or flow branch) for this chosen question is returned. We have done this by utilizing the State-Of-The_Art model in Natural Language understanding called BERT (https://arxiv.org/abs/1810.04805 ) which is usually trained in two steps: First pretraining in a big dataset in a specific language and since we are currently operating on a region with mostly Arabic speakers (Sudanese dialect) we collected around 15 million sentences from Twitter, Facebook, Books, and news sites and pretrained BERT on this data until it became proficiently able to understand. The second step is fine-tuning where the model is trained on domain-specific data using a task that we developed called semantic similarity, currently, this step should be done for each new customer (which takes a long time) and a version of the model should always be loaded in memory, because of these two issues this intelligent AI model is only available to premium customers (like Banks, Telecom companies,...etc) and not available to everybody on our Saas platform (https://platform.enigma-ai.com/).
