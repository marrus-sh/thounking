{% for post in site.posts %}
- [{{ post.title | default: "Untitled Post" }} <small>[<time>{{ post.date | date: "%Y-%m-%d" }}</time>]</small>]({{ post.url }}){% endfor %}
