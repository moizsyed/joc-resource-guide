---
layout: data
permalink: /
---

<h1 class="accent-color fw7">{{ site.title }}</h1>
<h2 class="mt3 f1-l f2 lh-solid mw7 fw5">{{ site.description }}</h2>

<div class="mt4 flex flex-row-l flex-column">
{% for item in site.data.navigation.pages %}
<a class="f3 w-20-l mr3 mb3 pa3 br1 bg-accent-color bg-big-btn" href="{{ item.url }}">{{ item.title }}</a>
{% endfor %}
</div>
