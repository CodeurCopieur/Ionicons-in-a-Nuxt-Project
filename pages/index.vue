<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        Codwerk
      </h1>
      <div class="links">
        <a
          href="https://www.linkedin.com/in/widdy-louis/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          <i class="icon ion-logo-linkedin"></i>
          Documentation
        </a>
        <a
          href="https://codepen.io/codwerk"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
        <i class="icon ion-logo-codepen"></i>
          codwerk
        </a>
        <a
          href="https://github.com/codwerk"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
        <i class="icon ion-logo-github"></i>
          codwerk
        </a>
        <a
          href="https://www.instagram.com/codwerk/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
        <i class="icon ion-logo-instagram"></i>
          codwerk
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
