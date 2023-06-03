---
title: 'Accelerating Monte-Carlo Tree Search on CPU-FPGA Heterogeneous Platform'
authors:
  - admin
  - Rajgopal Kannan
  - Viktor Prasanna

date: '2022-08-23'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-08-23'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2022 32nd International Conference on Field-Programmable Logic and Applications*
publication_short: In *IEEE/FPL*

abstract: Monte Carlo Tree Search (MCTS) methods have achieved great success in many Artificial Intelligence (AI) benchmarks. The in-tree operations become a critical performance bottleneck in realizing parallel MCTS on CPUs. In this work, we develop a scalable CPU-FPGA system for Tree-Parallel MCTS. We propose a novel decomposition and mapping of MCTS data structure and computation onto CPU and FPGA to reduce communication and coordination. High scalability of our system is achieved by encapsulating in-tree operations in an SRAM-based FPGA accelerator. To lower the high data access latency and inter-worker synchronization overheads, we develop several hardware optimizations. We show that by using our accelerator, we obtain up to 35 times speedup for in-tree operations, and superior scalability wrt number of parallel workers than state-of-the-art parallel MCTS implementations on CPU.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1R2HcN5_io5evyFRWwvq1GkPBmqs_iqNb/view?usp=sharing'
url_code: 'https://github.com/CatherineMeng/FPGA-Accelerated-MCTS/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'System Execution Model'
  focal_point: ''
  preview_only: false

---
