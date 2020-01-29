---
layout:     post
title:      【Linear Algebra】Vector Spaces and Rank
subtitle:   向量空间&秩
date:       2020-01-28
author:     Yunxuan
header-img: img/post4-hd.jpg
catalog: true
tags: 
    Linear_Algebra
---
Today, we are going talk about Vector Space and Rank 
# Vector Spaces
## Vector spaces
### Definition
From a slightly more abstract perspective, a vector space, X, is obtained by equipping vectors with the operations of addition and multiplication by a scalar. A simple example of a vector space is X = Rn, the space of n-tuples of real numbers. A less obvious example is the set of single-variable polynomials of a given degree.

### Axiom
The axioms must hold for all vectors **u**, **v**, and **w** in V and for all scalars c and d.
1.The sum of **u** and **v**, denoted by **u** + **v**, is in V.
2.http://chart.googleapis.com/chart?cht=tx&chl=\Large **u**+**v**=**v**+**u**.
3.http://chart.googleapis.com/chart?cht=tx&chl=\Large (**u**+**v**)+**w**=**u**+**v**+(**w**).
4.There is a **zero** vector **0** in V such that **u**+0=**u**.
5.For each **u** in V , there is a vector -**u** in V such that **u**+(-**u**)=**0**.
6.The scalar multiple of **u** by c, denoted by c**u**, is in V.
7.c(**u**+**v**)=c**u**+c**v**.
8.(c+d)**u**=c**u**+d**u**.
9.c(d**u**)=(cd)**u**.
10.1**u**=**u**.

### Formation of Vector Space
1.
