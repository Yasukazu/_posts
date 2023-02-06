---
title: Theme style SCSS again
date: 2023-02-05 08:46:20
tags: theme.css
---
This is _Post Excerpt_: Embedding renderer directive in comment (TURBO_PASCAL-like)
<!-- more -->
Using _Live Sass_, a plugin of VS Code, retried to use SCSS as a style sheet.
<details>
    <summary>settings.json</summary> 
<code>
    "liveSassCompile.settings.formats": [
        {
            "format": "expanded",
            "extensionName": ".css",
            "savePath": "~/css"
        },
        {
            "extensionName": ".min.css",
            "format": "compressed",
            "savePath": "~/min.css"
        }
    ],
    "liveSassCompile.settings.excludeList": [
        "/**/node_modules/**",
        "/.vscode/**"
    ],
    "liveSassCompile.settings.generateMap": false,
    //autoprefix, will auto add perfix like -webkit- -moz-..
    "liveSassCompile.settings.autoprefix": [
        "> 1%",
        "last 2 versions"
    ]
</code>
</details>

## _post_link_ tag plugin requires post filename contains no date

{% post_link added-archives-in-menu %}

```njk
{% post_link added-archives-in-menu %}
```