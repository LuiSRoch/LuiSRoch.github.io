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

<html>
  <head>
    <style>
      
      <?php
      if($_POST) {
    $visitor_name = "";
    $visitor_email = "";
    $email_title = "";
    $visitor_message = "";
     
    if(isset($_POST['visitor_name'])) {
        $visitor_name = filter_var($_POST['visitor_name'], FILTER_SANITIZE_STRING);
    }
     
    if(isset($_POST['visitor_email'])) {
        $visitor_email = str_replace(array("\r", "\n", "%0a", "%0d"), '', $_POST['visitor_email']);
        $visitor_email = filter_var($visitor_email, FILTER_VALIDATE_EMAIL);
    }
     
    if(isset($_POST['email_title'])) {
        $email_title = filter_var($_POST['email_title'], FILTER_SANITIZE_STRING);
    }
     
    if(isset($_POST['concerned_department'])) {
        $concerned_department = filter_var($_POST['concerned_department'], FILTER_SANITIZE_STRING);
    }
     
    if(isset($_POST['visitor_message'])) {
        $visitor_message = htmlspecialchars($_POST['visitor_message']);
    }
    
    else {
        $recipient = "gugolwifi@gmail.com";
    }
     
    $headers  = 'MIME-Version: 1.0' . "\r\n"
    .'Content-type: text/html; charset=utf-8' . "\r\n"
    .'From: ' . $visitor_email . "\r\n";
     
    if(mail($recipient, $email_title, $visitor_message, $headers)) {
        echo "<p>Thank you for contacting us, $visitor_name. You will get a reply within 24 hours.</p>";
    } else {
        echo '<p>We are sorry but the email did not go through.</p>';
    }
    } else {
    echo '<p>Something went wrong</p>';
    }
    ?>
      
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
    </style>
    </head>
    </html>


<form action="contact.php" method="post">
  <div class="elem-group">
    <label for="name">Your Name</label>
    <input type="text" id="name" name="visitor_name" placeholder="Enter your name" required>
  </div>
  <div class="elem-group">
    <label for="email">Your Email</label>
    <input type="email" id="email" name="visitor_email" placeholder="you@email.com" required>
  </div>
  <div class="elem-group">
    <label for="title">Subject</label>
    <input type="text" id="title" name="email_title" required placeholder="Idea for a project, help...?" required>
  </div>
  <div class="elem-group">
    <label for="message">Write a brief overview</label>
    <textarea id="message" name="visitor_message" placeholder="Your Message" required></textarea>
  </div>
  <button type="submit">Send Message</button>
</form>
