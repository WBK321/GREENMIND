<script>
</script>

<template>
  <div class="Logo">
    <nav class="nav">
      <a class="nav-link active" aria-current="page" href="#" id="shop"
        >GREENMIND</a
      >
      <a class="nav-link" href="#" id="Home">Home</a>
      <a class="nav-link" href="#">Products</a>
      <a class="nav-link" aria-disabled="true">Dontocts</a>
    </nav>
  </div>
  <div class="bloc_infa">
    <div class="bloc_information">
      <div class="bloc_gl_text">
        <h1 class="bloc_text">Buy your dream plants</h1>
        <div class="bloc_content">
          <div class="bloc_con_text_1">
            <p class="Number">50+</p>
            <p class="text">Plant Specles</p>
          </div>
          <div class="Separator">
            <p class="separator">|</p>
          </div>
          <div class="bloc_con_text_2">
            <p class="Number">100+</p>
            <p class="text">Customers</p>
          </div>
        </div>
        <div class="bloc_coms">
          <div class="bloc_input">
            <label for="validationCustom01"></label>
            <input
              type="text"
              class="form-control"
              id="validationCustom01"
              value="What are you looking for?"
              required
            />
          </div>
          <div class="bloc_img">
            <img
              src="../assets/Vector.png"
              title="Направление"
              alt="Направление"
            />
          </div>
          <div class="bloc_img_LOGO">
            <!-- <img src="../assets/Ras.jpg" title="Направление" alt="Направление"> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
 
<style scoped>
.Logo {
  margin: 20px 0px 0px 30px;
}

#shop {
  font-family: Bookman, URW Bookman L, serif;
  margin: 0px 30px 0px 10px;
  font-size: 28px;
  padding: 4px;
  color: black;
}

#Home {
  color: rgb(35, 35, 35);
}

a {
  margin: 0px 10px 0px 10px;
  font-size: 23px;
  font-weight: 500;
  color: rgb(99, 98, 98);
}

.bloc_infa {
  display: flex;
  align-items: center;
  justify-content: center;
}

.bloc_information {
  margin: 20px 0px;
  width: 1848px;
  height: 612px;
  background-color: #c1dcdc;
  border-radius: 25px;
}

.bloc_gl_text {
  width: 550px;
  height: 250px;
  padding: 10px 0px 0px 35px;
}

.bloc_text {
  font-size: 75px;
  font-weight: 600;
  color: rgb(0, 0, 0);
}

.bloc_content {
  display: flex;
}

.bloc_con_text_1 {
  margin: 0px 15px;
}

.bloc_con_text_2 {
  margin: 0px 35px;
}

.Separator {
  margin: 0px 20px 0px 20px;
}

.separator {
  font-size: 65px;
  font-weight: 300;
}

.Number {
  font-size: 55px;
  font-weight: 500;
}

.text {
  font-size: 28px;
}

.bloc_coms {
  display: flex;
}

.bloc_input {
  margin: 10px;
  display: flex;
}

.form-control {
  width: 480px;
  height: 55px;
}

.bloc_img {
  margin: 0px 0px 0px 0px;
}

.bloc_img_LOGO {
  background-color: black;
  margin: 0px 0px 0px 35px;
  width: 500px;
  height: 250px;
  border-top-left-radius: 25px;
}
</style>