---
layout: single
entries_layout: grid
classes: wide
author_profile: true
author: Anna Gass
---

<div>
    {% for post in site.posts %}
    <ul>
      <a href="{{ post.url }}"><img src="/assets/images/{{post.image}}.jpg" alt="Smiley face" height="150" width="150"></a>
      {{ post.title }}
    </ul>
    {% endfor %}
</div>