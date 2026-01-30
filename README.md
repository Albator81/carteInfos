# Faire village en Argonne

Ce projet est une carte interactive permettant de visualiser des points d'intérêt en Argonne.

## 🗺️ Utilisation
La carte principale est accessible via [ce lien](https://albator81.github.io/carteInfos/). Elle affiche les points documentés dans le fichier `data.json`. En cliquant sur un point, vous accéderez à une page de détails contenant des images, des descriptions et des liens utiles.

## 🛠️ Administration (Ajouter des points)
Pour mon collègue (qui n'est pas très à l'aise avec l'informatique, pas de panique !), voici la marche à suivre pour ajouter de nouveaux lieux sur la carte :

1.  **Ouvrez la page d'administration** : Allez sur [la page admin](https://albator81.github.io/carteInfos/admin).
2.  **Choisissez l'emplacement** : Cliquez sur la carte à l'endroit précis où vous souhaitez placer le point. Les coordonnées (Latitude et Longitude) s'afficheront automatiquement.
3.  **Remplissez le formulaire** : Donnez un titre, une description, et si possible un lien vers une image ou un site web.
4.  **Générez le code** : Cliquez sur le bouton vert **"Générer l'entrée JSON"**.
5.  **Mettez à jour la carte** :
    *   Un texte bizarre (du JSON) va apparaître en bas de la page.
    *   Copiez ce texte.
    *   Clique sur [ce lien pour ajouter](https://github.com/Albator81/carteInfos/edit/main/data.json).
    *   Collez ce texte à l'intérieur du crochet `{` et avant le dernier crochet `}`.

## 🚀 Publication sur GitHub
Une fois les fichiers modifiés dans votre dossier local :
1. Appuyez sur le bouton **Commettre des changements...**
2. Attendez un peu, et le point et la page vont être ajoutés et visibles sur le site
