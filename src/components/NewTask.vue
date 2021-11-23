<template>
  <div class="newTask">
    <input type="text" class="inputText" placeholder="Nova tarefa?" />
    <input type="button" class="addTask" value="+" />
  </div>
</template>
<style scoped>
input {
  border: solid #fff 1px;
  color: #fff;
}
.inputText {
  background-color: #555758;
  outline: 0;
  height: 20px;
  border-radius: 4px 0 0 4px;
  width: 250px;
}
::placeholder {
  color: #c8cdcc;
}
.addTask {
  background-color: #32bbf6;
  color: #fff;
  height: 24px;
  border-radius: 0 4px 4px 0;
}

.newTask {
  margin-top: 30px;
}
</style>