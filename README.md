# Sommaire

* <a href="#tds">TDs</a>
  * <a href="#td-n5-du-20-octobre-2017">TD n°5 du 20 octobre 2017</a>
  * <a href="#td-n4-du-13-octobre-2017">TD n°4 du 13 octobre 2017</a>
  * <a href="#td-n3-du-6-octobre-2017">TD n°3 du 6 octobre 2017</a>
  * <a href="#td-n2-du-29-septembre-2017">TD n°2 du 29 septembre 2017</a>
  * <a href="#td-n1-du-22-septembre-2017">TD n°1 du 22 septembre 2017</a>
* <a href="#squelette-de-base-dune-page-html">Squelette de base d'une page HTML</a>
* <a href="#liens-utiles">Liens utiles</a>

# TDs

## TD n°5 du 20 octobre 2017

### Exercice 1

[Sources de l'exercice](https://langages-web.github.io/TD5/TD5-EX1.zip)
[Résultat à obtenir](https://langages-web.github.io/TD5/resultat.jpg)

URLs des images à utiliser :
* https://langages-web.github.io/TD5/slider.jpg
* https://langages-web.github.io/TD5/what1.png
* https://langages-web.github.io/TD5/what2.png
* https://langages-web.github.io/TD5/what3.png
* https://langages-web.github.io/TD5/work1.jpg
* https://langages-web.github.io/TD5/work2.jpg
* https://langages-web.github.io/TD5/work3.jpg
* https://langages-web.github.io/TD5/work4.jpg

## TD n°4 du 13 octobre 2017

![PPT](pdf-icon.png) [Présentation](TD4/TD4.pdf)

### Exercice 1

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
_Clic droit &gt; afficher l'image_
![TD4-ex2](TD4/TD4-ex1-resultat.jpg)

### Exercice 2

_index.html :_
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Renard</title>
	<link rel="stylesheet" href="styles.css"/>
  </head>
  <body>
	<div id="contenant">
      <h1>Renard</h1>
      <img class="image" src="http://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Looking_Foxy.jpg/220px-Looking_Foxy.jpg">
      <div id="texte">
        <p>
          <span class="important">Fox is a common name for many species of carnivorous mammals belonging to the Canidae family</span>. Foxes are small to medium-sized canids (slightly smaller than the median-sized domestic dog), characterized by possessing a long narrow snout, and a bushy tail (or brush).
        </p>
        <p>
          <span class="important">Members of about 37 species are referred to as foxes, of which only 12 species actually belong to the Vulpes genus of 'true foxes'</span>. By far the most common and widespread species of fox is the red fox (Vulpes vulpes), although various species are found on almost every continent. The presence of fox-like carnivores all over the globe has led to their appearance in both popular culture and folklore in many cultures around the world (see also Foxes in culture). The gray fox is one of only two canine species known to climb trees; the other is the raccoon dog.
        </p>
      </div>
	</div>
  </body>
</html>
```

_styles.css :_
```css
#contenant {
	width: 400px;
}

#texte {
  width: 300px;
  background-color: grey;
  height: 200px;
  overflow: auto;
}

.important {
  font-weight: bold;
  text-decoration: underline;
}

.image {
  width: 300px;
}
```

_Résultat attendu_

![TD4-ex2](TD4/TD4-ex2-resultat.jpg)

### Exercice 3

URLs des images à utiliser :
* https://langages-web.github.io/TD4/titre.png
* https://langages-web.github.io/TD4/bandeau.jpg
* https://langages-web.github.io/TD4/p1.jpg
* https://langages-web.github.io/TD4/p2.jpg
* https://langages-web.github.io/TD4/p3.jpg

_index.html :_
```html
<!DOCTYPE html>
<html lang="fr">
	<head>
		<meta charset="utf-8">
		<title>Hifi Discount</title>
    <link href="styles.css" rel="stylesheet" type="text/css">
	</head>
	<body>
    <div id="contenant">
    </div>
	</body>
</html>

