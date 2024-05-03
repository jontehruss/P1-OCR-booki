
1. Containers (avec display: flex):
```css
div {
    display: flex; /* définit l’élément comme un élément flexbox. */
    flex-direction: column | row; /* définit la direction de l’élément (colonne ou ligne).*/
    justify-content: space-between | center | start | end; /* définit la position des éléments sur la page.*/
    align-items: center | flex-start | flex-end; /* définit la position des éléments dans la direction de l’élément.*/
    flex-wrap: nowrap | wrap; /* définit si les éléments peuvent être décalés ou non sur une nouvelle ligne.  */
}
```

2. Polices (paragraphes, titres):
```css
.polices {
   font-size: xpx; /* définit la taille de la police.*/
    font-family: 'x' | 'y' | 'z'; /* définit la police utilisée pour l’élément.*/
    line-height: xpx; /* définit la hauteur des lignes.*/
    color: #rgb(x, y, z); /* définit la couleur de l’élément.*/ 
}
```

3. Listes:
```css
.listes {
    list-style-type: none | disc | circle | square; /* définit le style de la liste (aucun, disc, cercle ou carré).*/
    list-style-position: inside | outside; /* définit la position du style de la liste (dans l’intérieur ou à l’extérieur de l’élément).*/
    list-style-width: 12px; /* définit la largeur du style de la liste.*/
}
```

4. Images:
```css
.images {
    background-image: url('x'); /* définit l’image de fond de l’élément.*/
    background-size: cover | contain; /* définit la taille de l’image de fond (recouvrir ou contenir).*/
    object-fit: cover | contain; /* définit la façon dont l’image est affichée (recouvrir ou contenir).*/
    height: 10px; /* définit la hauteur de l’élément.*/
    width: 10px; /* définit la largeur de l’élément.*/
}
```

```css
.hebergements-cards {} s'applique à tous les element dans le conteneur.

.hebergements-cards .card {} cible uniquement les éléments avec la classe "card".

.hebergements-cards card {} cible également uniquement les éléments avec la classe "card" en se basant sur leur nom de classe plutôt que tout autre caractéristique.
```