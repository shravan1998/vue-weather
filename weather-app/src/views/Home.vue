<template>
<div id="app">
<div id="nav">
<h1>Weather</h1>

<input type="text" class="search-bar">
<br>
<br>

<button class="button">Search</button> 
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

}
button.button:focus{
   outline-width: 0;
}
</style>

<script>
export default {
    
}
</script>