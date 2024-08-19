# Formatting text

Here are some font styles in $\LaTeX$:

<table>
<tr>
<td><strong>Command</strong></td>
<td><strong>Output</strong></td>
</tr>

<tr>
<td><code>\textbf{ ... }</code></td>
<td><strong>Text</strong></td>
</tr>

<tr>
<td><code>\textit{ ... }</code></td>
<td><i>Text</i></td>
</tr>

<tr>
<td><code>\emph{ ... }</code></td>
<td><em>Text</em></td>
</tr>

<tr>
<td><code>\underline{ ... }</code></td>
<td><u>Text</u></td>
</tr>

<tr>
<td><code>\textsc{ ... }</code></td>
<td><p><span style="font-variant: small-caps;">TEXT</span><p></td>
</tr>

<tr>
<td><code>\textrm{ ... }</code></td>
<td><p><span style="font-family: 'Times New Roman', Times, serif;">Text</span></p></td>
</tr>

<tr>
<td><code>\textsf{ ... }</code></td>
<td><p><span style="font-family: Arial, Helvetica, sans-serif;">Text</span></p></td>
</tr>

<tr>
<td><code>\texttt{ ... }</code></td>
<td><pre>Text</pre></td>
</tr>

<tr>
<td><code>\textsuperscript{ ... }</code></td>
<td>Text<sup>text</sup></td>
</tr>

<tr>
<td><code>\textsubscript{ ... }</code></td>
<td>Text<sub>text</sub></td>
</tr>

</table>

For outputs of commands from `\textsc{ ... }` to `\textsubscript{ ... }`, see [doc1.pdf](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session1/doc1.pdf) and for the commands, see [doc1.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session1/doc1.tex).

# Font size

Here are the various font sizes:

<table>
<tr>
<td><strong>Command</strong></td>
<td><strong>Description</strong></td>
</tr>

<tr>
<td><code>\tiny</code></td>
<td>The smallest font</td>
</tr>

<tr>
<td><code>\scriptsize</code></td>
<td>Font size for scripts</td>
</tr>

<tr>
<td><code>\footnotesize</code></td>
<td>Footnote font size</td>
</tr>

<tr>
<td><code>\small</code></td>
<td>Small font size</td>
</tr>

<tr>
<td><code>\normalsize</code></td>
<td>The default font size</td>
</tr>

<tr>
<td><code>\large</code></td>
<td>Large font size</td>
</tr>

<tr>
<td><code>\Large</code></td>
<td>Large font size</td>
</tr>

<tr>
<td><code>\LARGE</code></td>
<td>Large font size</td>
</tr>

<tr>
<td><code>\huge</code></td>
<td>Huge font size</td>
</tr>

<tr>
<td><code>\Huge</code></td>
<td>The largest font size</td>
</tr>
</table>

To look at the output of the above commands, see [doc2.pdf](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session1/doc2.pdf), and for the code, see [doc2.tex](https://github.com/0x50-0x42/latex/blob/LaTeX/Topic3/session1/doc2.tex).

There is something very important missing from `doc2.tex`.

* When we use any of these commands(for font size) before any text(or word), it not only affects the target sentence/word, but also affects the sentences following the target sentence/word. So, if we want it to only affect the target sentence/word, then we must enclose the command and the target sentence/word within `{` and `}` as:

```tex
{\Large word} statement(s) following word, these won't be affect by the command because it and the target word are enclosed within the curly braces.
```
* We can also use `\normalsize` after the target word/sentence to restore the following statements back to their normal size(this is if we aren't using the curly braces around the command and the target word/sentence).

See `doc1.tex` for the code and `doc1.pdf` for the output.

---
