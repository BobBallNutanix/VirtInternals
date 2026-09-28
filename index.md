# Welcome to Virt Internals

{% for post in site.posts %}
  {{ post.excerpt }}
  [Read full post]({{ post.url | relative_url }})
{% endfor %}
