---
title: Set config to add date before title in file name
date: 2023-01-27 21:58:58
tags: new_post_name
---

Set the main confiuration file of Hexo `_config.yml` to include newly created date in its file name.

```yaml
new_post_name: :day-:month-:year-:title.md # File name of new posts
```

Notify:
- This does not affect to create a new draft.
- The configuration file must be the main [ just under Hexo directory ] not in theme configuration directories.