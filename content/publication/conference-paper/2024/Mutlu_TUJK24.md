---
title: 'Precipitation forecast using GNSS technique and artificial neural network model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Serdar Erol

# Author notes (optional)
author_notes:
  - 'Corresponding author'

date: '2024-11-06T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-11-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Türkiye Ulusal Jeodezi Komisyonu 2024 Yılı Bilimsel Toplantısı*
publication_short: In *TUJK24*

abstract: Meteorological events in the troposphere, which is the lowest layer of the atmosphere, affect GNSS signals and delay the signals from reaching the Earth's surface. The precipitable water vapor (PWV) value calculated as a function of these tropospheric delay values is an indicator of the potential precipitation information that will emerge. Considering the unstable weather events caused by global warming, the use of GNSS-based data in addition to meteorological station data in near-real-time weather forecasts has become important in order to increase both spatial and temporal resolution. Numerous meteorological parameters influence precipitation, both directly and indirectly. Therefore, analyzing how a deep learning model performs when utilizing all of this data at once is a crucial area of research. Within the scope of this study, short-term precipitation prediction was carried out using the artificial neural network (ANN) approach, using GNSS and meteorological station data as input. This study used a feed-forward nonlinear autoregressive exogenous (NARX) neural network model for 30-minute precipitation prediction. As inputs to the model, GNSS-based tropospheric delay (wet, dry, total) and PWV values; relative humidity, pressure, wet and dry temperature measurements obtained from the meteorological sensor of the GNSS station; and precipitation rate data of NASA's Integrated Multi-satellite Retrievals for Global Precipitation Measurement (IMERG) project were used. The artificial neural network architecture consists of a 10-neuron hidden layer and a 1-neuron output layer, and the sigmoid function was preferred as the activation function. In this study, GNSS observation data with a 30-second sampling rate of the ISTA station of the International GNSS Service (IGS) network in 2021 were used. Tropospheric delay values were calculated using the open-source PRIDE PPP-AR software, and PWV values were derived from these delay values. The input data of the model were grouped as 60% training, 10% validation and 30% test. The predicted precipitation rate values were classified as no rain if there were 0 mm/hour, moderated rain if there were less than 5 mm/hour, and intense rain if there were greater than 5 mm/hour. In order to evaluate the performance of the model, the classification resulting from the prediction was compared with the true classes, and it was found that the overall classification success was over 90%.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'http://dx.doi.org/10.13140/RG.2.2.24315.63525'
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
  focal_point: ''
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


