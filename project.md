---
layout: page
permalink: /project/
---

<div class="posts">
    {% for post in site.posts %}
      <article class="post">
        <h1><a>{{ post.title }}</a></h1>
        <div class="entry">
          {{ post.excerpt }}
        </div>
      </article>
    {% endfor %}
</div><br>