---
title: 'SemGAN: Text to Image Synthesis from Text Semantics using Attentional Generative Adversarial Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ammar Khairi
  - Ruba Mutasim
  - Hiba Imam

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2021-02-26T00:00:00Z'
doi: '10.1109/ICCCEEE49695.2021.9429602'

# Schedule page publish date (NOT publication's date).
publishDate: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication:  2020 International Conference on Computer, Control, Electrical, and Electronics Engineering (ICCCEEE)
publication_short: In *ICCCEEE2020*

abstract: Text to Image Synthesis is the procedure of automatically creating a realistic image from a particular text description. There are numerous innovative and practical applications for text to image synthesis, including image processing and compute-raided design. Using Generative Adversarial Networks (GANs) alongside the Attention mechanism has led to huge improvements lately. The fine-grained attention mechanism, although powerful, does not preserve the general description information well in the generator since it only attends to the text description at word-level (fine-grained). We propose incorporating the whole sentence semantics when generating images from captions to enhance the attention mechanism outputs. According to experiments, on our model produces more robust images with a better semantic layout. We use the Caltech birds dataset to run experiments on both models and validate the effectiveness of our proposal. Our model boosts the original AttnGAN Inception score by +4.13% and the Fréchet Inception Distance score by +13.93%. Moreover, an empirical analysis is carried out on the objective and subjective measures to (i) address and overcome the limitations of these metrics (ii) verify that performance improvements are due to fundamental algorithmic changes rather than initialization and fine-tuning as with GANs models.

# Summary. An optional shortened abstract.
summary:  We use the Caltech birds dataset to run experiments on both models and validate the effectiveness of our proposal. Our model boosts the original AttnGAN Inception score by +4.13% and the Fréchet Inception Distance score by +13.93%.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Demo
  url: https://huggingface.co/spaces/ammarnasr/Sem-GAN-Bird-Image-Generator

url_pdf: 'https://github.com/ammarnasr/pdfs/blob/main/SemGAN_Text_to_Image_Synthesis_from_Text_Semantics_using_Attentional_Generative_Adversarial_Networks.pdf'
url_code: 'https://github.com/ammarnasr/SEM-GAN-WebAPP'
url_dataset: 'https://www.vision.caltech.edu/datasets/cub_200_2011/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image Taken from the paper'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
