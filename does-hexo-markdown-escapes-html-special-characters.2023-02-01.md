---
title: Does Hexo markdown escapes HTML special characters?
date: 2023-02-01 10:46:35
tags:
 - Markdown
 - Entity
 - HTML
---

In Hexo, A markdown-format post is converted to HTML.
HTML document needs to escape special characters like 'Less than', 'Greater than' and 'Apostropy' as:
'&lt;', '&gt;','&apos; / &#x27;', '&rarr;'.

## Result of entities:
- &lt; and &gt; must escape manually markdown writer himself / herself.
- Other HTML entities like aportrophe(&apos;) are no need to escape. 

### Escaping special characters 'L.T.'(&lt;), 'G.T.'(&gt;) and 'back-slash'(<pre lang='en'>\\</pre>)

 Three special characters:
 [ _less-than_ , _greater-than_ , _back-slash_ ]
[\<, \>, \\]

 need a **backslash** is inserted in front of each of them like:
[\\<, \\>, \\\\]

 not to be treated as embedding HTML tags and an **escape** character.