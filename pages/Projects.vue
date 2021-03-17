<template>
    <section>
        <div class="projects">
            <h1 class="projects__heading">
                A meager sort of <strong class="purple">Contribution</strong>  to Github
            </h1>
            <p>Here are a few projects that i worked as a beginner</p>
        </div>

        <div class="flex flex-wrap">
        <div class="project__card">
             <ProjectCards />
        </div>

        <div class="project__card">
             <ProjectCards />
        </div>

        <div class="project__card">
             <ProjectCards />
        </div>

        <div class="project__card">
             <ProjectCards />
        </div>
        </div>
       

    </section>



</template>

<script>
export default {
    
}
</script>

<style scoped>
section {
    background-color: #100D19;
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
.purple {
  color: #c770f0;
}

.project__card {

     padding-top: 50px !important;
  padding-bottom: 50px !important;
  padding-left: 25px !important;
  padding-right: 25px !important;
  min-width: 80% !important;
  width: 30%;
  display: flex  !important;
  margin-left: auto;
  margin-right: auto;
  height: auto !important;
}

</style>