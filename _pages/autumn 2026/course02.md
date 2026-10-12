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
12. Пусть $$F_n$$, $$F$$ -- эмпирическая и теоретическая функции распределения соответственно, $$G_n(t) = \sqrt{n}(F_n(t) - F(t))$$. Убедиться, что предельные конечномерные распределения есть гауссовские
с нулевым мат. ожиданием и $$k(s, t) = \min(F(s), F(t)) - F(s) F(t)$$

## Набор 4

1. Исследуйте на дифференцируемость (с.к. и по вероятности, по распределению):
    - однородный пуассоновский процесс
    - винеровский процесс
2. Убедитесь в справедливости соотношений (дифференцирование и интегрирование в смысле с.к., процессы достаточно гладкие):
    - $$E X'(t) = m'(t)$$
    - $$\mathrm{Cov}(X'(t), X'(s)) = \frac{\partial^2 k(t, s)}{\partial t \partial s}$$
    - $$\mathrm{Cov}(X(t), X'(s)) = \frac{\partial k(t, s)}{\partial s}$$
    - $$\mathrm{E}\int_a^b X(t) dt = \int_a^b m(t) dt$$
    - $$\mathrm{Cov}(X(t), \int_a^b X(s) ds) = \int_a^b k(t, s) ds$$
    - $$\mathrm{Cov}(\int_a^b X(t) dt, \int_c^d X(s) ds) = \int_a^b \int_c^d k(t, s) dt ds$$
3. Постройте К-Л разложение для:
    - Винеровского процесса (на [0, 1])
    - Броуновского моста
    - Процесса Орнштейна-Уленбека (на конечном интервале, скажем, $$[0, T]$$, там собственные числа будут находиться неявно)

    Hint: для поиска собственных чисел нужно продифференцировать интегральное урванеине и свести его к дифференциальному

## Набор 5

**1.** Цепь на $$\{0,1\}$$ с матрицей
$$P=\begin{pmatrix}1-a & a\\ b & 1-b\end{pmatrix}.$$
Найти $P^n$ явно, вычислить $$\lim_{n\to\infty} P^n$$ и скорость сходимости. При каких $$a,b$$ цепь не эргодична?

**2.** Цепь на состояниях $$\{1,\dots,6\}$$ с матрицей
$$P=\begin{pmatrix}
0 & 1 & 0 & 0 & 0 & 0\\
1 & 0 & 0 & 0 & 0 & 0\\
0 & 0 & \tfrac12 & \tfrac12 & 0 & 0\\
0 & 0 & 0 & 0 & 1 & 0\\
0 & 0 & \tfrac12 & \tfrac12 & 0 & 0\\
\tfrac13 & 0 & \tfrac13 & 0 & 0 & \tfrac13
\end{pmatrix}.$$
Нарисовать граф, выделить замкнутые классы и транзитные состояния, найти периоды. Найти все стационарные распределения и объяснить, почему оно не единственно. Найти вероятности поглощения из состояния 6 в каждый из замкнутых классов и $$\lim_{n\to\infty}P^n$$ там, где он существует.

**3.** Блуждание по $$\mathbb{Z}$$: $$p_{i,i+1}=p$$, $$p_{i,i-1}=1-p$$. Классифицировать состояния, исследовать на эргодичность и сильную эргодичность. Отдельно разобрать $$p=1/2$$ и показать нулевую возвратность.

**4.** Блуждание на $$\mathbb{Z}_+$$ с отражением: $$p_{i,i+1}=p$$, $$p_{i,i-1}=q$$ при $$i\ge1$$, $$p_{0,1}=p_0$$, $$p_{0,0}=q_0$$. Классифицировать состояния, исследовать на эргодичность и сильную эргодичность в зависимости от $$p,q,p_0$$. В эргодичном случае найти стационарное распределение.

**5.** Блуждание с двумя поглощающими состояниями 0 и $$M$$. Классифицировать состояния, найти вероятности поглощения в 0 и в $$M$$ и среднее время до поглощения. Рассмотреть конечное $$M$$ и $$M\to\infty$$ при $$p>q$$, $$p=q$$, $$p<q$$.

**6. Модель Эренфестов.** Две урны, $$N$$ шаров. На каждом шаге случайный шар перекладывается в другую урну, $$X_n$$ — число шаров в первой. Найти период, стационарное распределение и среднее время возвращения в состояние 0.

**7. Ожидание паттерна.** Монета подбрасывается до первого появления «ОО» (орёл-орёл). Построить цепь с поглощающим состоянием, найти $$\mathrm{E}\tau$$. То же для «ОР». Объяснить, почему ожидания различаются.

**8. Блуждание по графу.** Частица переходит в случайную соседнюю вершину графа. Показать, что стационарное распределение имеет вид $$\pi_i=\mathrm{deg}(i)/(2\vert E\vert)$$. Применить к коню на шахматной доске $$8\times8$$: найти среднее число ходов до возвращения в угловую клетку. Выяснить когда цепь периодична.

**9. Цепь с перезапуском.** Из состояния $$i\in\mathbb{Z}_+$$ переход в $$i+1$$ с вероятностью $$p_i$$ и в 0 с вероятностью $$1-p_i$$. Найти условия на $$\{p_i\}$$ для возвратности и положительной возвратности. Привести по примеру для каждого режима и для невозвратной цепи.

**10. Ветвящийся процесс Гальтона–Ватсона как цепь Маркова.** Пусть $$\xi_{n,k}$$, $$n\ge0$$, $$k\ge1$$, независимы и одинаково распределены, $$\mathbb{P}(\xi=j)=p_j$$, причём $$p_0>0$$ и $$p_0+p_1<1$$. Положим $$X_0=i$$ и
$$X_{n+1}=\sum_{k=1}^{X_n}\xi_{n,k}$$
(пустая сумма равна $$0$$).

1. Показать, что $$(X_n)$$ — однородная цепь Маркова на $$\mathbb{Z}_+$$ с переходными вероятностями $$p_{ij}=\mathbb{P}(\xi_1+\dots+\xi_i=j)$$. Явно выписать матрицу для $$\xi\sim\mathrm{Bernoulli}(p)$$ и для $$\xi\in\{0,2\}$$ с вероятностями $$p_0,\ p_2=1-p_0$$.
2. Классифицировать состояния: показать, что $$0$$ поглощающее, а все $$i\ge1$$ невозвратны. Выяснить, какие классы замкнуты и является ли цепь неприводимой.
3. Показать, что для любого $$i\ge1$$ почти наверное $$X_n=i$$ лишь конечное число раз. Вывести, что с вероятностью $$1$$ либо $$X_n\to0$$, либо $$X_n\to\infty$$.

**11. Теорема Пойа.** Для симметричного блуждания на $$\mathbb{Z}^d$$, $$d\ge2$$, показать, что $$p_{00}(2n)\sim c_d\, n^{-d/2}$$. Вывести возвратность при $$d=2$$ и невозвратность при $$d\ge3$$. Дополнительно: для блуждания на $$\mathbb{Z}^2$$ с вероятностями шагов вправо, влево, вверх, вниз, равными $$p,q,r,r$$ ($$p\ne q$$), найти асимптотику $$p_{00}(2n)$$ и сделать вывод о возвратности.

**12. Перемешивание колоды «верхняя карта в случайное место».** Колода из $$N$$ карт, состояние цепи — перестановка из $$S_N$$. За один шаг верхняя карта вынимается и вставляется на одну из $$N$$ позиций (включая верхнюю) равновероятно.

1. Показать, что цепь неприводима и апериодична. Показать, что матрица переходов дважды стохастическая, откуда равномерное распределение $$U$$ на $$S_N$$ стационарно и $$\mathrm{P}(X_n=\sigma)\to 1/N!$$.
2. Пусть $$T$$ — момент, когда карта, лежавшая изначально самой нижней, вставляется в колоду (сначала она поднимается на верх, затем перекладывается). Показать, что
   $$\mathrm{P}(X_T=\sigma,\ T=n)=\frac{\mathrm{P}(T=n)}{N!}\quad\text{для всех }\sigma,\ n,$$
   то есть $$T$$ — сильное стационарное время. *Указание:* в каждый момент карты, лежащие ниже исходной нижней, упорядочены равномерно среди всех возможных порядков.
3. Показать, что $$T$$ распределено как сумма независимых геометрических величин с параметрами $$\tfrac1N,\tfrac2N,\dots,\tfrac NN$$. Вывести, что
   $$\mathrm{E}T=N\sum_{j=1}^N\frac1j\sim N\ln N.$$
4. Вывести из п. 2 оценку $$\|\mathrm{P}(X_n\in\cdot)-U\|_{TV}\le\mathrm{P}(T>n)$$. Показать, что $$\mathrm{P}(T>N\ln N+cN)\le e^{-c}$$ при $$c>0$$. Сколько шагов нужно для разумного перемешивания колоды в $$52$$ карты?

## Набор 6

1. Пусть $$P=(p_{ij})$$ — матрица переходов неприводимой цепи Маркова на конечном множестве $$S$$.

    **Обратимой** будем называть цепь, для которой существует распределение $$\pi$$, удовлетворяющее **уравнениям детального баланса**:
    $$
    \pi_i p_{ij}=\pi_j p_{ji}\qquad (i,j\in S).
    $$

    1. Доказать, что всякое распределение $\pi$, удовлетворяющее уравнениям детального баланса, стационарно.
    2. Доказать, что цепь обратима тогда и только тогда, когда для любого цикла $$i_0,i_1,\ldots,i_k=i_0$$ выполняется критерий Колмогорова:
       $$
       \prod_{\ell=0}^{k-1}p_{i_\ell i_{\ell+1}}
       =\prod_{\ell=0}^{k-1}p_{i_{\ell+1}i_\ell}.
       $$
    3. Рассмотреть блуждание по циклу из $N\geslant 3$ вершин:
       $$
       p_{i,i+1}=p,\qquad p_{i,i-1}=q=1-p,
       $$
   где индексы берутся по модулю $$N$$, а $$0<p<1$$. Найти стационарное распределение и определить, при каких $$p$$ цепь обратима.
    4. Исследовать период цепи и существование предела $$P^n$$.

2. Спектральный метод и скорость сходимости

    Рассмотрим случайное блуждание с ленивыми шагами по циклу $$\mathbb Z/N\mathbb Z$$:
$$
p_{i,i}=\frac12,\qquad
p_{i,i+1}=p_{i,i-1}=\frac14,
$$
где $$N\geqslant3$$, индексы берутся по модулю $$N$$.

    1. Найти стационарное распределение и доказать эргодичность.
    2. Найти все собственные значения матрицы переходов, используя дискретное преобразование Фурье.
    3. Получить явную формулу для $$p_{ij}^{(n)}$$.
    4. Найти второе по величине собственное значение и спектральный зазор
       $$
       \gamma=1-\lambda_2.
       $$
    5. Получить оценку скорости сходимости к стационарному распределению и определить порядок времени перемешивания при $$N\to\infty$$ для фиксированной точности.

3. Случайное блуждание по дереву

    Пусть $$T$$ — бесконечное корневое $$d$$-регулярное дерево, $$d\geqslant2$$: из каждой вершины выходят ровно $$d$$ рёбер. Частица на каждом шаге равновероятно выбирает одного из соседей.

    1. Показать, что расстояние $$R_n$$ от частицы до корня само является цепью Маркова. Выписать её переходные вероятности.
    2. Найти вероятность когда-либо вернуться в корень после выхода из него.
    3. Классифицировать состояния исходной цепи при $$d=2$$ и $$d\geqslant 3$$.
    4. Найти вероятность достижения корня при старте из вершины на расстоянии $$k$$.
    5. Исследовать ожидаемое время возвращения в корень.

4. Цепь рождения–гибели с переменными вероятностями

    Рассмотрим цепь на $$\mathbb Z_+$$:
$$
p_{i,i+1}=a_i,\quad
p_{i,i-1}=b_i,\quad
p_{i,i}=1-a_i-b_i,\qquad i\ge1,
$$
    а из $$0$$:
$$
p_{0,1}=a_0,\qquad p_{0,0}=1-a_0,
$$
    где $$a_0>0$$, $$a_i,b_i>0$$ и $$a_i+b_i\leqslant 1$$.

    1. Получить необходимое и достаточное условие возвратности в терминах ряда, составленного из отношений $$b_i/a_i$$.
    2. Найти необходимое и достаточное условие положительной возвратности.
    3. Вывести формулу стационарного распределения (когда оно существует).
    4. Применить критерии к случаю
       $$
       a_i=\frac12-\frac{c}{i+1},\qquad
       b_i=\frac12+\frac{c}{i+1},\qquad i\ge1,
       $$
       при $$0<c<\frac12$$ и $$a_0=1$$. Определить точные интервалы $$c$$, соответствующие нулевой и положительной возвратности.
    5. Объяснить, почему даже очень слабый дрейф к нулю может изменить тип возвратности.

5. Случайное блуждание с ловушкой и редкими выходами

    Пусть $$X_n$$ — цепь на $$\{0,1,\ldots,N\}$$, $$N\geqslant2$$, с переходами
$$
\begin{aligned}
&p_{0,0}=1-\varepsilon,\qquad p_{0,1}=\varepsilon,\\
&p_{i,i-1}=p_{i,i+1}=\frac12,\qquad 1\le i<N,\\
&p_{N,N-1}=1,
\end{aligned}
$$
где $$0<\varepsilon\leqslant 1$$.

    1. Доказать неприводимость и определить период.
    2. Найти стационарное распределение.
    3. Найти среднее время первого достижения состояния $$N$$ при старте из $$0$$.
    4. Исследовать асимптотику найденного среднего времени при $$\varepsilon\to0$$ с фиксированным $$N$$.
    5. Объяснить, почему при малом $$\varepsilon$$ траектория может долго оставаться около $$0$$, хотя цепь неприводима и имеет единственное стационарное распределение.

6. Квазистационарное распределение

    Пусть $$X_n$$ — цепь Маркова на $$\{0,1,2\}$$ с матрицей
$$
P=\begin{pmatrix}
1&0&0\\
\frac14&\frac12&\frac14\\
\frac14&\frac14&\frac12
\end{pmatrix}.
$$
Состояние $$0$$ поглощающее. Положим
$$
\tau_0=\inf\{n\geqslant0:X_n=0\}.
$$

    1. Найти распределение $$X_n$$ при условии $$\tau_0>n$$, если $$X_0=1$$.
    2. Доказать существование предела
   $$
   \nu_j=\lim_{n\to\infty}\mathbb P_1(X_n=j\mid\tau_0>n),\qquad j=1,2.
   $$
    3. Показать, что $$\nu$$ является левым собственным вектором подматрицы $$Q$$ переходов между состояниями 1 и 2, соответствующим её наибольшему собственному значению $$\lambda$$.
    4. Доказать, что при начальном распределении $$\nu$$ время до поглощения имеет геометрическое распределение с параметром $$1-\lambda$$.
    5. Сформулировать достаточные условия существования и единственности квазистационарного распределения для произвольной конечной цепи с одним поглощающим состоянием.

7. Метастабильность: переход между двумя областями

    Рассмотрим цепь Маркова на состояниях $$\{0,1,2,3\}$$ с матрицей
$$
P_\varepsilon=
\begin{pmatrix}
1-\varepsilon&\varepsilon&0&0\\
\frac12&\frac12-\varepsilon&\varepsilon&0\\
0&\varepsilon&\frac12-\varepsilon&\frac12\\
0&0&\varepsilon&1-\varepsilon
\end{pmatrix},
\qquad 0<\varepsilon<\frac12.
$$

    1. Показать, что цепь неприводима, апериодична и обратима.
    2. Найти стационарное распределение $$\pi^{(\varepsilon)}$$.
    3. Вычислить среднее время первого достижения состояния 3 при старте из 0:
   $$
   H_{03}=\mathbb E_0\tau_3.
   $$
    4. Найти асимптотику $$H_{03}$$ при $$\varepsilon\to0$$.
    5. Исследовать собственные значения матрицы $$P_\varepsilon$$ и асимптотику спектрального зазора при $$\varepsilon\to0$$.
    6. Объяснить, как наличие редкого перехода между двумя частями пространства состояний связано с большим временем достижения и медленным перемешиванием.