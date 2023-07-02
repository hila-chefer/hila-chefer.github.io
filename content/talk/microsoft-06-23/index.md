---
title: "Attend-and-Excite: Attention-Based Semantic Guidance for Text-to-image Diffusion Models (English)"
event: Data Science Bond Microsoft
event_url: 
location: Online event
summary: This talk takes a deep dive into Attend-and-Excite. The paper presents a method to guide text-to-image diffusion models to generate all subjects in the input prompt, to mitigate subject neglect. This is achieved by defining an intuitive loss over the cross-attention maps during inference without any additional data or fine-tuning.
abstract: "Recent text-to-image generative models have demonstrated an unparalleled ability to generate diverse and creative imagery guided by a target text prompt. While revolutionary, current state-of-the-art diffusion models may still fail in generating images that fully convey the semantics in the given text prompt. We analyze the publicly available Stable Diffusion model and assess the existence of catastrophic neglect, where the model fails to generate one or more of the subjects from the input prompt. Moreover, we find that in some cases the model also fails to correctly bind attributes (e.g. colors) to their corresponding subjects. To help mitigate these failure cases, we introduce the concept of Generative Semantic Nursing (GSN), where we seek to intervene in the generative process on the fly during inference time to improve the faithfulness of the generated images. Using an attention- based formulation of GSN, dubbed Attend-and-Excite, we guide the model to refine the cross-attention units to attend to all subject tokens in the text prompt and strengthen — or excite — their activations, encouraging the model to generate all subjects described in the text prompt. We compare our approach to alternative approaches and demonstrate that it conveys the desired concepts more faithfully across a range of text prompts."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2023-07-02T14:00:00Z"
date_end: "2023-07-02T15:00:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2023-07-02T13:00:00Z"

authors: ["Hila Chefer"]
tags: ["Stable Diffusion","Attention", "Semantic Guidance"]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Microsoft**](https://microsoft.com)'
  focal_point: Right

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=RkI4BFG0GP0"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: 

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
# - internal-project

# Enable math on this page?
math: true
---

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}
