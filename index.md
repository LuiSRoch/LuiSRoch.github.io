---
layout: home
ref: index
lang: en
---
<div class="home">
  <ul class="post-list">  
    {% assign posts=site.posts | where:"lang", page.lang %}
    <li>
      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
    </li>
  </ul>
</div>
