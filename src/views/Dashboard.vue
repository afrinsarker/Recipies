<template>
<div class="about-selection">

  <div class="row">
          <div class="col-md-6 mb-4">
            <div class=image>
      <v-img
      src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F3023127.jpg&q=85"
      height="500px"
      
    ></v-img>
      
      <h1 class="heading"><a href="projects">Our Complete Collection of Christmas Desserts</a></h1>
      <p class="para">From Yule logs to cookies, find festive desserts to celebrate the season.</p>
    
      </div>

          </div>
          <div class="col-md-6 mb-4">
            <!-- First row -->
            <div class="col-md-8 mb-8">
                      <div class="img">
        <div class="pic1"
              >
        <v-img
      src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F967420.jpg"
      
      height="250px"
      
    ></v-img>
    <br>
    <h4><a href="projects">Our Complete Collection of Christmas Desserts</a></h4>
     <br>
        </div>
                      </div>
    <div class="pic2">
    <v-img class="pa-md-4" 
      src="https://c8.alamy.com/comp/HK112K/tasty-juicy-roast-pork-tenderloin-and-fresh-vegetables-on-an-old-table-HK112K.jpg"
      
      height="250px"
    ></v-img>
    <br>
    <h4><a href="projects">Beef Tenderloin Recipes</a>
     </h4>
    </div>
        
            </div>
            <!-- Third row -->
          </div>
        </div>

           <!---section--->
           <v-container
    class="my-6"
    fluid
    style="min-height: 434px"
    align="center"
  >
    <v-fade-transition mode="out-in">
      <v-row dense>
        <v-col cols="6">
          <v-card ml-5
          :loading="loading"
  
          width="950"  >
            <v-img
             src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F8713926.jpg"
              height="400"
              class="grey darken-4"
            ></v-img>
            <v-card-title><a href="team">Kim's Lasagna</a></v-card-title>

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
        </v-col>

        <v-col cols="6">
          <v-card
          :loading="loading"
  
          width="300" >
            <v-img
              src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F3210842.jpg"
              height="380"
              
              class="grey darken-4"
            ></v-img>
             <v-card-title><a href="team">Peanut Blossoms ||</a></v-card-title>

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
        </v-col>
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
                <div class="title black--text font-weight-bold"><a href="#">{{  card.title }}</a></div>
  
                   <v-rating
                      :value="4.5"
                       color="amber"
                       dense
          
                      half-increments
                      readonly
                      size="14"
                      ></v-rating>

              <div class="subheading">{{ card.name }}</div>
              <div class="black--text "><a href="#" class="black--text ">{{ card.role }}</a></div>
              

            </v-card-text>
            
      
        
             
            </v-card-actions>
          </v-card>
        </v-flex>
        
      </v-row>
    </v-container>
 

  </v-row>



</v-container>

<v-parallax
    height="300"
    src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F11%2F23%2FChristmas-cookies-banner-3.jpg"
  >
  </v-parallax>
  


 <v-container class="my-6">
  <v-row dense>
    
    <v-container fluid>
      <v-row dense>
        
        <v-flex xs12 sm6 md4 lg3 
          v-for="item in items"
          :key="item.title"
          :cols="item.flex"
    >
          <v-card  class="text-xs-center ma-3"
                   >
            <v-img
              :src="item.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="220px"
            >
              
            </v-img>
             
            <v-card-actions>
              
              <v-spacer></v-spacer>
              <v-card-text>
                
                <div class="title black--text font-weight-bold"><a href="projects">{{  item.title }}</a></div>
  
                   
           <v-rating
               :value="4.5"
                background-color="orange lighten-3"
                color="orange"
                dense
                half-increments
                readonly
                size="16"
             ></v-rating>
           
             <!--- <div class="rating">{{ item.rating }}</div>--->
              <div class="subheading">{{ item.describe }}</div>
              <div class="black--text ">{{ item.role }}</div>
              
            </v-card-text>
            
      
        
             
            </v-card-actions>
          </v-card>
        </v-flex>
        
      </v-row>
     
    </v-container>
  
  </v-row>



