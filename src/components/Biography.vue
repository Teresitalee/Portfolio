<template>
<v-img
  src="https://images.pexels.com/photos/2310642/pexels-photo-2310642.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
  height="527"
  :gradient="gradient"
  dark
  position-x
  position-y
  
  >
  <v-container grid-list-xl>
    <v-layout mt-4 align-space-between justify-space-between row fill-height>
      <v-flex xs4>
          <div class="mb-4 flex xs8 md12 ">
                <div class="font-weight-bold  yellow--text mb-4 display-1" >Who Im .</div>
                <div class="subheading white--text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque molestias veniam velit qui quasi, beatae amet reprehenderit non optio architecto, totam, expedita nostrum tempora. Aspernatur ut obcaecati nisi natus quaerat!</div>

                <v-responsive
                    align-center
                    justify-space-around
                    wrap
                    mt-4
                    >

                    <v-img>
                    <img
                        src="http://www.carmenrferro.com/wp-content/uploads/2014/01/images.jpeg"
                        alt="Teresita"
                        max-height="25"
                        width="180"
                        :gradient="gradient"
    dark
                    >
                    </v-img>

                </v-responsive>
            </div>   
      </v-flex>

      <v-flex xs3 mt-5 offset-sm1>
          <div class="xs6 md10 text-uppercase font-weight-medium pt-2 ml-2">
              <div class="yellow--text mb-3">Location : <span class="white--text text-capitalize">  Viña del mar</span></div> 
              <div class="yellow--text mb-3 " >Email : <span class="white--text text-lowercase">  teresita1852@gmail.com</span></div>
              <div class="yellow--text mb-3">Phone : <span class="white--text text-lowercase">  +56 953908406</span></div>
          </div>
      </v-flex>

      <v-flex xs5 offset-sm1>
          <div class="mb-2 text-xs-right">
            <div class="text-uppercase display-1 font-weight-bold white--text">front-end developer</div>
            <span class="yellow--text text-uppercase display-2 headline font-weight-light  text-xs-right">Teresita Madriaza</span>
            
                <v-layout
                    align-left
                    justify-space-around
                    wrap
                    mt-4
                    >

                    <v-img circle>
                    <img
                        src="https://cdn3.iconfinder.com/data/icons/business-round-flat-vol-1-1/36/user_account_profile_avatar_person_student_female-512.png"
                        alt="Teresita"
                        circle
                        max-height="60"
                        width="180"
                        
                    >
                    </v-img>
                </v-layout>
          </div>
      </v-flex>
    </v-layout>

    <template>
        <v-flex md6 offset-md4 mt-1>
            <v-layout>
                <div class="yellow--text">
                    <div class="font-weight-bold  yellow--text mb-4 display-1">What I can do for you ?</div>
                  
                    <v-expansion-panel >
                    <v-expansion-panel-content class="theme-dark">
                    <template v-slot:header>
                        <div class="title font-weight-light">Web Development</div>
                    </template>
                    <v-card>
                        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</v-card-text>
                    </v-card>
                    </v-expansion-panel-content>
                </v-expansion-panel>

                 <v-expansion-panel>
                    <v-expansion-panel-content>
                    <template v-slot:header>
                        <div class="title font-weight-light">Desing Graphic</div>
                    </template>
                    <v-card>
                        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</v-card-text>
                    </v-card>
                    </v-expansion-panel-content>
                </v-expansion-panel>

                 <v-expansion-panel>
                    <v-expansion-panel-content>
                    <template v-slot:header>
                        <div class="title font-weight-light">Branding</div>
                    </template>
                    <v-card>
                        <v-card-text>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</v-card-text>
                    </v-card>
                    </v-expansion-panel-content>
                </v-expansion-panel>
                    

                </div>

            </v-layout>
        </v-flex>
    </template>



  </v-container>
  </v-img>
</template>











<script>
export default {
   name: 'Biography'
}
</script>