---
title: "The performance analysis of the post-mission web-based static and kinematic PPP-AR service"
authors:
- admin
- Serdar Erol
- Reha Metin Alkan

author_notes:
- "Corresponding Author"
date: "2023-11-09T00:00:00Z"
doi: "https://doi.org/10.17794/rgn.2023.4.9"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-09T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Rudarsko-geološko-naftni zbornik, 38*(4)"
publication_short: ""

abstract: The use of the Precise Point Positioning (PPP) technique has become very advantageous with the development of GNSS positioning technology. It is possible to get highly accurate position information without the need of any reference station data using the PPP technique. However, there are various factors that affect the accuracy of PPP solutions, including the initial phase ambiguity solution type, which can be fixed or float, atmospheric effects, observation length, used satellite systems, and used precise products. The Canadian Spatial Reference System-Precise Point Positioning (CSRS-PPP) service, one of the online PPP services, was updated on October 20th, 2020, and upgraded to version 3, capable of the Ambiguity-Fixed (PPP-AR) solution. Prior to this date, the service had offered the Ambiguity-Float (PPP-Float) solution. In this study, it is aimed to investigate the effect of using different satellite systems (GPS, GPS&GLONASS), length of observation time, static/kinematic processing modes, and initial phase ambiguity solution types on PPP accuracy. The daily observation data of ANKR, ISTA, IZMI, MERS, and KRS1 IGS GNSS stations located within the borders of Türkiye, divided into different sub-sessions (1-hour, 2-hours, 4-hours, 8-hours, and 12-hours) were processed using CSRS-PPP web-based service as PPP-Float before the update and PPP-AR after the update. As a result of the comparison, the combined use of GPS & GLONASS satellite systems instead of using GPS satellites alone has increased horizontal and vertical accuracy in both static/kinematic PPP-Float and PPP-AR solutions. Considering the static solutions, horizontal and vertical position accuracies increase as the observation time increases in both ambiguity solution methods using different constellations. In the case of comparison of the ambiguity solution methods, it was found that the PPP-AR approach offered higher accuracy than the PPP-Float in all solution cases.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://hrcak.srce.hr/en/file/447303'
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
  caption: ''
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
slides: ''
---