<script setup>
defineProps(['title','sub'])
</script>

<template>
  <div class="card">
    <h3>{{ title }}</h3>
    <p>{{sub}}</p>
  </div>
</template>

<style scoped>
.card {
  border: 1px solid #ccc;
  border-top: 7px solid #AAAAFF;
  padding: 10px;
  margin: 5px 0;
  
}
</style>
