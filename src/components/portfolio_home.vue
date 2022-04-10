<template>
  <div class="portfolio_home">
    <div class="nav">
      <div class="nav-item">Resume</div>
      <div class="nav-item nav-center">Glory Kim</div>
      <div class="nav-item">LinkedIn</div>
    </div> 

    <div class="graphic devExperience">
      <img src="../assets/G.svg">
    </div>
    <div class="graphic simDev">
      <img src="../assets/L.svg">
    </div>
    <div class="graphic uiDev">
      <img src="../assets/O.svg">
    </div>
    <div class="graphic scrum">
      <img src="../assets/R.svg">
    </div>
    <div class="graphic years">
      <img src="../assets/Y.svg">
    </div>
  </div>
</template>

<script>
export default {
  name: 'portfolio_home',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.portfolio_home {
  display: block;
  width: 100vw;
  height: 100vh;
}
.nav {
  display: flex;
  align-items: center;
  justify-content: space-around;
}
.nav-item {
  flex: 1;
  border: 1px solid #3C556A;
  color: #C2C2C2;
  margin-top: 10px;
}
.nav-center {
  font-size: 1.5rem;
  color: #fff;
}
.graphic {
  display: inline-flex;
  justify-content: center;
  vertical-align: middle;
  width: auto;
  height: 50vh;
  padding: auto;
  background: no-repeat;
  margin-top: 40px;
}
.devExperience {
  position: absolute;
  z-index: 0;
}
.simDev {
  position: absolute;
  z-index: 1;
}
.uiDev {
  position: absolute;
  z-index: 2;
}
.scrum {
  position: absolute;
  z-index: 3;
}
.years {
  position: relative;
  z-index: 4;
}
</style>
