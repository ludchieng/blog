---
layout: index.liquid
---

{% for post in collections.posts.pages %}
## {{ post.title }}

{{ post.excerpt }}

[Lire l'article]({{ post.permalink }})
{% endfor %}
