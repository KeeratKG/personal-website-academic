---
title: "VacSIM: Learning Effective Strategies for COVID-19 Vaccine Distribution using Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Raghav Awasthi 
- admin
- Arshita Bhatt
- Mehrab Singh Gill
- Aditya Nagori
- Ponnurangam Kumaraguru
- Tavpritesh Sethi


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2020-09-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: On *arxiv*
#publication_short: In Elsevier's *IBM*

abstract: A COVID-19 vaccine is our best bet for mitigating the ongoing onslaught of the pandemic. However, vaccine is also expected to be a limited resource. An optimal allocation strategy, especially in countries with access inequities and a temporal separation of hot-spots might be an effective way of halting the disease spread. We approach this problem by proposing a novel pipeline VacSIM that dovetails Actor-Critic using Kronecker-Factored Trust Region (ACKTR) model into a Contextual Bandits approach for optimizing the distribution of COVID-19 vaccine. Whereas the ACKTR model suggests better actions and rewards, Contextual Bandits allow online modifications that may need to be implemented on a day-to-day basis in the real world scenario. We evaluate this framework against a naive allocation approach of distributing vaccine proportional to the incidence of COVID-19 cases in five different States across India and demonstrate up to 100,000 additional lives potentially saved and a five-fold increase in the efficacy of limiting the spread over a period of 30 days through the VacSIM approach. We also propose novel evaluation strategies including a standard compartmental model based projections and a causality preserving evaluation of our model. Finally, we contribute a new Open-AI environment meant for the vaccine distribution scenario, and open-source VacSIM for wide testing and applications across the globe.

# Summary. An optional shortened abstract.
summary: Published in Elsevier's Intelligence Based Medicine journal. Also presented at the RAISE Summit 2020 & MIT’s 'Vaccines For All' Conference.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Paper
  url: https://www.sciencedirect.com/science/article/pii/S2666521222000138

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

