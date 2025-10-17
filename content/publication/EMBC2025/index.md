---
title: 'BEAM: Brainwave Empathy Assessment Model for Early Childhood'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chen Xie
  - Gaofeng Wu
  - Kaidong Wang
  - Zihao Zhu
  - Xiaoshu Luo
  - Yan Liang
  - Feiyu Quan
  - Ruoxi Wu
  - Xianghui Huang
  - Han Zhang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-04-10'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-27'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *47th AnnualInternational Conference of the lEEE Engineering in Medicine and Biology Society*
publication_short: In *EMBC 2025*

abstract: Empathy in young children is crucial for their social and emotional development, yet predicting it remains challenging. Traditional methods often only rely on self-reports or observer-based labeling, which are susceptible to bias and fail to objectively capture the process of empathy formation. EEG offers an objective alternative; however, current approaches primarily extract static patterns, neglecting temporal dynamics. To overcome these limitations, we propose a novel deep learning framework, the Brainwave Empathy Assessment Model (BEAM), to predict empathy levels in children aged 4 to 6 years. BEAM leverages multi-view EEG signals to capture both cognitive and emotional dimensions of empathy. The framework comprises three key components- 1) a LaBraM-based encoder for effective spatio-temporal feature extraction, 2) a feature fusion module to integrate complementary information from multi-view signals, and 3) a contrastive learning module to enhance class separation. Validated on the CBCP dataset, BEAM outperforms state-of-the-art methods across multiple metrics, demonstrating its potential for objective empathy assessment and providing a preliminary insight into early interventions in children’s prosocial development.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Empathy Assessment from Pediatric EEG

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 10.5555/123456

# Custom links
# links:
#   - type: pdf
#     url: ""
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  filename: featured.jpg            # 明确指定用哪张图（放在与 index.md 同目录）
  alt_text: "BEAM architecture diagram"   # 无障碍/SEO
  caption: "Overall architecture of the proposed method."
  focal_point: Smart                # 智能裁剪，尽量保留主体
  preview_only: false               # false=页头也显示；true=只在列表卡片显示

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
