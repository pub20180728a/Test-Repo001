# index
## 004
### {{page.path}}
### {{page.url}}

<ul>
  {% for page in site.pages %}
    <li>
      <a href="{{ page.url }}">Go To {{ page.title }}</a>
      {{ post.path }}
    </li>
  {% endfor %}
</ul>


{% include_relative README.md %}
