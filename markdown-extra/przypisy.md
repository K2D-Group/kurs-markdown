Title: 		Przypisy  
Date: 		28-02-2015  
Source:     michelf.ca => https://michelf.ca/projects/php-markdown/extra/  
Reviewer:	Krystian Duma  
Private:	True  

# Przypisy

Footnotes work mostly like reference-style links. A footnote is made of two things: a marker in the text that will become a superscript number; a footnote definition that will be placed in a list of footnotes at the end of the document. A footnote looks like this:

```
That's some text with a footnote.[^1]

[^1]: And that's the footnote.
```

Footnote definitions can be found anywhere in the document, but footnotes will always be listed in the order they are linked to in the text. Note that you cannot make two links to the same footnotes: if you try, the second footnote reference will be left as plain text.

Each footnote must have a distinct name. That name will be used to link footnote references to footnote definitions, but has no effect on the numbering of the footnotes. Names can contain any character valid within an id attribute in HTML.

Footnotes can contain block-level elements, which means that you can put multiple paragraphs, lists, blockquotes and so on in a footnote. It works the same as for list items: just indent the following paragraphs by four spaces in the footnote definition:

```
That's some text with a footnote.[^1]

[^1]: And that's the footnote.

    That's the second paragraph.
```

If you want things to align better, you can leave the first line of the footnote empty and put your first paragraph just below:

```
[^1]:
    And that's the footnote.

    That's the second paragraph.
```