<template>
  <div>
    <input type="text" class="todo-input" placeholder="What needs
    to be done" v-model="newTodo">
    Todo list goes here
  </div>
</template>

<script>
export default {
  name: 'todo-list',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
  .todo-input{
    widows:100% ;
    padding: 10px 10px;
    font-size: 18px;
    margin-bottom:16px;

    &:focus{
      outline:0;
    }
  }
</style>
