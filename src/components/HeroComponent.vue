<template>
  <div class="jumbotron">
     <div class="hero-text">Viaggio a Londra i miss u </div>
  </div>
</template>


<script>
export default {
  name: 'HeroComponent',
}


</script>

<style>
.jumbotron{
    height:600px;
    background-image:url(https://images.musement.com/cover/0002/49/london-jpeg_header-148518.jpeg?w=1200&h=630&q=95&fit=crop);
    background-repeat:no-repeat;
    background-size: cover;
    background-position: center;
    position:relative;
}

.hero-text{
    position:absolute;
    bottom:20px;
    right:0;
    font-size:2rem;
    background-color:#ffffffa3;
    padding:1rem;
}

</style>