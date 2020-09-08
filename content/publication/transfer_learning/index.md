---
title: "A Transfer‐Learning Approach for Accelerated MRI Using Deep Neural Networks"
authors:
- admin
- Muzaffer Özbey
- Ahmet Burak Çatlı
- Tolga Çukur

date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Purpose, Neural networks have received recent interest for reconstruction of undersampled MR acquisitions. Ideally, network performance should be optimized by drawing the training and testing data from the same domain. In practice, however, large datasets comprising hundreds of subjects scanned under a common protocol are rare. The goal of this study is to introduce a transfer‐learning approach to address the problem of data scarcity in training deep networks for accelerated MRI. Methods, Neural networks were trained on thousands (upto 4 thousand) of samples from public datasets of either natural images or brain MR images. The networks were then fine‐tuned using only tens of brain MR images in a distinct testing domain. Domain‐transferred networks were compared to networks trained directly in the testing domain. Network performance was evaluated for varying acceleration factors (4‐10), number of training samples (0.5‐4k), and number of fine‐tuning samples (0‐100). Results, The proposed approach achieves successful domain transfer between MR images acquired with different contrasts (T1‐ and T2‐weighted images) and between natural and MR images (ImageNet and T1‐ or T2‐weighted images). Networks obtained via transfer learning using only tens of images in the testing domain achieve nearly identical performance to networks trained directly in the testing domain using thousands (upto 4 thousand) of images. Conclusion, The proposed approach might facilitate the use of neural networks for MRI reconstruction without the need for collection of extensive imaging datasets.
# Summary. An optional shortened abstract.
summary: We propose a transfer‐learning approach to address the problem of data scarcity in training deep networks for accelerated MRI.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
