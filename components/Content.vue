<template>
  <section
    id="content"
    class="SectionComponent hero section  is-relative is-medium"
  >
    <div class="container">
      <header class="SectionHeader__header is-centered">
        <h1 class="title is-spaced has-text-weight-bold is-2 is-size-4-mobile">
          最有效率的背單字計劃表
        </h1>
        <p class="has-text-weight-bold is-size-7-mobile">
          MemoryStack 是根據
          <a
            href="/integrations"
            target="_black"
            class="link-dashed has-text-primary"
            >The Ebbinghaus Forgetting Curve</a
          >
          規則之下產生的記單字計畫表，可以用來製造非常高效率的複習計畫，以更少的精力記住更多的內容，它非常適合考試準備，語言學習等。
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
