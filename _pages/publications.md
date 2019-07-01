---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<center><img src="images/Abstracts_wordcloud.png" alt="abstracts_wordcloud"></center>
<br/>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
