# First character larger than the others

* Package: `lettrine`.
* This package provides a facility to typeset the first character in a paragraph in larger font size.
* Syntax:

```tex
\usepackage{lettrine}
\lettrine{Big letter}{Rest of word} ...
```
* Example:
```tex
\lettrine{O}{nce} upon a time, \lipsum[1-2]
```
Here 'O' will be large.

* Example:

```tex
\lettrine{\textbf{O}}{once} upon a time, \lipsum[1-2]
```
Here, 'O' will be bold and large.

* Example:

```tex
\lettrine{\fbox{\textbf{O}}}{} nce upon a time, \lipsum[1-2]
```

---