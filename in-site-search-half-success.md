---
title: In-site search half success
date: 2023-02-11 01:22:15
tags:
categories:
---
It only works when input as `URL/search/?search=...`
<!-- more -->
Search box picks up all entries..
```JavaScript
function getSearchQueryFromUrlParams () {
  const params = window.location.search.substring(1).split('&');
  const search = params.filter(param => param.search(/$search=/));
  return search.length > 0 ? search[0].split('=')[1] : null;
}
```
<var>getSearchQueryFromUrlParams</var> returns `null` from search input text window.