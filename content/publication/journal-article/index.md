---
title: "Exploration of high dimensional free energy landscapes by a combination of temperature‐accelerated sliced sampling and parallel biasing"
authors:
- Abhinav Gupta
- Shivani Verma
- Ramsha Javed
- admin
- Saurabh Srivastava
- Nisanth N. Nair
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-06-30"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-30"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Computational Chemistry*(1)"
publication_short: "JCC"

abstract: Temperature‐accelerated sliced sampling (TASS) is an enhanced sampling method for achieving accelerated and controlled exploration of high‐dimensional free energy landscapes in molecular dynamics simulations. With the aid of umbrella bias potentials, the TASS method realizes a controlled exploration and divide‐and‐conquer strategy for computing high‐dimensional free energy surfaces. In TASS, diffusion of the system in the collective variable (CV) space is enhanced with the help of metadynamics bias and elevated‐temperature of the auxiliary degrees of freedom (DOF) that are coupled to the CVs. Usually, a low‐dimensional metadynamics bias is applied in TASS. In order to further improve the performance of TASS, we propose here to use a highdimensional metadynamics bias, in the same form as in a parallel bias metadynamics scheme. Here, a modified reweighting scheme, in combination with artificial neural network is used for computing unbiased probability distribution of CVs and projections of high‐dimensional free energy surfaces. We first validate the accuracy and efficiency of our method in computing the four‐dimensional free energy landscape for alanine tripeptide in vacuo. Subsequently, we employ the approach to calculate the eight‐dimensional free energy landscape of alanine pentapeptide in vacuo. Finally, the method is applied to a more realistic problem wherein we compute the broad four‐dimensional free energy surface corresponding to the deacylation of a drug molecule which is covalently complexed with a <jats:italic>β</jats:italic>‐lactamase enzyme. We demonstrate that using parallel bias in TASS improves the efficiency of exploration of high‐dimensional free energy landscapes.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Source Themes
# featured: false

# hugoblox:
  # ids:
    # arxiv: 1512.04133v1

links:
  - type: pdf
    url: http://onlinelibrary.wiley.com/doi/epdf/10.1002/jcc.26882
  # - type: code
    # url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
    # url: ""
  # - type: poster
    # url: ""
  # - type: project
    # url: ""
  # - type: slides
    # url: https://www.slideshare.net/
  # - type: source
    # url: ""
  # - type: video
    # url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  # focal_point: ""
  # preview_only: false

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

# {{% callout note %}}
# Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the *Slides* button to check out the example.
# {{% /callout %}}

My contribution to this work includes training **Artificial Neural Networks (ANNs)** to approximate Free Energy Surfaces obtained from the sampling method, PBTASS, developed by Dr. Abhinav Gupta. The architecture and details are given in the [Supplementary Paper](https://onlinelibrary.wiley.com/action/downloadSupplement?doi=10.1002%2Fjcc.26882&file=jcc26882-sup-0001-supinfo.pdf). The code was written in **Python** programming language using the **PyTorch** machine learning package.  
