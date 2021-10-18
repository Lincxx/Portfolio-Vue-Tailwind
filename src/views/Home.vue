<template>
  <div>
      <NavBar />
      <div class="relative h-screen w-screen bg-cover bg-center shadow-2xl" :style="`background-image:url(${bgImage})`">
      <div class="h-screen w-screen bg-red-800 opacity-75"></div> 
      <div class="absolute h-screen w-screen top-0 flex flex-col items-center justify-center">
        <h1 class="text-6xl font-bold text-white p-4 hover:bg-white hover:text-red-800">Jeremy Lincoln</h1>
        <h3 class="text-2xl font-bold text-white px-4 hover:bg-white hover:text-red-800">Development Team Lead / Front End Developer</h3>
      </div>
      
      </div>    
  </div>
</template>

<script>
import NavBar from '../components/NavBar'
import bgImage from '../assets/bg.jpg'
export default {
  components: {
    NavBar,
  },
  name: 'Home',
  data() {
    return {
      bgImage
    }
  }
}
</script>
