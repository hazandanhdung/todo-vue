<template>
  <div class="page-wrapper container ">
    Todo List Example
    <div class="box-todo-list">
      <TodoList></TodoList>
    </div>

  </div>
</template>

<script>
import TodoList from "../TodoList";

export default {
  name: 'landing-page',
  components: {
    TodoList
  },
  data() {
    return {
      TodoList
    }
  },
  methods: {},
  created() {
  }
  , mounted() {

  }
}

</script>


<style lang="scss" scoped>
.box-todo-list{
}

</style>
