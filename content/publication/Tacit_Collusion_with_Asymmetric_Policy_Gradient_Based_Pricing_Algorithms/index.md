---
title: 'Tacit Collusion with Asymmetric Policy Gradient-Based Pricing Algorithms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  # - Robert Ford

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-09-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: "Algorithms are increasingly taking precedence over humans in the pricing of goods and services, empowering firms to swiftly respond to market shifts with unparalleled precision. The current experimental algorithmic pricing literature as solely investigated the collusive capacity of either: (1) slow tabular-based reinforcement learning algorithms, (2) algorithms restricted to dealing with discrete action spaces, or (3) entirely homogeneous AI systems. Additionally, studies have largely avoided transfer learning: the ability of a trained reinforcement learning-based pricing algorithm agent to transfer knowledge from the learning environment to a potentially different ecosystem. Skeptics of tacit algorithmic collusion argue that these voids diminish the practical plausibility of this phenomenon. The first part of this paper shows that two state-of-the-art asymmetric deep reinforcement learning algorithms, Proximal Policy Optimization (PPO) and Soft Actor Critic (SAC), acting in a Bertrand-Markov pricing game with continuous action spaces converge to anti-competitive policies in a much shorter time than that previously reported. These collusive outcomes are sustained through the implementation of learned trigger strategies. Subsequently, the latter section shows that these algorithms can be trained in one environment and successfully transfer this knowledge to similarly related environments retaining supracompetitive outcomes."

# Summary. An optional shortened abstract.
summary: I explore the collusive capacity of asymmetric policy gradient-based pricing algorithms acting in a continuous action space and their ability to transfer this collusive power to unknown environments.

tags:
  - Deep Reinforcement Learning
  - Industrial Organization
  - Game Theory

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ''
  # preview_only: false

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

<!-- This work is largely driven by the results in my [previous paper](/publication/When_Asymmetric_Pricing_Algorithms_Collide/) on algorithmic pricing fixing. -->
