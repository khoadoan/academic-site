---
abstract: "For a given image generation problem, the intrinsic image manifold is
  often low-dimensional. We use the intuition that it is much better to train
  the GAN generator by minimizing the distributional distance between real and
  generated images in a small dimensional feature space representing such a
  manifold than on the original pixel space. We use the feature space of the GAN
  discriminator for such a representation. For distributional distance, we
  employ one of two choices: the Fr\\'{e}chet distance or direct optimal
  transport (OT); these respectively lead us to two new GAN methods:
  Fr\\'{e}chet-GAN and OT-GAN. The idea of employing Fr\\'{e}chet distance comes
  from the success of Fr\\'{e}chet Inception Distance as a solid evaluation
  metric in image generation. Fr\\'{e}chet-GAN is attractive in several ways. We
  propose an efficient, numerically stable approach to calculate the
  Fr\\'{e}chet distance and its gradient. The Fr\\'{e}chet distance estimation
  requires a significantly less computation time than OT; this allows
  Fr\\'{e}chet-GAN to use a much larger mini-batch size in training than OT.
  More importantly, we conduct experiments on a number of benchmark datasets and
  show that Fr\\'{e}chet-GAN (in particular) and OT-GAN have significantly
  better image generation capabilities than the existing representative primal
  and dual GAN approaches based on the Wasserstein distance."
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Khoa D. Doan
  - Fengjiao Wang
  - Saurav Manchanda
  - Sathiya K. Selvaraj
  - Avradeep Bhowmilk & Chandan K. Reddy
author_notes: []
publication: ""
summary: ""
url_dataset: ""
url_project: ""
publication_short: In *arxiv*
url_source: ""
url_video: ""
title: Image Generation via Minimizing Fréchet Distance in Discriminator Feature
  Space.
doi: ""
featured: true
tags: []
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: true
  filename: frechet-2021-demo.png
date: 2013-07-01T00:00:00Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
