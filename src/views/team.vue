<template>
<div class="about-selection">

           <!---section--->
           <v-container
    class="my-6"
    fluid
    
    align="center"
  >
    <v-fade-transition mode="out-in">
      <v-row dense>
        <div class="col-md-6 mb-4">
          <v-card ml-5
          :loading="loading"
  
           >
            <v-img
             src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F6837830.jpg&w=574&h=384&c=sc&poi=face&q=85"
              height="400"
              class="grey darken-4"
            ></v-img>
            <v-card-title>
Instant Pot® Basic Cabbage Rolls</v-card-title>

    <v-card-text>
      <v-row
        
        class="mx-0"
      >
        <v-rating
          :value="4.5"
          color="amber"
          dense
          half-increments
          readonly
          size="14"
        ></v-rating>

        <div class="grey--text ml-4">
          70
        </div>
      </v-row>

      <div class="black--text my-4 ">
        <span class="font-weight-light"> By </span>

            <span class="font-weight-bold"> bbypookins </span>
         
      </div>

      
    </v-card-text>

          </v-card>
        </div>

        <div class="col-md-6 mb-12">
          <v-card
          :loading="loading"
  
          width="300" >
            <v-img
              src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F8120851.jpg&w=272&h=272&c=sc&poi=face&q=85"
              height="380"
              
              class="grey darken-4"
            ></v-img>
             <v-card-title>Peanut Blossoms ||</v-card-title>

    <v-card-text>
      <v-row

        
        class="mx-0"
      >
        <v-rating
          :value="5"
          color="amber"
          dense
          half-increments
          readonly
          size="14"
        ></v-rating>

        <div class="grey--text ml-4">
          492
        </div>
      </v-row>

      <div class="black--text my-4 ">
        <span class="font-weight-light"> A perennial favourite </span>
        <br>
        <span class="font-weight-light"> By </span>

            <span class="font-weight-bold"> <u>Rosemarie Magee</u> </span>
         
      </div>

      
    </v-card-text>

          </v-card>
        </div>
      </v-row>
    </v-fade-transition>
           </v-container>
           <!----section--->


<v-container class="my-6">
  <v-row dense>
    
 
    

   
    <v-container fluid>
      <v-row dense>
        
        <v-flex xs12 sm6 md4 lg3 
          v-for="card in cards"
          :key="card.title"
          :cols="card.flex"
    >
          <v-card  class="text-xs-center ma-3">
            <v-img
              :src="card.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="220px"
            >
              
            </v-img>
             
            <v-card-actions>
              
              <v-spacer></v-spacer>
              <v-card-text>
                <div class="subtitle">{{  card.subtitle }}</div>
                <div class="title black--text font-weight-bold">{{  card.title }}</div>
  
                   <v-rating
                      :value="4.5"
                       color="amber"
                       dense
          
                      half-increments
                      readonly
                      size="14"
                      ></v-rating>

              <div class="subheading">{{ card.name }}</div>
              <div class="black--text ">{{ card.role }}</div>
              

            </v-card-text>
            
      
        
             
            </v-card-actions>
          </v-card>
        </v-flex>
        
      </v-row>
    </v-container>
  
  </v-row>



</v-container>
  
    <footer class=" text-center text-lg-left" style="background-color: white;">
      <!-- Grid container -->
      <section class="text-center" id="skills">
        <v-row justify="center"
         mt-5>
    <v-img  
       max-height="80"
      max-width="200"
      src="https://www.allrecipes.com/img/misc/og-default.png" 
      ></v-img>

     
    </v-row>
        <div class="row">
          <div class="col-lg-6 col-md-4">
            <i class="fas fa-cubes fa-3x " style="color: #481449;"></i>
            <h3 class="my-4">Magazines & More</h3>
            
          </div>
          <div class="col-lg-6 col-md-4">
            <i class="fas fa-sitemap fa-3x" style="color: #dd4b39;"></i>
            <h3 class="my-4">Learn More</h3>
            <p class="mb-md-3">
              Subscribe
            </p>
            <p class="mb-md-3">
              Customer Service
            </p>
            <p class="mb-md-3">
              Jobs
            </p>
            <p class="mb-md-3">
              Advertise
            </p>
            <p class="mb-md-3">
              Content Licensing
            </p>
            <p class="mb-md-3">
              Apps
            </p>
            <p class="mb-md-3">
              Sitemap
            </p>
          </div>
          <div class="col-lg-6 col-md-4">
            <i class="fas fa-graduation-cap fa-3x" style="color:#0082ca;"></i>
            <h3 class="my-4">Connect</h3>
            <span><small>Follow Us</small></span>
            <br>

             <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-2"
          dark
          icon
          color="green"
        >
          <v-icon size="18px">
            {{ icon }}
          </v-icon>
        </v-btn>
        <br>
            <v-btn
              class="ma-2"
               outlined 
             color="red black--text"
             >
            Global comunities
           

            </v-btn>
            <br>
            <br>
            <v-spacer></v-spacer>
            <span><small>Subscribe to Our Newsletter</small></span>
             <br>
             <v-btn depressed color="green uppercase white--text "> Sign Up </v-btn>
          </div>
          
          
        </div>
      </section>
      <!-- Grid container -->

      <!-- Copyright -->
       <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">

         <v-btn
              class="ma-2"
               outlined 
             color="red black--text"
             >
            OTHER MERIDITE SIDES 
           

            </v-btn>
            <v-spacer></v-spacer>
            <v-row justify="center"
         mt-5>
         
    <v-img  
       max-height="40"
      max-width="100"
      
      src="https://mma.prnewswire.com/media/655329/Meredith_Corporation_Logo.jpg?p=facebook" 
      ></v-img>
         
     
    </v-row>
    <br>
      <small> All recipes is part of the Meredith Food Group. © Copyright 2020 Meredith Corporationthis link opens in a new tab. All Rights Reserved.</small>
      <v-row
      justify="center"
     
    >
      <v-btn
        color="black"
        text
        rounded
        class="my-2"
      >
        <a href="#"><small>Privacy Policy</small></a>
      </v-btn>
       <v-btn
        color="black"
        text
        rounded
        class="my-2"
      >
        <a href="#"><small>Terms of Service</small></a>
      </v-btn>
       <v-btn
        color="black"
        text
        rounded
        class="my-2"
      >
        <a href="#"><small>Ad Choice</small></a>
      </v-btn>

       <v-btn
        color="black"
        text
        rounded
        class="my-2"
      >
        <a href="#"><small>Web Accessibility</small></a>
      </v-btn>
    </v-row>    
     
      </div>
      <!-- Copyright -->
    </footer>
  
</div>
</template>

<script>
  export default {
    data: () => ({
      cards: [
        { 
          subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F4401056.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F5899234.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F8509919.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
          { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVAEgflAwiZx400ccjGvnf9yN8HOHgbwTDeg&usqp=CAU",
            
            flex: 6 
            },
         { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F587542.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
         { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F12%2F04%2F3013176_original.jpg&q=85",
            
            flex: 6 
            }, 
        
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F2883617.jpg&w=272&h=272&c=sc&poi=face&q=85",
           
            flex: 6 
            },     
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F8042446.jpg&w=272&h=272&c=sc&poi=face&q=85",
           
            flex: 6 
            },     
            
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F01%2Fimage-4.jpg&q=85",
            
            flex: 6 
            }, 
          
            

      ],

links: [
        'Home',
        'About Us',
        'Team',
        'Services',
        'Blog',
        'Contact Us',
      ],

    }),
  }
</script>