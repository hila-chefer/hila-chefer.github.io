---
title: "Image-Based Clip-Guided Essence Transfer"
authors:
- Hila Chefer
- Sagie Benaim
- Roni Paiss
- Lior Wolf
date: "2021-10-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "CLIP is trained on a large corpus of matched images and text captions and is, therefore, much richer semantically than networks that perform multiclass classification for a limited number of classes only. It has been shown to be extremely suitable for zero-shot computer vision tasks; here, we demonstrate its ability to support semantic blending. While the StyleGAN space already performs reasonable blending for images of, e.g., two children, it struggles when blending images with different attributes. On the other hand, CLIP by itself struggles to maintain identity when blending. The combination of the two seems to provide a powerful blending technique, which enjoys the benefits of both representations. This is enabled through a novel method, which assumes additivity in the first latent space and ensures additivity in the second through optimization."

# Summary. An optional shortened abstract.
summary: This paper proposes a novel method to transfer the semantic essence from a target image to a source image, without changing the identity of the source. The method uses CLIP's image latent space, which is more stable and expressive than the textual latent space. 

tags:
- Transformers
- CLIP
- StyleGAN
- Essence Transfer
featured: false

links:
- name: 5 min summary
  url: https://www.casualganpapers.com/clip_image_to_image_style_transfer_essence_transfer/TargetCLIP-explained.html
url_pdf: https://arxiv.org/pdf/2110.12427.pdf
url_code: 'https://github.com/hila-chefer/TargetCLIP'
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
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}