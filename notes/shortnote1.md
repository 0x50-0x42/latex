# Notes

* Display an equation in one line(without any newlines in the equation):
```tex
${<your equation>}$
```
* We will need to put those braces if we want the equation to be in one line.
* `\ldots` displays three dots(`...`) for a sequence.
* Put a backslash before the trignometric function names in math mode.
* `\ln` gives us a natural log in $\LaTeX$ math mode.
* For roots(in math mode):
	* `\sqrt{<radicand>}` &rarr; displays <em>square root of <code>radicand</code></em>.
	* `\sqrt[<index>]{<radicand>}` &rarr; displays <em><code>index</code>-th root of <code>radicand</code></em>.
* Fraction(in math mode):
	* `\frac{<numerator>}{<denominator>}`
* `\displaystyle` is used with inline math mode(where mathematical expressions are written within `$....$`). It displays inline math as if it were displayed in display mode(where mathematical expressions are written within `$$...$$`).
* For getting some more vertical space after a newline(`\\`) use `[<X><unit>]` after `\\` as:

```tex
....
....
....
\begin{document}
	Some text.\\[6pt]
	Some more text here.
\end{document}
....
....
```
* The amount of space by which the first paragraph is indented can be controlled by using `\parindent <X>px` which means <em>indent the paragraph by <code>X</code> points</em>.
* Write this in the preamble which is the section before `\begin{document}`.
