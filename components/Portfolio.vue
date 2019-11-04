<template>
      <section>
         <card />
         <card />
         <card />
      </section>
</template>

<script>
import Card from '~/components/Card.vue'

export default {
  components: {
   Card
  }
}
</script>

<style scoped>
   @media only screen and (min-width: 1200px) {
      section{
         grid-column: 1;
         grid-row: 3;
      }
   }

   section{
      grid-column: 6 / 13;
      grid-row: 2;
   }

</style>