<template>
   <section>  
      <h1>{{post.header}}</h1>
      <p>{{post.content}}</p>
   </section>
</template>
<script>
/*
import Prismic from "prismic-javascript";
import PrismicDom from "prismic-dom" //importing the Dom
import PrismicConfig from "./../prismic.config.js";
*/

export default {
  data(){
     return {
     id: this.$route.params.id,
      posts: [
        { id: 'jupyter', header: 'fuck u bitch', content: 'hey'},
        { id: 'fucko', header: 'testing 2', content: 'hey 2'},
        { id: 'yes', header: 'testing 3', content: 'hey 3'}
      ]
   }
  },
  computed: {
     post(){
        return this.posts.find(post => post.id === this.id);
     } 
  }
/*
  async asyncData() {
    const api = await Prismic.getApi(PrismicConfig.apiEndpoint);
    let works = {};
    const results = await api.query(
      Prismic.Predicates.at("document.type", "works"),
      { lang: "en-us" } //This is a Prismic query option
    );
    console.log("Test 2");
    works = results.results[0];
    const header = PrismicDom.RichText.asText(works.data.post_title);
    const content = PrismicDom.RichText.asText(works.data.post_content);
    return { 
        works: works,
        header: header,
        content: content
    };
  } 
  */
};
</script>
