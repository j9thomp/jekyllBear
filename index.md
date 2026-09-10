---
layout: default
title: what!?
---

**what is a null modem adapter?** *it’s a simple connector used to establish a communication link between two devices - direct, unrefined, and strictly point-to-point.*

i plan to use this as a personal space to connect with thoughts related to all aspects of my life - from frivolous hobbies to personal reflection to complex professional activities. beware: you might also find the occasional nonsensical dispatch when i wander off into places unknown…sometimes communication can be a little messy!

to the one person on the planet who finds this blog: *enjoy.*

<hr style="margin: 3em 0; border: 0; border-top: 1px dashed var(--border-color);" />

{% for post in site.posts limit:10 %}
  <article style="margin-bottom: 3em;">
    <h2 style="margin-bottom: 0.2em;">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h2>
    
    <div class="post-content">
      {{ post.content }}
    </div>
  </article>
{% endfor %}