# 👕 Roblox Classic Clothing Maker

Un outil **100 % local** (une seule page HTML, aucun serveur, aucune donnée envoyée) pour créer
automatiquement des vêtements *classic* Roblox :

- **T-Shirt classic** → PNG 512×512
- **Shirt classic** → PNG 585×559 (template officiel)
- **Pants classic** → PNG 585×559 (template officiel)

## 🚀 Lancer l'outil

Ouvre simplement `index.html` dans ton navigateur (double-clic), c'est tout.

## ✨ Fonctionnalités

### Mode « Génération auto »
- 8 motifs : uni, rayures (H/V), dégradé, damier, pois, camouflage, tie-dye — ou **aléatoire**
- Palettes de couleurs générées automatiquement (harmonies complémentaires, analogues, triades…)
- Détails réalistes : col, boutons, poche, ourlets pour les shirts · ceinture, braguette,
  poches, bande latérale pour les pants · badge pour les t-shirts
- Texte personnalisé sur la poitrine
- **Génération en lot** : 1, 6, 12 ou 24 designs d'un coup
- Ombrage automatique des faces (côtés/dos plus sombres) pour un rendu volumique en jeu

### Mode « Depuis une image »
Dépose n'importe quelle image (logo, texture, dessin) et choisis le placement :
- **Remplir chaque face** — l'image couvre chaque zone du template
- **Étirer sur tout le template** — pour les designs déjà au format 585×559
- **Logo sur la poitrine** — couleur unie + ton logo centré (taille réglable)

### Export
- Téléchargement PNG individuel (transparence hors des zones du template ✔)
- **Tout télécharger en .zip** (généré dans le navigateur)
- Aperçu avatar approximatif + repères du template affichables

## 📤 Uploader sur Roblox

1. Va sur [create.roblox.com](https://create.roblox.com/dashboard/creations)
2. Section **Classic Clothing** (T-Shirts / Shirts / Pants)
3. Uploade le PNG généré, donne un nom, publie
4. 💰 Frais Roblox : **10 Robux** par Shirt/Pants publié · les T-Shirts sont gratuits
5. Chaque vêtement passe par la modération Roblox avant d'être visible

## 🗺️ Layout du template

Le layout 585×559 est codé dans `index.html` (`TORSO`, `limbCross`) : faces de 64 px par stud,
gouttières de 2 px, conformément au template officiel Roblox. Le torse est en haut au centre
(face avant en 231,74 · 128×128), les deux croix bras/jambes en bas.

> Les designs symétriques ne sont pas affectés par l'orientation gauche/droite des membres.
> Active « Afficher les repères » dans l'outil pour visualiser toutes les zones.
