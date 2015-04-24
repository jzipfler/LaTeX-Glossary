# LaTeX-Glossary
A collection of some glossary and acronym entries for the glossaries LaTeX package

# Usage

Include this after the package **hyperref** to have clickable links.
Include it as following in your TeX document preamble:
```latex
\usepackage[toc]{glossaries}
\makeglossaries
\loadglsentries{<PATH_TO_GLOSSARY_FILE>}
```
* toc:
	Shows up the glossary in your TableOfContent

To include/print the glossaty itself, you need to call the *printglossary* command.
You can specify the heading (defined as *title*) of the glossary and its name in the talbe of content (defined as *toctitle*).
```latex
\printglossary[title=<NAME_OF_GLOSSAR_AS_HEADING>,toctitle=<NAME_OF_GLOSSAR_IN_TOC>]
```

You can clone the git repository to a desired place, and link (or symlink), the file to your project to have it in this scope and up to date through git.

For more information take a look at:
http://en.wikibooks.org/wiki/LaTeX/Glossary

This project is "licensed" under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/), since it is not really a software project.
So feel free to extend it or just inform me about something that could be done better.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>
