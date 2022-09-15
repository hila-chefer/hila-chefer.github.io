---
title: "Optimizing Relevance Maps of Vision Transformers Improves Robustness"
authors:
- Hila Chefer
- Idan Schwartz
- Lior Wolf
date: "2022-11-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-20T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: IEEE/CVF International Conference on Computer Vision (ICCV)
# publication_short: In *NeurIPS*

abstract: "It has been observed that visual classification models often rely mostly on the image background, neglecting the foreground, which hurts their robustness to distribution changes. To alleviate this shortcoming, we propose to monitor the model's relevancy signal and manipulate it such that the model is focused on the foreground object. This is done as a finetuning step, involving relatively few samples consisting of pairs of images and their associated foreground masks. Specifically, we encourage the model's relevancy map (i) to assign lower relevance to background regions, (ii) to consider as much information as possible from the foreground, and (iii) we encourage the decisions to have high confidence. When applied to Vision Transformer (ViT) models, a marked improvement in robustness to domain shifts is observed. Moreover, the foreground masks can be obtained automatically, from a self-supervised variant of the ViT model itself; therefore no additional supervision is required."

# Summary. An optional shortened abstract.
summary: Vision models are known to use "shortcuts" in the data, i.e. use irrelevant cues, such as the image background, to achieve high accuracy. For example, since snowplows often co-occur with snow, a model may learn to classify any vehicle in the snow as a snowplow. In this work, we show that using a very short and simple *few-shot* finetuning process on the relevance maps of a Vision Transformer, we can teach the model *why* the label is correct, and enforce that the predictions are based on the *right* reasons. We demonstrate a significant improvement in the robustness of the Vision Transformers (ViTs) to distribution shifts.  

tags:
- Explainability
- Transformers
- Vision Transformer
- ImageNet
- Robustness

featured: false

links:
- name: Gradio demo
  url: https://huggingface.co/spaces/Hila/RobustViT
url_pdf: https://arxiv.org/abs/2206.01161
url_code: 'https://github.com/hila-chefer/RobustViT'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
