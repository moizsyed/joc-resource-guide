---
layout: data
permalink: /
---

<h1 class="accent-color fw7 lh-solid">{{ site.title }}</h1>
<p class="mt3 mb4 f1-l f2 lh-solid mw7 fw5">{{ site.description }}</p>

<div class="mt3">
{% for item in site.data.navigation.pages %}
<div class="dib mb3 f2 fw7 br-pill bw2 pa3 ba br2 b--accent-color bg-big-btn">
<a class="" href="{{ item.url }}">{{ item.title }}</a>
</div>
{% endfor %}
</div>
