<template>
  <div>
    <div class="flex justify-center items-center h-screen">
        <div class="text-center">
            <img class="inline mb-6" src="logo/vem-de-bike.png" width="40%" alt="" srcset="">
            <div class="mb-6">
                <input class="input-login" placeholder="Email" type="text">
                <input class="input-login" placeholder="Senha" type="password">
                <input class="btn-login" placeholder="Senha" type="submit">
            </div>
            <a href="#">Criar uma conta</a>
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
    .btn-login{
        box-sizing: border-box;
        width: 40%;
        height: 51px;
        left: 118px;
        top: 585px;
        margin-top: 20px;
        background: #2FBE34;
        border: 1px solid #164A0D;
        border-radius: 10px;
        cursor: pointer;
    }
    .btn-login:hover{
        background: #248527;
        border: 1px solid #164A0D;
        color: white;
    }
</style>