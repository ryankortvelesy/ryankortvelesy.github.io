---
title: AAMAS Presentation

event: AAMAS 2023
event_url: https://aamas2023.soton.ac.uk/

location: ExCeL London Conference Centre
address:
  street: Royal Victoria Dock, 1 Western Gateway
  city: London
  postcode: E16 1XL
  country: United Kingdom

summary: Presentation of *Permutation-Invariant Set Autoencoders with Fixed-Size Embeddings for Multi-Agent Learning* at AAMAS 2023.
abstract: The problem of permutation-invariant learning over set representations is particularly relevant in the field of multi-agent systems -- a few potential applications include unsupervised training of aggregation functions in graph neural networks (GNNs), neural cellular automata on graphs, and prediction of scenes with multiple objects. Yet existing approaches to set encoding and decoding tasks present a host of issues, including non-permutation-invariance, fixed-length outputs, reliance on iterative methods, non-deterministic outputs, computationally expensive loss functions, and poor reconstruction accuracy. In this paper we introduce a Permutation-Invariant Set Autoencoder (PISA), which tackles these problems and produces encodings with significantly lower reconstruction error than existing baselines. PISA also provides other desirable properties, including a similarity-preserving latent space, and the ability to insert or remove elements from the encoding. After evaluating PISA against baseline methods, we demonstrate its usefulness in a multi-agent application. Using PISA as a subcomponent, we introduce a novel GNN architecture which serves as a generalised communication scheme, allowing agents to use communication to gain full observability of a system.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2023-06-02T00:00:00Z'
date_end: '2023-06-02T00:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-06-02T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: Photos from the presentation at AAMAS 2023.
  focal_point: Right

links:   
  - name: Paper
    url: https://ryankortvelesy.github.io/publication/sae/
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---