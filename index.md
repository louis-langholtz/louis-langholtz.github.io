---
layout: page
---

## Software Projects

Here's a listing of projects with GitHub pages:
- [PlayRho](PlayRho/)

## Articles

- Coming soon.

## Presentations

<ul>
  {% for tag in site.tags %}
    {% if tag[0] == "presentation" %}
      {% for post in tag[1] %}
        <li>
          <a href="{{ post.url }}">{{post.date | date: "%B %-d, %Y"}}: {{ post.title }}</a>
        </li>
      {% endfor %}
    {% endif %}
  {% endfor %}
</ul>
