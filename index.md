 ---
 By default, content added below the "---" mark will appear in the home page
 between the top bar and the list of recent posts.
 To change the home page layout, edit the _layouts/home.html file.
 See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
<html lang="{{ site.lang }}">
  <body>
    <header>
      <a class="active" href="#">{{ site.languageNames[site.lang] }}</a>
      {% for lang in site.languageNames %}
      {% if lang[0] == site.lang %} {% continue %} {% endif %}
      {% if page.namespace %}
        <a href="{% tl {{ page.namespace }} {{ lang[0] }}%}">{{ lang[1] }}</a>
      {% else %}
        <a href="{{ site.baseurl_root }}/{{ lang[0] }}/">{{ lang[1] }}</a>
      {% endif %}
      {% endfor %}
    </header>
  </body>
</html>
