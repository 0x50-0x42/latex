# Section levels

<table>
<tr>
<td><strong>Level number</strong></td>
<td><strong>Command</strong></td>
<td><strong>Available in documentclasses</strong></td>
</tr>

<tr>
<td>$-1$</td>
<td><code>\part{...}</code></td>
<td><code>article</code>, <code>report</code>, <code>book</code></td>
</tr>

<tr>
<td>$0$</td>
<td><code>\chapter{...}</code></td>
<td><code>report</code>, <code>book</code></td>
</tr>

<tr>
<td>$1$</td>
<td><code>\section{...}</code></td>
<td>All documentclasses</td>
</tr>

<tr>
<td>$2$</td>
<td><code>\subsection{...}</code></td>
<td>All documentclasses</td>
</tr>

<tr>
<td>$3$</td>
<td><code>\subsubsection{...}</code></td>
<td>All documentclasses</td>
</tr>

<tr>
<td>$4$</td>
<td><code>\paragraph{...}</code></td>
<td>All documentclasses</td>
</tr>

<tr>
<td>$5$</td>
<td><code>\subparagraph{...}</code></td>
<td>All documentclasses</td>
</tr>

</table>

## Table of contents

The table of contents is created using the command `\tableofcontents` and is placed at the beginning of the document(after the `\maketitle`) command.

**Note:** When using `\tableofcontents`, we need to run the code twice, when the code is run the first time, a `.toc`, when we run the code the second time, it will read the contents from the `.toc` file and it will display it in the output.

## `\section[alias]{...}`

This command can be used when the name of the section is very long, and we don't want it to appear in the table of contents. The `alias` acts as a substitute to this long name and is going to appear in the table of contents instead of that long name.

## Avoid entry in Table of Contents

To avoid an entry of a section or a chapter in the table of contents, we can use `\chapter*{...}` or `\section*{...}` i.e. we basically append a `*` symbol to the commands.

## Special characters

The special characters `!`, `@`, `*`, `(`, `)`, `-`, `+`, `=`, `?`, `[`, `]`, `/` can be written literally in the document.

The following characters need to written with an escape character(`\`), else they will throw error or will display incorrectly. Some of them are `&`, `$`, `%`, `_`, `{`, `}`, `#`.

## Dashes

* Hyphen(-) is used in between two words.
* En dash (`\textendash`) is mostly used when specifying range of pages, years, etc.
* Em dash(`\textemdash`)(longer than En dash) is mostly used in place of parentheses or colon.

## Quotes

* \` in $\LaTeX$ represents the opening of quotes while ' represents the closing of quotes.

---
