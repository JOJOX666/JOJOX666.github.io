---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

# News

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b><br/>
{{ article.headline | markdownify }}<br/><br/>
{% endfor %}
</div>
