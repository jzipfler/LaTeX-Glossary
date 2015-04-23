# LaTeX-Glossary
A collection of some glossary and acronym entries for the glossaries LaTeX package

# Usage

Include this after the package **hyperref** to have clickable links.
Include it as following in your TeX document preamble:
```latex
\usepackage[toc]{glossaries}
\makeglossaries
\loadglsentries{content/99_Glossary}
```
* toc:
	Shows up the glossary in your TableOfContent

Use the following settings to print the glossary and set its name and the name of the entry in the toc:
```latex
\printglossary[title=Glossar,toctitle=Glossar]
```

To include the glossaty itself, you need to import the file to you projects TeX file.
This can be done with the *input* command.

```latex
\input{<PATH_TO_GLOSSARY_FILE>}
```
You can clone the git repository to a desired place, and link (or symlink), the file to your project to have it in this scope and up to date through git.

For more information take a look at:
http://en.wikibooks.org/wiki/LaTeX/Glossary

This project is "licensed" under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/).
So feel free to extend it or just inform me about something that could be done better.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>
