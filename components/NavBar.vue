<template>

 <header class="navbar ">
  <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
    <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
     
      <span class="ml-3 text-xl text-white">ZB</span>
    </a>
    <nav class=" md:mx-auto flex flex-wrap justify-center ml-6">
       <NuxtLink class="mr-10 " to="/">Home</NuxtLink>
    
      <NuxtLink  class="mr-10 " to="/about">
          About
      </NuxtLink>

        <NuxtLink  class="mr-10 " to="/projects">
          Projects
      </NuxtLink>
     
    </nav>
    <!-- <button class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0">Button
      <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
        <path d="M5 12h14M12 5l7 7-7 7"></path>
      </svg>
    </button> -->
  </div>
</header>
</template>

<script>
console.log("akddkj");
export default {};
</script>

<style scooped>



nav > a {
  
  font-weight: 500;
  margin-right: 50px !important;
  font-size: 20px;
 


}

nav > a::after {
   content: "";
  position: relative;
  display: block;
  height: 5px;
  width: 0;
  border-radius: 16px;
  background: #c95bf5;
  bottom: 1px;
  left: 0;
  z-index: -1;
  transition: all 0.3s ease-out 0s;
}

nav > a:hover {
  cursor: pointer;
}

nav > a:hover::after {
  width: 100%;
}



.navbar {
  position: fixed !important;
  
  z-index: 999;
  /* padding: 0.3rem 2rem !important; */
  color: white;
  width: 100%;
  font-size: 1.2rem !important;

   /* background-color: #212038d8 !important; */
  transition: all 0.3s ease-out 0s !important;
  box-shadow: 0px 10px 10px 0px rgba(9, 5, 29, 0.171) !important;
  backdrop-filter: blur(15px) !important;

}



  
</style>
