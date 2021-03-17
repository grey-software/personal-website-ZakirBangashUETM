<template>
  <section class="text-white body-font">
    <div
      class="home-section container mx-auto flex px-5 py-24 md:flex-row flex-col items-center"
    >
      <div
        class="home-header lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
      >
        <h1 class="heading">
          Greetings Everyone! <span class="wave">👋🏻</span>
        </h1>
        <h1 class="heading-name">
          I'M
          <strong class="main-name"> Zakir Ullah Bangash</strong>
        </h1>

        <div class="type">
          <vue-typer
            :text="[
              'I am React Developer',
              'I am Software Engineer',
              'I am Deep learning learner',
              'I am a Sharp learner',
            ]"
            :repeat="Infinity"
            :shuffle="false"
            initial-action="typing"
            :pre-type-delay="200"
            :type-delay="70"
            :pre-erase-delay="1000"
            :erase-delay="50"
            erase-style="backspace"
            :erase-on-complete="true"
            :caret-animation="blink"
          ></vue-typer>
        </div>
      </div>
      <div class="image md:w-5/12 w-full">
        <img  alt="hero" src="~/assets/computer.svg" />
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scooped>
.home-section {
  padding: 9rem 0 2rem !important;
  color: whitesmoke;
  text-align: left;
}

.home-header {
  height: 453px !important;
}
.type {
  padding: 50px;
  text-align: left;
  width: 100% !important;
}
.image {
  width: 40% !important;
  
}

.image > img {
  margin-top: -150px;
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
  background-position: top center;
  background-repeat: no-repeat;
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

.vue-typer {
  font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
}
.vue-typer .custom.char.typed {
  font-size: 2.2em !important;
  color: #be6adf !important;
  font-weight: 600 !important;
}

@media screen and (max-width: 767px) {
  .vue-typer .custom.char.typed {
    font-size: 1.4em !important;
    font-weight: 500 !important;
  }
  .Typewriter__cursor {
    display: none !important;
  }
  .image {
    width: 80% !important;
    margin-top: -80px !important;
  }
  .image > img {
  margin-top: 0px;
}
}
</style>
