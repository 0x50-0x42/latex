# Customize themes

* `\setbeamercolor{structure}{fg=<color>}` is used to change the color of the theme.
* Use `dvipsnames` with the `\documentclass` command as:

```tex
\documentclass[dvipsnames]{beamer}
....
....
```

## Components of a slide

### The title:

<img src="https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session5/theTitle.png" width="40%" height="40%">

* `\setbeamercolor{title}{bg=<color>, fg=<color>}

* To set the color of the frame/slide titles, we use:
	* `\setbeamercolor{frametitle}{bg=<color>, fg=<color>}`
* To set the background color of all the slides/frames to a particular color, use:
```tex
\setbeamercolor{background canvas}{bg=<color>}
```

---

### The footer

* We can change the colors of the footer.

#### Palette tertiary

<img src="https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session5/paletteTertiary.png" width="40%" height="40%">

* `\setbeamercolor{palette tertiary}{bg=<color>, fg=<color>}`

---

#### Palette secondary

<img src="https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session5/paletteSecondary.png" width="40%" height="40%">

* `\setbeamercolor{palette secondary}{bg=<color>, fg=<color>}`

---

#### Palette primary

<img src="https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session5/palettePrimary.png" width="40%" height="40%">

* `\setbeamercolor{palette primary}{bg=<color>, fg=<color>}`

---

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic6/session5/doc1.tex).

---

