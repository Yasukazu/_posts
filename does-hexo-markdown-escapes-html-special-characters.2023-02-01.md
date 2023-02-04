---
title: Does Hexo markdown escapes HTML special characters?
date: 2023-02-01 10:46:35
tags:
 - Markdown
 - Entity
 - HTML
---

In Hexo, A markdown-format post is converted to HTML format.

HTML documents need to escape special two characters:
- _Less-than_(\<) 
- _Greater-than_(\>)

respectively:
```
\&lt;
\&gt;
```

Markdown is easier than HTML about this escaping.

Just put an _escape_ character **backslash** before special characters as:
```
 \<
 \>
```

But Markdown also needs to escape **Backslash** (\\) as:

`\\`

or write its entity as:

`&bsol;`

HTML-Entity backslash appears as: &bsol;

And also, **Ampersand** (&) might be better to be escaped as:

`\&`

or write its entity as: `&amp;`

HTML-Entity ampersand appears as: &amp;