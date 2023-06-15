<script setup></script>
<template>
  <header>
    導覽列
    <RouterLink to="/"> home </RouterLink>
    <RouterLink to="about"> about </RouterLink>
    <RouterLink to="login"> login </RouterLink>
  </header>
  <main>
    <RouterView />
  </main>
  <footer class="mt-auto">footer</footer>
</template>
<style lang="scss"></style>
