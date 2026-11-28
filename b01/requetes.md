# Trois requêtes HTTP observées

Site étudié : https://suguline.com

| N° | Ressource (colonne « Nom ») | Méthode | URL complète | Code de statut | Type |
|---|---|---|---|---|---|
| 1 |theamazingworldofcap/ | GET | https://suguline.com/liste-des-boutiques/theamazingworldofcap/ | 200 | document |
| 2 | autoptimize/css/ | GET | https://suguline.com/wp-content/cache/autoptimize/css/autoptimize_single_2030176df39a8b78676e61a95e3589f2.css?ver=6.2.17 | 200 | stylesheet |
| 3 | carte-cadeau-Xbox-SUGULINE.webp | GET | https://suguline.com/wp-content/uploads/2025/07/Carte-cadeau-Xbox-SUGULINE.webp | 200 | image |

## Q1. Combien de requêtes au total la page a-t-elle déclenchées ?

La page a déclenché 363 requêtes au total. Cela s'explique parce qu'une page web charge plusieurs ressources : les images, les fichiers CSS, JavaScript, les polices et d'autres éléments nécessaires à son affichage.

## Q2. Avez-vous vu un code commençant par 3 ou par 4 ?

J'ai observé un code 302 pour la ressource Cropped-SUGULINE-Favicon-32x32.webp. Ce code indique une redirection temporaire : le navigateur est dirigé vers une autre adresse pour récupérer la ressource.

## Q3. Que désignent les éléments de cette adresse ?

localhost désigne mon ordinateur, sur lequel le serveur fonctionne.
3000 est le numéro du port utilisé par le serveur.
`/api/produits` est le chemin permettant d'accéder à l'API des produits.
`q=mil` est un paramètre qui permet de rechercher les produits contenant le mot « mil ».