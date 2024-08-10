# Page orientation, page breaks, set footnotes

## Orientation

* Orientation of a page refers to the direction in which it is displayed.
* Types of orientation:
	* Portrait(default) $\rightarrow$ height $>$ width.
	* Landscape $\rightarrow$ width $>$ height, helpful when we have a table with many columns.
* `geometry` package can be used to change the orientation of the entire document as: `\usepackage[landscape]{geometry}`.

## Changing orientation of a specific part

* `\usepackage{lscape}` $\rightarrow$ rotates **content** by $90$ degrees.
* `\usepackage{pdflscape}` $\rightarrow$ rotates **page** by $90$ degrees.
* Write the contents between `\begin{landscape}` and `\end{landscape}`.

## Page breaks

* `\pagebreaks`
* `\newpage`
* We can use one of these two commands if we want some content of the page to appear on a newpage.

## Footnotes

* These convey more information about certain statements that one writes in a document.
* Written at the bottom.
* Added using the `\footnote{text to be displayed as footnote}` command.

---
