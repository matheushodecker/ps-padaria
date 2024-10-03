<script setup>

</script>

<template>
<div class="container">
    <div class="title">
      <h1>login
      </h1>
     
    </div>
    <section class="formulario">
      <div class="form">
        <div class="form-group">
          <label for="email">E-mail:</label>
          <input type="email" id="email" placeholder="Digite seu e-mail aqui" />
        </div>
        <div class="form-group">
          <label for="senha">senha:</label>
          <input type="senha" id="senha" placeholder="Digite seu e-mail aqui" />
        </div>
        <button class="btn"><a href="/home">entrar</a></button>
        <a href="/cadastro">ainda nao tem conta</a>
      </div>
    </section>
  </div>

</template>

<style>
a{
  color: black;
}
.formulario {
  display: grid;
  grid-template-columns: 1fr, 1fr;
  background-color: #F3EBDA;
  border-radius: 5%;
}

.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  font-family: 'Arial', sans-serif;
}

.title {
  text-align: center;
  margin-bottom: 20px;
}

.form {
  display: flex;
  flex-direction: column;
  width: 300px;
  padding: 20px;


  
}

.form-group {
  margin-bottom: 10px;
}

.form-group label {
  display: block;
  margin-bottom: 5px;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-sizing: border-box;
}

.btn {
  background-color: #4caf50;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.image {
  width: 500px;
  height: 300px;
  margin-top: 20px;
}

.image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.header {
  text-align: center;
  margin-bottom: 20px;
}

.content {
  display: flex;
  justify-content: space-between;
  width: 80%;
}

.card {
  background-color: #fff;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  width: 48%;
}

.card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.card-body {
  padding: 20px;
}

.card-body h2 {
  margin-top: 0;
}

.card-body p {
  line-height: 1.5;
}
</style>
