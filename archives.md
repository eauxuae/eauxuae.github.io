---
layout: default
title: Archives
---

# Archives

Parcourir tous les articles des plus récents vers les plus anciens :

<ul class="archive-list">
  {% for post in site.posts %}
    <li>
        <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%d" }} {% assign m = post.date | date: "%m" %}{% case m %}
          {% when '01' %}jan.
          {% when '02' %}fév.
          {% when '03' %}mars
          {% when '04' %}avr.
          {% when '05' %}mai
          {% when '06' %}juin
          {% when '07' %}juill.
          {% when '08' %}août
          {% when '09' %}sept.
          {% when '10' %}oct.
          {% when '11' %}nov.
          {% when '12' %}déc.{% endcase %} {{ post.date | date: "%Y" }}</time>
          &ndash;
      <a href="{{ site.baseurl }}{{ post.url }}">
        {{ post.title }}
        </a>
    </li>
  {% endfor %}
</ul>