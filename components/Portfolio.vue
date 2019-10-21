<template>
   <div>
      <about />
      <section>
         <card />
         <card />
         <card />
      </section>
   </div>
</template>

<script>
import About from '~/components/About.vue'
import Card from '~/components/Card.vue'

export default {
  components: {
    About, Card
  }
}
</script>

<style>
   section{
      grid-column: 6 / 13;
      grid-row: 2;
   }
</style>