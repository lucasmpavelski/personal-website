---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Recommending Meta-Heuristics and Configurations for the Flowshop Problem via
  Meta-Learning: Analysis and Design'
subtitle: ''
summary: ''
authors:
- Lucas Marcondes Pavelski
- Marie-Éléonore Kessaci
- Myriam Regattieri Delgado
tags:
- '"flow shop scheduling;learning (artificial intelligence);search problems;simulated
  annealing;parameter values;meta-heuristics;hill climbing;simulated annealing;iterated
  local search;flowshop problems;Tabu search;gradient boosting machines;low-level
  meta-features;Irace parameter tuning;recommended MH;local search heuristics;meta-learning
  system;MH configurations;MH recommendation models;meta-feature;numerical parameters;categorical
  parameters;Boosting;Task analysis;Approximation algorithms;Tuning;Simulated annealing;meta
  learning;flowshop;optimization"'
categories: []
date: '2018-10-01'
lastmod: 2020-09-20T11:06:34-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-09-20T14:07:57.730354Z'
publication_types:
- 1
abstract: This work proposes a meta-learning system based on Gradient Boosting Machines
  to recommend local search heuristics for solving flowshop problems. The investigated
  approach can decide if a metaheuristic (MH) is suitable for each instance. It can
  also provide well-suited parameters for each recommended MH using data from Irace
  parameter tuning. This paper considers four MHs (Hill Climbing, Tabu Search, Simulated
  Annealing, and Iterated Local Search) as candidates to solve several flowshop instances.
  In the experiments, 540 flowshop problems (with different sizes, variants, and objectives)
  and 50 instances for each problem are considered, resulting in a total of 27,000
  instances being addressed. We use simple low-level meta-features in the meta-learning
  system like the number of jobs and machines, processing time distribution, flowshop
  variant, objective, and evaluations budget. Besides testing the recommendations
  in terms of accuracy and Kappa (for MH and categorical parameters), RMSE and R2
  (for numerical parameters), we also explore the importance of each meta-feature
  in MH recommendation models. Moreover, we perform a multiple correspondence analysis
  on MH configurations to gain further insights into the parameters values. Results
  show that the proposed approach is promising, particularly for MH recommendation.
publication: '*2018 7th Brazilian Conference on Intelligent Systems (BRACIS)*'
doi: 10.1109/BRACIS.2018.00036
---
