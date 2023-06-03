---
title: 'How to Avoid Zero-spacing in Fractionally-Strided Convolution? A Hardware-Algorithm Co-design Methodology'
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
publication: In *Proceedings of the 2021 IEEE 28th International Conference on High Performance Computing, Data, and Analytics*
publication_short: In *IEEE/HiPC*

abstract: Fractionally Strided Convolution (FSC) is a key operation in popular image-based Deep Learning models, for example, CNN back propagation, the decoding stage of convolutional auto-encoders and generative CNNs (GAN), etc. FSC typically performs  up-convolution on a 2-D grid image, i.e., expands it to a larger one, as compared to conventional (down)-convolution, resulting in more complex computation patterns. Specifically, it introduces additional interleaved zero-spacing (i.e. insertion and padding of zeros) in feature maps that impose excessive computation and memory access overheads on traditional convolution methods such as im2col. The resulting hardware under-utilization is especially severe in layers with large kernels and large strides, commonly seen in typical CNNs and Generative CNNs. In this paper, we propose a methodology to address this challenge using a multi-channel-multi-kernel parallel algorithm, kn2row, to eliminate zero-computations in FSC. We further develop a unified accelerator for kn2row-based convolution and FSC operations in High-Level Synthesis (HLS). Benefiting from the compute-reduction of kn2row, we achieve up to 14.6x improvement in effective resource utilization in typical convolutional auto-decoding layers, GAN layers and backward pass of Nature-CNN, a reinforcement learning bench-marking model. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://drive.google.com/file/d/1o2R5zsX06LfPq9SeeZmYbJ-Hqh1IHSsj/view?usp=sharing'
url_code: 'https://github.com/CatherineMeng/FPFSC-FPGA-Accelerated-Frationally-Strided-Convolution'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'A Multi-Channel-Multi-Kernel KN2ROW Approach for FSC'
  focal_point: ''
  preview_only: false



---


