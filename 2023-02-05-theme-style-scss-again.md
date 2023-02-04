---
title: Theme style SCSS again
date: 2023-02-05 08:46:20
tags:
---
This is _Post Excerpt_: Embedding renderer directive in comment (TURBO_PASCAL-like)
<!-- more -->
Using _Live Sass_, a plugin of VS Code, retried to use SCSS as a style sheet.
```json
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
```