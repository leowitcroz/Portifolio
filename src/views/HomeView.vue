<template>
  <div class="container-fluid">
    <div class="row">
      <div
        class="col-lg-6"
        style="
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
        "
      >
        <div class="main">
          <h1 class="title">LEONARDO CROZETTA</h1>
          <div>
            <p class="text">
              AKA Leo, I'm a fullstack developer, from Curitiba Brazil, focused
              on creating web applications that will bring success to the
              project of their company and help them grow
            </p>
          </div>
          <button class="btn">Projects</button>
        </div>
      </div>

      <div class="col-lg-6" style="margin-top: 6%">
        <div class="me">
          <img
            style="width: 70%; margin-right: 10%"
            src="../assets/eu-removebg-preview.png"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" setup>
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Libre+Franklin:ital,wght@0,100..900;1,100..900&display=swap");

.main {
  font-family: "Libre Franklin", sans-serif;
  margin-left: 10%;
  margin-top: 20%;
}

.text {
  margin-top: 1%;
  font-size: 1.4rem;
  font-weight: 500;
  color: rgb(75, 75, 75);
}

.btn {
  margin-top: 2%;
  background-color: #4f52aa;
  color: whitesmoke;
  font-size: 1.3rem;
  font-weight: 600;
  width: 30%;
}
.btn:hover {
  background-color: #4f52aa;
  text-decoration: underline;
  color: whitesmoke;
  cursor: pointer;
}

.title {
  font-weight: bold;
  font-size: 3.3rem;
}
</style>
