---
title: "Follow the Prophet: Accurate Online Conversion Rate Prediction in the Face of Delayed Feedback"
collection: publications
permalink: /publications/FollowTheProphet
excerpt: "Follow the Prophet: Accurate Online Conversion Rate Prediction in the Face of Delayed Feedback"
date: 2021-04-15
venue: "SIGIR"
year: 2021
paperurl: "https://dl.acm.org/doi/abs/10.1145/3404835.3463045"
authorlist: "Haoming Li, Feiyang Pan, Xiang Ao, Zhao Yang, Min Lu, Junwei Pan, Dapeng Liu, Lei Xiao, Qing He"
status: 'pub'
---
**Abstract:**
The delayed feedback problem is one of the imperative challenges in online advertising, which is caused by the highly diversified feedback delay of a conversion varying from a few minutes to several days. It is hard to design an appropriate online learning system under these non-identical delay for different types of ads and users. In this paper, we propose to tackle the delayed feedback problem in online advertising by "Following the Prophet" (FTP for short). The key insight is that, if the feedback came instantly for all the logged samples, we could get a model without delayed feedback, namely the "prophet". Although the prophet cannot be obtained during online learning, we show that we could predict the prophet's predictions by an aggregation policy on top of a set of multi-task predictions, where each task captures the feedback patterns of different periods. We propose the objective and optimization approach for the policy, and use the logged data to imitate the prophet. Extensive experiments on three real-world advertising datasets show that our method outperforms the previous state-of-the-art baselines..

**Download: [[ACM website]](https://dl.acm.org/doi/abs/10.1145/3404835.3463045)**
