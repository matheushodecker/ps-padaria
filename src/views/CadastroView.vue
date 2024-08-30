<script setup>

</script>

<template>
<div class="container">
    <div class="title">
      <h1>Cadastro de Clientes</h1>
      <p>
        Registre-se agora para ter acesso exclusivo a produtos frescos e deliciosos da nossa
        padaria.
      </p>
    </div>
    <div class="title">
      <h1>Cadastro de Contato</h1>
      <p>Preencha o formulário abaixo para se cadastrar e receber novidades da padaria.</p>
    </div>
    <section class="formulario">
      <div class="form">
        <div class="form-group">
          <label for="name">Nome do Cliente:</label>
          <input type="text" id="name" placeholder="Digite seu nome aqui" />
        </div>
        <div class="form-group">
          <label for="email">E-mail:</label>
          <input type="email" id="email" placeholder="Digite seu e-mail aqui" />
        </div>
        <div class="form-group">
          <label for="message">Mensagem:</label>
          <textarea id="message" placeholder="Digite sua mensagem aqui"></textarea>
        </div>
        <button class="btn">Enviar Mensagem</button>
      </div>
    </section>
  </div>

  <div class="container">
    <div class="header">
      <h1>Cadastro de Clientes</h1>
      <p>
        Registre facilmente os dados dos seus clientes para um atendimento personalizado e
        eficiente.
      </p>
    </div>
    <div class="content">
      <div class="card">
        <img
          src="https://images.unsplash.com/photo-1586497540021-40ffb083909a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
          alt="Cookies"
        />
        <div class="card-body">
          <h2>Registro de Vendas</h2>
          <p>
            Tenha controle total sobre suas vendas, registrando cada transação de forma simples e
            segura.
          </p>
        </div>
      </div>
      <div class="card">
        <img
          src="https://images.unsplash.com/photo-1576618249529-07f20b72f1a5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1470&q=80"
          alt="Cupcakes"
        />
        <div class="card-body">
          <h2>Cadastro de Produto</h2>
          <p>
            Adicione e gerencie seus produtos de forma prática, mantendo seu catálogo sempre
            atualizado e organizado.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
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

/* Rectangle 42 */ position: absolute; width: 783px; height: 86px; left: 568px; top: 301px;
background: #FFFFFF; /* Nome de Usuario */ position: absolute; width: 184px; height: 29px; left:
568px; top: 270px; font-family: 'Lato'; font-style: normal; font-weight: 400; font-size: 24px;
line-height: 29px; /* identical to box height */ color: #000000; /* Rectangle 45 */ position:
absolute; width: 324px; height: 80px; left: 535px; top: 1051px; background: #BC9270; border-radius:
42px;
