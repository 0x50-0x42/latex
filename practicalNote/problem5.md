# Alternating page numbers in article class.

To add alternate page numbering in the `article` class, we use the `twoside` option with the `article` class like so:

```tex
\documentclass[twoside]{article}
```

I found the solution fro [here](https://www.reddit.com/r/LaTeX/comments/10m0a04/implementing_alternating_headers/). We can also use `twoside` option with the `fancyhdr` package but that's something I have kept for later. For now, just using the `twoside` option with the `artcle` class works just fine.

---
