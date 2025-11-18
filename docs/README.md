# Geoffrey Liddell

This is Geoffrey Liddell's GitHub Pages website. [Here is a link to the homepage!](./)

The contact me page is [here](./contact)


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
