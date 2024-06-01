---
abstract: In many real-world settings, agents must learn from an offline dataset gathered by some prior behavior policy. Such a setting naturally leads to distribution shift between the behavior policy and the target policy being trained - requiring policy conservatism to avoid instability and overestimation bias. Autoregressive world models offer a different solution to this by generating synthetic, on-policy experience. However, in practice, model rollouts must be severely truncated to avoid compounding error. As an alternative, we propose policy-guided diffusion. Our method uses diffusion models to generate entire trajectories under the behavior distribution, applying guidance from the target policy to move synthetic experience further on-policy. We show that policy-guided diffusion models a regularized form of the target distribution that balances action likelihood under both the target and behavior policies, leading to plausible trajectories with high target policy probability, while retaining a lower dynamics error than an offline world model baseline. Using synthetic experience from policy-guided diffusion as a drop-in substitute for real data, we demonstrate significant improvements in performance across a range of standard offline reinforcement learning algorithms and environments. Our approach provides an effective alternative to autoregressive offline world models, opening the door to the controllable generation of synthetic training data.
slides: ""
url_pdf: https://arxiv.org/pdf/2402.12284
publication_types:
  - "1"
authors:
  - Michael Beukman
  - Samuel Coward
  - admin
  - Mattie Fellows
  - Minqi Jiang
  - Michael Dennis
  - Jakob Foerster
author_notes: []
publication: ICML 2024
summary: ""
url_dataset: ""
url_project: ""
publication_short: ""
url_source: ""
url_video: ""
title: "Refining Minimax Regret for Unsupervised Environment Design"
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
