---
layout: default
---

<div id="main">
		<h1>Schublade</h1>
		<h2>Texte von Peter Rumpf</h2>
		
<section class="post--content">
  <p class="post--date">{{ page.date | date_to_string }}</p>

  <h1>{{ page.title }}</h1>
  <p>{{ page.introduction }}</p>

  {{ content }}
</section>
</div>