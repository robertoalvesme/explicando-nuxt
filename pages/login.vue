<script setup>

const email = ref()
const password = ref()


const validarFormularioEEnviar = () => {

  alert(`Olá ${email.value} você vai se logar!`)

}

</script>


<template>

  <pre>
    email : {{ email }}
    password : {{ password }}
  </pre>


  <div class="login-container">
    <div class="login-form">
      <h1>Login</h1>

<!--      <form>-->
        <div class="form-group">
          <label for="email">E-mail:</label>
          <input v-model="email" type="email" id="email" required>
        </div>
        <div class="form-group">
          <label for="password">Senha:</label>
          <input v-model="password" type="password" id="password" required>
        </div>
        <button @click="validarFormularioEEnviar" type="button" class="login-button">Entrar</button>
<!--      </form>-->

    </div>
  </div>
</template>


<style scoped>
.login-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.login-form {
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

.login-button {
  width: 100%;
  padding: 10px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.login-button:hover {
  background-color: #0056b3;
}
</style>