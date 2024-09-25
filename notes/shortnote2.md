# More maths

* `\left` and `\right` typset dynamically typed delimiters. The delimiters are `( )`, `[ ]`, `|`, `\|`, `\{ \}`, `\langle \rangle` or the dot `.`.
	* `\langle` and `\rangle` are basically `<` and `>` in math-mode.
	* In place of `\{ \}` we can also write `\lbrace` and `\rbrace`.
	* `.` is used as a <em>blank delimiter</em>.
* `\mathbb{<variable>}` writes `<variable>` in <em>blackboard boldface style</em>. Requires the `amssymb` package.
* A set of real numbers:
```tex
$\mathbb{R}$
```
* If there is a `\left` then there has to be a `\right`.
	* The delimiters that they are used with may vary, for example, in this expression: `2\left(\frac{\sin\theta}{\cos\theta}\right\rbrace`, we can see that the delimiters that `\left` and `\right` are used with aren't the same, but <em>if there is a `\left` then there must be a `\right`.

---
