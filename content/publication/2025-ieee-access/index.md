---
title: "Adaptive Kalman Filtering: Measurement and Process Noise Covariance Estimation Using Kalman Smoothing"
authors:
- Theresa Kruse
- admin
- Knut Graichen
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2025-01-10T00:00:00Z"
doi: "10.1109/ACCESS.2025.3528348"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, Volume:13*"
publication_short: ""

abstract: The Kalman filter is one of the best-known and most frequently used methods for dynamic state estimation. In addition to a measurement and state transition model, the Kalman filter requires knowledge about the covariance of the measurement and process noise. However, the noise covariances are mostly unknown and may vary during the application. Adaptive Kalman filters solve this problem by estimating the noise covariances online to improve the state estimation. Existing methods are often limited in their application because they are designed to adapt only the measurement noise or the process noise covariance and tend to diverge when both are unknown. Moreover, most methods provide no or only local convergence results, which implies that a poor initialization can adversely affect the estimation of the noise covariances, leading to a deteriorated state estimation. This paper introduces a novel adaptive Kalman filter based on additional Kalman smoothing and analytically derived covariance estimators. Firstly, the unbiased measurement and process noise covariance estimators are derived from the maximum a posteriori formulation of the Kalman smoother. Then, based on these estimators, which depend on the system formulation and the state estimates of the Kalman smoother, the adaptive Kalman filter algorithm is presented. The convergence of the derived estimators can be shown for time-invariant systems for one-dimensional measurement and process noise. For higher-dimensional problems, the convergence can be tested simulatively for the specific dynamical system. A detailed evaluation of various simulation scenarios is presented, demonstrating the accuracy and robustness of the proposed method.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Adaptive Filtering
- Kalman Filter
- Noise Covariance Estimation

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10836673
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**IEEE**](https://ieeexplore.ieee.org/abstract/document/10836673)'
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
slides: ""
---
