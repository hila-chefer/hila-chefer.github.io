---
title: "Generic Attention-model Explainability for Interpreting Bi-Modal and Encoder-Decoder Transformers (Oral)"
authors:
- Hila Chefer
- Shir Gur
- Lior Wolf
date: "2021-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF International Conference on Computer Vision (ICCV)
publication_short: In *ICCV*

abstract: "Transformers are increasingly dominating multi-modal reasoning tasks, such as visual question answering, achieving state-of-the-art results thanks to their ability to contextualize information using the self-attention and co-attention mechanisms. These attention modules also play a role in other computer vision tasks including object detection and image segmentation. Unlike Transformers that only use self-attention, Transformers with co-attention require to consider multiple attention maps in parallel in order to highlight the information that is relevant to the prediction in the model's input. In this work, we propose the first method to explain prediction by any Transformer-based architecture, including bi-modal Transformers and Transformers with co-attentions. We provide generic solutions and apply these to the three most commonly used of these architectures: (i) pure self-attention, (ii) self-attention combined with co-attention, and (iii) encoder-decoder attention. We show that our method is superior to all existing methods which are adapted from single modality explainability."

# Summary. An optional shortened abstract.
summary: The paper presents an interpretability method for all types of attention, including bi-modal Transformers and encoder-decoder Transformers. The method achieves SOTA results for CLIP, DETR, LXMERT, and more.

tags:
- Explainability
- Transformers
- CLIP
- DETR
- LXMERT
- VisualBERT
- Cross-Attention
- Encoder-Decoder
featured: false

#links:
url_pdf: https://openaccess.thecvf.com/content/ICCV2021/papers/Chefer_Generic_Attention-Model_Explainability_for_Interpreting_Bi-Modal_and_Encoder-Decoder_Transformers_ICCV_2021_paper.pdf
#- name: ""
#   url: ""
 
url_code: 'https://github.com/hila-chefer/Transformer-MM-Explainability'
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
