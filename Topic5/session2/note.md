# Hyperlinks and Hypertexts

* Hyperlinks/hypertexts are clickable texts/links in a document which point to some other reference that a reader can access by clicking on it.

## Hyperlinks

* Hyperlinks/links are displayed in a document by using the `\url{...}` command.
* We also need to include the `url` package.
* Example:
	* `\url{www.overleaf.com}`
	* Displays `www.overleaf.com` as a clickable text in the document.

## Hypertexts

* Similar to hyperlinks.
* Here, some normal text is displayed instead of actual links and that text is clickable.
* Clicking on that text will take us to the url that we had <em>embedded</em>(if that's the right word) into that text.
* The package `hyperref` needs to be included for using this command.
* Example:

```tex
Click \href{www.overleaf.com}{here} to visit Overleaf.
```
The output will contain a text like this:
```
Click here to visit Overleaf.
```
Where, `here` will be a clickable text and on clicking it we will be redirected to `www.overleaf.com`.

* Usually used when the link is too long or you want to display some other information rather than the link.

<ins>Note</ins>:
The url included using `\url{}` command becomes <em>clickable</em> only when we include the `hyperref` package. Run [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic5/session2/doc1.tex) and find out.

---
