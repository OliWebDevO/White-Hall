
### `<meter>` :

**Définition** : l'élément HTML `<meter>` permet de créer un rendu visuel à partir de données chiffrées, et ce sous forme d'une barre de niveau.

**Attributs de l'élément `<meter>`** :
 - Min : Cet attribut représente la valeur minimale que peut prendre la mesure.
 - Max : Cet attribut représente la valeur maximale que peut prendre la mesure.
 - Low : Cet attribut représente la valeur maximale à partir de laquelle la mesure est considérée comme basse.
 - High : Cet attribut représente la valeur minimale à partir de laquelle la mesure est considérée comme haute.
 - Optimum : Cet attribut représente la valeur idéale pour la mesure. Si la valeur de optimum est inférieure à low, cela signifie que les valeurs les plus petites sont meilleures; si sa valeur est supérieure à high, cela signifie que les valeurs les plus grandes sont meilleures; enfin, s'il est compris entre low et high, cela signifie que les extrêmes ne sont pas les meilleures grandeurs.
 - Value : Cette attribut représente la valeur actuelle de la mesure. Cet attribut est obligatoire.

   Il est important de placer un élément HTML `<label>` devant `<meter>` afin de donner une description relative à la barre de niveau.

   Exemple : `<label for="fuel">Fuel level:</label>`

   Cette exemple de `<label>` permet de donner l'indication : "Fuel level:" devant la barre de niveau créer par `<meter>`.

**Exemple approfondi** : 

   Code : `<label for="fuel">Fuel level:</label>`

   `<meter id="fuel" min="0" max="100" low="33" high="66" optimum="80" value="50">at 50/100</meter>`

   Cet exemple donne une barre de niveau à moitié remplie (50/100). De plus la barre est de couleur jaune puisque la valeur optimum (80) est relativement éloignée de la valeur définie (50).
