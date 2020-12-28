<template>
   
    <nav>
      
        <v-card
    color="grey lighten-4"
    flat
    height="100px"
   
    tile
  >
    <v-toolbar dense pt-10>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title class="text-uppercase black--text ">
                    <span class="font-weight-light">Recipie</span>
                    <span>Books</span>
                    
                </v-toolbar-title>
                <v-spacer></v-spacer>
                 <v-toolbar-title >
                    
                    <span>Search</span>
                    
                </v-toolbar-title>
   
                <v-autocomplete
      v-model="select"
      :loading="loading"
      :items="items"
      :search-input.sync="search"
      cache-items
      class="mx-4"
      flat
      hide-no-data
      hide-details
      label="Find a Recipie"
      solo-inverted
    >
    
    </v-autocomplete>
    <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
   
      <v-spacer></v-spacer>

      <div class="text-center">
          <v-menu offset-y>
            <template v-slot:activator="{ on,attrs }">
              <v-btn text color="black" v-bind="attrs" v-on="on">
                
                <v-icon left small>mdi-account-group-outline</v-icon>
                <span>Menu</span>
                <v-icon>mdi-menu-down</v-icon>
                
              </v-btn>


            </template>

            <v-list>
              <v-list-item v-for="link in links" :key="link.text" router :to="link.route">
                <v-list-item-title>{{ link.text }}</v-list-item-title>
              </v-list-item>
            </v-list>
          </v-menu>
        </div>

      
    
      <span><small>Login</small></span>
      <v-spacer></v-spacer>
      <h5 class="m-5 ">Get All Recipies<br><div class="text-center"> Magazines</div></h5>
    </v-toolbar>

  

    

  </v-card>
       
    </nav>

   
   
</template>

<script>
export default {
    data(){
        return{
            drawer: false,
            links:[
                { icon: 'mdi-home', text: 'Dashboard', route: '/'},
                { icon: 'mdi-folder', text: 'My project', route: '/projects'},
                { icon: 'mdi-account', text: 'Team', route: '/team'},
            ]
        }
    }   
}
</script>
<style>

</style>
