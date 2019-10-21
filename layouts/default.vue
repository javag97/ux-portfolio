<template>
  <div>
    <nuxt />
  </div>
</template>

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
  font-size: 1.25em;
  /*word-spacing: 1px;*/
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

</style>
