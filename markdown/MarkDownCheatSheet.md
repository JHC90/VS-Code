
# 1. Table of Contents
[Erklärung wie man TOC einfügt in VSCode](https://marketplace.visualstudio.com/items?itemName=AlanWalk.markdown-toc)

ggf ein workaround in vscode => gehe in die Einstellungen von VS-Code(geh aufs zahnrad links unten :-) ), dort unter User-Settings und filtere die [eol](https://github.com/AlanWalk/markdown-toc/issues/65) heraus. Dort ändert man die default eol (end of line) in "\n\r" (standardmäßig ist auto ausgeählt). Danach klappt die Table Insection problemlos

<!-- TOC -->

- [1. Table of Contents](#1-table-of-contents)
- [2. Titles](#2-titles)
- [3. Emphasis](#3-emphasis)
- [4. Horizontal Rule](#4-horizontal-rule)
- [5. Formulas-Basics](#5-formulas-basics)
- [6. Media](#6-media)
  - [6.1. Bilder](#61-bilder)
  - [6.2. webp.Anomation](#62-webpanomation)
  - [6.3. Gif-Animatino](#63-gif-animatino)
  - [6.4. Youtube-Video](#64-youtube-video)
- [7. Links](#7-links)
- [8. Tables](#8-tables)

<!-- /TOC -->



# 2. Titles
> \# Title
> \## Subtitle
> \### second Subtitle
> \#### ...


# 3. Emphasis
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

> Coding section

Inline `code` has `back-ticks around` it.

```python
s = "Python syntax highlighting"
print(s)
```

# 4. Horizontal Rule


---
***
___

# 5. Formulas-Basics
* für die Formeln brauch ich die umschließenden "\$\$"
  $$1+1$$
* Summenzeichen 

Sum $\sum_{n=1}^{\infty} 2^{-n} = 1$ inside text	

# 6. Media
## 6.1. Bilder
![bild](./imgs/MarkdownPasterConfigPicture.PNG)
## 6.2. webp.Anomation
![webp.Anomation](./imgs/test.webp)
## 6.3. Gif-Animatino
![webp.Anomation](./imgs/DemoGif.gif)
## 6.4. Youtube-Video
[![Everything Is AWESOME](https://img.youtube.com/vi/StTqXEQ2l-Y/0.jpg)](https://www.youtube.com/watch?v=StTqXEQ2l-Y "Everything Is AWESOME")

# 7. Links
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title- Beim hovern kommt eine Bezeichnung](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text] // checke hier in diesem kapitel "Links" im Raw-Format, dann kann man die Referenzen erkennen.

[I'm a relative reference to a repository file](../CheatSheet.md)


[You can use numbers for reference-style link definitions][1]// checke hier in diesem kapitel "Links" im Raw-Format, dann kann man die Referenzen erkennen.

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

# 8. Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3