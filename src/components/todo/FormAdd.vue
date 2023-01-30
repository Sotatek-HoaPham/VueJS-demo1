<template>
  <form name="newform" v-on:submit.prevent="addItem">
    <label for="newitem">Add to the todo list</label>
    <input type="text" name="newitem" id="newitem" v-model="newitem">
    <button type="submit">Add item</button>
  </form>
</template>
<script>

</script>
<style>

</style>