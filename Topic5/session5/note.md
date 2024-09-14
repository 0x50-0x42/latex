# Creating bibliography

* First we create <em>.bib</em> file.

## Bibliography(.bib) file

* We put other citations in the bib file.

<strong><ins>Example-1</ins>:</strong>
```tex
@inproceedings{KEY,
	title={},
	author={},
	booktitle={},
	pages={X--Y},
	year={},
	organization={}
}
```

<strong><ins>Example-2: citing an article</ins>:</strong>
```tex
@article{KEY,
	title={},
	author={},
	journal={},
	volume={},
	number={},
	pages={X--Y},
	year={},
	publisher={}
}
```

<strong><ins>Example-3: citing a book</ins>:</strong>
```tex
@book{KEY,
	title={},
	author={},
	volume={},
	year={},
	publisher={},
	location={}
}
```

<strong><ins>Example-4: citing a URL</ins>:</strong>
```tex
@misc{KEY,
	title={},
	howpublished="\url{...}",
```

* In all the above examples, the `KEY` is the key that we will use to cite in the document.

## Cite

* After putting in the necessary citations into the bib file, we need to cite them in our document.
* To cite, we use the command `\cite{KEY}`.
* After this, mention the bibliography style and the bib file that we created:
```tex
\bibliographystyle{Style}
\bibliography{filename}
```
where `Style` can be `plain`, `alpha`, `unsrt` or `acm` and the `filename` is the name of the bib file.

* To include reference without citing, use: `\nocite{KEY}`.

* Whenever we change the bibliography style, it's a good practice to clean the auxiliary files which $\LaTeX$ has generated.
* From the menubar in TeXstudio:
	* Click `Tools` $\rightarrow$ `Clean Auxiliary Files`.
* Conference like ACM, IEEE, etc. have their own $\LaTeX$ templates.

* Format of IEEE:
```tex
\documentclass[conference]{IEEEtran}
....
....

\begin{document}

....
....
....

\bibliographystyle{IEEEtran}
\bibliography{filename}

\end{document}
```

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic5/session5/doc1.tex), [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic5/session5/doc2.tex), [biblio.bib](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic5/session5/biblio.bib).

---
