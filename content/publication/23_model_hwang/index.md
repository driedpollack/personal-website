---
title: 'Model-Based Reinforcement Learning with Multinomial Logistic Function Approximation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Min-hwan Oh

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-12-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: _Proceedings of the 37th AAAI Conference on Artificial Intelligence_ (__AAAI__), 2023
publication_short: _AAAI_ 2023 [Oral presentation]

abstract: We study model-based reinforcement learning (RL) for episodic Markov decision processes (MDP) whose transition probability is parametrized by an unknown transition core with features of state and action. Despite much recent progress in analyzing algorithms in the linear MDP setting, the understanding of more general transition models is very restrictive. In this paper, we establish a provably efficient RL algorithm for the MDP whose state transition is given by a multinomial logistic model. To balance the exploration-exploitation trade-off, we propose an upper confidence bound-based algorithm. We show that our proposed algorithm achieves $\tilde{\mathcal{O}}(d \sqrt{H^3 T})$ regret bound where $d$ is the dimension of the transition core, $H$ is the horizon, and $T$ is the total number of steps. To the best of our knowledge, this is the first model-based RL algorithm with multinomial logistic function approximation with provable guarantees. We also comprehensively evaluate our proposed algorithm numerically and show that it consistently outperforms the existing methods, hence achieving both provable efficiency and practical superior performance.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2212.13540'
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_poster: 'publication/aaai23_ucrl-mnl/poster.pdf'
# url_project: ''
# url_slides: 'publication/aaai23_ucrl-mnl/slides.pdf'
# url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
