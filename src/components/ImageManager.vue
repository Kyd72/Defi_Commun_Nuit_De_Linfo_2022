<!--
<template>
<div :style="{backgroundImage:'url('+lienImageFond+')'}" id="ImageManager">

  <img alt=" " id="button" v-bind:src="lienImageHerosATrouver"  v-on:click="changerBackground" v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">
</div>

</template>

<script>
  export default {


  name: 'ImageManager',
  data(){
    return {
      mPosition : 'relative',
      mHeight : 30,
      mWidth : 30,
      mLeft : 500,
      mTop : 300,
      lienImageHerosATrouver :'https://e7.pngegg.com/pngimages/766/558/png-clipart-symbol-pause-button-text-orange-thumbnail.png  ',
      lienImageFond : 'https://i.ibb.co/dkHwWBG/pexels-ihsan-aditya-1056251.jpg',
      niveau :0,
      style : "left: 600px",
      top : 400,
      left : "position: relative; left: 600px; top: 400px;",
      imageBackGround : ["https://uc9059bd2774b57c741cad007246.previews.dropboxusercontent.com/p/thumb/ABs2jlBgDwFf30XlGKGUqYYD0H9BgiWBX4Xjd1QeHs4xuVW8nvjDZJpcF92S9gz2gHkKRUQmJXP8xjsO4fzHK4i2YefSqA5v5AU-pbjT5iRnmcE2GGqSQjZDmbNevzV9wCWaju_lDwvdO5eBHbVVnBC5dyjKxxwLGXKcmAUdZeIhOWxmMXFksWRpysZBmaY7keX6A3Tj00ANUOTZaadOBGPZI2wjC1X0-WPlRkvcyG8sUU44rgw73regYlHlC4RzXJHogLN9FgcIRvwddY8PQ9AD76Zs57vK4fGBxUeCZ6jNb0w0aJgQGfhbY8T-l8TXFPNRAhlrV8XtywE6_PUvqos3xTziZw5bW2j3n_b70hG3gkKCL8_p17GE_x8DsJ9CVHg/p.png","http://sitecommun.alwaysdata.net/f_un.png","http://sitecommun.alwaysdata.net/f_deux.jpg","http://sitecommun.alwaysdata.net/f_trois.png","http://sitecommun.alwaysdata.net/f_quatre.jpg","http://sitecommun.alwaysdata.net/f_cinq.jpg"],
      imageHeros : ["https://uc894383089cd6f7b685943ae34b.previews.dropboxusercontent.com/p/thumb/ABtAtop7xKsM-JbVcnHsze2G-Mju1i6zWOtbhC9-e-IiJN_elLwW0Ql81KqQTpABN3pgYljwsXTwcEC0TPAvBiW1C1GVAoQcY_bc8rFCq-G0b5mOk2-4mCIlaQsPqtfcn1j5T4E0q-8XEBHGMNSmJF7DvW_BH4Ev7wsQu0jXCke9ZZy534vxQ2AqRvVZmkp-5myUzBQ19XbO41yFxu5vBvr1F8N70KQNpuDxXkZ1dh1dpImad_bJ1-uE8GnEN-7J9-jtdkGI1NTk-CgwE5IVYujTbwCnS62iJUbDXaFRvDxHY7TjuJz-GWlq1tQJJjy0SGp4Mu4v2VaGU&#45;&#45;9Ob3yF1c7D6WB0i6QiPxDih62wz-rdhka17JwKAhA4Y3IghnWGek/p.png","http://sitecommun.alwaysdata.net/h_un.png", "http://sitecommun.alwaysdata.net/h_deux.png", "http://sitecommun.alwaysdata.net/h_trois.png", "http://sitecommun.alwaysdata.net/h_quatre.png", "http://sitecommun.alwaysdata.net/h_cinq.png"],
  /* "url(https://vuejs.org/images/logo.png)"*/

    }

    ;
  },



  methods : {
    changerBackground(){
      this.lienImageFond=this.imageBackGround[this.niveau]
      this.lienImageHerosATrouver=this.imageHeros[this.niveau]
      this.niveau++
      this.mLeft= Math.random()*550
      this.mTop=Math.random()*390

    }
  },
}
</script>

<style scoped>

#button{
  position: relative;
  height: 40px;
  width: 40px;
  border: 3px solid #73AD21;
  left: 600px; top: 400px;
}
/*#ImageManager{

  display: table;

  width: 100%;
  border: 3px solid #73AD21;
  background-size: cover;


}

*/



