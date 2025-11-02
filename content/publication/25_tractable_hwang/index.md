---
title: "Tractable Multinomial Logit Contextual Bandits with Non-Linear Utilities"
authors:
- admin
- Dahngoon Kim
- Min-hwan Oh
# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2025-11-02T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2024-05-30T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _Advances in Neural Information Processing Systems 39_ (__NeurIPS__), 2025
publication_short: _NeurIPS_ 2025

abstract: We study the \textit{multinomial logit} (MNL) contextual bandit problem for sequential assortment selection. Although most existing research assumes utility functions to be linear in item features, this linearity assumption restricts the modeling of intricate interactions between items and user preferences. A recent work~\citep{zhang2024contextual} has investigated general utility function classes, yet its method faces fundamental trade-offs between computational tractability and statistical efficiency. To address this limitation, we propose a computationally efficient algorithm for MNL contextual bandits leveraging the upper confidence bound principle, specifically designed for non-linear parametric utility functions, including those modeled by neural networks. Under a realizability assumption and a mild geometric condition on the utility function class, our algorithm achieves a regret bound of $\tilde{\mathcal{O}}(\sqrt{T})$, where $T$ denotes the total number of rounds. Our result establishes that sharp $\tilde{\mathcal{O}}(\sqrt{T})$-regret is attainable even with neural network-based utilities, without relying on strong assumptions such as neural tangent kernel approximations. To the best of our knowledge, our proposed method is the first computationally tractable algorithm for MNL contextual bandits with non-linear utilities that provably attains $\tilde{\Ocal}(\sqrt{T})$ regret. Comprehensive numerical experiments validate the effectiveness of our approach, showing robust performance not only in realizable settings but also in scenarios with model misspecification.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://openreview.net/pdf?id=kNoh1TuV4R'
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
