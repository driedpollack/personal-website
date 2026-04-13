---
title: "Diversified Multinomial Logit Contextual Bandits"
authors:
- Heesang Ann
- admin
- Min-hwan Oh
# Author notes (optional)
# author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'

date: '2026-01-26T00:00:00Z'
# doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2024-05-30T00:00:00Z' # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _International Conference on Learning Representation_ (__ICLR__), 2026
publication_short: _ICLR_ 2026

abstract: Existing contextual \textit{multinomial logit} (MNL) bandits model relevance-driven choice but ignore the potential benefits of within-assortment diversity, while submodular/combinatorial bandits encode diversity in rewards but lack structured choice probabilities. We bridge this gap with the \textit{diversified multinomial logit} (DMNL) contextual bandit, which augments MNL choice probabilities with a generally submodular diversity function, thereby formalizing the relevance--diversity trade-off within a single model. Incorporating diversity renders exact MNL assortment optimization intractable. We propose a \textit{white-box} UCB-based algorithm, $\texttt{OFU-DMNL}$, that constructs assortments item-wise by maximizing optimistic marginal gains, avoids black-box optimization oracles. We show that $\texttt{OFU-DMNL}$ achieves at least a $(1-\tfrac{1}{e+1})$-\textit{approximate} regret bound $\tilde{\mathcal{O}}\big(d \sqrt{T/K}\big)$, where $d$ is the context dimension, $K$ the maximum assortment size, and $T$ the horizon, and attains an improved approximation factor over standard submodular baselines.  Experiments demonstrate consistent gains and, relative to exhaustive enumeration, comparable regret with substantially lower runtime. Overall, DMNL bandits provide a principled and practical foundation for diversity-aware assortment optimization under uncertainty, and $\texttt{OFU-DMNL}$ offers a statistically and computationally efficient solution.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []
# - Source Themes
featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://openreview.net/pdf?id=swwelQtLRn'
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
