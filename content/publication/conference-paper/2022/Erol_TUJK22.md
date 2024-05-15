---
title: 'Performance Analysis of Real-Time Multi-GNSS Precise Point Positioning Technique'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Serdar Erol
  - admin
  - Reha Metin Alkan

# Author notes (optional)
author_notes:
  - 
  - 'Corresponding author'

date: '2022-11-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Türkiye Ulusal Jeodezi Komisyonu 2022 Yılı Bilimsel Toplantısı*
publication_short: In *TUJK22*

abstract: The Single-baseline Real-time Kinematic method was used in applications where real-time high accurate positioning is required. Studies carried out to eliminate some of the limitations in this method have brought up the idea of adding real-time positioning feature to Continuously Operating Reference Stations, thus Network-RTK (Network-RTK) method has emerged. The Network-RTK method offers a homogeneous accuracy in the centimeter level. However, in the Network-RTK method, it is necessary to have a reference network consisting of reference stations whose position is known with high accuracy, as well as a strong communication infrastructure is required to transmit the data of the stations to the control center and to transmit the obtained corrections to the rover receiver. Studies to eliminate these requirements in both RTK methods have led to the emergence of the technique called Precise Point Positioning (PPP). An average of 10-30 minutes of convergence time is required in order to achieve centimeter-decimeter accuracy with this method. This is a major shortcoming of PPP and significantly limits its usability in real-time applications. Within the scope of the IGS-RTS (The International GNSS Service-Real-Time Service) project launched in 2013, the production of real-time precise satellite orbit and clock corrections and code/phase biases in addition to broadcasted ephemeris was started, as a result of that real-time PPP (RT-PPP) concept emerged. The IGS-RTS products used in this method are calculated by IGS analysis centers, formatted according to the RTCM State Space Representation (SSR) standard, and streamed real-time via the Internet with the NTRIP (The Networked Transport of RTCM via Internet Protocol) protocol. In the RT-PPP method, users need a computer/receiver connected to the internet and with a suitable software installed in order to take real-time corrections and GNSS measurements. Therefore, various interruptions in the data and correction retrieval process may limit real-time positioning or cause it to be impossible at all. For RT-PPP applications, real-time products in SSR format are offered by other institutions besides IGS. In this context, in addition to IGS Analysis Centers such as BKG, CAS, CNES, DLR, GFZ, GMV and WHU, real-time satellite orbit and clock correction services such as NAVCAST and MADOCA are available. In this study, approximately 10 hours of real-time PPP application was carried out using the data of ISTA station, which is the only IGS-RTS point streaming real-time data in Türkiye. Correction products of IGS-RTS's CNES and BKG analysis centers and NAVCAST service were used in the study. RT-PPP solutions was done by using the aforementioned correction products with GPS-only, Galileo-only, and combination of both satellite systems. According to the results obtained from the study, it has been seen that it is possible to reach 1 dm horizontal and 2 dm vertical accuracies in the solutions obtained from all correction products. It has been seen that the RT-PPP accuracy and convergence performance obtained by using GPS and Galileo systems together are more successful than the results obtained by using a single system. On the other hand, the solutions obtained using only the Galileo satellite system could not provide the cm-dm accuracy expected from the RT-PPP technique. In general, the obtained results show that the performance of the RT-PPP method depends on the used service, the analysis center and also the software and monitoring network used in the production of corrections. As a result, it has been seen that the most important key factor in obtaining real-time PPP solution by using the correction products of services such as IGS and NAVCAST is a stable, uninterrupted and high-quality internet connection.

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/publication/365127653_Gercek-Zamanli_Coklu-GNSS_Hassas_Nokta_Konumlama_Multi-GNSS_RT-PPP_Tekniginin_Performansinin_Incelenmesi_Performance_Analysis_of_Real-Time_Multi-GNSS_Precise_Point_Positioning_Technique'
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


