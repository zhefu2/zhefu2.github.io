---
title: "From Interaction to Prediction: A Multi-interactive Attention-based Approach to Product Rating Prediction"
collection: publications
category: manuscripts
permalink: /publication/2025-01-paper-title-number
excerpt: 'Li Yu, Wei Gong, Dongsong Zhang, Yu Ding, <b>Zhe Fu</b>'
date: 2025-01-17
venue: 'INFORMS Journal on Computing'
paperurl: 'http://zhefu2.github.io.github.io/files/JOc2025.pdf'
---
Despite increasing research on product rating prediction, very few studies have considered user-item interaction relationships at multiple levels. To address this critical limitation, we propose a novel rating prediction method based on multi-interaction attention (RPMIA) by learning user-item interaction relationships at three levels simultaneously from online consumer reviews for predicting product ratings with reasonable interpretability. Specifically, RPMIA first deploys a multihead cross-attention mechanism to capture the interaction between contexts of items and users. Then, it uses a bilayer gate-based mechanism to extract the aspects of items and users and a self-attention mechanism to learn their interaction at the aspect level. Finally, the aspects of users and items are coupled together to form meaningful user-item aspect pairs via a joint attention. A multitask predictor that integrates a factorization machine and a feedforward neural network is designed to generate a rating prediction. We empirically evaluated RPMIA with seven real-world data sets. The results demonstrate that RPMIA outperforms the state-of-the-art methods consistently and significantly. We also conduct a user study to assess the interpretability of the RPMIA method.
