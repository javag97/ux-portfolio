<template>
      <portfolio class="container"/>
</template>

<script>
import Portfolio from '~/components/Portfolio.vue'

export default {
  components: {
   Portfolio
  }
}
</script>

<style>
.container{
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  grid-template-rows: 64px 1fr 64px;
  grid-gap: 48px;
  padding: 0 3%;
}
</style>
