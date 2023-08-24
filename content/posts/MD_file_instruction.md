+++
title = "How to write a .md file"
date = "2023-05-21T18:29:25+08:00"
author = "potter"
baseURL = ''
authorTwitter = "_bjpotter"
cover = ""
tags = ["tutorial", "spotlight"]
keywords = ["tutorial", "content"]
description = "none"
showFullContent = true
readingTime = true
hideComments = true
color = "" #color from the theme settings
+++

# Heading 1

## Heading 2

### Heading 3

### and so on...

If you want to comment content, please wrap your comments into `<!-- "your comments" -->`

<!-- this is a comment, which will not show up in the final output -->

This is a **bold text**.

This is an *italic text*.

This ***text*** is both **bold** and *italic*.

You can create an **unordered list** like this:

* Item 1
* Item 2
  * Item 2.1
  * item 2.2
    * Item 2.2.1
    * ...

For **ordered** list:

1. Item 1
2. Item 2
   1. Item 2.1
   2. Item 2.2
      1. Item 2.2.1
      2. ...

Click [here](/) to go home. This is the way to our [personal website department](/personal-website). Inside `[]` is the text with hyperlink that links to somewhere in our website. The URL of that page can be accessed in `.toml` file, and the URL is wrapped inside `()`.

You can copy and paste emoji from this [GitHub repository](https://gist.github.com/rxaviers/7360908) 😊.

You can put your codes like this:

An `inline code` locates in a single line.

```python
# This is a code block

printf("Hello the world")
```

```java
// This is also a block of code, and you can specify the language you use after ``` to highlight it.

System.out.println("Hello the world");
```

> This is a blockquote.

***

Use `***`, `---`, or `___` to create a horizontal line.

___

Use `![Image Title](URL)` to include an image online.

![UBC Forestry Centre](https://victoria.mediaplanet.com/app/uploads/sites/114/2022/09/UBC-Forestry-Header-888x500.jpg)
 
 
 
Here you can link a youtube video via shortcode:
 
 
 
{{< youtube id="w7Ft2ymGmfc" autoplay="true" >}} 
 
 
 
For more information of shortcode, click [here](https://gohugo.io/content-management/shortcodes/#use-hugos-built-in-shortcodes).