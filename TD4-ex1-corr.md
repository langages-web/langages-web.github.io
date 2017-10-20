## TD n°4 - exercice 1 - correction


_styles.css :_
```css
/* Règle concernant l'ensemble du contenu */
body {
  background-color: #F6F6F6;
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}

/* Pour éviter que les liens ne soient soulignés */
a {
  text-decoration: none;
}

/* Pour les éléments ayant un fond bleu */
.fond-bleu {
  background-color: #62A9D2;
}

/* Bandeau gris en haut */
#bandeau {
  background-color: #43474A;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 160px;
}

/* Conteneur principal */
#contenu {
  position: relative;
  padding: 0;
  background-color: #FFFFFF;
  width: 605px;
  margin: 0 auto;
}

/* Section entete */
#entete {
  background-color: #43474A;
  border-bottom: 5px solid #62A9D2;
  padding-bottom: 20px;
}

/* Logo */
#entete span {
  font-family: serif;
  color: #FFFFFF;
  padding: 20px 10px;
  font-size: 30px;
}

/* Logo */
#entete span em {
  color: #62A9D2;
  font-size: 45px;
}

/* Lien en haut à droite */
#entete a {
  color: #A8B0B6;
  font-size: 12px;
  position: absolute;
  right: 0;
  top: 20px;
}

/* Section titre */
#titre {
  padding: 30px 0 40px;
}

/* Titre principal */
h1 {
  font-size: 32px;
  color: #555555;
  text-align: center;
}

/* Sous titre */
#titre div {
  color: #99A1A6;
  font-size: 13px;
  text-align: center;
  padding: 10px 70px;
}

/* Section réseaux sociaux */
#reseaux {
  padding: 20px;
  font-style: italic;
  color: #0F4666;
}

/* Boutons réseaux sociaux */
#lienTwitter, #lienFacebook {
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
.image {
  margin-top: 30px;
  background-color: #000000;
  color: #FFFFFF;
}

/* Image */
.image img {
  width: 100%;
}

/* Légende image */
.image div {
  padding: 20px;
  font-size: 21px;
  display : inline-block;
  width: 70%;
}

/* Lien sous image */
.image a {
  font-size: 12px;
  color: #FFFFFF;
  padding: 10px;
}

/* Sections de texte */
.texte {
  width: 39%;
  display: inline-block;
  margin: 30px;
}

/* Titres sections texte */
.texte h2 {
  color: #555555;
  font-size: 20px;
}

/* Paragraphes section texte */
.texte p {
  text-align: justify;
  color: #999999;
  font-size: 13px;
}

/* Liens section texte */
.texte a {
  color: #62A9D2;
  font-weight: bold;
  font-size: 13px;
}

```

