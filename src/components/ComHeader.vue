<template>
        <header>
            <h1>{{msg}} </h1>
        </header>
</template>
  

<script>
export default {
    name : 'ComHeader',
    props:{
    msg : String
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
header{
  background-color: black ;
  color: white;
  padding: 20px;
  text-align: center;
  font-weight: bold;
  text-transform: uppercase;
  font-size: 20px;
}

</style>