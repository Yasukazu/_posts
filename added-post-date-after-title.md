---
title: Added post date after title
date: 2023-01-28 13:40:59
tags: 
      - config
      - CSS
      - Layout
      - hgroup
      - date.format
---

Under `ym-start/layout/index.pug`,
 block content > main > article.post > a 

Added an **hgroup** tag which contains:

 - `h2.title= post.title`
 - `time.date= post.date.format(config.date_format)`

And also, edited the stylesheet of `ym-start/sources/css/theme.css` to make title and date inline as:
```CSS
hgroup.title-date > h2.title {
    display: inline;
}
```