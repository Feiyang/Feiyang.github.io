---
title: "Field-aware calibration: a simple and empirically strong method for reliable probabilistic predictions"
collection: publications
permalink: /publications/calibration
excerpt: "Field-aware calibration: a simple and empirically strong method for reliable probabilistic predictions"
date: 2020-01-11
venue: "WWW"
year: 2020
paperurl: "https://arxiv.org/abs/1905.10713"
video: "https://youtu.be/_uQlorn1X5A"
authorlist: "Feiyang Pan, Xiang Ao, Pingzhong Tang, Min Lu, Dapeng Liu, Lei Xiao and Qing He"
citation: "Feiyang Pan, Xiang Ao, Pingzhong Tang, Min Lu, Dapeng Liu, Lei Xiao and Qing He. 2020. Field-aware calibration: a simple and empirically strong method for reliable probabilistic predictions. In Proceedings of the 2020 World Wide Web Conference (WWW'19), May 13-17, 2019, San Francisco, CA, USA. ACM, New York, NY, USA, 11 pages. https://doi.org/10.1145/3308558.3313616"
status: 'acc'
---
**Abstract:**
It is often observed that the probabilistic predictions given by a machine learning model can disagree with averaged actual outcomes on specific subsets of data, which is also known as the issue of miscalibration. It is responsible for the unreliability of practical machine learning systems. For example, in online advertising, an ad can receive a click-through rate prediction of 0.1 over some population of users where its actual click rate is 0.15. In such cases, the probabilistic predictions have to be fixed before the system can be deployed.

In this paper, we first introduce a new evaluation metric named **field-level calibration error** that measures the bias in predictions over the sensitive input field that the decision-maker concerns. We show that existing post-hoc calibration methods have limited improvements in the new field-level metric and other non-calibration metrics such as the AUC score. To this end, we propose **Neural Calibration**, a simple yet powerful post-hoc calibration method that learns to calibrate by making full use of the field-aware information over the validation set. We present extensive experiments on five large-scale datasets. The results showed that Neural Calibration significantly improves against uncalibrated predictions in common metrics such as the negative log-likelihood, Brier score and AUC, as well as the proposed field-level calibration error.

**Download: [[PDF]](https://arxiv.org/abs/1905.10713)**
**Video: [[YouTube video]](https://youtu.be/_uQlorn1X5A)**
