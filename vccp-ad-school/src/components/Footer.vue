<script></script>

<template>
  <div class="footer-div">
    <ul>
      <li><a href="https://">CV Link</a></li>
      <li><a href="https://github.com/Mwape-Kurete">Github Link</a></li>
      <li><a href="mailto:kurete.mwape@gmail.com">Email</a></li>
      <li>
        <a
          href="https://www.instagram.com/boxdcheesecake?igsh=MXFiZzMyM2Z3MHdjZQ%3D%3D&utm_source=qr"
          >Portfolio Instagram</a
        >
      </li>
      <li><a href="">Linked In</a></li>
    </ul>
  </div>
</template>

<style>
ul {
  display: inline-grid;
  grid-auto-flow: row;
  grid-gap: 24px;
  justify-items: center;
  margin: auto;
  list-style-type: none;
}

li {
}
@media (min-width: 500px) {
  ul {
    grid-auto-flow: column;
  }
}

a {
  color: black;
  text-decoration: none;
  box-shadow: inset 0 -1px 0 hsla(0, 0%, 100%, 0.4);
}

a:hover {
  box-shadow: inset 0 -1.2em 0 hsla(0, 0%, 100%, 0.4);
}

li:last-child {
  grid-column: 1 / 2;
  grid-row: 1 / 2;
}

li:hover ~ li p {
  animation: wave-animation 0.3s infinite;
}

/* below is just for demo styling */

.footer-div {
  display: flex;
  height: 185px;
  width: 100%;
  bottom: 0 !important;
  background-color: #ecc113;
  line-height: 1.3;
  color: #000;
  font-family: "Darumadrop One";
}
</style>
