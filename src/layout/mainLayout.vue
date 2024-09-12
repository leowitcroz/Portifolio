<template>
  <div class="nav">
    <div class="logo">
      <img style="width: 25%;" src="../assets/logo_.png" alt="">
    </div>
    <div class="options">
      <p class="items">About</p>
      <p class="items">Work</p>
      <p class="items">Experience</p>
      <p class="items">Contact</p>
      <p class="items">Resume</p>
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

.logo{
  display: flex;
  justify-content: center;
  align-items: center;
}

.items {
  color: #f5f5f5;
  margin-top: 4%;
  margin-bottom: 4%;
  margin-right: 35px;
  font-size: 1.1rem;
  font-weight: 600;
}
.items:hover {
  cursor: pointer;
  text-decoration: underline;
}
</style>