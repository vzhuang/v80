---
title: 'Computational Optimal Transport: Complexity by Accelerated Gradient Descent
  Is Better Than by Sinkhorn’s Algorithm'
booktitle: Proceedings of the 35th International Conference on Machine Learning
year: '2018'
volume: '80'
series: Proceedings of Machine Learning Research
address: 
month: 0
publisher: PMLR
pdf: http://proceedings.mlr.press/v80/dvurechensky18a/dvurechensky18a.pdf
url: http://proceedings.mlr.press/v80/dvurechensky2018a.html
abstract: We analyze two algorithms for approximating the general optimal transport
  (OT) distance between two discrete distributions of size $n$, up to accuracy $\varepsilon$.
  For the first algorithm, which is based on the celebrated Sinkhorn’s algorithm,
  we prove the complexity bound $\widetilde{O}\left(\frac{n^2}{\varepsilon^2}\right)$
  arithmetic operations ($\widetilde{O}$ hides polylogarithmic factors $(\ln n)^c$,
  $c>0$). For the second one, which is based on our novel Adaptive Primal-Dual Accelerated
  Gradient Descent (APDAGD) algorithm, we prove the complexity bound $\widetilde{O}\left(\min\left\{\frac{n^{9/4}}{\varepsilon},
  \frac{n^{2}}{\varepsilon^2} \right\}\right)$ arithmetic operations. Both bounds
  have better dependence on $\varepsilon$ than the state-of-the-art result given by
  $\widetilde{O}\left(\frac{n^2}{\varepsilon^3}\right)$. Our second algorithm not
  only has better dependence on $\varepsilon$ in the complexity bound, but also is
  not specific to entropic regularization and can solve the OT problem with different
  regularizers.
layout: inproceedings
id: dvurechensky18a
tex_title: 'Computational Optimal Transport: Complexity by Accelerated Gradient Descent
  Is Better Than by Sinkhorn’s Algorithm'
firstpage: 1367
lastpage: 1376
page: 1367-1376
order: 1367
cycles: false
bibtex_editor: Dy, Jennifer and Krause, Andreas
editor:
- given: Jennifer
  family: Dy
- given: Andreas
  family: Krause
bibtex_author: Dvurechensky, Pavel and Gasnikov, Alexander and Kroshnin, Alexey
author:
- given: Pavel
  family: Dvurechensky
- given: Alexander
  family: Gasnikov
- given: Alexey
  family: Kroshnin
date: 2018-07-03
container-title: Proceedings of the 35th International Conference on Machine Learning
genre: inproceedings
issued:
  date-parts:
  - 2018
  - 7
  - 3
extras:
- label: Supplementary PDF
  link: http://proceedings.mlr.press/v80/dvurechensky18a/dvurechensky18a-supp.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---
