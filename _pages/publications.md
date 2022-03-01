---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
I have also previously published under the names *Vedad Kunovac Hodžić* and *Vedad Hodžić*. An up-to-date list of publications on NASA ADS can be found [here](https://tinyurl.com/KunovacADS).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
