<template>
  <div id="chrono" >
    <button id="pause_btn" v-on:click="stopChrono"  > Pause </button>
    <button id="chrono_text" v-on:click="startChrono" >COMMENCER : {{minutes}}: {{secondes}}</button>
  </div>
</template>

<script>
export default {



  name: 'ChronoManager',

  data(){
    return{
      minutes: 0,
      secondes: 0,
      totalSecondes: 0,
      timer:''
    };
  },
  methods : {

    startChrono (){
      var v = this;
      v.timer = setInterval(function (){
        v.minutes = Math.floor(++v.totalSecondes / 60);
        v.secondes = v.totalSecondes - (v.minutes * 60);
      } , 1000);

    },

    stopChrono(){clearInterval(this.timer)}

  /*props: {
    msg: String
  }*/
},

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
