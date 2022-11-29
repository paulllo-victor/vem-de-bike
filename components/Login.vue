<template>
  <div>
    <div class="flex justify-center items-center h-screen">
        <div class="text-center">
            <img class="inline mb-6" src="logo/vem-de-bike.png" width="40%" alt="" srcset="">
            <div class="mb-6">
                <input class="input-login" placeholder="Email" type="text">
                <input class="input-login" placeholder="Senha" type="password">
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
    .input-login{
        box-sizing: border-box;
        width: 70%;
        height: 51px;
        left: 63px;
        top: 405px;
        padding: 10px;
        border: 1px solid #CCCCCC;
        filter: drop-shadow(0px 4px 4px rgba(0, 0, 0, 0.25));
        border-radius: 10px;
        margin-bottom: 15px;
    }
</style>