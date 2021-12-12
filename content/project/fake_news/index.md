---
title: Fake News Analysis
summary: Determining how to discriminate fake news with LDA 
tags:
- Deep Learning
date: "2018-12-25T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: FakeNews Wordcloud
  focal_point: Smart

# links:
# - icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Fake News has been more and more common throughout news media in nowadays. What can you do to discriminate true and fake news? Here, I conducted analysis between true and fake news using the Kaggle Fake News Dataset. I experimented using Latent Dirchlet Allocation(LDA) to detect news topics to see if fake news is biased towards which. However, using LDA document topic vectors did not achieve good accuracies in discriminating fake news. Deep learning methods including using pre-trained word embeddings and SOTA language models are still proven most effective!
