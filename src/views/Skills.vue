<template>
    <v-container>
        <v-flex>
            <v-layout align-center justify-center row fill-height>
                <h2>Mis Conocimientos</h2>
            </v-layout>
        </v-flex>
          <Progress />  
    </v-container>

  
</template>

<script>
import Progress  from "@/components/Progress.vue";

    export default {
        components:{
            Progress
        }
    }


</script>