---
title: "Automated EEG Reporting Pipeline for Infant Resting-State Analysis"
authors:
- Chen Xie
date: "2025-06-01"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-01"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["software"]

# Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: Manual resting-state EEG reporting for infants is time-consuming and hard for families to interpret. We present an end-to-end pipeline that automates infant EEG reporting and generates family-readable summaries grounded in spectral analysis. The system ingests data, performs preprocessing and artifact handling, and computes power spectral density, band power, and age-normed indices. A lightweight GUI supports full-workflow monitoring and exception handling. To produce plain-language narratives while preserving privacy, we deploy local large language models (Qwen2.5-7B, DeepSeek-V) to condition on structured spectral outputs and render individualized reports. In deployment to 300+ participants from the CBCP cohort, the pipeline delivered age-referenced, frequency-band reports with per-subject textual summaries and reduced report turnaround by ~3 days, improving throughput. This work demonstrates a practical path to scalable, privacy-conserving EEG reporting in early childhood settings and a template for integrating analytical pipelines with on-device language models for clinical communication.

# Summary. An optional shortened abstract.
summary: 

tags:
- Automated Reporting for Infant EEG

featured: true

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
# - type: preprint
#   provider: arxiv
#   id: 1512.04133v1
- type: code
  url: https://github.com/xxxie-cccs/Resting-EEG-report-GUI-demo
# - type: slides
#   url: https://www.slideshare.net/
# - type: dataset
#   url: "#"
# - type: poster
#   url: "#"
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'GUI interface schematic with corresponding step input parameters. Click the button below to run'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
<!-- 
This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
