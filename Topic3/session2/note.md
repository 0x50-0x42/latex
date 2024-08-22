# Coloring text and pages of document

* Basic colors:
	* red
	* blue
	* green
	* white
	* yellow, etc
* To use colors, include the package: `color`.
* There are more colors apart from the basic colors.
* To use those additional colors, use the package: `xcolor` with the parameter `dvipsnames`.

## Coloring the text

* For single color:
	* `\textcolor{blue}{Text to be colored}`
* For mixing a color with white, say red, use:
	* `\textcolor{red!70}{Text to be colored}`, results into a mixture of 70\% of red and 30\% of white.
* For mixing two colors, say red with blue, use:
	* `\textcolor{red!70!blue}{Text to be colored}`, results into a mixture of red and blue.

## Coloring the page

* For coloring a whole page, use:
	* `\pagecolor{yellow}`, colors the whole page in yellow.
* All the colors and the color combinations that were used `\textcolor{}{}` can also be used with `\pagecolor{}`.

---
