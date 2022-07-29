<template>
  <div>
    <section class="todoapp">
      <TodoHeader />

      <TodoMain />

      <todo-footer />
    </section>
  </div>
</template>

<script>
import TodoFooter from './components/TodoFooter.vue'
import TodoHeader from './components/TodoHeader.vue'
import TodoMain from './components/TodoMain.vue'

export default {
  components: {
    TodoHeader,
    TodoMain,
    TodoFooter
}
}
</script>

<style>

</style>