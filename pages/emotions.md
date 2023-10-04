---
title: About
layout: page
permalink: /emotions.html
---
<ul>
{% for e in site.emotions%}
<li><a href="{{ e.url | relative_url}}">{{e.title}}</a></li>{% endfor %}
</ul>

<p>{% for e in site.emotions%}
{{e.title}},{{ e.url | relative_url}},Emotions<br>{% endfor %}</p>