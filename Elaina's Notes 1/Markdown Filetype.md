
Markdown is a widely used lightweight [[Markup Language]] for formatting text using a plain-text editor. This means nearly every text editor can view and edit these files. 

To do this, the formatting is done using [[#Markdown Syntax]], which indicates how words and phrases should look. When opening a markdown file (.md) in a supported program, this syntax is interpreted and displayed as formatting. 

But what if I don't have a such program?
The markdown syntax has been made such that it is incredibly easy to read. If you didn't know better, you could easily assume it was simply a stylistic choice.

"Markdown at it’s core is nothing but a [[JavaScript|javascript]] library" [[#^79e371|Some blog]]

__________________________________________________________________________

Here are a few sites that use markdown:
	-[[GitHub]]
	 -[[Reddit]]
	 -[[Discord]]
	 -[[Stackoverflow]]
	 -[[ChatGPT|ChatGPT's responses]]
	 -Majority of all documentation for open source projects is written in Markdown

## Markdown Syntax:

#### Headings
	# H1
	 ## H2
	 ### H3
	 etc
The more "#" there are in front, the smaller it becomes.
The less "#" there are in front, the more priority it has. ***Anything*** underneath with a lower priority then the heading will be grouped with it, unless separated by something with a higher *or* equal priority.
#### Paragraphs
blah blah; some text

This is a ***paragraph***; it is separated by a blank line (as seen above).
#### Text Formatting
	*italic*
	**bold**
	 ***bold italic***
	 ~~strikethrough~~
*italic*
**bold**
***bold italic***
~~strikethrough~~
#### Lists

##### Ordered Lists
	`01. First Item
	`02. Second Item
	`01. Wrong number, but renders correctly
	`296. some other ordered point
	1. First Item
	2. Second Item
	3. Wrong number, but renders correctly
	4. some other ordered point
	5. 
Notice how it even effects these "tab lists"(?)
Also, clicking enter auto creates next number ^520d5a

[[#^520d5a|Dis]] must actually be part of [[Obsidian]] :P 
##### Unordered Lists
	`Can either use "*", "+" or "-"
	`- First
	`- Second
	`- Third
- First
- Second
- Third
##### Nested lists

Just indent an element
	`01. First
		`09. First but sub
	`00. Second
	`- First
		`- First but sub
	`- Second
1. First
	1. First but sub
2. Second
- First
	- First but sub
- Second
#### Links
*For note-to-note links, check [[Obsidian#Internal Links|Obsidian-Internal Links]]

`[This is a link to Google](https://www.google.com/)`

## Sources:

markdown guide:
https://www.markdownguide.org/getting-started/

some blog:
https://sdgniser.github.io/coding_club_blogs/blogs/2023/12/29/markdown.html ^79e371

wiki:
https://en.wikipedia.org/wiki/Markdown
