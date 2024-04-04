# Projet Pixi Studio

Pixi Studio est une agence de développement web et design graphique spécialisée dans la création de sites web modernes et réactifs, offrant des solutions uniques et personnalisées à nos clients.

## Prérequis

Avant de commencer, assurez-vous d'avoir installé Node.js et npm sur votre machine. Ces outils sont nécessaires pour installer Sass et compiler les fichiers SCSS en CSS.

## Installation

Pour configurer le projet localement, suivez ces étapes :

```bash
git clone https://exempledepot.com/projet-pixi-studio.git
cd projet-piwi-studio
npm install
```

Cela installera toutes les dépendances nécessaires, y compris Sass.

<!-- ----------------------------------------------------------------------------------- -->

## Structure Sass

Notre structure Sass est conçue pour être modulaire et facile à maintenir :

sass/
|
|-- abstracts/
| |-- \_variables.scss # Variables globales pour les couleurs, typographies, etc.
| |-- \_mixins.scss # Mixins réutilisables pour les gradients, transitions, etc.
|
|-- base/
| |-- \_reset.scss # Reset/Normalize pour une base cohérente entre les navigateurs
| |-- \_typography.scss # Règles de base pour la typographie
|
|-- components/
| |-- \_buttons.scss # Styles des boutons
| |-- \_carousel.scss # Carrousels, sliders
|
|-- layout/
| |-- \_header.scss # Style de l'en-tête
| |-- \_footer.scss # Style du pied de page
|
|-- pages/
| |-- \_home.scss # Styles spécifiques à la page d'accueil
| |-- \_about.scss # Styles pour la page À propos
|
`-- main.scss # Fichier principal qui importe tous les fichiers SCSS

## Compilation Sass

Pour compiler vos fichiers Sass en CSS, utilisez la commande suivante :

```bash
npm run compile:sass
```

Cette commande surveille vos fichiers Sass pour tout changement et les compile automatiquement en CSS.

<!-- ----------------------------------------------------------------------------------- -->

## Contribution

Nous accueillons avec plaisir les contributions de la communauté ! Pour plus de détails sur comment contribuer, veuillez consulter notre fichier CONTRIBUTING.md.

<!-- ----------------------------------------------------------------------------------- -->

## Licence

Ce projet est publié sous la licence MIT. Voir le fichier LICENSE pour plus d'informations.
