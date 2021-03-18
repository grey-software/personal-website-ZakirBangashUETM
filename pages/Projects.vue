<template>
  <section>
    <div class="projects">
      <h1 class="projects__heading">
        A meager sort of <strong class="purple">Contribution</strong> to Github
      </h1>
      <p>Here are a few projects that i worked as a beginner</p>
    </div>

    <div class="flexing">
      <div
        class="project__card"
        v-for="project in projectsInfo"
        :key="project.id"
      >
        <ProjectCards
          :img="project.img"
          :title="project.title"
          :description="project.description"
          :url="project.url"
        />
      </div>
    </div>
  </section>
</template>

<script>
import { Pr } from "~/assets/data.js";
export default {
  data() {
    return {
      projectsInfo: Pr,
    };
  },
};
</script>

<style scoped>
.flexing {
  display: flex !important;
  flex-wrap: wrap !important;
  justify-content: center !important;
}
section {
  background-color: #100d19;
  color: white;
  position: relative !important;
  padding-top: 150px !important;
  padding-bottom: 30px !important;
}

.projects {
  text-align: center;
}
.projects__heading {
  text-align: center;
  color: white !important;
  font-size: 2.3em !important;
  font-weight: 500 !important;
  padding-top: 10px !important;
}

@media screen and (max-width: 768px) {
  .projects__heading {
    font-size: 1.8em !important;
  }
}

.purple {
  color: #c770f0;
}

.project__card {
  padding-top: 50px !important;
  padding-bottom: 50px !important;
  padding-left: 25px !important;
  padding-right: 25px !important;
}
</style>