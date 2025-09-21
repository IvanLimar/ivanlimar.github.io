---
layout: single
author_profile: false
toc: true
toc_sticky: true
permalink: /for-students/autumn2025/stohasticprocessct/
sidebar:
  nav: "docs"
classes: wide
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# О курсе

Более-менее подробную аннотацию, в том числе и литературу, можно посмотреть в [syllabus](/assets/files/2025_autumn_stohasticproces_ct_syllabus.pdf).

# Таблица с результатами

- [таблица](https://docs.google.com/spreadsheets/d/1JVmOmdup4iRp7yM1gVB3cmMWM4gbGoYVf4KXHPL8rAQ/edit?gid=0#gid=0)

# Зачёт

*To be announced* 

# Задачи

## Набор 1

1. Пусть $$Y(t) = V\cos(\psi t - \Theta)$$, где $$V$$ имеет плотность
$$f(x) = \frac{x\exp\{-\tfrac{x^2}{2\sigma^2}\}}{\sigma^2}\mathrm{I}(x\geqslant 0)$$,
$$\Theta \sim \mathrm{U}[0, 2\pi]$$, $$V, \Theta$$ -- независимы, $$\psi \in \mathbb{R}$$ -- фиксированное число. Найти одномерный и двумерный законы распределения
процесса, функции мат. ожиданий и ковариаций.
2. Пусть $$\{\xi_n\}_{n \in \mathbb{N}}$$ -- последовательность независимых неотрицательных одинаково распределенных случайных величин,
$$S_0 = 0$$, $$S_n = (\xi_1 + \ldots + \xi_n)$$. Положим $$X_t = \sup\{n \geqslant 0: S_n \leqslant t\}$$, $$t \geqslant 0$$
    - Показать, что $$X_t$$ конечен с вероятностью 1 в любой момент времени $$t$$
    - К какой константе сходится (и как)  $$X_t / t$$ при $$t \to \infty$$?
    - Найти предел по распределению $$\frac{X_t - at}{\sqrt{t}}$$

## Набор 2

1. Customers arrive at a bank according with a Poisson process with a rate 20
customers per minute. Suppose that two customer arrived during the first hour. What is the
probability that at least one arrived during the first 20 minutes?
2. Cars cross a certain point in a highway in accordance with a Poisson process
with rate equals 3 cars per minute. If Deb blindly runs across the highway, then what is the
probability that she sill be injured if the amount of time it takes her to cross the road is $$s$$
seconds? Do it for $$s = 2, 5, 10, 20$$.
3. Two individuals, A and B, both require kidney transplants. If A does not
receive a new kidney, then A will die after an exponential time with mean $$\lambda_a$$ and B will die
after an exponential time with mean  $$\lambda_b$$. New kidneys arrive in accordance with a Poisson
process having rate  $$\lambda$$. It has been decided that the first kidney will to A or to B if B is alive
and A is not at the time and the next one to B (if is still living).
    - What is the probability that A obtains a new kidney?
    - What is the probability that B obtains a new kidney?
4. A certain theory supposes that mistakes in cell division occur according to a
Poisson process with rate 2.5 per year., and that an individual dies when 196 such mistakes
have occurred. Assuming this theory find
    - the mean lifetime of an individual,
    - the variance of the lifetime of an individuals.
    - the probability that an individual dies before age 67.2
    - the probability that an individual reaches age 90.
    - the probability that an individual reaches age 100.
5. For a tyrannosaur with 10,000 calories stored:
The tyrannosaur uses calories uniformly at a rate of 10,000 per day. If his stored calories
reach 0, he dies. The tyrannosaur eats scientists (10,000 calories each) at a Poisson rate of 1 per day.
The tyrannosaur eats only scientists. The tyrannosaur can store calories without limit until needed.
Calculate the expected calories eaten in the next 2.5 days.
6. The claims department of an insurance company
receives envelopes with claims for insurance coverage at a Poisson rate of $$\lambda = 50$$ envelopes
per week. For any period of time, the number of envelopes and the numbers of claims in
the envelopes are independent. The numbers of claims in the envelopes have the following
distribution: one with probability 0.2, two -- 0.25, three -- 0.4, four -- 0.15. Using the normal approximation, calculate the 90th percentile of the number of claims
received in 13 weeks.

## Набор 3

Здесь $$W(t)$$ -- винеровский процесс, $$B(t)$$ -- броуновский мост

1. Найти $$\mathrm{E}(W(t) \vert \{W(\tau), \tau < s\})$$, $$t > s$$
2. Показать, что распределение $Y(t) = W(t + t_0) - W(t_0)$ будет совпадать с распределением $$W(t)$$ (*стационарность приращений*)
3. То же самое для случайного процесса $$Z(t) = tW(1/t), Z(0) = 0$$.
4. Пусть $$X(t)$$, $$t \geqslant 0$$, -- гауссовский процесс со стационарными и независимыми приращениями. Показать, что найдутся
$$c \in \mathbb{R}$$, $$\sigma > 0$$ и $$W(t)$$ такие, что $$X(t) = ct + \sigma W(t)$$.
5. Показать, что $$B(1 - t)$$ тоже броуновский мост
6. Показать, что $$B(t) = W(t) - tW(1)$$
7. Убедиться, что процесс Орнштейна-Уленбека U(t) является стационарным и $$U(t) = e^{-t/2}W(e^t)$$
8. Пусть $$B^H(t)$$, $$t \in \mathbb{R}$$, $$H \in (0; 1]$$ -- гауссовский процесс с нулевым математическим ожиданием и функцией
$$k(s, t) = \frac{1}{2}(\vert s \vert^{2H}+ \vert t\vert^{2H} - \vert |s - t|\vert^{2H})$$, называемый дробным броуновским движением. Рассмотрите отдельно случаи $$H = 1/2$$ имеет
$$H = 1$$.
9. Рассмотрим $$Y(t) = \frac{B^H(ct)}{c^H}$$, $$c > 0$$. Убедиться, что $$Y(t)$$ -- дробное броуновское движение
10. Показать, что дробное броуновское движение процесс со стационарными приращениями
11. Пусть $$F_n$$, $$F$$ -- эмпирическая и теоретическая функции распределения соответственно, $$G_n(t) = \sqrt{n}(F_n(t) - F(t))$$. Убедиться, что предельный (по распределению)
процесс есть гауссовский с нулевым мат. ожиданием и $k(s, t) = \min(F(s), F(t)) - F(s) F(t)$