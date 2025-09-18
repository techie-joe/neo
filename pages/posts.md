---
title: Posts
description: Posts on this site.
permalink: posts
---

# {{ page.title }}

> {{ page.description }}

{% for p in site.posts %}{% if p.title %}- [{{ p.title }}]({{ site.github.url }}{{ p.url }})
{% else %}- [(Untitled post)]({{ site.github.url }}{{ p.url }})
{% endif %}{% endfor %}

&nbsp;  
&nbsp;  

---

{% include back.html %}
<a title="Go to Home Page" class="_bt -l -flat" href="{{ site.github.url }}">Go to Home Page</a>