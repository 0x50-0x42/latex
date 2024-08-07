# Commands vs Environments

## Command

* In $\LaTeX$, a command starts with a backslash character followed by the name of the command.
* Example: `\today`, `\pagebreak`, etc.
* Some commands take arguments or parameters which are placed between curly braces.
* Example: `\title{...}`, `\author{...}`, `\section{...}`, etc.
* Some commands take optional arguments which are mentioned in square brackets.

## Environment

* An environment is denoted as: `\begin{...} ...  \end{...}`
* Example:
```tex
\begin{landscape}
	...
\end{landscape}
```

# Package vs Class

* Basic difference: In $\LaTeX$, a document can have only 1 class but many packages.

## Package

* Has `.sty` extension.
* Also called _style files_.
* Primary objective: To add some functionality, irrespective of the class in which it will be used.
* Example: `geometry` package which is used to specify margins and paper size, `graphicx` package which is used to include an image, etc..

## Class

* Has `.cls` extension.
* Reponsible for the overall layout, structuring(organizing) and formatting of a document.
* Example: a `book` class contains chapters, sections and parts; while an `article` contains sections, subsections.

---