</v-container>
 <!---complete--->


<v-container fluid>
     <v-row>
    <v-col
      cols="6"
      sm="4"
      
    >
      <v-card flat
          :loading="loading"
         
         
  
     >
            <v-img
              src="https://img-global.cpcdn.com/recipes/f15236db3c69698d3c2b524af20e68f09a357b949f87a56587c25c0f2614c2d3/751x532cq70/novoghodnieie-piechienie-%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D0%BD%D0%BE%D0%B5-%D1%84%D0%BE%D1%82%D0%BE-%D1%80%D0%B5%D1%86%D0%B5%D0%BF%D1%82%D0%B0.jpg"
              height="250"
              class="grey darken-4"
            ></v-img>
             

      
      <v-card-title> Christmas Dessert Recipes</v-card-title>
      <v-card-text>
      <div class="text--primary">
         Find the best Christmas desserts this baking season. Allrecipes has more than 1,470 trusted Christmas dessert recipes from 
         
      </div>

      </v-card-text>
           <div class="text-center">
    <v-btn
      class="ma-2"
      outlined
      color="indigo"
    >
     <a href="#" >view all</a>
    </v-btn>
           </div>

          </v-card>
    </v-col>

    <v-col
      cols="6"
      sm="4"
      
    >
      <v-card flat
          :loading="loading"
         
         
  
     >
            <v-img
              src="https://media.gettyimages.com/photos/three-cocktails-at-outdoor-bar-picture-id154894193"
              height="250"
              class="grey darken-4"
            ></v-img>
             

      
      <v-card-title> Christmas Dessert Recipes</v-card-title>
      <v-card-text>
      <div class="text--primary">
         Find the best Christmas desserts this baking season. Allrecipes has more than 1,470 trusted Christmas dessert recipes from 
         
      </div>

      </v-card-text>
           <div class="text-center">
    <v-btn
      class="ma-2"
      outlined
      color="indigo"
    >
     <a href="#"> view all</a>
    </v-btn>
           </div>

          </v-card>
    </v-col>

    <v-col
      cols="6"
      sm="4"
      
    >
      <v-card flat
          :loading="loading"
         
         
  
     >
            <v-img
              src="https://soupism.files.wordpress.com/2018/04/fasolada.jpg?w=1200"
              height="250"
              class="grey darken-4"
            ></v-img>
             

      
      <v-card-title><a href="projects"> Christmas Dessert Recipes</a></v-card-title>
      <v-card-text>
      <div class="text--primary">
         Find the best Christmas desserts this baking season. Allrecipes has more than 1,470 trusted Christmas dessert recipes from 
         
      </div>

      </v-card-text>
           <div class="text-center">
    <v-btn
      class="ma-2"
      outlined
      color="indigo"
    >
      <a href="#"> view all</a>
    </v-btn>
           </div>

          </v-card>
    </v-col>
  </v-row>
    </v-container>

    <!--complete-->

    <v-container class="my-6">
  <v-row dense>
    
 
    

   
    <v-container fluid>
      <v-row dense>
        
        <v-flex xs12 sm6 md4 lg3 
          v-for="bard in bards"
          :key="bard.title"
          :cols="bard.flex"
    >
          <v-card  class="text-xs-center ma-3">
            <v-img
              :src="bard.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="220px"
            >
              
            </v-img>
             
            <v-card-actions>
              
              <v-spacer></v-spacer>
              <v-card-text>
                <div class="subtitle">{{  bard.subtitle }}</div>
                <div class="title black--text font-weight-bold"><a href="projects">{{  bard.title }}</a></div>
  
                   <v-rating
                      :value="4.5"
                       color="amber"
                       dense
          
                      half-increments
                      readonly
                      size="14"
                      ></v-rating>

              <div class="subheading">{{ bard.name }}</div>
              <div class="black--text ">{{ bard.role }}</div>
              

            </v-card-text>
            
      
        
             
            </v-card-actions>
          </v-card>
        </v-flex>
        
      </v-row>
    </v-container>


  </v-row>
  </v-container>

  <!----complete---->

  <v-row>
    
    <v-col
      cols="6"
      sm="3"

      
    >
      
            
             
     <v-btn
      class="ma-2"
      
      color="primary"
    >
     New collection
    </v-btn>
      
      <v-card-title><a href="team">15 New Year's Food Traditions</a></v-card-title>
      <v-card-text>
      <div class="text--primary">
        prime rib tends to steal the show.Cheeck out our menu suggestions for supporting characters.
         
      </div>

      </v-card-text>
           <div class="text-center">
    <v-btn
      class="ma-2"
      outlined
      color="indigo"
    >
      <a href="#">view all</a>
    </v-btn>
           </div>

         
    </v-col>
   

    <v-col
      cols="6"
      sm="3"
    >
       <v-card flat
          :loading="loading"
         
         
  
     >
            <v-img
              src="https://i.pinimg.com/originals/bf/9e/5f/bf9e5fc734b09918339d6f43e6fa1b26.jpg"
              height="300"
              class="grey darken-4"
            ></v-img>
             

      
      
          </v-card>
    </v-col>

    <v-col
      cols="6"
      sm="3"
    >
       <v-card flat
          :loading="loading"
         
         
  
     >
            <v-img
              src="https://www.canadianturkey.ca/media/homestyle-turkey-tourti%C3%A8re-L-web-final.jpg"
              height="300"
              class="grey darken-4"
            ></v-img>
             

      
      
          </v-card>
    </v-col>
    <v-col
      cols="6"
      sm="3"

    >
       <v-card flat
          :loading="loading"
         
         
  
     >
            <v-img
              src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F09%2F15%2FReal-Homemade-Tamales.jpg"
              height="300"
              class="grey darken-4"
            ></v-img>
             

      
    
          </v-card>
    </v-col>
  </v-row>

  <!----complete--->
  <!---newline--->
  <v-container class="my-6">
  <v-row dense>
    
    <v-container fluid>
      <v-row dense>
        
        <v-flex xs12 sm6 md4 lg3 
          v-for="bar in bars"
          :key="bar.title"
          :cols="bar.flex"
    >
          <v-card  class="text-xs-center ma-3">
            <v-img
              :src="bar.src"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="220px"
            >
              
            </v-img>
             
            <v-card-actions>
              
              <v-spacer></v-spacer>
              <v-card-text>
                
                <div class="subtitle">{{  bar.subtitle }}</div>
                <div class="title black--text font-weight-bold"><a href="projects">{{  bar.title }}</a></div>
  
                   
           <v-rating
               :value="4.5"
                background-color="orange lighten-3"
                color="orange"
                dense
                half-increments
                readonly
                size="16"
             ></v-rating>
           
             <!--- <div class="rating">{{ item.rating }}</div>--->
              <div class="subheading">{{ bar.describe }}</div>
              <div class="black--text ">{{ bar.role }}</div>
              
            </v-card-text>
            
      
        
             
            </v-card-actions>
          </v-card>
        </v-flex>
        
      </v-row>
     
    </v-container>
  
  </v-row>



