# React-Movie-App 

Une application **React + Vite** qui consomme l’API de **The Movie Database (TMDB)** pour :
- afficher les films populaires,
- rechercher des films,
- gérer une liste de favoris (via un contexte React),
- naviguer entre Home et Favorites avec React Router.

---

## Fonctionnalités
- **Popular movies** : chargement de la liste des films populaires depuis TMDB.
- **Search** : recherche par titre.
- **Favorites** : ajout/suppression de favoris (gérés côté front via le contexte).
- **Navigation** : routes :
  - `/` → Home
  - `/favorites` → Favorites

---

##  Stack
- **React**
- **Vite**
- **React Router DOM**
- Fetch API (requêtes HTTP vers TMDB)

---

## Prérequis
- **Node.js** : recommandé **20.19+** (Vite récent le demande souvent)
- **npm**

Vérifier :

`node -v`
`npm -v`

## Configuration TMDB (obligatoire avant d’exécuter)

L’app a besoin d’une clé API TMDB.

1. Créer un compte sur TMDB : https://www.themoviedb.org/

2. Aller dans Paramètres (Settings) → API

3. Cliquer sur Generate / Créer une clé API

4. Remplir le formulaire : TMDB donnera une API Key

5. Dans le dossier `frontend`, créer un fichier **`.env`** et y mettre :
`VITE_TMDB_API_KEY=ta_cle_api` => remplacer ta_cle_api par la clé générée par l'API



## Installation & exécution

Depuis la racine du repo :

`cd frontend`
`npm install`
`npm run dev`

Ensuite ouvrir l’URL affichée par Vite (http://localhost:5173).


