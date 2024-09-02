---
layout: single
author_profile: true
toc: true
toc_sticky: true
permalink: /for-students/latex
sidebar:
  nav: "docs"
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# Несколько слов о LaTex

[LaTeX](https://www.latex-project.org/) -- один из наиболее популярных макропакетов для системы компьютерной
верстки [TeX](https://tug.org/) (иными словами -- высокоуровневое расширение для TeX). Предназначен для набора и
верстки текста, содержащего в том числе математические выражения.

## Установка и запуск

 - Online. Например, [Overleaf](https://overleaf.com/). Здесь ничего устанавливать не нужно
и запуск производится через веб-интерфейс.
 - Локальная установка:
     - Win. [MikTeX](https://miktex.org/) или [TeX Live](https://www.tug.org/texlive/).
     - Linux. Упомянутый [TeX Live](https://www.tug.org/texlive/).
     - macOS. [MacTeX](https://www.tug.org/mactex/).
     - Ко всем упомянутым дистрибутивам прилагается простенькая IDE [TeXworks](https://www.tug.org/texworks/).

## Структура файла с расширением *tex*

Набор tex-файла можно сравнить с процессом программирования. Как в начале любого нетривиального исходного файла практически
любого языка программирования сначала импортируются/подключаются необходимые модули и библиотеки, так и tex-файл начинается
с *преамбулы*. Приведём пример преамбулы:

```
\documentclass[10pt]{extarticle}

\usepackage{cmap}
\usepackage[T1,T2A]{fontenc}
\usepackage[utf8]{inputenc}
\usepackage[english, russian]{babel}

\usepackage{amssymb}
\usepackage{amsmath}
\usepackage{amsthm}
\usepackage{dsfont}
\usepackage{bm}
\usepackage{diagbox}

\usepackage[left=5mm,right=5mm,top=5mm,bottom=5mm,bindingoffset=0mm]{geometry}
\usepackage{indentfirst}

\usepackage{float}

\DeclareMathOperator{\N}{\mathbb{N}}
\DeclareMathOperator{\R}{\mathbb{R}}
\DeclareMathOperator{\Z}{\mathbb{Z}}
\DeclareMathOperator{\CC}{\mathbb{C}}
\DeclareMathOperator{\PP}{\mathrm{P}}
\DeclareMathOperator{\Expec}{\mathrm{E}}
\DeclareMathOperator{\Var}{\mathrm{Var}}
\DeclareMathOperator{\Cov}{\mathrm{Cov}}
\DeclareMathOperator{\asConv}{\xrightarrow{a.s.}}
\DeclareMathOperator{\LpConv}{\xrightarrow{Lp}}
\DeclareMathOperator{\pConv}{\xrightarrow{p}}
\DeclareMathOperator{\dConv}{\xrightarrow{d}}
```

В первой строке преамбулы мы определяем тип документа. В данном случае -- *extarticle* (более тонкие настройки
в сравнении со стандартным *article*). Далее с помощью команды `\usepackage[options]{packageName}` подключаем
нужные нам пакеты (в данном случае настраиваем язык, кодировку, подключаем дополнительные математические команды и
шрифты, задаем разметку страницы и формат текска). В конце определяем нужные нам дополнительные математические команды.

Основной контент набирается в среде *document* (можно считать аналогом функции *main*):

```
\begin{document}
   Content
\end{document}
```

Некоторые особенности набора текста:
 - Перед очередным новым абзацем должна быть пустая строка
 - Каждая новая глава/параграм/пункт начинается с соответствующей команды `\chapter{chapeterName}`,
 `\section{sectionName}`, `\subsection{sectionName}`
 - Математические выражения внутри текста набираются внутри одинарных долларовых скобок `Text $formula$ text`
 - Выделенные выражения выделяются двойными долларовыми скобками `$$Complicated formula$$`. Иногда удобнее
 использовать среды *equation*, *eqnarray*, *align*, *gather* и т.п., особенно если нам нужны нумерованные формулы
 - Списки
```
\begin{enumerate}
    \item First ordered entry
    \item Second ordered enter
\end{enumerate}
\begin{enumerate}
    \item First unordered entry
    \item Second unordered enter
\end{enumerate}
```

## Further reading

Написанное очень сложно назвать даже *руководством для новичка*, так как покрывает очень малое, поэтому интересующиеся
могут посмотреть источники/литературу:

 - [Comprehensive TeX Archive Network](https://www.ctan.org/)
 - [Overleaf documentation](https://www.overleaf.com/learn)
 - [Список англоязычных книг](https://www.latex-project.org/help/books/)
 - [Stack Overflow для TeX](https://tex.stackexchange.com/)
 - С.М.Львовский. Набор и вёрстка в системе LaTeX