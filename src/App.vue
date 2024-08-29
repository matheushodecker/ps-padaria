<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" width="125" height="125" />

    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/loja">loja</RouterLink>
        <RouterLink to="/cadastro">Cadastro</RouterLink>
        <RouterLink to="/vendas">Vendas</RouterLink>
      </nav>
    </div>
  </header>
<RouterView/>
</template>

<style scoped>
body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

h1,
h2,
h3 {
  text-align: center;
  margin-top: 0;
  margin-bottom: 20px;
}

p {
  text-align: center;
  margin-bottom: 20px;
  line-height: 1.6;
}

.btn {
  display: inline-block;
  background-color: #007bff;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s;
}

.btn:hover {
  background-color: #0056b3;
}

/* Header styles */
header {
  background-color: #fff;
  padding: 20px;
  border-bottom: 1px solid #ddd;
}

.logo img {
  max-width: 200px;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  text-align: right;
}

nav li {
  display: inline-block;
  margin-left: 20px;
}

nav a {
  text-decoration: none;
  color: #333;
}

/* Hero section styles */
.hero {
  background-image: url('hero.jpg');
  background-size: cover;
  background-position: center;
  padding: 100px 0;
  text-align: center;
  color: #fff;
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 40px;
}

/* Pães frescos section styles */
.paes-frescos {
  padding: 40px 0;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
}

.item {
  text-align: left;
  border: 1px solid #ddd;
  padding: 20px;
}

.item img {
  max-width: 100%;
  height: auto;
  margin-bottom: 20px;
}

/* Pães em destaque section styles */
.paes-em-destaque {
  padding: 40px 0;
}

.paes-em-destaque .item {
  text-align: center;
}

/* Sobre section styles */
.sobre {
  padding: 40px 0;
}

.sobre .item {
  text-align: left;
}

.sobre ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.sobre li {
  margin-bottom: 10px;
}

/* Avaliações section styles */
.avaliacoes {
  background-color: #f0f0f0;
  padding: 40px 0;
  text-align: center;
}

.estrelas {
  font-size: 2em;
  margin-bottom: 20px;
  color: #ffc107;
}

/* Footer styles */
footer {
  background-color: #333;
  color: #fff;
  padding: 40px 0;
}

footer .grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

footer h3 {
  margin-top: 0;
  margin-bottom: 20px;
}

footer ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

footer li {
  margin-bottom: 10px;
}

footer a {
  text-decoration: none;
  color: #fff;
}

.social-media li {
  display: inline-block;
  margin-right: 10px;
}

.social-media a {
  font-size: 1.5em;
  color: #fff;
}

.social-media a:hover {
  color: #ffc107;
}

input[type='email'] {
  width: 100%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
  margin-bottom: 10px;
}

/* Responsive styles */
@media (max-width: 768px) {
  .grid {
    grid-template-columns: 1fr;
  }
}
</style>
