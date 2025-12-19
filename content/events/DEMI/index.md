---
title: PiMPiC Framework

event: MICCAI Conference Workshop
event_url: https://demi-workshop.github.io/#/:~:text=Long%20Papers%3A-,PiMPiC%3A%20An%20Overlap%2DAware%20Contrastive%20Learning%20Framework%20for%203D%20Patch%2DBased%20Medical%20Image%20Segmentation,-Balancing%20Redundancy%20and

location: Daejeon Conference Center, South Korea
# address:
  # street: ''
  # city: Daejeon, South Korea
  # region: ''
  # postcode: ''
  # country: South Korea

summary: PiMPiC; An Overlap-Aware Contrastive Learning Framework for 3D Patch-Based Medical Image Segmentation
abstract: 'Deep learning models for 3D medical image segmentation typically require large annotated datasets to achieve high accuracy. However, collecting such datasets is time-consuming, costly, and constrained by privacy regulations. Contrastive learning, a self-supervised technique, enables models to learn meaningful data representations without any labeled data. However, applying traditional contrastive learning methods to medical images is challenging due to the structural similarity of human tissues, which often results in false negatives when similar tissues are treated as dissimilar. Additionally, slice-wise contrastive learning approaches rely on relative slice positions to form positive and negative pairs, limiting generalization to 3D patches and requiring image preregistration. To address these issues, we propose two novel modules for contrastive learning-based pretraining of 3D segmentation. The first, Patch Intersection Measurement (PiM), estimates the overlap between two patches in the embedding space. The second, Patch Intersection Contrast (PiC), encourages embeddings of overlapping regions to align closely while pushing non-overlapping regions apart. Experiments on two datasets for pancreas and kidney cancers segmentation demonstrated that our method outperforms both the state-of-the-art (SOTA) and the baseline segmentation models. Notably, for pancreas segmentation, even when trained with only 5% of the labeled data, our method achieves 12% and 4% improvement in Dice score compared to the baseline and SOTA, highlighting its effectiveness in low-data scenarios.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2025-09-27T10:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-10-15T00:00:00Z'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
  - type: code
    url: https://github.com/rezakarimzadeh/pimpic
  # - type: slides
  #   url: https://slideshare.net
  # - type: video
  #   url: https://youtube.com
  - type: link
    url: https://link.springer.com/chapter/10.1007/978-3-032-08009-7_3

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---

<!-- > [!NOTE]
> Click on the **Slides** button above to view the built-in slides feature.

Slides can be added in a few ways:

- **Create** slides using Hugo Blox Builder's [_Slides_](https://docs.hugoblox.com/reference/content-types/) feature and link using the `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to this page bundle and link it using `links: [{ type: slides, url: path/to/file } ]` in front matter
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://docs.hugoblox.com/reference/markdown/).

Further event details, including [page elements](https://docs.hugoblox.com/reference/markdown/) such as image galleries, can be added to the body of this page. -->
