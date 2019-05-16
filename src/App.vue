<template>
  <v-app>
     <v-toolbar app class="black">
      <v-toolbar-title class="font-weight-thin white--text" >Resume Portfolio</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down" >
        <v-btn flat class="pink--text" to="/">Home</v-btn>
        <v-btn flat class="pink--text" to="/about">About</v-btn>
        <v-btn flat class="pink--text" to="/portfolio">Portfolio</v-btn>
        <v-btn flat class="pink--text" to="/skills">Skills</v-btn>
        <v-btn flat class="pink--text" to="/contact">Contact</v-btn>
      </v-toolbar-items>    
  </v-toolbar>

    <v-content>
        <router-view/>    
    </v-content>



    <v-footer
    dark
    height="auto"
  >
    <v-card
      class="flex"
      flat
      tile
    >
        <v-spacer></v-spacer>

      <v-card-actions class="grey darken-3 justify-center">
        &copy;2019 — <strong>Made with love</strong>
      </v-card-actions>
    </v-card>
  </v-footer>  
  </v-app>
   
</template>



<script>

export default {
  name: 'App',
  components: {
   
    
  }
  
}
</script>
