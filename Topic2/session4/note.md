# Multicolumn document

* A document is typeset to single-column by default.
* Two-columns are generally used in research papers, journals, large books, etc.
* Documents like magazines, newspapers, posters, etc. are typeset in multiple columns.
* To typeset the entire document into two columns just mention `[twocolumn]` as a parameter while mentioning the `\documentclass{}`.
* The `multicol` package can also be used to typeset a document into multicolumns. The contents must be written between <br>`\begin{multicols}{<No. of columns>}`<br>`...`<br>`\end{multicols}` environment.
* We can also set some spacing between the columns by using the `\setlength{\columnsep}{<X>pt}` command.
* `\setlength{\columnseprule}{<X>pt}` can also be used to add a line separating the columns apart.
* If we want some text to start from the next column, then we can use `\columnbreak`.

---
