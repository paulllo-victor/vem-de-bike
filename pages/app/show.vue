<template>
  <div class="px-6">
    <div class="text-center">
       <img class="inline" src="/images/logo.png" alt="" srcset="">
        <h4 class="font-medium">Amantes de bike Recife</h4>
        <img class="inline" src="/images/star.png" alt="" srcset="">
        
    </div>
    <h5 class="font-bold mt-6">Comentários</h5>
    <div class="mt-6">
        <div class="flex items-start mb-4" v-for="(persona,i) in personas" :key="i">
            <div>
                <img :src="persona.link" width="64px" alt="">
            </div>
            <div class="px-4">
                <h5 class="font-bold">{{persona.name}}</h5>
                <span>{{persona.description}}</span>
            </div>
        </div>
    </div>

    
    <div class="pt-4 text-cemter">
        <NuxtLink to="/app/groups" class="btn-custom block">Entrar</NuxtLink>
    </div>
  </div>
</template>

<script>
export default {
    layout: 'app',
    data(){
        return{
            personas: [
                {
                    'link': '/images/img-1.png',
                    'name': 'Bruna Luísa',
                    'description': 'Grupo Alegre e divertido, ótimas pessoas!',
                },
                {
                    'link': '/images/img-2.png',
                    'name': 'Leornado Silva',
                    'description': 'Grupo de Ciclismo unido e organizado!!',
                },
            ]
        }
    },
    head() {
        return {
            title: 'Vem de bike'
        }
    },
}
</script>

<style scoped>
    .input-custom,.btn-custom{
        width: 100% !important;
    }
</style>