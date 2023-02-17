---
title: Enabled post_asset_folder for _config.yml
date: 2023-02-17 07:39:40
tags:
categories:
---
If `post_asset_folder` is true,  the same name directory of the created post file name without extension.
<!-- more -->
In post document, the asset folder and file can get with:
```njk
{% asset_path filename %}
```