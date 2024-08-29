---
title: "Quantitave Imaging for Particle Beam Microscopy"
#subtitle: "* Manuscript in preparation *"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Vaibhav Choudhary
- Akshay Agarwal
- Vivek Goyal

# Author notes (optional)
author_notes:
 - "Boston University"
 - "Boston University"
 - "Boston University"

#date: "2013-07-01T00:00:00Z"
#doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
# publication: In *Wowchemy Conference*
# publication_short: In *ICW*



# Summary. An optional shortened abstract.
summary:   New quantitative and physics-informed methods for secondary electron imaging in particle beam microscopy (*Manuscript in preparation* ).<span style="color:blue">Read more...</span>

#tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
  caption: "Particle Beam Microscopy"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

In this paper, we discuss a new physics-inspired forward process for imaging samples made from two different materials under a PBM. Under this model, the SE yield is taken to be a measurement of a sample property at that scan location and is distributed as a Truncated two-component Poisson Mixture. We show that this mixture distribution is generally more informative about the SE yield than using a Poisson distribution with a mean given by the beam's convolution with the sample, as has been done conventionally.  We further leverage this mixture model to derive new estimators for edge localization. Thus, our new model allows us to quantitatively give the boundary between the two materials on a grid as opposed to the prior work on post-processing and qualitative improvements on images obtained from the SE counts. We show that the edge position estimation using the Mixture-Model-based estimators can be done more accurately than the beam width used for scanning the sample. We also compare the new edge estimators to an estimator based on the previous convolution-based forward model and show that our new estimators have lesser variance in edge localization on datasets acquired from an SEM.
