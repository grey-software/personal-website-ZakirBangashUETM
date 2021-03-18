<template>
  <footer class="text-gray-600 body-font">
    <div class="footer__dev">
      <h3>Developed by ZakirBangash</h3>
    </div>
    <div class="footer__copyRight">
        <h3>Copyright © {{dataPicker}} ZB</h3>
    </div>
    <div class="footer__icons">
      <a href="https://pk.linkedin.com/in/zakir-bangash-6b33a0199">
    <span class="icon"><font-awesome-icon :icon="['fab', 'linkedin']"/></span>
    </a>
    <a href="https://www.facebook.com/zakir.bangash.16">
    <span class="icon"><font-awesome-icon :icon="['fab', 'facebook']"/></span>
    </a>
    <a href="https://www.github.com/zakirBangash">
    <span class="icon"><font-awesome-icon :icon="['fab', 'github']"/></span>
    </a>

    <a href="https://www.instagram.com/zakirbangash99">
    <span class="icon"><font-awesome-icon :icon="['fab', 'instagram']"/></span>
    </a>
    </div>
</footer>
</template>

<script>
export default {
  computed: {
    dataPicker(){
        let date = new Date();
        return date.getFullYear();
    }
  
    
  }

}
</script>

<style>
footer {
  display: flex;
  justify-content:space-between;
  align-items: center;
  background-color: rgb(10, 4, 22);
  bottom: 0 !important;
  padding-top: 10px !important;
  padding-bottom: 8px !important ;
  padding-left: 60px;
  padding-right: 60px;
}

.footer__icons > span {
  margin-right: 5px;
}
h3 {
  font-size: 1em;
  color: white !important;
  margin-top: 0.5em !important;
  margin-bottom: 0.5em !important;
}
.icon {
  font-size: 24px  !important;
}

@media screen and (max-width:768px) {
  footer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  h3 {
    width: 300px;
    text-align: center;
  }
}

</style>
