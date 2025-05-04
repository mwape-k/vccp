<script></script>

<template>
  <div class="hero-cont">
    <div class="navbar">
      <div class="background">
        <a class="navig-links" href="#background">BACKGROUND</a>
      </div>
      <div class="why-me-nav">
        <a class="navig-links" href="#why">WHY ME</a>
      </div>
      <div class="current-likes">
        <a class="navig-links" href="#currents">CURRENT LIKES</a>
      </div>
    </div>
    <div class="hero-container">
      <div class="col-left">
        <div class="mwape">MWAPE</div>
        <img class="heroimg-1-icon" alt="" src="../assets/HeroImg-1.svg" />
        <div class="mwape1">MWAPE</div>
      </div>
      <div class="col-mid">
        <img class="heroimg-2-icon" alt="" src="../assets/HeroImg-2.svg" />
      </div>
      <div class="col-right">
        <img class="heroimg-3-icon" alt="" src="../assets/HeroImg-3.svg" />
        <div class="kurete">KURETE</div>
        <div class="kurete1">KURETE</div>
      </div>
    </div>
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Darumadrop+One&family=Rock+3D&display=swap");

a {
  text-decoration: none;
  color: #212121;
  transition: all 300ms ease-in;
}

a:hover {
  color: #1e504d;
}
.background {
  width: 111px;
  position: absolute;
  margin: 0 !important;
  top: 9.21px;
  left: 85.5px;
  display: inline-block;
  z-index: 0;
}
.why-me-nav {
  width: 67px;
  position: absolute;
  margin: 0 !important;
  top: 9.21px;
  left: calc(50% - 33.19px);
  display: inline-block;
  z-index: 1;
}
.current-likes {
  width: 122px;
  position: absolute;
  margin: 0 !important;
  top: 9.21px;
  left: 711.24px;
  display: inline-block;
  z-index: 2;
}
.navbar {
  width: 906.6px;
  margin: 0 !important;
  position: absolute;
  top: 21.45px;
  left: 20%;
  box-shadow: 0px 2.948148012161255px 2.95px rgba(0, 0, 0, 0.25);
  border-radius: 36.85px;
  background-color: #fff;
  height: 44.2px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding: 14.7px 85.5px;
  box-sizing: border-box;
  gap: 243.2px;
  z-index: 0;
}
.mwape {
  align-self: stretch;
  position: relative;
  z-index: 0;
}
.heroimg-1-icon {
  width: 339.3px;
  position: relative;
  height: 421.2px;
  z-index: 1;
}
.mwape1 {
  width: 454px;
  position: absolute;
  margin: 0 !important;
  top: 33.9px;
  left: 0px;
  font-size: 103.52px;
  font-family: "Rock 3D";
  display: inline-block;
  z-index: 2;
}
.col-left {
  width: 455.5px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  position: relative;
  gap: 30.2px;
}
.heroimg-2-icon {
  width: 339.3px;
  position: relative;
  height: 421.2px;
}
.col-mid {
  height: 643.8px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  padding: 7.4px;
  box-sizing: border-box;
}
.heroimg-3-icon {
  width: 339.3px;
  position: relative;
  height: 421.2px;
  z-index: 0;
}
.kurete {
  align-self: stretch;
  position: relative;
  z-index: 1;
}
.kurete1 {
  width: 419px;
  position: absolute;
  margin: 0 !important;
  top: 537.3px;
  left: 0px;
  font-size: 85.84px;
  font-family: "Rock 3D";
  display: inline-block;
  z-index: 2;
}
.col-right {
  width: 419.4px;
  height: 643.8px;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  justify-content: flex-start;
  position: relative;
  gap: 81.1px;
  font-size: 121.83px;
}
.hero-container {
  margin: 0 !important;
  position: absolute;
  bottom: 50px;
  left: 6%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  gap: 29.5px;
  z-index: 1;
  font-size: 132.76px;
  color: #fff;
}
.hero-cont {
  width: 100%;
  height: 796px;
  margin-left: 10% !important;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  align-content: center;
  box-sizing: border-box;
  font-size: 17.69px;
  color: #212121;
  font-family: "Darumadrop One";
}
</style>
