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


<style scoped>
.signup-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.signup-form {
  width: 100%;
  max-width: 400px;
  padding: 20px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
}

.form-group {
  margin-bottom: 15px;
}

.form-group label {
  display: block;
  margin-bottom: 5px;
}

.form-group input {
  width: 100%;
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

.signup-button {
  width: 100%;
  padding: 10px;
  background-color: #28a745;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.signup-button:hover {
  background-color: #218838;
}
</style>