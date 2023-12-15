
### `<meter>` :

**Définition** : l'élément HTML `<meter>` permet de créer un rendu visuel à partir de données chiffrées, et ce sous forme d'une barre de progression.

**Attributs de l'élément `<meter>`** :
 - Min : Cet attribut représente la valeur minimale que peut prendre la mesure.
 - Max : Cet attribut représente la valeur maximale que peut prendre la mesure.
 - Low : Cet attribut représente la valeur maximale à partir de laquelle la mesure est considérée comme basse.
 - High : Cet attribut représente la valeur minimale à partir de laquelle la mesure est considérée comme haute.
 - Optimum : Cet attribut représente la valeur idéale pour la mesure. Si la valeur de optimum est inférieure à low, cela signifie que les valeurs les plus petites sont meilleures; si sa valeur est supérieure à high, cela signifie que les valeurs les plus grandes sont meilleures; enfin, s'il est compris entre low et high, cela signifie que les extrêmes ne sont pas les meilleures grandeurs.
 - Value : Cette attribut représente la valeur actuelle de la mesure. Cet attribut est obligatoire.

   Il est important de placer un élément HTML `<label>` devant `<meter>` afin de donner une description à la barre de progression.

   Exemple : `<label for="fuel">Fuel level:</label>`

   Cette exemple de `<label>` permet de donner l'indication : "Fuel level:" devant la barre de progression créer par `<meter>`.

**Exemple approfondi** : 

   Code : `<label for="fuel">Fuel level:</label>`

   `<meter id="fuel" min="0" max="100" low="33" high="66" optimum="80" value="50">at 50/100</meter>`

   [exemple] [http://cepegra-labs.be/webdesign/fed2023/oliver/03_html-css/02_Tests&Exercices/29_Exemple_De_Meter/index]

   Cet exemple montre une barre de progression à moitié remplie (50/100). De plus la barre est de couleur jaune puisque la valeur définie (50) est plus petite que l'attribut high (66); si la valeur est définie sur un nombre plus petit que l'attribut low, la barre est rouge.

**Compatibilité Web ** : 

   L'élément HTML `<meter>` est compatible avec tous les navigateurs web sauf WebView d'Android.


   

### `<progress>` :

**Définition** : Tout comme l'élément HTML `<meter>`, l'élément HTML `<progress>` permet de créer un rendu visuel à partir de données chiffrées, et ce sous forme d'une barre de progression. Cependant les données nécéssaires soint moindres, ce qui rend sa réalisation plus simple, mais également moins complète.

**Attributs de l'élément `<progress>`** :
 
 - Max : Cet attribut représente la valeur maximale que peut prendre la mesure.
 
 - Value : Cette attribut représente la valeur actuelle de la mesure. Cet attribut est obligatoire.

   Il est important de placer un élément HTML `<label>` devant `<progress>` afin de donner une description à la barre de progression.

   Exemple : `<label for="file">File progress:</label>`

   Cette exemple de `<label>` permet de donner l'indication : "File progress:" devant la barre de progression créer par `<progress>`.

**Exemple approfondi** : 

   Code : `<label for="file">File progress:</label>`

   `<<progress id="file" max="100" value="70">70%</progress>`

   [exemple] [http://cepegra-labs.be/webdesign/fed2023/oliver/03_html-css/02_Tests&Exercices/29_Exemple_De_Progress/index]

   Cet exemple montre une barre de progression remplie à 70%.


**Compatibilité Web ** : 

   L'élément HTML `<progress>` est compatible avec tous les navigateurs web existants.

