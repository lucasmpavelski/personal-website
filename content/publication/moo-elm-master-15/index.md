---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Otimização evolutiva multiobjetivo baseada em decomposição e assistida por
  máquinas de aprendizado extremo
subtitle: ''
summary: ''
authors:
- Lucas Marcondes Pavelski
tags: []
categories: []
date: '2015-01-01'
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
publishDate: '2020-09-20T14:35:31.981912Z'
publication_types:
- 7
abstract: Many real optimization problems have more than one objective function. When
  the objectives are in conflict, there is a need for specialized strategies, as is
  the case of the Multi-objective Optimization Evolutionary Algorithms (MOEAs). However,
  if the functions evaluation is expensive (high computational or economical costs)
  many proposed MOEAs are impractical. An alternative might be the use of a machine
  learning model to approximate the fitness function (surrogates) in the optimization
  algorithm. This work proposes and investigates a framework called ELMOEA/D that
  aggregates state-of-the-art MOEAs based on decomposition of objectives (MOEA/D)
  and extreme learning machines as surrogate models. The proposed framework is tested
  with different MOEA/D variants and show good results in benchmark problems, compared
  to a literature algorithm that also encompasses MOEA/D but uses surrogate models
  based on radial basis function networks. The ELMOEA/D framework is also applied
  to the protein structure prediction problem (PSPP). Despite the fact that the results
  achieved by the proposed approach were not as encouraging as the ones achieved in
  the benchmarks (when the algorithms with and without surrogates are compared), many
  aspects of both algorithm and problem are explored. Finally, the ELMOEA/D framework
  is applied to an alternative formulation of the PSPP and the results lead to various
  directions for future works.
publication: ''
url_pdf: http://repositorio.utfpr.edu.br/jspui/handle/1/1254
---