```

styles.css :
```css
@import url(https://fonts.googleapis.com/css?family=Open+Sans);
* {margin:0px; padding:0px; box-sizing: border-box;}


body {
  font-family: "Open Sans", Arial, Helvetica, sans-serif;
  background-color: #eeeeee;
}

#contenant {
  width: 600px;
  margin: 0 auto; 
  background: #ffffff;
}
```

_Résultat attendu (Clic droit &gt; afficher l'image)_
![TD4-ex2](TD4/TD4-ex1.jpg)

## TD n°3 du 6 octobre 2017

![PPT](pdf-icon.png) [Présentation](TD3/TD3.pdf)

### Exercice 1

URLs des images à utiliser :
* https://langages-web.github.io/TD2/pizza1.png
* https://langages-web.github.io/TD2/pizza2.png
* https://langages-web.github.io/TD2/pizza3.png

#### Correction (Exercices 1 & 2)

* HTML

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Titre</title>
	<link rel="stylesheet" href="styles.css"/>
  </head>
  <body>
    <table>
      <thead>
        <tr>
          <th>Pizza</th>
          <th>Composition</th>
          <th>Prix</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>
            <span>Boeuf - Pepperoni</span><br/>
            <img src="https://langages-web.github.io/TD2/pizza1.png" alt="boeuf"/>
          </td>
          <td>
            <ul>
              <li>Sauce barbecue</li>
              <li>Mozzarella</li>
              <li>Oignons émincés</li>
              <li>Tomates en dés</li>
              <li>Éffiloché de bœuf</li>
            </ul>
          </td>
          <td class="prix">
            12 €
          </td>
        </tr>
        <tr>
          <td>
            <span>Figue - Chèvre</span><br/>
            <img src="https://langages-web.github.io/TD2/pizza2.png" alt="boeuf"/>
          </td>
          <td>
            <ul>
              <li>Mozzarella</li>
              <li>Chèvre</li>
              <li>Fourme d'Ambert</li>
              <li>Bacon</li>
              <li>Figues</li>
            </ul>
          </td>
          <td class="prix">
            11 €
          </td>
        </tr>
        <tr>
          <td>
            <span>Savoyarde Reblochon</span><br/>
            <img src="https://langages-web.github.io/TD2/pizza3.png" alt="boeuf"/>
          </td>
          <td>
            <ul>
              <li>Crème</li>
              <li>Reblochon</li>
              <li>Pommes de terre</li>
              <li>Lardons</li>
              <li>Oignons</li>
            </ul>
          </td>
          <td class="prix">
            10 €
          </td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
```
* CSS

```css
* { font-family: Arial; }

th {
	background-color: teal;
	color: white;
}

span {
	font-style: italic;
font-size: 16px;
font-weight: bold;
}

table {
	border : 1px solid black;
}

.prix {
	background-color : LightGray;
}
```

## TD n°2 du 29 septembre 2017

![PPT](pdf-icon.png) [Présentation](TD2/TD2.pdf)

### Exercice 1

