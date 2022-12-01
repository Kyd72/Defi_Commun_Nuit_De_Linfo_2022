<template>
  <div v-show="path === 'decouverte'">
    <ImageManager id="imManager" v-show="path === 'decouverte'" />
  </div>
  <div v-show="path === 'welcome'">
    <PageAcceuil  v-show="path === 'welcome'"/>
  </div>
  <div v-show="path === 'final'">
    <PageFinal  />
  </div>
  <div style="display:flex; justify-content:center; font-size: 20px;font-weight: bold;position: fixed;top:0px;">
    <div style="margin-left: 15%" @click="welcome"> Acceuil </div>
    <div style="margin-left: 15%" @click="decouverte"> Jouer au jeu </div>
    <div style="margin-left: 15%" @click="final"> Final </div>
  </div>
</template>

<script>

import ImageManager from "@/components/ImageManager.vue";
import PageAcceuil from "@/components/PageAcceuil.vue";
import PageFinal from "@/components/PageFinal.vue";

export default {
  name: 'App',
  components: {
    ImageManager,
    PageAcceuil,
    PageFinal
  },
  data(){
    return{
      path: 'welcome',
    }
  },
  methods: {
    decouverte(){
      this.path = 'decouverte'
    },
    final(){
      this.path = 'final'
    },
    welcome(){
      this.path = 'welcome'
    }
  }
}
</script>

<style scoped>


#imManager{
  margin: auto;


  width: 1100px;
  height: 573px;
 /* padding-top: 34.03%; /* (img-height / img-width * container-width) */
  /* (853 / 1280 * 100) */



  }

#chManager{
  /*border: 3px solid #73AD21;*/
  position: center;
}


</style>
