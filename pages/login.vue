<script setup>

const meuRoteador = useRouter()

const email = ref()
const password = ref()



const validarFormularioEEnviar = () => {

  alert(`Olá ${email.value} você vai se logar!`)

  meuRoteador.push('/escolher')

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
