# 🍯 Coopérative Thimdrine — Site Vitrine

Site vitrine responsive conçu et développé pour la **Coopérative Thimdrine**, un regroupement de 25 femmes de la région de Nador (Rif, Maroc) produisant du miel de thym, de l'huile d'olive extra vierge et de la confiture de figue de barbarie.

## 🌐 Liens du Projet

* **Site déployé (GitHub Pages)** : <https://chrdalachraf85-blip.github.io/sprint1-css-html/>

* **Dépôt GitHub** : <https://github.com/chrdalachraf85-blip/sprint1-css-html>

* **Maquette Figma** : [Lien vers la maquette Figma](https://www.figma.com/design/Cy4ik0pqJzKmxNujivD7c2/Thimdrine---site-vitrine-d%E2%80%99une-coop%C3%A9rative-du-Rif--Copy-?node-id=2049-862&t=62hXoxgxC2ocNd0L-1)

* **Gestion de projet (Jira / GitHub Projects)** : [Lien vers le Kanban](https://github.com/users/chrdalachraf85-blip/projects/1) *(Remplacez par votre lien Board)*

## 📑 Sommaire

* [Présentation du Projet](#-présentation-du-projet)

* [Arborescence du Site](#-arborescence-du-site)

* [Aperçu & Captures d'écran](#-aperçu--captures-décran)

* [Technologies & Normes](#-technologies--normes)

* [Charte Graphique](#-charte-graphique)

* [Spécifications Techniques](#-spécifications-techniques)

* [Auteur](#-auteur)

## 📌 Présentation du Projet

Ce projet s'inscrit dans le cadre du **Brief 1 (YouCode Nador)**. L'objectif est de fournir à la présidente de la coopérative, Mme Fadma, une présence en ligne professionnelle permettant de présenter l'histoire de la coopérative, mettre en valeur ses produits du terroir et recevoir des demandes de commandes d'acheteurs.

### Fonctionnalités principales :

* **4 pages interconnectées** avec un en-tête (`<header>`) et un pied de page (`<footer>`) communs.

* **Formulaire de commande** complet avec validation native en HTML5 sans JavaScript.

* **Mise en page 100% Flexbox & CSS Grid** réactive et adaptée aux écrans mobiles et ordinateurs.

* **Accessibilité et sémantique HTML5** (un seul `<h1>` par page, structure claire, navigation fluide).

## 📄 Arborescence du Site

```
sprint1-css-html/
├── index.html            # Page d'accueil (Hero banner, présentation, produits phares, CTA)
├── produits.html         # Catalogue des 6 produits en cartes Flexbox/Grid
├── a-propos.html         # Histoire, valeurs et chiffres clés de la coopérative
├── contact.html          # Formulaire de demande de commande avec validation HTML5
├── css/
│   ├── style.css         # Variables CSS global (:root), normalisation, header & footer
│   ├── acceuil.css       # Styles spécifiques à la page d'accueil
│   ├── produits.css      # Styles du catalogue produit
│   ├── a_propos.css      # Styles de la page À propos
│   └── contact.css       # Styles du formulaire et de la bannière contact
└── images/               # Logos, illustrations SVG et photographies des produits

```

## 🛠️ Technologies & Normes

* **HTML5** : Structuration sémantique (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).

* **CSS3 Natif** :

  * Déclaration des variables globales via `:root`.

  * Mise en page Flexbox et Grid.

  * Media Queries pour l'adaptation mobile (`@media (min-width: 1024px)`).

* **Git & GitHub** :

  * Historique de commits respectant la convention **Conventional Commits** (`feat:`, `fix:`, `style:`, `docs:`).

  * Déploiement continu via **GitHub Pages**.

## 🎨 Charte Graphique

La charte graphique s'inspire des couleurs naturelles du terroir du Rif :

* **Thym / Vert Olive** : `--couleur-thym: #3E5C35;`

* **Thym Foncé** : `--couleur-thym-fonce: #2C4326;`

* **Miel** : `--couleur-miel: #E0A526;`

* **Figue de barbarie** : `--couleur-figue: #8A2846;`

* **Fond Lin / Sable** : `--couleur-lin: #FBF6EC;` | `--couleur-sable: #F3EAD7;`

* **Polices** :

  * Titres : `'Lora', Georgia, serif`

  * Corps de texte : `'Source Sans 3', Arial, sans-serif`

## ⚙️ Spécifications Techniques

* **Formulaire Native HTML Validation** :

  * Champs requis : `required`

  * Format d'adresse e-mail : `type="email"`

  * Sélection de quantité minimale : `min="1"`

## 👤 Auteur

**Achraf Cherdal**

Apprenant Développeur Web @ **YouCode Nador**

* **GitHub** : [@chrdalachraf85-blip](https://github.com/chrdalachraf85-blip)