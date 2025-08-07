<script setup lang="ts">
const ten: number = 10
const hello: string = 'hello'
const bool: boolean = true
const obj: object = {
  a: 10,
}

const link: string = `<a href="/">link</a>`
</script>

<template>
  <header>{{ ten }}</header>
  <main>{{ hello }}</main>
  <div>{{ bool }}</div>
  <div v-html="link"></div>
  <footer>{{ obj }}</footer>
</template>

<style lang="scss" scoped></style>
