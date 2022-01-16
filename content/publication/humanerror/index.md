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
abstract: Segmenting histology images is challenging because of the sheer size of the images with millions or even billions of pixels. Typical solutions include dividing input images into patches of fixed size and/or down-sampling to meet memory constraints. Such operations incur information loss in the field-of-view (FoV) i.e., spatial coverage and the image resolution. The impact on segmentation performance is, however, as yet understudied. In this work, we start with a motivational experiment which demonstrates that the trade-off between FoV and resolution affects the segmentation performance on ultra-high resolution images—and furthermore, its influence also varies spatially according to the local patterns in different areas. We then introduce foveation module, a learnable “dataloader” which, for a given ultra-high resolution image, adaptively chooses the appropriate configuration (FoV/resolution trade-off) of the input patch to feed to the downstream segmentation model at each spatial location of the image. The foveation module is jointly trained with the segmentation network to maximise the task performance. We demonstrate on three publicly available high-resolution image datasets that the foveation module consistently improves segmentation performance over the cases trained with patches of fixed FoV/resolution trade-off. Our approach achieves the SoTA performance on the DeepGlobe aerial image dataset. On the Gleason2019 histopathology dataset, our model achieves better segmentation accuracy for the two most clinically important and ambiguous classes (Gleason Grade 3 and 4) than the top performers in the challenge by 13.1% and 7.5%, and improves on the average performance of 6 human experts by 6.5% and 7.5%. Our code and trained models are available at [https://github.com/lxasqjc/Foveation-Segmentation](https://github.com/lxasqjc/Foveation-Segmentation).
draft: false
share: true
slides: ""

summary: Different human experts provide their estimates of the “true” segmentation labels under the influence of their own biases and competence levels. Treating these noisy labels blindly as the ground truth limits the performance that automatic segmentation algorithms can achieve. In this work, we present a method for jointly learning, from purely noisy observations alone, the reliability of individual annotators and the true segmentation label distributions, using two coupled CNNs.

url_pdf: https://arxiv.org/pdf/2007.15963
url_code: https://github.com/moucheng2017/Learn_Noisy_Labels_Medical_Images
links:
  - name: Link
    url: https://arxiv.org/abs/2007.15963

doi: ""
featured: true
tags:
  - ""
projects:
  - humanerror
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: humanerror.jpg
date: 2020-07-01T00:00:00.000Z
publishDate: 2020-07-01T00:00:00.000Z


---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
