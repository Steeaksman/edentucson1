<template>
    <!-- <div class="flex flex-col items-center p-8 h-screen
    ">
       
      <h1> 
        This is the index page 
        It calls donny.ts on the server using the useFetch composable   
        The  server returns a json datatype
    </h1> -->

<!-- DISPLAY THE  returned DATA FROM THE SERVER CALL -->
<!-- <ul>
  <li>
    <img :src="scizor.sprite"/>
  </li>
  <li>
    {{ scizor.id }}: {{ scizor.name }}
  </li>
  </ul> -->
<!-- {{ data }}
    
    
<UButton color ="red" to="/vidtest5">Lingus by Snarky Puppy</UButton>
<UButton color ="blue" to="/vidtest6">Bearologist</UButton>

</div> -->

<section class="hero bg-cover bg-center h-screen flex items-center justify-center" style="background-image: url('/img/hero_2.jpg')">




</section >



  </template>


  <script setup>
  
  //CALL THE ENDPOINT ON THE SERVER with the UseFetch composable 
  const { data} = await useFetch(
    '/api/donny'
  )
</script>
  