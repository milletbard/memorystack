<template>
  <div class="container-main">
    <Navbar />
    <div class="layout-main">
      <Content />
      <progress class="progress" value="25" max="100">15%</progress>
      <why-works />
      <progress class="progress" value="50" max="100">15%</progress>
      <how-works />
      <progress class="progress" value="75" max="100">15%</progress>
      <get-started />
      <progress class="progress" value="100" max="100">15%</progress>
      <Footer />
    </div>
  </div>
</template>

<script>
import Navbar from '../components/Navbar'
import Content from '../components/Content'
import HowWorks from '../components/HowWorks'
import WhyWorks from '../components/WhyWorks'
import GetStarted from '../components/GetStarted'
import Footer from '../components/Footer'

export default {
  name: 'App',
  components: {
    Navbar,
    Content,
    HowWorks,
    WhyWorks,
    GetStarted,
    Footer
  },
  data: () => ({
    title: 'MemoryStack | 讀書計畫產生器'
  }),
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: '1',
          name: 'MemoryStack',
          content:
            "透過有系統的複習形成長期記憶, 讓知識不容易遺忘, 用於生產'讀書計畫'並進行規律複習的生產力工具, "
        }
      ],
      link: [
        {
          rel: 'icon',
          type: 'image/x-icon',
          href: './assets/favicon/nuxt-icon-favicon.ico'
        }
      ]
    }
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
  width: 90%;
}

.links {
  padding-top: 15px;
}

.progress {
  width: 85%;
  margin: 0 auto;
  margin-top: 1.5rem;
}

.box {
  width: 100%;
  border-radius: 30px;
  padding: 30px;
  max-width: 660px;
}

.button {
  border-radius: 30px;
}

@font-face {
  font-family: 'jf-openhuninn';
  src: url('../assets/fonts/jf-openhuninn-1.0.ttf');
}
* {
  font-family: 'jf-openhuninn', Helvetica, Arial, sans-serif !important;
}
</style>
