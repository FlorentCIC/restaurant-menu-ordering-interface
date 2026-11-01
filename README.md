# Restaurant Menu Ordering Interface

## Présentation du projet

Ce projet consiste à développer une interface web responsive permettant aux utilisateurs de découvrir différents restaurants, de consulter leurs menus et de sélectionner les repas proposés.

L'application présente quatre restaurants et leurs cartes respectives, dans le but de proposer une expérience de consultation simple, intuitive et adaptée à différents supports.

## Fonctionnalités

- Page d'accueil présentant les quatre restaurants.
- Accès aux pages individuelles de chaque restaurant.
- Consultation des menus et des plats proposés.
- Interface de commande avec présentation des tarifs.
- Navigation entre les différentes pages.
- Adaptation de l'affichage aux ordinateurs, tablettes et smartphones.

## Technologies utilisées

- **HTML5** : structure des pages web.
- **SCSS** : organisation et écriture des feuilles de style.
- **CSS3** : mise en forme et adaptation responsive.
- **Sass** : compilation du SCSS en CSS.

## Structure du projet

```text
restaurant-menu-ordering-interface/
│
├── images/                  # Ressources visuelles
├── pages/                   # Pages des quatre restaurants
│   ├── resto-1.html
│   ├── resto-2.html
│   ├── resto-3.html
│   └── resto-4.html
│
├── index.html               # Page d'accueil
├── style.scss               # Feuille de style source
├── style.css                # Feuille de style compilée
├── package.json             # Configuration et scripts Sass
├── package-lock.json        # Versions des dépendances
└── README.md                # Documentation du projet
```

## Installation et lancement du projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/FlorentCIC/restaurant-menu-ordering-interface.git
```

### 2. Accéder au dossier

```bash
cd restaurant-menu-ordering-interface
```

### 3. Installer les dépendances

```bash
npm install
```

### 4. Compiler les fichiers SCSS

```bash
npm run build
```

Cette commande compile `style.scss` en `style.css`.

Pour lancer la compilation automatique pendant le développement :

```bash
npm run sass
```

Le site peut ensuite être consulté en ouvrant le fichier `index.html` dans un navigateur.

## Responsive Design

L'interface a été conçue pour s'adapter aux différentes tailles d'écran : ordinateurs, tablettes et smartphones.

Une attention particulière a été portée à la disposition des éléments, à la lisibilité des menus et à l'adaptation des cartes des restaurants sur les petits écrans.

## À propos du projet

Ce projet est issu du Projet 3 de la formation Développeur Web d'OpenClassrooms.

Il a été repris et retravaillé afin d'améliorer l'organisation du code, la cohérence des feuilles de style et l'adaptation de l'interface aux différents formats d'écran.

**Objectif :** concevoir et intégrer une interface web responsive de consultation de menus de restaurants.
