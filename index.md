---
layout: home
ref: index
lang: en
---
<div class="home">
  <ul class="post-list">
    {% assign posts=site.posts | where:"lang", page.lang %}
  </ul>
</div>
