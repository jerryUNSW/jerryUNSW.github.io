---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

{% if site.author.googlescholar %}
  <small>Also available on <a href="{{site.author.googlescholar}}">Google Scholar</a>.</small>
{% endif %}
