---
layout: home
---

<ul>
    {% for post in site.posts %}
        <li> 
            <h3><a href="{{ post.url }}"> {{ post.title }} </a></h3>
            <p> {{ page.date | date_to_string }} </p>
            <p>{{ post.excerpt }}</p>
        </li>
    {% endfor %}
</ul>