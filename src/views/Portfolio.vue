<template>
<v-img
  src="https://images.pexels.com/photos/2310642/pexels-photo-2310642.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
  height="527"
  :gradient="gradient"
  dark
  position-x
  position-y
  
  >
<v-container>

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