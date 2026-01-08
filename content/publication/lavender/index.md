---
title: "Diffusion Instruction Tuning"
publication_types:
  - "1"
authors:
  - Chen Jin
  - Ryutaro Tanno
  - Amrutha Saseendran
  - Tom Diethe
  - Philip Teare
publication: ICML, 2025
publication_short: ICML, 2025
abstract: "We introduce Lavender, a simple supervised fine-tuning (SFT) method that boosts the performance of advanced vision-language models (VLMs) by leveraging state-of-the-art image generation models such as Stable Diffusion. Specifically, Lavender aligns the text-vision attention in the VLM transformer with the equivalent used by Stable Diffusion during SFT, instead of adapting separate encoders. This alignment enriches the model’s visual understanding and significantly boosts performance across in- and out-of-distribution tasks. Lavender requires just 0.13 million training examples—2.5% of typical large-scale SFT datasets—and fine-tunes on standard hardware (8 GPUs) in a single day. It consistently improves state-of-the-art open-source multimodal LLMs (e.g., Llama-3.2-11B, MiniCPM-Llama3-v2.5), achieving up to 30% gains and a 68% boost on challenging out-of-distribution medical QA tasks. By efficiently transferring the visual expertise of image generators with minimal supervision, Lavender offers a scalable solution for more accurate vision-language systems. All code, training data, and models will be shared."
draft: false
share: true
slides: ""

summary: Lavender efficiently fine-tunes advanced vision-language models by aligning their text-vision attention with Stable Diffusion.

links:
  - name: Page
    url: https://astrazeneca.github.io/vlm/
  - name: Arxiv
    url: https://arxiv.org/abs/2502.06814
# url_video: https://www.youtube.com/watch?v=n4irrHj8xIA
url_pdf: 'https://arxiv.org/pdf/2502.06814'
# url_code: https://github.com/AstraZeneca/MCPL/tree/master
doi: ""
featured: true
tags:
  - Diffusion Models
projects:
  - lavender
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2025-01-31T00:40:17.187Z
publishDate: 2025-02-04T00:00:00.000Z

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
