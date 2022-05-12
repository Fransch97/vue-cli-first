<template>
  <div class="jambo">
    <div class="overlay">
      <h1 id="jumbi">{{msg}}</h1>
    </div>
  </div>
</template>

<script>
export default {
    name: "MyHero",
    props:{
      msg: String
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
    display: flex;
    align-items: center;
    justify-content: center;
  }
  .overlay h1{
    color: white;
    text-transform: uppercase;
    font-weight: bold;
    display: inline-block;
    position: absolute;
    font-size: 5vw;
  }
</style>