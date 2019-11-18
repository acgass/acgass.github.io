---
feature_image: "images/welcome.jpg"
feature_text: |
                # Side Project Number One
                Learning new technologies, One side project at a time
layout: page
---

#### Most recent Posts

<ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>