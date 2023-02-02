---
title: Does Hexo markdown escapes HTML special characters?
date: 2023-02-01 10:46:35
tags:
 - Markdown
 - Entity
 - HTML
---

In Hexo, A markdown-format post is converted to HTML format.

HTML documents need to escape special two characters: _Less-than_(\<) and _Greater-than_(\>) as:
```HTML
&lt; &gt;
```

Markdown is easier than HTML about this escaping.

Just put an _escape_ character **backslash** before special characters as.
```
 \<  &lt; 
 \>  &gt;
```

But Markdown also needs to escape the _escape_ character itself as:
```
\\  &bsol;
```