```
Déclaration d'indépendance du cyberespace

La Déclaration d'indépendance du cyberespace est un document rédigé le 8 février 1996 à Davos en Suisse par John Perry Barlow, un des fondateurs de l'Electronic Frontier Foundation. Il soutient l'idée qu'aucun gouvernement (ou qu'aucune autre forme de pouvoir) ne peut s'imposer et s'approprier Internet, alors en pleine extension. Il a été écrit en partie en réponse à l'adoption de la Loi sur les télécommunications de 1996 aux États-Unis.

Contenu

" Governments of the Industrial World, you weary giants of flesh and steel, I come from Cyberspace, the new home of Mind. On behalf of the future, I ask you of the past to leave us alone. You are not welcome among us. You have no sovereignty where we gather. "
— John Perry Barlow, A Declaration of the Independence of Cyberspace

La Déclaration énonce, dans seize paragraphes courts, le refus de l'appropriation d'internet par un gouvernement extérieur, en particulier celui des États-Unis. Il affirme que les États-Unis n'ont pas eu le "consentement des gouvernés" pour appliquer leurs lois sur Internet, et que l'Internet est à l'extérieur des frontières de n'importe quel pays. Il précise qu'Internet se régule lui-même, avec ses propres codes et langages sociaux, basé sur l'éthique de réciprocité. Il le fait dans un langage évocateur de la Déclaration d'Indépendance des États-Unis, ce qui est flagrant dans ses derniers paragraphes. Bien que le document mentionne la Loi sur les télécommunications, il accuse également la Chine, l'Allemagne, la France, la Russie, Singapour, et l'Italie d'étouffer l'Internet.

Contexte

Au moment où le document a été rédigé, Barlow avait déjà beaucoup écrit sur Internet et ses phénomènes sociaux et juridiques3. C'est également l'un des membres fondateurs de l'Electronic Frontier Foundation. L'un de ses travaux les plus connus reste " The Economy of Ideas ", alors publié en mars 1994 dans le magazine Wired, il y avait fait allusion à Thomas Jefferson et certaines des idées qu'il écrirait dans sa déclaration.

Critiques

En raison de son objet, le travail de Barlow est rapidement devenu célèbre et largement diffusé sur Internet. Dans les trois mois, environ 5 000 sites avaient des copies de la Déclaration. À neuf mois, ce nombre a été estimé à 40 000. Pour aborder la vision de Barlow d'un Internet autonome, un magistrat virtuel a été mis en place par l'Institut de droit du cyberespace, désormais hébergé par le "Chicago-Kent College of Law". Les magistrats seraient nommés par l'Institut et ainsi que par d'autres groupes juridiques afin de résoudre les différends en ligne. En dehors d'Internet, les réponses seront moins positives.

Liens externes

(en) Déclaration d'indépendance du cyberespace [archive] : original, en anglais
Déclaration d'indépendance du cyberespace [archive] : traduction française
Site de l'Electronic Frontier Foundation [archive] (EFF)
```

URLs à utiliser :
* https://projects.eff.org/~barlow/Declaration-Final.html
* http://editions-hache.com/essais/barlow/barlow2.html
* https://www.eff.org/

#### Correction (Exercices 1 & 2)
```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>Titre</title>
	</head>
	<body>
		<h1>Déclaration d'indépendance du cyberespace</h1>
		<p>
			La Déclaration d'indépendance du cyberespace est un document rédigé le 8 février 1996 à Davos en Suisse par John Perry Barlow, un des fondateurs de l'Electronic Frontier Foundation. Il soutient l'idée qu'aucun gouvernement (ou qu'aucune autre forme de pouvoir) ne peut s'imposer et s'approprier Internet, alors en pleine extension. Il a été écrit en partie en réponse à l'adoption de la Loi sur les télécommunications de 1996 aux États-Unis.
		</p>
		<h2>Contenu</h2>

		<quote>
			" Governments of the Industrial World, you weary giants of flesh and steel, I come from Cyberspace, the new home of Mind. On behalf of the future, I ask you of the past to leave us alone. You are not welcome among us. You have no sovereignty where we gather. "
		</quote>
		<p>
			<em>— John Perry Barlow, A Declaration of the Independence of Cyberspace</em>
		</p>
		<p>
			La Déclaration énonce, dans seize paragraphes courts, le refus de l'appropriation d'internet par un gouvernement extérieur, en particulier celui des États-Unis. Il affirme que les États-Unis n'ont pas eu le "consentement des gouvernés" pour appliquer leurs lois sur Internet, et que l'Internet est à l'extérieur des frontières de n'importe quel pays. Il précise qu'Internet se régule lui-même, avec ses propres codes et langages sociaux, basé sur l'éthique de réciprocité. Il le fait dans un langage évocateur de la Déclaration d'Indépendance des États-Unis, ce qui est flagrant dans ses derniers paragraphes. Bien que le document mentionne la Loi sur les télécommunications, il accuse également la Chine, l'Allemagne, la France, la Russie, Singapour, et l'Italie d'étouffer l'Internet.
		</p>
		<h2>Contexte</h2>
		<p>
			Au moment où le document a été rédigé, Barlow avait déjà beaucoup écrit sur Internet et ses phénomènes sociaux et juridiques3. C'est également l'un des membres fondateurs de l'Electronic Frontier Foundation. L'un de ses travaux les plus connus reste " The Economy of Ideas ", alors publié en mars 1994 dans le magazine Wired, il y avait fait allusion à Thomas Jefferson et certaines des idées qu'il écrirait dans sa déclaration.
		</p>
		<h2>Critiques</h2>
		<p>
			En raison de son objet, le travail de Barlow est rapidement devenu célèbre et largement diffusé sur Internet. Dans les trois mois, environ 5 000 sites avaient des copies de la Déclaration. À neuf mois, ce nombre a été estimé à 40 000. Pour aborder la vision de Barlow d'un Internet autonome, un magistrat virtuel a été mis en place par l'Institut de droit du cyberespace, désormais hébergé par le "Chicago-Kent College of Law". Les magistrats seraient nommés par l'Institut et ainsi que par d'autres groupes juridiques afin de résoudre les différends en ligne. En dehors d'Internet, les réponses seront moins positives.
		</p>
		<h2>Liens externes</h2>
		<p>
			<ul>
				<li><a href="https://projects.eff.org/~barlow/Declaration-Final.html">(en) Déclaration d'indépendance du cyberespace [archive] : original, en anglais</a></li>
				<li><a href="#">Déclaration d'indépendance du cyberespace [archive] : traduction française</a></li>
				<li>Site de l'<a href="https://www.eff.org/">Electronic Frontier Foundation [archive] (EFF)</a></li>
			</ul>	
		<p>
	</body>
</html>
```

