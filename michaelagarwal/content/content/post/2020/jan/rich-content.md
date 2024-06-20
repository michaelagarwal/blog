---
title: Rich Content Via Hugo
date: 2024-02-06
tags: ["hugo","shortcodes"]
image : "/img/posts/img-5.jpg"
Description  : 'Hugo ships with several Built-in Shortcodes for rich content, along with a Privacy Config and a set of Simple Shortcodes that enable.'
featured: true
---

Hugo ships with several [Built-in Shortcodes](https://gohugo.io/content-management/shortcodes/#use-hugos-built-in-shortcodes) for rich content, along with a Privacy Config and a set of Simple Shortcodes that enable static and no-JS versions of various social media embeds.

&nbsp;
## YouTube privacy enhanced shortcode

The youtube shortcode embeds a responsive video player for YouTube videos. Only the ID of the video is required, e.g.:

*YouTube URL:*
```
https://www.youtube.com/watch?v=3qHkcs3kG44
```

Shortcode:
```
{{</* youtube 3qHkcs3kG44 */>}}
```
Rendered output:
{{< youtube 3qHkcs3kG44 >}}

**Headings**

To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level three (h3), use three number signs (e.g., ### My Header).
&nbsp;
# Heading level 1 	
## Heading level 2 	
### Heading level 3 
#### Heading level 4 
##### Heading level 5 
###### Heading level 6 	

**Paragraphs**

To create paragraphs, use a blank line to separate one or more lines of text.

Markdown

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

**Bold**

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

**Italic**

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

Italicized text is the *cat's meow*.

**Images**

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title after the URL in the parentheses.

![This place was so cool](/img/posts/img-12.jpg "Just an Image")

[To view more about basic syntaxs, click here.](https://www.markdownguide.org/basic-syntax/)
<!--Photo by Dimitri Houtteman on Unsplash-->
