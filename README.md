# David's homepage

This page is the main entry of my personal projects. ALL of these projects are just proofs of concept or notes that I feel sharing.

## Blog
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
