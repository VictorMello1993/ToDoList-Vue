<template>
  <div class="container">
    <div class="taskItem">
      <input type="button" class="button" value="x" />
      <span>Tarefa 1</span>
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style scoped>
.taskItem {
  width: 180px;
  height: 70px;
  background-color: #e64c05;
  color: #fff;
  text-align: center;
  border-radius: 4px;  
  position: relative;

  display: flex;
  justify-content: center;
  align-items: center;  
}

.button {
  border-radius: 10px;
  border: none;
  background-color: #000;

  color: #fff;
  opacity: 0.5;

  position: absolute;
  top: 2px;
  right: 2px;
}
</style>