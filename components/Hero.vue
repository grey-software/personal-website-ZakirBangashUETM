<template>
  <section class="text-white body-font">
    <div
      class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
    >
      <div
        class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
      >
       <h1 class="heading">
                Greetings Everyone! <span class="wave">👋🏻</span>
              </h1>
               <h1 class="heading-name">
                I'M
                <strong class="main-name"> Zakir Ullah Bangash</strong>
              </h1>
        <!-- <h1
          class="title-font sm:text-4xl text-3xl mb-4 font-medium "
        >
          Before they sold out <br class="hidden lg:inline-block" />readymade
          gluten
        </h1> -->
        <p class="mb-8 leading-relaxed">
          Copper mug try-hard pitchfork pour-over freegan heirloom neutra air
          plant cold-pressed tacos poke beard tote bag. Heirloom echo park
          mlkshk tote bag selvage hot chicken authentic tumeric truffaut hexagon
          try-hard chambray.
        </p>
        <div class="flex justify-center">
          <button
            class="inline-flex text-white bg-green-500 border-0 py-2 px-6 focus:outline-none hover:bg-green-600 rounded text-lg"
          >
            Button
          </button>
          <button
            class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg"
          >
            Button
          </button>
        </div>
      </div>
      <div class="md:w-4/12  w-full">
        <img
          class="imag"
          alt="hero"
          src="~/assets/computer.svg"
        />
      </div>
    </div>
   
  </section>
</template>

<script>
export default {};
</script>

<style scooped>
.image {
  width: 70% !important;
  float: right;
}


section {
  position: relative;
  z-index: -1;

  background-image: linear-gradient(
      to bottom left,
      rgba(17, 16, 16, 0.678),
      rgba(12, 10, 22, 0.863)
    ),
    url("~assets/home-bg.jpg");
  object-fit: contain;
  background-position: top center;
  background-repeat: no-repeat;
  background-size: cover;
  padding-bottom: 30px !important;
  padding-top: 30px !important;
}

.wave {
  animation-name: wave-animation; /* Refers to the name of your @keyframes element below */
  animation-duration: 2.1s; /* Change to speed up or slow down */
  animation-iteration-count: infinite; /* Never stop waving :) */
  transform-origin: 70% 70%; /* Pivot around the bottom-left palm */
  display: inline-block;
}

@keyframes wave-animation {
  0% {
    transform: rotate(0deg);
  }
  10% {
    transform: rotate(14deg);
  } /* The following five values can be played with to make the waving more or less extreme */
  20% {
    transform: rotate(-8deg);
  }
  30% {
    transform: rotate(14deg);
  }
  40% {
    transform: rotate(-4deg);
  }
  50% {
    transform: rotate(10deg);
  }
  60% {
    transform: rotate(0deg);
  } /* Reset for the last half to pause */
  100% {
    transform: rotate(0deg);
  }
}

.heading {
  font-size: 2.4em !important;
  padding-left: 50px !important;
  padding-bottom: 15px;
}

.heading-name {
  font-size: 2.5em !important;
  padding-left: 45px !important;
}

.main-name {
  color: #cd5ff8;
}
</style>