### Exercice 3

URL de l'image à utiliser :
* https://langages-web.github.io/TD2/photo.png

### Exercice 4

URL à utiliser :
* https://langages-web.github.io/TD2/photo-grande.png

#### Correction (Exercices 3 & 4)

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>Titre</title>
	</head>
	<body>
		<h1>John Doe</h1>
		<em>Dévéloppeur Web</em><br>
		<a href="https://langages-web.github.io/TD2/photo-grande.png"><img src="https://langages-web.github.io/TD2/photo.png" alt="John Doe"></a>
		<p>Développeur web indépendant, j’interviens sur tous types de projets de création et refonte de site internet.</p>
		<h2>Compétences</h2>
		<ul>
			<li>HTML / CSS</li>
			<li>Javascript</li>
			<li>PHP / MySQL</li>
		</ul>
		<h2>Formation</h2>
		<ul>
			<li><strong>2004</strong> : Ingénieur ESIEE option telecom</li>
			<li><strong>1999</strong> : BAC S</li>
		</ul>
	</body>
</html>
```

## TD n°1 du 22 septembre 2017

![PPT](pdf-icon.png) [Présentation](TD1/TD1.pdf)

![PPT](pdf-icon.png) [Support de cours de Stéphanie Walter](TD1/initiation-HTML-CSS.pdf)

![HTML](html-icon.png) <a href="TD1/avec-CSS.html" target="_blank">Exemple 1 - Une page avec CSS</a>

![HTML](html-icon.png) <a href="TD1/sans-CSS.html" target="_blank">Exemple 2 - La même page sans CSS</a>

![HTML](html-icon.png) <a href="TD1/compare.html" target="_blank">Comparatif avec et sans CSS</a>

![HTML](html-icon.png) <a href="TD1/t1.html" target="_blank">Ma première page Web publiée</a>

# Squelette de base d'une page HTML

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>Titre</title>
	</head>
	<body>
	</body>
</html>
```

# Liens utiles
![LIEN](link-icon.png) [Balises HTML avec leurs caractéristiques](http://htmlreference.io/)
![LIEN](link-icon.png) [Memento des propriétés CSS](https://openclassrooms.com/courses/apprenez-a-creer-votre-site-web-avec-html5-et-css3/memento-des-proprietes-css)