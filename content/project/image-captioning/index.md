---
title: Multilingual Image Captioning
summary: Used Pretrained CLIP image encoder and GPT-2 Language Model to build a multilingual image captioning system on English, Arabic, French, and Deutsch. The system was trained on 1.5M images and 4.5M captions from the Multi30K dataset, with 4 prefix adapters each on a specific language. The system was able to generate captions in the four languages with high accuracy.
tags:
  - Deep Learning
  - NLP
  - Computer Vision
  - Multilingual
  - Multimodal

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
    url: ''
url_code: 'https://github.com/ammarnasr/Multi-Lingual-Image-Captioning'
url_pdf: 'https://github.com/ammarnasr/pdfs/blob/main/MultiLingual_captioner.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: code-llm
---

This project started as an assignment for a course in my MSc program, where we initially decided to benchmark different image-to-text (image captioning) systems in four different languages (English, Arabic, French, and Deutsch) as it was never done before. We used two types of encoders (CNN and CLIP) and two types of decoders (LSTM and GPT2 with Adapters), we trained multiple models using a combination of those types and benchmarked on Crossmodal-3600 (paper coming soon).

After that we decided to push it a step further by developing the first multilingual captioning system on the above-mentioned languages, we used CLIP as an encoder for the images and trained GPT2 with four adapters each on a specific language, although the Mcaptioner gave decent results but the quality of the generated text varied massively between the four languages depending on the type of GPT2 model used (the English GPT2 would give inferior results in other languages), to fix this our next step is to try to train on a multilingual GPT2 model or an adaptation of the original GPT2 for different models.

