<template>
  <div class="footer-container">
    <a
      href="https://github.com/cesarsl"
      class="footer-link"
      target="_blank"
      rel="noopener"
      ><img
        src="img/logo/github.svg"
        alt="Perfil de cesarsl no GitHub"
        class="footer-icon"
    /></a>
    <a
      href="https://www.linkedin.com/in/cesarliedke/"
      class="footer-link"
      target="_blank"
      rel="noopener"
      ><img
        src="img/logo/linkedin.svg"
        alt="Perfil de cesarliedke no LinkedIn"
        class="footer-icon"
    /></a>
  </div>
</template>

<style>
.footer-container {
  position: fixed;
  bottom: 0;
  right: 0;
  display: flex;
  padding: 1rem;
}

.footer-link {
  align-self: center;
  flex-shrink: 1;
  height: 2rem;
  margin-left: 1rem;
  text-decoration: none;
}

.footer-link:first-of-type {
  margin-left: 0;
}

.footer-icon {
  width: 2rem;
  height: 2rem;
}
</style>
