---
layout: course
title: STATS 357 / MS&E 330 — Reliability and Validity in Artificial Intelligence
---

# STATS 357 / MS&E 330: Reliability and Validity in Artificial Intelligence

Tijana Zrnic, Stanford University, Spring 2026

---

## Announcements

- [5/7] Please send me your brief project descriptions by Fri, May 8 (see Ed for details).
- [5/7] No lecture on Monday, May 11. I'll have extra office hours (see Ed for details).
- [4/29] Homework 3 is up! It's due on 5/13 EOD.
- [4/26] I posted annotated versions of all lecture slides on Canvas.
- [4/15] Homework 2 is up! It's due on 4/29 EOD.
- [4/8] I adjusted the class schedule. On May 11 we won't have a lecture, but we'll have extended office hours that week.
- [4/3] We expanded enrollment. There are a handful of people still on the waitlist, but I expect everyone will be able to enroll.
- [4/1] Homework 1 is up! It's due on 4/15 EOD.
- [3/31] Slides for lectures 1 & 2 have been posted on Canvas.
- Welcome to STATS 357 / MS&E 330!

---

## Lectures

Mon/Wed 9:30am-10:50am, [McCullough 122](https://campus-map.stanford.edu/?id=04-490)

---

## Staff

Instructor: Tijana Zrnic
- Office hours: Mon 11am-12pm, [CoDa E248](https://campus-map.stanford.edu/?id=07-430)

Teaching assistant: Reese Feldmeier
- Office hours: Thu 3pm-4:30pm, [CoDa B06](https://campus-map.stanford.edu/?id=07-430)

---

## Course description

This course examines the principles and methods required to make artificial intelligence (AI) systems reliable and scientifically sound. Topics include evaluation and benchmarking, notions of validity, distribution shift, predictive inference, AI-assisted statistical inference, data attribution, and beyond. Problem sets will involve both mathematical components and coding projects.

Prerequisites include mathematical maturity in probability, statistics, and optimization, and proficiency in Python.

---

## Syllabus

| Lecture | Date | Topics | Reading |
|---------|---------|---------|---------|
| 1 | Mar 30 | Benchmarks; Holdout method | [1, Ch. 3 & 4] |
| 2 | Apr 1 | Cross-validation; Bootstrap | [1, Ch. 4; 2; 3] |
| 3 | Apr 6 | Model selection & selection bias; Overfitting pt. 1: reward hacking | [1, Ch. 4 & 5; 4] |
| 4 | Apr 8 | Overfitting pt. 2: benchmark contamination | [5] |
| 5 | Apr 13 | Internal, external, & construct validity | [6; 7; 8] |
| 6 | Apr 15 | _Frontier lecture_ | see signup sheet |
| 7 | Apr 20 | Distribution shift | [9, Ch. 1 & 6; 10] |
| 8 | Apr 22 | Predictive inference; Conformal prediction | [11] |
| 9 | Apr 27 | Predictive inference under distribution shift | [12; 13; 14] |
| 10 | Apr 29 | Calibration | [15; 16; 17] |
| 11 | May 4 | Multicalibration; Multiaccuracy | [18; 19; 20] |
| 12 | May 6 | _Frontier lecture_ | see signup sheet |
|   | May 11 | No class; Extended office hours instead |  |
| 13 | May 13 | AI for science; Prediction-powered inference (PPI) | [21; 22] |
| 14 | May 28 | AI-assisted annotation | TBD |
| 15 | May 20 | Data attribution | TBD |
|   | May 25 | Memorial Day (no class) |   |
| 16 | May 27 | _Frontier lecture_ | TBD |

"Frontier lectures" will consist of student presentations of frontier papers related to the class topics.

[1] M. Hardt. [The Emerging Science of Machine Learning Benchmarks](https://mlbenchmarks.org). _https://mlbenchmarks.org_, 2025.\
[2] S. Bates, T. Hasie, R. Tibshirani. [Cross-Validation: What Does It Estimate and How Well Does It Do It?](https://arxiv.org/abs/2104.00673) _Journal of the American Statistical Association (JASA)_, 2024.\
[3] S. Wager. [Cross-Validation, Risk Estimation, and Model Selection: Comment on a Paper by Rosset and Tibshirani](https://arxiv.org/abs/1909.11696). _Journal of the American Statistical Association (JASA)_, 2020.\
[4] L. Gao, J. Schulman, J. Hilton. [Scaling Laws for Reward Model Overoptimization](https://proceedings.mlr.press/v202/gao23h). _International Conference on Machine Learning (ICML)_, 2023.\
[5] Y. Oren, N. Meister, N. Chatterji, F. Ladhak, T. B. Hashimoto. [Proving Test Set Contamination in Black Box Language Models](https://arxiv.org/abs/2310.17623). _International Conference on Learning Representations (ICLR)_, 2024.\
[6] O. Salaudeen, A. Reuel, A. Ahmed, S. Bedi, Z. Robertson, S. Sundar, B. Domingue, A. Wang, S. Koyejo. [Measurement to Meaning: A Validity-Centered Framework for AI Evaluation](https://arxiv.org/abs/2505.10573). 2025.\
[7] M. Mancoridis, K. Vafa, B. Weeks, S. Mullainathan. [Potemkin Understanding in Large Language Models](https://arxiv.org/abs/2506.21521). _International Conference on Machine Learning (ICML)_, 2025.\
[8] J. D. Gaebler, C. Isley, C. Avery, S. Goel. [Reassessing the Role of Standardized Tests in University Admissions](https://5harad.com/papers/testing-debate.pdf). 2026.\
[9]  J. Quiñonero-Candela, M. Sugiyama, A. Schwaighofer, N. D. Lawrence. [Dataset Shift in Machine Learning](https://mitpress.mit.edu/9780262545877/dataset-shift-in-machine-learning/). _MIT Press_, 2008.\
[10] Z. Lipton, Y.-X. Wang, A. Smola. [Detecting and Correcting for Label Shift with Black Box Predictors](https://proceedings.mlr.press/v80/lipton18a.html). _International Conference on Machine Learning (ICML)_, 2018.\
[11] A. N. Angelopoulos, S. Bates. [A Gentle Introduction to Conformal Prediction and Distribution-Free Uncertainty Quantification](https://arxiv.org/abs/2107.07511). _Foundations and Trends in Machine Learning_, 2023.\
[12] I. Gibbs, E. J. Candès. [Adaptive Conformal Inference Under Distribution Shift](https://arxiv.org/pdf/2106.00170). _Advances in Neural Information Processing Systems (NeurIPS)_, 2021.\
[13] A. N. Angelopoulos, E. J. Candès, R. J. Tibshirani. [Conformal PID Control for Time Series Prediction](https://arxiv.org/abs/2307.16895). _Advances in Neural Information Processing Systems (NeurIPS)_, 2023.\
[14] R. F. Barber, E. J. Candès, A. Ramdas, R. J. Tibshirani. [Conformal Prediction Beyond Exchangeability](https://arxiv.org/abs/2202.13415). _Annals of Statistics_, 2023.\
[15] C. Guo, G. Pleiss, Y. Sun, K. Q. Weinberger. [On Calibration of Modern Neural Networks](https://proceedings.mlr.press/v70/guo17a/guo17a.pdf). _International Conference on Machine Learning (ICML)_, 2017.\
[16] A. Kumar, P. Liang, T. Ma. [Verified Uncertainty Calibration](https://proceedings.neurips.cc/paper/2019/hash/f8c0c968632845cd133308b1a494967f-Abstract.html). _Advances in Neural Information Processing Systems (NeurIPS)_, 2019.\
[17] K. Tian, E. Mitchell, A. Zhou, A. Sharma, R. Rafailov, H. Yao, C. Finn, C. Manning. [Just Ask for Calibration: Strategies for Eliciting Calibrated Confidence Scores from Language Models Fine-Tuned with Human Feedback](https://aclanthology.org/2023.emnlp-main.330/). _Conference on Empirical Methods in Natural Language Processing (EMNLP)_, 2023.\
[18] U. Hebert-Johnson, M. Kim, O. Reingold, G. Rothblum. [Multicalibration: Calibration for the (Computationally-Identifiable) Masses](https://proceedings.mlr.press/v80/hebert-johnson18a.html?ref=https://githubhelp.com). _International Conference on Machine Learning (ICML)_, 2018.\
[19] M. Kim, A. Ghorbani, J. Zou. [Multiaccuracy: Black-Box Post-Processing for Fairness in Classification](https://dl.acm.org/doi/abs/10.1145/3306618.3314287). _AAAI/ACM Conference on AI, Ethics, and Society (AIES)_, 2019.\
[20] I. Gibbs, J. J. Cherian, E. J. Candès. [Conformal Prediction with Conditional Guarantees](https://academic.oup.com/jrsssb/article/87/4/1100/8058684?guestAccessKey=). _Journal of the Royal Statistical Society: Series B (JRSSB)_, 2025.\
[21] A. N. Angelopoulos, S. Bates, C. Fannjiang, M. I. Jordan, T. Zrnic. [Prediction-Powered Inference](https://www.science.org/doi/full/10.1126/science.adi6000). _Science_, 2023.\
[22] A. N. Angelopoulos, J. C. Duchi, T. Zrnic. [PPI++: Efficient Prediction-Powered Inference](https://arxiv.org/abs/2311.01453). 2023.

---

## Grading

If you are taking the class for a letter grade:\
Homework (40%): four biweekly problem sets with math and coding problems\
Frontier lecture presentation (10%): one ~10 minute group presentation of a paper you will choose\
Final project (50%): group final project on a topic broadly related to the class

If you are taking the class for CR/NC, you don't have to do a frontier lecture presentation. Only homework and final project.

---

## Logistics

Homework and lecture slides will be distributed on Canvas. For homework submissions, we will use Gradescope. For Q&A and class-related discussions, we will use Ed.
