---
title: "A Framework for Mapping DRL Algorithms with Prioritized Replay Buffer onto Heterogeneous Platforms"
authors:
- Chi Zhang
- admin
- Viktor Prasanna

date: "2023-04-05"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-05"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Parallel and Distributed Systems*(1)"
publication_short: In *IEEE/TPDS*

abstract: The computation primitives of DRL with Prioritized Replay Buffer include environment emulation, neural network inference, sampling from Prioritized Replay Buffer, updating Prioritized Replay Buffer and neural network training. The speed of running these primitives varies for various DRL algorithms, making a fixed mapping of DRL algorithms inefficient. In this work, we propose a framework for mapping DRL algorithms onto heterogeneous platforms consisting of a multi-core CPU, a GPU and a FPGA. 

tags:
- Deep Reinforcement Learning
- Heterogeneous Computing
featured: false


url_pdf: https://drive.google.com/file/d/1EI0yEW43fzTFfCcz88BJ74O9uEHMFI_Z/view?usp=sharing
url_code: 'https://github.com/vermouth1992/hipc21'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'High Level Workflow'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---