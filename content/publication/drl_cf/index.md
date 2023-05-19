---
title: 'FPGA acceleration of Deep Reinforcement Learning Using On-chip Replay Management'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zhang Chi
  - Viktor Prasanna

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-05-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-17'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 19th ACM International Conference on Computing Frontiers*
publication_short: In *ACM/CF*

abstract: A major bottleneck in parallelizing deep reinforcement learning (DRL) is in the high latency to perform various operations used to update the Prioritized Replay Buffer on CPU. The low arithmetic intensity of these operations leads to severe under-utilization of the SIMT computation power of GPUs. In this work, we propose a high-throughput on-chip accelerator for Prioritized Replay Buffer and learner that efficient allocates computation and memory resources to saturate the FPGA computation power. Our design features hardware pipelining on FPGA such that the latency of replay operations is completely hidden. 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1GOy_ehtrjD5hzoOI2Pr-hoSv7vl1zeUA/view?usp=sharing'
url_code: 'https://github.com/vermouth1992/hipc21'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'DRL System'
  focal_point: ''
  preview_only: false



---


