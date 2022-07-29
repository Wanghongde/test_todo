<template>
  <section class="main">
    <input id="toggle-all" class="toggle-all" type="checkbox" >
		<label for="toggle-all">Mark all as complete</label>
    
    <ul class="todo-list">
      <li class="completed" >
        <div class="view">
          <input class="toggle" type="checkbox" />
          <label>任务名</label>
          <button class="destroy"></button>
        </div>
      </li>
    </ul>
  </section>
  
</template>

<script>
export default {
}
</script>