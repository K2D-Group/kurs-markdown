Title: 		Ogrodzone Bloki Kodu  
Date: 		28 Luty 2015  
Source:     https://michelf.ca/projects/php-markdown/extra/ - Michel Fortin  
Reviewer:	Krystian Duma  

# Ogrodzone Bloki Kodu

Markdown Extra introduced a syntax code block without indentation. Fenced code blocks are like Markdown’s regular code blocks, except that they’re not indented and instead rely on start and end fence lines to delimit the code block. The code block starts with a line containing three or more tilde ~ characters, and ends with the first line with the same number of tilde ~. For instance:

This is a paragraph introducing:

```
~~~~~~~~~~~~~~~~~~~~~
a one-line code block
~~~~~~~~~~~~~~~~~~~~~
```

You can also use backticks \` characters intead of tilde:

```
``````````````````
another code block
``````````````````
```

Contrary to their indented counterparts, fenced code blocks can begin and end with blank lines:

```
~~~

blank line before
blank line after

~~~
```

Indented code blocks cannot be used immediately following a list because the list indent takes precedence; fenced code block have no such limitation:

```
1.  List item

    Not an indented code block, but a second paragraph
    in the list item

~~~~
This is a code block, fenced-style
~~~~
```

Fenced code blocks are also ideal if you need to paste some code in an editor which doesn’t have a command for increasing the indent of a block of text, such as a text box in your web browser.

You can specify a class name that will apply to a code block. This is useful if you want to style differently code blocks depending on the language. Or you could also use it to tell a syntax highlighter what syntax to use.

```
~~~~~~~~~~~~~~~~~~~~~~~~~~~~ .html
<p>paragraph <b>emphasis</b>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

The class name is placed at the end of the first fence. It can be preceded by a dot, but this is not a requirement. You can also use a special attribute block:

```
~~~~~~~~~~~~~~~~~~~~~~~~~~~~ {.html #example-1}
<p>paragraph <b>emphasis</b>
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
```

In the HTML output, code block attributes will be applied on the code element; if you want to see them on the pre element instead, set the configuration variable code_attr_on_pre on the parser to true. See the configuration reference for more details.