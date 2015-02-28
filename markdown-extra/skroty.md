Title: 		Skróty
Date: 		28 Luty 2015
Source:     https://michelf.ca/projects/php-markdown/extra/

# Skróty

Markdown Extra adds supports for abbreviations (HTML tag <abbr>). How it works is pretty simple: create an abbreviation definition like this:

```
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
```

then, elsewhere in the document, write text such as:

```
The HTML specification
is maintained by the W3C.
```

and any instance of those words in the text will become:

```
The <abbr title="Hyper Text Markup Language">HTML</abbr> specification
is maintained by the <abbr title="World Wide Web Consortium">W3C</abbr>.
```

Abbreviations are case-sensitive, and will span on multiple words when defined as such.An abbreviation may also have an empty definition, in which case <abbr> tags will be added in the text but the title attribute will be omitted.

```
Operation Tigra Genesis is going well.

*[Tigra Genesis]:
```

Abbreviation definitions can be anywhere in the document. They are stripped from the final document.

