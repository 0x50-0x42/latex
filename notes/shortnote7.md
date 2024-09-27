# Packages
* For getting 1 inch margins on all sides, use package: `fullpage`. Simply writing `\usepackage{fullpage}` is enough.
* Size of font, type of paper can be mentioned in `\documentclass` as:
```tex
\documentclass[10pt, a4paper]{article}
```

<p align="center">
OR
</p>

```tex
\documentclass[10pt, letterpaper]{article}
```
and many more...

* Package `geometry` is used if we want to customize the margins of our paper.
* We can also specify the size of the paper as:

```tex
\usepackage[paperwidth=8.5in, paperheight=11in]{geometry}
```
* For using special symbols like the set of all real numbers, we use the package `amsfonts`. Using this package, we will be able to work with the `\mathbb{<letter>}` command.

---

# Macros
* Used to define our own $\LaTeX$ commands.
* `\def\<custom user commandname>{<text or expression or command(s) to be substituted>}`.
* To create macros, we use the `\def` command as:
```tex
\def\eq1{\dfrac{x}{3x^2+1}}
```
`\eq1` is the command defined by us. So anytime we need to use that fraction, we don't have to write it, instead we can just use `\eq1` in place. But we must use it within `$...$` or `$$...$$` as: `$\eq1$` or `$$\eq1$$`

* We can also use the `\newcommand` for defining our own commands.
```tex
\newcommand{cmd}[args]{def}
```
> `cmd` &rarr; a command name beginning with a `\`. It must not be already defined and must not begin with `\end`.

> `args` &rarr; an integer from 1 to 9 denoting the number of arguments of the command being defined. The default is for the command to have no arguments.

> `def` &rarr; Output of the command.

* Example:
```tex
\newcommand{\boldItalic}[1]{\textbf{\textit{#1}}}
```
Here, our custom command `\boldItalic` takes a single argument and will be used as:
```tex
This \LaTeX session is \boldItalic{amazing}.
```
Only a single pair of `{ }` have been used with `\boldItalic`. The number of `{ }` pairs used with a custom command denotes the number of arguments that that custom command takes.
* Example:
```tex
\newcommand{\intro}[2]{Hello and welcome to this \emph{#1} \LaTeX \textbf{#2}}
```
Here, the custom command `\intro` will be used as:
```tex
\intro{extra}{session}
       % #1      #2
```
`extra` will be emphasized and `session` will appear bold. So, whatever text we put within `{ }` of the custom command are all arguments. `#1`, `#2`, are basically argument calls that will get replaced by the text placed within the corresponding number of braces of the custom command.
* Click [here](https://waterprogramming.wordpress.com/2021/10/05/make-latex-easier-with-custom-commands/) to see more.

---

# Graphics

* For changing the width and height of an image in terms of percentage, we use:
```tex
\includegraphics[width=0.5\textwidth]{parrot.png} % image size is 50% of textwidth
```
* We cannot use `width` and `height` at the same time. We can use only one of them.

<ins>Note</ins>: If we want to get a larger fraction then we can use `\dfrac{<numerator>}{<denominator>}`. It displays larger fraction in inline math mode. It requires the `amsmath` package.


---
