---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
title: Techie Joe's Neo theme
layout: home
---
<div class="_flex my-2">
  <div class="_flex-main">
    <h1 id="_hero-title">{{ site.title }}</h1>
  </div>
  {% include topmenu.html %}
</div>
---
{% include demo.md %}