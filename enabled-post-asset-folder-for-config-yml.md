---
title: Enabled post_asset_folder for _config.yml
date: 2023-02-17 07:39:40
tags: [embed, post]
categories: Hexo
---
If `post_asset_folder` is true,  the same name directory of the created post file name without extension.
<!-- more -->
In post document, the asset folder and file can get with:
```njk
{% asset_path filename %}
```

## How to link to another post

- Use _post_link_ tag plugin

```njk
{% post_link _filename-without-extension_ _title_ [escape escape: true(default)/false] %}
```

{% post_link ignore-diacritical-marks-in-search "How to embed images in a post" %}