</v-container>
  <!---newline--->

  
  


<section class="text-center" id="about">
        <h1 class="my-5">
          <strong>Gifts From Your Kitchen</strong>
        </h1>
  <div class="row">
          <div class="col-md-6 mb-4">
            <div class=image>
      <v-img
      src="https://www.julieseatsandtreats.com/wp-content/uploads/2017/10/Parmesan-Crusted-Tilapia-panko-1024x683.jpg"
      height="500px"
      
    ></v-img>
      
      <h1 class="heading"><a href="team">Our Complete Collection of Christmas Desserts</a></h1>
      <p class="para">From Yule logs to cookies, find festive desserts to celebrate the season.</p>
    
      </div>

          </div>
          <div class="col-md-6 mb-4">
            <!-- First row -->
            <div class="row">
              <div class="col-md-4 mb-4">
                <v-img
              src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2015%2F03%2F17%2F1158304-Ham-Cups-and-Eggs-230654-Kims-Cooking-Now-2000.jpg"
              height="120"
              class="grey darken-4"
            ></v-img>
              </div>
              <div class="col-md-6 mb-4">
                
                <p><a href="team">Our Top 20 Most Popular Homemade Christmas Candy Recipes</a></p>
              </div>
            </div>
            <!-- First row -->

            <!-- Second row -->
           
            <div class="row">
              <div class="col-md-4 mb-4" style="color: #c61118;">
               <v-img
              src="https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F1878913.jpg&q=85"
              height="100"
              class="grey darken-4"
            ></v-img>
              </div>
              <div class="col-md-6 mb-4">
                
                <p>10 Homemade Food Gifts</p>
              </div>

            </div>
            <!-- Second row -->

            <!-- Third row -->
            
           <div class="row">
              <div class="col-md-4 mb-4" style="color: #c61118;">
               <v-img
              src="https://ukcdn.ar-cdn.com/recipes/originals/8ca0568e-ac9d-4296-b3b6-f4a3a4422e32.jpg"
              height="100"
              class="grey darken-4"
            ></v-img>
              </div>
              <div class="col-md-6 mb-4">
                
                <p>15 Christmas Cookies That Won't Crumble In the Mail</p>
              </div>

            </div>

            <div class="row">
              <div class="col-md-4 mb-4" style="color: #c61118;">
               <v-img
              src="https://d1yfn1dfres2va.cloudfront.net/001/c0/c2/c0c27e3401dd776470a6d17efebf6b35_250x250.jpg"
              height="100"
              class="grey darken-4"
            ></v-img>
              </div>
              <div class="col-md-6 mb-4">
                
                <p>10 Tasty Cookie Mixes for Gift-Giving</p>
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
                <div class="title black--text font-weight-bold"><a href="projects">{{  card.title }}</a></div>
  
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
            
            src: "https://i.pinimg.com/474x/32/95/99/329599a3ad59eaba9936d3cd840a176f.jpg",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F756445.jpg&q=85",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F12%2F05%2F186125_original.jpg",
            
            flex: 6 
            },
          { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?q=85&c=sc&poi=face&url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F7557119.jpg",
            
            flex: 6 
            },
         { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://www.livewellbakeoften.com/wp-content/uploads/2020/01/Sugar-Cookie-Icing-8.jpg",
            
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
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F885601.jpg",
           
            flex: 6 
            },     
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://thedomesticrebel.com/wp-content/uploads/2015/12/GINGERBREAD-MOLASSES-COOKIES.jpg",
           
            flex: 6 
            },     
            
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F2192657.jpg",
            
            flex: 6 
            }, 
          
            

      ],
     bards: [
         { 
          subtitle: "BUTTERCREAM FROSTING", 
          title: "Quick and Almost-Professional Buttercream Icing",
           name: "After failing to find the perfect recipe for buttercream icing, I found one that worked for me and then added my ow",
            role: "By xoshadyxo",
            
            src: "https://ukcdn.ar-cdn.com/recipes/originals/c10c2451-743a-4496-b2e6-eb4c3431c03d.jpg",
            
            flex: 6 
            },
        { 
           subtitle: "BAKED ASPARAGUS", 
          title: "Oven-Roasted Asparagus",
           name: "Salty and savory, the roasting method kills the natural bitterness of asparagus.",
            role: "By swedishmilk",
            src: "https://i.pinimg.com/474x/0f/1c/ae/0f1caec072c036e24d02619b083aff07.jpg",
            
            flex: 6 
            },
        { 
           subtitle: "GERMAN RECIPES", 
          title: "Juicy Roasted Chicken",
           name: "My grandmother's recipe for roasted chicken. We are German and she used ",
            role: "By ROBINROCKINGBIRD",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F389250.jpg&q=85",
            
            flex: 6 
            },
          { 
           subtitle: "APPLE PIE", 
          title: "Apple Pie by Grandma Ople",
           name: "This was my grandmother's apple pie recipe. I have never seen another one quite like it. It will always be my favorite",
            role: "By Angie Gorkoff",
            src: "https://bloximages.chicago2.vip.townnews.com/nwitimes.com/content/tncms/assets/v3/editorial/c/6b/c6b56680-c85e-5e67-93f9-c903b3f3569f/555369c75585a.image.jpg?resize=1200%2C1200",
            
            flex: 6 
            },
         { 
           subtitle: "SWEET POTATO SIDE DISHES", 
          title: "Yummy Sweet Potato Casserole",
           name: "My family begs me to make this creamy baked dish every Thanksgiving and Christmas. What makes it so good is the",
            role: "By TINA B",
            src: "https://img.tebyan.net/big/1397/06/19166213601244211710115421621022021379184234.jpg?w=1200",
            
            flex: 6 
            },
         { 
           subtitle: "CHOCOLATE FUDGE", 
          title: "Fudge",
           name: "I double the recipe and put in a glass baking dish (9x13 inches). Nice for holidays . . . Keep it for a secret and",
            role: "By Dana",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F150611.jpg&q=85",
            
            flex: 6 
            }, 
        
        { 
           subtitle: "BUFFALO CHICKEN DIP", 
          title: "Buffalo Chicken Dip",
           name: "This tangy, creamy dip tastes just like Buffalo chicken wings. It's best served hot with crackers and celery sticks. Everyone loves the results!",
            role: "By NUNPUNCH",
            src: "https://i.pinimg.com/originals/70/b9/bb/70b9bb3657f03875d2ef3c89c3c62674.png",
           
            flex: 6 
            },     
        { 
           subtitle: "SUGAR COOKIES", 
          title: "Soft Christmas Cookies",
           name: "Soft cut out sugar cookie that I have used for years. I sprinkle with colored sugar before baking or you could also try icing them when cool.",
            role: "By Georgie Bowers",
            src: "https://images.media-allrecipes.com/userphotos/56142.jpg",
           
            flex: 6 
            },     
            
         { 
           subtitle: "PEANUT BUTTER FUDGE", 
          title: "Easiest Peanut Butter Fudge",
           name: "This is the best recipe for creamy and delicious peanut butter fudge I have ever used. It is great for sharing at work.",
            role: "By ANGIEH",
            src: "https://s3.us-east-2.amazonaws.com/pfimg1/001/cb/b9/cbb97c2413378a8d6f404f501e78b404_1000w.jpg",
            
            flex: 6 
            }, 
          
            

      ],

    icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ], 
   items: [

        { 
         
          title: "Air Fryer Roasted Chestnuts",
           describe: "I don't have a fireplace to roast my chestnuts. Using the air fryer and water is a perfec",
            role: "By Buckwheat Queen",
            
            src: "https://southmountaincreamery.com/wp-content/uploads/2018/11/fresh-chestnuts.png",
            
            flex: 6 
            },
        { 
           
          title: "Yellow Curry Fried Rice",
           describe: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By genalynne",
            src: "https://www.westviamidwest.com/wp-content/uploads/2017/08/moroccan-rice-pilaf-2_600-opt-480x360.jpg",
            
            flex: 6 
            },
        { 
            
          title: "Air Fryer Broiled Grapefruit",
           describe: "Warm and juicy grapefruit with a sweet crunchy topping.",
            role: "By France C",
            src: "https://images.media-allrecipes.com/userphotos/8079468.jpg",
            
            flex: 6 
            },
          { 
            
          title: "Terri's Spicy Vegetable Smoothie",
           describe: "This is so healthy and delicious, I could drink it every day. Compare to commercial vegetable juice; this h",
            role: "By Terri Myers",
            src: "https://vegnbake.com/wp-content/uploads/2020/10/122.jpg",
            
            flex: 6 
            },
         { 
            
          title: "Beef Barley Vegetable Soup",
           describe: "Slow cooker, hearty, easy. Serve with a hearty bread, and enjoy.",
            role: "By MARGOC",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F348836.jpg",
            
            flex: 6 
            },
         { 
            
          title: "Creamy Slow Cooker Steel-Cut Oats",
           describe: "Wake up to a delicious and filling breakfast of creamy steel-cut oats, cooked in the slow cooker with",
            role: "By russellbknox",
            src: "https://cdn.copymethat.com/media/orig_creamy_slow_cooker_steel_cut_oats_20201119134549260975xma1qh.jpg",
            
            flex: 6 
            }, 
        
        { 
            
          title: "Red Wine Hot Chocolate",
           describe: "Chocolate and red wine are two things that go so well together. Combining them on a cold winter night and toppi",
            role: "By Kim's Cooking Now",
            src: "https://images.media-allrecipes.com/userphotos/7248304.jpg",
           
            flex: 6 
            },     
        { 
           
          title: "Perfect Crab-Stuffed Mushrooms",
           describe: "These little goodies are the perfect addition to your next holiday gathering or even the perfect appetizer to serve",
            role: "By Lisa Felton Nash",
            src: "https://static.onecms.io/wp-content/uploads/sites/43/2020/07/07/perfect-crab-stuffed-mushrooms-2000.jpeg",
           
            flex: 6 
            },     
            
        { 
           
          title: "Rockin' Oysters Rockefeller",
           describe: "These little goodies are the perfect addition to your next holiday gatherin",
            role: "By Cassandra Kennedy",
            src: "https://media.gettyimages.com/photos/oysters-rockefeller-picture-id904257072?s=612x612",
            
            flex: 6 
            }, 
          
            

      ],
  bars: [
        { 
          subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            
            src: "https://i.pinimg.com/originals/6c/d2/42/6cd242efb97ee86c642ccbffa4cb54c8.jpg",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fimages.media-allrecipes.com%2Fuserphotos%2F4535940.jpg&q=85",
            
            flex: 6 
            },
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F06%2F19%2FEasy-Meatloaf.jpg",
            
            flex: 6 
            },
          { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F11%2F19%2F4589158_original-2000.jpg&w=272&h=272&c=sc&poi=face&q=85",
            
            flex: 6 
            },
         { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://i.pinimg.com/originals/b0/f9/4a/b0f94a854acf699ae8839aec06e1e58c.png",
            
            flex: 6 
            },
         { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://i.pinimg.com/originals/5e/ba/bc/5ebabcaafba73d2342e773c9a21a93f0.jpg",
            
            flex: 6 
            }, 
        
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://i.pinimg.com/originals/ce/1d/b2/ce1db2678f8558a3055ddb2ffd2f90fa.jpg",
           
            flex: 6 
            },     
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F43%2F2020%2F09%2F04%2FOven-Roasted-Turkey-Breast-2000.jpg",
           
            flex: 6 
            },     
            
        { 
           subtitle: "STUFFED MUSHROOMS", 
          title: "Mouth-Watering Stuffed Mushrooms",
           name: "These delicious mushrooms taste just like restaurant-style stuffed mushroo..",
            role: "By Angie Gorkoff",
            src: "https://images.media-allrecipes.com/userphotos/300x300/3875444.jpg",
            
            flex: 6 
            }, 
          
            

      ],   
    
    

    }),
  }
</script>