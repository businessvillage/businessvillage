<!DOCTYPE html>
<html>
<title>BLOG DE BUSINESS VILLAGE</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1 {font-family: "Montserrat", sans-serif}
img {margin-bottom: -7px}
.w3-row-padding img {margin-bottom: 12px}
</style>
<body>
	<img src="../Photos BUSINESS VILLAGE/3.jpg" id="JB" alt="BV" style="position: absolute; top: 100px; left: 20px;" />
 <script type="text/javascript">
 	function move(amplitude, frequence, vitesse, larg, posYi, sens) {
   el = document.getElementById('JB');
   posX = parseInt(el.style.left);
   posY = parseInt(el.style.top);
   if (eval(posX+el.width) >= larg && sens == 1) {
   	sens = -sens;
   } else if (eval(posX) <= 0 && sens == -1) {
   	sens = -sens;
   }
   posX = eval(posX+sens*vitesse);
   posY = Math.round(posY + sens*amplitude*Math.cos(posX/(frequence*vitesse)));
   el.style.top = posY + 'px';
   el.style.left = posX + 'px';
   setTimeout('move('+amplitude+', '+frequence+', '+vitesse+', '+larg+', '+posYi+', '+sens+')', 20);
 	}
 	move(6, 10, 5, document.body.clientWidth, eval(parseInt(document.getElementById('JB').style.top)), 1);
 </script>
  
  <hr id="about">
  <div class="w3-container w3-padding-32 w3-center">  
<div id="bloc_page">
        <header>
            <h1><img src="../Photos BUSINESS VILLAGE/BV17_LOGO BVILLAGE_RVB_SMALL.jpg" style="width:20%" alt="Logo_page" title="Accueil" id="logo"/></h1>
			<h2><img src="../Photos BUSINESS BOAT/BV17_LOGO BBOAT_RVB_SMALL.jpg" style="width:20%"alt="Logo_page" title="Accueil" id="logo"/></h2>
<nav class="w3-sidebar w3-black w3-animate-top w3-xxlarge" style="display:none;padding-top:150px" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-black w3-xxlarge w3-padding w3-display-topright" style="padding:6px 24px">
    <i class="fa fa-remove"></i>
  </a>
  <div class="w3-bar-block w3-center">
    <a href="http://www.business-village.biz" class="w3-bar-item w3-button w3-text-grey w3-hover-black">A propos</a>
    <a href="http://www.business-village.biz/index.php/espaces-new-tech" class="w3-bar-item w3-button w3-text-grey w3-hover-black">Du côté de nos séminaires</a>
    <a href="https://www.facebook.com/pg/businessvillage.biz/reviews/?ref=page_internal" class="w3-bar-item w3-button w3-text-grey w3-hover-black">L'avis de nos internautes</a>
    <a href="http://www.business-village.biz/index.php/sophie-et-philippe-nos-valeurs" class="w3-bar-item w3-button w3-text-grey w3-hover-black">Contactez-nous!</a>
	  
  </div>
</nav>

<div class="w3-content" style="max-width:1500px">

<div class="w3-opacity">
<span class="w3-button w3-xxlarge w3-white w3-right" onclick="w3_open()"><i class="fa fa-bars"></i></span> 
<div class="w3-clear"></div>
<header class="w3-center w3-margin-bottom">
  <h1><b>BLOG DE BUSINESS VILLAGE</b></h1>
  <p><b>Du coeur dans le Business !</b></p>
  <p class="w3-padding-16"><button class="w3-button w3-black" onclick="myFunction()">+/-</button></p>
</header>
</div>

<div class="w3-row" id="myGrid" style="margin-bottom:128px">
  <div class="w3-third">
    <img src="20180116_075713.jpg" style="width:100%">
    <img src="20180116_224617.jpg" style="width:100%">
    <img src="20180118_091431.jpg" style="width:100%">
    <img src="aifel.jpg" style="width:100%">
    <img src="20180116_222359.jpg" style="width:100%">

  </div>

  <div class="w3-third">
    <img src="Business Village.JPG" style="width:100%">
    <img src="boules lumineuses sur la piscine.jpg" style="width:100%">
    <img src="Central.png" style="width:100%">
    <img src="Cottage.jpg" style="width:100%">
    <img src="meetingsuite1.jpg" style="width:100%">
    <img src="meat_1.jpg" style="width:100%">
	<img src="../Photos BUSINESS VILLAGE/Le Pavillon Blanc.jpg" style="width:100%">
  </div>

  <div class="w3-third">
    <img src="Cottage chambre royale.jpg" style="width:100%">
    <img src="cabane-2personnes2.jpg" style="width:100%">
    <img src="Meeting Suite.jpg" style="width:100%">
    <img src="38c.jpg" style="width:100%">
    <img src="../Photos BUSINESS VILLAGE/stanford-pleniere2.jpg" style="width:100%">
    <img src="20180116_100706.jpg" style="width:100%">
  </div>
</div>

</div>
<div class="w3-padding-32">
      <h2><b>Qui sommes-nous?</b></h2>
      <h6><i>La passion du partage en séminaires d'entreprise</i></h6>
      <p align="justify">BV est un village à une heure et quart de Paris, une bulle en forêt, magnifique
par son authenticité et la modernité de ses équipements technologiques.
Et depuis cette année, BV anime un autre lieu tout aussi original, sur l’eau :
des bateaux exceptionnels, sur la Seine, au pied de la Tour Eiffel.
A chaque fois, dans chaque lieu, vous trouverez la même originalité et
une occasion unique de mettre du coeur dans votre business.
	<p><h5><b>BUSINESS VILLAGE :</b></h5></p>
<p>Souplesse et Espace, en forêt ou sur l'eau, chaque instant de votre journée est organisé dans les moindres détails. Mais le rythme, c'est vous qui l'imposez, pas nous!</p>
	<p>Prenez place dans la générosité. Culture d'entreprise et grands espaces font bon ménage: espace, lumière et new tech.</p>

<p>En comité restreint ou jusqu'à 400 personnes, retrouvez-nous dans les salles aménagées selon vos besoins. 22 salles entièrement modulables dont une plénière de 700M2</p>
	<p>Le chef est en cuisine, du petit-déjeuner au dîner, les repas sont élaborés sur place prennent en compte toutes les spécificités et les goûts de chacun.</p>
	
<p><h5><b>BUSINESS BOAT :</b></h5></p>
	<p>Meetings & Boats. Au pied de la Tour Eiffel, l'inoubliable expérience de travailler à bord de nos luxueux bateaux.</p>
	<p><h5><b>Nos valeurs :</b></h5></p>
	<p>- Liberté</p>
	<p>- Espace</p>
	<p>- Écoute</p>
	<p>- Générosité</p>
	<p>- Qualité</p>
	<p>- Discrétion</p>
	<p>- Souplesse</p>
	<p>- Originalité</p>
    </div>
  </div>
<footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin-top:128px"> 
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
  <p class="w3-medium">Visitez notre site internet : <a href="http://www.business-village.biz" target="_blank" class="w3-hover-text-green">Business Village</a>
	</p>
</footer>
 
<script>

	function myFunction() {
    var x = document.getElementById("myGrid");
    if (x.className === "w3-row") {
        x.className = "w3-row-padding";
    } else { 
        x.className = x.className.replace("w3-row-padding", "w3-row");
    }
}

function w3_open() {
    document.getElementById("mySidebar").style.width = "100%";
    document.getElementById("mySidebar").style.display = "block";
}

function w3_close() {
    document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>

