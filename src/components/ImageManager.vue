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

    <img alt=" " id="button12" src="http://sitecommun.alwaysdata.net/t??l??phone_pench??.png" v-on:click="description12"  v-bind:style="{
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
      <h5>Listes des ??l??ments ?? trouver</h5>
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
        "pifeltro: m??dicament",
        "pilule du lendemain",
        "pilule contraceptive",
        "pr??servatif masculin",
        "pr??servatif f??minin",
        "ruban rouge : VIH",
        "t??l??phone : site sexulait??s info sant??",
        "post it: num??ro sida info service",
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
      this.descriptionh2="c???est un anneau en silicone qui doit ??tre port?? 15h/jour, il chauffe et remonte les testicules emp??chant la production de spermatozo??des (les testicules sont excentr??es du corps car elles doivent ??tres ?? une temp??ratures plus faible que celui-ci pour produire des spermatozo??des).\n"

    },

    description2(){
      this.descriptionh1="Calendrier"
      this.descriptionh2="La Journ??e mondiale du sida, ou Journ??e mondiale de lutte contre le sida, est une journ??e internationale consacr??e ?? la sensibilisation ?? la pand??mie du sida. Elle est organis??e tous les 1er d??cembre.\n" +
          "Cette journ??e fut ??tablie le 1er d??cembre 1988 par l'Organisation mondiale de la sant?? (OMS)."

    },

    description3(){
      this.descriptionh1="Diaphragme contraceptif/Cape cervicale"
      this.descriptionh2="C???est une coupelle (changement de forme selon diaphragme ou cape cervicale) en latex ou en silicone qui se glisse dans le vagin pour emp??cher le passage des spermatozo??des.Il doit ??tre utilis?? en association avec les spermicides pour une meilleure efficacit??. Il peut ??tre pos?? au moment du rapport sexuel (ou maximum 2h avant) puis ??tre retir?? 8h apr??s le rapport sexuel.\n"

    },description4(){
      this.descriptionh1="lubrifiant "
      this.descriptionh2="Il permet de faciliter la p??n??tration en palliant la s??cheresse vaginale et les irritations.// permettre rapports sexuels non-douloureux"

    },description5(){
      this.descriptionh1="patch contraceptif  \n"
      this.descriptionh2="c???est un timbre qui se colle sur la peau, Il contient un estrog??ne et un progestatif, qui traversent la peau et passent progressivement dans la circulation sanguine. Il doit ??tre appliqu?? sur le ventre,  les ??paules ou dans le bas du dos et prot??ge pendant 4 semaines, les 3 premi??res semaines il doit ??tre chang?? 1 fois par semaine, puis la quatri??me semaine des saignements vont appara??tre. En cas d???oubli au moment o?? il faut le changer, on reste prot??g??e pendant 48 heures.\n."

    },description6(){
      this.descriptionh1="pilule"
      this.descriptionh2="C???est un m??dicament qui contient des hormones ressemblant ?? celles que fabriquent naturellement le corps ?? prendre tous les jours, et si possible ?? la m??me heure. Il existe 2 types de pilules : combin??es (contient un estrog??ne et un progestatif, elles suppriment l???ovulation)  et microprogestatives (contient seulement 1 progestatif , elles suppriment l???ovulation ou emp??chent le passage des spermatozo??des)"

    },

    description7(){
      this.descriptionh1="pilule du lendemain"
      this.descriptionh2="La contraception d???urgence hormonale se pr??sente sous la forme d???un comprim?? unique ?? prendre le plus t??t possible apr??s le rapport ?? risque et jusqu????? cinq jours apr??s le rapport sexuel. L???hormone de synth??se pr??sente dans la pilule retarde l???ovulation et donc emp??che la rencontre entre l???ovule et le spermatozo??de."

    },description8(){
      this.descriptionh1=""
      this.descriptionh2=""

    },

    description9(){
      this.descriptionh1="Les pr??servatifs"
      this.descriptionh2="Le pr??servatif est le seul moyen de contraception efficace contre la transmission d???IST!\n"

    },

    description10(){
      this.descriptionh1="Ruban rouge "
      this.descriptionh2="Le ruban rouge est le symbole universel de la lutte contre le sida et de la solidarit?? avec les personnes qui en sont atteintes. Arborer le ruban rouge, c???est donc afficher au grand jour son appartenance ?? un groupe que l???on esp??re le plus large possible : le groupe de ceux qui rejettent toute forme de discrimination ?? l?????gard des personnes atteintes par le sida.\n" +
          "Cre??e?? a?? l'initiative du Visual Aids Artists Caucus (un groupe d'artistes ame??ricains) et de Franck Moore,( un peintre qui vit et travaille a?? New York ), le ruban rouge voit le jour avec l'ide??e que l'on pourrait le porter pre??s du coeur pour symboliser la solidarite?? avec les personnes touche??es par le VIH et celles de??ce??de??es du sida.\n"

    },description11(){
      this.descriptionh1="informations sur le Sida"
      this.descriptionh2="telephone : 0 800 840 800\n" +
          "https://www.sida-info-service.org\n" +
          "ou le lundi de 17h ?? 21h, les mercredi et jeudi de 13 h ?? 17 h\n" +
          "(0 810 630 515 - 0,06??? /min + prix de l'appel)\n" +
          "https://www.vih-info-soignants.fr\n"

    },description12(){
      this.descriptionh1="sexualit?? info sant??"
      this.descriptionh2="Sexualit??s Info Sant?? est une nouvelle offre de Sida Info Service qui vous pr??sente l???alternative de communiquer ?? propos de la sexualit??. C???est un espace qui vous offre une ??coute adapt??e qui prend en compte votre v??cu de la sexualit?? (exp??riences, d??sirs, angoisses), votre vie sociale et relationnelle, votre sant?? et votre bien-??tre. \n" +
          "Contact: \n" +
          "\tt??l??phone : Au 0 800 00 69 07\n"

    },description13(){
      this.descriptionh1="Autotest VIH\n"
      this.descriptionh2="Comment l???utiliser?\n" +
          "https://youtu.be/JsjU_WuxZH8  / m??me principe que autotest covid\n" +
          "test sanguin, ?? partir d???une goutte de sang au prise au bout du doigt\n" +
          "permet de mettre en ??vidence les anticorps (anti-VIH-1)\n" +
          "exposition au virus datant de 3 mois (si r??sultat positif, confirm?? en laboratoire)\n" +
          "Qu???elle est la Fiabilit?? d???un autotest VIH ? 98.8%\n" +
          "O?? est-ce disponible? en pharmacie et en ligne (prix : 18-30???)\n"

    },description14(){
      this.descriptionh1="informations sur les h??patites"
      this.descriptionh2="telephone : 0 800 845 800\n" +
          "https://www.hepatites-info-service.org\n"

    },description15(){
      this.descriptionh1="Les Traitements contre le VIH : \n"
      this.descriptionh2="pifeltro: m??dicament qui emp??che la reproduction du virus dans les cellules infect??es, sans toutefois permettre son ??limination, il est ?? 100% remboursable.Il n?????limine pas les risques de transmission. Il peut aussi provoquer des ??tourdissements ou une baisse de vigilance.\n"

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
