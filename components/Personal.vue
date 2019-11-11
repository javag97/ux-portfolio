<template>
   <div class="aside__wrapper">
      <nuxt-link class="nuxt-link--text" to="/"><h1>Javier Garcia</h1></nuxt-link>
      <h3>User Experience Designer</h3>
      <p>Visual designer, web technologist, pop culture nerd, gamer, matcha enthusiast.</p>
      <nav><a href="https://linkedin.com/in/javigme/">LinkedIn</a> / <a href="https://github.com/javag97">Github</a> / <a href="mailto:javier.garcia549@gmail.com">Email</a></nav>
   </div>
</template>


<style scoped>
   .aside__wrapper{
      position: relative;
      top: -100px;
   }

   h1{
      font-size: 3em;
      line-height: 0.9;
   }

   h3{
      padding-top: 1em;
      font-size: 1.5em;
      font-variant-caps: small-caps;
      -moz-font-feature-settings: "smcp";
      -webkit-font-feature-settings: "smcp";
      font-feature-settings: "smcp";
   }

   p{
      padding-top: 0.5em;
   }

   nav{
      padding-top: 2em;
   }

</style>

