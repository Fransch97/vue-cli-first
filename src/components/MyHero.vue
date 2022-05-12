<template>
  <div class="jambo">
    <div class="overlay">
      <h1 id="left">{{left}}</h1>
      <h1 id="right">{{right}}</h1>
    </div>
  </div>
</template>

<script>
export default {
    name: "MyHero",
    props:{
      left: String,
      right: String
    }
}
</script>

<style>
*{
  font-family: sans-serif;
}
 .jambo{
    border-radius: 20px;
    width: 60vw;
    height: 60vh;
    margin: 30px auto;
    background-image: url('https://blastmagazine.com/wp-content/uploads/2012/07/707-hermes-dummy.jpg?is-pending-load=1');
    background-size: cover;
    background-position: center ;
    overflow: hidden;
  }
  
  img{
    border-radius: 20px;
    width: 100%;
    opacity: 1;
  }
  .overlay{
    background: rgba(0, 0, 0, 0.218);
    width: 100%;
    height: 100%;
    position: relative;
  }
  .overlay h1{
    color: white;
    text-transform: uppercase;
    font-weight: bold;
    width: 100%;
    font-size: 5vw;
    color: rgb(255, 225, 0);
    position: absolute;
    text-shadow: 0px 20px 10px black;
  }
  #left{
    top: 30%;
    left: 30%;
  }
  #right{
    bottom: 30%;
    left: 40%;
  }
</style>