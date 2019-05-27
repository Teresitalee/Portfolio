<template>
<v-img
  src="https://images.unsplash.com/photo-1447703693928-9cd89c8d3ac5?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=751&q=80"
  height="927"
  dark
  position-x
  position-y
  
  >
<v-container fluid>
    <v-layout mt-4 align-start justify-start row fill-height>
      <v-flex xs4>
          <div class="mb-4 flex xs8 md12  ">
            <div class="font-weight-bold  yellow--text  mb-4 display-1" >My works recently .</div>
            <div class="subheading white--text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque molestias!</div>
            </div>
      </v-flex>
    </v-layout>
    <Gallery />  
    
</v-container>
</v-img>
</template>

<script>

    import Gallery  from "@/components/Gallery.vue";

    export default {
        components:{
            Gallery
        }
    }
</script>