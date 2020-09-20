---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An empirical analysis of constraint handling on evolutionary multi-objective
  algorithms for the Environmental/Economic Load Dispatch problem
subtitle: ''
summary: ''
authors:
- Josiel Neumann Kuk
- Richard Aderbal Gonçalves
- Lucas Marcondes Pavelski
- Sandra Mara Guse Scós Venske
- Carolina Paula de Almeida
- Aurora Trinidad Ramirez Pozo
tags:
- '"Multi-objective optimization"'
- '"EELD"'
- '"Repair procedures"'
- '"Pareto-based algorithms"'
- '"Indicator-based algorithms"'
categories: []
date: '2021-01-01'
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
publishDate: '2020-09-20T14:35:31.353808Z'
publication_types:
- 2
abstract: This paper analyses different multi-objective evolutionary algorithms to
  deal with the Environmental/Economic Load Dispatch (EELD). EELD is formulated as
  a multi-objective optimization problem in which two competing objectives (fuel cost
  and pollutants emission) should be optimized simultaneously while fulfilling constraints.
  Due to the typical process of an evolutionary algorithm (EA), the use of operators
  applied to individuals of the population might violate constraint rules of the problem.
  The way in which EAs deal with such constraint rules is an important point and it
  is directly related to the quality of the generated solutions. One of the contributions
  of this paper is the analysis of the impact of a repair procedure in four multi-objective
  EAs. The analyzed approaches are evaluated in eight known instances (with 3, 6,
  10, 20 and 40 generators) of the multi-objective EELD. Furthermore, two new instances
  (with 80 and 120 generators) are proposed and evaluated in this work. Experiments
  were applied using Dominance Ranking, hypervolume and unary-epsilon indicators,
  empirical attainment functions and statistical tests, in order to evaluate the algorithms
  performances. The results point to the consistency of the NSGA-II with repair procedure
  compared to the literature algorithms, and it outperforms other approaches in most
  of the considered instances.
publication: '*Expert Systems with Applications*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0957417420305984
doi: https://doi.org/10.1016/j.eswa.2020.113774
---
