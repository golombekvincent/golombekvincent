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
    <label for="fname"><h3 class="text_center">Votre nom</h3></label>
    <input type="text" id="name" name="name" placeholder="Votre nom...">

<label for="name"><h3 class="text_center">Votre email</h3></label>
<input type="email" id="email" name="email" placeholder="Votre email...">
    
<label for="message"><h3 class="text_center">Votre message</h3></label>
<input type="text" id="message" name="message" placeholder="Votre message...">
    
  <div class="container">
    <div class="button_contact" onclick="sendMail()">Envoyer</div>
</div>
</form>



</div> 





<script src="javascript/javascript.js"></script>