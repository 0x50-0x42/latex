# Alternating page numbers in article class.

To add alternate page numbering in the `article` class, we use the `twoside` option with the `article` class like so:

```tex
\documentclass[twoside]{article}
```

I found the solution from [here](https://www.reddit.com/r/LaTeX/comments/10m0a04/implementing_alternating_headers/). We can also use `twoside` option with the `fancyhdr` package but that's something I have kept for later. For now, just using the `twoside` option with the `artcle` class works just fine.

# New problem

After using `twoside` with the `article` class, I encountered this problem:

<img src="https://github.com/0x50-0x42/latex/blob/LaTeX/practicalNote/images/ss1.png" width="50%" height="50%">

Now, as mentiond in the [comment](https://www.reddit.com/r/LaTeX/comments/10m0a04/comment/j61glz3/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) of the above aforementioned link, I downloaded the most recent version of `fancyhdr.sty` and placed in the folder where I was writing the document and then used the `twoside` option with `fancyhdr` and this solved my issue:

<img src="https://github.com/0x50-0x42/latex/blob/LaTeX/practicalNote/images/ss2.png" width="50%" height="50%">

---
