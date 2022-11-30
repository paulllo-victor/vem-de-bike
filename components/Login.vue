<template>
  <div>
    <div class="flex justify-center items-center h-screen">
        <div class="text-center">
            <img class="inline mb-6" src="logo/vem-de-bike.png" width="40%" alt="" srcset="">
            <div class="mb-6">
                <input class="input-custom" placeholder="Email" type="text">
                <input class="input-custom" placeholder="Senha" type="password">
                <input class="btn-custom" placeholder="Senha" type="submit">
            </div>
            <NuxtLink to="/app">Criar uma conta</NuxtLink>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
    
</style>