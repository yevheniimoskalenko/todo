<template
  ><div>
    <div class="header">
      <h2>Завдання на весь час</h2>
    </div>
    <div class="form">
      <div class="content-inputs">
        <vs-input v-model="value" border placeholder="Завдання" />
      </div>
      <div class="center">
        <vs-button :active="active == 1" @click="active = 1">
          Створити
        </vs-button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return { value: '' }
  },
}
</script>
<style>
.vs-input-content {
  width: 100%;
}
.header {
}
.form {
  padding: 10px;
}
</style>
