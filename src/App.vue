<template>
  <div id="app">
    <header-box :nav="nav"/>
    <main-box/>
    <footer-box :recentPosts="recentPosts" :servicesList="servicesList"/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import MainBox from './components/MainBox.vue'
import FooterBox from './components/FooterBox.vue'

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
    FooterBox
  },
  data() {
    return {
      nav: [
        {
          id: "LmdC1DBnluad8j8x",
          url: "/home",
          label: "home"
        },
        {
          id: "j41FZZYypjSlRXYg",
          url: "/about",
          label: "about"
        },
        {
          id: "66X8On66mtrqf40M",
          url: "/services",
          label: "services"
        },
        {
          id: "1wzWq2vu7ccnQvgC",
          url: "/packages",
          label: "packages"
        },
        {
          id: "U4iBqAKdf62jBrgI",
          url: "/insight",
          label: "insight"
        }
      ],
      recentPosts: [
        {
          id: "gDo5L9yc39zjqT7P",
          url: "/posts/recent/post-one",
          postTitle: "When is it the right time to sell your company?",
          postContent: "Lorem ipsum dolor sit amet"
        },
        {
          id: "Rv5kcc91YdxGG3sQ",
          url: "/posts/recent/post-two",
          postTitle: "Personal debt or company debt we explore your options",
          postContent: "Lorem ipsum dolor sit amet"
        },
        {
          id: "8Hkd6XpM01TguL3y",
          url: "/posts/recent/post-three",
          postTitle: "An interview with a so-called business angel",
          postContent: "Lorem ipsum dolor sit amet"
        }
      ],
      servicesList: [
        {
          id: "C9sjW28kkIls3dp1",
          url: "/services/service-three",
          serviceTitle: "small business loan services",
          serviceContent: "Lorem ipsum dolor sit amet"
        },
        {
          id: "M8dcXom58wb9ll0T",
          url: "/services/service-three",
          serviceTitle: "credit rating advice services",
          serviceContent: "Lorem ipsum dolor sit amet"
        },
        {
          id: "Xo0cTkx27svMZ4pE",
          url: "/services/service-three",
          serviceTitle: "crowd funding services",
          serviceContent: "Lorem ipsum dolor sit amet"
        },
      ]
    }
  }
}
</script>

<style lang="scss">
@import './style/common.scss';
</style>
