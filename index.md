---
layout: page
---

Here's a listing of some Open Source repositories of mine:
- [PlayRho](PlayRho/)
- [pyspellcode](https://github.com/louis-langholtz/pyspellcode)
- [flow](https://github.com/louis-langholtz/flow)

And some more recent presentations:
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
