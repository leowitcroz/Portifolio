<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-1 social" style="padding-left: 0">
        <div class="fundo">
          <div class="medias" style="margin-top: 30px">
            <a href="https://github.com/leowitcroz"
              ><img src="../assets/github.svg" alt=""
            /></a>
          </div>
          <div class="medias">
            <a href="https://www.linkedin.com/in/leonardo-crozetta-2a6873286/"
              ><img src="../assets/linkedin.svg" alt=""
            /></a>
          </div>
          <div class="medias">
            <a
              href="https://wa.me/5541999838087?text=Hey%2C%20I%20would%20like%20to%20know%20more%20about%20your%20work"
              ><img src="../assets/whatsapp.svg" alt=""
            /></a>
          </div>
          <div class="medias">
            <a href="https://lattes.cnpq.br/8496934641440705"
              ><img src="../assets/file-user1.svg" alt=""
            /></a>
          </div>
        </div>
      </div>
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
          <div>
            <h1 class="title">LEONARDO CROZETTA</h1>
            <p class="text">
              AKA Leo, I'm a fullstack developer, from Curitiba Brazil, focused
              on creating web applications that will bring success to the
              project of their company and help them grow
            </p>
          </div>
          <button class="btn">Projects</button>
        </div>
      </div>

      <div class="col-lg-5" style="margin-top: 4%">
        <div class="me">
          <img
            style="width: 80%"
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
  margin-top: 17%;
}

.fundo {
  align-items: center;
  padding: 10%;
  background-color: rgb(223, 222, 222);
  border-top-right-radius: 15px;
  border-bottom-right-radius: 15px;
}

.medias {
  display: flex;
  justify-content: center;
  align-items: center;
}

.medias img {
  margin-bottom: 30px;
  width: 30px;
  margin-right: 5px;
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
  font-size: 2.9rem;
}

.social {
  margin-top: 8%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
}
</style>
