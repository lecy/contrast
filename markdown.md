---
title:  "Markdown Guide"
---

Markdown is a set of simple conventions for formatting text on GitHub. It makes it easy to create professional documents with minimal effort. You need only follow a few simple rules.

## Formatting Text

```
With Markdown, it is possible to emphasize words by making them *italicized*, using *astericks* or _underscores_, or making them **bold**, using **double astericks** or __double underscores__. Of course, you can combine those two formats, with both _**bold and italicized**_ text, using any combination of the above syntax. You can also add a strikethrough to text using a ~~double tilde~~.
```

With Markdown, it is possible to emphasize words by making them *italicized*, using *astericks* or _underscores_, or making them **bold**, using **double astericks** or __double underscores__. Of course, you can combine those two formats, with both _**bold and italicized**_ text, using any combination of the above syntax. You can also add a strikethrough to text using a ~~double tilde~~.

You can create [inline links](https://github.com) by wrapping link text in square brackets [ ], and then wrapping the URL in parentheses ( ). 

```
[link text](https://link_url.com)
```
You can insert images with an exclamation mark in front of square brackets ![ ], and then wrapping the image file name in parentheses ( ). 

```
![](image_file.png)
```

It is common practice to place all of the image files in an "assets" or "images" folder to keep your directory tidy. You can reference files inside a folder using the folder name and the forward slash:

```
![](assets/flower.jpg)
```

![](assets/flower.jpg)

---


## Formatting Headers

```
# Heading One (h1)

## Heading Two (h2)

### Heading Three (h3)

#### Heading Four (h4)

##### Heading Five (h5)

###### Heading Six (h6)
```
# Heading One (h1)

## Heading Two (h2)

### Heading Three (h3)

#### Heading Four (h4)

##### Heading Five (h5)

###### Heading Six (h6)

---



## Formatting Blockquotes

### Single line

```
> My mom always said life was like a box of chocolates. You never know what you're gonna get.
```
> My mom always said life was like a box of chocolates. You never know what you're gonna get.

### Multiline

```
> What do you get when you cross an insomniac, an unwilling agnostic and a dyslexic?
>
> You get someone who stays up all night torturing himself mentally over the question of whether or not there's a dog.
>
> – _Hal Incandenza_
```

> What do you get when you cross an insomniac, an unwilling agnostic and a dyslexic?
>
> You get someone who stays up all night torturing himself mentally over the question of whether or not there's a dog.
>
> – _Hal Incandenza_

## Horizontal Rule

```
---
```

---


## Tables

```
| Title 1          | Title 2          | Title 3         | Title 4         |
|------------------|------------------|-----------------|-----------------|
| First entry      | Second entry     | Third entry     | Fourth entry    |
| Fifth entry      | Sixth entry      | Seventh entry   | Eight entry     |
| Ninth entry      | Tenth entry      | Eleventh entry  | Twelfth entry   |
| Thirteenth entry | Fourteenth entry | Fifteenth entry | Sixteenth entry |

```

| Title 1          | Title 2          | Title 3         | Title 4         |
|------------------|------------------|-----------------|-----------------|
| First entry      | Second entry     | Third entry     | Fourth entry    |
| Fifth entry      | Sixth entry      | Seventh entry   | Eight entry     |
| Ninth entry      | Tenth entry      | Eleventh entry  | Twelfth entry   |
| Thirteenth entry | Fourteenth entry | Fifteenth entry | Sixteenth entry |


---


## Lists

### Unordered

```
* First item
* Second item
* Third item
    * First nested item
    * Second nested item
```
* First item
* Second item
* Third item
    * First nested item
    * Second nested item

### Ordered

```
1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item
```
1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item
