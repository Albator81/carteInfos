# Faire village en Argonne

Ce projet est une carte interactive permettant de visualiser des points d'intérêt en Argonne.

## 🗺️ Utilisation
La carte principale est accessible via [ce lien](https://albator81.github.io/carteInfos/). Elle affiche les points documentés dans le fichier `data.json`. En cliquant sur un point, vous accéderez à une page de détails contenant des images, des descriptions et des liens utiles.

## 🛠️ Administration (Ajouter des points)

1.  **Ouvrez la page d'administration** : Allez sur [la page admin](https://albator81.github.io/carteInfos/admin).
2.  **Choisissez l'emplacement** : Cliquez sur la carte à l'endroit précis où vous souhaitez placer le point. Les coordonnées (Latitude et Longitude) s'afficheront automatiquement.
3.  **Remplissez le formulaire** : Donnez un titre, une description, et si possible un lien vers une image ou un site web.
4.  **Générez le code** : Cliquez sur le bouton vert **"Générer l'entrée JSON"**.
5.  **Mettez à jour la carte** :
    *   Appuyez sur le bouton **Copier le code JSON**
    *   Clique sur [ce lien pour ajouter](https://github.com/Albator81/carteInfos/edit/main/data.json).
    *   Collez ce texte sur une nouvelle ligne JUSTE après le crochet `[`.

- Une fois le texte collé au bonne endroit :

1. Appuyez sur le bouton **Commettre des changements...** (en anglais: **Commit changes...**)
2. Attendez un peu, et le point et la page vont être ajoutés et visibles sur le site.
