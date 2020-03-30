<template>
  <section class="SectionComponent why-works hero section is-relative">
    <div class="container">
      <div class="SectionHeader__header content is-centered">
        <h1 class="title is-spaced has-text-weight-bold is-3 is-size-5-mobile">
          為什麼這個計劃表有效？
        </h1>
        <p class="has-text-weight-bold is-4 is-size-6-mobile">
          MemoryStack 是根據
          <a
            href="https://en.wikipedia.org/wiki/Forgetting_curve"
            target="_black"
            class="link-dashed has-text-primary"
            >The Ebbinghaus Forgetting Curve</a
          >
          規則之下產生的讀書計畫表，可以用來製造高效率的複習計畫，科學證實，有規律地複習，能夠幫助你形成長期記憶。
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'WhyWorks'
}
</script>

<style scoped>
.why-works .container {
  display: flex;
  flex-direction: column;
  max-width: 600px;
  justify-content: center;
  align-items: center;
}
</style>
