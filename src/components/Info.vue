<template>
  <div>
    <p v-if="esta_trabalhando">Estou trabalhando no momento.</p>
    <p v-else>Estou em busca</p>
    <p>Utilizo as seguintes tecnologias:</p>
    <ul>
      <li>PHP</li>
      <li>Laravel</li>
      <li>Vue</li>
    </ul>
    <p v-show="mostrar_email">Mande uma mensagem para: {{ email }}</p>
    <p v-if="4 > 2">Testando</p>
  </div>
</template>

<script>
export default {
  name: 'Info',
  data () {
    return {
      esta_trabalhando: false,
      mostrar_email: true,
      email: 'teste@teste.com'
    }
  }
}
</script>
