---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Disease Subtype Detection"
summary: ""
authors: []
tags: []
categories: []
date: 2020-09-16T22:09:10-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
 A heterogeneous disease like cancer is activated through multiple pathways and different perturbations.
Depending upon the activated pathway, the survival of patients vary significantly and show different efficacy to various drugs. Therefore, cancer subtype detection using genomics level data is an important research problem. Subtype detection is often a complex problem, and most of the time needs multiomics data fusion to achieve accurate subtyping. Recently different data fusion and subtyping approaches have been proposed, such as kernel based fusion, matrix factorization and deep learning autoencoders. In this paper, we compared the performance of different deep learning autoencoders for cancer subtype detection.
We performed cancer subtype detection on four different cancer types from the TCGA dataset using four different autoencoder implementations. We also predicted the optimal number of subtypes in a cancer using the silhouette score. We observed that the detected subtypes exhibit significant differences in survival rate. Furthermore, we also compared the effect of feature selection and similarity measures for subtype detection.