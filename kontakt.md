---
layout: page
title: Kontakt
ref: contact
lang: de
order: 8
---

<div class="wrapper">
    
<img class="mon_histoire" src="img/Contact.jpg"/>

<p class="text_center">
    
Möchten Sie mich kontaktieren ?<br>
Füllen Sie dieses Formular aus, es geht schneller als mit einer Brieftaube !

</p>

<form>
    <label for="fname"><h3 class="text_center">Ihr Name</h3></label>
    <input type="text" id="name" name="name" placeholder="Votre nom...">

<label for="name"><h3 class="text_center">Ihre E-mail</h3></label>
<input type="email" id="email" name="email" placeholder="Ihre E-mail...">
    
<label for="message"><h3 class="text_center">Ihre Botschaft</h3></label>
<input type="text" id="message" name="message" placeholder="Ihre Botschaft...">
    
  <div class="container">
    <div class="button_contact" onclick="sendMail()">Senden</div>
</div>
</form>



</div> 





<script src="javascript/javascript.js"></script>
