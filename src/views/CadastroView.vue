<template>
    <div class="container">
      <div class="title">
        <h1>Cadastro de Clientes</h1>
        <p>Registre-se agora para ter acesso exclusivo a produtos frescos e deliciosos da nossa padaria.</p>
      </div>
      <div class="title">
        <h1>Cadastro de Contato</h1>
        <p>Preencha o formulário abaixo para se cadastrar e receber novidades da padaria.</p>
      </div>
      <div class="form">
        <div class="form-group">
          <label for="name">Nome do Cliente:</label>
          <input type="text" id="name" placeholder="Digite seu nome aqui">
        </div>
        <div class="form-group">
          <label for="email">E-mail:</label>
          <input type="email" id="email" placeholder="Digite seu e-mail aqui">
        </div>
        <div class="form-group">
          <label for="message">Mensagem:</label>
          <textarea id="message" placeholder="Digite sua mensagem aqui"></textarea>
        </div>
        <button class="btn">Enviar Mensagem</button>
      </div>
      <div class="image">
        <img src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" alt="Padaria">
      </div>
    </div>
  </template>
  
  <style>
  .container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
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
    border: 1px solid #ccc;
    border-radius: 5px;
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
    background-color: #4CAF50;
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
  </style>