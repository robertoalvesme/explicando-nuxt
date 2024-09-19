<template>
  <div class="welcome-screen">
    <div class="logo-container">
      <img src="https://ocd.avaya.com/img/avaya.png" alt="Logo da Aplicação" class="logo">
    </div>
    <h1>Bem-vindo à Aplicação</h1>
    <div class="selection-buttons">
      <nuxt-link to="/signup" class="button">Criar Nova Conta</nuxt-link>
      <nuxt-link to="/login" class="button">Já Tenho Cadastro</nuxt-link>
    </div>
  </div>
</template>


<style scoped>
.welcome-screen {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
}

.logo-container {
  margin-bottom: 20px;
}

.logo {
  max-width: 150px; /* Ajuste conforme o tamanho do seu logo */
}

.selection-buttons {
  display: flex;
  flex-direction: column;
}

.button {
  background-color: #007bff;
  color: white;
  padding: 10px 20px;
  margin: 10px 0;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.button:hover {
  background-color: #0056b3;
}
</style>