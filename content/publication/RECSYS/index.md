---
title: "Interpretable Contextual Team-aware Item Recommendation: Application in Multiplayer Online Battle Arena Game"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Vladimir Araujo
- Francisca Cattan
- Denis Parra

# Author notes (optional)
author_notes:
- "Main author"

date: "2020-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR*

abstract: The video game industry has adopted recommendation systems to boost users interest with a focus on game sales. Other exciting applications within video games are those that help the player make decisions that would maximize their playing experience, which is a desirable feature in real-time strategy video games such as Multiplayer Online Battle Arena (MOBA) like as DotA and LoL. Among these tasks, the recommendation of items is challenging, given both the contextual nature of the game and how it exposes the dependence on the formation of each team. Existing works on this topic do not take advantage of all the available contextual match data and dismiss potentially valuable information. To address this problem we develop TTIR, a contextual recommender model derived from the Transformer neural architecture that suggests a set of items to every team member, based on the contexts of teams and roles that describe the match. TTIR outperforms several approaches and provides interpretable recommendations through visualization of attention weights. Our evaluation indicates that both the Transformer architecture and the contextual information are essential to get the best results for this item recommendation task. Furthermore, a preliminary user survey indicates the usefulness of attention weights for explaining recommendations as well as ideas for future work. The code and dataset are available at https://github.com/ojedaf/IC-TIR-Lol.

# Summary. An optional shortened abstract.
summary:  We develop TTIR, a contextual recommender model derived from the Transformer neural architecture that suggests a set of items to every team member, based on the contexts of teams and roles that describe the match. TTIR outperforms several approaches and provides interpretable recommendations through visualization of attention weights.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: https://ojedaf.github.io/tnt_site/

url_pdf: 'https://dl.acm.org/doi/10.1145/3383313.3412211'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
