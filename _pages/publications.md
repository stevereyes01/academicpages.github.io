---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
 See [CV](https://stevereyes01.github.io/cv/) for links in the section **"Publications in which I made a significant contribution"**
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
