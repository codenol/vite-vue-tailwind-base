<script setup>
</script>

<template>
  <div class="flex bg-white rounded-xl items-center text-center max-w-sm m-4 mx-auto p-6"> 
    {{ msg }}
  </div>
</template>

<script>
  export default {
    data() {

    },
    methods:{

    },
    props:{
      msg: String,
    }
  }
</script>

<style scoped>
</style>
