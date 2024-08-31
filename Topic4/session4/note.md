# Handling large data in a table

* To handle large data in a table, we use the `longtable` package and instead of `tabular` environment, we use the `longtable` environment.
* Used as:
	* `\begin{longtable}{alignment}`<br>`...`<br>`\end{longtable}`
	* `alignment` can be any combination of `c`, `r` or `l` either separated by `|` or nothing.
* Now, if we use a really long table, then it will easily span across multiple pages.

* Observe that there is a problem in [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session4/doc1.tex) and that is, we cannot see the the heading of the table in the pages where the table has been spanned. To resolve that we use the `\endhead` command just after we have mentioned the names of the columns.

See: [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session4/doc2.tex).

---
