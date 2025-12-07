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
2. Показать, что распределение $$Y(t) = W(t + t_0) - W(t_0)$$ будет совпадать с распределением $$W(t)$$ (*стационарность приращений*)
3. То же самое для случайного процесса $$Z(t) = tW(1/t), Z(0) = 0$$.
4. Пусть $$X(t)$$, $$t \geqslant 0$$, -- гауссовский процесс со стационарными и независимыми приращениями и непрерывен в среднем квадратичном (в смысле $$L_2$$), то есть
$$\lim_{h \to s}\mathrm{E}\vert X(h) - X(s) \vert^2 = 0$$. Показать, что найдутся
$$c \in \mathbb{R}$$, $$\sigma > 0$$ и $$W(t)$$ такие, что $$X(t) = ct + \sigma W(t)$$.
5. Показать, что $$B(1 - t)$$ тоже броуновский мост
6. Показать, что $$B(t) = W(t) - tW(1)$$
7. Убедиться, что процесс Орнштейна-Уленбека U(t) является стационарным и $$U(t) = e^{-t/2}W(e^t)$$
8. Пусть $$B^H(t)$$, $$t \in \mathbb{R}$$, $$H \in (0; 1]$$ -- гауссовский процесс с нулевым математическим ожиданием и функцией
$$k(s, t) = \frac{1}{2}(\vert s \vert^{2H}+ \vert t\vert^{2H} - \vert s - t\vert^{2H})$$, называемый дробным броуновским движением. Рассмотрите отдельно случаи $$H = 1/2$$ имеет
$$H = 1$$.
9. Рассмотрим $$Y(t) = \frac{B^H(ct)}{c^H}$$, $$c > 0$$. Убедиться, что $$Y(t)$$ -- дробное броуновское движение
10. Показать, что дробное броуновское движение процесс со стационарными приращениями
11. Пусть $$F_n$$, $$F$$ -- эмпирическая и теоретическая функции распределения соответственно, $$G_n(t) = \sqrt{n}(F_n(t) - F(t))$$. Убедиться, что предельный (по распределению)
процесс есть гауссовский с нулевым мат. ожиданием и $$k(s, t) = \min(F(s), F(t)) - F(s) F(t)$$

## Набор 4

- [файл с задачами](https://drive.google.com/file/d/1F2OAtkYG8pQmHx9C3eU_TnHIolP2UGY9/view) (*будет пополняться*)

## Набор 5

Задачи на условное математическое ожидание:

1. Докажите линейность условного математического ожидания
2. Докажите формулу полного математического ожидания $$\mathrm{E}X = \mathrm{E}[\mathrm{E}(X \vert \mathcal{F})]$$
3. Случайные величины $$(X_k)_{k \in \mathbb{N}}$$ независимы и имеют математическое ожидание, равное $$a$$. Пусть $$\nu$$ -- целочисленная 
случайная величина, принимающая неотрицательные значения с математическим ожиданием $$b$$ и не зависящая от $$X_k$$. Положим
$$S_\nu = X_1 + \ldots + X_\nu$$. Найти $$\mathrm{E} \mathrm{S_\nu}$$.
4. Условной дисперсией называется 
величина $$\mathrm{Var}(X \vert \mathcal{F}) = \mathrm{E}[(X - \mathrm{E}(X\vert \mathcal{F}))^2 \vert \mathcal{F}]$$. Покажите, что
    - справедливо соотношение $$\mathrm{Var}(X \vert \mathcal{F}) = \mathrm{E}(X^2\vert \mathcal{F}) - \mathrm{E}^2(X\vert \mathcal{F})$$
    (воспользуйтесь тем, что, если $$Y$$ измеримо относительно $$\mathcal{F}$$, то $$\mathrm{E}(XY \vert \mathcal{F}) = Y \mathrm{E}(X\vert\mathcal{F})$$)
    - разложение дисперсии $$\mathrm{Var} X = \mathrm{E}\mathrm{Var}(X\vert Y) + \mathrm{Var}(\mathrm{E}(X \vert Y))$$
5. В контексте задачи 3 дополнительно предположите существование одинаковых дисперсий у $$X_k$$ и дисперсию у $$\nu$$. Найдите $$\mathrm{Var}S_Y$$.
6. Пусть $$X$$ независима от $$\mathcal{F}$$, то есть $$\sigma(X)$$ независима от $$\mathcal{F}$$. Показать, что
$$\mathrm{E}(X\vert\mathcal{F}) = \mathrm{E}X$$
7. Показать, что $$\mathrm{E}(X\vert\mathcal{F})$$ минимизирует выражение $$\mathrm{E}(X - Y)^2$$, где $$Y$$ -- функция, измеримая относительно
$$\mathcal{F}$$.

## Набор 6

1. Пусть $$Y(t) = N(t) - \lambda t$$. Доказать, что $$Y(t)$$ -- мартингал
2. Пусть $$X_{i, j}$$ -- независимые одинаково распределенные величины, принимающие целые неотрицательные значения, с математическим ожиданием $$m$$. Положим
$$Z_1 = 1 $$, $$Z_2 = X_{1, 1}$$, $$\dots$$, $$Z_n = X_{n, 1} + \ldots + X_{n, Z_{n - 1}}$$ -- модель ветвящегося процесса. Показать, что
$$M_n = Z_n / m^n$$ -- мартингал.
3. Пьяница стоит на семнадцатом метре стометрового моста. С вероятностью 0.5 он шагает на один метр вправо или влево. Найти:
    - вероятность того, что он дойдёт до конца моста, при этом не побывав в начале
    - математическое ожидание количества шагов, которое требуется пройти либо до начала, либо до конца
4. Есть кот, любящий гулять по клавиатуре, что готов делать это бесконечно долго, но он не любит слово **абракадабра** и как только его видит он сразу останавливается.
Найти математическое ожидание длины получивашейся строки (считать, что на клавиатуре 33 русских символа и других кнопок нет). 

**Подсказка**:
Рассмотрите следующее казино: каждое новое нажатие кота на клавиатуру приходит новый человек, вносит 1 руболь и называет букву <<A>>, если он угадал, то получает 33 рубля и остается, иначе уходит. Если остался, он ставит все 33 рубля и в случае успеха получает 33 в квадрате рублей, иначе уходит и т.д. Рассмотреть $$X_n$$ -- баланс казино на момент времени $$n$$ и $$T_n = \min(n, T)$$, $$T$$ -- момент, когда в первый раз случилось искомое слово

## Набор 7

1. Вычислите интеграл $$I_{\theta} = \int_{0}^t W(s)dW(s)$$ как предел интегральных сумм
для равномерного разбиения $$x_k = k t/n$$, $$k \in \{0,\ldots, n\}$$, причём в качестве точки выбирайте
$$t_{k, \theta} = (1 -\theta)x_{k - 1} + \theta x_k$$ (в классе мы рассмотрели случай $$\theta = 0$$ -- интеграл Ито). В частности, убедиться, что в данном примере при $$\theta = 0.5$$ (интеграл Стратоновича) справедливо интегрирование
по частям.

Решить стохастические дифференциальные уравнения:

1. $$d X(t) = \mu X(t)dt + \sigma X(t) d W(t)$$, hint: $$F(t, x) = \ln x$$
2. $$d X(t) = -\mu X(t)dt + \sigma d W(t)$$, hint: $$F(t, x) = e^{\mu t} x$$
3. $$d X(t) = \frac{\beta - X(t)}{T - t}dt + d W(t)$$, hint: $$F(t, x) = \frac{\beta - x}{T - t}$$