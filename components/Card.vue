<template>
   <div>
      <img src="https://source.unsplash.com/random/800x400" />
      <h2>Single Document Mode</h2>
      <p>B2B Compute for Data Science</p> 
      <button>
         Read more
      </button>
   </div>
</template>


<style scoped>
   div{
      display: flex;
      flex-direction: column;
   }

   img{
      width: 100%;
      height: 400px;
   }

   h2{
      padding-bottom: 0.25em;
      padding-top: 0.25em;
      font-weight: 600;
      letter-spacing: 0.02em;
   }

   p{
      padding-bottom: 0.5em;
      font-size: 0.9em;
   }

   button{
      font-size: 1.25em;
      padding: 0.25em;
      background: #090835;
      letter-spacing: 0.05em;
      color: #EEEEEE;
      border-radius: 2px;
      margin: 0.5em 0px 3em;
   }


</style>