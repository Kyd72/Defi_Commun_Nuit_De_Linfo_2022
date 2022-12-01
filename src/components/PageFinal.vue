<template>
  <header>
    <a href="#" class="logo"></a>
    <ul>
      <li><a href="depart.html">Home</a></li>
      <li><a href="acceuil.html">Jeu</a></li>

    </ul>
  </header>
  <div class="resume">
    <div class="prevention">

      La prévention des infections sexuellement transmissibles est primordiale.

    </div>
    <div class="box">
      <div class="rightbox">
        <p class="droite">
          En cas de prise de risque involontaire, il existe des traitements d'urgence (TPE) disponibles aux services d'urgences partout en France.
        </p>
      </div>
      <div class="leftbox">
        <p class="gauche">
          En cas d'infection, il existe des traitements. Il faut prévenir son(ses) partenaire(s). Les traitements rendent la charge virale indétectable.
        </p>
      </div>
    </div>
    <div>
      <section>
        <img style="text-align:center; width:40%; height: 40%;" src="http://sitecommun.alwaysdata.net/VIH.png" id="capote">
        <img style="text-align:left;width: 30%; height: 30%;" src="http://sitecommun.alwaysdata.net/ruban%20rouge.png" id="ruban%20rouge">
        <img style="text-align:right; width:40%; height: 40%;" src="http://sitecommun.alwaysdata.net/preservatifs.png" id="ruban%20rouge">
      </section>
    </div>
    <div class="quote">
      <h3 class="quote">
        Mieux vaut prévenir que guérir!
      </h3>
    </div>

  </div>

</template>

<script>
export default {
  name: "PageFinal"
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family:'Poppins', sans-serif;
}
body
{
  min-height: 100vh;
  background: linear-gradient(#94237b,#7e1d59);

}
header
{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  padding: 30px 30px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
header.logo
{
  color: #fff;
  font-weight: 700;
  text-decoration:none;
  font-size: 2em;
  text-transform: uppercase;
  letter-spacing: 2px;
}
header ul

{
  display: flex;
  justify-content: center;
  align-items: center;
}
header ul li{
  list-style: none;
  margin-left: 20px;

}
header ul li a
{
  text-decoration: none;
  padding: 6px 15px;
  color: #fff;
  border-radius: 20px;
}
header ul li a:hover,
header ul li a.active
{
  background: #fff;
  color: #551044;

}
section
{
  position: relative;
  width: 75%;
  height: 80vh;
  margin-left: 270px;
  display: flex;
  justify-content: center;
  align-items: center;
}
div.class{
  display: flex;
  flex-direction: column;
  gap:5px;
}
div.box{
  color: white;
  display: flex;
  justify-content: space-around;
  margin-bottom: 200px;
  margin: 0px 40px;
  font-size: 4vh;
}
.prevention{
  color: white;
  align-self:center;
  font-size: 5vh;
  text-align: center;
  margin-bottom: 200px;
  margin-top: 150px;
}
.quote{
  color: white;
  align-self: center;
  text-align: center;
  margin-bottom: 100px;
  margin-top: 30px;

}
footer{
  text-align: center;
  color:white;
  padding-bottom: 20px;
}
</style>