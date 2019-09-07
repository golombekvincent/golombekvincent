---
layout: page
title: Contact
ref: contact
lang: fr
order: 4
---

<div class="wrapper">
    
<img class="mon_histoire" src="img/Contact.jpg"/>

<p class="text_center">
    
Vous souhaitez me contacter ?<br>
Remplissez ce formulaire, c’est plus rapide que par pigeon voyageur !

</p>

<form>
    <label><h3 class="text_center">Votre nom</h3></label>
    <input type="text" id="name" name="name" placeholder="Votre nom...">

<label><h3 class="text_center">Votre email</h3></label>
<input type="email" id="email" name="email" placeholder="Votre email...">
    
<label><h3 class="text_center">Votre message</h3></label>
<textarea rows="5" id="message" name="message" placeholder="Votre message..."></textarea>
    
  <div class="container">
    <div class="button_contact" onclick="sendMail()">Envoyer</div>
</div>
</form>



</div> 





<script src="javascript/javascript.js"></script>