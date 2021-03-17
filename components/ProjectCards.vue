<template>
    <div class="projectCard">
        <img src="~/assets/corona.jpg" alt="">
        <div class="projectCard__body">
            <h1>Covid 19 Tracker</h1>
            <p>This is small project developed with React and Chart.js</p>
                  <div class="flex py-5 justify-center">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">
            <font-awesome-icon :icon="['fas', 'externallink']"  />View Project
            <i class="fas fa-external-link-alt"></i>
        </button>
        
      </div>

        </div>
    </div>
    
</template>

<script>
export default {
    
}
</script>

<style scoped>
.projectCard {
    box-shadow: 0 4px 5px 3px rgba(119, 53, 136, 0.459) !important;
  color: white !important;
  background-color: transparent !important;
  opacity: 0.9 !important;
  transition: all 0.5s ease 0s !important;
  height: 100% !important;
}

.projectCard > img {
    padding: 20px;
    object-fit: contain;
    width: 100%;
    border-radius: 10%;
    display: flex  !important;
    justify-content: center  !important;
    align-items: center !important;
    margin-left: auto;
    margin-right: auto;
}

.projectCard:hover {
     transform: scale(1.02) !important;
  overflow: hidden !important;
  box-shadow: 0 4px 4px 5px rgba(129, 72, 144, 0.561) !important;
}

.projectCard__body {
    text-align: center;
    font-weight: 500;
    padding-bottom: 40px;
}

.projectCard__body > h1 {
    font-size: 2.1em;
}




</style>