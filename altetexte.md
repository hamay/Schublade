---
layout: default
---

<div id="main">		

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}<strong>{{ post.date | date: "%B %e, %Y" }}</strong></a>
    </li>
  {% endfor %}
</ul>
		
</div>