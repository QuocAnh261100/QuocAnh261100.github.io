---
title: "Designing Search Space for Unbounded Bayesian Optimization via Transfer Learning"
collection: publications
category: conferences
permalink: /publication/transfer_BO
excerpt: 'This paper introduces a transfer-learning-based Bayesian Optimization algorithm that automatically designs promising search spaces without needing prior knowledge, overcomes restrictive assumptions, and outperforms state-of-the-art methods across benchmarks.'
date: 2025-07-29
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence'
slidesurl: #
paperurl: #
citation: '<b>Quoc-Anh Hoang Nguyen*</b>, The Hung Tran*, Sunil Gupta, Dung D. Le'
---

Abstract
------

Bayesian optimization (BO) is a powerful method for optimizing expensive black-box functions and has been successfully applied across various scenarios. While traditional BO algorithms optimize each task in isolation, there has been recent interest in speeding up BO by transferring knowledge across similar previous tasks. However, most recent studies on this problem are based on two implicit assumptions that (1) the search space of the test task (the ultimate task the model aims to solve) needs to be defined suitably a priori and (2) the optimum of the test task is very close to the evaluations of the previous tasks. These restrictive assumptions limit BO's applicability in real-world scenarios. In this paper, we propose an approach that leverages transfer learning to design promising search spaces for BO, thereby overcoming these limitations. Our approach eliminates the need for prior knowledge of the search spaces of both the test and previous tasks while also relaxing the assumption that the test task’s optimum is close to evaluations of previous tasks. We propose a novel BO algorithm to automatically design promising search spaces for BO, not only exploiting regions near good evaluations of previous tasks but also exploring other promising regions using strategy shifting and expanding the search space. Our algorithm leverages both task similarity measurements and the best evaluation achieved so far for the test task. Further, theoretically, we prove that our proposed algorithm is guaranteed to find a global optimum in the worst-case scenario although the search spaces are unknown. Finally, we empirically demonstrate that our algorithms considerably boost BO and outperform the state-of-the-art on a wide range of benchmarks.
