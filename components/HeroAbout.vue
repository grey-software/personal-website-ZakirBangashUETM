<template>
  <div class="heroAbout">
    <div class="hero__about__section" id="about">
      <div class="hero__about__description">
        <h1>LET ME <span class="purple"> INTRODUCE </span> MYSELF</h1>
        <p class="hero__about__body">
          I fell in love with programming and I have at least learnt something,
          I think… 🤷‍♂️
          <br />
          <br />I am fluent in classics like
          <i>
            <b class="purple"> C, C++ and Javascript. </b>
          </i>
          <br />
          <br />
          My current focus is on &nbsp;
          <i>
            <b class="purple">
              Open Source Products
            </b>
          </i>
          <br />
          <br />
          <!-- Whenever possible, I also apply my passion for developing products
          with
          <i>
            <b class="purple"> Modern Javascript Frameworks</b>
          </i> -->
          <!-- &nbsp; like
          <i>
            <b class="purple"> Node.js and React.js</b>
          </i> -->
        </p>
      </div>
      <div class="hero__about__right">
        <!-- <Tilt> -->
        <img src="~/assets/avatar.svg" class="img" alt="avatar" />
      </div>
    </div>

    <div class="hero__about__social">
      <h1>FIND ME ON</h1>
      <p>Feel free to <span class="purple">connect </span>with me</p>

      <div class="hero__social-links">
        <div class="social-icons">
          <a
            href="https://github.com/ZakirBangash"
            target="_blank"
            rel="noreferrer"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather feather-github"
            >
              <path
                d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"
              ></path>
            </svg>
          </a>
        </div>

        <div class="social-icons">
          <a
            href="https://www.linkedin.com/in/zakir-bangash-6b33a0199/"
            target="_blank"
            rel="noreferrer"
          >
            <svg fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5 feather" viewBox="0 0 24 24">
            <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"></path>
            <circle cx="4" cy="4" r="2" stroke="none"></circle>
          </svg>
          </a>
        </div>

        <div class="social-icons">
          <a href="" target="_blank" rel="noreferrer" class="home-social-icons">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather"
            >
              <path
                d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
              />
            </svg>
          </a>
        </div>

        <div class="social-icons">
          <a
            href="https://gitlab.com/ZakirBangash"
            target="_blank"
            rel="noreferrer"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="24"
              height="24"
              viewBox="0 0 24 24"
              fill="none"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              class="feather"
            >
              <path
                d="M22.65 14.39L12 22.13 1.35 14.39a.84.84 0 0 1-.3-.94l1.22-3.78 2.44-7.51A.42.42 0 0 1 4.82 2a.43.43 0 0 1 .58 0 .42.42 0 0 1 .11.18l2.44 7.49h8.1l2.44-7.51A.42.42 0 0 1 18.6 2a.43.43 0 0 1 .58 0 .42.42 0 0 1 .11.18l2.44 7.51L23 13.45a.84.84 0 0 1-.35.94z"
              ></path>
            </svg>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// tyle={{ fontSize: "2.6em" }}
export default {};
</script>

<style scoped>
.heroAbout {
  position: relative;
  background-color: #161125;
  padding-bottom: 70px !important;
  padding-top: 70px !important;
}

.hero__about__section {
  display: grid;
  grid-template-columns: auto auto auto;
  grid-gap: 100px;
  color: white;
  padding: 10px 130px;
}

.hero__about__description {
  color: white !important;
  padding-top: 100px !important;
  padding-bottom: 70px !important;
  text-align: center;
  grid-column: 1 / span 2;
}

.hero__about__right {
  padding-top: 100px !important;
  padding-bottom: 70px !important;
  text-align: center;
  display: flex;
  align-items: center;
}
.purple {
  color: #c770f0;
}

.hero__about__description > h1 {
  font-size: 2.6em;
  font-weight: 600;
}

.hero__about__body {
  padding-top: 50px;
  font-size: 1.2em !important;
  text-align: left !important;
}

@media screen and (max-width: 768px) {
  .hero__about__section {
    background-color: #161125;
    display: grid;
    position: relative;
    grid-template-columns: auto;
    width: 100% !important;
    color: white;
    padding: 10px 24px !important;
  }

  .img {
    position: absolute;
    top: 85%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
}

.hero__about__social {
  text-align: center !important;
  padding-top: 25px;
  color: white !important;
}

.hero__about__social > h1 {
  font-size: 2.5em;
  margin-bottom: 0.5rem;
  font-weight: 500;
  line-height: 1.2;
}

.hero__social-links {
  display: flex !important;
  align-items: center;
  justify-content: center;
  padding-top: 15px !important;
}

.social-icons {
  width: 40px !important;
  height: 40px !important;
  margin-right: 10px;
  display: flex !important;
  justify-content: center !important;
  align-items: center !important;
  background: rgba(255, 255, 255, 0.972) !important;
  border-radius: 50% !important;
  transition: 0.5s !important;
}



.feather {
  color: #87209e;
}

.feather:hover {
  color: white;
}


.social-icons:hover {
  background-color: #87209e !important;
  color:white !important;
  box-shadow: 0 0 5px #87209e;
  text-shadow: 0 0 2px #87209e;
}


</style>