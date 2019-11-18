---
layout: page
permalink: /projects/
feature_text: |
                # projects
---

The whole point of this site: my side projects. there isn't much to say outside of what I said on the <a href="../about/"> about page </a>. I'll link the corresponding github repos to the project posts if you want to go check out my code and leave suggests. I'll need as much advice as I can get as I learn these new languages and frame works.

#### Project Posts

<ul>
    {% for post in site.posts %}
        {% if post.categories contains "projects" %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        {% endif %}
    {% endfor %}
  </ul>