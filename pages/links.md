---
layout: mypost
title: Links
---

You are welcomed to add friend links here，just send me an email. My information is below:

```
title: {{ site.title }}
description：{{ site.description }}
url：{{ site.domainUrl }}{{ site.baseurl }}
logo：{{ site.domainUrl }}{{ site.baseurl }}/static/img/logo.png
```

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
