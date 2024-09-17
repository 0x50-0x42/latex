# Overlays

* Add some animation effects to the text in the slides.

* Sometimes we may need to display certain
	* text
	* rows of a table
	* items
* We need to <em>reveal</em> them one by one.

* Following are the animation effects.

## `\pause`

* Used in lists, blocks, text, tables, etc.
* Dislays one by one.
* Items appear in Sequential order.

---

## Overlay

* Used in lists, blocks, etc.
* Sequence number is specified.
* Displays items in specified sequence.
* Syntax:
	* `<No.->`
	* `<No.>` $\rightarrow$ display the item only in slide number `No.`.

---

* Use `\pause` after the block environments.
```tex
\begin{block}{Some title}
	...
\end{block}
\pause

\begin{alertblock}{title}
	...
\end{alertblock}

...
...
```

* Use the sequence number along with the block environment.
```tex
\begin{block}{Some title}<1->
	...
\end{block}

\begin{alertblock}{title}<3->
	...
\end{alertblock}

...
...
```

## Onslide

* Similar to overlay.
* Displays text in specified sequence.
* Used for normal text, tables, etc.
* `\onslide<No.->`, where `No.` is a sequence number.
* This command should be written <em>prior</em> to the items in that row.

---

* We can set the text <em>to be displayed</em> to light grey color using: `\setbeamercovered{transparent}`.
* We can use this command for slides of our choice.
* We can also use `\setbeamercovered{invisible}` if donot want <em>to the text to be displayed</em> to be visible.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session3/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session3/doc2.tex), [doc3.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session3/doc3.tex).

---
