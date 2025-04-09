---
title: '2D Car Detection in Radar Data with PointNets'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Andreas Danzer
  - admin
  - Martin Bach
  - Klaus Dietmayer

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2019-10-30T00:00:00Z'
doi: '10.1109/ITSC.2019.8917000'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-11-28T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2019 IEEE Intelligent Transportation Systems Conference (ITSC)*
publication_short: In *IEEE ITSC 2019*

abstract: For many automated driving functions, a highly accurate perception of the vehicle environment is a crucial prerequisite. Modern high-resolution radar sensors generate multiple radar targets per object, which makes these sensors particularly suitable for the 2D object detection task. This work presents an approach to detect 2D objects solely depending on sparse radar data using PointNets. In literature, only methods are presented so far which perform either object classification or bounding box estimation for objects. In contrast, this method facilitates a classification together with a bounding box estimation of objects using a single radar sensor. To this end, PointNets are adjusted for radar data performing 2D object classification with segmentation, and 2D bounding box regression in order to estimate an amodal 2D bounding box. The algorithm is evaluated using an automatically created dataset which consist of various realistic driving maneuvers. The results show the great potential of object detection in high-resolution radar data using PointNets.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Object Detection
  - Radar Data
  - PointNets

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8917000'
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  #caption: 'Image credit: [**IEEE**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10920240)'
  #focal_point: ''
  #preview_only: false

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

