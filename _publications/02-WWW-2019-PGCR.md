---
title: "Policy Gradients for Contextual Recommendations"
collection: publications
permalink: /publications/PGCR
excerpt: "Policy Gradients for Contextual Recommendations"
date: 2018-12-01
venue: "WWW"
year: 2019
paperurl: "https://arxiv.org/abs/1802.04162"
authorlist: "Feiyang Pan, Qingpeng Cai, Pingzhong Tang, Fuzhen Zhuang, Qing He"
citation: "Feiyang Pan, Qingpeng Cai, Pingzhong Tang, Fuzhen Zhuang, Qing He. 2019. Policy Gradients for Contextual Recommendations. In Proceedings of the 2019 World Wide Web Conference (WWW'19), May 13-17, 2019, San Francisco, CA, USA. ACM, New York, NY, USA, 11 pages. https://doi.org/10.1145/3308558.3313616"
status: 'pub'
---
**Abstract:**
Decision making is a challenging task in online recommender systems. The decision maker often needs to choose a contextual item at each step from a set of candidates. Contextual bandit algorithms have been successfully deployed to such applications, for the trade-off between exploration and exploitation and the state-of-art performance on minimizing online costs. However, the applicability of existing contextual bandit methods is limited by the over-simplified assumptions of the problem, such as assuming a simple form of the reward function or assuming a static environment where the states are not affected by previous actions. In this work, we put forward Policy Gradients for Contextual Recommendations (PGCR) to solve the problem without those unrealistic assumptions. It optimizes over a restricted class of policies where the marginal probability of choosing an item (in expectation of other items) has a simple closed form, and the gradient of the expected return over the policy in this class is in a succinct form. Moreover, PGCR leverages two useful heuristic techniques called Time-Dependent Greed and Actor-Dropout. The former ensures PGCR to be empirically greedy in the limit, and the latter addresses the trade-off between exploration and exploitation by using the policy network with Dropout as a Bayesian approximation. PGCR can solve the standard contextual bandits as well as its Markov Decision Process generalization. Therefore it can be applied to a wide range of realistic settings of recommendations, such as personalized advertising. We evaluate PGCR on toy datasets as well as a real-world dataset of personalized music recommendations. Experiments show that PGCR enables fast convergence and low regret, and outperforms both classic contextual-bandits and vanilla policy gradient methods.

**Download: [[PDF]](https://arxiv.org/abs/1802.04162)**
