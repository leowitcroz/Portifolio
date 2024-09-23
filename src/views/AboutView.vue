<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-6" style="display: flex; justify-content: center; align-items: center; height: 90vh; ">
        <img class="eu-img" src="../assets/eu.jpg" alt="" />
      </div>
      <div class="col-6" style="margin-top: 10%;">
        <div class="texts">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
          Exercitationem quidem fugit eaque. Ratione numquam maxime natus
          necessitatibus. Accusamus voluptatem atque saepe sunt perferendis
          dignissimos numquam, debitis labore ratione praesentium ex?
        </div>
      </div>
    </div>
  </div>
</template>
  
  <script lang="ts" setup>
</script>
  
  <style>
@import url("https://fonts.googleapis.com/css2?family=Libre+Franklin:ital,wght@0,100..900;1,100..900&display=swap");

.eu-img {
  border-radius: 4% 27% 10% 29% / 10% 49% 9% 51%;
  border: 5px solid #6967c3;
  width: 65%;
  margin-left: 5%;
}

.texts {
  margin-right: 10%;
  text-align: left;
  font-size: 1.4rem;
  font-weight: 500;
  color: rgb(75, 75, 75);
  background-color: rgb(223, 222, 222);
  padding: 4%;
  border-radius: 15px;
}
</style>
  