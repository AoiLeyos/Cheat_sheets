L'ID > la classe : l'id prend toujours la priorité sur celui de la classe en raison de la spécificité plus élevée des IDs par rapport au classes.

On peut implementer les IDs et les classes dans html :
### EX : 
`<div id="monElement" class="maClasse">`
puis on spécifie dans le fichier CSS :

**Style appliqué via l'ID** :

#monElement {
    background-color: blue;
    color: white
}

**Style appliqué via la classe** :

.maClasse {
    padding: 10px;
    border: 1px solid black;
}

Pseudo classe : une classe mais qui fonctionne seulement si il y a une action particulière 

ex: *hover qui active la classe quand on passe la souris dessus*

#### Les position :

**Position relative:** il se positionne par rapport à sa position normale dans le flux du document, on peut le déplacer avec "top,right,bottom,left"

**Position absolu:** se positionne par rapport a son premier ancêtre positionné, sinon se positionne par apport au document (ne prend pas en compte les élement 'static')

**Position fixe:** l'élement reste fixe même lorsque la page défile

**Position flottant:** Les élemens peuvent être retirés du flux du document et placés sur le côté gauche ou droit de leur conteneur

mettre la balise <link href=""> pour lier au css 


**justify-content:** (flex-start (default),flex-end,center,space-between,space-around,space-evenly)

**align-items:** (flex-start,flex-end,center,baseline,stretch(default))
flex-direction: (row(default),row-reverse,column,column-reverse)

**order:** intégré un chiffre , par défault 0, 1 priorité,-1 non priorisé

**align-self:** flex-start,flex-end,center,baseline,stretch

**flex-wrap:** nowrap (default),wrap,wrap-reverse

**flex-flow:** flex-direction & flex-wrap

**align-content:** flex-start,flex-end,center,space-between,space-around,space-evenly,stretch (default)
