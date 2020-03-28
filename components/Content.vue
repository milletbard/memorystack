<template>
  <section
    id="content"
    class="SectionComponent hero section  is-relative is-medium"
  >
    <div class="container box">
      <header class="SectionHeader__header is-centered">
        <h1 class="title is-spaced has-text-weight-bold is-3 is-size-5-mobile">
          最有效率的背單字計劃表
        </h1>
        <p class="has-text-weight-bold is-4 is-size-6-mobile">
          MemoryStack 是一種 web
          app，可以幫助你使用更有效率的方式記住你想學習的知識內容，它很適合拿來準備考試，語言學習。
        </p>
      </header>
      <div class="buttons is-centered">
        <button
          class="button is-bold is-primary is-outlined"
          @click="routePush"
        >
          Get started
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Content',
  methods: {
    routePush() {
      window.open('https://milletbard.com/26Memory/#/', '_self')
    }
  }
}
</script>
<style scoped>
#content {
  margin-top: 72px;
}

#content .container {
  display: flex;
  flex-direction: column;
  max-width: 600px;
  height: 240px;
  justify-content: space-between;
}
</style>
