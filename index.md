{% for post in site.posts %}
- [{{ post.title | default: post.slug | default: "Untitled Post" }} <small>[<time>{{ post.date | date: "%Y-%m-%d" }}</time>]</small>]({{ post.url | relative_url }}){% endfor %}
