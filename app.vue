<template>
  <div>
    <!--NuxtRouteAnnouncer />
    <NuxtWelcome /-->
    

    <form  @submit="submit">
      Name
      <input type="text" name="name"/><br>
      Email
      <input type="email" name="name"/><br>

      <button type="submit" >Save</button>
    </form>


    
  </div>
</template>


<script setup>


  const submit = (e) => {
    e.preventDefault();
    console.log(e);
  }

</script>