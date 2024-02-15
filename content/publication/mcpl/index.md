---
title: "An Image is Worth Multiple Words: Discovering Object Level Concepts using Multi-Concept Prompt Learning"
publication_types:
  - "1"
authors:
  - Chen Jin
  - Ryutaro Tanno
  - Amrutha Saseendran
  - Tom Diethe
  - Philip Teare
publication: Preprint, Under Review
publication_short: Preprint, Under Review
abstract: "Textural Inversion, a prompt learning method, learns a singular text embedding for a new 'word' to represent image style and appearance, allowing it to be integrated into natural language sentences to generate novel synthesised images. However, identifying multiple unknown object-level concepts within one scene remains a complex challenge. While recent methods have resorted to cropping or masking individual images to learn multiple concepts, these techniques often require prior knowledge of new concepts and are labour intensive. To address this challenge, we introduce Multi-Concept Prompt Learning (MCPL), where multiple unknown 'words' are simultaneously learned from a single sentence-image pair, without any imagery annotations. To enhance the accuracy of word-concept correlation and refine attention mask boundaries, we propose three regularisation techniques: Attention Masking, Prompts Contrastive Loss, and Bind Adjective. Extensive quantitative comparisons with both real-world categories and biomedical images demonstrate that our method can learn new semantically disentangled concepts. Our approach emphasises learning solely from textual embeddings, using less than 10% of the storage space compared to others."
draft: false
share: true
slides: ""

summary: We introduce Multi-Concept Prompt Learning (MCPL), an innovative approach in textural inversion, focusing on mask-free learning multiple object-level concepts simultaneously from a single sentence-image pair.

links:
  - name: Page
    url: https://astrazeneca.github.io/mcpl.github.io/
  - name: Arxiv
    url: https://arxiv.org/abs/2310.12274
# url_video: https://recorder-v3.slideslive.com/?share=63834&s=2a9de36c-8627-40cd-9fa5-ef8accc61cca
url_pdf: 'https://github.com/lxasqjc/chenjin-academic/blob/master/content/publication/mcpl/mcpl_icml24_preprint.pdf'
url_code: https://github.com/lxasqjc/MCPL
doi: ""
featured: true
tags:
  - ""
projects:
  - mcpl
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2023-10-18T00:40:17.187Z
publishDate: 2023-10-18T00:00:00.000Z

---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
