---
layout: home
ref: index
lang: en
---
<div class="home">
  <ul class="post-list">
    {% assign posts=site.posts | where:"lang", page.lang %}
    {% for post in posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>
</div>
