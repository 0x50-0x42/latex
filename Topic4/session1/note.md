# Tables

* One can create a table using the `tabular` environment:
	* `\begin{tabular}{cols}`<br>`...`<br>`\end{tabular}`
	* Here `cols` is replaced by any of the following alignments:
		* `l`
		* `r`
		* `c`
		* `p{Xcm}`: left align
	* `&` denotes a column.
	* `\\` denotes the end of a row.
* Example table:
```tex
\begin{tabular}{clr}
	No. & Item & Price \\
	1 & Pen & 10 \\
	2 & Pencil & 5 \\
\end{tabular}
```

* The `tabular` environment is followed by the alignment for each column `clr` where:
	* `c` represents center alignment, this is for the first column.
	* `l` represents left alignment, this is for the second column.
	* `r` represents right alignment, this is for the third column.
* To adjust the column width, we use:

```tex
\begin{tabular}{p{1cm}p{3cm}p{2cm}}
	No. & Item & Price \\
	1 & Pen & 10 \\
	2 & Pencil & 5 \\
\end{tabular}
```
Here, the first column is $1$ cm in width, the second column is $3$ cm in width and the third column is $2$ cm in width.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session1/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session1/doc2.tex).


---
