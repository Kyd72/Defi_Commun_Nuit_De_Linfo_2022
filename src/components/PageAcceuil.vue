<template>
  <div class="body">
    <header>
      <a href="#" class="logo"></a>
      <div class="bienvenue">Bienvenue au grand jeu préventif!</div>
    </header>
    <div class="enter">
      <p class="coeur">
        La prévention, c'est sympa, mais c'est souvent ennuyant. Alors, dans la tradition des point'n'click des années 80, nous vous invitons a trouver dans la chambre qui vient les objets qui peuvent vous aider a combattre les mst et les ist. Des objets de tout les jours, aux droles de prototypes tout juste sortis sur le marché, ayez l'oeil précis!
      </p>
      <p class="coeur">
        A la fin du jeu, vous aurez la possibilité d'en appredre plus sur les éléments que vous avez recherchés. Renseignez-vous!
      </p>
      <section>
        <img style="text-align:center; width:40%; height: 40%;" src="http://sitecommun.alwaysdata.net/VIH.png" id="capote">
        <img style="text-align:left;width: 30%; height: 30%;" src="http://sitecommun.alwaysdata.net/ruban%20rouge.png" id="ruban%20rouge">
        <img style="text-align:right; width:40%; height: 40%;" src="http://sitecommun.alwaysdata.net/preservatifs.png" id="ruban%20rouge">
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: "PageAcceuil"
}
</script>

<style scoped>

.body{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family:'Poppins', sans-serif;
}
.home{
  border-radius: 50px;
  border-width: 0;
  background-color: #94237b;
  cursor: pointer;
  color: white;
  text-decoration: none;
}
.enter{
  margin-top: 300px;;
}


.bienvenue{
  display: block;
  margin-left: auto;
  margin-right: auto;
  color: white;
  font-size: 50px;
}

.coeur{
  margin-left: 150px;
  font-size: large;
  color: white;
  margin-right: 200px;
}

.pbout{
  margin-top: 50px;
  text-align: right;
  margin-right: 100px;
}

.body
{
  min-height: 100vh;
  background: linear-gradient(#94237b,#7e1d59);

}
header
{
  position: absolute;
  top: 0;
  Left: 0;
  width: 95%;
  padding: 30px;
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
  padding: 6px;
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
  width: 100%;
  height: 100vh;
  padding: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>