---
layout: page
permalink: /podcasts/
feature_text: |
                # Podcasts
---

I spent several years living alone. I loved it, except when the apartment got quiet, so I started listening to podcasts. Now that I live with people again, I don't get much of a chance to listen to podcasts unless I am coding or driving. Since its not safe to blog while driving, I'll blog about the podcasts I'm listening to while coding. I hope you find some some shows you enjoy.

#### Most recent recommendations


<ul>
    {% for post in site.posts %}
        {% if post.categories contains "podcasts" %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        {% endif %}
    {% endfor %}
  </ul>