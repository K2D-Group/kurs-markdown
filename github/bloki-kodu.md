Title: 		Bloki kodu i składnia  
Date: 		28-02-2015  
Source:     Codex Project => https://github.com/codexproject/docs/blob/master/writing-reference/github-flavored-markdown.md  
Reviewer:	Krystian Duma  
Private:	True  


### Fenced code blocks
Standard Markdown converts text with four spaces at the beginning of each line into a code blockl; GFM also supports fenced blocks. Just wrap your code in ` ``` ` (three backticks; as shown below) and you won't need to indent it by four spaces.

> **Note** that although fenced code blocks don't have to be preceeded by a blank line -- unlike indented code blocks -- we recommend placing a blank line before them to make the raw Markdown easier to read.

	Here's an example:

	```
	function text() {
		console.log("notice the blank line before this function?");
	}
	```

### Syntax highlighting
Code blocks can be take a step further by adding syntax highlighting. In your fenced block, add an optional language identifier and we'll run it through syntax highlighting. For example, to syntax highlight PHP code:

	```php
	function sayHello()
	{
		echo "Hello World!";
	}

	sayHello();
	```

becomes

```php
function sayHello()
{
	echo "Hello World!";
}

sayHello();
```