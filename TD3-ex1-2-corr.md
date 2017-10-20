## TD n°3 - exercices 1 & 2 - correction


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