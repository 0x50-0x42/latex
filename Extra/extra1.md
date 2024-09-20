# Including PDF

* $\LaTeX$ provides a facility to include some or all pages of a `.pdf` file into your document.

## Package needed
* `pdfpages` which is used as:

```tex
\usepackage[final|draft]{pdfpages}
```

## Insert all pages
* Syntax:
	- `\includepdf[pages=-]{Filename.pdf}`

## Insert certain pages
* Page numbers should be separated by a comma. The following command inserts page1, page 3, a blank page, and pages 5 to 8 from the `file.pdf` file:
	- `\includepdf[pages={1, 3, {}, {5-18}}]{file.pdf}`
	
## Page style
* Syntax:
	- `\includepdf[pages=-, pagecommand={\thispagestyle{...}}]{file.pdf}`