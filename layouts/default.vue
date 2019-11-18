<template>
  <div class="container">
      <about />
      <nuxt />
  </div>
</template>

<script>
import About from '~/components/About.vue'

export default {
  components: {
    About
  }
}
</script>

<style>

  @font-face {
    font-family: "Work Sans";
    src: url("/static/WOFF2/WorkSans-Regular.woff2") format("woff2"),
    url("/static/WOFF/WorkSans-Regular.woff") format("woff");
    font-weight: normal;
    font-style: normal;
  }
  @font-face {
    font-family: "Work Sans";
    src: url("/static/WOFF2/WorkSans-Bold.woff2") format("woff2"),
    url("/static/WOFF/WorkSans-Bold.woff") format("woff");
    font-weight: bold;
    font-style: normal;
  }
    @font-face {
    font-family: "Work Sans";
    src: url("/static/WOFF2/WorkSans-SemiBold.woff2") format("woff2"),
    url("/static/WOFF/WorkSans-SemiBold.woff") format("woff");
    font-weight: 600;
    font-style: normal;
  }
  @font-face {
    font-family: "Work Sans";
    src: url("/static/WOFF2/WorkSans-ExtraBold.woff2") format("woff2"),
    url("/static/WOFF/WorkSans-ExtraBold.woff") format("woff");
    font-weight: 800;
    font-style: normal;
  }
    @font-face {
    font-family: "Work Sans";
    src: url("/static/WOFF2/WorkSans-Light.woff2") format("woff2"),
    url("/static/WOFF/WorkSans-Light.woff") format("woff");
    font-weight: 300;
    font-style: normal;
  }
  @font-face {
    font-family: "Work Sans";
    src: url("/static/WOFF2/WorkSans-Italic.woff2") format("woff2"),
    url("/static/WOFF/WorkSans-Italic.woff") format("woff");
    font-weight: normal;
    font-style: italic;
  }

html {
  font-family: 'Work Sans', -apple-system, BlinkMacSystemFont,
    Roboto, Arial, sans-serif;
  font-size: 1.5em;
  /*word-spacing: 1px;*/
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  -moz-font-feature-settings: "salt" 1;
  -webkit-font-feature-settings: "salt" 1;
  font-feature-settings: "salt" 1;
  color: #090835;
}
   section{
      grid-column: 1;
      grid-row: 3;
   }

   @media only screen and (min-width: 1200px) {
      section{
      grid-column: 6 / 13;
      grid-row: 2;
      }
   }

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

a{
   text-decoration: underline;
}

.nuxt-link--button{
   color: #EEEEEE;
   text-decoration: none;
}

.nuxt-link--text{
   color: #090835;
   text-decoration: none;
}

.container{
      align-items: start;
      display: grid;
      grid-template-columns: 1fr;
      grid-template-rows: 24px 1fr 64px;
      grid-gap: 48px;
      padding: 0 3%;
   }

   @media only screen and (min-width: 1200px) {
      .container{
         grid-template-columns: repeat(12, 1fr);
      }
   }
</style>
