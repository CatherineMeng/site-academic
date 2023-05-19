---
title: 'Dynamap: Dynamic algorithm mapping framework for low latency cnn inference'
authors:
  - admin
  - Sanmukh Kuppannagari
  - Rajgopal Kannan
  - Viktor Prasanna

date: '2021-02-17'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-17'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2021 ACM/SIGDA International Symposium on Field-Programmable Gate Arrays*
publication_short: In ACM/FPGA

abstract: Emerging CNNs have diverse per-layer computation characteristics including parallelism, arithmetic intensity, locality, and memory footprint. Per-layer strategy selection and fine-grained tuning is required to achieve low end-to-end latency. In this paper, we address these problems by an algorithm-architecture co-optimization framework, DYNAMAP, consisting of (1) a unified hardware overlay that can be reused across layers, supporting dynamic mapping of all three families of popular convolution algorithms; (2) a novel software Design Space Exploration (DSE) flow that chooses the optimal strategy mapping at compile time. We show that the algorithm mapping space increases exponentially with network depth, and while the optimal algorithm selection problem is NP-hard in general, by exploiting the series-parallel structure of CNN models, we demonstrate a polynomial-time solution for optimal algorithm mapping on SOTA CNN graphs.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1HPGKYHxuyjABwYBUk0eek-RHPVOCL36Q/view?usp=sharing'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Example optimal algorithm mappings on the inception module task graphss'
  focal_point: ''
  preview_only: false



---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}
