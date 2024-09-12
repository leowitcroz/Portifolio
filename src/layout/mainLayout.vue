<template>
  <div class="nav">
    <div class="logo">logo</div>
    <div class="options">
      <p>About</p>
      <p>Work</p>
      <p>Experience</p>
      <p>Contact</p>
      <p>Resume</p>
    </div>
  </div>
  <router-view />
</template>

<style>
.nav {
  background-color: #6967c3;
  display: flex;
  justify-content: space-between;
}

.options {
  display: flex;
}
</style>