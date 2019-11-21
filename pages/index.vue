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
  data: () => ({
      cards: [
        { id: 'jupyter', url:'https://source.unsplash.com/user/erondu', header: 'Single Document Mode', description: 'hey'},
        { id: 'start', url:'https://source.unsplash.com/random/800x600', header: 'testing 2', description: 'hey 2'},
        { id: 'cpc', url:'https://images.unsplash.com/photo-1573568783055-e47b4fd80830?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=80', header: 'testing 3', description: 'hey 3'}
      ]
  })
}
</script>

