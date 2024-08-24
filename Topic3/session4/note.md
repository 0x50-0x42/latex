# Spacing in document

## Fixed spacing
* By default a $\LaTeX$ document is single-spaced.
* For setting the spacing, we use the `setspace` package.
* For setting the spacing for the entire document:
	* `\singlespacing`
	* `\onehalfspacing`
	* `\doublespacing`
* For setting the spacing for a certain part of the document:
	* `\begin{singlespace | onehalfspace | doublespace}`<br>`...`<br>`\end{...}`

## Vertical spacing
* Here, we can provide spacing between the content of the document, for example, spacing between the two paragraphs, a between some text and an image, or between text and a table.
* Following commands are used:
	* `\vspace{Xpt}`
	* `\smallskip`
	* `\medskip`
	* `\bigskip`
	* `\vfill` $\rightarrow$ produces a rubber length which can stretch or shrink vertically.

## Horizontal spacing
* Following commands are used:
	* `\` $\rightarrow$ adds a single space
	* `\,` $\rightarrow$ adds a little more space than `\`.
	* `\hspace{Xpt}` $\rightarrow$ sets horizontal space of X points.
	* `\hfill` $\rightarrow$ produces a rubber length which can stretch or shrink horizontally.

<ins>Note</ins>:<br>
When we simply write some text on a new page in article, or book or report, the first line is indented. To remove that indentation, we use the `\noindent` command before writing our text.

## Custom spacing
* We can also have custom spacing.
* Custom spacing for entire document:
	* `\spacing{X}`
* Custom spacing for a certain part:
	* `\begin{spacing}{X}`<br>`...`<br>`\end{spacing}`
* For using these commands and environments, we will need the `setspace` package.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session4/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session4/doc2.tex), [doc3.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session4/doc3.tex) and [doc4.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session4/doc4.tex).

---
