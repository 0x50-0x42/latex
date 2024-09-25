# Lists

## Enumerated lists
* To start the list numbering from a number other than 1, we will use the `\setcounter{enumi}{<number>}` command.
* Example:
```tex
\begin{enumerate}\setcounter{enumi}{5}
	\item Pencil
	\item Calculator
	\item Ruler
	\item Notebook
\end{enumerate}
```
This will start numbering the list from 6 which is 5+1. So any number that you provide in `{ }`, the list will start counting from the number that is 1 more than the mentioned number.
* If we don't want the list to be numbered, we just use `[]` after `\item` as:
```tex
\begin{enumerate}\setcounter{enumi}{5}
	\item[] Pencil
	\item[] Calculator
	\item[] Ruler
	\item[] Notebook
\end{enumerate}
```
This is an un-numbered list(not unordered list).

---
