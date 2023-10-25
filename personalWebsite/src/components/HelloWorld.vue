<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      <a href="https://github.com/vickEretus" target="_blank" rel="noopener">GitHub</a>
      <a href="https://www.linkedin.com/in/victor-pineda-a287a81a3" target="_blank" rel="noopener">Linkedin</a>
Computer science student seeking a spring or summer position internship, Experienced in Several different coding languages. Interested in different fields of the computer science, Available February-August 2024




    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
