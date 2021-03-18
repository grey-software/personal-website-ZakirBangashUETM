<template>
  <section class=" about relative pt-40 pb-8 bg-gray-900 text-white pl-32">
    <div class="container mx-auto flex px-5 md:flex-row flex-col items-center">
      <div class="about__left">
        <h1 class="text-center pb-5 pt-1">Know Who <strong class="purple">I'M</strong></h1>
    
          <blockquote>
            <p>
              Hi Everyone, I am
              <span class="purple">Zakir Ullah Bangash </span> from
              <span class="purple"> Kp, Pakistan.</span> <br />
              I am Student of BSc Software Engineering at UET Mardan.
              <br />
              <br />

              Apart from coding, some other activities that I love to do!
            </p>

            <div>
              <span class="about__icon"
                ><font-awesome-icon :icon="['fa', 'hand-point-right']"
              /></span>
              Playing Games
            </div>
            <div>
              <span class="about__icon"
                ><font-awesome-icon :icon="['fa', 'hand-point-right']"
              /></span>
              Watching Pakistani Dramas
            </div>
            <div>
              <span class="about__icon"
                ><font-awesome-icon :icon="['fa', 'hand-point-right']"
              /></span>
              Travelling
            </div>
          </blockquote>
      </div>

      <div class="about__right">
        <img class="about__right__image" src="~/assets/about.png" alt="" />
      </div>
    </div>
    <h1 class="about__techStack">
      TECH <strong class="purple">STACK </strong>
    </h1>

  

    <div class="about__tech__icons">
      <div class="icons hover:bg-purple-700">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M3 3h18v18H3V3m4.73 15.04c.4.85 1.19 1.55 2.54 1.55c1.5 0 2.53-.8 2.53-2.55v-5.78h-1.7V17c0 .86-.35 1.08-.9 1.08c-.58 0-.82-.4-1.09-.87l-1.38.83m5.98-.18c.5.98 1.51 1.73 3.09 1.73c1.6 0 2.8-.83 2.8-2.36c0-1.41-.81-2.04-2.25-2.66l-.42-.18c-.73-.31-1.04-.52-1.04-1.02c0-.41.31-.73.81-.73c.48 0 .8.21 1.09.73l1.31-.87c-.55-.96-1.33-1.33-2.4-1.33c-1.51 0-2.48.96-2.48 2.23c0 1.38.81 2.03 2.03 2.55l.42.18c.78.34 1.24.55 1.24 1.13c0 .48-.45.83-1.15.83c-.83 0-1.31-.43-1.67-1.03l-1.38.8z"
            fill="#626262"
          />
        </svg>
      </div>

      <div class="icons">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M12 1.85c-.27 0-.55.07-.78.2l-7.44 4.3c-.48.28-.78.8-.78 1.36v8.58c0 .56.3 1.08.78 1.36l1.95 1.12c.95.46 1.27.47 1.71.47c1.4 0 2.21-.85 2.21-2.33V8.44c0-.12-.1-.22-.22-.22H8.5c-.13 0-.23.1-.23.22v8.47c0 .66-.68 1.31-1.77.76L4.45 16.5a.26.26 0 0 1-.11-.21V7.71c0-.09.04-.17.11-.21l7.44-4.29c.06-.04.16-.04.22 0l7.44 4.29c.07.04.11.12.11.21v8.58c0 .08-.04.16-.11.21l-7.44 4.29c-.06.04-.16.04-.23 0L10 19.65c-.08-.03-.16-.04-.21-.01c-.53.3-.63.36-1.12.51c-.12.04-.31.11.07.32l2.48 1.47c.24.14.5.21.78.21s.54-.07.78-.21l7.44-4.29c.48-.28.78-.8.78-1.36V7.71c0-.56-.3-1.08-.78-1.36l-7.44-4.3c-.23-.13-.5-.2-.78-.2M14 8c-2.12 0-3.39.89-3.39 2.39c0 1.61 1.26 2.08 3.3 2.28c2.43.24 2.62.6 2.62 1.08c0 .83-.67 1.18-2.23 1.18c-1.98 0-2.4-.49-2.55-1.47a.226.226 0 0 0-.22-.18h-.96c-.12 0-.21.09-.21.22c0 1.24.68 2.74 3.94 2.74c2.35 0 3.7-.93 3.7-2.55c0-1.61-1.08-2.03-3.37-2.34c-2.31-.3-2.54-.46-2.54-1c0-.45.2-1.05 1.91-1.05c1.5 0 2.09.33 2.32 1.36c.02.1.11.17.21.17h.97c.05 0 .11-.02.15-.07c.04-.04.07-.1.05-.16C17.56 8.82 16.38 8 14 8z"
            fill="#626262"
          />
        </svg>
      </div>

      <div class="icons">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M12 10.11c1.03 0 1.87.84 1.87 1.89c0 1-.84 1.85-1.87 1.85c-1.03 0-1.87-.85-1.87-1.85c0-1.05.84-1.89 1.87-1.89M7.37 20c.63.38 2.01-.2 3.6-1.7c-.52-.59-1.03-1.23-1.51-1.9a22.7 22.7 0 0 1-2.4-.36c-.51 2.14-.32 3.61.31 3.96m.71-5.74l-.29-.51c-.11.29-.22.58-.29.86c.27.06.57.11.88.16l-.3-.51m6.54-.76l.81-1.5l-.81-1.5c-.3-.53-.62-1-.91-1.47C13.17 9 12.6 9 12 9c-.6 0-1.17 0-1.71.03c-.29.47-.61.94-.91 1.47L8.57 12l.81 1.5c.3.53.62 1 .91 1.47c.54.03 1.11.03 1.71.03c.6 0 1.17 0 1.71-.03c.29-.47.61-.94.91-1.47M12 6.78c-.19.22-.39.45-.59.72h1.18c-.2-.27-.4-.5-.59-.72m0 10.44c.19-.22.39-.45.59-.72h-1.18c.2.27.4.5.59.72M16.62 4c-.62-.38-2 .2-3.59 1.7c.52.59 1.03 1.23 1.51 1.9c.82.08 1.63.2 2.4.36c.51-2.14.32-3.61-.32-3.96m-.7 5.74l.29.51c.11-.29.22-.58.29-.86c-.27-.06-.57-.11-.88-.16l.3.51m1.45-7.05c1.47.84 1.63 3.05 1.01 5.63c2.54.75 4.37 1.99 4.37 3.68c0 1.69-1.83 2.93-4.37 3.68c.62 2.58.46 4.79-1.01 5.63c-1.46.84-3.45-.12-5.37-1.95c-1.92 1.83-3.91 2.79-5.38 1.95c-1.46-.84-1.62-3.05-1-5.63c-2.54-.75-4.37-1.99-4.37-3.68c0-1.69 1.83-2.93 4.37-3.68c-.62-2.58-.46-4.79 1-5.63c1.47-.84 3.46.12 5.38 1.95c1.92-1.83 3.91-2.79 5.37-1.95M17.08 12c.34.75.64 1.5.89 2.26c2.1-.63 3.28-1.53 3.28-2.26c0-.73-1.18-1.63-3.28-2.26c-.25.76-.55 1.51-.89 2.26M6.92 12c-.34-.75-.64-1.5-.89-2.26c-2.1.63-3.28 1.53-3.28 2.26c0 .73 1.18 1.63 3.28 2.26c.25-.76.55-1.51.89-2.26m9 2.26l-.3.51c.31-.05.61-.1.88-.16c-.07-.28-.18-.57-.29-.86l-.29.51m-2.89 4.04c1.59 1.5 2.97 2.08 3.59 1.7c.64-.35.83-1.82.32-3.96c-.77.16-1.58.28-2.4.36c-.48.67-.99 1.31-1.51 1.9M8.08 9.74l.3-.51c-.31.05-.61.1-.88.16c.07.28.18.57.29.86l.29-.51m2.89-4.04C9.38 4.2 8 3.62 7.37 4c-.63.35-.82 1.82-.31 3.96a22.7 22.7 0 0 1 2.4-.36c.48-.67.99-1.31 1.51-1.9z"
            fill="#626262"
          />
        </svg>
      </div>

      <div class="icons">
          <svg class="sv" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" focusable="false" width="1em" height="1em" style="-ms-transform: rotate(360deg); -webkit-transform: rotate(360deg); transform: rotate(360deg);" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path d="M20 18.69l-7.3 4.05c-.5.26-1 .26-1.5 0L4 18.69L17.05 5.54l.35-.1c.3 0 .47.13.5.4L20 18.69M9.35 5.74L4.8 13.29L6.7 1.34c.03-.27.2-.4.5-.4c.2 0 .33.06.4.25l2.15 3.95l-.4.6M13.85 7L4.3 16.59l7.25-12.3c.1-.2.25-.29.45-.29s.33.09.4.29L13.85 7z" fill="#626262"/></svg>
      </div>

      <div class="icons">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M2 3h3.5L12 15l6.5-12H22L12 21L2 3m4.5 0h3L12 7.58L14.5 3h3L12 13.08L6.5 3z"
            fill="#626262"
          />
        </svg>
      </div>
      <div class="icons">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M21.8 18.36L16.03 8.08c-.1-.08-.4-.65-1-.65c-.25 0-.6.1-.96.65l-.74 1.18l-2.02-3.61c-.05-.1-.4-.65-1-.65c-.25 0-.65.1-.95.65L2.18 18.31c-.05.1-.35.69-.05 1.19c.1.25.4.5 1.06.5h17.66c.1 0 .75 0 1.05-.5c.1-.24.2-.64-.1-1.14m-13.7-.05l-.15.55H3.24l7.12-12.52l2.3 4.13l-4.56 7.84m1.11.55l4.11-7.2l4.18 7.2H9.21m9.53 0l-.2-.55L14 10.46l1.03-1.73l5.72 10.13h-2.01z"
            fill="#626262"
          />
        </svg>
      </div>

      <div class="icons">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M12 17.56l4.07-1.13l.55-6.1H9.38L9.2 8.3h7.6l.2-1.99H7l.56 6.01h6.89l-.23 2.58l-2.22.6l-2.22-.6l-.14-1.66h-2l.29 3.19L12 17.56M4.07 3h15.86L18.5 19.2L12 21l-6.5-1.8L4.07 3z"
            fill="#626262"
          />
        </svg>
      </div>

      <div class="icons ">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M5 3l-.65 3.34h13.59L17.5 8.5H3.92l-.66 3.33h13.59l-.76 3.81l-5.48 1.81l-4.75-1.81l.33-1.64H2.85l-.79 4l7.85 3l9.05-3l1.2-6.03l.24-1.21L21.94 3H5z"
            fill="#626262"
          />
        </svg>
      </div>
       <div class="icons">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M8 16.61v-1.24l6-3.46V7.23l-5 2.89l-5-2.89V13l-1 .58L2 13V5l1.07-.62L9 7.81l3.93-2.27l2-1.16L16 5v8.06L10.92 16l4.05 2.33l5.03-2.9V11l1-.58l1 .58v5.58l-7.03 4.06L8 16.61m14-6.86l-1 .58l-1-.58V8.58L21 8l1 .58v1.17z"
            fill="#626262"
          />
        </svg>
      </div>

      <div class="icons">
        <svg
          class="sv"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          aria-hidden="true"
          focusable="false"
          width="1em"
          height="1em"
          style="
            -ms-transform: rotate(360deg);
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
          "
          preserveAspectRatio="xMidYMid meet"
          viewBox="0 0 24 24"
        >
          <path
            d="M11.79 11.5H9.72V8.19h2.47c1.26 0 1.96.56 1.96 1.59c0 1.12-.83 1.72-2.36 1.72m.37 1.13H9.72v3.64h2.56c1.56 0 2.38-.63 2.38-1.83s-.85-1.81-2.5-1.81M22 5.31v13.38C22 20.5 20.5 22 18.69 22H5.31C3.5 22 2 20.5 2 18.69V5.31C2 3.5 3.5 2 5.31 2h13.38C20.5 2 22 3.5 22 5.31m-6 9.19c0-1.38-.92-2.37-2.33-2.55v-.06c1-.18 1.79-1.18 1.79-2.26c0-1.55-1.2-2.58-2.96-2.58H8.43v10.36h4.04c2.21 0 3.53-1.09 3.53-2.91z"
            fill="#626262"
          />
        </svg>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>


