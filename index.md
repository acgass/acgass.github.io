---
layout: single
author_profile: true
author: Anna Gass
---

<div>
    {% for post in site.posts %}
      <img src="/assets/images/{{post.image}}.jpg" alt="Smiley face" height="65" width="65">
      <a href="{{ post.url }}">{{ post.title }}</a>
    {% endfor %}
  </div>