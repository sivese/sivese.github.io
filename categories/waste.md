# Waste of Money

부정을 저지른 기사가 참회의 수행길을 떠나듯, 저의 수년간의 돈낭비를 참회하고자 합니다. 여기는 제 참회록의 모음집입니다.

## Arduino & Raspberry Pi Bundle

{% for post in site.posts %}
    <li> 
        <h3><a href="{{ post.url }}"> {{ post.title }} </a></h3>
        <p> {{ page.date | date_to_string }} </p>
        <p>{{ post.excerpt }}</p>
    </li>
    {{ post.category }}
    {{ post.categories }}
    {{ post }}
    {% if post.category == "Waste" %}
    <li> 
        <h3><a href="{{ post.url }}"> {{ post.title }} </a></h3>
        <p> {{ page.date | date_to_string }} </p>
        <p>{{ post.excerpt }}</p>
    </li>
    {% endif %}
{% endfor %}