/*#button{
margin:auto;
  position: center;
  border: 3px solid #73AD21;
}*/




</style>
defi 222222222222222222
-->

<template>
  <div id="main">
    <div :style="{backgroundImage:'url(https://cache.marieclaire.fr/data/photo/w1200_h630_ci/5n/chambre-ado-idee-deco.jpg)'}" id="ImageManager">

    <img alt=" " id="button1" src="http://sitecommun.alwaysdata.net/anneau contraceptif homme.png" v-on:click="description1"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button2" src="http://sitecommun.alwaysdata.net/calendrier.jpg" v-on:click="description2"   v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button3" src="http://sitecommun.alwaysdata.net/diaphragme.png" v-on:click="description3"   v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button4" src="http://sitecommun.alwaysdata.net/lubrifiant.jpg" v-on:click="description4"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button5" src="http://sitecommun.alwaysdata.net/patch.png" v-on:click="description5"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button6" src="http://sitecommun.alwaysdata.net/pillule contraceptives.png" v-on:click="description6"   v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button7" src="http://sitecommun.alwaysdata.net/Pillule-du-lendemain-transparente-2.jpg"  v-on:click="description7"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button8" src="http://sitecommun.alwaysdata.net/preservatif-feminin.jpg" v-on:click="description8"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button9" src="http://sitecommun.alwaysdata.net/preservatifs.png" v-on:click="description9"   v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button10" src="http://sitecommun.alwaysdata.net/ruban rouge.png" v-on:click="description10"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button11" src="http://sitecommun.alwaysdata.net/sida info service.png" v-on:click="description11"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button12" src="http://sitecommun.alwaysdata.net/téléphone_penché.png" v-on:click="description12"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button13" src="http://sitecommun.alwaysdata.net/vih test.png" v-on:click="description13"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button14" src="http://sitecommun.alwaysdata.net/VIH.png" v-on:click="description14"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">

    <img alt=" " id="button15" src="http://sitecommun.alwaysdata.net/pifeltro traitement vih.png" v-on:click="description15"  v-bind:style="{
   position: mPosition,
  height: (mHeight)+'px',
  width: (mWidth)+'px',
  left: (Math.random()*mLeft)+'px',
  top: (Math.random()*mTop)+'px',}">
  </div>
    <div id="liste" >
      <h5>Listes des éléments à trouver</h5>
      <ul v-for="(element, index) in liste" :key="index" >
        <li style="font-size: 13px;font-weight: bold ">{{element}}</li>
      </ul>

    </div>
    <div id="description"> <h1>{{ descriptionh1 }}</h1>  <p>{{descriptionh2}}</p> </div>
  </div>




</template>

