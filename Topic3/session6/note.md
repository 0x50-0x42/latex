# Writing mathematics
* Mathematical expressions are written between:
	* `$ ... $`
	* `\[ ... \]`
* For writing complex mathematical expressions, we need to include either `amsmath` or `mathtools`.
* `amsmath` is included in `mathtools`.
* `$ ... $` basically typsets the expression written within it along with the regular text.
* `\[ ... \]` displays the expression written within it in a separate line.

## Fractions
* Fractions are typeset using `\frac{numerator}{denominator}`.

## Variable size of braces
* Sizes:
	* `\Bigg`
	* `\bigg`
	* `\Big`
	* `\big`

## Summation
* Syntax:
	* `\sum_{min}^{max}`

# Integration, matrices and equations

## Integration
* Syntax: similar to summation:
	* `\int_{min}^{max}`
* Limits:
	* `\lim_{ ... }`

## Matrix
* Written within:
	* `\begin{ ... }`<br>`...`<br>`\end{ ... }`
* Environments:
	* `matrix` $\rightarrow$ without border
	* `pmatrix` $\rightarrow$ with round bracket
	* `bmatrix` $\rightarrow$ with box bracket
	* `Bmatrix` $\rightarrow$ with curly bracket
	* `vmatrix` $\rightarrow$ with \|
	* `Vmatrix` $\rightarrow$ with \|\|
* `&` denotes the new column.
* `\\` denotes the new row.

## Equations
* Written within:
	* `\begin{equation}`<br>`...`<br>`\end{equation}`
* Only one equation can be written in the environment.
* These equations are centered and numbered.
* There is not need of `$ ... $`.

## The align environment
* Used to show steps for solving an equation.
* Also used to show equations on multiple lines.
* `\\` denotes the next line.

If an equation is `3x+6=9`, then the `=` will not be aligned properly for each step of the solution because the equation and its steps will be centered by default, to align the `=` of each step with the `=` of the other step, we will use `&` before `=`.

Each step of the solution will also contain equation numbers. To remove the from each step, use `\nonumber` in the required steps:

```tex
\begin{align}
	3x - 6 &= 9\\
	3x &= 9 + 6 \nonumber \\
	x &= \frac{9 + 6}{3} \nonumber \\
	x &= 5 \nonumber
\end{align}
```

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session6/doc1.tex).

---
