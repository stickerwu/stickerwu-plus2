<template>
  <h1 class="title">
    Stickerwu-Plus2 UI 组件展示
  </h1>
  <nav class="nav">
    <router-link to="/">Icon</router-link>
    <router-link to="/button">Button</router-link>
    <router-link to="/card">Card</router-link>
    <router-link to="/dialog">Dialog</router-link>
    <router-link to="/pager">Pager</router-link>
    <router-link to="/collapses">Collapses</router-link>
    <router-link to="/tooltip">Tooltip</router-link>
    <router-link to="/dropdown">Dropdown</router-link>
  </nav>
  <div class="displayArea">
    <router-view />
  </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
h1.title {
  text-align: center;
  font-weight: 200;
}

.nav {
  display: flex;
  height: 50px;
  justify-content: center;
  align-items: center;
}

.displayArea {
  margin-top: 2em;
}

.active {
  border-bottom: 3px solid hsla(160, 100%, 37%, 1);
}
</style>