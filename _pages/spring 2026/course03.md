---
layout: single
author_profile: false
toc: true
toc_sticky: true
permalink: /for-students/spring2026/eaistatml/
sidebar:
  nav: "docs"
classes: wide
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# О курсе

Более-менее подробную аннотацию, в том числе и литературу, можно посмотреть в [syllabus](https://drive.google.com/file/d/1fTdyO_2BGOQLaoFdLRiAVKCxIg3_0XjV/view).

# Таблицы с результатами

 - [таблица](https://docs.google.com/spreadsheets/d/12k4NgT3mo9kFLEy-oIuo9OwT-65qrYimnrdXiIYQMVQ/)

# Условия РГР/Лаб.

 - [первая](https://drive.google.com/file/d/1h2WB3vxWdIF71QB7Nf_TJv6_8dyNLAVS/view)
 - [вторая](https://drive.google.com/file/d/1EFCjpEN6TOGUJqZmvxXVLz2zOquoNRpt/view)

# Экзамен

*To be announced*

# Задачи

# Набор 1: про условные распределения и связанные с ним вещи

В этих задачах считать, что функция потерь -- квадратическая.

1. Пусть $$(X, Y)$$ - гауссовский вектор, причем пусть $$\mu = (\mu_X, \mu_Y)$$, где $$\mu_X = \mathrm{E}X$$, $$\mu_Y = \mathrm{E}Y$$, и матрицу ковариаций $$\Sigma$$ тоже разбейте на блоки. Найдите распределение $$X$$ при условии $$Y$$. Hint: рассмотрите $$U = X - AY$$, где $$A$$ -- матрица такая, что $$U$$ и $$Y$$ некореллированы (а что с независимостью в этом случае?), из этого равенства выразите $$X$$.
2. Пусть дана выборка из нормального распределения со
средним $$a$$ и единичной дисперсией, причём параметр $$a$$ имеет распределение Бернулли с параметром 1/2. Построить байесовскую
оценку параметра $$a$$. Постройте credible interval (equal tail and highest dencity)
3. Пусть дана выборка из равномерного распределения на
отрезке $$[0, \theta]$$, причём $$\theta$$ принимает значения 1 и 2 с равными вероятностями. Построить байесовскую оценку параметра $$\theta$$. Постройте credible interval (equal tail and highest dencity)
4. Пусть дана выборка из нормального распределения со
средним $$a$$ и единичной дисперсией, причём параметр $$a$$ равномерно распределён на [0, 1]. Построить байесовскую
оценку параметра $$a$$. Постройте credible interval (equal tail and highest dencity)
5.  Пусть дана выборка из распределения Пуассона, причём
параметр $$\lambda$$ принимает значения 1 и 2 с вероятностями 1/3 и 2/3
соответственно. Построить байесовскую оценку параметра $$\lambda$$. Постройте credible interval (equal tail and highest dencity)