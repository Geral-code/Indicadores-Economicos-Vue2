<template>
<div>
   <Navbar/>
   <div class="container mt-5">
       <slot/>

   </div>
</div>
  
</template>

<script>
import Navbar from '../components/Navbar.vue';
export default {
    components: {
        Navbar
    }

}
</script>

<style>

</style>