---
title: Foveation for Segmentation of Ultra-High Resolution Images
publication_types:
  - "1"
authors:
  - Chen Jin
  - Ryutaro Tanno
  - Moucheng Xu
  - Thomy Mertzanidou
  - Daniel C. Alexander
publication_short: MICCAI, 2020
abstract: Segmentation of ultra-high resolution images is challenging because of their enormous size, consisting of millions or even billions of pixels. Typical solutions include dividing input images into patches of fixed size and/or down-sampling to meet memory constraints. Such operations incur information loss in the field-of-view (FoV) i.e., spatial coverage and the image resolution. The impact on segmentation performance is, however, as yet understudied. In this work, we start with a motivational experiment which demonstrates that the trade-off between FoV and resolution affects the segmentation performance on ultra-high resolution images—and furthermore, its influence also varies spatially according to the local patterns in different areas. We then introduce foveation module, a learnable “dataloader” which, for a given ultra-high resolution image, adaptively chooses the appropriate configuration (FoV/resolution trade-off) of the input patch to feed to the downstream segmentation model at each spatial location of the image. The foveation module is jointly trained with the segmentation network to maximise the task performance. We demonstrate on three publicly available high-resolution image datasets that the foveation module consistently improves segmentation performance over the cases trained with patches of fixed FoV/resolution trade-off. Our approach achieves the SoTA performance on the DeepGlobe aerial image dataset. On the Gleason2019 histopathology dataset, our model achieves better segmentation accuracy for the two most clinically important and ambiguous classes (Gleason Grade 3 and 4) than the top performers in the challenge by 13.1% and 7.5%, and improves on the average performance of 6 human experts by 6.5% and 7.5%. Our code and trained models are available at [https://github.com/lxasqjc/Foveation-Segmentation](https://github.com/lxasqjc/Foveation-Segmentation).
draft: false
featured: true
tags:
  - ''
projects:
  - foveation
slides: ''
url_pdf: https://discovery.ucl.ac.uk/id/eprint/10113531/1/paper1822.pdf
summary: We introduce foveation module, a learnable “dataloader” which, for a given ultra-high resolution image, adaptively chooses the appropriate configuration (FoV/resolution trade-off) of the input patch to feed to the downstream segmentation model at each spatial location of the image.
# url_dataset: http://example.org
# url_project: http://example.org
# url_source: https://github.com/lxasqjc/Foveation-Segmentation
url_video: https://youtu.be/MxaO9DtNeEQ
author_notes:
  - Equal contribution
  - Equal contribution
publication: In *MICCAI, 2020*
date: 2020-09-29T00:00:00Z
# url_slides: http://example.org
#links:
#  - name: Custom Link
#    url: http://example.org
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
publishDate: 2020-09-29T00:00:00Z
# url_poster: http://example.org
url_code: https://github.com/lxasqjc/Foveation-Segmentation
doi: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
