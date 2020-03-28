<template>
  <section class="SectionComponent hero section content is-relative is-medium">
    <div class="container box">
      <header class="SectionHeader__header is-centered">
        <h1 class="title is-spaced has-text-weight-bold is-3 is-size-5-mobile">
          最有效率的讀書計劃表
        </h1>
        <p class="has-text-weight-bold is-4 is-size-6-mobile">
          MemoryStack 是一種 web
          app，自動產生有效率的複習計畫，可幫助您以更少的精力記住更多的內容，它很適合拿來準備考試，語言學習。
        </p>
        <br />
      </header>

      <div class="buttons is-centered">
        <button
          class="button is-bold is-primary  is-medium  is-outlined"
          @click="routePush"
        >
          開始使用
        </button>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Content",
  methods: {
    routePush() {
      window.open("https://milletbard.com/26Memory/#/", "_self")
    }
  }
}
</script>
<style scoped>
.content {
  margin-top: 72px;
}

.content .container {
  display: flex;
  flex-direction: column;

  justify-content: space-between;
}
</style>
