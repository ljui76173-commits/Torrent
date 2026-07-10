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
Des **vrais styles de vêtements**, pas juste des motifs :
- **Shirts** : t-shirt col rond, hoodie (cordons + poche kangourou + capuche), veste varsity,
  maillot de sport avec numéro, chemise (col + boutons), pull rayé
- **Pants** : jean (surpiqûres, poches, passants), jogging, cargo, short (jambes coupées,
  la peau apparaît), pantalon costume (pli de repassage)
- **T-Shirts** : badge, marinière, dégradé, sport avec numéro, tie-dye, camouflage
- 18 palettes de couleurs soignées (avec variation aléatoire) ou couleur au choix
- Motif du tissu configurable (rayures, damier, camo…) ou choisi par le style
- Texte personnalisé sur la poitrine (T-Shirt)
- **Génération en lot** : 1, 6, 12 ou 24 designs d'un coup
- **Shadows réalistes** : ombrage des faces, assombrissement des bords, plis de tissu,
  grain textile

### Mode « Depuis une image »
Dépose n'importe quelle image (logo, dessin, même une photo) :
- ✂️ **Suppression automatique du fond** (détection des couleurs de bord, sensibilité
  réglable) + recadrage automatique sur le motif
- Placements : **logo sur la poitrine** (ombre portée incluse), remplir chaque face,
  ou étirer sur tout le template
- Ombres réalistes optionnelles sur le vêtement

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
