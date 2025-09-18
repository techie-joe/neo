---
title: Pages
description: Pages on this site.
---

# {{ page.title }}

> {{ page.description }}

{% for p in site.pages %}{% if p.title and p.title != page.title %}- [{{ p.title }}]({{ site.github.url }}{{ p.url }})
{% endif %}{% endfor %}

&nbsp;  
&nbsp;  

---

{% include back.html %}
<a title="Go to Home Page" class="_bt -l -flat" href="{{ site.github.url }}">Go to Home Page</a>