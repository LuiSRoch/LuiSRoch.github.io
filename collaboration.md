---
layout: page
title: Contact Me
subtitle: Collaborate with me on data analysis for finance, supply chain or real estate
permalink: /collaboration/
---
<html lang="en">

  <body>

    <div class="site">
      <header class="site-header">

<!-- site-header -->
   <div class="page-content">

    I work with data science to provide analytics and visualizations on real estate, financial industry, 
    and supply chain. I'm interested in combining data mining, statistics and visualizations using a combination
    of tools; from Python & SQL to Scala to Tableau to plotly-dash.
	<br />

   </div>

<!--
<h2> Customers </h2>

<div class="projects">
  <div class="grid no-gutters">

    <div class="unit half">
      <div class="project">
        <h4 class="project-title"><a href="https://www.certace.com/" target="_blank">certace</a></h4>
        <p><img src="/assets/img/certace.png" width='800'></p>
      </div>
    </div>

    <div class="unit half">
      <div class="project">
        <h4 class="project-title"><a href="http://alphacruncher.com/" target='_blank'>alphacruncher</a></h4>
        <p><img src="/assets/img/alphacruncher.svg" width='800'></p>
      </div>
    </div>

  </div>
</div>
-->

<h4> Contact </h4>

If you are interested in sharing ideas and working together, please fill out the form and I'll get back to you right away!
<br/>
<html>
<head>
<style> 
textarea {
  width: 80%;
  height: 90px;
  padding: 6px 12px;
  box-sizing: border-box;
  border: 1px solid #ccc;
  border-radius: 1px;
  background-color: #f8f8f8;
  font-size: 12px;
  resize: none;
}
</style>
</head>
</html>

<br/>
    <div id='formview'>
      <form action="https://formspree.io/gugolwifi@gmail.com" method="POST" class="cform">
        <input type="email" name="email" placeholder="Your email address">
        <br/>
        <textarea type="message" placeholder="Your Message"></textarea>
          <input type="hidden" name="_subject" value="request">
          <input type="text" name="_gotcha" style="display:none">
          <button type="submit">Send</button>
      </form>
    </div>

<br />

div.elem-group {
  margin: 40px 0;
}

label {
  display: block;
  font-family: 'Aleo';
  padding-bottom: 4px;
  font-size: 1.25em;
}

input, select, textarea {
  border-radius: 2px;
  border: 1px solid #ccc;
  box-sizing: border-box;
  font-size: 1.25em;
  font-family: 'Aleo';
  width: 500px;
  padding: 8px;
}

textarea {
  height: 250px;
}

button {
  height: 50px;
  background: green;
  color: white;
  border: 2px solid darkgreen;
  font-size: 1.25em;
  font-family: 'Aleo';
  border-radius: 4px;
  cursor: pointer;
}

button:hover {
  border: 2px solid black;
}

<form action="contact.php" method="post">
  <div class="elem-group">
    <label for="email">Your E-mail</label>
    <input type="email" id="email" name="visitor_email" placeholder="You@something.com" required>
  </div>
  <div class="elem-group">
    <label for="message">Tell me about your project</label>
    <textarea id="message" name="visitor_message" placeholder="Your Message Here." required></textarea>
  </div>
  <button type="submit">Send Message</button>
</form>
