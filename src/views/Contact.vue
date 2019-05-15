<template>
<v-container mt-5>
    <v-flex>
        <v-layout align-center justify-center row fill-height>
            <div class="mb-4">
                <h1>Get in touch</h1>
            </div>
        </v-layout>
    </v-flex>
    <Form />  
</v-container>
  
</template>

<script>

     import Form  from "@/components/Form.vue";

    export default {
        components:{
            Form
        }
    }
</script>