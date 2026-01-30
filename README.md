# Faire village en Argonne

Ce projet est une carte interactive permettant de visualiser des points d'intérêt en Argonne.

## 🗺️ Utilisation
La carte principale est accessible via `index.html`. Elle affiche les points documentés dans le fichier `data.json`. En cliquant sur un point, vous accéderez à une page de détails contenant des images, des descriptions et des liens utiles.

## 🛠️ Administration (Ajouter des points)
Pour mon collègue (qui n'est pas très à l'aise avec l'informatique, pas de panique !), voici la marche à suivre pour ajouter de nouveaux lieux sur la carte :

1.  **Ouvrez la page d'administration** : Allez sur `admin.html`.
2.  **Choisissez l'emplacement** : Cliquez sur la carte à l'endroit précis où vous souhaitez placer le point. Les coordonnées (Latitude et Longitude) s'afficheront automatiquement.
3.  **Remplissez le formulaire** : Donnez un titre, une description, et si possible un lien vers une image ou un site web.
4.  **Générez le code** : Cliquez sur le bouton vert **"Générer l'entrée JSON"**.
5.  **Mettez à jour la carte** :
    *   Un texte bizarre (du JSON) va apparaître en bas de la page.
    *   Copiez ce texte.
    *   Ouvrez le fichier `data.json`.
    *   Collez ce texte à l'intérieur du crochet `[` et avant le dernier crochet `]`.
    *   **Attention** : Assurez-vous qu'il y a bien une virgule entre chaque bloc de données.

## 🚀 Publication sur GitHub
Une fois les fichiers modifiés dans votre dossier local :
1. Envoyez (Push) les changements sur votre dépôt GitHub.
2. Activez **GitHub Pages** dans les réglages (Settings > Pages) pour rendre le site accessible à tous.