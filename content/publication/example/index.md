---
title: "MC-Calib: A generic and robust calibration toolbox for multi-camera systems"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- F Rameau
- J Park
- Oleksandr Bailo
- In So Kweon

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2022-01-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-12T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Computer Vision and Image Understanding*
publication_short: In *CVIU*

abstract: In this paper, we present MC-Calib, a novel and robust toolbox dedicated to the calibration of complex synchronized multi-camera systems using an arbitrary number of fiducial marker-based patterns. Calibration results are obtained via successive stages of refinement to reliably estimate both the poses of the calibration boards and cameras in the system. Our method is not constrained by the number of cameras, their overlapping field-of-view (FoV), or the number of calibration patterns used. Moreover, neither prior information about the camera system nor the positions of the checkerboards are required. As a result, minimal user interaction is needed to achieve an accurate and robust calibration which makes this toolbox accessible even with limited computer vision expertise. In this work, we put a strong emphasis on the versatility and the robustness of our technique. Specifically, the hierarchical nature of our strategy allows to reliably calibrate complex vision systems even under the presence of noisy measurements. Additionally, we propose a new strategy for best-suited image selection and initial parameters estimation dedicated to non-overlapping FoV cameras. Finally, our calibration toolbox is compatible with both, perspective and fisheye cameras. Our solution has been validated on a large number of real and synthetic sequences including monocular, stereo, multiple overlapping cameras, non-overlapping cameras, and converging camera systems. Project page: https://github.com/rameau-fr/MC-Calib

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://github.com/rameau-fr/MC-Calib

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S1077314221001818'
url_code: 'https://github.com/rameau-fr/MC-Calib'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
