---
layout: default
---
### blog.dgs3.fish
The intersection of history, technology, cooking, etc.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <h4>{{ post.subtitle }}</h4>
      <div id="content">{{ post.excerpt }}</div>
      <a href="{{ post.url }}" class="button">Read more</a>
    </li>
  {% endfor %}
</ul>
