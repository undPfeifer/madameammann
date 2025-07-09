<template>
    <input 
      type="radio" 
      :class="{ active: inputState === 'on' }" 
      @click="switchIt"
    >
  </template>
  
  <style scoped>
  input {
    all: unset;
    height: 30px;
    aspect-ratio: 1/1;
    border: 1px solid black;
    border-radius: 100px;
    cursor: pointer;
  }
  
  input.active {
    background-color: black;
  }
  </style>
  
  <script setup>
  import { ref } from 'vue'
  
  const inputState = ref('on')
  
  function switchIt() {
    inputState.value = inputState.value === 'on' ? 'off' : 'on'
  }
  </script>
  