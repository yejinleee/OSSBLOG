---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home_custom
---

<ul>
    {% for post in site.posts %}
    <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <!-- <p> {{post.content}} </p>  -->
    {{post.excerpt}}
    </li>
    {% endfor %}
</ul>

{% assign title = "home" %}
{% if title == "home" %}
    This is the homepage
{% elsif title == "about" %}
    <h1>This is the about page</h1>
{% else %}
    <h1>Welcome!</h1>
{% endif %}

{% assign products = "Kiwi,Tui,Kea,Karariki,Weka" | split: "," %}
<ul>
{% for item in products %}
<li>{{ item }}</li>
{% endfor %}
</ul>