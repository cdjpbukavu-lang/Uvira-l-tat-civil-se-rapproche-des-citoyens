# CDJP Bukavu — Campagne mobile d'état civil à Uvira

Mini-site institutionnel éditorial, responsive et prêt pour GitHub Pages, accompagné des 9 photographies originales optimisées pour le web.

## Mise en ligne sur GitHub Pages

1. Créez un nouveau dépôt GitHub (par exemple `cdjp-etat-civil-uvira`) ou utilisez un dépôt dédié déjà existant.
2. Décompressez l'archive ZIP sur votre ordinateur.
3. Dans le dépôt GitHub, choisissez **Add file → Upload files** et chargez le fichier `index.html` ainsi que le dossier `images` (en respectant sa structure). Ajoutez éventuellement ce `README.md`.
4. Cliquez sur **Commit changes**.
5. Ouvrez **Settings → Pages**. Dans « Build and deployment », sélectionnez **Deploy from a branch**, choisissez la branche `main` et le dossier `/(root)` puis cliquez sur **Save**.
6. L'adresse publique sera généralement `https://NOM-UTILISATEUR.github.io/NOM-DU-DEPOT/` une fois la publication terminée.

Il n'est pas nécessaire de configurer un serveur, une base de données ni des extensions.

## Contenu

- `index.html` : article intégral et code CSS/JavaScript intégré (animations, navigation mobile, galerie zoom, bouton de partage, barre de progression).
- `images/` : les 9 images au format WebP, optimisées pour réduire la taille de chargement.
- `ARTICLE.md` : texte éditorial pour réemploi institutionnel.

## Personnaliser

- Modifier l'article : rechercher `id="initiative"` dans `index.html`.
- Modifier les récits : rechercher `id="histoires"`.
- Modifier les images : remplacer les fichiers WebP en conservant leurs noms, ou actualiser les chemins dans `index.html`.
- Ajouter le logo officiel : le monogramme typographique « CDJP » est provisoire ; remplacer l'élément `.brandmark` par une image officielle autorisée.
- Modifier couleurs et typographies : variables CSS dans `:root`.

## Avant la mise en ligne publique

Les photos présentent des personnes et des enfants, parfois des documents administratifs. Vérifiez l'autorisation de diffusion de ces images, particulièrement pour les mineurs, et assurez-vous que les informations personnelles figurant sur les documents ne sont pas lisibles. Des éléments d’un acte ont été discrètement floutés dans une photographie de remise, par précaution ; cela ne dispense pas d’une validation éditoriale et du consentement avant publication. Vérifiez également les formulations institutionnelles et les rôles de chaque organisation avant diffusion.

Ce site ne collecte aucune donnée personnelle ni formulaire. Les polices Google Fonts chargées depuis un service externe peuvent être remplacées par des polices locales ou système si nécessaire.

## Aperçus des liens sur les réseaux sociaux

Pour que WhatsApp, Facebook ou LinkedIn affichent l’image de couverture, renseignez la balise `og:image` dans `index.html` avec l’URL **absolue** de votre image après publication (par exemple `https://votre-compte.github.io/votre-depot/images/02-mobilisation-citoyenne.webp`).
