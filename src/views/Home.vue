<template>
  <div>
    <div class="main">
      <div class="frameContainer">
        <div class="frame1">frame1</div>
        <div class="frame4">frame2</div>
        <div class="frame3">frame3</div>
        <div class="frame2">frame4</div>
      </div>
    </div>
  </div>
</template>
<style >
body{
  height: 100%;
}
.main {
  width: 100%;
  height: 100vh; 
  background-color: rgba(8, 7, 7, 0.959);
  background-size: cover;
  background-position: center;
}
.frameContainer{
 display: grid;
  grid-template-columns: 25rem 25rem;
  grid-template-rows: 15rem  15rem; 
  column-gap: 40px;
  row-gap: 40px;
  padding: 40px;
  justify-content: center;
}
.frame1:hover{
  width: 26rem;
  height: 16rem;
  background: linear-gradient(rgb(47,150,163), rgb(48, 62, 143));
  border-radius: 5px;
  box-shadow:rgb(47,150,163);
  cursor: pointer;
}

.frame2:hover{
  width: 26rem;
  height: 16rem;
  border-radius: 5px;
  background-color: #F0FFF0;
   box-shadow:   inset  0 -7px 9px -7px black;
   cursor: pointer;

}

.frame3:hover{
  width: 26rem;
  height: 16rem;
  border-radius: 5px;
  background-color: #A9A9A9	;
  box-shadow:   inset  0 -7px 9px -7px #696969;
  cursor: pointer;
}
.frame4:hover{
   width: 26rem;
  height: 16rem;
  border-radius: 5px;
  background-color:#000033;
  box-shadow:   inset  0 -7px 9px -7px #0000FF;
  cursor: pointer;

}

.frame1{
  
  background: linear-gradient(rgb(47,150,163), rgb(48, 62, 143));
  border-radius: 5px;
  box-shadow:rgb(47,150,163)
}


.frame2{

  border-radius: 5px;
  background-color: #F0FFF0;
   box-shadow:   inset  0 -7px 9px -7px black;
}
.frame3{
  
  border-radius: 5px;
  background-color: #A9A9A9	;
  box-shadow:   inset  0 -7px 9px -7px #696969;
}

.frame4{
 
  border-radius: 5px;
  background-color:#000033;
  box-shadow:   inset  0 -7px 9px -7px #0000FF;
}


.repo{
  text-align: center;
  justify-content: center;
  
}
.resume{
  text-align: center;
  justify-content: center;
}


/* ----------- iPhone 5, 5S, 5C and 5SE ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 320px) 
  and (max-device-width: 568px)
  and (-webkit-min-device-pixel-ratio: 2) {

    .frameContainer{
  display: grid;
  grid-template-columns: 9rem 9rem;
  grid-template-rows: 9rem  9rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 50px;
  justify-content: center;
}

}

/* ----------- iPhone 6, 6S, 7 and 8 ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 375px) 
  and (max-device-width: 667px) 
  and (-webkit-min-device-pixel-ratio: 2) { 

  .frameContainer{
  display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 50px;
  justify-content: center;
}


}

/* ----------- iPhone 6+, 7+ and 8+ ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 414px) 
  and (max-device-width: 736px) 
  and (-webkit-min-device-pixel-ratio: 3) { 

.frameContainer{
 display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 50px;
  justify-content: center;
}

}

/* ----------- iPhone X ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 375px) 
  and (max-device-width: 812px) 
  and (-webkit-min-device-pixel-ratio: 3) { 

    .frameContainer{
 display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 50px;
  justify-content: center;
}

}


/* ----------- Galaxy S4, S5 and Note 3 ----------- */

/* Portrait and Landscape */
@media screen 
  and (device-width: 320px) 
  and (device-height: 640px) 
  and (-webkit-device-pixel-ratio: 3) {

       .frameContainer{
 display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 5px;
  row-gap: 5px;
  padding: 50px;
  justify-content: center;
}
   

}

/* ----------- Galaxy S6 ----------- */

/* Portrait and Landscape */
@media screen 
  and (device-width: 360px) 
  and (device-height: 640px) 
  and (-webkit-device-pixel-ratio: 4) {

         .frameContainer{
 display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 50px;
  justify-content: center;
}

}
/* -----------google pixel------ */
/* Portrait and Landscape */
@media screen 
  and (device-width: 360px) 
  and (device-height: 640px) 
  and (-webkit-device-pixel-ratio: 3) {
 
          .frameContainer{
 display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 50px;
  justify-content: center;
}

}

/* ----------- Google Pixel XL and S5 ----------- */

/* Portrait and Landscape */
@media screen 
  and (device-width: 360px) 
  and (device-height: 640px) 
  and (-webkit-device-pixel-ratio: 4) {

           .frameContainer{
 display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 20rem;
  justify-content: center;
}

}

/* ----------- iPad 1, 2, Mini and Air ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 768px) 
  and (max-device-width: 1024px) 
  and (-webkit-min-device-pixel-ratio: 1) {
              .frameContainer{
 display: grid;
  grid-template-columns: 20rem 20rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 30px;
  row-gap: 30px;
  padding: 20rem;
  justify-content: center;
}

}

/* ----------- iPad 3, 4 and Pro 9.7" ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 768px) 
  and (max-device-width: 1024px) 
  and (-webkit-min-device-pixel-ratio: 2) {
                
                 .frameContainer{
 display: grid;
  grid-template-columns: 20rem 20rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 60px;
  row-gap: 60px;
  padding: 20rem;
  justify-content: center;
}

}

/* ----------- iPad Pro 10.5" ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 834px) 
  and (max-device-width: 1112px)
  and (-webkit-min-device-pixel-ratio: 2) {

                    .frameContainer{
 display: grid;
  grid-template-columns: 20rem 20rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 60px;
  row-gap: 60px;
  padding: 20rem;
  justify-content: center;
}

}

/* ----------- iPad Pro 12.9" ----------- */

/* Portrait and Landscape */
@media only screen 
  and (min-device-width: 1024px) 
  and (max-device-width: 1366px)
  and (-webkit-min-device-pixel-ratio: 2) {

                       .frameContainer{
 display: grid;
  grid-template-columns: 20rem 20rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 60px;
  row-gap: 60px;
  padding: 50rem;
  justify-content: center;
}

}

/* ----------- Galaxy Tab S ----------- */

/* Portrait and Landscape */
@media 
  (min-device-width: 800px) 
  and (max-device-width: 1280px)
  and (-webkit-min-device-pixel-ratio: 2) {

                          .frameContainer{
 display: grid;
  grid-template-columns: 10rem 10rem;
  grid-template-rows: 10rem  10rem; 
  column-gap: 10px;
  row-gap: 10px;
  padding: 50px;
  justify-content: center;
}

}








</style>

<script>
export default {
  name: "Home",
};
</script>
