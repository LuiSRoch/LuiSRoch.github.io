---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
<html lang="{{ site.lang }}">
---
  
<body>

<a href="#eng" data-reload>English</a>
<a href="#fr" data-reload>Français</a>
  
<select class="selectpicker" data-width="fit">
  <option data-content='<span class="flag-icon flag-icon-us"></span> English'>English</option>
  <option data-content='<span class="flag-icon flag-icon-fr"></span> Français'>Français</option>
</select>

<p id="hi">
  Welcome!
</p>

<script>
  var language={
    eng: {
      welcome: "Welcome!"
  },
    fr: {
      welcome: "Bievenue !"
  }
  };
  
  if (window.location.hash) {
    if (window.location.hash === "#fr") {
      hi.textContent = language.fr.welcome;
  }
  }

</script>

</body>
