# Merging rows and columns

* To merge rows of a table, we need to use the `multirow` package.
* Syntax:
	* `\multirow{NumberOfRows}{width}{content of the row}`.
	* `NumberOfRows` means the number of rows to merge.
	* `width` is any value, but if `*` is used it means the content's natural width.
	* `content of row` is the content of the row that will displayed in the table.
* Example:

```tex
\begin{tabular}{|c|l|l|r|}
	\hline
	No. & Item & Quantity & Price \\
	\hline
	1 & Pen & 3 & \multirow{2}{*}{3} & 10 \\
	\cline{1-2}\cline{4-4}
	2 & Pencil & & 5 \\
	\hline
\end{tabular}
```

	* Here, `2` means the number of rows that will be merged, in this table it's the $2^{nd}$ and the $3^{rd}$ rows.
	* `*` means the natural width of the cell.
	* `3` is the cell content that will be displayed in the table.
* We don't need any packages to merge columns, we just use:
	* `\multcolumn{TotalColumns}{Alignment}{actual content}`.
	* `TotalColumns` means number of columns to be merged.
	* `Alignment` means of the alignment of the cell content i.e. `l`, `r` or `c`.
	* `actual content` means the actual content that will be displayed in the column.
* We can adjust the spacing of the table using the `\arraystretch` command as:
	* `\renewcommand{\arraystretch}{value}`.
	* `value` is $1$ by default.
	* This command is used before the `tabular` environment.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session3/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session3/doc2.tex).

---
