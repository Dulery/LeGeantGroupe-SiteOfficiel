# Le Géant Groupe — Site Officiel

🌐 **[legéantgroupe.fr](https://www.legéantgroupe.fr)**

Site web officiel de la communauté **Le Géant Groupe**, un groupe WhatsApp francophone actif depuis 2017. Le site centralise l'histoire du groupe, ses événements, ses membres, ses actualités, et propose des fonctionnalités interactives comme un salon de chats animé.

---

## Sommaire

- [Objectif du site](#objectif-du-site)
- [Pages et fonctionnalités](#pages-et-fonctionnalités)

---

## Objectif du site

Le site a pour but de regrouper en un seul endroit tout ce qui concerne le Géant Groupe :

- Présenter l'**histoire** et les **origines** du groupe depuis 2017
- Lister les **membres importants** et leurs rôles
- Publier des **actualités** et annoncer les **événements**
- Conserver les **archives** de la vie du groupe
- Proposer une page d'**infos hebdomadaires** avec des articles d'actualité et une recette du jour
- Offrir un mini-jeu interactif (**Meow**) où les membres peuvent ajouter leur chat dans un salon 2D animé

---

## Pages et fonctionnalités

### `index.html` — Accueil
Page principale avec :
- Présentation du Géant Groupe
- Timeline historique (de 2017 à aujourd'hui)
- Bouton pour rejoindre le groupe WhatsApp
- Données dynamiques chargées depuis Firebase (Firestore)

### Actualités
Affiche les dernières nouvelles du groupe publiées par les admins, triées par date, avec titre, description et image.

### Événements
Liste les événements à venir et passés organisés par le Géant Groupe, avec image de couverture et statut.

### Archives
Conserve l'historique du groupe : anciens contenus, souvenirs, et les anciennes Infos Hebdomadaires — une tradition où les admins publiaient chaque semaine un récapitulatif de la vie du groupe.

### Membres
Présente les responsables (fondateur, admins, modérateurs) et les membres notables, avec leur rôle et leur histoire dans le groupe.

### Infos Hebdomadaires
Page d'actualités générales : articles de presse en français filtrables par catégorie (Politique, Technologie, Sport, Business, Science) et une recette du jour.

### Meow — Salon des Chats 🐱
Mini-jeu interactif réservé aux membres. Avec un code d'accès nominatif reçu via WhatsApp, chaque membre peut ajouter la photo de son chat. Tous les chats apparaissent alors dans un salon 2D animé où ils rebondissent sur un canvas HTML5.
