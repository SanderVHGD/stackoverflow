<template>
  <div>
    <nav
      class="navbar header has-shadow is-primary"
      role="navigation"
      aria-label="main navigation"
    >
      <div class="container">
        <div class="navbar-brand">
          <a
            class="navbar-item"
            href="/"
          >
            Stackoverflow
          </a>

          <div class="navbar-burger">
            <span />
            <span />
            <span />
          </div>
        </div>
      </div>
    </nav>

    <section class="main-content columns">
      <div class="container">
        <Nuxt />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' }
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' }
        }
      ]
    }
  }
}
</script>
