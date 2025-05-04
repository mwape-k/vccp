<script></script>

<template>
  <div class="container-fluid">
    <div class="header-section">
      <div class="likes-header">
        <div class="current-likes-lovessss">CURRENT LIKES (LOVESSSS)</div>
        <div class="current-likes-lovessss1">CURRENT LIKES (LOVESSSS)</div>
      </div>
    </div>
    <div class="row cards">
      <div class="col-6 artist-custom-card">
        <div class="fav-artist-card">
          <img class="image-2-icon" alt="" src="../assets/deki-alem.png" />
          <div class="header1">
            <div class="current-favourite-artist">
              Current Favourite Artist: Deki Alem
            </div>
          </div>
        </div>
      </div>
      <div class="col-6 drink-custom-card">
        <div class="fav-drink">
          <img
            class="image-from-rawpixel-id-1523235-icon"
            alt=""
            src="../assets/matcha.png"
          />
          <div class="artist-lbl">
            <div class="current-drink-order">Current Drink Order</div>
          </div>
          <div class="artist-lbl1">
            <div class="iced-matcha-latte">Iced Matcha Latte</div>
            <div class="iced-matcha-latte1">Iced MAtcha LAtte</div>
          </div>
          <div class="basic-graph">
            <img
              class="basic-graph-child"
              alt=""
              src="../assets/Vector 1.svg"
            />
            <div class="its-basic-i">it’s basic... i know...</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.header-section {
  margin-bottom: 10%;
}
.cards {
  display: flex;
  flex-direction: row;
  justify-content: center; /* or use 'center' or 'start' based on your need */
  gap: 15rem; /* optional spacing between the two cards */
}

.artist-custom-card,
.drink-custom-card {
  width: 50%;
}
/*header section*/
.current-likes-lovessss {
  position: absolute;
  top: 0px;
  left: 0px;
}
.current-likes-lovessss1 {
  position: absolute;
  top: 0.73px;
  left: 37px;
  font-size: 70.34px;
  font-family: "Darumadrop One";
}
.likes-header {
  width: 100%;
  position: relative;
  height: 102.7px;
  text-align: left;
  font-size: 46.89px;
  color: #fff;
  font-family: "Rock 3D";
}

/*fav-artist*/

.image-2-icon {
  position: absolute;
  top: 41.75px;
  left: 88.55px;
  width: 443px;
  height: 363.4px;
  object-fit: cover;
}
.current-favourite-artist {
  position: relative;
}
.header1 {
  position: absolute;
  top: 0px;
  left: 94.51px;
  background-color: #fa5406;
  width: 444.7px;
  height: 55px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 0px 132.6px;
  box-sizing: border-box;
}
.deki-alem {
  position: relative;
  z-index: 0;
}
.deki-alem1 {
  width: 192px;
  position: absolute;
  margin: 0 !important;
  top: 0px;
  left: 106.97px;
  font-family: "Rock 3D";
  display: inline-block;
  z-index: 1;
}
.artist-lbl1 {
  position: absolute;
  top: 393.44px;
  left: 0px;
  background-color: #fa5406;
  width: 444.7px;
  height: 55px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 0px 132.6px;
  box-sizing: border-box;
  gap: 7.3px;
  font-size: 29.31px;
}
.fav-artist-card {
  width: 100%;
  position: relative;
  height: 448.4px;
  text-align: left;
  font-size: 17.58px;
  color: #000;
  font-family: "Darumadrop One";
}

/*fav-drink*/

.image-from-rawpixel-id-1523235-icon {
  position: absolute;
  top: 0px;
  left: 104.77px;
  width: 394.8px;
  height: 571.7px;
  object-fit: contain;
}
.current-drink-order {
  position: relative;
}
.artist-lbl {
  position: absolute;
  top: 88.65px;
  left: 94.51px;
  background-color: #f6b4b8;
  width: 444.7px;
  height: 55px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 0px 132.6px;
  box-sizing: border-box;
}
.iced-matcha-latte {
  width: 329px;
  position: relative;
  display: inline-block;
  flex-shrink: 0;
  z-index: 0;
}
.iced-matcha-latte1 {
  width: 403px;
  position: absolute;
  margin: 0 !important;
  top: 0px;
  left: calc(50% - 202.67px);
  font-size: 32.8px;
  font-family: "Rock 3D";
  display: inline-block;
  z-index: 1;
}
.artist-lbl1 {
  position: absolute;
  top: 482.1px;
  left: 0px;
  background-color: #f6b4b8;
  width: 444.7px;
  height: 55px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 0px 132.6px;
  box-sizing: border-box;
  gap: 7.3px;
  font-size: 30.77px;
}
.basic-graph-child {
  position: absolute;
  top: 0px;
  left: 65.19px;
  width: 124.2px;
  height: 84.5px;
}
.its-basic-i {
  position: absolute;
  top: 85.34px;
  left: 0px;
  display: inline-block;
  width: 166.5px;
  height: 25.4px;
}
.basic-graph {
  position: absolute;
  top: 251.74px;
  left: 10.66px;
  width: 189.4px;
  height: 110.8px;
  font-size: 13.12px;
  color: #fff;
}
.fav-drink {
  width: 100%;
  position: relative;
  height: 571.7px;
  text-align: left;
  font-size: 17.58px;
  color: #000;
  font-family: "Darumadrop One";
}
</style>
