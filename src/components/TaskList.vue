<template>
  <div class="taskList">
    <TaskItem />
  </div>
</template>
<script>
import TaskItem from "./TaskItem.vue";
export default {
  components: {
    TaskItem,
  },
};
</script>

<style scoped>
.taskList {
  margin-top: 30px;
}
</style>