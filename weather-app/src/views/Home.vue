<template>
<div id="app">
<div id="nav">
<h1>Weather</h1>

<input type="text" class="search-bar">
<br>
<br>

<button class="button">Search</button> 
</div>
<br>
<br>
<div class="weather">
<div class="card">
  
  <div class="container">
    <h1><b>28.3 C</b></h1>
  </div>
</div>
<span>
    Humidity  &nbsp;  Dew Point
    <br>
   <b> 81.9%     &nbsp;  24.9 C </b>
</span>
</div>

</div>

</template>

<style scoped>
.search-bar{
    color: white;
    width: 100%;
    height:30px;
    border:none;
    font-size: 30px;
    border-bottom: 2px solid white;
}
input.search-bar:focus{
   outline-width: 0;
}
.button{
    width:90px;
    height: 50px;
    color:white;
    border:2px solid white;
    border-radius: 2%;
    background:#2A2441;
}
button.button:focus{
   outline-width: 0;
}
.card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width:20%;
  height: 100px;
  background: #9933ff;
    display: flex;
    align-items:center;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}
.weather {
            display: flex;
            align-items: center;
        }
           
        span {
            padding: 10px;
        }
</style>

<script>
export default {
    
}
</script>