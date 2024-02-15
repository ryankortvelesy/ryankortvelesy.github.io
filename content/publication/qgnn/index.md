---
title: 'QGNN: Value Function Factorisation with Graph Neural Networks'

authors:
  - admin
  - Amanda Prorok

date: '2022-05-25T00:00:00Z'
doi: ''

publishDate: '2022-05-25T00:00:00Z'

# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Under Review at the Journal for Autonomous Agents and Multi-Agent Systems (JAAMAS)
publication_short: Under Review

abstract: In multi-agent reinforcement learning, the use of a global objective is a powerful tool for incentivising cooperation. Unfortunately, it is not sample-efficient to train individual agents with a global reward, because it does not necessarily correlate with an agent's individual actions. This problem can be solved by factorising the global value function into local value functions. Early work in this domain performed factorisation by conditioning local value functions purely on local information. Recently, it has been shown that providing both local information and an encoding of the global state can promote cooperative behaviour. In this paper we propose QGNN, the first value factorisation method to use a graph neural network (GNN) based model. The multi-layer message passing architecture of QGNN provides more representational complexity than models in prior work, allowing it to produce a more effective factorisation. QGNN also introduces a permutation invariant mixer which is able to match the performance of other methods, even with significantly fewer parameters. We evaluate our method against several baselines, including QMIX-Att, GraphMIX, QMIX, VDN, and hybrid architectures. Our experiments include Starcraft, the standard benchmark for credit assignment; Estimate Game, a custom environment that explicitly models inter-agent dependencies; and Coalition Structure Generation, a foundational problem with real-world applications. The results show that QGNN outperforms state-of-the-art value factorisation baselines consistently.

# Summary. An optional shortened abstract.
summary: A GNN-based value factorisation method, enabling credit assignment on collaborative tasks (*i.e.* tasks with interdependencies between agents).

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2205.13005.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
slides: ""
---

