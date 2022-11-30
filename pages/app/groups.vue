<template>
  <div class="px-6">
     <input class="input-custom" placeholder="Pesquisar" type="text">
     <h4 class="font-bold mb-4">Grupo perto de você</h4>
     <div v-for="(link,i) in links" :key="i">
    <NuxtLink to="/app/show" class="block mb-6 font-medium" >
        {{ link.name }}
    </NuxtLink>
     </div>
    
  </div>
</template>

<script>
export default {
    layout: 'app',
    data(){
        return{
            links: [
                {
                    'name': 'Amantes de bike Recife',
                },
                {
                    'name': 'Andando de bike por Recife',
                }
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
    .input-custom{
        width: 100% !important;
    }
</style>