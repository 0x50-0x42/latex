# Equation arrays
* Environment: `align`.
* Package: `mathtools`.
* We can write multiple equations here. We end one line of an equation with a `\\`.
* Example:
```tex
\begin{align}
	5x^2-9=x+3\\
	5x^2-x-12=0
\end{align}
```
The equals `=` won't be aligned in this example. To align the equals of the equations, we will place a `&` before each `=`.
* Example:
```tex
\begin{align}
	5^x2-9&=x+3\\
	5x^2-x-12&=0
\end{align}
```
* For equations that have nothing on the left of the `=`, we just do this:
```tex
\begin{align}
	5^x2-9&=x+3\\
	5x^2-x-12&=0\\
	&=12+x-5x^2
\end{align}
```
All the `=` will be lined up. Also, the equations are numbered by default. To remove the numbering of the equations, we use the `align*` environment.

* Example:
```tex
\begin{align*}
	5x^2-9&=x+3\\
	5x^2-x-12&=0\\
	&=12+x-5x^2
\end{align*}
```

---
