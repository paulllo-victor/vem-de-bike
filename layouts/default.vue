<template>
  <div class="bg-content">
    <div class="content">
        <Nuxt />
    </div>
  </div>
</template>

<style scoped>
    .bg-content{
        background-color: rgba(243,244,246) !important;
        display: flex;
        justify-content: center;
        height: 100vh;
    }
    .content{
        box-shadow: 0 10px 20px #888888;
        display: relative;
        width: 30%;
        height: 100vh;
    }
    @media screen and (max-width: 1000px) {
        .content{
            width: 100%;
        }
    }
</style>