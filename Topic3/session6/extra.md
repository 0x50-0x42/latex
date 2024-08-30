# Extra

* Web-related icons are also supported by $\LaTeX$ via the `fontawesome` package.

I faced some problems while compiling my tex document in TeXstudio, it said `fontawesome.sty` not found.

So I googled and found that it will resolved on running:
```bash
$ sudo apt install texlive-full
```

Now, I encountered a new issue, I got this output:

```bash
....
....
Setting up thunderbird-locale-en (1:52.3.0+build1-0ubuntu0.16.04.1) ...
Setting up thunderbird-locale-en-us (1:52.3.0+build1-0ubuntu0.16.04.1) ...
Setting up context (2015.05.18.20150601-2) ...
Running mtxrun --generate. This may take some time... done.
Pregenerating ConTeXt MarkIV format. This may take some time...

```

And this was taking forever to complete. So I again googled it and was surprised to find that the solution(for me) was as simple as pressing the
RETURN key. [Click here](https://askubuntu.com/questions/956006/pregenerating-context-markiv-format-this-may-take-some-time-takes-forever/1509109#1509109).

After this was resolved, I then opened TeXstudio again and ran the $\LaTeX$ code and it ran!

* [https://www.tug.org/FontCatalogue/](https://www.tug.org/FontCatalogue/), click the type of font that you wish to use, followed by the name of the font. Some more information is displayed i.e. which packages to be included, the command for styling the content, etc.


---
