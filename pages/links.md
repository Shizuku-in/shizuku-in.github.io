---
layout: mypost
title: リンク
---

みんなは１人のために、１人はみんなのために

```
名称：{{ site.title }}
説明：{{ site.description }}
URL：{{ site.domainUrl }}{{ site.baseurl }}
アバター ：{{ site.domainUrl }}{{ site.baseurl }}/static/img/logo.jpg
```

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
