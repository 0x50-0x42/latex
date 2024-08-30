# Table borders

* For adding the vertical lines that form both the border and also separator of columns in a table, we need to add the `|` in the column alignments.
* For adding the horizontal lines to separate each row, we use the `\hline` command.
* Example:

```tex
\begin{tabular}{|c|l|l|r|}
	\hline
	No. & Item & Quantity & Price \\
	\hline
	1 & Pen & 3 & 10 \\
	\hline
	2 & Pencil & 3 & 5 \\
	\hline
\end{tabular}
```
* The `\cline{i-j}` command creates a horizontal line in the columns `i` and `j`. In simple words, this command is used for drawing a horizontal line selectively.

## Dashed borders

* To create dashed borders, we can use the package `arydshln`.
* For creating vertical borders we use the `:`.
* For creating horizontal lines, we use `\hdashline[size of dash / space between dashes]`.
* For selectively creating horizontal lines, we use `cdashline{i-j}[size of dash / space between dashes]`.
* Example:
	* `\hdashline[1pt/2pt]`
	* `\cdashline{2-3}[1pt/2pt]`

See [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session2/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session2/doc2.tex).

---
