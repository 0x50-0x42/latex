# Page styling

* The `article` class displays the page number in the footer.
* The `book` class places the page number in the footer where the chapter begins and then in the header.
* Customization can be done using the following commands:
	* `\pagestyle{<style>}` $\rightarrow$ for the entire document.
	* `\thispagestyle{<style>}` $\rightarrow$ for the current page.

* Some styles are:
	* `empty` $\rightarrow$ neither header nor footer.
	* `plain` $\rightarrow$ footer contains the page number.
	* `headings` $\rightarrow$ header contains section name and page number.

* `\setcounter{page}{<Number>}` is used to reset the page number.

* Following are the various page numbering styles for `\setcounter{page}{<Number>}`:
	* `Arabic` $\rightarrow$ 1, 2, 3, ...
	* `roman` $\rightarrow$ i, ii, iii, ...
	* `Roman` $\rightarrow$ I, II, III, ...
	* `alph` $\rightarrow$ a, b, c, ...
	* `Alph` $\rightarrow$ A, B, C, ...
	* `\pagenumbering{<style>}` is used to set the page numbering style for the pages(note: one use, works for the whole document).

# Fancy page style

* We can use the `fancyhdr` package to customize a page.
* We have to use `\pagestyle{fancy}` to style the page.

# Setting the header and footer

<table>
<tr>
<td><strong>Align</strong></td>
<td><strong>Header</strong></td>
<td><strong>Footer</strong></td>
</tr>

<tr>
<td>Left</td>
<td><code>\lhead{...}</code></td>
<td><code>\lfoot{...}</code></td>
</tr>

<tr>
<td>Center</td>
<td><code>\chead{...}</code></td>
<td><code>\cfoot{...}</code></td>
</tr>

<tr>
<td>Right</td>
<td><code>\rhead{...}</code></td>
<td><code>\rfoot{...}</code></td>
</tr>

</table>

# Document information

<table>
<tr>
<td><strong>Information</strong></td>
<td><strong>$\LaTeX$ command</strong></td>
</tr>

<tr>
<td>Current page number</td>
<td><code>\thepage</code></td>
</tr>

<tr>
<td>title 'Chapter'</td>
<td><code>\chaptername</code></td>
</tr>

<tr>
<td>Chapter number</td>
<td><code>\thechapter</td>
</tr>

<tr>
<td>Section number</td>
<td><code>thesection</code></td>
</tr>

<tr>
<td>Total number of pages</td>
<td><code>\usepackage{lastpage}</code><br><code>\pageref{LastPage}</code></td>
</tr>

</table>


# Horizontal line after header and footer

* `\renewcommand{\headrulewidth}{Xpt}`.
* `\renewcommand{\footrulewidth}{Xpt}`.
* `X` denotes the width of the line.

---
