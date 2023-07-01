---
title: "The Hidden Language of Diffusion Models"
authors:
- Hila Chefer
- Oran Lang
- Mor Geva
- Volodymyr Polosukhin 
- Assaf Shocher
- Michal Irani
- Inbar Mosseri
- Lior Wolf
date: "2023-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

## Publication name and optional abbreviated publication name.
#publication: Conference on Neural Information Processing Systems (NeurIPS)
#publication_short: In *NeurIPS*

abstract: Text-to-image diffusion models have demonstrated an unparalleled ability to generate high-quality, diverse images from a textual concept (e.g., "a doctor", "love"). However, the internal process of mapping text to a rich visual representation remains an enigma. In this work, we tackle the challenge of understanding concept representations in text-to-image models by decomposing an input text prompt into a small set of interpretable elements. This is achieved by learning a pseudo-token that is a sparse weighted combination of tokens from the model's vocabulary, with the objective of reconstructing the images generated for the given concept. Applied over the state-of-the-art Stable Diffusion model, this decomposition reveals non-trivial and surprising structures in the representations of concepts. For example, we find that some concepts such as "a president" or "a composer" are dominated by specific instances (e.g., "Obama", "Biden") and their interpolations. Other concepts, such as "happiness" combine associated terms that can be concrete ("family", "laughter") or abstract ("friendship", "emotion"). In addition to peering into the inner workings of Stable Diffusion, our method also enables applications such as single-image decomposition to tokens, bias detection and mitigation, and semantic image manipulation.

# Summary. An optional shortened abstract.
summary: This paper presents a novel interpretability method for text-to-image diffusion models. The method uses the model's textual space to explain how diverse images are generated from text prompts. Given a textual concept (e.g., "a president"), the method generates exemplar images from the model, and learns to decompose the concept into a small set of interpretable tokens from the model's vocabulary, uncovering intriguing semantic connection, biases, and more. 

tags:
- Explainability
- Interpretability
- Diffusion Models 
- Stable Diffusion
- Concept Decomposition
featured: true

links:
- name: Project page
  url: https://hila-chefer.github.io/Conceptor/
url_pdf: https://arxiv.org/abs/2306.00966
url_code: 'https://github.com/hila-chefer/Conceptor'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

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
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

[comment]: <> (![]&#40;featured.png&#41;)