# CSV to $\LaTeX$ table
* Package: `csvsimple`.
* This package provides us with the facility of processing a CSV file and displaying it in the $LaTeX$ tabular format.
* Let's consider a CSV file named `items.csv`:

```csv
No., Item, Price
1, Scale, 20
2, Red Pen, 10
3, Pencil, 20
4, Eraser, 5
```

Following is the $\LaTeX$ code to display the above CSV file in $\LaTeX$ tabular format:
```tex
\documentclass{article}

\usepackage{csvsimple}

\begin{document}
	\csvautotabular{items.csv}
\end{document}
```

---