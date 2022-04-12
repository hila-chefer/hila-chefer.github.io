---
title: "No Token Left Behind: Explainability-Aided Image Classification and Generation"
authors:
- Roni Paiss
- Hila Chefer
- Lior Wolf
date: "2022-04-11T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: IEEE/CVF International Conference on Computer Vision (ICCV)
# publication_short: In *ICCV*

abstract: "The application of zero-shot learning in computer vision has been revolutionized by the use of image-text matching models. The most notable example, CLIP, has been widely used for both zero-shot classification and guiding generative models with a text prompt. However, the zero-shot use of CLIP is unstable with respect to the phrasing of the input text, making it necessary to carefully engineer the prompts used. We find that this instability stems from a selective similarity score, which is based only on a subset of the semantically meaningful input tokens. To mitigate it, we present a novel explainability-based approach, which adds a loss term to ensure that CLIP focuses on all relevant semantic parts of the input, in addition to employing the CLIP similarity loss used in previous works. When applied to one-shot classification through prompt engineering, our method yields an improvement in the recognition rate, without additional training or fine-tuning. Additionally, we show that CLIP guidance of generative models using our method significantly improves the generated images. Finally, we demonstrate a novel use of CLIP guidance for text-based image generation with spatial conditioning on object location, by requiring the image explainability heatmap for each object to be confined to a pre-determined bounding box."

# Summary. An optional shortened abstract.
summary: The paper presents a novel use of explainability to perform zero-shot tasks such as image classification and generation. We demonstrate that CLIP guidance based on pure similarity scores between the image and text is unstable as the scores can be based on irrelevant or partial data. Our method demonstrates the effectiveness of using explainability to stabilize the scores.
# We show significant improvement using our method for image classification via improved prompt engineering, as well as text-conditioned image editing and generation. 

tags:
- Explainability
- Transformers
- CLIP
featured: false

links:
url_pdf: https://arxiv.org/abs/2204.04908
# url_code: 'https://github.com/hila-chefer/Transformer-MM-Explainability'
#- name: ""
#   url: ""
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
