<template>
      <section>
        <card 
          v-for="card in cards"
          v-bind:key="card.id"
          v-bind:header="card.header"
          v-bind:url="card.url"
          v-bind:description="card.description"
          />
      </section>
</template>

<script>
import Card from '~/components/Card.vue'

export default {
  components: {
   Card
  },
  data: function() {
    return{
      cards: [
        { id: 1, url:'https://source.unsplash.com/user/erondu', header: 'testing', description: 'hey'},
        { id: 2, url:'https://source.unsplash.com/user/erondu', header: 'testing 2', description: 'hey 2'},
        { id: 3, url:'https://source.unsplash.com/user/erondu', header: 'testing 3', description: 'hey 3'}
      ]
    }
  }
}
</script>

