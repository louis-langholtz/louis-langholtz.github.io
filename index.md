Site links:
- [GitHub](https://github.com/louis-langholtz/)
- [StackOverflow](https://stackoverflow.com/users/7410358/louis-langholtz)

Software project websites:
- [PlayRho](PlayRho/)

Articles:
- Coming soon.

Blog:
- See [posts](_posts).

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
