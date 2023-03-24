---
title: Disqus comment
date: 2023-03-24 18:23:36
tags: comment
categories: Hexo
---
Tried to have a commenting system.
<!-- more -->
## Disqus comment system:

```JavaScript
<div id="disqus_thread"></div>
<script>
    const disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    (function() {
    const d = document, s = d.createElement('script');
    s.src = 'https://yasukazu-1.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
```