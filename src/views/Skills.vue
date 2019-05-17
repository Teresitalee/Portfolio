<template>
    <v-container>
        <v-container fluid  >
    <v-layout row justify-space-between>
      <v-flex xs6>
          <div class="yellow--text display-2 font-weight-bold">What I know.</div>  
      </v-flex>
      
      <v-flex xs4>
        <div class="font-italic">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatum a labore explicabo facere error vel ea, ducimus, consectetur eum tenetur repudiandae quo voluptates quasi, eveniet laboriosam. Distinctio aut maiores quisquam.</div>
        <div class="mt-3">
          
          
          <v-btn  class="orange--text content" src="./assets/Resume Teresita Madriaza Segura_compressed.pdf">download cv</v-btn>
        </div>
      </v-flex>
    </v-layout>

    <!-- education skills -->
    
    <template>
  <v-container grid-list-md >
    <v-layout row wrap>
       <!--education  -->
      <v-flex  xs4>  
        <div class="display-1 headline font-weight-medium mb-4 yellow--text text-capitalize">My education</div>
        <v-card>
        <v-layout class="text-capitalize subheading">
          <div>Hunter College University of New York</div>
        </v-layout>
        <v-layout class="yellow--text headline text-capitalize text-lg-right font-weight-regular">
          <div>Bacher arts</div>
        </v-layout>
        <v-layout>
          <div class="subheading text-capitalize text-xs-right">Restoring medio oriente</div>
        </v-layout>
        <v-layout class="subheading text-xs-right">
          <div >2000-2003</div>
        </v-layout>
      </v-card>

      <v-card >
        <v-layout mt-3>
          <div class="subheading text-capitalize">DUOC UC</div>
        </v-layout>
        <v-layout>
          <div class="yellow--text headline  text-capitalize text-xs-right">Bacher arts</div>
        </v-layout>
        <v-layout>
          <div class="subheading text-capitalize text-xs-right">Restoring medio oriente</div>
        </v-layout>
        <v-layout>
          <div class="subheading text-capitalize text-xs-right">2000-2003</div>
        </v-layout>
      </v-card>

      <v-card >
        <v-layout mt-3>
          <div class="text-capitalize subheading">Bootcamp Laboratoria LA</div>
        </v-layout>
        <v-layout>
          <div class="yellow--text headline  text-capitalize text-xs-right">Bacher arts</div>
        </v-layout>
        <v-layout>
          <div class="subheading text-capitalize text-xs-right">Restoring medio oriente</div>
        </v-layout>
        <v-layout>
          <div class="subheading text-capitalize text-xs-right">2000-2003</div>
        </v-layout>
      </v-card>
      </v-flex>

      <!--skills  -->
      <v-flex xs4 offset-xs5 offset-md2>
        <div class="display-1 headline font-weight-medium mb-4 yellow--text text-capitalize">My Skills</div>
        <v-layout >
          <div class="yellow--text title text-uppercase font-weight-light">Graphic/media</div>
        </v-layout>

        <v-layout >
          <div class="text-capitalize mt-4">Photoshop</div>
          <div class="mt-3 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >
          </v-rating>
          </div>
        </v-layout>

        <v-layout >
          <div class="text-capitalize mt-4">Ilustrator</div>
          <div class="mt-3 ml-3">
          <v-rating v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >

          </v-rating>
          </div>
        </v-layout>

        <v-layout >
          <div class="text-capitalize mt-4">adobe xd</div>
          <div class="mt-3 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >
          </v-rating>
          </div>
        </v-layout>

        <v-layout mt-3>
          <div class="yellow--text title text-uppercase font-weight-light ">Programming</div>
        </v-layout>

        <v-layout >
          <div class="text-capitalize mt-4">React JS</div>
          <div class="mt-3 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >
          </v-rating>
          </div>
        </v-layout>

        <v-layout >
          <div class="text-capitalize mt-4">Vue JS</div>
          <div class="mt-3 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >

          </v-rating>
          </div>
        </v-layout>

        <v-layout >
          <div class="text-capitalize mt-4">Laravel</div>
          <div class="mt-3 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >

          </v-rating>
          </div>
        </v-layout>

        <v-layout mt-3 >
          <div class="yellow--text title text-uppercase font-weight-light ">Otro</div>
        </v-layout>
        <v-layout >
          <div class="text-capitalize mt-3">Inglés</div>
          <div class="mt-2 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >

          </v-rating>
          </div>
        </v-layout>
        <v-layout >
          <div class="text-capitalize mt-3">Boostrap</div>
          <div class="mt-2 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >

          </v-rating>
          </div>
        </v-layout>
        <v-layout >
          <div class="text-capitalize mt-3">Vuetify</div>
          <div class="mt-2 ml-3">
          <v-rating 
          v-model="rating"
          record
          color="yellow accent-4"
          dense
          half-increments
          >

          </v-rating>
          </div>
        </v-layout>
        
      </v-flex>

    </v-layout>
  </v-container>
</template>
   
  </v-container> 
  </v-container>
  
</template>

<script>
import Progress  from "@/components/Progress.vue";


    export default {
        components:{
            Progress,
           
        }
    }


</script>
