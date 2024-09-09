---
layout: single
author_profile: true
toc: true
toc_sticky: true
permalink: /for-students/jupyter-notebook/
sidebar:
  nav: "docs"
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# Несколько слов о Jupyter Notebook

[Jupyter Notebook](https://jupyter.org/) -- интерактивный блокнот, с помощью которого можно составить отчёт,
содержащий текст с математическими вставками, программный код и в котором отображается результат исполнения кода
("печатающие" и "рисующие" функции). Весьма удобен для выполнения учебных и не только работ.

## Установка и запуск

 - Online. Например, [Google Colaboratory](https://colab.google/). Здесь ничего устанавливать не нужно
и запуск производится через веб-интерфейс.
 - Если на вашем ПК есть [Python](https://python.org), то Jupyter Notebook можно установить через
[pip](https://pypi.org/project/pip/). Запуск -- через консоль.
 - Это далеко не все, можно устанавливать через другие менеджеры пакетов или дистрибутивы, например,
 [Conda](https://docs.conda.io/en/latest/) и [Anaconda](https://www.anaconda.com/) соответственно. Запуск --
через консоль или GUI-интерфейс соответственно.

## О файле типа *.ipynb*

Исходники представляют блоков двух типов:

- текстовые в формате [Markdown](https://daringfireball.net/projects/markdown/) --
облегченный язык разметки текста (например, контент этого сайта набран как раз с его помощью),
- исполняемый код (Python, R, *etc.*).


### Кратко о *Markdown*

Весь базовый синтаксис может быть описан в виде следующей схемы:

```
# First level title

## Second level title

Indent

Another indent. *Italic text*. **Bold text**.
***Bold and italic text***. [Some site](https://example.com)

- First simple bulleted list entry
- Second simple bulleted list entry

1. First simple numbered list entry
2. Second simple numbered list entry

- Nested bulleted list example
    - Nested bulleted list example
```

Более детально детально с синтаксисом Markdown также можно ознакомиться [здесь](https://www.markdownguide.org/).

Также внутри Markdown-блока можно делать LaTeX-вставки:

- inline example: `Some text $a^2 + b^2 = c^2$`
- display math:

```
Some content

$$Some complicated expression$$

Some content
```

Несколько слов о LaTeX можно прочитать на соответствующей [странице](/for-students/latex).

### Полезные модули для Python

Могут быть полезными следующие модули:

- [NumPy](https://numpy.org/). Для численных вычислений, в частности, удобен для работы с векторами.
- [SciPy](https://scipy.org/). Включает в себя численные алгоритмы из различных областей математики.
- [Matplotlib](https://matplotlib.org/). Для рисования различных графиков.
- [Pandas](https://pandas.pydata.org/). Для анализа и преобразования данных.
- Несколько фрейморков для ML:
    - [scikit-learn](https://scikit-learn.org/stable/)
    - [TensorFlow](https://www.tensorflow.org/)
    - [Keras](https://keras.io/)