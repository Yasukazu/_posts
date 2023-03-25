---
title: Disqus comment
date: 2023-03-24 18:23:36
tags: comment
categories: Hexo
---
Tried to have a commenting system.
<!-- more -->
## Disqus comment system:
- Changed: `(d.head || d.body)` to `(d.body)`
- Disqus in article(post)
---
<div id="disqus_thread"></div>
<script>
            const page_path = "2023/03/24/disqus-comment/";
            const page_url = "https://blog.yskz.dev/" + page_path ";
            var disqus_config = function ()
            {
                this.page.url = page_url;
                this.page.identifier = '/' + page_path;
            };
            (function ()
            {
                var d = document,
                    s = d.createElement('script');
                s.src = 'https://yasukazu-1.disqus.com/embed.js';
                s.setAttribute('data-timestamp', +new Date());
                (d.body).appendChild(s);
            })();
    noscript.
            - Please enable JavaScript to view the #[a(href="https://disqus.com/?ref_noscript",rel="nofollow") comments powered by Disqus.]
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>