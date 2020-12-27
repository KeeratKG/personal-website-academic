---
title: "DEAP Cache: Deep Eviction Admission and Prefetching for Cache"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Ayush Mangal 
- Jitesh Jain
- admin
- Omkar Bhalerao 


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"
- "Equal contribution"

date: "2020-09-19T00:00:00Z"
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
#publication_short: In *ICW*

abstract: Recent approaches for learning policies to improve caching, target just one out of the prefetching, admission and eviction processes. In contrast, we propose an end to end pipeline to learn all three policies using machine learning. We also take inspiration from the success of pretraining on large corpora to learn specialized embeddings for the task. We model prefetching as a sequence prediction task based on past misses. Following previous works suggesting that frequency and recency are the two orthogonal fundamental attributes for caching, we use an online reinforcement learning technique to learn the optimal policy distribution between two orthogonal eviction strategies based on them. While previous approaches used the past as an indicator of the future, we instead explicitly model the future frequency and recency in a multi-task fashion with prefetching, leveraging the abilities of deep networks to capture futuristic trends and use them for learning eviction and admission. We also model the distribution of the data in an online fashion using Kernel Density Estimation in our approach, to deal with the problem of caching non-stationary data. We present our approach as a "proof of concept" of learning all three components of cache strategies using machine learning and leave improving practical deployment for future work.

# Summary. An optional shortened abstract.
summary: Submitted to AAAI 2021 as a Student Abstract.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2009.09206'
url_code: 'https://github.com/vlgiitr/deep_cache_replacement'
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
