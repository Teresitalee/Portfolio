<template>
<v-layout class="mt-4">
    <v-flex xs12 sm6 offset-sm3>
      <v-card>
        <v-img
          src="https://cdn.vuetifyjs.com/images/cards/desert.jpg"
          aspect-ratio="2.75"
        ></v-img>

        <v-card-title primary-title >
          <div class="d-inline-block">
            <h3 class="headline mb-0 ">Teresita Madriaza Segura</h3>
            <div> {{ card_text }} </div>
          </div>
        </v-card-title>
         <v-card-text>
          <p class="text-md-center">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dignissimos necessitatibus repellat optio nisi veniam, corporis ullam dolorum sunt fuga quasi dolor distinctio nulla vel voluptates hic incidunt itaque quod magni.</p>
     
        </v-card-text>
 </v-card>


       <template>
        <v-container mt-4 >
         <v-flex xs12 sm8 offset-sm4>
           <v-layout>
              <v-card-actions>
              <div >  
              <v-btn class="pink--text" round color="dark" dark>Descargar PDF</v-btn>
              </div>
        </v-card-actions>
        <v-spacer></v-spacer>
           </v-layout>
         </v-flex>
        </v-container>
       </template>

    </v-flex>
  </v-layout>
  
</template>

<script>
export default {
   name: 'Biography'
}
</script>