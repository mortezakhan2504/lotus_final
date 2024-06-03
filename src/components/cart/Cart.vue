<script>

export default {
   props:['photobg', "header" , "text" , 'img']
}
</script>

<template>
    <div class="cartbox" :style=photobg>
    <div class='textbox'>
        <h1>{{header}}</h1>
        <p>{{text}}</p>
    </div>
    <div class="imagebox">
      <img :src=img />
    </div>
    </div>
</template>

<style>
    @import "./css/main.css";
</style>
