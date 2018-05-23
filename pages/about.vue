<template>
  <div>
    <h1>About <i>{{ name.toUpperCase() }}</i></h1>
    <h2>age <b>{{ age * 2 }}</b></h2>
    <input :value="name" type="text"><br>
    <input v-model="name" type="text"><br>
    <input v-model="name" readonly type="text">
  </div>
</template>
<script>
export default {
  data() {
    return {
      name: 'Somsak2',
      age: 25,
    }
  },
}
</script>