<script setup>
import { ref } from 'vue';
import MyComponent from './MyComponent.vue'

const msg = ref('Text')
</script>



<template>

<input placeholder="text please" v-model="msg" />

  <MyComponent title="Welcome" sub="ahmed" />
  <MyComponent title="Features" sub="toto"/>
  <MyComponent :sub="msg" title="msg" />
</template>

