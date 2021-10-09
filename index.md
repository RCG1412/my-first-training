---
title: My Markdown Document
author: John Doe
layout: demo_template
---

{% include sample_for_includes.txt %}

## written by {{page.author}}

# My general practice for Markdown writing

## What is Markdown

Markdown is a very lightweight markup language that lets you create rich text (meaning text that has emphasis, headers, etc) in any plain text editor. Markdown, like HTML, allows you to specify text formatting, but it is far less expressive than HTML, which is perfectly fine since it is only meant to format text and not create full web pages.

## Markdown Syntax (table format)

| Element | Syntax | Example
| ----| ---- | ---- |
| Heading | `#` | # Summer Olympcis |
| Links | `[link text](url)` | Sholay |

## Markdown Syntax (unordered list format)

- For first heading use **Heading 1** element and the syntax will be `#`.
- For images use **images** elemnt and syntax will be `![image alt text] (path to image file)`. 

    ![poster](https://upload.wikimedia.org/wikipedia/en/5/52/Sholay-poster.jpg)
  
## List of Social Networking Websites
 
 1.  Facebook
 1.  Twitter
 1.  Instagram
 1.  Snapchat
 
## Some Codes example 
 
 XML documents must contain one root element that is the parent of all other elements:
 
 ```
 <root>
  <child>
    <subchild>.....</subchild>
  </child>
</root> 
``` 
## Question
_Did you like Markdown_
[] Yes  [] No

