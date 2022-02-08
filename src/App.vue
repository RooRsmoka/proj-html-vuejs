<template>
  <div id="app">
    <header-bar :nav="nav"/>
    <main-box/>
    <footer-box/>
  </div>
</template>

<script>
import HeaderBar from './components/HeaderBar.vue'
import MainBox from './components/MainBox.vue'
import FooterBox from './components/FooterBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBar,
    MainBox,
    FooterBox
  },
  data() {
    return {
      nav: [
        {
          id: "LmdC1DBnluad8j8x",
          label: "home",
          url: "/home"
        },
        {
          id: "j41FZZYypjSlRXYg",
          label: "about",
          url: "/about"
        },
        {
          id: "66X8On66mtrqf40M",
          label: "services",
          url: "/services"
        },
        {
          id: "1wzWq2vu7ccnQvgC",
          label: "packages",
          url: "/packages"
        },
        {
          id: "U4iBqAKdf62jBrgI",
          label: "insight",
          url: "/insight"
        }
      ]
    }
  }
}
</script>

<style lang="scss">
@import './style/common.scss';
</style>
