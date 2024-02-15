---
title: 'VMAS: A Vectorized Multi-Agent Simulator for Collective Robot Learning'

authors:
  - Matteo Bettini
  - admin
  - Jan Blumenkamp
  - Amanda Prorok

date: '2022-07-07T00:00:00Z'
doi: ''

publishDate: '2022-07-07T00:00:00Z'

# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Distributed Autonomous Robotic Systems (DARS)
publication_short: DARS

abstract: While many multi-robot coordination problems can be solved optimally by exact algorithms, solutions are often not scalable in the number of robots. Multi-Agent Reinforcement Learning (MARL) is gaining increasing attention in the robotics community as a promising solution to tackle such problems. Nevertheless, we still lack the tools that allow us to quickly and efficiently find solutions to large-scale collective learning tasks. In this work, we introduce the Vectorized Multi-Agent Simulator (VMAS). VMAS is an open-source framework designed for efficient MARL benchmarking. It is comprised of a vectorized 2D physics engine written in PyTorch and a set of twelve challenging multi-robot scenarios. Additional scenarios can be implemented through a simple and modular interface. We demonstrate how vectorization enables parallel simulation on accelerated hardware without added complexity. When comparing VMAS to OpenAI MPE, we show how MPE's execution time increases linearly in the number of simulations while VMAS is able to execute 30,000 parallel simulations in under 10s, proving more than 100x faster. Using VMAS's RLlib interface, we benchmark our multi-robot scenarios using various Proximal Policy Optimization (PPO)-based MARL algorithms. VMAS's scenarios prove challenging in orthogonal ways for state-of-the-art MARL algorithms. The VMAS framework is available at [this https URL](https://github.com/proroklab/VectorizedMultiAgentSimulator). A video of VMAS scenarios and experiments is available at [this https URL](https://www.youtube.com/watch?v=aaDRYfiesAY).

# Summary. An optional shortened abstract.
summary: A vectorised simulation environment for reinforcement learning.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2207.03530.pdf'
url_code: 'https://github.com/proroklab/VectorizedMultiAgentSimulator'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=aaDRYfiesAY'

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

<span aria-hidden=true>&#215;</span></button></div><div class=modal-body><pre><code class="tex hljs"></code></pre></div><div class=modal-footer><a class="btn btn-outline-primary my-1 js-copy-cite" href=# target=_blank><i class="fas fa-copy"></i> Copy
</a><a class="btn btn-outline-primary my-1 js-download-cite" href=# target=_blank><i class="fas fa-download"></i> Download</a><div id=modal-error></div></div></div></div></div><script src=https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin=anonymous></script><script src=https://cdnjs.cloudflare.com/ajax/libs/instant.page/5.1.0/instantpage.min.js integrity="sha512-1+qUtKoh9XZW7j+6LhRMAyOrgSQKenQ4mluTR+cvxXjP1Z54RxZuzstR/H9kgPXQsVB8IW7DMDFUJpzLjvhGSQ==" crossorigin=anonymous></script><script src=https://cdnjs.cloudflare.com/ajax/libs/jquery.imagesloaded/4.1.4/imagesloaded.pkgd.min.js integrity="sha256-lqvxZrPLtfffUl2G/e7szqSvPBILGbwmsGE1MKlOi0Q=" crossorigin=anonymous></script><script src=https://cdnjs.cloudflare.com/ajax/libs/jquery.isotope/3.0.6/isotope.pkgd.min.js integrity="sha256-CBrpuqrMhXwcLLUd5tvQ4euBHCdh7wGlDfNz8vbu/iI=" crossorigin=anonymous></script><script src=https://cdnjs.cloudflare.com/ajax/libs/highlight.js/10.2.0/highlight.min.js integrity="sha512-TDKKr+IvoqZnPzc3l35hdjpHD0m+b2EC2SrLEgKDRWpxf2rFCxemkgvJ5kfU48ip+Y+m2XVKyOCD85ybtlZDmw==" crossorigin=anonymous></script><script src=https://cdnjs.cloudflare.com/ajax/libs/highlight.js/10.2.0/languages/r.min.js></script><script src=https://cdnjs.cloudflare.com/ajax/libs/highlight.js/10.2.0/languages/python.min.js></script><script src=https://cdnjs.cloudflare.com/ajax/libs/highlight.js/10.2.0/languages/latex.min.js></script><script src=https://cdnjs.cloudflare.com/ajax/libs/leaflet/1.7.1/leaflet.min.js integrity="sha512-SeiQaaDh73yrb56sTW/RgVdi/mMqNeM2oBwubFHagc5BkixSpP1fvqF47mKzPGWYSSy4RwbBunrJBQ4Co8fRWA==" crossorigin=anonymous></script><script id=search-hit-fuse-template type=text/x-template>
        <div class="search-hit" id="summary-{{key}}">
          <div class="search-hit-content">
            <div class="search-hit-name">
              <a href="{{relpermalink}}">{{title}}</a>
              <div class="article-metadata search-hit-type">{{type}}</div>
              <p class="search-hit-description">{{snippet}}</p>
            </div>
          </div>
        </div>
      </script><script src=https://cdnjs.cloudflare.com/ajax/libs/fuse.js/3.2.1/fuse.min.js integrity="sha256-VzgmKYmhsGNNN4Ph1kMW+BjoYJM2jV5i4IlFoeZA9XI=" crossorigin=anonymous></script><script src=https://cdnjs.cloudflare.com/ajax/libs/mark.js/8.11.1/jquery.mark.min.js integrity="sha256-4HLtjeVgH0eIB3aZ9mLYF6E8oU5chNdjU6p6rrXpl9U=" crossorigin=anonymous></script><script src=/js/bootstrap.bundle.min.6aed84840afc03ab4d5750157f69c120.js></script><script src=/en/js/wowchemy.min.f7a5e0a5c39e010ad2fd6899a284771d.js></script><script async defer src=https://buttons.github.io/buttons.js></script></body></html>