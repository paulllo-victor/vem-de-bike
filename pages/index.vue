<template>
  <div>
    <transition name="fade-leave">
      <!-- <Load v-if="loading"/>
      <Login v-else/> -->
      <Login/>
    </transition>

  </div>
</template>

<script>
export default {
  name: 'IndexPage',
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
