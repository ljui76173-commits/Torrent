# 👕 Roblox Classic Clothing Maker

Un outil **100 % local** (une seule page HTML, aucun serveur, aucune donnée envoyée) pour créer
automatiquement des vêtements *classic* Roblox :

- **T-Shirt classic** → PNG 512×512
- **Shirt classic** → PNG 585×559 (template officiel)
- **Pants classic** → PNG 585×559 (template officiel)

## 🚀 Lancer l'outil

Ouvre simplement `index.html` dans ton navigateur (double-clic), c'est tout.

## ✨ Fonctionnalités

### Rendu « tissu réel »
Chaque vêtement passe par un moteur de rendu inspiré des best-sellers du catalogue :
trame textile pixel par pixel (toile / maille / sergé denim + délavage), éclairage
volumique par face, coutures, prints érodés façon sérigraphie usée, grain photo,
palettes désaturées relevées dans le catalogue — plus d'aplats vectoriels.

### Galerie persistante & collections 🏪
La galerie survit au rechargement (les recettes de génération sont sauvegardées et
rejouées), avec favoris ⭐, suppression à l'unité, et un **nom d'item prêt à coller**
dans le catalogue sur chaque carte (clic = copié). Le bouton **Collection** génère
6 ensembles déclinés d'un même style d'un coup.

### Ensembles assortis 🧥+👖
Un bouton génère le **shirt et le pants coordonnés** (même palette, styles appariés :
hoodie→jogging, emo→emo skinny, chemise→costume…) et l'aperçu avatar porte les deux.
C'est le format « matching set » qui marche le mieux sur le catalogue.

### Mode « Génération auto »
Des **vrais styles de vêtements**, dont les tendances :
- **Shirts** : t-shirt col rond, hoodie, veste varsity, maillot de sport, chemise, pull rayé,
  🖤 **Emo** (cœur brisé, manches rayées), ✨ **Y2K** (papillon, sparkles), 🌸 **Kawaii**,
  🎸 **Grunge** (flanelle usée), 🔥 **Streetwear** (gros print)
- **Pants** : jean, jogging, cargo, short (peau visible), costume,
  🖤 **Emo** (skinny + chaîne + ceinture cloutée), ✨ **Y2K** (flare + papillon brodé),
  🎸 **Grunge** (jean troué — la peau apparaît dans les déchirures), 🌸 **Kawaii**
- **T-Shirts** : badge, marinière, dégradé, sport, tie-dye, camo + Emo / Y2K / Kawaii / Grunge
- **Coupe au choix** : mixte, féminine (crop top + manches courtes) ou masculine
- Palettes thématiques par tendance + 18 palettes générales soignées, ou couleur au choix
- Texte personnalisé sur la poitrine (T-Shirt), génération en lot (jusqu'à 24)
- **Shadows réalistes** : ombrage des faces, bords assombris, plis de tissu, grain textile

### Mode « Depuis une image »
Dépose n'importe quelle image (logo, dessin, même une photo) :
- ✂️ **Suppression automatique du fond** (sensibilité réglable) + recadrage sur le motif
- Placements : **logo poitrine** (ombre portée), **logo devant + dos**,
  🎯 **placement libre** — glisse tes images directement sur l'aperçu (déplacement à la
  souris, taille, rotation, duplication, plusieurs stickers superposables, et le fond peut
  être un design généré en mode auto), **motif répété** (tissu imprimé, taille réglable),
  **image continue par partie du corps**, ou étirée sur tout le template
- Ombres réalistes optionnelles sur le vêtement

### Couverture garantie des épaules
Le tissu est peint sur toute la zone englobante de chaque croix du template (gouttières
comprises) : la position exacte des petites faces HAUT/BAS variant selon les versions du
template officiel, les couvrir large garantit qu'en jeu, le dessus des bras/jambes et les
dessous sont toujours texturés. Les pixels en trop ne sont jamais affichés par Roblox.

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
