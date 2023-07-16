<template>


<div class="flex flex-col h-screen">
    <div class="p-2 my-2 hover:bg-blue-50 rounded-full w-min
dark:hover:bg-white/20 " :class="transition">
    <NuxtLink to="">
        <div class="w-8 h-8">
      <LogosTwitter/>
      </div>
    </NuxtLink>
</div>  
</div>




    

</template>

<script setup>
const transition = 'transition ease-in-out duration-350'
</script>

<style scoped>

</style>