---
layout: data
permalink: /
---

<h1 class="accent-color fw7 lh-solid">{{ site.title }}</h1>
<p class="mt3 mb4 f1-l f2 lh-solid mw7 fw5">{{ site.description }}</p>

<div class="mt3 flex flex-row-l flex-column">
{% for item in site.data.navigation.pages %}
<a class="f3 mr3 mb3 ph3 pv2 br-pill bg-accent-color bg-big-btn fw7 b--accent-color bw2 ba" href="{{ item.url }}">{{ item.title }}</a>
{% endfor %}
</div>
