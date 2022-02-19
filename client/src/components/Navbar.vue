<template>
<div class="flex px-2 py-3 justify-between w-full m-auto bg-gray-800">
        <router-link to="/" class="text-2xl px-2 py-3 cursor-pointer font-light text-white">
            Geo 
            <span class="text-green-500">coding</span>
        </router-link>
        <router-link to="/about" class="px-3 py-4 font-light text-xl mr-8 cursor-pointer text-white hover:text-gray-300">
            about
        </router-link>
    </div>
</template>
<script>
export default {
  name: 'Home',
  components: {
  }
}
</script>
<style>
body::-webkit-scrollbar {
  display: none;
}
</style>