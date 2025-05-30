---
layout: archive
title: "CV"
permalink: cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

## Beihang University, Beijing, China, Aug.2018 - June 2025
* Ph.D. Candidate in School of Computer Science and Engineering
* GPA: 3.73 / 4.00 ｜ Ranking: 13/91 (Top 14%)
* Supervised by **[Prof. Wenfei Fan](https://homepages.inf.ed.ac.uk/wenfei/)**

## Northwest A&F University, Xi'an, China, Aug.2014 - June 2018
* B.S. in College of Information Engineering
* GPA: 3.80 / 4.00 ｜ Ranking: 1/318 (Top 1%)


# Work experience

## Shenzhen Institute of Computing Sciences ([SICS](https://www.sics.ac.cn/)), Shenzhen, China, Mar.2021 - Oct.2024
* Research Intern in Fundamental Research Center
  * Graph Data Mining
  * Recommendation Systems
  * Explainability

### 1. Graph Data Mining and Recommendation System Optimization
* **Project Overview**: RecLogic, a logic framework to enhance the accuracy of machine learning (ML) models for recommendation systems by integrating logic conditions to reduce false positives and false negatives without retraining models.

* **Technical Approach**: (1) Developed prediction rules (TIEs) that integrate dual-star graph patterns with logic conditions, reducing false positives/negatives by 16.21% AUC in critical prediction zones (i.e., near the recommendation threshold). (2) Implemented a generation-based approach using LSTM for pattern generation and decision trees for predicate generation to learn TIEs. (3) Proposed a parallel algorithm for applying TIEs in the recommendation module, achieving scalable performance by parallelizing path matching.

* **Tech Stack**: Python/PyTorch (traditional recommendation models), C++ (subgraph matching), LSTM, Decision Trees.

* **Deployment**: SIGMOD 2023. Implemented in SICS [AIRec](https://airec.grandhoo.com/) Recommendation platform.

### 2. Graph Neural Networks and Explainable Recommendation Systems
* **Project Overview**:Makex, a logic approach to explaining why a GNN-based model M(x,y) recommends item y to user x, providing both global and local explanations for recommendations.

* **Technical Approach**: (1) Proposed Rules for ExPlanations (REPs) defined by dual-star graph patterns and dependency, revealing the topological and feature conditions for recommendations. (2) Implemented a GNN-guided algorithm using Monte Carlo Tree Search (MCTS) to discover REPs and generate global explanations. (3) Utilized the 1-WL test to explain GNN behaviors, ensuring faithfulness to GNN predictions, achieving 32% higher recognizability and 42% higher reliability in global explanations compared to baselines. (4) Developed a Top-k algorithm for local explanations, the fidelity and sparsity of its top-1 explanation are 0.893 and 0.00225% on average, 80.62% and 3 orders of magnitude better than the baselines, respectively. It takes only 0.38s to generate top-1 explanation on large graphs, 75.8X faster than baselines on average.

* **Tech Stack**: Python/PyTorch (GNNs), C++ (subgraph matching), MCTS, 1-WL test.

* **Deployment**: VLDB 2024. Implemented in SICS [MedHunter](https://medhunter.grandhoo.com/) AI Drug Discovery Platform.

### 3. Graph Data Mining and Logic-Driven Sequential Recommendation
* **Project Overview**: LDSRec, a novel framework that integrates logic rules with sequential recommendation models by representation learning to capture users' short-term behaviors and long-term preferences.

* **Technical Approach**: (1) Defined SEquential Rules (SERs) that combine sequential graph patterns with logic preconditions, enabling polynomial time representation learning. (2) Transformed user behavior sequences into a global heterogeneous graph, maintaining strict temporal order via path centric subsequence division, and item co-occurrence dependencies, and capturing high-order dependencies through correlated interaction paths. (3) Combined SER-guided embeddings with original model outputs, optimized via contrastive learning to align logic rules with latent user interest representations. The model was further optimized using a loss function that integrates logic-driven contributions.

* **Tech Stack**: Python/PyTorch (sequential recommendation), C++ (subgraph matching), LSTM/Transformer, Contrastive Learning.

* **Deployment**: Under submission VLDB 2026.



# Honors and Awards

### Beihang University
* May. 2025 Outstanding Graduates of Beihang University
* Apr. 2024 ACM SIGMOD Student Support Scholarship Award
* Nov. 2021 Outstanding Student Cadre Award, Beihang University
* Oct. 2021 The First Prize Scholarship, Beihang University
* Jan. 2021 Outstanding Graduate Student Award, Beihang University
* Dec. 2020 President Scholarship for Graduate Students Award, Beihang University
* Nov. 2020 Outstanding Student Cadre Award, Beihang University
* Oct. 2020 The Second Prize Scholarship, Beihang University
* Oct. 2019 The Second Prize Scholarship, Beihang University

### Northwest A&F University
* Jun. 2018 Outstanding Undergraduate Thesis Award, Northwest A&F University
* Nov. 2017 **National Scholarship**
* Nov. 2017 The First Prize Scholarship, Northwest A&F University
* Nov. 2017 Outstanding Student, Northwest A&F University
* Nov. 2016 **National Scholarship**
* Nov. 2016 The First Prize Scholarship, Northwest A&F University
* Nov. 2016 Outstanding Student, Northwest A&F University


# Academic Services
* Volunteer of VLDB 2024
* Sub-reviewer: TKDE 2023, EDBT 2023, ICDE 2024

# Teaching Assistant Experience
* Teaching Assistant of Formal Languages and Automa, Beihang University, 2020-2021
