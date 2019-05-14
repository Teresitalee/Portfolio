<template>
<v-container>
    <v-flex>
        <v-layout align-center justify-center row fill-height>
            <div class="mb-4">
                <h2>Get in touch</h2>
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