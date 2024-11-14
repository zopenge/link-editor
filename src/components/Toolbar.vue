<template>
  <div class="toolbar">
    <button class="toolbar-button">Button 1</button>
    <button class="toolbar-button">Button 2</button>
    <button class="toolbar-button">Button 3</button>
  </div>
</template>

<script>
export default {
  name: 'Toolbar'
}
</script>

<style scoped>
.toolbar {
  display: flex;
  background-color: #f0f0f0;
  padding: 10px;
  border-bottom: 1px solid #ccc;
}

.toolbar-button {
  margin-right: 10px;
  padding: 5px 10px;
  background-color: #007bff;
  color: white;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

.toolbar-button:hover {
  background-color: #0056b3;
}
</style> 