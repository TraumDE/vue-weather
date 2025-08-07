<script setup lang="ts">
const id: string = 'red'
const newColor: string = 'blue'
const greenColor: string = 'green'
</script>

<template>
  <header :class="newColor"></header>
  <main :id></main>
  <div v-bind:class="greenColor"></div>
</template>

<style lang="scss" scoped></style>
