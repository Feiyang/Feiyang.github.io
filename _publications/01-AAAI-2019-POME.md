---
title: "Policy Optimization with Model-based Explorations"
collection: publications
permalink: /publications/POME
excerpt: "Policy Optimization with Model-based Explorations"
date: 2018-11-18
venue: "AAAI"
year: 2019
paperurl: "https://aaai.org/ojs/index.php/AAAI/article/view/4392"
authorlist: "Feiyang Pan, Qingpeng Cai, An-Xiang Zeng, Chun-Xiang Pan, Qing Da, Hualin He, Qing He, Pingzhong Tang"
citation: "Feiyang Pan, Qingpeng Cai, An-Xiang Zeng, Chun-Xiang Pan, Qing Da, Hualin He, Qing He, Pingzhong Tang. Policy Optimization with Model-based Explorations. In AAAI 2019."
status: 'pub'
---
**Abstract:**
Model-free reinforcement learning methods such as the Proximal Policy Optimization algorithm (PPO) have successfully applied in complex decision-making problems such as Atari games. However, these methods suffer from high variances and high sample complexity. On the other hand, model-based reinforcement learning methods that learn the transition dynamics are more sample efficient, but they often suffer from the bias of the transition estimation. How to make use of both model-based and model-free learning is a central problem in reinforcement learning. In this paper, we present a new technique to address the trade-off between exploration and exploitation, which regards the difference between model-free and model-based estimations as a measure of exploration value. We apply this new technique to the PPO algorithm and arrive at a new policy optimization method, named Policy Optimization with Model-based Explorations (POME). POME uses two components to predict the actions" target values: a model-free one estimated by Monte-Carlo sampling and a model-based one which learns a transition model and predicts the value of the next state. POME adds the error of these two target estimations as the additional exploration value for each state-action pair, i.e, encourages the algorithm to explore the states with larger target errors which are hard to estimate. We compare POME with PPO on Atari 2600 games, and it shows that POME outperforms PPO on 33 games out of 49 games.

**Download: [[PDF]](https://aaai.org/ojs/index.php/AAAI/article/view/4392)**
