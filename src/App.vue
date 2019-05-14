<template>
  <v-app>
     <v-toolbar app class="pink">
      <v-toolbar-title class="font-weight-thin white--text" >Teresita Madriaza</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-sm-and-down" >
        <v-btn flat>Home</v-btn>
        <v-btn flat>About</v-btn>
        <v-btn flat>Portfolio</v-btn>
        <v-btn flat>Skills</v-btn>
        <v-btn flat>Contact</v-btn>
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
