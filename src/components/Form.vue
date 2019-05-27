<template>
  <v-container >
     <v-layout row>
      <v-flex  row xs10 >
        <div>
          <v-responsive
                    >
                    <v-img 
                     height="300"
                     width="550"
                     :src="require('@/assets/pic1.png')"
                    >
                    </v-img>
                </v-responsive>
          </div>  
    </v-flex>

       </v-layout>   
  </v-container>
</template>

<script>
export default {
    name: 'Form'
}

</script>



