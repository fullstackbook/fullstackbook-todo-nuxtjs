<template>
  <div class="layout">
    <h1 class="title">To Do</h1>
    <slot></slot>
  </div>
</template>

<style>
.layout {
  width: 300px;
  margin: 20px;
}

.title {
  text-align: center;
  font-size: 24px;
  margin: 10px;
  font-family: Arial, Helvetica, sans-serif;
}
</style>