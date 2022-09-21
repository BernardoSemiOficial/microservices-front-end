<script lang="ts">
  import { defineComponent } from 'vue';
  import { RouterLink, RouterView } from 'vue-router'

  export default defineComponent({
    name: "App",
    components: {
      RouterLink,
      RouterView
    }
  })
</script>

<template>
  <RouterLink to="/">Cadastro</RouterLink>
  <RouterLink to="/products">Listagem</RouterLink>
  <RouterView />
</template>

<style scoped>

</style>
