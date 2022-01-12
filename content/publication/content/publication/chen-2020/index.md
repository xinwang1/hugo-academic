---
title: "More Practical and Adaptive Algorithms for Online Quantum State Learning"
date: 2020-01-01
publishDate: 2021-12-28T15:12:02.231793Z
authors: ["Yifang Chen", "Xin Wang"]
publication_types: ["2"]
abstract: "Online quantum state learning is a recently proposed problem by Aaronson et al. (2018), where the learner sequentially predicts $n$-qubit quantum states based on given measurements on states and noisy outcomes. In the previous work, the algorithms are worst-case optimal in general but fail in achieving tighter bounds in certain simpler or more practical cases. In this paper, we develop algorithms to advance the online learning of quantum states. First, we show that Regularized Follow-the-Leader (RFTL) method with Tallis-2 entropy can achieve an $O(sqrtMT)$ total loss with perfect hindsight on the first $T$ measurements with maximum rank $M$. This regret bound depends only on the maximum rank $M$ of measurements rather than the number of qubits, which takes advantage of low-rank measurements. Second, we propose a parameter-free algorithm based on a classical adjusting learning rate schedule that can achieve a regret depending on the loss of best states in hindsight, which takes advantage of low noisy outcomes. Besides these more adaptive bounds, we also show that our RFTL with Tallis-2 entropy algorithm can be implemented efficiently on near-term quantum computing devices, which is not achievable in previous works."
featured: false
publication: "*arXiv preprint arXiv:2006.01013*"
url_pdf: "http://arxiv.org/abs/2006.01013"
---

