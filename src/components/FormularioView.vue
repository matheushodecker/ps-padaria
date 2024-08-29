

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
      <div class="image">
        <img
          src="https://images.unsplash.com/photo-1524758631624-e2822e304c36?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80"
          alt="Padaria"
        />
      </div>
    </section>
  </div>
</template>

<style scoped>

</style>
