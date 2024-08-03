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

## `\section[alias]{...}`

This command can be used when the name of the section is very long, and we don't want it to appear in the table of contents. The `alias` acts as a substitute to this long name and is going to appear in the table of contents instead of that long name.

---
