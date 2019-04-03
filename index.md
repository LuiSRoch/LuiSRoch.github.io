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
 <! Doctype html> 
<body>

<a href="#eng" data-reload>English</a>
<a href="#fr" data-reload>Français</a>

<p id="hi">
  Welcome!
</p>

<script>
  # Define language reload-anchros
  var datareload =  document.querySelectorAll("[data-reload]");
  # Language translations
  var language={
    eng: {
      welcome: "Welcome!"
  },
    fr: {
      welcome: "Bievenue !"
  }
  };
  
  # Define language via window hash
  if (window.location.hash) {
    if (window.location.hash === "#fr") {
      hi.textContent = language.fr.welcome;
  }
  }

  # define language reload onclick iliteration
  
  for (i = 0; i <= datareload.length; i++){
    datareload[i].onclick = function(){
      location.reload(true);
    };
  }
  
</script>

</body>

</html>
