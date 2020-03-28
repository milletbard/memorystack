<template>
  <div class="container-main">
    <Navbar />
    <div class="layout-main">
      <Content />
      <progress class="progress" value="15" max="100">15%</progress>

      <how-works />
    </div>

    <Features />
    <Footer />
  </div>
</template>

<script>
import Navbar from '../components/Navbar'
import Content from '../components/Content'
import HowWorks from '../components/HowWorks'
// import Features from '../components/Features'
// import Footer from '../components/Footer'
export default {
  name: 'App',
  components: {
    Navbar,
    Content,
    HowWorks
    // Features,
    // Footer
  }
}
</script>

<style>
.container-main {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: flex-start;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
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

.layout-main {
  display: flex;
  flex-direction: column;
}

.links {
  padding-top: 15px;
}

@font-face {
  font-family: 'jf-openhuninn';
  src: url('../assets/fonts/jf-openhuninn-1.0.ttf');
}
* {
  font-family: 'jf-openhuninn', Helvetica, Arial, sans-serif !important;
}
</style>
