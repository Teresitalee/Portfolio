<template>
<v-img
  src="https://images.pexels.com/photos/2310642/pexels-photo-2310642.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
  height="827"
  dark
  position-x
  position-y
  
  >
    <v-container>
        <v-container fluid  >
    <v-layout row justify-space-between>
      <v-flex xs6>
          <div class="yellow--text display-2 font-weight-bold">What I know.</div>  
      </v-flex>
      
      <v-flex xs4>
        <div class="font-italic white--text">Lorem ipsum dolor sit amet consectetur adipisicing elit..</div>
        <div class="mt-3">
          
        
          <v-btn  class="yellow black--text " src="./assets/Resume Teresita Madriaza Segura_compressed.pdf">download
          <v-icon right >file_download</v-icon>
          </v-btn>
        </div>
      </v-flex>
    </v-layout>

    <!-- education skills -->
    
    <template>
  <v-container grid-list-md >
    <v-layout row wrap>
       <!--education  -->
      <v-flex  xs4>
        
        <div class="display-1 headline font-weight-medium mb-4 yellow--text text-capitalize">My education <v-icon color="yellow">school</v-icon>  </div>
        
        
        <v-layout class="text-uppercase subheading">
          <div class="white--text">Hunter College University of New York</div>
        </v-layout>
        <v-layout class="yellow--text headline text-capitalize text-lg-right font-weight-regular align-space-between justify-end">
          <div>Bacher arts</div>
        </v-layout>
        <v-layout align-space-between justify-end >
          <div class="subheading text-capitalize text-xs-right white--text">Restoring medio oriente</div>
        </v-layout>
        <v-layout class="subheading text-xs-right align-space-between justify-end">
          <div class="white--text mb-3" >2000-2003</div>
        </v-layout>

        <v-sheet
         class="d-flex"
         color="yellow"
         height="2" 
        >
        </v-sheet>
     

      
        <v-layout mt-3>
          <div class="subheading text-capitalize white--text">DUOC UC</div>
        </v-layout>
        <v-layout align-space-between justify-end >
          <div class="yellow--text headline  text-capitalize text-xs-right">computer sciense</div>
        </v-layout>
        <v-layout align-space-between justify-end>
          <div class="subheading text-capitalize text-xs-right white--text">Analist programming</div>
        </v-layout>
        <v-layout align-space-between justify-end>
          <div class="subheading text-capitalize text-xs-right white--text mb-3">2010-2015</div>
        </v-layout>

        <v-sheet
         class="d-flex"
         color="yellow"
         height="2" 
        >
        </v-sheet>
      

     
        <v-layout mt-3>
          <div class="text-uppercase subheading white--text ">Bootcamp Laboratoria scl</div>
        </v-layout>
        <v-layout align-space-between justify-end >
          <div class="yellow--text headline  text-capitalize text-xs-right">Programming</div>
        </v-layout>
        <v-layout align-space-between justify-end >
          <div class="subheading text-capitalize text-xs-right white--text">Front-end Developer</div>
        </v-layout>
        <v-layout align-space-between justify-end >
          <div class="subheading text-capitalize text-xs-right white--text ">2018</div>
        </v-layout>
      </v-flex>

      <!--skills  -->
      <v-flex xs4 offset-xs5 offset-md2>
        <div class="display-1 headline font-weight-medium mb-4 yellow--text text-capitalize">My Skills <v-icon color="yellow">stars</v-icon></div>
        <v-layout >
          <div class="yellow--text title text-uppercase font-weight-light">Graphic/media</div>
        </v-layout>

        <v-layout >
          <div class="text-capitalize mt-4 white--text">Photoshop</div>
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
          <div class="text-capitalize mt-4 white--text">Ilustrator</div>
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
          <div class="text-capitalize mt-4 white--text">adobe xd</div>
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
          <div class="text-capitalize mt-4 white--text">React JS</div>
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
          <div class="text-capitalize mt-4 white--text">Vue JS</div>
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
          <div class="text-capitalize mt-4 white--text">Laravel</div>
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
          <div class="text-capitalize mt-3 white--text">Inglés</div>
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
          <div class="text-capitalize mt-3 white--text">Boostrap</div>
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
          <div class="text-capitalize mt-3 white--text">Vuetify</div>
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
  </v-img>
</template>

<script>
import Progress  from "@/components/Progress.vue";


    export default {
        components:{
            Progress,
           
        }
    }


</script>
