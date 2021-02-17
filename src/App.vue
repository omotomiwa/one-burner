<template>

  <div id="app">
    <div id="nav">
      <ul>
     <li><router-link to="/">Home</router-link> </li>
     <li> <router-link to="/about">About</router-link> </li>
     <li> <router-link to="/contact">Contact</router-link></li>
      </ul>
    </div>
    <router-view/>
    
    <footer>© Copyright 2021</footer>
    
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  padding: 0;
  margin:0;

}
#nav{
  text-align: center;
  width: 100%;
  height: 70px;
  min-height: 70px;
  padding-top: 30px;
  background: #35424a;
  color: #ffffff;
  border-bottom: #e8491d 3px solid;
}

#nav a{
  color: #ffffff;
  text-decoration: none;
  text-transform:uppercase;
  font-size: 12px;
}

#nav ul{
  margin: 0;
  padding: 0;
}

#nav li{
  display: inline;
  padding: 0 20px 0 20px;
}
#nav a:hover{
  color: #e8491d;
  font-weight: bold;
}


footer{
  width: 100%;
  height: 70px;
  background-color:#111;
  text-align: center;
  color: #ffffff;
  font-size: 20px;
  padding-top: 20px;
}



</style>
