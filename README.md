# A&A Hotels

Site web vitrine pour A&A Hotels, réalisé en HTML, CSS et JavaScript.

## Lancer le site

Le projet est un site statique : aucune installation ni serveur applicatif n'est nécessaire.

1. Ouvrez le dossier du projet dans Visual Studio Code.
2. Ouvrez `index.html` dans un navigateur.

Pour une expérience de développement plus pratique, installez l'extension **Live Server** dans VS Code, puis faites un clic droit sur `index.html` et choisissez **Open with Live Server**.

## Pages

- `index.html` : accueil et présentation de l'hôtel.
- `A propos.html` : emplacements et services.
- `chambre.html` : chambres et suites disponibles.
- `reservation.html` : formulaire de réservation.
- `payement.html` : maquette de la page de paiement.

## Technologies et techniques utilisées

- **HTML** structure les pages, la navigation, les sections de contenu et les formulaires.
- **CSS** gère la présentation : couleurs, typographie, Flexbox et grilles pour les mises en page, ainsi que des transitions et effets au survol.
- Des **media queries** adaptent notamment la navigation et le pied de page aux petits écrans.
- **JavaScript** ajoute des interactions, comme l'ouverture du menu burger et le changement d'apparence de la navigation lors du défilement.
- Des **vidéos en arrière-plan** sont utilisées dans les bannières d'accueil et de présentation, avec une image de secours.
- La page de réservation présente un **carrousel d'images** réalisé avec jQuery et Slick Carousel.
- Font Awesome, Remix Icon, Google Fonts et Google Maps sont intégrés depuis des services externes.

Le site est statique : il n'utilise pas de serveur applicatif ni de base de données. Les formulaires ne sont pas reliés à un système de réservation, et la page de paiement est uniquement une maquette.

## Structure du projet

- Les fichiers `.css` définissent l'apparence des pages : couleurs, polices, espacements, grilles, formulaires et adaptation aux écrans mobiles. `footer.css` fournit le style de pied de page partagé.
- `index.js` contient les interactions JavaScript partagées, notamment le menu et la barre de navigation.
- `photo/` contient les images utilisées par le site, notamment les visuels des destinations de la page « À propos » : Venise, San Francisco, Marrakech, la Grèce, la Thaïlande et Aspen.
- `video/` contient les vidéos de fond de l'accueil et du bandeau de la page « À propos ».

## À savoir

- La page de paiement est une maquette : aucun paiement n'est traité. **N'entrez pas de véritables coordonnées bancaires.** 

- L'accueil et la page « À propos » partagent une palette olive et beige, assortie aux tons des pages de réservation. L'accueil et le bandeau d'introduction d'« À propos » ont une vidéo en arrière-plan, avec une photo de secours et un filtre sombre. La photo du yacht est dans la section « Nos Yachts » d'« À propos ».

- Certaines icônes, polices et dépendances de carrousel sont chargées depuis des services externes et nécessitent une connexion Internet.


Réalisé en projet d'équipe, ( Awa et Adile )


Ressources externes pour certaines icônes, polices et cartes, par exemple Font Awesome, Google Fonts et Google Maps.
images/videos libres de droits:
Pixabay 
https://pixabay.com/fr/ 
 unsplash :
 https://unsplash.com/fr