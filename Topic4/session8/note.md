# Working with image borders

## Image border

* `\fbox{\includegraphics{...}}`
* Example:
	* `\fbox{\includegraphics{computer.png}}`
	* This command will display the image `computer.png` within borders.
* To adjust image border thickness, use `\setlength{\fboxrule}{<X>pt}`.
* `X` is the number that represents the thickness of the border.
* Example:
	* `\setlength{\fboxrule}{2pt}`
* To adjust the spacing between the border and the image, we use `\setlength{\fboxsep}{<X>pt}`.
* `X` is the number that represents the space between the border and the image.
* Example:
	* `\setlength{\fboxsep}{15pt}`

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic4/session8/doc1.tex).

---
