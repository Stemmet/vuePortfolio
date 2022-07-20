<template>
    <header>CONTACT ME</header>

<form id="form" class="topBefore">
		  <input id="name" type="text" placeholder="NAME">
		  <input id="email" type="text" placeholder="E-MAIL">
		  <textarea id="message" type="text" placeholder="MESSAGE"></textarea>
  <input id="submit" type="submit" value="GO!">
  
</form>
</template>

<script>

</script>

<style>

input::-webkit-input-placeholder, textarea::-webkit-input-placeholder {
  color: #F9AC66;
  font-size: 0.875em;
}

input:focus::-webkit-input-placeholder, textarea:focus::-webkit-input-placeholder {
  color: #F9AC66;
}

input::-moz-placeholder, textarea::-moz-placeholder {
  color: #F9AC66;
  font-size: 0.875em;
}

input:focus::-moz-placeholder, textarea:focus::-moz-placeholder {
  color: #F9AC66;
}

input::placeholder, textarea::placeholder {
  color: #F9AC66;
  font-size: 0.875em;
}

input:focus::placeholder, textarea::focus:placeholder {
  color: #F9AC66;
}

input::-ms-placeholder, textarea::-ms-placeholder {
  color: #F9AC66;
  font-size: 0.875em;
}

input:focus::-ms-placeholder, textarea:focus::-ms-placeholder {
  color: #F9AC66;
}

/* on hover placeholder */

input:hover::-webkit-input-placeholder, textarea:hover::-webkit-input-placeholder {
  color: #165945;
  font-size: 0.875em;
}

input:hover:focus::-webkit-input-placeholder, textarea:hover:focus::-webkit-input-placeholder {
  color: #165945;
}

input:hover::-moz-placeholder, textarea:hover::-moz-placeholder {
  color: #165945;
  font-size: 0.875em;
}

input:hover:focus::-moz-placeholder, textarea:hover:focus::-moz-placeholder {
  color: #165945;
}

input:hover::placeholder, textarea:hover::placeholder {
  color: #165945;
  font-size: 0.875em;
}

input:hover:focus::placeholder, textarea:hover:focus::placeholder {
  color: #165945;
}

input:hover::placeholder, textarea:hover::placeholder {
  color: #165945;
  font-size: 0.875em;
}

input:hover:focus::-ms-placeholder, textarea:hover::focus:-ms-placeholder {
  color: #165945;
}

header {
  position: relative;
  margin: 100px 0 25px 0;
  font-size: 3em;
  text-align: center;
  letter-spacing: 7px;
}

#form {
  position: relative;
  width: 500px;
  margin: 50px auto 100px auto;
  height: 50vh;
  display: grid;
  justify-content: center;
}

input {
  font-size: 0.875em;
  width: 75vh;
  height: 50px;
  padding: 0px 15px 0px 15px;
  
  background: transparent;
  outline: none;
  color: #ED6B5B;
  
  border: solid 2px #F9AC62;
  border-bottom: none;
  
  transition: all 0.3s ease-in-out;
  -webkit-transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  -ms-transition: all 0.3s ease-in-out;
}

input:hover {
  background: #F9AC66;
  color: #165945;
}

textarea {
  width: 75vh;
  max-width: 75vh;
  height: 110px;
  max-height: 110px;
  padding: 15px;
  
  background: transparent;
  outline: none;
  
  color: #ED6B5B;
  font-size: 0.875em;
  
  border: solid 2px #F9AC66;
  
  transition: all 0.3s ease-in-out;
  -webkit-transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  -ms-transition: all 0.3s ease-in-out;
}

textarea:hover {
  background: #F9AC66;
  color: #165945;
}

#submit {
  width: 75vh;
  
  padding: 0;
  margin: -5px 0px 0px 0px;
  
  font-size: 0.875em;
  color: #165945;
  background: #F9AC66;
  
  outline:none;
  cursor: pointer;
  
  border: solid 2px #F9AC66;
  border-top: none;
}

#submit:hover {
  color: #F9AC62;
  background-color: #ED6B5B;
}
</style>