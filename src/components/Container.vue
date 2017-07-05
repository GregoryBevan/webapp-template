<template>
  <div class="container">
    <div class="header">Header</div>
    <div class="sidebar">Sidebar</div>
    <div class="content">Content</div>
    <div class="footer">Footer</div>
  </div>
</template>

<script>
export default {
  name: 'container'
}
</script>

<style scoped>
.container {
  display: grid;
  grid-template-columns: 5% 5% auto 5% 5%;
  grid-template-rows: 15% auto 15%
}

.header {
  background-color: black;
  color: white;
  grid-column: 1 / span 5;
  grid-row: 1 / span 1;
  border:2px;
}

.sidebar {
  grid-column: 2;
  grid-row: 2
}

.content {

}

.footer {

}
</style>