<script>
export default {


  name: 'ImageManager',
  data(){
    return {
      liste : ["anneau masculin contraceptif",
        "anneau vaginal",
        "calendrier",
        "lubrifiant",
        "patch contraceptif",
        "pifeltro: médicament",
        "pilule du lendemain",
        "pilule contraceptive",
        "préservatif masculin",
        "préservatif féminin",
        "ruban rouge : VIH",
        "téléphone : site sexulaités info santé",
        "post it: numéro sida info service",
        "autotest VIH",
        "virus VIH"
  ],
      descriptionh1:'',
      descriptionh2:'',
      mPosition : 'relative',
      mHeight : 27,
      mWidth : 48 ,
      mLeft : 100,
      mTop : 450,
      lienImageHerosATrouver :'https://e7.pngegg.com/pngimages/766/558/png-clipart-symbol-pause-button-text-orange-thumbnail.png  ',
      lienImageFond : 'https://i.ibb.co/dkHwWBG/pexels-ihsan-aditya-1056251.jpg',
      niveau :0,
      style : "left: 600px",
      top : 400,
      left : "position: relative; left: 600px; top: 400px;",
      imageBackGround : ["https://uc9059bd2774b57c741cad007246.previews.dropboxusercontent.com/p/thumb/ABs2jlBgDwFf30XlGKGUqYYD0H9BgiWBX4Xjd1QeHs4xuVW8nvjDZJpcF92S9gz2gHkKRUQmJXP8xjsO4fzHK4i2YefSqA5v5AU-pbjT5iRnmcE2GGqSQjZDmbNevzV9wCWaju_lDwvdO5eBHbVVnBC5dyjKxxwLGXKcmAUdZeIhOWxmMXFksWRpysZBmaY7keX6A3Tj00ANUOTZaadOBGPZI2wjC1X0-WPlRkvcyG8sUU44rgw73regYlHlC4RzXJHogLN9FgcIRvwddY8PQ9AD76Zs57vK4fGBxUeCZ6jNb0w0aJgQGfhbY8T-l8TXFPNRAhlrV8XtywE6_PUvqos3xTziZw5bW2j3n_b70hG3gkKCL8_p17GE_x8DsJ9CVHg/p.png","http://sitecommun.alwaysdata.net/f_un.png","http://sitecommun.alwaysdata.net/f_deux.jpg","http://sitecommun.alwaysdata.net/f_trois.png","http://sitecommun.alwaysdata.net/f_quatre.jpg","http://sitecommun.alwaysdata.net/f_cinq.jpg"],
      imageHeros : ["https://uc894383089cd6f7b685943ae34b.previews.dropboxusercontent.com/p/thumb/ABtAtop7xKsM-JbVcnHsze2G-Mju1i6zWOtbhC9-e-IiJN_elLwW0Ql81KqQTpABN3pgYljwsXTwcEC0TPAvBiW1C1GVAoQcY_bc8rFCq-G0b5mOk2-4mCIlaQsPqtfcn1j5T4E0q-8XEBHGMNSmJF7DvW_BH4Ev7wsQu0jXCke9ZZy534vxQ2AqRvVZmkp-5myUzBQ19XbO41yFxu5vBvr1F8N70KQNpuDxXkZ1dh1dpImad_bJ1-uE8GnEN-7J9-jtdkGI1NTk-CgwE5IVYujTbwCnS62iJUbDXaFRvDxHY7TjuJz-GWlq1tQJJjy0SGp4Mu4v2VaGU--9Ob3yF1c7D6WB0i6QiPxDih62wz-rdhka17JwKAhA4Y3IghnWGek/p.png","http://sitecommun.alwaysdata.net/h_un.png", "http://sitecommun.alwaysdata.net/h_deux.png", "http://sitecommun.alwaysdata.net/h_trois.png", "http://sitecommun.alwaysdata.net/h_quatre.png", "http://sitecommun.alwaysdata.net/h_cinq.png"],
      /* "url(https://vuejs.org/images/logo.png)"*/

    }

        ;
  },



  methods : {
    description1(){
      this.descriptionh1="anneau thermique masculin"
      this.descriptionh2="c‘est un anneau en silicone qui doit être porté 15h/jour, il chauffe et remonte les testicules empêchant la production de spermatozoïdes (les testicules sont excentrées du corps car elles doivent êtres à une températures plus faible que celui-ci pour produire des spermatozoïdes).\n"

    },

    description2(){
      this.descriptionh1="Calendrier"
      this.descriptionh2="La Journée mondiale du sida, ou Journée mondiale de lutte contre le sida, est une journée internationale consacrée à la sensibilisation à la pandémie du sida. Elle est organisée tous les 1er décembre.\n" +
          "Cette journée fut établie le 1er décembre 1988 par l'Organisation mondiale de la santé (OMS)."

    },

    description3(){
      this.descriptionh1="Diaphragme contraceptif/Cape cervicale"
      this.descriptionh2="C’est une coupelle (changement de forme selon diaphragme ou cape cervicale) en latex ou en silicone qui se glisse dans le vagin pour empêcher le passage des spermatozoïdes.Il doit être utilisé en association avec les spermicides pour une meilleure efficacité. Il peut être posé au moment du rapport sexuel (ou maximum 2h avant) puis être retiré 8h après le rapport sexuel.\n"

    },description4(){
      this.descriptionh1="lubrifiant "
      this.descriptionh2="Il permet de faciliter la pénétration en palliant la sécheresse vaginale et les irritations.// permettre rapports sexuels non-douloureux"

    },description5(){
      this.descriptionh1="patch contraceptif  \n"
      this.descriptionh2="c’est un timbre qui se colle sur la peau, Il contient un estrogène et un progestatif, qui traversent la peau et passent progressivement dans la circulation sanguine. Il doit être appliqué sur le ventre,  les épaules ou dans le bas du dos et protège pendant 4 semaines, les 3 premières semaines il doit être changé 1 fois par semaine, puis la quatrième semaine des saignements vont apparaître. En cas d’oubli au moment où il faut le changer, on reste protégée pendant 48 heures.\n."

    },description6(){
      this.descriptionh1="pilule"
      this.descriptionh2="C’est un médicament qui contient des hormones ressemblant à celles que fabriquent naturellement le corps à prendre tous les jours, et si possible à la même heure. Il existe 2 types de pilules : combinées (contient un estrogène et un progestatif, elles suppriment l’ovulation)  et microprogestatives (contient seulement 1 progestatif , elles suppriment l’ovulation ou empêchent le passage des spermatozoïdes)"

    },

    description7(){
      this.descriptionh1="pilule du lendemain"
      this.descriptionh2="La contraception d’urgence hormonale se présente sous la forme d’un comprimé unique à prendre le plus tôt possible après le rapport à risque et jusqu’à cinq jours après le rapport sexuel. L’hormone de synthèse présente dans la pilule retarde l’ovulation et donc empêche la rencontre entre l’ovule et le spermatozoïde."

    },description8(){
      this.descriptionh1=""
      this.descriptionh2=""

    },

    description9(){
      this.descriptionh1="Les préservatifs"
      this.descriptionh2="Le préservatif est le seul moyen de contraception efficace contre la transmission d’IST!\n"

    },

    description10(){
      this.descriptionh1="Ruban rouge "
      this.descriptionh2="Le ruban rouge est le symbole universel de la lutte contre le sida et de la solidarité avec les personnes qui en sont atteintes. Arborer le ruban rouge, c’est donc afficher au grand jour son appartenance à un groupe que l’on espère le plus large possible : le groupe de ceux qui rejettent toute forme de discrimination à l’égard des personnes atteintes par le sida.\n" +
          "Créé à l'initiative du Visual Aids Artists Caucus (un groupe d'artistes américains) et de Franck Moore,( un peintre qui vit et travaille à New York ), le ruban rouge voit le jour avec l'idée que l'on pourrait le porter près du coeur pour symboliser la solidarité avec les personnes touchées par le VIH et celles décédées du sida.\n"

    },description11(){
      this.descriptionh1="informations sur le Sida"
      this.descriptionh2="telephone : 0 800 840 800\n" +
          "https://www.sida-info-service.org\n" +
          "ou le lundi de 17h à 21h, les mercredi et jeudi de 13 h à 17 h\n" +
          "(0 810 630 515 - 0,06€ /min + prix de l'appel)\n" +
          "https://www.vih-info-soignants.fr\n"

    },description12(){
      this.descriptionh1="sexualité info santé"
      this.descriptionh2="Sexualités Info Santé est une nouvelle offre de Sida Info Service qui vous présente l’alternative de communiquer à propos de la sexualité. C’est un espace qui vous offre une écoute adaptée qui prend en compte votre vécu de la sexualité (expériences, désirs, angoisses), votre vie sociale et relationnelle, votre santé et votre bien-être. \n" +
          "Contact: \n" +
          "\ttéléphone : Au 0 800 00 69 07\n"

    },description13(){
      this.descriptionh1="Autotest VIH\n"
      this.descriptionh2="Comment l’utiliser?\n" +
          "https://youtu.be/JsjU_WuxZH8  / même principe que autotest covid\n" +
          "test sanguin, à partir d’une goutte de sang au prise au bout du doigt\n" +
          "permet de mettre en évidence les anticorps (anti-VIH-1)\n" +
          "exposition au virus datant de 3 mois (si résultat positif, confirmé en laboratoire)\n" +
          "Qu’elle est la Fiabilité d’un autotest VIH ? 98.8%\n" +
          "Où est-ce disponible? en pharmacie et en ligne (prix : 18-30€)\n"

    },description14(){
      this.descriptionh1="informations sur les hépatites"
      this.descriptionh2="telephone : 0 800 845 800\n" +
          "https://www.hepatites-info-service.org\n"

    },description15(){
      this.descriptionh1="Les Traitements contre le VIH : \n"
      this.descriptionh2="pifeltro: médicament qui empêche la reproduction du virus dans les cellules infectées, sans toutefois permettre son élimination, il est à 100% remboursable.Il n’élimine pas les risques de transmission. Il peut aussi provoquer des étourdissements ou une baisse de vigilance.\n"

    },
  },


}
</script>

<style scoped>

#main{
  content: "";
  display: table;
  clear: both;


}

#liste{

  float: right;
  height: 470px;

  padding: 0 10px;

  width: 15%;

}

#description{
  font-size: 20px;
  position: fixed;

  width: 75%;
  height: 35px;

  top:490px;
}

#ImageManager
{
float: left;
  width: 900px;
  height: 472.5px;

}

/*#ImageManager{

  display: table;

  width: 100%;
  border: 3px solid #73AD21;
  background-size: cover;


}

*/



/*#button{
margin:auto;
  position: center;
  border: 3px solid #73AD21;
}*/




</style>
