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
Cliquez sur le bouton c’est plus rapide que par pigeon voyageur !

</p>

<form>
    <label for="fname">Votre nom</label>
    <input type="text" id="name" name="name" placeholder="Votre nom...">

<label for="name">Votre email</label>
<input type="email" id="email" name="email" placeholder="Votre email...">
    
<label for="message">Votre message</label>
<input type="text" id="message" name="message" placeholder="Votre message...">
    
  <div class="container">
    <div class="button_contact" onclick="sendMail()">Envoyer</div>
</div>
</form>



</div> 

<style type="text/css">    
    
input[name="name"], select {
  width: 100%;
  padding: 12px 20px;
  margin: 0 0 5% 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[name="message"], select {
  width: 100%;
  padding: 50px 20px;
  margin: 0 0 5% 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=email], select {
  width: 100%;
  padding: 12px 20px;
  margin: 0 0 5% 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}


.button_contact{
    margin:auto;
    padding: 10px 20px;
    color: #f2e0c8;
    border:5px outset grey;
    background-color: #40565c;
    display: inline-block;
    text-align: center;
    cursor: pointer;
}


.button_contact:hover{
color: #f2e0c8;
background-color:#bd8c51;
border:5px outset orange;
}

</style>



<script type="text/javascript">
function sendMail() {
    var name = $('#name').val();
    var email = $('#email').val();
    var message = $('#message').val();
    window.location.href = 'mailto:golombek.vincent@gmail.com?subject=The subject - ' + name + ' (' + email + ')' + '&body=' + message;
    location.reload();
};
</script>