<style scoped>


.about {
  position: relative !important;
  padding-top: 150px !important;
  padding-bottom: 30px !important;
  background: #130f1a;
  color: white !important;
  padding-left: 120px;
}

@media screen and (max-width: 768px) {
  .about {
    padding-left: 0;
  }
}

.about__left {
  flex: 0.6 !important;
  padding-top: 20px;
  padding-bottom: 50px;
}

.purple {
  color: #c770f0;
}

.about__left > h1 {
  font-size: 2.1em !important;
}

.about__icon {
  margin-right: 10px;
}

.about__right {
  flex: 0.3;
}

.about__right__image {
  width: 100% !important;
}


.about__techStack {
  color: white !important;
  font-size: 2.3em !important;
  font-weight: 500 !important;
  padding: 10px 0 !important;
   margin-left: 430px; 
  
}

@media screen and (max-width:768px) {
    .about__techStack {
        margin-left: 0;
        text-align: center;
    }
}

.about__tech__icons {
 display: flex;
 justify-content: center;
 flex-wrap: wrap;
 margin-right: 140px;
}


@media (max-width: 767px) {
  .about__tech__icons {
    margin: 10px !important;
  }
}

.sv {
 
  padding: 20px !important;
  line-height: 1.6 !important;
}

.icons {
      width: 100px;
      height: 100px;
      font-size: 5.5em !important;
      margin: 15px !important;
      border: 1.7px solid rgba(200, 137, 230, 0.637) !important;
      border-radius: 5px !important;
      box-shadow: 4px 5px 4px 3px rgba(89, 4, 168, 0.137) !important;
      transition: all 0.4s ease 0s !important;
}

.icons:hover {
  transform: scale(1.05) !important;
  overflow: hidden  !important;
  border: 2.2px solid rgba(197, 115, 230, 0.883) !important;
}





</style>