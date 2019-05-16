<template>
<v-container mt-5>
    <v-flex xs4 md6>
        
        <v-layout align-center justify-center row fill-height>
            <div class="mb-4">
                <h1 display-1  class="font-weight-bold font-italic pink--text" >Let´s talk.</h1>
                <h4 class="subheading">Lorem ipsum dolor sit amet consectetur adipisicing elit. Atque molestias veniam velit qui quasi, beatae amet reprehenderit non optio architecto, totam, expedita nostrum tempora. Aspernatur ut obcaecati nisi natus quaerat!</h4>
            </div>
        </v-layout>
           <Social />  
    </v-flex>
    <Form />
  
</v-container>
  
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