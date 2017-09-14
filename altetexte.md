---
layout: default
---

<div id="main">

    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong></p>			
	

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
		
</div>