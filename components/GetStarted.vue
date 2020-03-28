<template>
  <section class="get-started hero section is-relative is-medium">
    <div class="container box ">
      <div class="is-centered ">
        <h2 class="title is-spaced has-text-weight-bold is-4 is-size-6-mobile">
          MemoryStack 入門
        </h2>
        <p class="bold has-text-grey is-4 is-size-6-mobile">
          開始創建你的讀書計畫
        </p>
        <br />
      </div>
      <div class="buttons is-centered">
        <button
          class="button is-bold is-primary is-medium is-outlined"
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
  name: "GetStarted",
  methods: {
    routePush() {
      window.open("https://milletbard.com/26Memory/#/", "_self")
    }
  }
}
</script>
