---
layout: default
title: Publications
---

{% include navigation.html %}

## Services

<ul>
{% for service in site.data.services %}
  <li>
      {{ service.type }}. {{ service.event }}
  </li>
{% endfor %}
</ul>


## Selected Publications

<ul>
{% for publication in site.data.publications %}
    <li>
      <a href="{{ publication.link }}"> {{ publication.name }} </a>. {{ publication.authors }}. {{ publication.venue }}.
    </li>
{% endfor %}
</ul>


