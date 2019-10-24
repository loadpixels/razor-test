<template lang="pug">
  div
    b-navbar(type="dark" variant="dark")
      .container
        b-navbar-brand(to="/")
          img(src="~assets/navbar-logo.png" width="100" alt="Luminous")
        b-navbar-toggle(target="nav-collapse")
        b-collapse(id="nav-collapse" is-nav)
          b-navbar-nav
            b-nav-item(to="/") Home
            b-nav-item(to="/what") What is SMSC?
            b-nav-item-dropdown(text="Why Luminous?")
              b-dropdown-item(to="/why") Why not?
              b-dropdown-item(to="/coz") Coz it's awesome
            b-nav-item(to="/pricing") Pricing
            b-nav-item(to="/faqs") FAQs
            b-nav-item(to="/resources") Resources
          b-navbar-nav.ml-auto
            b-btn.mx-3(variant="primary" to="/demo") Demo
            b-btn(variant="primary" to="/demo") Sign up


    nuxt
</template>

<script>
export default {}
</script>
<style lang="scss"></style>
