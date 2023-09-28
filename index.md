Site links:
- [GitHub](https://github.com/louis-langholtz/)
- [StackOverflow](https://stackoverflow.com/users/7410358/louis-langholtz)

Software project websites:
- [PlayRho](PlayRho/)

Articles:
- Coming soon.

All Posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{post.date | date: "%B %-d, %Y"}}: {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
