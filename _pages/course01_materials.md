---
layout: single
author_profile: true
toc: true
toc_sticky: true
permalink: /for-students/autumn2024/mathstatct/materials/
sidebar:
  nav: "docs"
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# Материалы

Здесь буду выкладывать материалы по курсу

- [Презентация про инструменты для статистического анализа](https://drive.google.com/file/d/1ryCMavfdJkc7CWXqtAwKAJi3Zn2_93pr/view?usp=sharing),
[листинг](https://colab.research.google.com/drive/1kwEuPR6joNaxJtoHIzjkqHTL4tnujGpl?usp=sharing)

## Лабораторные работы

- [Первая](https://drive.google.com/file/d/1_iRnFlzB9Q1NUrcE2ntDIeKdnDP6LrmB/view)
- [Вторая](https://drive.google.com/file/d/1zcMYyRCZqVTYVOUGmB6ML_N4NKSKeorD/view)
- [Третья](https://drive.google.com/file/d/1rb3BFrS5Qh0aVA-EEgjcnCBYOtec6NIN/view)

## Задачи с практик

### Занятие 1

Будем считать, что $$X_1$$, $$\dots$$, $$X_n$$ -- независимые одинаково распределенные случайные величины с
функцией распределения $$F$$ (данную модель будем называть *простейшей выборкой*, а $$F$$ -- теоретической функцией
распределения), если не сказано иное.

Кроме того, нам понадобится следующая нотация:

$$\overline{g(X)} = \frac{1}{n}\sum_{i = 1}^ng(X_i)$$,

где $$g(.)$$ -- некоторая функция.

Отсортированный по возрастанию массив $$X_1$$, $$\dots$$, $$X_n$$ будем обозначать как
$$X_{(1)}$$, $$\dots$$, $$X_{(n)}$$, то есть $$X_{(1)} \leq \ldots \leq X_{(n)}$$ (отсортированная последовательность
называется *вариационным рядом*).

1. Пусть $$F_n(t) = \frac{1}{n}\sum_{i = 1}^n \mathrm{1}(X_i \leqslant t)$$ -- эмпирическая функция распределения.
Оценить $$\delta$$, для которого $$\mathrm{P}(|F_n(t) - F(t)| < \delta) \geqslant \gamma$$ при данном заданном
$$\gamma \in (0, 1)$$.

2. Рассмотрим $$\overline{X}$$ -- *выборочное среднее*.
    - Найти приближенное распределение $$\overline{X}$$ при достаточно больших $$n$$ (что нужно потребовать, чтобы получился
    содержательный ответ?)
    - При следующих предположениях на $$F$$ найти распределение $$\overline{X}$$:
        - нормальное распределение с математическим ожиданием $$\mu$$ и дисперсией $$\sigma^2$$
        - пуассоновский закон с параметром $$\lambda$$
        - экспоненциальный закон с параметром $$\lambda$$
        - распределение Коши
        - равномерное распределение на $$[-1, 1]$$ (вспомните, с помощью каких менее очевидных объектов можно задавать
        вероятностное распределение)

3. Рассмотрим $$S_*^2 = \overline{(X - \overline{X})^2}$$ -- *выборочную дисперсию*. Найти
$$\mathrm{E}\ S_*^2$$ и $$\mathrm{Var}\ S_*^2$$.
4. Упражнение на вариационный ряд:
    - Найти функцию распределения для $$X_{(n)}$$
    - То же самое для $$X_{(1)}$$
    - Аналогично для $$X_{(k)}$$
    - Предположим, что существует теоретическая плотность $$p$$. Найти плотность для $$X_{(k)}$$
    (ответ предыдущего пункта записать через [regularized incomplete beta function](https://en.wikipedia.org/wiki/Beta_function#Incomplete_beta_function))
    - Найти совместную плотность для $$(X_{(1)}, \dots, X_{(n)})$$
    - Найти совместную плотность для $$(X_{(l)}, X_{(s)})$$, $$1 \leq l < s \leq n$$

### Занятие 2

Во всех задачах требуется найти оценку методом моментов, вычислить смещение, дисперсию и MSE
(или хотя бы написать формулу, по которым это считается). Какими свойствами
обладают найденные оценки?
1. Shifted exponential
2. $$\Gamma$$ (one parametr is unknown, both are unknown)
3. Биномиальное
4. Распределение Коши $$\mathrm{Cauchy}(x_0, 1)$$
5. Распределение Парето $$\mathrm{Pareto}(x_0, \beta)$$

### Занятие 3

Во всех задачах требуется найти оценку методом максимального правдоподобия, вычислить смещение, дисперсию и MSE
(или хотя бы написать формулу, по которым это считается). Какими свойствами
обладают найденные оценки?
1. Пуассон
2. Геометрическое
3. Равномерное на $$[\theta_1, \theta_2]$$
4. Laplace (*loc* is unknown, *scale* is given)
5. Shifted exponential
6. Распределение Коши

### Занятие 4

Для регулярных моделей из предыдущих упражнений посчитать информацию Фишера

### Занятие 6

1. Как с помощью минимума и максимума (первая и $$n$$-ая порядковые статистики) можно
построить *точный* доверительный интервал для равномерного закона на $$[0, theta]$$?
2. Построить асимптотический доверительный интервал для второго момента
3. Для выборки из экспоненциального распределения (*использовать стандартную для нас параметризацию*) с помощью 
асимптотически нормальных оценок (почему и откуда они взялись?
$$1 / \overline{X}$$ и $$\sqrt{2 / \overline{X^2}}$$. Какой доверительный интервал
*лучше* (и что можно понимать под качеством)?

## Экзамен