---
title: Knowledge-Based QA System
summary: The system utilizes state-of-the-art natural language processing techniques like BERT (Bidirectional Encoder Representations from Transformers) to understand the user's question and find the best matching question-answer pair. Fine-tuning BERT on domain-specific data allows the system to become adept at understanding queries in a particular domain.
tags:
  - Deep Learning
  - NLP
  - Multilingual
  - Knowledge-Based QA
  - Deployment
  - Software Development

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
    url: 'https://knowledge-based-app.streamlit.app/'
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
## Knowledge-Based Question Answering System

I led the development of an intelligent question answering system that can understand natural language questions posed by users and provide accurate answers by matching the questions to the most similar ones from a database. 

The project was funded through the Existing AI Services Round 2 with the goal of building an affordable knowledge-based conversational AI service for small and medium businesses. My responsibilities included:

- Researching state-of-the-art natural language processing techniques for question answering
- Training a BERT model on a large Arabic text corpus for language understanding 
- Fine-tuning the BERT model on domain-specific question-answer datasets
- Implementing parallel training techniques using adapters to allow low-cost retraining
- Creating an API endpoint for the QA system
- Incorporating the service into an existing conversational AI platform

### Technical Details

The system is built using PyTorch and the Transformers library. I pretrained a BERT model on 15 million sentences of Arabic text data scraped from public sources. This teaches the model to understand Arabic language. 

I then implemented a semantic similarity fine-tuning method to train BERT on domain-specific question-answer pairs. This tunes the model to match and rank questions based on similarity.

To optimize costs, I researched and applied adapter modules which allow parallel training of BERT on multiple domains. This enables low-cost retraining for new customers.

The trained QA model is served through a REST API built with Flask. Users can send questions as JSON and get back relevant answers. The API is incorporated into a full conversational platform.

### Impact

This project makes state-of-the-art natural language processing accessible to small businesses as an AI service. It provides them with an intelligent conversational agent that can answer customers' questions accurately and in a personalized manner. 

Over 15 businesses are already using the QA system to improve customer satisfaction and increase sales opportunities. The adapters technique has brought down the cost of retraining by 5x.

By leading this complex AI project from research to deployment, I demonstrated expertise in natural language processing, deep learning, and productionizing AI systems. The project added valuable new capabilities to a commercial platform.