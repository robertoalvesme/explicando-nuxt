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

