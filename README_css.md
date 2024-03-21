# booki-starter-pack

            ************** GLOSSAIRE css **************

<\*> : "wildcard" ou "astérisque". Il peut être utilisé pour représenter tous les éléments ou toutes les valeurs dans une certaine catégorie.

<root> : souvent utilisée pour définir des variables CSS globales (variables personnalisées)[généralement associé à la pseudo-classe :root (racine du doc)]

un exp

<!-- :root {
--main-color: #3498db;
--background-color: #ecf0f1;
}

body {
background-color: var(--background-color);
color: var(--main-color);
} -->

<inherit> les propriétés CSS d'un élément sont automatiquement dérivées de son parent, évite d'avoir à spécifier explicitement la valeur à chaque fois. Cela permet d'établir une relation de style cohérente et de simplifier la maintenance du code CSS.

<height: auto;> La propriété CSS utilisée pour spécifier que la hauteur d'un élément doit être automatiquement ajustée en fonction de son contenu. Cela signifie que l'élément s'adaptera dynamiquement pour contenir tout son contenu sans avoir besoin d'une hauteur spécifique définie manuellement.
Valeur couramment utilisée pour les éléments qui ont un contenu variable ou dynamique, comme les boîtes de texte, les conteneurs d'images, etc.

<object-fit: cover;> appliqué à une image. L'image sera ajustée pour remplir entièrement la zone de conteneur tout en conservant son rapport hauteur/largeur d'origine. Si l'image est plus grande que la zone de conteneur, elle sera élargie ou réduite pour couvrir entièrement la zone sans déformer l'image, et toute partie de l'image qui dépasse de la zone sera coupée.

<overflow: hidden;> est une manière de contrôler le comportement de débordement du contenu à l'intérieur d'un élément en le cachant s'il dépasse les limites de cet élément.

<display: flex;> déclare que l'élément est un conteneur flexible,
<justify-content: center;> centrer les éléments enfants horizontalement à l'intérieur du conteneur flexible.
<justify-content: space-between;>, les éléments flexibles seront disposés avec un espacement égal entre eux,
<justify-content: flex-start;> les éléments flexibles seront alignés au début du conteneur flex.
<flex-wrap : wrap;> propriété CSS utilisée avec Flexbox pour définir si les éléments enfants d'un conteneur flex doivent être ajustés sur une seule ligne ou peuvent être répartis sur plusieurs lignes selon l'espace disponible.

<rating> est souvent utilisé pour désigner une classe ou un élément HTML qui représente une évaluation ou une note attribuée à un produit, un service ou toute autre entité.

<Etude du code pour le footer > 
.site-footer>* { 
    flex: 1; 
    padding: 20px;
}
<*> applique un style à tous les enfants direct d'un élément. 
<flex: 1> : Flexbox pour que chaque élément enfant direct prenne autant d'espace disponible que possible dans le conteneur parent et en répartissant de manière équitable l'espace entre les enfants également.

<kebab-case> est une convention de nommage des variables, identifiants de classe, noms de fichiers... Cette convention veut que les mots soient en minuscules et séparés par des tirets. Cela rend le code plus lisible et plus cohérent.

            ************** QUESTIONS css **************

Pour Stéphane :
Dans Body : Pretinant d'ajouter "min-height = 100%" pour qu'il s'adapte à tous les écran ou pas necessaire ?

font-size : Mieux en "rem" ? s'adapte mieux à tout type d'écran, surtout pour l'accessibilité _/
/_ ou font-size: 1.37rem; soit 16px = 1rem \*/

            ************** CHECK LIST css **************

- Fichier CSS relié : ok
- Réaliser le header :
  Placer le logo avec 30px de marge pour chaque coté : ok
  Placer la navigation, pour ça créer une class header-nav
