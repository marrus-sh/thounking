---
---

{% for post in site.posts %}
    - [<small>[<time>{{ post.date | date: "%Y-%m-%d" }}</time>]</small> {{ post.title | default: "Untitled Post" }}]({{ post.url }}){% endfor %}
