<template>
<v-img
  src="https://images.pexels.com/photos/2310642/pexels-photo-2310642.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
  height="727"
  dark
  position-x
  position-y
  
  >
<v-container grid-list-md mt-5>
    <v-layout row wrap>
        <v-flex xs6>
            <div class="mb-4 flex xs8 md12 ">
                <div class="font-weight-bold  yellow--text mb-4 display-1" >Let´s talk .</div>
                <div class="subheading white--text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque molestias veniam velit qui quasi, beatae amet reprehenderit non optio architecto, totam, expedita nostrum tempora. Aspernatur ut obcaecati nisi natus quaerat!</div>
            </div>
        </v-flex>

        <v-flex xs6>
            <div class="mb-4 flex xs8 md12 right">
                <div class="font-weight-bold  yellow--text mb-4 display-1" >Social Icons .</div>
               <v-flex xs12 mt-2 text-md-center>
                    <div class="xs12 md8 text-uppercase font-weight-medium pt-2 ml-2">
                        <div>
                             <v-btn outline large fab color="yellow"  >
                                <v-icon dark color="white" class=" text-xs-center " >call</v-icon>
                                </v-btn>
                                <span class=" subheading white--text text-capitalize font-italic" href="https://www.emol.com/">  +56 953908406</span>
                        </div>
                        <div>
                             <v-btn outline large fab color="yellow"   >
                                <v-icon dark color="white" class=" text-xs-center " >mail_outline</v-icon>
                                </v-btn>
                                <span class=" subheading white--text text-capitalize font-italic" href="https://www.emol.com/">  teresita1852@gmail.com</span>
                        </div>
                        <div>
                            <v-btn outline large fab color="yellow" >
                                <v-icon dark color="white" class=" text-xs-center " >share</v-icon>
                            </v-btn>
                            <span class="subheading white--text text-capitalize font-italic" href="https://www.emol.com/">  mi cv (compartelo)</span>
                        </div>





                        
                    </div>
                </v-flex>
                
            </div>
        </v-flex>
    </v-layout>
    <Form />
  
</v-container>
</v-img>
</template>

<script>

     import Form  from "@/components/Form.vue";
     import Social  from "@/components/Social.vue"

    export default {
        components:{
            Form,
            Social
        }
    }
</script>