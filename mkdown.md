# Markdown
What is Markdown?

**Markdown** is a markup language developed by [**John Gruber**](https://daringfireball.net) in collaboration with [**Aaron Swartz**](http://www.aaronsw.com) in 2004.

We quote the definition of Markdown provided by [John Gruber](https://daringfireball.net/projects/markdown/):

> Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).
> 
> Thus, “Markdown” is two things: (1) a plain text formatting syntax; and (2) a software tool, written in Perl, that converts the plain text formatting to HTML. See the [Syntax](https://daringfireball.net/projects/markdown/syntax) page for details pertaining to Markdown’s formatting syntax. You can try it out, right now, using the online [Dingus](https://daringfireball.net/projects/markdown/dingus).

The advantage of Markdown is to write in plain text without worrying about formatting and therefore without distractions since with markup, and you can enrich your text at any time.

We propose publishing the main Markdown commands on this page (continuously updated).

***

The Markdown logo ([**The Markdown Mark**](https://github.com/dcurtis/markdown-mark)) ![md](/images/markdown/mdlogo32x20.png#center) has been designed and realized by [Dustin Curtis](https://twitter.com/dcurtis) ([https://dustincurtis.com](https://dustincurtis.com/)) with the contribution of Mac Tyler ([http://mactyler.com](http://mactyler.com/)).

***

## CommonMark
The [CommonMark](https://commonmark.org) project arose because the description of Markdown syntax created by [John Gruber](https://daringfireball.net) is not uniquely specified.

There is a lack of a unique specification of Markdown. That has resulted in different implementations over the years, such that not all editors can reproduce the language uniquely.

For these reasons, **John MacFarlane** (the developer of Pandoc), **Martin Woodward** and **Jeff Atwood** - who call themselves a group of Markdown fans - have decided to create the [**CommonMark**](https://commonmark.org) project aimed at defining a single Markdown syntax.

We quote what is on the CommonMark website:

> There’s no standard test suite for Markdown; [**MDTest**](https://github.com/michelf/mdtest/) is the closest thing we have. The only way to resolve Markdown ambiguities and inconsistencies is [**Babelmark**](https://johnmacfarlane.net/babelmark2/), which compares the output of 20+ implementations of Markdown against each other to see if a consensus emerges.
> 
> We propose **a standard, unambiguous syntax specification for Markdown**, along with a **suite of comprehensive tests** to validate Markdown implementations against this specification. We believe this is necessary, even essential, for the future of Markdown.

The project is genuinely worthy for those who consider Markdown a relevant resource.

We hope developers, especially those dealing with Markdown editor developments, can refer to the CommonMark specifications to have a unique Markdown syntax.

***

## Mermaid

For **Mermaid** see [this post](https://notes.nicfab.eu/en/posts/mermaid/).

***

## Markdown Syntax

***

### Header H1:

```
# Header H1
```
or
```
Header H1
=========
```

### Header H2:

```
## Header H2
```
or
```
Header H1
---------
```

### Header H3:

```
### Header H3
```

### Header H4:

```
#### Header H4
```

### Bold
```
**bold**
```
or
```
__bold__
```

### Italic
```
*Italic**
```
or
```
_Italic_
```

### Strikethrough
```
~~strikethrough~~
```

### Highlight
```
==highlight==
```

### Superscript
```
N^4^
```
or
```
N<sup>4</sup>
```

### Subscript
```
H~2~O
```
or
```
H<sub>2</sub>O
```


### Link
```
[link](https://domain.com)
```
or
```
[link][1]

[1]: (https://domain.com)
```
or
```
<https://domain.com>
```
if you want to add an attribute
```
[link](https://domain.com "Write here for an attribute")
```

### Mailto
```
<name@domain.com>
```

### Images
```
![text](https://domain.com/immage.jpg)
```
or
```
[text][1]

[1]: (https://domain.com/immage.jpg)
```
or (centered)
```
![text](https://domain.com/immage.jpg#center)
```
or (with a description)
```
![text](https://domain.com/immage.jpg "Description")
```

### Blockquotes
```
> quote
```
or nested
```
>> nested quote
```

### Unordered list
```
* Point
* Point
* Point
```
or
```
- Point
- Point
- Point
```
or
```
+ Point
+ Point
+ Point
```

### Ordered list
```
1. First
2. Second
3. Third
```
or
```
1) First
2) Second
3) Third
```
or
```
1. First 
1. Second
1. Third
```

### To-do list 
```
- [x] to do 01
- [ ] to do 02
- [ ] to do 03
```

### Horizontal rule
```
*** (three consecutive asterisks)
```
or
```
--- (three consecutive dashes)
```
or
```
___ (three consecutive underscores)
```

### Inline code
```
`inline code`
```
or
```
	code block (indented of four spaces)
```

### Fenced Code Block
<pre><code>
```
code block

ABC

ABC

```
</pre></code>

or

<pre><code>
~~~

code block

ABC

ABC

~~~
</pre></code>

or (indented of four spaces)

<pre><code>
	abc
	abc
	abc

</pre></code>

or

<pre><code>
```python

print(f"2+2 = {2+2}")

```
</pre></code>

### Tables
```
| Column1  | Column2  | Column3  |
| -------- | -------- | -------- |
| One      | Two      | Three    |
| Four     | Five     | Six      |
```

### Footnote
```
Text where to put the footnote identifier[^1]
[^1]: footnote text
```
or
```
Text where to put the footnote label[^label]
[^label]: footnote text
```


---

This page is a *work-in-progress* and therefore, the page may be subject to updates.


***Stay tuned!***

***

{{< chat markdown >}}

