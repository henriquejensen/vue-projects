<script setup>
import Title from "./components/AppTitle.vue";
import Form from "./components/FormCard.vue";
</script>

<template>
  <main class="container">
    <section class="section">
      <Title title="Adicionar nova carta" />
      <Form />
    </section>
    <section class="section section--dark">
      <Title title="Pré-visualização" />
    </section>
  </main>
</template>

<style>
body {
  margin: 0;
  padding: 0;
  background-color: #e5e5e5;
}
.container {
  display: flex;
  justify-content: center;
}

.section {
  flex: 1;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.section--dark {
  background-color: #023031;
  color: white;
}
</style>
