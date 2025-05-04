<script setup>
import NavBar from "./components/NavBar.vue";
import HeroSection from "./components/HeroSection.vue";
import Background from "./components/Background.vue";
import WhyMe from "./components/WhyMe.vue";
import CurrentLikes from "./components/CurrentLikes.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="layout">
    <header class="head">
      <HeroSection />
    </header>
    <main class="main-sec">
      <div id="background" class="background-main-cont">
        <Background />
      </div>
      <div id="why" class="why-main-container">
        <WhyMe />
      </div>
      <div id="currents" class="current-main-container">
        <CurrentLikes />
      </div>
    </main>
    <footer>
      <Footer />
    </footer>
  </div>
</template>

<style scoped>
body {
  background-image: url("@/assets/texture-background.png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  min-height: 100vh;
  margin: 0 auto;
}

footer {
  bottom: 0;
  width: 100%;
}
header .head {
  width: 100%;
  top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  margin-bottom: 5%;
  flex: 1;
}

.main-sec {
  flex: 1;
}

.background-main-cont {
  margin-bottom: 10%;
  flex: 1;
}

.why-main-container {
  margin-bottom: 10%;
  flex: 1;
}

.current-main-container {
  margin-bottom: 10%;
  flex: 1;
}
</style>
