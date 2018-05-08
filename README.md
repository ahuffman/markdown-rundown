# Markdown Rundown
This file aims to be a simple example of some of the most common features of markdown syntax to be used when writing repository documentation.  View the source of this file to see the appropriate markdown syntax for each example.

 Some of the examples used in this file are written in "GFM" ([GitHub Flavored Markdown](https://github.github.com/gfm)), because GitHub is one of the most prolific communities of available open-source repositories in the world, and the "GFM" specifications and extensions are becoming more widely accepted and implemented.

## Table of Contents:
1. [History](#history)
2. [Headings](#headings)
3. [Horizontal Rule](#horizontal-rule)
4. [Code Blocks](#code-blocks)
5. [Inline Code/Monospace](#inline-codemonospace)
6. [Emphasis](#emphasis)
7. [Tables](#tables)
8. [Links](#links)
9. [Images](#images)
  	* [Alt/Hover Text](#althover-text)
  	* [No Alt/Hover Text](#no-althover-text)
  	* [Linked Image](#linked-image)
10. [Linebreaks/Paragraphs](#linebreaksparagraphs)
11. [Blockquotes](#blockquotes)
12. [Lists](#lists)
    * [Unordered Lists](#unordered-lists)
    * [Ordered Lists](#ordered-lists)
    * [Ordered Lists with Sub-lists](#ordered-lists-with-sub-lists)
13. [Author](#author)
14. [License](#license)

---

## History
A history of markdown can be found on [wikipedia](https://en.wikipedia.org/wiki/Markdown).

---
## Headings
# H1
## H2
### H3
#### H4
##### H5
###### H6
---
## Horizontal Rule
You will see these used throughout this document.  A horizontal rule is a nice way of dividing up sections of a document.  It is written as 3 or more hyphens most commonly, but can also be asterisks or underscores:
```
---
***
___
```
---
***
___
## Code Blocks
Code blocks with language specific syntax highlighting can be produced:
```yaml
---
- hosts: all
  tasks:
  ...
```
Code blocks can also be written without specific highlighting.  Here's the same example without yaml specified:
```
---
- hosts: all
  tasks:
  ...
```
---
## Inline Code/Monospace
Sometimes you want to point out a `variable` or command such as `ls /` inline.  This can be done by surrounding the text with back ticks `.

---
## Emphasis
|Emphasis|Example|Text Surrounded By|
|:---:|:---:|:---:|
|italic|*italic*|single asterisk|
|bold|**bold**|two asterisks|
|bold-italic|***bold-italic***|three asterisks|
|strike-through|~~strike-through~~|two tildes|
|all|~~***all***~~|two tildes and three asterisks|
---
## Tables
The second line of the table defines how the columns will align in the table.  This special delimiter row uses a combination of colons along with three or more hyphens. Beginning and ending pipe (`|`) characters are not required to create a table.

|Aligned left|Centered|Aligned Right|No alignment|
|:-----------|:------:|------------:|------------|
|to the left|in the middle|to the right|wherever|
---
## Links
Links to can point to a relative path (i.e. path from where this file is) or a fully qualified path/URL.
This is a link to [Ansible Documentation](http://docs.ansible.com), and is a fully qualified path.  
This is a relative link to a [README.md](../README.md).

---
## Images
Images look similar to a link, but can have an alt or hover text.
### Alt/Hover Text
![Ansible](https://avatars1.githubusercontent.com/u/1507452?s=200)
### No Alt/Hover Text
![](https://avatars1.githubusercontent.com/u/1507452?s=200)
### Linked Image
[![Ansible](https://avatars1.githubusercontent.com/u/1507452?s=200)](http://www.ansible.com)

---
## Linebreaks/Paragraphs
### Single new line:
This is line 1, here is some example text. Some markdown implementations require two trailing spaces and a newline to break.  
This is line 2, here is some more example text.
### Two new lines:
This is line 1, here is some example text.

This is line 2, here is some more example text.

---
## Blockquotes
This is normal text.
> This is a blockquote.
> Here is a second line of a blockquote with some more example text.

---
## Lists
### Unordered Lists
These can be created by using either an asterisk, plus, or minus sign. They are interchangeable:
* item1
+ item2
- item3

### Ordered Lists
1. item 1
2. item 2
3. item 3

### Ordered Lists with Sub-lists
1. item 1
2. item 2
3. item 3
    * sub-item 1
    * sub-item 2
    * sub-item 3
4. item 4
5. item 5

---
## Author
[Andrew J. Huffman](mailto:ahuffman@redhat.com)

---
## [License](LICENSE)
