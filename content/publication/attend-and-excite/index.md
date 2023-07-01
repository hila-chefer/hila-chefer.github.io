---
title: "Attend-and-Excite: Attention-Based Semantic Guidance for Text-to-Image Diffusion Models"
authors:
- Hila Chefer*
- Yuval Alaluf*
- Yael Vinker
- Lior Wolf
- Daniel Cohen-Or 
date: "2023-01-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ACM SIGGRAPH (SIGGRAPH)
publication_short: In *SIGGRAPH*

abstract: "Recent text-to-image generative models have demonstrated an unparalleled ability to generate diverse and creative imagery guided by a target text prompt. While revolutionary, current state-of-the-art diffusion models may still fail in generating images that fully convey the semantics in the given text prompt. We analyze the publicly available Stable Diffusion model and assess the existence of catastrophic neglect, where the model fails to generate one or more of the subjects from the input prompt. Moreover, we find that in some cases the model also fails to correctly bind attributes (e.g., colors) to their corresponding subjects. To help mitigate these failure cases, we introduce the concept of Generative Semantic Nursing (GSN), where we seek to intervene in the generative process on the fly during inference time to improve the faithfulness of the generated images. Using an attention-based formulation of GSN, dubbed Attend-and-Excite, we guide the model to refine the cross-attention units to attend to all subject tokens in the text prompt and strengthen - or excite - their activations, encouraging the model to generate all subjects described in the text prompt. We compare our approach to alternative approaches and demonstrate that it conveys the desired concepts more faithfully across a range of text prompts."

# Summary. An optional shortened abstract.
summary: The paper presents a method to guide text-to-image diffusion models to generate all subjects in the input prompt, to mitigate subject neglect. This is achieved by defining an intuitive loss over the cross-attention maps during inference without any additional data or fine-tuning.

tags:
- Stable Diffusion
- Attention
- Semantic Guidance
featured: false
featured: false

links:
- name: Project page
  url: https://attendandexcite.github.io/Attend-and-Excite/
- name: HuggingFace demo
  url: https://huggingface.co/spaces/AttendAndExcite/Attend-and-Excite
url_pdf: https://arxiv.org/abs/2301.13826
url_code: 'https://github.com/yuval-alaluf/Attend-and-Excite'
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

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}
