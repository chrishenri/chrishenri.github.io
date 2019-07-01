---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<center><img src="Abstracts_wordcloud.png" alt="abstracts_wordcloud" width="200"></center>
<center><span style = "font-size:0.7em;">Wordcloud produced from the abstracts of all publications</span></center>
<br/>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
