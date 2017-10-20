## TD n°4 - exercice 2 - fichiers à utiliser


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