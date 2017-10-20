## TD n°4 exercice 1


_index.html :_
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Titre</title>
    <link rel="stylesheet" href="styles.css"/>
  </head>
  <body>
    <div id="bandeau"></div> <!-- bandeau gris en haut -->
    <div id="contenu">    <!-- contenu de la newsletter -->
      <div id="entete">
        <span>Fabulous<em>.</em></span>
        <a href="#">If you have trouble viewing this email, click here. &#128279;</a>
      </div>
      <div id="titre">
        <h1>Who we are</h1>
        <div>Give information about your lifestyle, philosophy or what the impact you’re trying to make is.</div>
      </div>
      <div id="reseaux" class="fond-bleu">
        <span>Stay in Touch !</span>
        <div id="lienTwitter">t</div>
        <div id="lienFacebook">f</div>
      </div>
      <div class="image">
        <img src="https://langages-web.github.io/TD4/bigImg.jpg">
        <div>Something Cleverfont</div>
        <a href="#" class="fond-bleu">Find out more</a>
      </div>
      <div class="texte">
        <h2>Quick tip</h2>
        <p>
          Give a quick tip about an improvement to lifestyle - such as a nutrition, breathing or meditation. Give more information on a landing page.
        </p>
        <a href="#">Read More</a>
      </div>
      <div class="texte">
        <h2>Invite people to a class</h2>
        <p>
          Do you have specials if people invite a friend? Do you offer a summer special, Back to school promotion, New Year’s resolution or Spring Detox ?
        </p>
        <a href="#">Read More</a>
      </div>
    </div>
  </body>
</html>
```
_styles.css :_
```css
/* Règle concernant l'ensemble du contenu */
_selecteur_ {
	background-color: #F6F6F6;
	margin: 0;
	padding: 0;
	font-family: sans-serif;
}

/* Pour éviter que les liens ne soient soulignés */
_selecteur_ {
	text-decoration: none;
}

/* Pour les éléments ayant un fond bleu */
_selecteur_ {
	background-color: #62A9D2;
}

/* Bandeau gris en haut */
_selecteur_ {
	background-color: #43474A;
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 160px;
}

/* Conteneur principal */
_selecteur_ {
	position: relative;
	padding: 0;
	background-color: #FFFFFF;
	width: 605px;
	margin: 0 auto;
}

/* Section entete */
_selecteur_ {
	background-color: #43474A;
	border-bottom: 5px solid #62A9D2;
	padding-bottom: 20px;
}

/* Logo */
_selecteur_ {
	font-family: serif;
	color: #FFFFFF;
	padding: 20px 10px;
	font-size: 30px;
}

/* Logo */
_selecteur_ {
	color: #62A9D2;
	font-size: 45px;
}

/* Lien en haut à droite */
_selecteur_ {
	color: #A8B0B6;
	font-size: 12px;
	position: absolute;
	right: 0;
	top: 20px;
}

/* Section titre */
_selecteur_ {
	padding: 30px 0 40px;
}

/* Titre principal */
_selecteur_ {
	font-size: 32px;
	color: #555555;
	text-align: center;
}

/* Sous titre */
_selecteur_ {
	color: #99A1A6;
	font-size: 13px;
	text-align: center;
	padding: 10px 70px;
}

/* Section réseaux sociaux */
_selecteur_ {
	padding: 20px;
	font-style: italic;
	color: #0F4666;
}

/* Boutons réseaux sociaux */
_selecteur_ {
	background-color: #95C5E2;
	float: right;
	width: 32px;
	height: 45px;
	border-radius: 50%;
	font-size: 40px;
	font-weight: bold;
	padding-left: 13px;
	margin-top: -12px;
	margin-left: 15px;
}

/* Section image */
_selecteur_ {
	margin-top: 30px;
	background-color: #000000;
	color: #FFFFFF;
}

/* Image */
_selecteur_ {
	width: 100%;
}

/* Légende image */
_selecteur_ {
	padding: 20px;
	font-size: 21px;
	display : inline-block;
	width: 70%;
}

/* Lien sous image */
_selecteur_ {
	font-size: 12px;
	color: #FFFFFF;
	padding: 10px;
}

/* Sections de texte */
_selecteur_ {
	width: 39%;
	display: inline-block;
	margin: 30px;
}

/* Titres sections texte */
_selecteur_ {
	color: #555555;
	font-size: 20px;
}

/* Paragraphes section texte */
_selecteur_ {
	text-align: justify;
	color: #999999;
	font-size: 13px;
}

/* Liens section texte */
_selecteur_ {
	color: #62A9D2;
	font-weight: bold;
	font-size: 13px;
}
```