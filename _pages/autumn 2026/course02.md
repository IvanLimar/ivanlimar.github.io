---
layout: single
author_profile: false
toc: true
toc_sticky: true
permalink: /for-students/autumn2026/aictstohastic/
sidebar:
  nav: "docs"
classes: wide
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# О курсе

Смотри [аннотацию](https://drive.google.com/file/d/1v0fHkE5RYkT3-zCNfV25jdSiIIEZVPYU/view)

# Зачёт/экзамен

*To be announced*

# Задачи

## Набор 1

1. Пусть $$Y(t) = V\cos(\psi t - \Theta)$$, где $$V$$ имеет плотность
$$f(x) = \frac{x\exp\{-\tfrac{x^2}{2\sigma^2}\}}{\sigma^2}\mathrm{I}(x\geqslant 0)$$,
$$\Theta \sim \mathrm{U}[0, 2\pi]$$, $$V, \Theta$$ -- независимы, $$\psi \in \mathbb{R}$$ -- фиксированное число. Найти одномерный и двумерный законы распределения
процесса, функции мат. ожидания и ковариаций.
2. Пусть $$\{\xi_n\}_{n \in \mathbb{N}}$$ -- последовательность независимых неотрицательных одинаково распределенных случайных величин,
$$S_0 = 0$$, $$S_n = (\xi_1 + \ldots + \xi_n)$$. Положим $$X_t = \sup\{n \geqslant 0: S_n \leqslant t\}$$, $$t \geqslant 0$$
    - Показать, что $$X_t$$ конечен с вероятностью 1 в любой момент времени $$t$$
    - К какой константе сходится (и как)  $$X_t / t$$ при $$t \to \infty$$?
    - Найти предел по распределению $$\frac{X_t - at}{\sqrt{t}}$$
3. Докажите, что винеровский и пуассоновский процессы являются процессами Леви. **NB:** в формулировке определения процесса Леви не указал, что он еще должен быть непрерывен по вероятности, то есть $$X(t + \varepsilon)$$ стремится по вероятности к $$X(t)$$ при $$\varepsilon \to 0$$.
4. Случайная величина $$X$$ и ее распределение называются безгранично делимыми, если для всякого натурального $$N$$ найдутся независимые одинаково распределенные случайные величины $$X_{N, 1}, \ldots, X_{N, N}$$, для которых распределение суммы $$X_{N, 1} + \ldots + X_{N, N}$$ совпадает с распределением $$X$$. Докажите, что сечение процесса Леви $$X(t)$$ является безгранично делимой случайной величиной.
5. Найдите функции мат. ожидания, дисперсии и ковариаций для процесса Леви.
6. Рассмотрим случайный процесс $$Y(t) = \xi \cos(\omega t) + \eta \sin(\omega t)$$, где $$\xi$$, $$\eta$$ – независимые гауссовские величины с нулевым математическим ожиданием и дисперсией $$\sigma^2$$. Найдите функции мат. ожидания и ковариаций. Является ли данный процесс стационарным в узком смысле и процессом с независимыми приращениями? Является ли процесс гауссовским?
7. Пусть $$X(t) = W(t) + Ut$$, где $$W(t)$$ – винеровский процесс, $$U$$ -- независимая от $$W(t)$$ случайная величина. Найдите функции мат. ожидания и ковариаций. Являются ли приращения независимым? Является ли процесс $$X(t)$$ гауссовским, если $$U$$ -- гауссовская случайная величина? Является ли $$X(t)$$ процессом Леви?

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
7. Calls arrive at a call center according to a Poisson process with rate $$20$$ per hour. Each call is independently classified as:
- emergency with probability $$0.1$$;
- technical support with probability $$0.6$$;
- billing with probability $$0.3$$.

    Let $$T_E$$ be the time of the first emergency call and $$T_B$$ the time of the first billing call.

    Find:

    - $$P(T_E<T_B)$$;
    - $$P(T_E<1<T_B)$$;
    - $$P(T_E+T_B<1)$$;
    - $$E[\min(T_E,T_B)]$$;
    - $$P(T_E<T_B\mid N(1)=5)$$.
8. Customers arrive according to a nonhomogeneous Poisson process with intensity

    $$
    \lambda(t)=2+t,\qquad 0\leq t\leq 4.
    $$

    Suppose that exactly $$10$$ customers arrive during the first $$4$$ hours.

    Find:

    1. the conditional probability that exactly $$4$$ customers arrived during the first hour;

    2. the conditional expected number of customers arriving during the first $$2$$ hours;

    3. the probability that the third customer arrived before $$t=1$$;

    4. the conditional distribution of the arrival time of a randomly selected customer.

9. The number of accidents on a highway follows a nonhomogeneous Poisson process with intensity

    $$
    \lambda(t)=\frac{6t}{1+t^2},
    $$

    where $$t$$ is measured in hours.

    Find:

    1. the probability that no accidents occur during the first $$3$$ hours;

    2. the probability that exactly $$2$$ accidents occur between hours $$1$$ and $$4$$;

    3. the expected time of the first accident, conditional on at least one accident occurring before $$t=4$$;

    4. the probability that the second accident occurs before $$t=2$$.

10. Claims arrive according to a Poisson process with rate $$\lambda=4$$ per day. Each claim independently has size

    $$
    X=
    \begin{cases}
    1, & p=0.5,\\
    3, & p=0.3,\\
    10, & p=0.2.
    \end{cases}
    $$

    Let $$S$$ be the total claim amount during one day.

    Find

    $$
    P(S>10\mid N(1)\geq 2).
    $$
    
    Then find
    
    $$
    E[N(1)\mid S>10].
    $$


11. Scientists arrive according to a Poisson process with rate $$2$$ per day. Each scientist independently carries a random amount of food:

    $$
    X=
    \begin{cases}
    5, & p=0.4,\\
    10, & p=0.4,\\
    20, & p=0.2.
    \end{cases}
    $$

    A dinosaur initially has $$15$$ units of food and consumes food continuously at a rate of $$10$$ units per day. Food can be stored without limit.

    The dinosaur dies when its food level reaches zero.

    Let $$T$$ be its lifetime.

    Find:

    1. $$P(T>2)$$;

    2. $$P(T>3)$$;

    3. $$E[T]$$;

    4. the probability that the dinosaur eats at least $$3$$ scientists before dying;

    5. $$P(T>3\mid N(3)=4)$$.



12. The number of customers arriving at a supermarket follows a nonhomogeneous Poisson process with intensity

    $$
    \lambda(t)=20+10\sin\left(\frac{\pi t}{12}\right),
    \qquad 0\leq t\leq12.
    $$

    Each customer spends an independent random amount $$X$$, where

    $$
    P(X=0)=0.1,\qquad
    P(X=5)=0.4,\qquad
    P(X=10)=0.3,\qquad
    P(X=20)=0.2.
    $$

    Let

    $$
    S(t)=\sum_{i=1}^{N(t)}X_i
    $$

    be the total revenue by time $$t$$.

    Find:

    1. $$E[N(12)]$$;

    2. $$E[S(12)]$$;

    3. $$\operatorname{Var}(S(12))$$;

    4. $$P(N(6)>100)$$;

    5. using a normal approximation, estimate

    $$
    P(S(12)>1500);
    $$

    6. find the approximate $$95$$th percentile of $$S(12)$$.
    
## Набор 3

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
10. Покажите, что $$X(t) = W(t) - \frac{t}{T}W(T)$$, $$t \in [0, T]$$, независим от $$W(T)$$. Найдите функцию ковариаций.
11. Показать, что дробное броуновское движение процесс со стационарными приращениями
12. Пусть $$F_n$$, $$F$$ -- эмпирическая и теоретическая функции распределения соответственно, $$G_n(t) = \sqrt{n}(F_n(t) - F(t))$$. Убедиться, что предельный (по распределению)
процесс есть гауссовский с нулевым мат. ожиданием и $$k(s, t) = \min(F(s), F(t)) - F(s) F(t)$$