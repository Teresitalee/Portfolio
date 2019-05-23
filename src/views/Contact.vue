<template>
<v-img
  src="https://images.pexels.com/photos/2310642/pexels-photo-2310642.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
  height="727"
  :gradient="gradient"
  dark
  position-x
  position-y
  
  >
<v-container mt-5>
    <v-flex xs4 md6>
        
        <v-layout align-center justify-center row fill-height>
            <div class="mb-4">
                <h1 display-1  class="font-weight-bold font-italic yellow--text" >Let´s talk.</h1>
                <h4 class="subheading white--text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque molestias veniam velit qui quasi, beatae amet reprehenderit non optio architecto, totam, expedita nostrum tempora. Aspernatur ut obcaecati nisi natus quaerat!</h4>
            </div>
        </v-layout>
           <Social />  
    </v-flex>
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