# Including SVG images

* To include svg images, we use the `svg` package.
* Including an svg image is same as including a png or a jpg image. We do it with the `\includesvg{...}` command.
* Just like `\includegraphics{...}` is written within the `figure` environment, `\includesvg{...}` can also be written within the `figure` environment.
* it's just like `\includegraphics{...}` command.
* **Do install [Inkscape](https://inkscape.org/) before working with the `svg` package because it needs inkscape**.
* This is how you include an SVG image:

```tex
\begin{figure}[H]
	\centering
	\includesvg[width=100mm]{images/parrot}
\end{figure}
```

<p align = "center">
OR
</p>

```tex
\begin{figure}[H]
	\centering
	\includesvg[width=100mm]{images/parrot.svg}
\end{figure}
```

You may/maynot provide the `.svg` extension.

* After this, if you are in TeXstudio, then go `Options` &rarr; `Configure TeXstudio` &rarr; `Commands` and from there Choose the `PdfLaTeX` field and add the option `--shell-escape` option to it.

<img src="https://github.com/0x50-0x42/latex/blob/LaTeX/practicalNote/images/ss3.png" width="50%" height="50%">

Only then it will run.


* Sources: [https://mirror.niser.ac.in/ctan/graphics/svg/doc/svg.pdf](https://mirror.niser.ac.in/ctan/graphics/svg/doc/svg.pdf), [https://tex.stackexchange.com/questions/2099/how-to-include-svg-diagrams-in-latex](https://tex.stackexchange.com/questions/2099/how-to-include-svg-diagrams-in-latex), [https://www.baeldung.com/cs/latex-svg-images](https://www.baeldung.com/cs/latex-svg-images).

---
