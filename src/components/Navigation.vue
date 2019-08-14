<template>
  <b-navbar id="nav" toggleable="lg" type="dark" variant="info">
    <div class="container">
      <b-navbar-brand>
        <router-link to="/" role="link">Front End Framework</router-link>
      </b-navbar-brand>

      <b-navbar-toggle target="nav_collapse" />

      <b-collapse is-nav id="nav_collapse">
        <b-navbar-nav class="ml-auto" role="menu">
          <li class="nav-item" role="menuitem">
            <router-link role="link" class="nav-link" to="/">Home</router-link>
          </li>
          <li class="nav-item" role="menuitem">
            <router-link role="link" class="nav-link" to="/about">About</router-link>
          </li>
        </b-navbar-nav>
      </b-collapse>
    </div>
  </b-navbar>
</template>

<script>
  export default {
    name: 'navigation',
    props: {
      msg: String
    }
  }
</script>

<style lang="less">
@import '~../less/variables.less';
</style>