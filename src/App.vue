<template>
  <v-app>
     <v-toolbar app class="black">
      <v-toolbar-title class="font-weight-thin white--text" >Teresita Madriaza</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down" >
        <v-btn flat class="pink--text">Home</v-btn>
        <v-btn flat class="pink--text">About</v-btn>
        <v-btn flat class="pink--text">Portfolio</v-btn>
        <v-btn flat class="pink--text">Skills</v-btn>
        <v-btn flat class="pink--text">Contact</v-btn>
      </v-toolbar-items>    
  </v-toolbar>

    <v-content>
        <router-view/>
    </v-content>
  </v-app>    
</template>

<script>

export default {
  name: 'App',
  data () {
    return {
      //
    }
  }
}
</script>
