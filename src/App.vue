<template>
  <div>
    <h1>Todo-Do-List</h1>
    <div>
      <TodoNew />
      <TodoList />
    </div>
  </div>
</template>

<script>
import TodoNew from "@/components/TodoNew.vue";
import TodoList from "@/components/TodoList.vue";

export default {
  components: {
    TodoNew,
    TodoList,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
