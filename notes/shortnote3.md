# Tables

* We can add any number of vertical lines in a table:
```tex
\begin{tabular}{|c||c|c|c|}
	\hline
	$x$ & 1 & 2 & 3\\
	\hline
	$f(x)$ & 10 & 11 & 12\\
	\hline
\end{tabular}
```
This code produces a table with four columns and two rows and there will be two vertical lines after the first column.

---

* There is another option/parameter that can be used with `table` environment and that is the `H` parameter which used as:
```tex
\begin{table}[H]
	\begin{tabular}{|c||c|c|c|}
		\hline
		$x$ & 1 & 2 & 3\\
		\hline
		$f(x)$ & $\frac{1}{2}$ & 11 & 12\\
		\hline
		\end{tabular}
	\caption{This table contains some values}
\end{table}
```
`H` tells the compiler to place the table at that exact location in the page, instead of moving it to somewhere else. Requires the `float` package to work.
* The placement of `\caption{}` inside the `table` environment determines where the caption will appear for the table. Here the `\caption{}` is after `\end{tabular}` which means that the caption will appear below the table. If `\caption{}` is before `\begin{tabular}`, then the caption will appear above the table.

---

* To add paragraphs inside a table, we will need to use the `p` argument which indicates that we want to use paragraphs as cell entries.
* Example:
```tex
\begin{table}[H]
	\centering
	\renewcommand{\arraystretch}{1.5}
	\begin{tabular}{|l|p{3in}|}
		\hline
		$f(x)$ & $f'(x)$\\
		\hline
		$x>0$ & The function $f(x)$ is increasing.The function $f(x)$ is increasing.The function $f(x)$ is increasing.The function $f(x)$ is increasing.The function $f(x)$ is increasing.\\
		\hline
	\end{tabular}
	\caption{Relationship between $f(x)$ anad $f'(x)$}
\end{table}
```
`p` indicates that we are using a paragraph for a cell. To enable text-wrapping, we will also mention the width of the cell in `{ }`. If the width of the contents exceeds the mentioned cell width, a line break will occur.

---
