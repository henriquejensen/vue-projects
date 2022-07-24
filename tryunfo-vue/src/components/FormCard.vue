<script setup></script>

<template>
  <form class="form">
    <label for="name" class="form--label form--label__column">
      Nome
      <input id="name" type="text" />
    </label>
    <label for="description" class="form--label form--label__column">
      Descrição
      <textarea id="description" />
    </label>
    <label for="attr01" class="form--label">
      Attr01
      <input id="attr01" type="number" />
    </label>
    <label for="attr02" class="form--label">
      Attr02
      <input id="attr02" type="number" />
    </label>
    <label for="attr03" class="form--label">
      Attr03
      <input id="attr03" type="number" />
    </label>
    <p>Pontos restantes = {{ 0 }}</p>
    <label for="image" class="form--label">
      Imagem
      <input id="image" type="file" />
    </label>
    <label for="rare" class="form--label form--label__column">
      Raridade
      <select for="rare">
        <option>Raro</option>
      </select>
    </label>
    <label for="trunfo" class="form--label">
      <input id="trunfo" type="checkbox" />
      Super Trybe Trunfo
    </label>
    <button type="submit">Salvar</button>
  </form>
</template>

<style scoped>
.form {
  display: flex;
  flex-direction: column;
}

.form--label {
  margin: 0.2rem 0;
}

.form--label__column {
  display: flex;
  flex-direction: column;
}
</style>
