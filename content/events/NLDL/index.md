---
title: Extremal Contours

event: Northern Light Deep Learning (NLDL) Conference
event_url: https://www.nldl.org/program/main-program#:~:text=11%3A00%20%E2%80%93%2011,Kirkegaard%2C%20Bulat%20Ibragimov

location: Tromsø, Norway
# address:
  # street: ''
  # city: Daejeon, South Korea
  # region: ''
  # postcode: ''
  # country: South Korea

summary: Extremal Contours; Gradient-driven contours for compact visual attribution
abstract: 'Faithful yet compact explanations for vision models remain a challenge, as commonly used dense perturbation masks are often fragmented and overfitted, needing careful post-processing. Here, we present a training-free explanation method that replaces dense masks with smooth tunable contours. A star-convex region is parameterized by a truncated Fourier series and optimized under an extremal preserve/delete objective using the classifier gradients. The approach guarantees a single, simply connected mask, cuts the number of free parameters by orders of magnitude, and yields stable boundary updates without cleanup. Restricting solutions to low-dimensional, smooth contours makes the method robust to adversarial masking artifacts. On ImageNet classifiers, it matches the extremal fidelity of dense masks while producing compact, interpretable regions with improved run-to-run consistency. Explicit area control also enables importance contour maps, yielding a transparent fidelity-area profiles. Finally, we extend the approach to multi-contour and show how it can localize multiple objects within the same framework. Across benchmarks, the method achieves higher relevance mass and lower complexity than gradient and perturbation based baselines, with especially strong gains on self-supervised DINO models where it improves relevance mass by over 15% and maintains positive faithfulness correlations.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-01-06T10:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-02-01T00:00:00Z'

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
    url: https://github.com/rezakarimzadeh/extremal-contours
  # - type: slides
  #   url: https://slideshare.net
  # - type: video
  #   url: https://youtube.com
  - type: link
    url: https://arxiv.org/abs/2511.01411

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
