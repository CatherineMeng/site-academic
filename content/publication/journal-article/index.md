---
title: "A Framework for Mapping DRL Algorithms with Prioritized Replay Buffer onto Heterogeneous Platforms"
authors:
- Chi Zhang
- admin
- Viktor Prasanna
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Parallel and Distributed Systems*(1)"
publication_short: "TPDS"

abstract: Despite the recent success of Deep Reinforcement Learning (DRL) in self-driving cars, robotics and surveillance, training DRL agents takes tremendous amount of time and computation resources. We aim to accelerate DRL with Prioritized Replay Buffer due to its state-of-the-art performance on various benchmarks. The computation primitives of DRL with Prioritized Replay Buffer include environment emulation, neural network inference, sampling from Prioritized Replay Buffer, updating Prioritized Replay Buffer and neural network training. The speed of running these primitives varies for various DRL algorithms, making a fixed mapping of DRL algorithms inefficient. In this work, we propose a framework for mapping DRL algorithms onto heterogeneous platforms consisting of a multi-core CPU, a GPU and a FPGA.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Deep Reinforcement Learning
- Heterogeneous Computing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://drive.google.com/drive/u/1/folders/1nabQX4KdmBlfyR2SZK4rNjWEgUWDXQFq
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
  caption: 'High Level [**Diagram**](https://github.com/CatherineMeng/site-academic/blob/main/images/tpds_img.PNG)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).


---
title: "PPOAccel: A High-Throughput Acceleration Framework for Proximal Policy Optimization"
authors:
- admin
- Sanmukh Kuppannagari
- Rajgopal Kannan
- Viktor Prasanna
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-12-13"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Parallel and Distributed Systems*(1)"
publication_short: "TPDS"

abstract: Proximal Policy Optimization (PPO) is the state-of-the-art policy optimization based RL algorithm which achieves superior overall performance on various benchmarks. A PPO agent iteratively optimizes its policy - a function which chooses optimal actions approximated by a DNN, with each iteration consisting of two computationally intensive phases: Sample Generation - where agents inference on its policy and interact with the environment to collect data, and Model Update - where the policy is trained using the collected data. 
In this paper, we develop the first high-throughput PPO accelerator on CPU-FPGA heterogeneous platform. 

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Proximal Policy Optimization
- Accelerator Design
- FPGA
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://drive.google.com/file/d/1nIggaAom2gjh76Rftho-7z3EChoi43nM/view?usp=sharing
url_code: 'https://github.com/CatherineMeng/PPO_2CU'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'High Level [**Diagram**](https://github.com/CatherineMeng/site-academic/blob/main/images/overview_ppoaccel.png)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
