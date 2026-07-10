---
title: "Generalized Linear Bandits with Memory"
authors:
- Heesang Ann
- Hyunjun Choi
- Taehyun Hwang
- Younghoon Shin
- Haeju Cheong
- Min-hwan Oh
# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2026-05-01T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2024-05-30T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _International Conference on Machine Learning_ (__ICML__), 2026
publication_short: _ICML_ 2026

abstract: We study generalized linear bandits with memory, an endogenous non-stationary setting in which rewards depend on past actions through a finite memory matrix. Building on prior work for linear models (Clerici et al., 2024), we show that the previously known $\tilde{\mathcal{O}}(T^{3/4})$ regret bound stems from a loose analysis, and we provide a sharpened analysis that recovers a $\tilde{\mathcal{O}}(\sqrt{T})$ regret rate in the linear case. We then extend this improvement to generalized linear models and propose a block-wise algorithm based on shrunken confidence bounds. Our algorithm achieves a regret bound of $\tilde{\mathcal{O}}\left(\sqrt{mT} + d\sqrt{T} + \sqrt{\kappa}\, d^{2} m^{1/4} T^{1/4} + \kappa d^{2} \right)$, where $d$ denotes the feature dimension, $m$ the memory length, and $\kappa$ a curvature parameter of the link function. This attains a $\sqrt{T}$-type rate despite nonlinear rewards and memory effects. To the best of our knowledge, this analysis provides a unified treatment of memory-induced non-stationarity and nonlinear link functions, while ensuring that the leading regret term is independent of the curvature of the link function. We conduct numerical experiments that are consistent with our theoretical findings.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://openreview.net/pdf?id=DfZS0M8leJ'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
