---
layout: post
title: "How to write posts with markdown language?"
date: "2022-11-18"
categories: markdown language
---

1. this list will be replaced by the table of contents
{:toc}


## To write headings...

There are 6 levels.

~~~md
# Heading level 1
## Heading level 2
### Heading level 3
#### Heading level 4
##### Heading level 5
###### Heading level 6
~~~
# This is level 1.
{:.no_toc}
and
###### This is level 6.
{:.no_toc}


## To write *italic*...

~~~md
*italic*
_italic_
~~~

## To write **bold **...

~~~md
**bold**
__bold__
~~~

## To write ~~strikethrough~~...

~~~md
~~strikethrough~~
~~~

## To write <u>underscore</u>...

~~~md
<u>underscore</u>
~~~

## To link a site address...

~~~md
[link](https://www.naver.com)
~~~

## To use quotation...

> quote
>> quote

~~~md
> quote
>> quote
~~~


## To list...
1. ordered list1
2. ordered list2

- unodered list1
* unodered list2

~~~md
1. ordered list1
2. ordered list2

- unodered list1
* unodered list2
~~~

## To write some code blocks...

e.g. python code
~~~md
```python
print()#python code
```
~~~
or 
```md
~~~python
print()#python code
~~~
```