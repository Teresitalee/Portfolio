<template>
  <v-container grid-list-md >
     <v-layout row align-space-between justify-space-around  fill-height  >
       <v-flex  xs4>
         <form>
            <v-text-field
              v-model="name"
              :error-messages="nameErrors"
              :counter="10"
              label="Name"
              required
              @input="$v.name.$touch()"
              @blur="$v.name.$touch()"
            ></v-text-field>
            <v-text-field
              v-model="email"
              :error-messages="emailErrors"
              label="E-mail"
              required
              @input="$v.email.$touch()"
              @blur="$v.email.$touch()"
            ></v-text-field>
            <v-select
              v-model="select"
              :items="items"
              :error-messages="selectErrors"
              label="Item"
              required
              @change="$v.select.$touch()"
              @blur="$v.select.$touch()"
            ></v-select>
            <v-checkbox
              v-model="checkbox"
              :error-messages="checkboxErrors"
              label="Do you agree?"
              required
              @change="$v.checkbox.$touch()"
              @blur="$v.checkbox.$touch()"
            ></v-checkbox>

            <v-btn @click="submit">submit</v-btn>
            <v-btn @click="clear">clear</v-btn>
  </form>
        


      </v-flex>

      <v-flex  row xs8 >
        <div class="right">
          <v-responsive
                   
                    
                    >
                    <v-img 
                     height="300"
                     width="550"
                     :src="require('@/assets/pic1.png')"
                    >
                    </v-img>
                </v-responsive>
          </div>  
    </v-flex>

       </v-layout>   
  </v-container>
</template>

<script>
export default {
    name: 'Form'
}

</script>



