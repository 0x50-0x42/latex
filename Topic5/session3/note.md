# Cross referencing

* Cross referencing means refering to certain part within the same document.
* We can refer to:
	* Section, subsection ...
	* Table.
	* Figure.
	* Page number.

* There are two parts:
	1. Involves creating a label with some key.
		* `\label{Some KEY}`
	2. Involves refering with that key.
		* `\ref{Some KEY}` $\rightarrow$ this command displays the number of either the chapter, section, subsection, table, etc which is clickable.
		* `\pageref{Some KEY}` $\rightarrow$ this command displays the name of either the chapter, section, subsection, table, etc. which is clickable.
		* `\nameref{Some KEY}` $\rightarrow$ this command inserts the page where the element whose label is used appears. That page number is clickable.

<ins>NOTE:</ins>: For the references to work properly, include the `hyperref` package. If `hyperref` is not included then the references will
not be clickable.

* Best practices used for defining labels

	* `ch:` $\rightarrow$ for chapter.
	* `sec:` $\rightarrow$ for section.
	* `subsec:` $\rightarrow$ for subsection.
	* `fig:` $\rightarrow$ for figure.
	* `tbl:` $\rightarrow$ for table.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic5/session3/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic5/session3/doc2.tex).

The section numbers, page numbers automatically change.

---
