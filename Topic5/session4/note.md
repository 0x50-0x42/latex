# Creating indexes

* An index contains a list of words and the page numbers on which they appear in the book.
* Used to refer using page number.
* Package required: `imakeidx`.
* The `\makeindex` command should follow `\usepackage{imakeidx}`.
* After this, we start marking the words to be displayed in the index. For this we use the `\index{word-to-be-marked}` command.
* The `\printindex` command will display the index.
* To add a subentry, use:
```tex
\index{Parent KEY!KEY}
```
* To cross-reference a key, use:
```tex
\index{KEY|see{Other KEY}}
```

* Once the index starts growing, we must display it in two or multiple columns.
* `\makeindex[columns=X]`
	* The `columns` argument in the `\makeindex` command gives the facility of mentioning the number of columns.
	* `X` denotes a number.
* To set a custom title, use `\makeindex[title=title name]`.
* The `intoc` argument in the command `\makeindex[intoc]`, will display the index title and its page number in the table of contents.

See: [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic5/session4/doc1.tex).

---
