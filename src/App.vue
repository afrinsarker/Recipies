<template>
  <v-app class="grey lighten-4">
    <Navbar />
    
    <v-content class="mx-5 mb-5">
      <router-view></router-view>
    </v-content>


   <v-footer app>
    <!-- -->
  </v-footer>
</v-app>
  
</template>

<script>
import Navbar from '@/components/Navbar'

export default {
  name: 'App',

  components: { Navbar },

  data () {

     return {

    }
    
  }
}
</script>
