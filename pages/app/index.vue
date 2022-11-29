<template>
  <div class="text-center p-6">
    <NuxtLink to="/app" class="btn-custom">Pesquisar Grupo</NuxtLink>
    <NuxtLink to="/app" class="btn-custom">Rotas interativas</NuxtLink>
    <NuxtLink to="/app" class="btn-custom">Retire sua Bike</NuxtLink>
    <NuxtLink to="/app" class="btn-custom">Criar Grupo</NuxtLink>
    <NuxtLink to="/app" class="btn-custom">Resgate seus pontos</NuxtLink>
  </div>
</template>

<script>
export default {
  layout: 'app',
  data(){
    return {
      loading: true
    }
  },
  head() {
      return {
        title: 'Vem de bike'
      }
  },
  mounted(){
    setTimeout(() => {
      this.loading = false
    }, 2000);
  }
}
</script>

<style scoped>
  .btn-custom{
    width: 100% !important;
    display: inline-block;
  }
</style>
