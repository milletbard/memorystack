<template>
  <nav class="navbar is-fixed-top header">
    <div class="container">
      <div class="navbar-brand">
        <a class="navbar-item is-size-4 has-text-primary">
          <logo style="margin-right: -10px;" />MemoryStack</a
        >

        <!-- <a
          role="button"
          class="navbar-burger burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
          @click="toggleBurger"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a> -->
      </div>

      <!-- <div id="nav-menu" :class="`navbar-menu ${active ? 'is-active' : ''}`">
        <div class="navbar-start"></div>

        <div class="navbar-end">
          <div class="navbar-item">
            <div class="buttons">
              <div class="navbar-item">
                <button
                  class="button is-bold is-primary is-outlined"
                  @click="routePush"
                >
                  Get started
                </button>
              </div>
            </div>
          </div>
        </div>
      </div> -->
    </div>
  </nav>
</template>

<script>
import Logo from './Logo'
export default {
  name: 'Navbar',
  components: {
    Logo
  },
  data: () => ({
    active: false
  }),
  methods: {
    toggleBurger() {
      const { active } = this
      this.active = !active
    }
    // routePush() {
    //   window.open('https://milletbard.com/26Memory/#/', '_self')
    // }
  }
}
</script>
<style>
.navbar {
  border-bottom: 1px solid #526488;
}
/* @keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
} */
</style>
