---
title: In-site search Hexo server success
date: 2023-02-14 10:48:46
tags: search
categories: Hexo
---
In-sit search function works only in Hexo server mode.
<!-- more -->
## Misunderstandings:
- HTML **form** tag redirects to `action=` URL, if no `action` property, redirects document root ('/'). Countermeasure is `Event.preventDefault()` in called function.
- HTML **template** tag is made to use from JavaScript.  In js code, usually the template is used after cloning as: `document.importNode(template.content, true)`. *(`true` means recursive clone aka: including all its descendants) In other words, **template** is a pre-defined format strategy of `document.createDocumentFragment()` to insert a new element tree in an HTML document.

## Useful teaching webpage:
<https://catnose.me/learning/html/template>