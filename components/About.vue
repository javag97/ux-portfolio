<template>
   <aside>
      <img src="~/static/portrait.jpg" class="aside__portrait"/>
      <personal/>
   </aside>
</template>

<style scoped>

   aside{
      position: inherit;
      top: 72px;
      grid-column: 1;
      grid-row: 2;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
   }

   @media only screen and (min-width: 1200px) {
      aside{
         grid-column: 1 / 5;
         position: sticky;
      }
   }

   img{
      width: 250px;
      
   }

   .aside__portrait{
      align-self: flex-end;
   }


</style>

<script>
import Personal from '~/components/Personal.vue'

export default {
  components: {
    Personal
  }
}
</script>

