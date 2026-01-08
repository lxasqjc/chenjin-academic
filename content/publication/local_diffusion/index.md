---
title: Tackling Structural Hallucination in Image Translation with Local Diffusion
publication_types:
  - "1"
authors:
  - Seunghoi Kim
  - Chen Jin
  - Tom Diethe
  - Matteo Figini
  - Henry F. J. Tregidgo
  - Asher Mullokandov
  - Philip Teare
  - Daniel C. Alexander
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *ECCV, 2024, Oral*
publication_short: ECCV, 2024, Oral
abstract: Recent developments in diffusion models have advanced conditioned image generation, yet they struggle with reconstructing out-of-distribution (OOD) images, such as unseen tumors in medical images, causing "image hallucination" and risking misdiagnosis. We hypothesize such hallucinations result from local OOD regions in the conditional images. We verify that partitioning the OOD region and conducting separate image generations alleviates hallucinations in several applications. From this, we propose a training-free diffusion framework that reduces hallucination with multiple Local Diffusion processes. Our approach involves OOD estimation followed by two modules, a "branching" module generates locally both within and outside OOD regions, and a "fusion" module integrates these predictions into one. Our evaluation shows our method mitigates hallucination over baseline models quantitatively and qualitatively, reducing misdiagnosis by 40% and 25% in the real-world medical and natural image datasets, respectively. It also demonstrates compatibility with various pre-trained diffusion models.
draft: false
share: true
slides: ""

summary: Training-free diffusion framework that reduces hallucinations via multiple local diffusion processes, cutting hallucinations by 40% (medical) and 25% (natural).

url_pdf: https://arxiv.org/abs/2404.05980v5
url_code: https://github.com/edshkim98/LocalDiffusion-Hallucination
doi: ""
featured: true
tags:
  - Diffusion Models
projects:
  - local_diffusion
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2024-04-09T00:40:17.187Z
publishDate: 2024-04-09T00:00:00.000Z

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
