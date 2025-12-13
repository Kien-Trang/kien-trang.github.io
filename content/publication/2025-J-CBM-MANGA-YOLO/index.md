---
title: "MANGA-YOLO: A Mamba-inspired YOLO model with group attention for breast mass detection in mammograms"
authors:
- admin
- Fung Ting Ting
- Bao Quoc Vuong
- Chee-Ming Ting
author_notes:
date: 
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-27T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computers in Biology and Medicine, (199)*, pp. 111339, 2025"
publication_short: ""

abstract: Breast cancer continues to be the primary cause of mortality from cancer in women globally, highlighting the urgent necessity for early and accurate identification. Although mammogram is the gold standard for screening, several challenges still exist, such as low contrast, varying sizes of masses, and irregular mass shapes. To address these limitations, we propose MANGA-YOLO, a novel learning model for breast mass detection inspired by the Mamba and transformer architecture. Our model integrates Mamba-Inspired Attention with Contextual Awareness (MACA) to improve feature extraction by capturing long-range dependencies and enhancing contextual understanding. Additionally, we introduce a Spatial and Channel Group Attention (SCGA) module, which combines convolutional spatial refinement with group self-attention. This enriches feature representation by strengthening boundary sensitivity and emphasizing global information through a series of attention modules, thus improving the detection of masses with diverse sizes. These improvements enable more precise detection of small, low-contrast, and irregularly shaped masses. The proposed approach is evaluated on three mammography datasets – INbreast, VinDr-Mammo, and CBIS-DDSM – achieving 0.881, 0.69, and 0.664 for mAP50 metric, respectively. The results show the outperformance of our method over existing state-of-the-art models. It suggests that MANGA-YOLO offers a more robust and efficient approach to automated breast mass detection, potentially improving early diagnosis and clinical decision making. The code is available at https://github.com/Kien-Trang/MANGA-YOLO.


# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

links:
- name: "DOI"
  url: "https://doi.org/10.1016/j.compbiomed.2025.111339"

- name: "Paper"
  url: "https://www.sciencedirect.com/science/article/pii/S0010482525016932"
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
