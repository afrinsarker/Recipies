<template>
<div >


  
  

  <section class="text-center" id="about">
        <h1 class="my-5">
          <strong>Our Complete Collection of Christmas Desserts</strong>
        </h1>
  <div class="row">
          <div class="col-md-6 mb-4">
            <div class=image>
      <v-img
      src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F7008429.jpg&w=288&h=161&c=sc&poi=face&q=85"
      height="400px"
      
    ></v-img>
      
      <h1 class="heading"><a href="#">More Ham Leftovers Recipes</a></h1>
      <p class="para">From Yule logs to cookies, find festive desserts to celebrate the season.</p>
    
      </div>

          </div>
          <div class="col-md-6 mb-4">
            <!-- First row -->
            <div class="col-md-8 mb-8">
                      <div class="img">
        <div class="pic1"
              >
       
    <br>
    <h4><a href="#">Our Complete Collection of Christmas Desserts</a></h4>
     <br>
        </div>
                      </div>
    <div class="pic2">
    <v-img class="pa-md-4" 
      src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F29555.jpg&w=288&h=161&c=sc&poi=face&q=85"
      
      height="250px"
    ></v-img>
    <br>
    <h4><a href="#">Beef Tenderloin Recipes</a>
     </h4>
    </div>
        
            </div>
            <!-- Third row -->
          </div>
        </div>
  </section>

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
            
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F4728363.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F7687229.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F4536012.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
          { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F1028943.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
         { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F817225.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
         { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F6559810.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            }, 
        
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F1192753.jpg&w=272&h=272&c=sc&poi=face&q=85",
           
            flex: 6 
            },     
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F400591.jpg&w=272&h=272&c=sc&poi=face&q=85",
           
            flex: 6 
            },     
            
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F774534.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            }, 
          
            

      ],
       
    
    

    }),
  }
</script>