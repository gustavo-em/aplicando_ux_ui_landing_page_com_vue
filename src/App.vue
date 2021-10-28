<template>
  <div>
    <Header/>
    <div class="container">
      <transition>
        <router-view/>
      </transition>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
export default {
    name:"App",
    components:{
      Header
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&family=Zen+Kurenaido&display=swap');

.div_link{
    display: flex;
    align-items: center;
}
.v-enter-active {
  transition: all .3s ease;
}
.v-enter, .v-leave-to {
  transform: translateX(10px);
  opacity: 0;
}
</style>
