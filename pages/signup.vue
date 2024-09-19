<template>
  <div class="signup-container">
    <div class="signup-form">
      <h1>Cadastro</h1>
      <form>
        <div class="form-group">
          <label for="name">Nome:</label>
          <input type="text" id="name"  required>
        </div>
        <div class="form-group">
          <label for="phone">Telefone:</label>
          <input type="tel" id="phone" required>
        </div>
        <div class="form-group">
          <label for="email">E-mail:</label>
          <input type="email" id="email"  required>
        </div>
        <button type="submit" class="signup-button">Cadastrar</button>
      </form>
    </div>
  </div>
</template>

