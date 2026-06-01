---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **Ph.D.** in Electronics, Babol Noshirvani University of Technology, Babol, Iran (2014–2020)
  - Thesis: *Building Damage Assessment after Natural Disasters by Fusion of Earth Observation Images*
- **M.Sc.** in Electronics, Iran University of Science and Technology, Tehran, Iran (2011–2014)
  - Thesis: *Proposing Parallel Data Stream Clustering Algorithm Based on GPU*
- **B.Sc.** in Electronics, Shahid Beheshti University, Tehran, Iran (2006–2011)

---

## Positions

- **Senior Lecturer** — Karlstad University, Geomatics, Department of Environmental and Life Sciences, Sweden (2026–Present)
- **Postdoctoral Researcher** — Linköping University, Institute for Analytical Sociology (IAS), Sweden (2025–Present)
- **Postdoctoral Researcher** — Chalmers University of Technology, Data Science and AI Division, Gothenburg, Sweden (2021–2025)
- **Postdoctoral Researcher** — Babol Noshirvani University of Technology, Babol, Iran (2020–2021)
- **Visiting PhD Student** — KTH Royal Institute of Technology, Geoinformatics Division, Stockholm, Sweden (2017–2018)

---

## Teaching

- Introduction to Data Science and AI — Chalmers University of Technology
- Design of AI Systems — Chalmers University of Technology
- Deep Statistics: AI and Earth Observations for Sustainable Development — Harvard University
- AI for Earth and Environmental Sciences — University of Gothenburg
- Microprocessor and Assembly Language — Babol Noshirvani University of Technology
- Digital Systems — Babol Noshirvani University of Technology

---

## Skills

- **Machine Learning / Deep Learning**: CNNs, self-supervised learning, Bayesian/probabilistic models, time-series models, Random Forest, SVMs
- **Earth Observation**: Multispectral (Landsat, Sentinel-2), radar/SAR (Sentinel-1), VHR imagery
- **Platforms & Tools**: Google Earth Engine, PyTorch, TensorFlow, CUDA/GPU computing, Python
- **GIS & Geospatial**: Land cover mapping, spatial analysis, urban analytics, big geospatial data management

---

## Publications

{% if site.publications %}
{% assign sorted_pubs = site.publications | sort: 'date' | reverse %}
{% for post in sorted_pubs %}
  {% include archive-single-cv.html %}
{% endfor %}
{% endif %}

---

## Public Datasets & Products

- **Iran Land Cover Map** — National-scale land cover classification using Sentinel imagery
- **Time-Series Africa Urban-Rural Map** — Continental settlement map using deep learning
- **Time-Series Africa Poverty Map** — Poverty estimation across Africa
- **ELC10: European 10 m Land Cover Map 2018** — High-resolution European land cover

---

## Web Applications

- [Urban Area Extraction](https://ee-mohammadkakooei.projects.earthengine.app/)
- [Africa Poverty Map](https://ee-mohammadkakooei.projects.earthengine.app/)
- [Africa Urban-Rural Map](https://ee-mohammadkakooei.projects.earthengine.app/)

---

## Collaborations

KTH Royal Institute of Technology · Harvard University · University of Gothenburg · Chalmers University of Technology · AI Sweden · UNHCR · Linköping University
