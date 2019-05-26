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
                <div class="text-xs-center">
                <v-btn  outline large fab color="yellow" text-md-center>
                <v-icon dark color="white">call</v-icon>
                </v-btn>
                <v-btn  outline large fab color="yellow">
                <v-icon dark color="white" class="text-sm-center" >mail_outline</v-icon>
                </v-btn >
                <v-btn  outline large fab color="yellow">
                <v-icon dark color="white" class="text-xs-center">share</v-icon>
                </v-btn>
                

                </div>

                
                
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