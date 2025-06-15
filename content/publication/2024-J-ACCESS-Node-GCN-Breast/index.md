---
title: "Node-Based Graph Convolutional Network With SLIC Method for Breast Cancer Ultrasound Images Classification"
authors:
- admin
- Fung Ting Ting
- Bao Quoc Vuong
- Chee-Ming Ting
author_notes:
date: 
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, (12)*, pp. 171036-171054, 2024"
publication_short: ""

abstract: This research presents a novel node-based Graph Convolutional Network (GCN) approach for the classification of breast cancer from ultrasound images. Utilizing the Simple Linear Iterative Clustering (SLIC) algorithm, superpixels are segmented and treated as nodes and connected based on color similarity and spatial proximity. This enables the graph data capturing both long-range and short-range dependencies among image features. The graph-structured data is processed through a multi-layer GCN, which effectively aggregates and learns from complex node interrelations to classify the nodes as benign, malignant, or normal. In the final stage, a voting rule is applied to the node classification in order to perform the final image-level classification. Overall, the proposed framework yielded impressive findings on two distinct datasets, Breast Ultrasound Images Dataset (BUSI) and Breast Ultrasound Image dataset from Brazil (BUSBRA). Different numbers of connections between nodes are evaluated to indicate the importance of hidden insight interconnections in the medical imaging domain. The results give an accuracy of 98.73% for the BUSI dataset and 98.40% in the case of the BUSBRA dataset, indicating superior performance compared to conventional and other advanced methodologies. This highlights the potential of employing node-based GCNs for breast cancer detection using ultrasound imagery in clinical applications.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

links:
- name: "DOI"
  url: "https://doi.org/10.1109/ACCESS.2024.3488188"

- name: "Paper"
  url: "https://ieeexplore.ieee.org/document/10738815"
url_pdf: ''
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
slides: 
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
