<template>
    <div class="projectCard">
        <img :src="require(`~/assets/${img}`)" alt="">
        <div class="projectCard__body">
            <h1>{{title}}</h1>
            <p>{{description}}</p>
                  <div class="flex py-5 justify-center">
                      <a :href="url">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">
            View Project
        </button>
        </a>
      </div>

        </div>
    </div>
    
</template>

<script>
export default {
    props:['img','title','description','url'],
    
}
</script>

<style scoped>
.projectCard {
    /* width: 30% !important; */
    width: 350px  !important;
    height: 500px  !important;
  box-shadow: 0 4px 5px 3px rgba(119, 53, 136, 0.459) !important;
  /* margin: 10px auto  !important; */
  color: white !important;

  background-color: transparent !important;
  opacity: 0.9 !important;
  transition: all 0.5s ease 0s !important;
  
}

@media  screen and (max-width:576px) {
    .projectCard{
    width: 300px  !important;
    }
}

@media screen and (max-width:280px) {
    .projectCard {
        width:180px !important;
    }
}

.projectCard > img {
    padding: 20px;
    object-fit: contain;
    width: 100%;
    border-radius: 15%;
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