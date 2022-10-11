---
title: "Image-Based Clip-Guided Essence Transfer"
authors:
- Hila Chefer
- Sagie Benaim
- Roni Paiss
- Lior Wolf
date: "2022-10-20T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IEEE/CVF European Conference on Computer Vision (ECCV)
publication_short: In *ECCV*

abstract: "We make the distinction between (i) style transfer, in which a source image is manipulated to match the textures and colors of a target image, and (ii) essence transfer, in which one edits the source image to include high-level semantic attributes from the target. Crucially, the semantic attributes that constitute the essence of an image may differ from image to image. Our blending operator combines the powerful StyleGAN generator and the semantic encoder of CLIP in a novel way that is simultaneously additive in both latent spaces, resulting in a mechanism that guarantees both identity preservation and high-level feature transfer without relying on a facial recognition network. We present two variants of our method. The first is based on optimization, while the second fine-tunes an existing inversion encoder to perform essence extraction. Through extensive experiments, we demonstrate the superiority of our methods for essence transfer over existing methods for style transfer, domain adaptation, and text-based semantic editing."

# Summary. An optional shortened abstract.
summary: This paper proposes a novel method to transfer the semantic properties that constitute high-level textual description from a target image to a source image, without changing the identity of the source. The method uses CLIP's image latent space, which is more stable and expressive than the textual latent space. 

tags:
- Transformers
- CLIP
- StyleGAN
- Essence Transfer
featured: false

links:
- name: 5 min summary
  url: https://www.casualganpapers.com/clip_image_to_image_style_transfer_essence_transfer/TargetCLIP-explained.html
- name: 5 min video (ECCV)
  url: https://www.youtube.com/watch?v=GY_g4aDi_ys
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