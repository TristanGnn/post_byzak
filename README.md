# Post_byZak

Site de Post_byZak : articles, événements, photos et shop autour du vélo.

## Structure

```
frontend/              Site public (HTML statique)
  index.html           Accueil : derniers articles, futurs événements, photos, shop
  articles.html        Tous les articles, avec filtres par catégorie
  article.html         Page d'un article
  admin/               Back-office (CMS) pour Zak
    editeur.html       Écrire un article : infos, photo, texte, vidéo, aperçu
    mise-en-page.html  Choisir les articles de l'accueil, leur ordre et leur format
backend/               Schéma Supabase (tables, règles RLS) — à venir
app/                   Réservé
docs/maquettes/        Anciennes maquettes de référence
```

## Voir le site en local

Ouvrir `frontend/index.html` dans un navigateur. Pour les vidéos YouTube, passer par un serveur local (par exemple l'extension Live Server de VS Code).

## État

- Pages publiques et back-office : maquettes avec contenu d'exemple
- À faire : brancher Supabase (articles, auteurs, accueil), connexion de Zak, mise en ligne
