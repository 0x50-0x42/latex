# Bullets and numbering

## Unordered list
* Bulleted list.
* Created as follows:

```tex
\begin{itemize} % begin the itemize environment
	\item Mouse
	\item Keyboard
	\item Monitor
\end{itemize}
```
* Each item represents a point in the list.

## Ordered list
* Numbered list.
* Created as follows:

```tex
\begin{enumerate} % begin the enumerate environment
	\item Red
	\item Blue
	\item Green
\end{enumerate}
```

## Description list
* Labeled list.
* Created as follows:

```tex
\begin{description} % begin the description environment
	\item[Input Devices]: mouse, keyboard
	\item[Output Devices]: monitor, printer
\end{description}
```
* The command `\item` takes an argument in `[]` brackets.

## Nested list
* List inside another list.
* Structure:

```tex
% any list can be nested within any other list
\begin{itemize}
	\item item1
	\item item2
	\begin{itemize}
		\item subitem2.1
		\item subitem2.2
		\begin{enumerate}
			\item subsubitem2.2.1
			\item subsubitem2.2.2
		\end{enumerate}
	\end{itemize}
	\item item3
	\begin{desciption}
		\item[subitem3.1:] blah blah
		\item[subitem3.2:] blah blah
	\end{description}
\end{itemize}
```

## Changing numbering style in enumerate
* To change the numbering style of enumerate, we need the `enumerate` package.
* Following styles are supported:
	* (i, ii, ...)
	* (I, II, ...)
	* (a, b, ...)
	* (A, B, ...)
	* (1, 2, ...)
* Syntax:

```tex
\begin{enumerate}[<style>]
	\item someitem
	...
\end{enumerate}
```
* Example:

```tex
\begin{enumerate}[(A)]
	\item someitem1
	\item someitem2
	% and so on
\end{enumerate}
```
* The list items will be numbered as <br>`(A) subitem1`<br>`(B) subitem2`.<br> Notice that the `()` have also been included.

## Change bullet style
* To change the style of the bullets in the unordered list, for that we need the `amssymb` package.
* Style:
	* `\blacksquare`
	* `\square`
	* `\bullet`
	* `\cdot`
	* `\diamond`
	* `-`
	* `+`
	* `\circ`
* Level:
	* `i`
	* `ii`
	* `iii`
	* `iv`
* This level number denotes the nesting level.

* Command:
	* `\renewcommand{\labelitem<Level>}{$<Style>$}`

* Example:
	* `\renewcommand{\labelitemiv}{$\diamond$}`

---
