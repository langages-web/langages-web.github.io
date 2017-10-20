## TD n°4 - exercice 3 - correction


index.html :_
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
      <img src="https://langages-web.github.io/TD4/titre.png" alt="hifidiscount">
      <div id="menu">
        <a href="#">Amplificateur</a> | 
        <a href="#">Enceintes</a> | 
        <a href="#">Casques</a> | 
        <a href="#">Meubles et supports</a>
      </div>
      <img src="https://langages-web.github.io/TD4/bandeau.jpg" alt="bandeau">
      <div id="produits">
        <table>
          <tr>
            <td>
              <img src="https://langages-web.github.io/TD4/p1.jpg" alt="JBL ES80">
            </td>
            <td>
              <span class="categorie">Enceinte colonne</span><br>
              JBL ES80 (la paire)<br><br>
              <span class="ancien-prix">899 €</span>
              <span class="prix">349 €</span>
            </td>
          </tr>
          <tr>
            <td>
              <img src="https://langages-web.github.io/TD4/p2.jpg" alt="JBL ES80">
            </td>
            <td>
              <span class="categorie">Platine vinyle hi-fi</span><br>
              Pro-Ject Debut 3 DC<br><br>
              <span class="ancien-prix">399 €</span>
              <span class="prix">279 €</span>
            </td>
          </tr>
          <tr>
            <td>
              <img src="https://langages-web.github.io/TD4/p3.jpg" alt="JBL ES80">
            </td>
            <td>
              <span class="categorie">Casque hi-fi</span><br>
              Sennheiser HD600<br><br>
              <span class="ancien-prix">899 €</span>
              <span class="prix">349 €</span>
            </td>
          </tr>
        </table>
      </div>
    </div>
  </body>
</html> 
```

_styles.css :_
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

#menu {
  background: #393e46;
  text-align: center;
  color: #eeeeee;
  font-size: 18px;
}

#menu a {
  color: #eeeeee;
  text-decoration: none;
  
}

.categorie {
  font-size: 13px;
}

.ancien-prix {
  color: #999999;
  text-decoration: line-through;
}

.prix {
  color: #00adb5;
  font-size: 25px;
  font-weight: bold;
}
```

