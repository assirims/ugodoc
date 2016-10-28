# Tests

This page is temporary. It tests possibilities with a markdown document.

## Content

[TOC]

## List

- 'Apprenez à programmer en Python'
- "Automate the Boring Stuff with Python"

## Symbols

- << >>
- ...
- short dash: -
- mid dash: --
- long dash: ---

## Code

```python
def aaa():
	print("a")
```

## Font

Enter superscript:
2^10^ is 1024.

pip install MarkdownSuperscript

Enter subscript:
The molecular composition of water is H~2~O.

pip install MarkdownSubscript

## Embed videos

[!embed](http://www.youtube.com/watch?v=9bZkp7q19f0)

pip install pyembed-markdown

## Build a table

|    |    |
|---|---|
|a  |b  |
|c  |d  |

Draw a line:

-----

Without outside borders:

First Header | Second Header | Third Header
------------ | ------------- | ------------
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell

-----

With outside borders:

| First Header | Second Header | Third Header |
| ------------ | ------------- | ------------ |
| Content Cell | Content Cell  | Content Cell |
| Content Cell | Content Cell  | Content Cell |

-----

Aligned:

First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right

-----