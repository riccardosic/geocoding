<template>
  <div class="flex-col w-full">
    <Navbar/>
    <router-view/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
export default {
  name: 'Home',
  components: {
    Navbar,
  }
}
</script>
