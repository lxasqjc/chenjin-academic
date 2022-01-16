---
title: Disentangling Human Error from the Ground Truth in Segmentation of
  Medical Images
publication_types:
  - "1"
authors:
  - Le Zhang
  - Ryutaro Tanno
  - Mou-Cheng Xu
  - Chen Jin
  - Joseph Jacob
  - Olga Ciccarelli
  - Frederik Barkhof
  - Daniel C Alexander
publication: In *NeurIPS 2020*
publication_short: NeurIPS, 2020
abstract: "Recent years have seen increasing use of supervised learning methods
  for segmentation tasks. However, the predictive performance of these
  algorithms depends on the quality of labels. This problem is particularly
  pertinent in the medical image domain, where both the annotation cost and
  inter-observer variability are high. In a typical label acquisition process,
  different human experts provide their estimates of the “true” segmentation
  labels under the influence of their own biases and competence levels. Treating
  these noisy labels blindly as the ground truth limits the performance that
  automatic segmentation algorithms can achieve. In this work, we present a
  method for jointly learning, from purely noisy observations alone, the
  reliability of individual annotators and the true segmentation label
  distributions, using two coupled CNNs. The separation of the two is achieved
  by encouraging the estimated annotators to be maximally unreliable while
  achieving high fidelity with the noisy training data. We first define a toy
  segmentation dataset based on MNIST and study the properties of the proposed
  algorithm. We then demonstrate the utility of the method on three public
  medical imaging segmentation datasets with simulated (when necessary) and real
  diverse annotations: 1) MSLSC (multiple-sclerosis lesions) 2) BraTS (brain
  tumours) 3) LIDC-IDRI (lung abnormalities). In all cases, our method
  outperforms competing methods and relevant baselines particularly in cases
  where the number of annotations is small and the amount of disagreement is
  large. The experiments also show strong ability to capture the complex spatial
  characteristics of annotators’ mistakes."
draft: false
projects:
  - humanerror
slides: ""
url_pdf: https://arxiv.org/pdf/2007.15963
doi: ""
featured: true
tags:
  - ""
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: humanerror.jpg
summary: Different human experts provide their estimates of the “true”
  segmentation labels under the influence of their own biases and competence
  levels. Treating these noisy labels blindly as the ground truth limits the
  performance that automatic segmentation algorithms can achieve. In this work,
  we present a method for jointly learning, from purely noisy observations
  alone, the reliability of individual annotators and the true segmentation
  label distributions, using two coupled CNNs.
date: 2020-07-01T00:00:00.000Z
links:
  - name: Link
    url: https://arxiv.org/abs/2007.15963
publishDate: 2020-07-01T00:00:00.000Z
url_code: https://github.com/moucheng2017/Learn_Noisy_Labels_Medical_Images
share: true
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
