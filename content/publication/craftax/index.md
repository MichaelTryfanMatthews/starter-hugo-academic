---
abstract: Benchmarks play a crucial role in the development and analysis of reinforcement learning (RL) algorithms. We identify that existing benchmarks used for research into open-ended learning fall into one of two categories. Either they are too slow for meaningful research to be performed without enormous computational resources, like Crafter, NetHack and Minecraft, or they are not complex enough to pose a significant challenge, like Minigrid and Procgen. To remedy this, we first present Craftax-Classic, a ground-up rewrite of Crafter in JAX that runs up to 250x faster than the Python-native original. A run of PPO using 1 billion environment interactions finishes in under an hour using only a single GPU and averages 90% of the optimal reward. To provide a more compelling challenge we present the main Craftax benchmark, a significant extension of the Crafter mechanics with elements inspired from NetHack. Solving Craftax requires deep exploration, long term planning and memory, as well as continual adaptation to novel situations as more of the world is discovered. We show that existing methods including global and episodic exploration, as well as unsupervised environment design fail to make material progress on the benchmark. We believe that Craftax can for the first time allow researchers to experiment in a complex, open-ended environment with limited computational resources.
slides: ""
url_pdf: https://arxiv.org/abs/2402.16801
publication_types:
  - "1"
authors:
  - admin
  - Michael Beukman
  - Benjamin Ellis
  - Mikayel Samvelyan
  - Matthew Jackson
  - Samuel Coward
  - Jakob Foerster
author_notes: []
publication: ICML 2024 (Spotlight)
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: "Craftax: A Lightning-Fast Benchmark for Open-Ended Reinforcement Learning"
doi: ""
featured: false
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: false
date: 2024-06-01T18:37:16.642Z
url_slides: ""
publishDate: 2024-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---
