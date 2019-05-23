<template>
 <v-container>
   <v-layout row wrap>
     <v-flex xs6 align-end justify-start column fill-height

>
       <v-card class="dark">
         <v-container fluid>
           <v-layout row>
             <v-flex xs5 sm4 md3>
               <v-img
               src="https://www.valuecoders.com/blog/wp-content/uploads/2018/05/laravel.jpg"
               height="200"
              
               > 
               </v-img>
             </v-flex>

             <v-flex xs7 sm8 md9  >
               <v-card-title grey--text >
                 <div>
                   <h4 class="dark--text mb-0 text-lg-right">Laravel</h4>
                    <p class="dark--text text-lg-right">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                 <div class="text-lg-right">23 abril 2019</div>
                  </div>
               </v-card-title>
               <v-card-actions >
                 <v-btn fab dark small color="pink">
                   <v-icon dark>link</v-icon>  
                 </v-btn>
               </v-card-actions>
             </v-flex>


           </v-layout>

         </v-container>
       </v-card>

     </v-flex>

   </v-layout>
   



















    
  </v-container> 
</template>


<script>
export default {
    name: 'Gallery'
}
</script>