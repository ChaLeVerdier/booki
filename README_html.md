# booki-starter-pack

            ************** GLOSSAIRE html **************

- <aria"-labels"> : "Accessible Rich Internet Applications" définit un ensemble d'attributs pour améliorer la sémantique des éléments HTML et fournir des informations supplémentaires aux technologies d'assistance.

Le <span> est utilisé pour encapsuler un élément. Les balises <span> sont des éléments en ligne qui sont généralement utilisés pour appliquer des styles spécifiques à une partie du contenu sans changer la structure du document.

L'attribut <aria-hidden> est utilisé pour indiquer aux technologies d'assistance que le contenu d'un élément n'est pas pertinent pour la signification ou l'interaction de la page. Lorsque <aria-hidden="true"> est appliqué à un élément, son contenu est complètement masqué pour les utilisateurs d'outils d'assistance. Cela signifie que le contenu ne sera pas perçu par les lecteurs d'écran ou autres dispositifs d'assistance, et il ne sera pas annoncé ou rendu accessible à l'utilisateur.

              ************** TESTS html **************

Pour le HEADER :

Pour le logo reviendra à la page d'accueil grace à : ./ (exp : <a href="./" title="Logo du site">)

Ajout d'une liste avec attributs "ul" et "li" puis d'un lien "a" pour ancrer un élément dans la page.

<nav>
    <a href="#hebergement-a-marseille">Hébergement</a> 
    <a href="#activite-a-marseille">Activités</a>
</nav>

Pour le FORMULAIRE :

<section class="search-bar">
    <i class="fa-solid fa-location-dot"></i>
    <h2 class="search-bar-content">Marseille, France</h2>
    <a href="#">Recherche</a>
</section>

            ************** CHECK LIST html **************

- Fichier CSS relié : ok
- Non demandé : ajout de l'icon "shortcut icon" pour l'onglet : ok
- Header : revoir avec l'attribut nav : ok

  - # pour simuler présence du lien : ok
    - et pour créer une ancre dans la page.

les "id" sont plus important que les "class" donc placé en prio : <section id="hebergements" class="hebergements" > en raison de leur spécificité élevée, de leur unicité et de leur priorité dans l'application des styles.

- Section Recherche et filtre : ok

  - Ajout du titre H1 + paragraphe p : ok
  - Intégrer un formulaire Recherche : ok avec "form" et flexbox
  - Intégrer un formulaire Filtre : ok avec une liste et flexbox

- Section Hébergements Populaires Activités : ok
  Hébergement et populaire : Avec div et non section pour éviter d'avoir à ajouter un titre (W3C).

  - Intégrer section "Hébergements" : ok
    - Ajouter les "6 cards" en s'appuyant sur celles de "Populaires" : ok
    - Changer les images "img src" : ok
    - Changer les titres, textes et prix avec div class="card-content" ; "card-txt" ; "card-title" ; "card subtitle" ; "card-rating" (étoile : fa) : ok
    - Utilisation du CSS clac pour obtenir les gap entre les cards
  - Intégrer section "Populaires" : ok (déjà fourni)
  - Intégrer section "Activités" : ok

- Section Footer : ok
  - Intégrer section "Footer" : ok
