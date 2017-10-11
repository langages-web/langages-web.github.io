# Sommaire

* <a href="#tds">TDs</a>
  * <a href="#td-n4-du-13-octobre-2017">TD n°4 du 13 octobre 2017</a>
  * <a href="#td-n3-du-6-octobre-2017">TD n°3 du 6 octobre 2017</a>
  * <a href="#td-n2-du-29-septembre-2017">TD n°2 du 29 septembre 2017</a>
  * <a href="#td-n1-du-22-septembre-2017">TD n°1 du 22 septembre 2017</a>
* <a href="#squelette-de-base-dune-page-html">Squelette de base d'une page HTML</a>
* <a href="#liens-utiles">Liens utiles</a>

# TDs

## TD n°4 du 13 octobre 2017

### Exercice 1

![TD4-ex1](TD4/TD4-ex1.jpg)

URLs des images à utiliser :
* https://langages-web.github.io/TD4/titre.png
* https://langages-web.github.io/TD4/bandeau.jpg
* https://langages-web.github.io/TD4/p1.jpg
* https://langages-web.github.io/TD4/p2.jpg
* https://langages-web.github.io/TD4/p3.jpg

index.html :
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

## TD n°3 du 6 octobre 2017

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